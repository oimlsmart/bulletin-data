# CLAUDE.md

Guidance for Claude Code sessions working in `bulletin-data`.
Sibling repo of `relaton-data-oiml` under `~/src/relaton/`.

## What this repo is

A **data mirror**, not a software project. It holds:

- Every OIML Bulletin PDF published since 1960 (quarterly issues).
- A `ocr.md` text extraction alongside each PDF.
- Per-issue `README.md` placeholders for HTML-only editions (no PDF).

There is no Ruby, JavaScript, or any source code here. The pipeline that
populates this tree lives in the sibling repo
`~/src/relaton/relaton-data-oiml/backfill/` (see <<pipeline>>).

## Golden rule: never delete PDFs

The PDFs in this tree are **source data** — the original OIML Bulletin
artifacts, downloaded once from oiml.org. They are not regenerable from
any other file in this repo or anywhere else. Treat them as immutable
source.

- Never `rm` a PDF, even one that looks misnamed or duplicated.
- Never overwrite a PDF with a "normalized" version. Original filename and
  bytes are preserved verbatim from the download.
- If a PDF appears misplaced, ask the user — do not move or rename it.

See `~/src/oimlsmart/bulletin-data/README.adoc` for the full layout and
naming conventions.

## Layout

```
<year>/<issue>/
  *.pdf       # one or more original PDFs
  ocr.md      # GLM-OCR extraction (or Tesseract for 5 GLM-blocked issues)
```

Year = calendar year. Issue = `01`/`02`/`03`/`04` (quarterly, zero-padded).

Pre-1980 folders may contain two bulletins (early Bulletin was irregular).
HTML-only editions (2024/03 onward, partially) have only a `README.md`.

## File-naming drift (don't "fix" it)

PDF filenames reflect the URL OIML served at download time. The scheme
drifted across decades:

- pre-1980: `<year>-bulletin-<num>.pdf`
- 1980s–1990s: `oiml-bulletin-<month>-<year>.pdf`
- 2000s+: `oiml_bulletin_<month>_<year>.pdf`
- Oversize parts: `_part1.pdf` / `_part2.pdf`, or `_p1a.pdf` / `_p1b.pdf` /
  `_p1c.pdf` for the 3-way split.

Do **not** rename files to a uniform scheme. The original filename is part
of the provenance.

## Oversize PDFs and .gitignore

GitHub's per-file limit is 100 MB. PDFs that exceed this are split into
parts that fit; the original unsplit PDF is kept locally only and listed
in `.gitignore` so it is never pushed. The `.gitignore` may look empty at
times — that just means there are currently no oversize unsplit PDFs
sitting on disk. Don't "tidy" it.

`skipped_oversize_pdfs/` is a legacy directory kept for its `README.md`,
which documents the splitting procedure. It is empty of PDFs. Don't
remove it.

## Known OCR irregularities

Five issues were OCR'd via Tesseract because GLM's content filter rejected
them page-by-page. The `ocr.md` for these is lower quality than the rest
of the corpus:

- `2018/03`, `2018/04`, `2019/02`, `2023/01`, `2023/02`

If editing or validating text from these, expect more noise than
elsewhere.

[[pipeline]]
## The pipeline lives elsewhere

Every script that populates this tree is in
`~/src/relaton/relaton-data-oiml/backfill/`:

| Script | Purpose
| `populate_bulletin_data.rb`     | Downloads PDFs into `<year>/<issue>/`. Idempotent.
| `ocr_scanned_era_parallel.rb`   | GLM-OCR every issue lacking `ocr.md`, across N workers. All eras.
| `ocr_oversize.rb`               | Splits >50 MB PDFs into ≤12-page chunks before GLM-OCR.
| `tesseract_fallback.rb`         | Tesseract fallback for the 5 GLM-blocked issues above.

Run scripts from inside `relaton-data-oiml`, never from here. This repo
has no `Gemfile`, no `bin/`, no executable code.

## Git workflow

- Default branch: `main`.
- Commits are typically data-only ("data: ...", "feat: add ... PDFs + OCR",
  "fix: gitignore oversize PDFs").
- Large binary pushes are normal here — this is a 7 GB tree. Don't be
  alarmed by multi-hundred-MB commits when adding new issues.
- Never force-push to `main`. Never push tags.

## Remote URL leaked a token — rotate it

As of 2026-07-02, `.git/config` for this repo embeds a GitHub
`x-access-token:gho_...` URL in `origin`. That token is sensitive —
anyone reading the repo's `.git/config` (or a backup) gets push access.
Recommend the user rotate it and switch the remote to a clean
`https://github.com/oimlsmart/bulletin-data.git` URL (or use a
`credential.https://github.com.helper` instead).
