# skipped_oversize_pdfs

This directory previously held Bulletin PDFs that exceeded GLM-OCR's
50MB size limit. They've been split into 2 (or 3 for the 128MB
2024-01 PDF) parts and moved to their respective year/issue folders.

If new oversize PDFs appear, split them with:
```
pdftk large.pdf cat 1-N output year/issue/file_part1.pdf
pdftk large.pdf cat N+1-M output year/issue/file_part2.pdf
```

where N is roughly half the page count.
