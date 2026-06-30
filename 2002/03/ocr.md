![](page=0,bbox=[182, 219, 266, 304])

<div align="center">

# Editorial

</div>

Market surveillance

The OIML Certificate System now has over 900 certificates registered, but this alone is not sufficient to ensure free circulation of measuring instruments and worldwide acceptance of measurement results. The final goal of the OIML is the establishment of a worldwide global measurement system as described in the Birkeland Report, and calls for further developments:

- To develop confidence in the certificates and test reports,

- To establish a system for assessing the conformity of instruments to the certified type in order to develop confidence in individual instruments, and

- To establish a system for assessing the instruments in service and their use in order to develop confidence in measurement results.

The first issue is covered by the work on the MAA, which will facilitate type approvals. The second issue calls for a system of product certification which would facilitate initial verification. But in all cases these three issues need to establish principles and procedures for the follow-up to the systems, for supervision and surveillance.

A mutual acceptance agreement is based on initial evaluation of the confidence which may be granted to

issuing authorities, but also necessitates constant attention from each participant to the certificates issued in order to maintain the level of confidence and to avoid deviations in the implementation of the Recommendations. Mutual information and intercomparisons are important tools for this.

Conformity to type cannot be fully assessed by simple tests and necessitates random examinations on various specific features of the instruments, as well as a follow-up to the manufacturing processes. This issue is partially addressed by the work in the European Union on market surveillance. The OIML should start a more general reflection on the ways to ensure and survey conformity to type in production.

Assessment of instruments in service may be partially answered by formal reverification procedures, but more generally for this third issue, surveillance of the repairers owners and users of instruments is of major importance.

This issue of the Bulletin presents different contributions to these reflections: surveillance of instruments in service, intercomparisons and quality management, and gives details of a forthcoming conference on market surveillance.

CONSUMER PROTECTION

<div align="center">

# Surveillance policies on weighing and measuring instruments

</div>

GIUSEPPE ARDIMENTO

Weights and Measures Officer

Camera di Commercio Industria Artigianato

e Agricoltura di Napoli

EMILIO CLEMENTE

Chief Executive Weights and Measures Officer Camera di Commercio Industria Artigianato Agricoltura di Genova

## 1 Introduction

The surveillance policy operated by a Local Metrology Authority (LMA) is the means by which both consumer protection and the fairness of commercial transactions are ensured in the marketplace.

Generally, the surveillance policy provides for periodical inspection and/or random surveillance to be made on instruments in order to ascertain whether they maintain a steady level of performance within the required accuracy limits during a stated period fixed by law.

The choice of an appropriate weighing and measuring instrument inspection and surveillance policy is nowadays a major concern for LMAs because the new approach European Directive on Measuring Instruments (MID) [1] is oriented to conformity assessment by means of procedural modules that predominantly allow manufacturers having sound quality assurance systems to "self-certify" their own products.

Thus, since article 14 of the MID provides for market surveillance operated by EU Member States, the inspection of instruments put into use may be regarded as the only truly independent control in the lifetime of certain instruments [2].

However, in many jurisdictions the large number of devices subjected to legal control does not allow LMAs to efficiently operate in order to ensure fairness in the marketplace and to protect consumers. In these cases it

is necessary to entrust the task of periodical inspection to private organizations or laboratories, provided that the latter can guarantee an adequate quality management system for inspections as well as independence and competence in performing inspections, whilst allowing the LMAs to continue their task of carrying out an a posteriori sample control on inspected devices in order to monitor the overall performance of those organizations.

## 2 Main requirements for licensing private verifying organizations or laboratories

A solution which could be implemented in order to solve the problem of assessing the prerequisites of an organization seeking verification licensing is to apply the ISO/IEC 17025 General requirements for the competence of testing and calibration laboratories [3].

Indeed legal metrology legislations actually tend to transfer those principles into the national regulation framework, but they often do not provide for an adequate a posteriori surveillance; moreover, since the number of weighing and measuring devices used for legal purposes can range from hundreds up to several thousands in many jurisdictions, it is necessary to adopt statistical decision criteria [8] to ascertain whether licensed organizations or laboratories do assure adequate performance when inspecting and certifying instruments.

This paper deals with the attempt to conceive a statistical test method to assess the above quoted performances by means of drawing by the LMAs samples from licensee inspected instrument population and infer a decision based on a stated significance level (see [6] and [7]).

## 3 The French statistical decision test model

The French regulation Arrêté du 22 mars 1993 relatif au contrôle des instruments de pesage a fonctionnement non automatique, en service [4] (Decree of 22 March 1993 relating to the inspection of nonautomatic weighing instruments in service) could be of inspiration to design sound statistical decision tests.

In that regulation (articles 10 and 11) criteria on the significance level of statistical tests as well as the minimum licensee verified instrument population size are set out, namely:

- An a posteriori control which can be exerted on, say, an annual basis by means of statistical tests must have a significance level (see [5] and [6]) of 0.05 or less;

- Licensed laboratories or organizations must perform at least 500 inspections per year in a given LMA jurisdiction;

- The verifying license must be repealed if the a posteriori control reveals that the licensee improperly accepts or refuses instruments in a proportion greater than 5 %.

## 4 The probability model

In order to study the statistical significance level of the decision test to be performed, the binomial distribution can be used: in this instance, the population size has to be considered in respect of the sample size; thus, indicating with:

p the probability of finding an instrument properly accepted or refused;

q = 1-p the probability of finding an instrument improperly accepted or refused.

(Note: p and q are empirically defined as the proportion of properly and improperly accepted or refused instruments in the population subjected to investigation).

The probability of finding exactly r instruments properly accepted or refused in sample of n is:

$$
P (r) = \binom {n} {r} \square p ^ {r} \square q ^ {n - r}
$$

![](page=2,bbox=[104, 1663, 1002, 2430])

<div align="center">

Fig.1 The normal distribution and the confidence level $ \alpha $ along with its one way critical z-value

</div>

When large samples are involved in the investigation it becomes more convenient to use a normal distribution, since that is the limit to which the binomial distribution tends as n increases.

The approximation of the binomial distribution by means of the normal distribution can generally be considered as satisfactory where the two following constraints hold simultaneously:

$$
n \square p \geq 5 \quad a n d \quad n \square q \geq 5
$$

If the conditions set out in (2) hold then the normal approximation can be used, thus facilitating calculations. A normal distributed stochastic variable z with zero mean and unity standard deviation can be defined [5] as:

$$
z = (X - n \square p) / \sqrt {(n p q)}
$$

where X is the current number of weighing and measuring instruments properly accepted or refused. In equation (3) use has been made of the above quoted approximation because the population mean $ \mu $ and the standard deviation $ \sigma $ characterizing the normal distribution have been set to be equal as follows:

$$
\mu = \mathrm {n} \square \mathrm {p} \mathrm {a n d} \sigma = \sqrt {(\mathrm {n p q})}
$$

(see [5], Chapter 7).

## 5 The statistical decision test in detail

The statistical decision test is based on the analysis of the z variable as defined in equation (3).

The decision as to whether the licensee verifying performance can be deemed satisfactory shall be taken by minimizing the I type error ([5] and [6]), i.e. the probability of rejecting the hypothesis $ H_{0} $ ,where $ H_{0} $ denotes the fact that a licensee performs its work well, for example, properly accepting or refusing at least 95 % of the verified instrument population.

Usually for legal purposes the probability of a I Type error (denoted as $ \alpha $ ) is set to 0.05 as in the French regulation described in paragraph 2.

In Figure 1 a typical one-way decision test is shown: in such a type of statistical decision test the critical $ z $ -value $ ( z_{c} ) $ is $ z_{c}=-1.645 $ for the significance level set to $ \alpha=0.05 $ (see [5], Chapter 10 and [6]).

Moreover, in the case of poor licensee performance, further investigations are needed in order to evaluate the probability of a II Type error [7] associated with the sample based statistical decision.

An acceptable criterion to render the decision reliable with respect to the occurrence of II Type error could be the following:

- The probability (indicated as $ \beta $) of accepting $ H_{0} $ hypothesis (p = 0.95) when the actual p equals 0.90 must be less than 0.10.

An administrative provision of the LMA limiting or even withdrawing the private organizations or laboratories verifying license should always be based on the analysis of the occurrence of the II Type error in addition to the I Type error one [8].

## 6 Worked out examples of statistical evaluation of licensee performances

This section deals with the attempt to provide some examples in order to better explain the calculations that should be carried out for evaluating the performances of the licensed verifying laboratories and organizations.

## 6.1 Example No.1

A licensed laboratory notifies the LMA of a list of 1680 verified small capacity weighing instruments.

The LMA decides to inspect 150 weighing instruments and finds 142 conforming to the relevant metrological regulations from this sample: in symbols

$$
\text {P o p u l a t i o n}: \quad N = 1 6 8 0
$$

$$
\mathrm {N u m b e r o f c o n f o r m i n g} \quad X = 1 4 2 \mathrm {i n s t r u m e n t s}
$$

In order to assess the licensee performances,

$$
p = 0. 9 5
$$

$$
q = 1 - p = 0. 0 5
$$

and so the expected number of conforming instruments in a sample and the standard deviation are respectively

$$
\mu = n \square p = 1 4 2. 5
$$

$$
\sigma = \sqrt {\left(n \bar {p} q\right)} = 2. 6 7
$$

The z critical value for the test is

$$
Z _ {\mathrm {c}} = - 1. 6 4 5
$$

From the definition of the z variable in (3), the acceptance criteria can be written as

$$
[ (X - n \square p) / \sqrt {(n p q)} ] \geq z _ {\mathrm {c}}
$$

From equation (5) the acceptance criterion can be written as follows

$$
\begin{array}{l} X \geq n \square p + z _ {c} \square [ \sqrt {(n p q)} ] = \\ = n \square p - 1. 6 4 5 \square [ \sqrt {(n p q)} ] = \\ = X _ {\mathrm {L I M}} \\ \end{array}
$$

Since X = 142 and from (6) $ X_{\mathrm{LIM}}=138 $ , the laboratory passes the a posteriori control at a significance level of 0.05.

## 6.2 Example No.2

A servicing company is accredited to perform official inspections after a fuel dispenser repair.

In one year it submits to the LMA 1950 "self verification" reports. An a posteriori control of the LMA on a sample of 150 reveals that 131 dispensers can be deemed as conforming to the relevant regulations.

In symbols,

$$
N = 1 9 5 0
$$

$$
n = 1 5 0
$$

$$
X = 1 3 1
$$

Using the same symbols as in the example 6.1 above, we have

$$
\mu = n \square p = 1 4 2. 5
$$

$$
\sigma = \sqrt {(n p q)} = 2. 6 7
$$

$$
X _ {\mathrm {L I M}} = n \square p - 1. 6 4 5 \square (\mathrm {n p q}) = 1 4 2. 5 - 1. 6 4 5 \square 2. 6 7 = 1 3 8
$$

Since $ X<X_{\mathrm{LIM}} $ the acceptance criterion does not hold. But nothing can be said about the performance level delivered by the licensee because only I Type error has been investigated: i.e. only the probability of rejecting hypothesis $ H_{0} $ is below the significance level 0.05.

It should be necessary, in order to decide whether the company performance is poor, to investigate the II Type error by using the criterion set out in Paragraph 4:

- The probability (indicated as $ \beta $) of accepting $ H_{0} $ hypothesis (p = 0.95) when the actual p equals 0.90 must be less than 0.10.

That graphically corresponds to the situation depicted in Figure 2.

In order to reasonably state that the company performances are not satisfactory to the LMA granting the verifying license, the area $ \beta $ (the so-called consumer risk [5]) should be less than or equal to 0.10

Thus, in order to evaluate $ \beta $ let

$$
p = 0. 9 0
$$

$$
q = 1 - p = 0. 1 0
$$

The corresponding values for $ \mu $ and $ \sigma $ are

$$
\mu_ {\beta} = n \square p = 1 5 0 \square 0. 9 0 = 1 3 5
$$

$$
\sigma_ {\beta} = \sqrt {(n / p / q)} = 3. 6 7
$$

Thus

$$
z _ {\beta} = \left(X _ {\mathrm {L I M}} - \mu_ {\beta}\right) / \sigma_ {\beta} = (1 3 8 - 1 3 5) / 3. 6 7 = 0. 8 2
$$

$$
\beta = \mathrm {P r o b a b i l i t y} \left(z \geq z _ {\beta}\right) = 0. 2 1
$$

The criterion set out in paragraph 4 and above is not met; thus the sample should be enlarged to render the decision based on the sample test more reliable.

A further 50 dispensers are then randomly drawn from the population and inspected by the LMA. The results it achieves, considering the whole sample, are

$$
n = 2 0 0
$$

$$
X = 1 7 0
$$

$$
\mathrm {L e t}
$$

$$
p = 0. 9 5
$$

$$
q = 1 - p = 0. 0 5
$$

We then have

$$
\mu = n \square p = 2 0 0 \square 0. 9 5 = 1 9 0
$$

$$
\sigma = \sqrt {(\mathrm {n} \square \mathrm {p} \square)} = 3. 0 8
$$

$$
X _ {\mathrm {L I M}} = \mu - z _ {\mathrm {c}} \square \sigma = 1 9 0 - 1. 6 4 5 \square 3. 0 8 = 1 8 4
$$

Since $ X<X_{\mathrm{LIM}} $ the company does not pass the I Type error criterion. In order to establish whether the decision is well-founded that the company performances are not satisfactory, let us analyze the II Type error.

$$
\mathrm {L e t}
$$

$$
p = 0. 9 0
$$

$$
q = 1 - p = 0. 1 0
$$

![](page=4,bbox=[102, 1886, 1002, 2428])

<div align="center">

Fig. 2 $ \alpha $ -confidence level, $ \beta $ -confidence level and the probability density for good performance (p=0.95) and for poor performance (p=0.90)

</div>

We have

$$
\mu_ {\beta} = n \square p = 2 0 0 \square 0. 9 0 = 1 8 0
$$

$$
\sigma_ {\beta} = \sqrt {(\mathrm {n} \square \mathrm {p} \square)} = 4. 2 4
$$

Thus,

$$
z _ {\beta} = \left(X _ {\mathrm {L I M}} - \mu_ {\beta}\right) / \sigma_ {\beta} = (1 8 4 - 1 8 0) / 4. 2 4 = 0. 9 4
$$

$$
\beta = \mathrm {P r o b a b i l i t y} \left(z \geq z _ {\beta}\right) = 0. 1 7
$$

Also this time the II Type error criterion is not met: thus we need to further increase the sample size in order to achieve the required significance level. A further subsample of 50 dispensers is drawn from the population of licensee verified instruments.

The overall results obtained by the LMA are

$$
n = 2 5 0
$$

$$
X = 2 1 4
$$

$$
\mathrm {L e t}
$$

$$
p = 0. 9 5
$$

$$
q = 1 - p = 0. 0 5
$$

We have then

$$
\mu = n \square p = 2 5 0 \square 0. 9 5 = 2 3 7. 5
$$

$$
\sigma = \sqrt {(n \bar {p} \bar {q})} = 3. 4 5
$$

$$
X _ {\mathrm {L I M}} = \mu - z _ {\mathrm {c}} \square \sigma = 2 3 7. 5 - 1. 6 4 5 \square 3. 4 5 = 2 3 1
$$

Since $ X<X_{\mathrm{LIM}} $ the LMA confirms that the company does not pass the I Type error criterion. The analysis of the II Type error yields:

$$
\mathrm {L e t}
$$

$$
p = 0. 9 0
$$

$$
q = 1 - p = 0. 1 0
$$

We have

$$
\mu_ {\beta} = n \square p = 2 5 0 \square 0. 9 0 = 2 2 5
$$

$$
\sigma_ {\beta} = \sqrt {(n \square q)} = 4. 7 4
$$

Thus,

$$
z _ {\beta} = \left(X _ {\mathrm {L I M}} - \mu_ {\beta}\right) / \sigma_ {\beta} = (2 3 1 - 2 2 5) / 4. 7 4 = 1. 2 7
$$

$$
\beta = \mathrm {P r o b a b i l i t y} \left(z \geq z _ {\beta}\right) = 0. 1 0
$$

Based on the results obtained the LMA may reasonably conclude that the servicing performance of the company is not satisfactory and thus the quality assurance system on which the verifying license was granted must be reviewed; meanwhile the LMA will have to limit, suspend or even withdraw the license.

## 7 Acknowledgements

The authors wish to thank Mr Jean-François Magaña (BIML Director); they also extend their thanks to Mrs. Corinne Lagauterie (Sous-Direction de la Métrologie, France) for supplying useful information about Reference 4, Mr Constantine V. Cotsoradis (Kansas Department of Agriculture) who gave detailed information about the statistical testing program on the performance of licensed servicing companies operating in the state of Kansas, USA and, last but not least, Dr. Walter Bich (Istituto di Metrologia G. Colonnetti, Italy) as well as Prof. Giulio Barbato (Politecnico di Torino, Italy) for their courtesy in granting valuable hints and comments to this paper.

## References

[1] Directive of the European Parliament and of the Council on Measuring instruments (MID), Commission proposal 15/09/2000

[2] Michael Harvey, The Balance must swing towards inspection, The Trading Standards Review, October 1998

[3] ISO - IEC 17025: General requirements for the competence of testing and calibration laboratories

[4] Arrêté du 22 mars 1993 relatif au contrôle des instruments de pesage a fonctionnement non automatique, en service, J.O. de la République Française du 28 mars 1993

[5] Murray R. Spiegel, Statistics, Mc Graw-Hill

[6] ISO 2854: Statistical interpretation of data - Techniques of estimation and tests relating to means and variables

[7] ISO 3494: Statistical interpretation of data - Power tests relating to means and variances

[8] Nello Polese, Misure per la gestione, Collana di Ingegneria Economico - Gestionale, Edizioni Scientifiche Italiane

![](page=5,bbox=[544, 1521, 871, 1946])

GIUSEPPE ARDIMENTO Weights and Measures Officer

Camera di Commercio

Industria Artigianato

e Agricoltura di Napoli

![](page=5,bbox=[1031, 1526, 1359, 1946])

EMILIO CLEMENTE

Chief Executive Weights and Measures Officer

Camera di Commercio Industria Artigianato e Agricoltura di Genova

INTERCOMPARISONS

<div align="center">

# NAWI intercomparison carried out by the APLMF

</div>

IAN HOERLEIN

Former Head of Standardization

and Certification, NSC (Australia)

Report prepared for the APLMF

(Summarized by the BIML for publication)

<div align="center">

# Intercomparisons in the field of legal metrology

</div>

An intercomparison on non-automatic weighing instruments (NAWI) carried out by the Asia-Pacific Legal Metrology Forum (APLMF)

General introduction on intercomparisons in the field of legal metrology

One important element to facilitate international trade is the acceptance of measurement results since the price of goods and services is based on a number of quantitative and qualitative parameters, many of which are determined through measurements.

Several international bodies are concerned with this matter, including the Meter Convention (which has developed a mutual acceptance agreement on the equivalence of national measurement standards and measurement certificates based on a system of intercomparisons), ISO and the IEC (for example through the standardization of measurement methods) and the OIML (in so far as measuring instruments covered by OIML Recommendations are used in international trading operations). As a result of the role it has played, the OIML has been granted observer status by the WTO TBT Committee, within which several international organizations (ISO, IEC, OIML, etc.) cooperate closely.

Another of the OIML's responsibilities is to develop mutual acceptance of type approval certificates with a view to reducing the redundancy of national or regional legal metrology controls.

In order to reach these goals, the OIML Action Plan provides for the organization of intercomparisons (preferably at the regional level) concerning:

- testing standards and equipment, in order to prove their equivalence; and

measuring instruments, in order to prove that the participating legal metrology laboratories may implement OIML requirements in a uniform manner.

In addition, the BIML has the responsibility to publish the results of such intercomparisons in order to keep other countries and regions informed.

It is not practical, especially due to the large number of pages involved, to publish intercomparison reports in the OIML Bulletin in their entirety. Current policy is therefore to publish only a summary, the complete report being accessible on the OIML web site and/or the site of the Regional Legal Metrology Organization concerned.

## The APLMF intercomparison on NAWI

Below is a summary of the report published by the National Standards Commission (NSC) of Australia Pilot Secretariat for this APLMF intercomparison carried out between June 1996 and April 2000. The complete report, dated July 2000, is available for download on the OIML web site www.oiml.org. The summary has been compiled by the BIML and approved by the APLMF and the NSC.

## 1. Purpose of the intercomparison

The scope of the intercomparison of non-automatic weighing instrument testing is to provide a transparent basis for the comparability of pattern approval evaluation of weighing instruments carried out by legal metrology authorities in the Asia-Pacific region. It is expected that these results will make a significant contribution to mutual recognition agreements between participating members. Some members of WELMEC have also participated to provide a comparability with pattern evaluation testing in the Western European Region.

The OIML is responsible for providing the means for harmonization of legal metrology requirements for its Members. One such means is the OIML Certificate System whereby an OIML Member can (under certain

conditions) issue an OIML certificate and a test report for a particular measuring instrument and these can be accepted by other Members as a basis for their own pattern approval without further testing. This system forms the basis for mutual recognition agreements between Members. However acceptance of tests conducted by other laboratories is only likely if there is mutual confidence in the capabilities of laboratories. This intercomparison is aimed at fostering such confidence.

## 2. Participants

The following agreed to participate in the intercomparison: Australia, Canada, People's Republic of China, Germany, Indonesia, Japan, Republic of Korea Malaysia, New Zealand, Russia, Chinese Taipei, United Kingdom and the United States of America. Two State laboratories represented the USA.

## 3. Artefacts

Two non-automatic weighing instruments were circulated among the participants. These instruments were of a type intended for direct trading with the public and had tare and price computing facilities.

The instruments were of the same pattern:

<table border="1"><tr><td>Manufacturer:</td><td>CAS Corporation</td></tr><tr><td>Model:</td><td>CAS AP-1</td></tr><tr><td>Class:</td><td>3</td></tr><tr><td>Maximum capacity:</td><td>15kg</td></tr><tr><td>Verification scale interval(e):</td><td>0.005kg</td></tr><tr><td>Temperature range:</td><td>-10℃ to +40℃</td></tr><tr><td>Nominal voltage:</td><td>220V</td></tr></table>

## 4. Instructions for the intercomparison

Detailed instructions were provided to all participants in order to eliminate deviations in the examination and testing that might result in inconsistencies in the evaluation results. These instructions mainly covered:

- a visual inspection of the equipment when received, its initial set-up and calibration;

the examinations and test to be carried out (according to OIML R 76-1);

the preliminary tests;

the test report to be completed (according to OIMLR 76-2); and

the dispatch of the instrument to its next destination (including customs formalities).

5. Circulation schedule

Due to a number of factors, the final circulation schedules for the two instruments differed from the initial schedules. Table 1 gives these final schedules, and notes explain certain delays in the circulation, resulting from technical or administrative constraints.

## 6. Comments on the instruments

The two instruments used for the intercomparison were purchased by the Commission from the local agent for CAS Corporation. The instruments were common, class III non-automatic weighing instruments of electronic, load cell type intended for direct trading with the public and having tare and price computing facilities.

On receipt of the instruments preliminary tests were carried out to establish whether they were suitable for the intercomparison. The tests revealed that there were some areas of non-compliance with R 76 but this was not considered to be a problem. In fact it was considered that an instrument with some points of non-compliance would be beneficial for an intercomparison, particularly if the performance was near a specified limit of error.

In particular the Commission noted that for both instruments the temperature effect on no-load indication exceeded the error limit considerably and that the temperature effect on the weighing performance was close to the limits of the maximum permissible errors at some temperatures. The latter affected other weighing performance tests such as tare and damp-heat as well. In addition the instruments were affected by radiated electromagnetic fields at some frequencies. The Commission found that the instruments showed a tendency to creep during the load tests. One laboratory also commented on a tendency for Instrument A to drift which caused errors during decreasing load tests.

However the instruments showed good repeatability and as it turned out they maintained their performance over the whole period of the intercomparison despite breakdowns and other mishaps. Both instruments, when retested by the Commission, showed similar but not quite the same results as they did on the initial tests. Both instruments were damaged once during an electrostatic discharge test with the keyboard failing when a discharge was applied to the keyboard. Both were repaired by the local CAS agent in the country where the damage was done and both continued to perform after the repair. On its return to the Commis-

sion Instrument B was found not to perform at maximum capacity. A piece of plastic was removed from the bump stop for the load cell and this fixed the problem. Instrument A did not have the piece of plastic. Instrument A lost the liquid in the level indicator but the subsequent laboratory in the schedule performed the tilt test as if there was no level indicator. The level indicator was replaced on return to the Commission. Three test reports for the temperature effect on zero indication for Instrument B showed a dramatically different performance to the others. Perhaps the instrument was rezeroed between tests. Instrument A did show a shift in the temperature effect on span for $ - 1 0 \mathrm {^o C} $ for the last two tests.

## 7. Comments on the test results

As described above, the instruments were reliable and repeatable enough to provide meaningful results on all tests included in the intercomparison. There was a fair degree of agreement in the test results by all laboratories for both instruments. The performance of both instruments was very similar. As agreed, the results for the initial tests obtained by the Commission as the Pilot Laboratory are considered to be the reference results.

A large number of graphs and tables have been prepared for both instruments showing the results obtained by each laboratory and are included in the

<div align="center">

Table 1 Final circulation schedules for the two instruments

</div>

<table border="1"><tr><td></td><td>Country</td><td>Organization</td><td>Import date</td><td>Export date</td></tr><tr><td rowspan="9">Instrument A serial no.95111021</td><td>Australia</td><td>National Standards Commission</td><td></td><td>22.7.96</td></tr><tr><td>New Zealand</td><td>Trade Measurement Unit</td><td>5.8.96</td><td>7.10.96</td></tr><tr><td>USA</td><td>Ohio Department of Agriculture</td><td>11.10.96</td><td>23.12.96</td></tr><tr><td>Canada</td><td>Measurement Canada</td><td>3.1.97</td><td>?</td></tr><tr><td>USA</td><td>California Division of Measurement Standards</td><td>$?^{1}$</td><td>27.5.97</td></tr><tr><td>Japan</td><td>National Research Laboratory of Metrology</td><td>2.6.97</td><td>16.7.97</td></tr><tr><td>Australia</td><td>National Standards Commission</td><td>10.8.97</td><td>19.11.99</td></tr><tr><td>Canada</td><td>Measurement Canada</td><td>$14.12.99^{2}$</td><td>16.500</td></tr><tr><td>Australia</td><td>National Standards Commission</td><td>25.5.00</td><td></td></tr><tr><td rowspan="12">Instrument B serial no.95111033</td><td>Australia</td><td>National Standards Commission</td><td>—</td><td>22.7.96</td></tr><tr><td>China</td><td>China State Bureau of Technical Supervision</td><td>18.8.96</td><td>12.9.96</td></tr><tr><td>Germany</td><td>Physikalisch-Technische Bundesanstalt</td><td>18.10.96</td><td>2.1.97</td></tr><tr><td>United Kingdom</td><td>National Weights and Measures Laboratory</td><td>$6.1.97^{3}$</td><td>4.9.97</td></tr><tr><td>Australia</td><td>National Standards Commission</td><td>28.9.97</td><td>17.3.98</td></tr><tr><td>Russia</td><td>Russian Research Institute for Metrological Services</td><td>$22.5.98^{4}$</td><td>29.6.98</td></tr><tr><td>Korea</td><td>Korean National Institute of Technology and Quality</td><td>6.7.98</td><td>7.8.98</td></tr><tr><td>Chinese Taipei</td><td>National Bureau of Standards, Electronics Testing Center</td><td>12.8.98</td><td>23.10.98</td></tr><tr><td>Malaysia</td><td>SIRIM</td><td>$25.8.99^{5}$</td><td>1.12.99</td></tr><tr><td>Australia</td><td>National Standards Commission</td><td>3.12.99</td><td>13.1.00</td></tr><tr><td>Indonesia</td><td>Directorate Metrology</td><td>20.1.00</td><td>6.3.00</td></tr><tr><td>Australia</td><td>National standards Commission</td><td>12.4.00</td><td></td></tr></table>

1 Instrument failed and had to be repaired by a CAS agent.

$ ^{2} $ Canada requested to retest the instrument, as results from the first test were not available.

$ ^{3} $ Instrument had to be repaired which caused considerable delay. The instrument was returned to the Pilot Secretary for retesting.

4 Instrument held up in Russian Customs.

5 Instrument misplaced at the wrong address in Malaysia for nearly a year.

Annexes of the complete text of the report. These have been drawn up to show the difference in results between laboratories as well as the comparison with the maximum permissible errors specified. A comparison has also been made between the conclusions reached by each laboratory for the checklist.

As a measure of the degree of concurrence between laboratories, the maximum difference between the reference results and all other results are shown on the graphs and can be compared with the applicable maximum permissible error. However no matter how small this may be, if one result is just inside the maximum permissible errors and one is just outside, then the final decision of whether the instrument passes or fails will be different.

A comparison has also been made of the test facilities and standards used by each laboratory for the tests.

The complete text of the report contains detailed comments on each test for each instrument.

## 8. Comments on the checklist

The checklist forms the second major part of the OIMLR76-2 test report. It has to be completed to show whether or not the pattern complies with the functional requirements of OIMLR76. The report requires the laboratory to mark either the 'passed' or 'failed' columns against each item with an 'X' depending on the result of the examination. If the item is not applicable to that pattern both columns should be marked with a '/'.

Some of the laboratories:

Figures A.12 and B.12 of the Annexes to the complete text of the report compare laboratories and for each instrument show how the checklist was completed. Some laboratories also recorded remarks in the appropriate column.

made up their own copy of the checklist which was not identical with OIML R 76-2, e.g. it had different page numbers, items were on a different page and some items were missing;

- did not use the correct symbols to complete the columns for 'passed', 'failed' or 'not applicable';

did not enter symbols for all requirements.

For the purpose of accepting reports from other laboratories as part of the OIML Certificate System, it is important for the reports to be uniform in all respects.

When looking at the results specific to Instruments A and B, one may notice that although there was considerable agreement between laboratories, there were some disagreements.

Overall most laboratories failed the checklist in the Summary of Pattern Evaluation. However one laboratory (Instrument A) and two laboratories (Instrument B) recorded 'passed' while, in both cases, one laboratory recorded neither 'passed' nor 'failed'. The Pilot Laboratory did not repeat the checklist on the return of the instrument.

Figures A.12 and B.12 compare the results for each item given by each laboratory for Instruments A and B respectively. As the two instruments are the same, the charts for each instrument can also be compared. All participants can therefore see the differences and compare their results with other laboratories. The items for which significantly different results were obtained are listed and commented in the complete text of the report.

## 9. Test facilities and standards

Figures A.13 and B.13 of the annexes to the complete text of the report compare the test facilities and standards used by the laboratories in the intercomparison tests of Instruments A and B respectively.

## 10. Conclusions and recommendations

Despite a number of problems which developed during the intercomparison and the extra time required to complete the circuit of test laboratories, the intercomparison can be considered a success as it has provided meaningful results on the capability of the laboratories to test non-automatic weighing instruments to the requirements of OIML R 76.

Although the results show general agreement on the performance of the instruments, there are enough differences to require consideration by the APLMF to determine the conclusions and recommendations of the intercomparison. Some of the differences are explainable and can be overcome. However others are not. In particular the varying interpretations of the requirements in the checklist need some consideration.

The Pilot Laboratory, Australia tested the two instruments three times, i.e. at the beginning and end of the circuit as well as in between. The results are not exactly the same for each test but there is reasonable agreement for the tests for Instrument B showing that its performance remained stable. However the results for Instrument A indicate that its performance did change by a small amount but the results are still comparable.

DEFINITIONS IN PREPACKAGING

<div align="center">

# Consistent definitions in prepackaging and their relationship

</div>

## 1 Summary

DR. W. FRANKVOORT and J.M. ROMMERTS NMi, The Netherlands

In prepackaging, a prepackage is defined as the combination of a product and the packing material in which it is prepacked. The product is defined through the definition of "packing material" as everything that is intended to be left over after use, except for items naturally in the product. Use includes consumption or subjecting to a treatment.

The relationship between content and quantity is set by this definition: the content of a prepackage is the quantity of product in a prepackage. Content and quantity can be actual, nominal and average.

The use of the word "net" in net content and net quantity is superfluous: the quantity of product in a prepackage (or content of a prepackage) is by definition net of packing material and should not be used in the future.

## 2 Preface

The authors would like to thank:

The members of WELMEC Working Group 6 for their critical comments;

Mr. D. Hanekuyk of the European Commission for his suggestions of European Legislation.

- Definitions that derive from a basic definition are in orange text;

Hints while reading this document:

Basic definitions are marked with this symbol: $ \textcircled{x} $;

- Clarifications and remarks are in italics and lower case;

References to legislation or interpretation of legislation are in the page footers and are marked in the text with a figure (for instance: $ ^{1} $).

## 3 Introduction

A Dutch court of law decided that individual wrappings of sweets that are sold in a bag are considered to be product rather than packing material, because the difference between product and packing material is not clear in legislation.

Two international documents are currently being revised that cover the subject of prepackaging:

OIML Recommendation R 87 (Net quantity of product in prepackages);

European Council Directives 75/106/EEC and 76/211/EEC;

This study helps to achieve international harmonization on the subject of definitions in prepackaging to facilitate fair competition and to prevent barriers to trade.

This paper gives the definitions of "prepackage", "packing material" and "prepacked product" and their relationship in part 4 and gives guidance to terms that are related to the terms "quantity" and "contents" in chapter 5.

## 4 Definitions

This part gives the definitions of prepackage, packing material and prepacked product that are consistent and leave no room for misunderstanding.

## 4.1 Prepackage

A prepackage is defined as the combination of a product and the packing material in which it is prepacked $ ^{1} $

Prepackage is also referred to as "package" (USA) and "pre-package".

## 4.2 Packing material

Packing material is everything that is intended to be left over after use, except for items naturally in the product. Use includes consumption or subjecting to a treatment $ ^{1} $

Packing material is also referred to as "individual package $ ^{2} $ "package", "packaging", "packaging material(s)" and "packing materials".

Packing material is generally used to preserve, transport, inform about and as an aid while using the product it contains.

It proved to be easier to define "packing material" to differentiate between the product and packing material within a prepackage than to define "product", which would have had the same result.

Instead of leaving it up to the packer to identify the product on the label on which the indication of quantity applies, this definition does it for him, leaving no room for misunderstanding, thus facilitating fair competition.

The definition distinguishes between product and packing material with the phrase "intended to be left over after use". The US Weights and Measures Law differentiates with the phrase "items not considered to be part of the commodity" $ ^{3} $ which should give the same result.

Sometimes it is not clear what part of the prepackage "is intended to be left over after use". This is the case where certain items might or might not be used, for instance fruits in sweetened fruit-juice. Then the label of the prepackage might give guidance as to if and how to use the different items of the product (for instance by a recipe). Also several examples listed in annex III together with the application of this definition might give guidance.

Recycling, reusable (refillable) packing material or using the packing material by an end-user is still "intended to be left over after use".

When prepackages contain solid goods in a liquid medium, the definition of packing material differentiates between the product and the liquid medium when the liquids are not naturally in the product and intended to be left over after use. This is in accordance with the definition of "net weight" of the Unites States Weights and Measures Law $ ^{4} $

## 4.3 Product

By defining the terms "prepackage" and "packing material", there is no need to define the term "product" as it is everything apart from the packing material in a prepackage.

Product is also referred to as "commodity", "consumer commodity", "goods" and "contents".

Usually the product is the reason the prepackage is purchased.

## 4.4 Prepacked product

A product is prepacked when it is combined with packing material of whatever nature, whether such packing material encloses the product completely or only partially, without the purchaser being present and the quantity of product contained in the packing material cannot be altered without the packing material either being opened or undergoing a perceptible modification $ ^{5} $

Product cannot be prepacked when there is no packaging material. Desiccating and hygroscopic products can only be prepacked in packing material preventing the effects.

An example of a product that is enclosed only partially by the packing material is knitting yarn.

This definition also includes prepackages of which the quantity is determined individually after the dosing of the product.

## 5 Linguistic problems

The word "content" has two meanings, illustrated by the following two phrases:

1. "the content of this glass jar is marmalade", where it is used with the meaning of "product"

2. "the content of this glass jar is 200 ml", where it is used with the meaning of "amount"

An example of the first meaning can be found in Directive 75/106/EEC (Annex I, 1.1):

The actual volume of the contents shall not be less on average, than the nominal volume of the contents.

An example of the second meaning can be found in Directive 76/211/EEC (Annex I, 1.1):

The actual contents shall not be less, on average, than the nominal quantity

When using the terms "content" and "quantity" in relation to prepackage, product and package, it is easy to become confused, especially when interpreting different legislation.

This part sets the relationship between content and quantity, explains why the term "net" may be abolished and explains about different types of content and quantity.

A complete overview of terms is given in annex I.

## 5.1 Content and quantity

The relationship between content and quantity is set by these definitions:

The content of a prepackage is the quantity of product in a prepackage.

Content is also referred to as "contents" and "quantity of content".

The term "content" usually relates to the "product" as that is what a prepackage contains. Content of a product relates to ingredients.

The quantity of product in a prepackage is the amount of product in a prepackage.

The term "quantity" can be replaced with:

The "weight" of product in a prepackage is the amount of product in a prepackage expressed in kilogram;

The "volume" of product in a prepackage is the amount or product in a prepackage expressed in litre;

The "length" of product in a prepackage is the amount of product in a prepackage expressed in metre;

The "area" of product in a prepackage is the amount of product in a prepackage expressed in square metre;

The number of product in a prepackage is the amount of product in a prepackage expressed in numerical count.

The term "quantity" can apply to the product and the packing material of a prepackage. Usually the quantity of product is meant. When the quantity of packing material of a prepackage is meant, this should be formulated explicitly to prevent misunderstanding.

## 5.2 Actual, nominal, average

The terms "actual", "nominal", and "average" specify the terms "content" and "quantity".

The nominal quantity of product in the prepackage is the quantity indicated on the prepackage.

The symbol " $ Q_{n} $ " is used to designate "nominal quantity of product".

The nominal quantity is also referred to as "labeled quantity" and "declared quantity".

The term "nominal quantity of product in the prepackage" has the same meaning as "nominal content of the prepackage".

The nominal quantity of product is the quantity of product the prepackage is supposed to contain. It gives a packer a target to aim at.

The actual quantity of the product in the prepackage is the quantity of product, which the prepackage in fact contains.

The term "actual quantity of product in the prepackage" has the same meaning as "actual content of the prepackage".

The actual quantity is a characteristic of an individual prepackage.

The average quantity of product in prepackages is the arithmetic average actual quantity of product in prepackages.

The term "average quantity of product in the prepackage" has the same meaning as "average content of the prepackage".

The average quantity is a characteristic of any collection of prepackages, whether such a collection is termed population, batch, lot or sample.

The nominal, actual and average quantity relate differently to one another when used in a system of predetermined nominal quantity (the nominal quantity is set before dosing) and a system of individual measured quantity (the nominal quantity is set after dosing).

## 5.3 Net

Net content and net quantity are frequently used terms in prepackaging and in legislation. The use of the word "net" is superfluous: the quantity of product in a prepackage (or content of a prepackage) is by definition net of packing material.

This has been recognized in:

The European Council Directive 2000/13/EC relating to the labeling, presentation and advertising of foodstuffs, where "quantity" is regarded to be "net quantity $ ^{1} $ ;

The USA Weights and Measures Law, where "weight" is regarded to be "net weight" $ ^{2} $

As the terms "net quantity" and "net content" appear in legislation, these are the definitions:

The net content of a prepackage is the quantity of product in a prepackage.

The net quantity of product in a prepackage is the amount of product in a prepackage.

By these definitions, the term "net content of a prepackage" is equal to "content of a prepackage" and the term "net quantity of product in a prepackage" is equal to "quantity of product in a prepackage".

In future, the term "net" may be abolished as content and quantity of product are by definition "net" of packing material.

## 6 Recommendations

This document can be used as a "translator" between different legislation. The definitions below set the standard for future legislation. They leave no room for misunderstanding and facilitate fair competition.

A prepackage is defined as the combination of a product and the packing material in which it is prepacked.

- Packing material is everything that is meant to be left over after use, except for items naturally in the product. Use includes consumption or subjecting to a treatment.

Prepacked product: a product is prepacked when it is placed in packing material of whatever nature, whether such packing material encloses the product completely or only partially, without the purchaser being present and the quantity of product contained in the packing material cannot be altered without the packing material either being opened or undergoing a perceptible modification.

The content of a prepackage is the quantity of product in a prepackage.

The quantity of product in a prepackage is the amount of product in a prepackage.

- The nominal quantity of product in the prepackage is the quantity indicated on the prepackage. The symbol $ Q_{n} $ is used to designate "nominal quantity of product".

- The actual quantity of the product in the prepackage is the quantity of product, which the prepackage in fact contains.

- The average quantity of product in prepackages is the arithmetic average actual quantity of product in prepackages.

In future, the term "net" in relation to content and quantity should be abolished as content and quantity of product are by definition "net" of packing material.

<div align="center">

Annex I Overview of terms

</div>

<table border="1"><tr><td></td><td colspan="2">prepackage of in</td><td colspan="2">product of in</td><td colspan="2">packing material of in</td></tr><tr><td>content</td><td>content of a prepackage:quantity of product</td><td>content in a prepackage:this is the product</td><td>content of the product:content of the product relates to ingredients</td><td>content in the product:anything in the product relates to ingredients</td><td>content of the packing material:quantity of product</td><td>content in the packing material:this is the product</td></tr><tr><td>net content</td><td>net content of a prepackage:superfluous:content is by definition‘net’this relates to‘product’which is by definition‘net’of packing material</td><td>net content in a prepackage:superfluous:content is by definition‘net’this relates to‘product’which is by definition‘net’of packing material</td><td>net content of the product:content of the product relates to ingredients‘net’of what?</td><td>net content in the product:anything in the product relates to ingredients</td><td>net content of the packing material:superfluous:content is by definition‘net’of packing material</td><td>net content in the packing material:superfluous:content is by definition‘net’this relates to‘product’which is by definition‘net’of packing material</td></tr><tr><td>quantity</td><td>quantity of prepackage:quantity of product and packing material(gross quantity)</td><td>quantity in a prepackage:quantity of product(definition:prepackage is combination of a product and the packing material in which it is prepacked)</td><td>quantity of product:amount of product</td><td>quantity in product:quantity of identified ingredient(s) in the product(anything in the product relates to ingredients)</td><td>quantity of packing material:quantity of packaging materials</td><td>quantity in the packing material:quantity of product</td></tr><tr><td>net quantity</td><td>net quantity of prepackage:‘net’of what?</td><td>net quantity in a prepackage:quantity of product(which is by definition)net of the packing material</td><td>net quantity of product:amount of product,net of the packing material</td><td>net quantity in product:anything in the product relates to ingredients</td><td>net quantity of packing material:quantity of packaging materials,by definition net of the product</td><td>net quantity in packing material:quantity of product(which is by definition)net of the packing material</td></tr></table>

<div align="center">

Definitions in legislation and official guides to legislation

</div>

<div align="center">

Annex II

</div>

<table border="1"><tr><td></td><td>US Weights and Measures Law</td><td>US Packaging and labelling Regulation</td><td>OIML R87 draft 3 (net quantity of product...)</td><td>OIML R79 (labelling requirements...)</td><td>76/211/EEC (e-marking...)</td><td>2000/13/EC (foodstuff...)</td><td>This study</td></tr><tr><td>prepackage</td><td>The term package means any container or wrapping in which any consumer commodity is enclosed for use in the delivery or display of that commodity to retail purchasers.</td><td>The term &quot;package&quot;...means any commodity enclosed in a container or wrapped in any manner in advance of wholesale or retail sale, or determined in advance of wholesale or retail sale.
Consumer package and package of consumer commodity: a package that is customarily produced or distributed for sale through retail sales agencies or instrumentalities for consumption or use by individuals for the purposes of personal care or in the performance of services ordinarily rendered in or about the household or in connection with personal possessions.</td><td>Prepackage. - Combination of a product and the individual package in which it is prepacked.</td><td>Any commodity intended for sale that is enclosed in a container wrapped in any manner, and whose quantity has been determined.</td><td>A prepackage within the meaning of this Directive is the combination of a product and the individual package in which it is prepacked.</td><td></td><td>A prepackage is defined as the combination of a product and the packing material in which it is prepacked.</td></tr><tr><td>packing material</td><td></td><td></td><td>Individual package...(also called packaging or packaging material).-Everything meant to be left over after use of the product, except for items naturally in the product.Use includes consumption or subjecting to a treatment.
Package (also called packaging or packaging material(s)).-Materials generally used to preserve, transport, inform about and serve as an aid while using the product it contains.</td><td></td><td></td><td></td><td>Packing material is everything that is meant to be left over after use, except for items naturally in the product.Use includes consumption or subjecting to a treatment.</td></tr></table>

<table border="1"><tr><td></td><td>US Weights and Measures Law</td><td>US Packaging and labelling Regulation</td><td>OIML R87 draft 3(net quantity of product)</td><td>OIML R79(labeling requirements)</td><td>76/211/EEC(e-marking)</td><td>2000/13/EC(foods staff)</td><td>This study</td></tr><tr><td>product</td><td>The term consumer commodity or commodity means any article, product, or commodity of any kind or class which is environmentally produced or distributed for sale through retail sales agencies or institutionalities for consumption by individuals, or use by individuals for purposes of personal care or in the performance of services ordinarily maintained within the household, and which usually is consumed or expended in the course of such consumptions or use.</td><td></td><td></td><td></td><td></td><td></td><td>By defining the terms ‘packaged product’ and ‘packing material’, the term ‘product’ or other defined it is a revolving aspect from the packaging material in a packaged product.</td></tr><tr><td>prepacked product</td><td></td><td></td><td>Prepackaged product. A single item for presentation as such in the ultimate consumer, comprising of a product and the packaging unit which it was put before being offered for sale, whether such packaging encloses the product completely or only partially, but in any case in such a way that the contents cannot be altered without opening or changing the packaging.</td><td></td><td>A product is prepacked when it is placed on a package of whatever nature without the purchaser being present and the quantity of product contained in the package has a predetermined value and cannot be altered without the package either being opened or undergoing a perceptible modification.</td><td>pre-packaged foodstuff product shall mean any single item for presentation as such in the ultimate consumer, comprising of a foodstuff product and the packaging into which it was put before being offered for sale, whether such packaging encloses the foodstuff product completely or only partially, but in any case in such a way that the contents cannot be altered without opening or changing the packaging.</td><td>A product is prepacked when it is placed in a package of whatever nature, whether such packaging encloses the product completely or only partially, without the purchaser being present and the quantity of product contained in the package cannot be altered without the package either being opened or undergoing a perceptible modification.</td></tr><tr><td>content</td><td></td><td></td><td></td><td></td><td></td><td></td><td>The content of a prepackaged product is the quantity of product in a packaged product.</td></tr><tr><td>net content</td><td></td><td></td><td></td><td></td><td></td><td></td><td>The net content of a prepackaged product is the quantity of product in a packaged product.</td></tr></table>

<table border="1"><tr><td></td><td>US Weights and Measures Law</td><td>US Packaging and Labelling Regulation</td><td>OIML R87 draft 3(net quantity of product,...)</td><td>OIML R79(labeling requirements,...)</td><td>76/211/EEC(e-marking,...)</td><td>2000/13/EC(foodstuff,...)</td><td>This study</td></tr><tr><td>net quantity</td><td>This term “weight” is used in connection with any commodity or service means net weight. When a commodity is solid by drained weight, the term means net drained weight.</td><td></td><td>The amount of the identified product in the package exclosure of wrappers and any other material packed with such product.Note: The symbol Qq is used to describe this term in this Recommendation.</td><td>The quantity of the identified product in the package exclosure of wrappers and any other material packed with such product.This term relates to specifications on a package and does not account for the actual contents in an individual package. The procedure for determining whether a production lot meets regulations are provided in OIML R87 Net compliance on package.</td><td></td><td>Where the indication of a certain type of quantity of g. nominal quantity, minimum quantity, average quantity is required by community provisions or, where there are none, by national provisions, this quantity shall be regarded as the net quantity for the purposes of this Directive.</td><td>Net quantity in the quantity of product in a package.</td></tr><tr><td>nominal quantity</td><td></td><td>A declaration of net quantity of the commodity in the package, exclosure of wrappers and any other material packed with such commodity... shall appear on the principal display panel of a consumer package.</td><td>Nominal” Quantity (Qq) -The amount of the identified product in a package exclosure of the package and any other material packed with the product.“The” nominal” not quantity is declared on the label by the package.</td><td></td><td>The nominal quantity nominal weight or volume of the contents of a package is the weight of volume ordered on the package.Use the quantity of product which the package is deemed to contain.</td><td></td><td>The nominal quantity of product on the package is the quantity unrelated on the package.</td></tr><tr><td>actual content actual quantity</td><td></td><td></td><td>while the “actual” not quantity in the quantity of product in the package determined by measurement.</td><td></td><td>The actual contents of the package are the quantity weight or volume of product which it in that condition.andThe quantity of product contained in a package (all packaging quantity), known as the “actual contents”.</td><td></td><td>The actual quantity of product in the quantity of product which the package in fact contains.</td></tr><tr><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr></table>

<div align="center">

Annex III Examples of the application of the definition of 'packing material'

</div>

<table border="1"><tr><td>prepackage</td><td>general description</td><td>problem</td><td>product</td><td>application of the definition</td><td>remarks</td></tr><tr><td>fruits in sweetened juice</td><td>solid goods in a liquid medium</td><td>sometimes the liquid is also consumed</td><td>solid goods when the label gives guidance with(for example)a recipe how to use the liquid as an ingredient,the liquid medium is not‘meant to be left over after use’and therefore also‘product’</td><td>Packing material is everything that is meant to be left over after use,except for items naturally in the product.Use includes consumption or subjecting to a treatment</td><td></td></tr><tr><td>hair styling gel with air bubbles</td><td>viscous product with gas bubbles entrapped,for production or promotional reasons</td><td>some assume that the volume of the gel includes the air bubbles,because the bubbles are wanted by consumers(better selling product)</td><td>hair styling gel</td><td>bubbles(and other packing materials like tube or plastic jar)</td><td>when the solid items and the liquid are considered to be‘product’both their nominal quantities must be on the label to inform the consumer</td></tr><tr><td>ice glazed foodstuff</td><td>a frozen foodstuff is covered with a liquid that freezes to prevent the loss of water of the product</td><td>some assume that the glazing is part of the product as compensation for the loss of weight because of the freezing of the product</td><td>foodstuff</td><td>ice glaze(and other packing materials),even though the freezing of product usually causes the product to loose weight</td><td>also applies to paint and glue measuring problems have lead to a different application of the definition</td></tr><tr><td>lollypops</td><td>product with an item added to enable or promote the use of the product</td><td>some assume that the weight of a‘lollypop’also includes the stick,because without the stick a lollypop is a sweet</td><td>sweet</td><td>stick(and other packing materials like wrappings and a bag)</td><td>also applicable on non-foods measuring problems has lead to a different application of the definition</td></tr><tr><td>ice cream on a stick</td><td>product with an item added to enable or promote the use of the product</td><td>some assume that the weight also includes the weight of the stick</td><td>ice cream</td><td>stick(and other packing materials like paper or plastic packing material)</td><td>it also applies for sticks with a question and answer on them</td></tr><tr><td>ice cream with a spoon</td><td>product with an item added to enable or promote the use of the product</td><td>some assume that the weight also includes the weight of the spoon</td><td>ice cream</td><td>spoon(and other packing materials like plastic storage bin)</td><td></td></tr><tr><td>chocolate egg with a toy inside</td><td>product with an item added to enable or promote the use of the product</td><td>some assume that the weight also includes the weight of the toy</td><td>chocolate egg</td><td>toy(and other packing materials like kitchen foil)</td><td></td></tr><tr><td>paint with a stirring stick</td><td>product with an item added to enable or promote the use of the product</td><td>some assume that the weight also includes the weight of the stirring stick</td><td>paint</td><td>stirring stick(and other packing materials like can)</td><td></td></tr><tr><td>liquor with a pear in the bottle</td><td>liquid product with a solid ingredient added that contributes to taste or for promotional reasons</td><td>some assume that the volume also includes the volume of the pear because it is visible and it contributes to the taste of the liquor</td><td>liquor</td><td>pear(and other packing materials like glass bottle)</td><td></td></tr></table>

<table border="1"><tr><td>prepackage</td><td>general description</td><td>problem</td><td>product</td><td>application of the definition</td><td>remarks</td></tr><tr><td>liquor with a caterpillar in the bottle</td><td>liquid product with a solid ingredient added that contributes to taste or for promotional reasons</td><td>some assume that the volume also includes the volume of the pear because it is visible and it contributes to the taste of the liquor</td><td>liquor</td><td>Packing material is everything that is meant to be left over after use, except for items naturally in the product. Use includes consumption or subjecting to a treatment</td><td></td></tr><tr><td>liquor with raisins</td><td>liquid product with a solid ingredient added that contributes to taste</td><td>the raisons are eaten</td><td>liquor with raisins</td><td>other packing materials (usually a glass jar)</td><td></td></tr><tr><td>residue in wine</td><td>liquid with natural residue</td><td>some assume that the residue in wine is not part of the product because it is not consumed</td><td>wine and residue</td><td>other packing materials (like glass bottles or plastic cans), the residue is ‘naturally in the product’</td><td></td></tr><tr><td>residue in beer</td><td>liquid with added residue</td><td>yeast or barm is added during production to undergo secondary fermentation in the bottle</td><td>beer</td><td>residue (and other packing materials like glass bottle or can)</td><td></td></tr><tr><td></td><td></td><td>some assume that the volume also includes the volume of the yeast or barm because it is essential for the quality of the product</td><td></td><td></td><td></td></tr><tr><td>bones in poultry</td><td>part of a natural product not meant to be used</td><td>some assume that the weight of the poultry does not include the bones, because the are not consumed</td><td>poultry and bones</td><td>the bones are ‘naturally in the product’</td><td></td></tr><tr><td>fish bones</td><td>part of a natural product not meant to be used</td><td>some assume that the weight of the fish does not include the fish bones, because the are not consumed</td><td>fish and bones</td><td>the fish bones are ‘naturally in the product’</td><td></td></tr><tr><td>pips in fruits</td><td>part of a natural product not meant to be used</td><td>some assume that the weight of the fruit does not include the pips or skin, rind or peel, because the are not consumed</td><td>fruits and pips, skin, rind or peel</td><td>the pips, skin, rind or peel are ‘naturally in the product’</td><td></td></tr><tr><td>wrappings of sweets</td><td>small individually wrapped products together packed</td><td>some assume that the weight of the individual wrappings are part of the products, because the products would not be sellable if the individual wrappings were not there</td><td>sweets</td><td>individual wrappings (and other packing materials like plastic bag)</td><td></td></tr><tr><td>carbonated soft drinks and beer</td><td>liquids with carbon dioxide dissolved</td><td>the carbon dioxide is dissolved under pressure and exists in the brim space of the bottle or can</td><td>liquid with carbon dioxide</td><td>carbon dioxide in brim space (and other packing materials like glass bottle or tin can)</td><td>this suggests that (in general) the quantity of product should be determined under conditions a consumer uses the product (20 °C and 1 bar)</td></tr><tr><td>coffee powder under vacuum</td><td>product under vacuum</td><td>the product is kept fresh because it can not react with the oxygen in the air inside the packing material, the prepackage gets heavier when weighed with the packing material opened</td><td>coffee</td><td>opened packing material</td><td>measuring problems has lead to a different application of the definition</td></tr></table>

<table border="1"><tr><td>prepackage</td><td>general description</td><td>problem</td><td>product</td><td>application of the definition</td><td>remarks</td></tr><tr><td></td><td></td><td></td><td></td><td>Packing material is everything that is meant to be left over after use, except for items naturally in the product. Use includes consumption or subjecting to a treatment</td><td></td></tr><tr><td>coffee powder under pressurized gas</td><td>product in pressurized gas</td><td>the product is kept fresh because it can not react with oxygen in the air inside the packing material</td><td>coffee</td><td>opened packing material</td><td></td></tr><tr><td>coffee</td><td>product is left over after use</td><td>this facilitates unfair competition with packers who pack coffee in a vacuum</td><td></td><td></td><td></td></tr><tr><td>paint</td><td>product is left over after use</td><td>the drinkable coffee is obtained by pouring hot water on the coffee powder, wet coffee powder is left over after use</td><td>coffee powder</td><td>pouring the hot water is considered subjecting to a treatment</td><td></td></tr><tr><td>mozzarella cheese</td><td>product is left over after use</td><td>the paint is put on, thus being left over after use</td><td>paint</td><td>to paint is subjecting to a treatment</td><td></td></tr><tr><td>meat</td><td>product dries out</td><td>the cheese desiccates (usually water) during storage where the liquid does not evaporate from the prepackage</td><td>cheese</td><td>the liquid is naturally in the product and that therefore the liquid is part of the product, even though not used</td><td>the quantity of product of hygroscopic products or desiccating products, should be determined with a standard percentage of moist</td></tr><tr><td>soap</td><td>product dries out</td><td>the meat desiccates (usually water) during storage sometimes this is compensated for by adding more water before packing it</td><td>meat</td><td>the liquid is naturally in the product and that therefore the liquid is part of the product, even though not used</td><td>measuring problems have lead to a different application of the definition in the case of desiccating of hygroscopic product the quantity of product is altered without the packing material being opened or undergoing a perceptible modification, for this reason sometimes such product can not be prepacked without proper packing material</td></tr><tr><td>cat litter</td><td>hygroscopic product</td><td>the product gains weight because of its hygroscopic characteristics</td><td>cat litter</td><td>other packing materials (like plastic bag)</td><td></td></tr><tr><td>waxed cheese</td><td>eatable packing material</td><td>the wax is eatable</td><td>cheese</td><td>wax is meant to be left over after use (and other packing materials)</td><td>measuring problems has lead to a different application of the definition</td></tr><tr><td>sausage (with eatable skin)</td><td>eatable packing material</td><td>the skin is eatable</td><td>sausage and skin</td><td>the skin is not meant to be left over after use</td><td></td></tr></table>

R111

<div align="center">

# Data registration and quality management on examination of high accuracy class weights

</div>

ROBERT MATZINGER, Maro-Elektronik, Germany DETLEF SCHEIDT, Verification Authority of Rhineland-Palatinate, Germany

The Verification Authority of Rhineland-Palatinate (located in Bad Kreuznach, Germany) owns an air-conditioned weighing laboratory equipped with seven comparator weighing machines, in which the examination (calibration or verification) of weights of accuracy classes $ F_{1} $ and $ E_{2} $ takes place using the substitution method in accordance with OIML Recommendation R 111.

In the laboratory the following weights are examined:

- Standard weights used by the Verification Authority for the verification of scales,

![](page=22,bbox=[102, 1749, 1008, 2423])

Micro scale with 6 g maximum for the determination of weights of accuracy class $ E_{2} $

- Weights used by the chemical and pharmaceutical industry, and

- Weights used in the field of quality assurance.

To establish traceability to national standards and depending on the field of application, corresponding calibration or verification certificates are issued.

Up to the beginning of 1997, weighing results were determined manually. Measurement deviations of weights were found by comparison to corresponding nominal weights and the measured values obtained during the weighing cycle (standard weight - test weight standard weight) were transcribed onto forms. The necessary calculations of the measurement deviations and measurement uncertainties were performed afterwards with the aid of the handwritten records, and then transcribed onto the corresponding certificates. However, the number of certificates to be issued increased continuously and so it became necessary to minimize the time spent on recording and calculating the data, and to eliminate possible transfer errors by automating the whole process.

With the company Maro-Elektronik a partner was found that had the ability to write a program for transferring weighing results data onto a computer.

So the calculation of measurement deviations and uncertainties dependent on the standard weights used in their corresponding accuracy class had to be performed based on automatically entered data of the values measured. Simultaneously, the certificates to be issued had to be produced by the computer.

The program was especially tailored to the requirements of the Verification Authority of Rhineland-Palatinate and has successfully been used for testing weights and drawing up certificates since March 1997.

In the meantime, with the professional support of a reputed weight manufacturer, Häfner Gewichte GmbH, Maro-Elektronik had extensively revised their software and now offers a complete hardware and software package called Scales-net32, which is designed for legal verification authority laboratories as well as for accredited calibration laboratories and weight manufacturers.

The package consists of several components: the basic version consists of a comparator weighing machine, a terminal, a climatic station, a PC plug-incard and the PC software. The system can be expanded at any time.

This configuration is able to manage up to four climatic stations or data loggers and display on a monitor the ambient climatic data of all the climatic stations that are connected, as well as to store the data for documentation. For example, the first three inputs of a connected data logger having eight inputs can be used for room temperature, ambient air pressure and

air humidity, so that the remaining five inputs are available for the temperature sensors, which are incorporated in the comparators or scales. Defining which channel of the data logger is connected to which temperature sensor of a comparator or scale is achieved by adjusting the PC software. In this way, during the comparison the temperature in the weighing room can be registered. The climatic station continuously displays the room temperature on a four-digit display and therefore continuously indicates the actual values. If the temperature parameter that is set is exceeded by drift, this is signaled by a flashing LED display. At present, the system is able to manage 28 scale controllers and four climatic stations.

It is possible to connect to the system automatic and non-automatic working scales and comparator weighing machines with load changing equipment of various manufacturers (as well as those which are to be operated manually). The only necessity is to have a defined connection to the particular scale.

For the operation of the PC software, a Pentium 166 MHz or higher with Windows 95/98/NT is necessary.

The software provides all the relevant data that is required by the units (for example the climatic station and the comparator weighing machine with the scale). Also, the connections for the data import and export are designated in accordance with ASCII.

The comparator weighing machine consists of a micro-processor controlled input and output unit which enables the user to connect to the scale and PC software, and the user is guided in a straightforward way by a menu on the scale controller.

At the beginning of a weight comparison the user is asked to enter the required basic data, such as:

- Inspector,

- Scale registration number,

- Customer identification number,

- Order number,

- Serial number of the test unit set of weights,

- Nominal value,

- Accuracy class of the unit under test,

- Characteristic "point" or "star" for double weights,

- Shape of weights (for example: polygonal disk or cylindrical weight),

- Density or volume of the test unit, and

- Set of standards used.

After this data has been entered, the scale is tested to ascertain:

a) If it is suited to this nominal value or class, and

b) If the preset adjustments and fixed calibration time limits are not exceeded, and

c) If the standard weights used are qualified for their designation and if their recalibration time limits are not exceeded.

![](page=23,bbox=[972, 284, 1879, 921])

Micro scale with 6 g maximum and scale controller

This ensures that on a scale which, for example, is qualified for accuracy class $ E_{2} $ an examination of an $ E_{1} $ weight cannot be carried out - which consequently guarantees that on a scale with an expired calibration period, a weighing process cannot be performed.

It also means that in this enhanced examination program, the test equipment is also monitored in addition to the computation of the measuring results, in order to better ensure quality assurance. If the calibration and adjustment of the scale or the calibration of the sets of standards used is performed using Scalesnet32, a statement relative to the quality progress of the scale or the standards can be made. If the scale or the data set is blocked, the user will be informed by the scale-controller. The release of the scale will be obtained by a new calibration or adjustment.

The user is asked to place the test weight on the scale pan and to confirm the selected type of weighing cycle on the comparator weighing machine: "Standard test unit - standard" or "standard - test unit - test unit standard". After the scale has reached its position or after a certain lapse of time (for time-controlled weighing) the weighing data is automatically entered into the comparator weighing machine. On each weighing, the parameters detected (room temperature, air pressure, air humidity) are combined with the weighing data and the customer data.

After the predefined number of weighing cycles (depending on the accuracy class of the test unit) have been performed and the weighing process has been

![](page=24,bbox=[101, 284, 1009, 963])

Automatic comparator weighing machine for the determination of weights up to 50 kg of accuracy class $ E_{2} $ with scale controller

concluded, the data package obtained is transmitted to the PC and evaluated. It can then be printed out in the form of a verification, calibration or test certificate.

The entire method and evaluation are based on current OIML Recommendations (notably R 111) and the weighing data is stored in a database, which remains accessible for the purposes of checking back up on the history of a weight or set of weights.

The Verification Authority of Rhineland-Palatinate took delivery of new hardware at the end of June 2000 and has upgraded to a more recent version of Scalesnet32. The built-in test monitoring program can now be integrated into the quality management system of the Verification Authority because of the new user-friendly hardware and the extended software package, in addition to the automated evaluation of the measuring results and drawing up of the certificates.

Robert Matzinger

Maro-Elektronik

Breslauer Straße 4

D-55559 Bretzenheim

Germany

Detlef Scheidt Verification Authority of Rhineland-Palatinate Bad Kreuznach Germany

<div align="center">

# Assessment of OIML Activities

</div>

2001

## Contents

1 OIML Member States and Corresponding Members

2 New and revised OIML Recommendations, Documents and other Publications issued

3 OIML Technical Committees and Subcommittees: Meetings and degree of participation of OIML Members

4 Liaisons with other international and regional bodies

5 Degree of implementation of OIML Recommendations by OIML Members

6 Categories of measuring instruments covered by the OIML Certificate System

7 Cumulative number of registered OIML certificates (as at the end of 2001)

8 Degree of acceptance of OIML certificates by OIML Members

9 Distribution of the OIML Bulletin and revenue from sales of OIML Publications

10 Connections to and development of the OIML Internet site

11 Activities in support of development

<div align="center">

# Assessment of OIML Activities 2001

</div>

## 1 OIML Member States and Corresponding Members

<table border="1"><tr><td>Member States:</td><td>58</td><td>(+1)</td><td>Albania</td></tr><tr><td>Corresponding Members:</td><td>53</td><td>(+2)</td><td>Comores,Gabon,Uzbekistan(Albania became a Member State)</td></tr><tr><td>Total:</td><td>111</td><td>(+3)</td><td></td></tr></table>

## 2 New OIML Recommendations and Documents issued

<table border="1"><tr><td>New Recommendations issued:</td><td>3</td><td>R130,R131,R132</td></tr><tr><td>New Document issued:</td><td>1</td><td>D27</td></tr></table>

<table border="1"><tr><td></td><td>1998</td><td>1999</td><td>2000</td><td>2001</td></tr><tr><td>Total number of Recommendations:</td><td>108</td><td>108</td><td>111</td><td>114</td></tr><tr><td>Total number of Documents:</td><td>25</td><td>26</td><td>26</td><td>27</td></tr><tr><td>Total number of other Vocabularies:</td><td>3</td><td>3</td><td>3</td><td>3</td></tr><tr><td>Total number of other Publications:</td><td>17</td><td>17</td><td>17</td><td>17</td></tr></table>

## 3 OIML Technical Committees and Subcommittees: Meetings and degree of participation of OIML Members

<table border="1"><tr><td>TC 8/SC 5</td><td>9 October 2001</td><td>Brussels</td><td>11</td><td>P-members present out of 24</td></tr><tr><td>TC 8/SC 7</td><td>5-9 March 2001</td><td>Brussels</td><td>10</td><td>P-members present out of 19</td></tr><tr><td>TC 9/SC 2</td><td>7-9 November 2001</td><td>Teddington</td><td>12</td><td>P-members present out of 23</td></tr><tr><td>TC 11</td><td>16-17 January 2001</td><td>Berlin</td><td>8</td><td>P-members present out of 18</td></tr><tr><td>TC 17/SC 1</td><td>22 June 2001</td><td>Berlin</td><td>6</td><td>P-members present out of 14</td></tr></table>

## 4 Liaisons with other international and regional bodies

BIML representatives participated in the following meetings in 2001:

<table border="1"><tr><td>WTO TBT Committee</td><td>23 January &amp; 8-9 October</td><td>Geneva</td><td>Informal Meeting and Committee Meeting</td></tr><tr><td>CIPM - ILAC - CIML - APMP</td><td>21 February</td><td>Paris</td><td>Joint Meeting</td></tr><tr><td>SADCMEL</td><td>26 April</td><td>Maseru</td><td>Committee Meeting</td></tr><tr><td>JCGM</td><td>9-10 May &amp; 28-29 November</td><td>Sèvres</td><td>WG2 Meetings</td></tr><tr><td>WELMEC</td><td>24-25 May</td><td>Dublin</td><td>Committee Meeting</td></tr><tr><td>European Commission</td><td>7 June</td><td>Brussels</td><td>Meeting on the MID</td></tr><tr><td>SECI</td><td>11-12 June</td><td>Istanbul</td><td>Road Transport Committee Meeting</td></tr><tr><td>EMLMF</td><td>28-29 June</td><td>Poitiers</td><td>3rd Forum Meeting</td></tr><tr><td>UN/ECE</td><td>29-31 October</td><td>Geneva</td><td>Working Party Meeting</td></tr><tr><td>APLMF</td><td>13-15 November</td><td>Auckland</td><td>Committee Meeting</td></tr><tr><td>EA</td><td>21-22 November</td><td>Budapest</td><td>General Assembly</td></tr><tr><td>ISO CASCO</td><td>29-30 November</td><td>Geneva</td><td>Annual Meeting</td></tr><tr><td>SIM</td><td>13-14 December</td><td>Miami</td><td>Annual Meeting</td></tr></table>

In addition, the CIML President, Vice-Presidents, Development Council Chairperson and certain CIML Members represented the OIML at meetings of:

$$
A P L M F - C O O M E T - E M L M F - E U R O M E T - I S O - S A D C M E L - W E L M E C
$$

Concerning various technical activities of ISO, IEC, CEN, CENELEC and the European Commission, OIML experts participated in meetings and/or reports were given for the following fields:

Water meters

Draft European Directive on Measuring Instruments (MID); WELMEC WG 8

Acoustic measurements

Electromagnetic interference

## 5 Degree of implementation of OIML Recommendations by OIML Members

An inquiry on the implementation of OIML Recommendations was made in 2000. In comparison with the previous inquiries made in 1992 and in 1996, the significant increase in the number of countries implementing individual Recommendations and in the degree of implementation ensured is represented in the histogram on the following page. Based on the inquiry, on additional information and on corrections received from Member States in 2001, the highest performing OIML Recommendations in 2001 were as in the table below:

<table border="1"><tr><td>R76</td><td>Nonautomatic weighing instruments</td><td>Implemented in 39 countries</td></tr><tr><td>R35</td><td>Material measures of length for general use</td><td>Implemented in 33 countries</td></tr><tr><td>R111</td><td>Weights of classes $ E_{1},E_{2},F_{1},F_{2},M_{1},M_{2},M_{3} $</td><td>Implemented in 33 countries</td></tr><tr><td>R50</td><td>Continuous totalizing automatic weighing instruments</td><td>Implemented in 29 countries</td></tr><tr><td>R31</td><td>Diaphragm gas meters</td><td>Implemented in 29 countries</td></tr><tr><td>R117</td><td>Measuring systems for liquids other than water</td><td>Implemented in 29 countries</td></tr><tr><td>R51</td><td>Automatic catchweighing instruments</td><td>Implemented in 28 countries</td></tr></table>

![](page=28,bbox=[227, 371, 1774, 1227])

Number of Member States implementing OIML Recommendations

Histogram showing the degree of implementation of OIML Recommendations in force in 1992, 1996 and 2000

## 6 Categories of measuring instruments covered by the OIML Certificate System

Thirty-four categories of measuring instruments are covered by the following OIML Recommendations:

<table border="1"><tr><td>R31</td><td>R88</td><td>R110</td><td>R126</td></tr><tr><td>R50</td><td>R93</td><td>R112</td><td>R127</td></tr><tr><td>R51</td><td>R97</td><td>R113</td><td>R128</td></tr><tr><td>R58</td><td>R98</td><td>R114</td><td>R129</td></tr><tr><td>R60</td><td>R102</td><td>R115</td><td>R130</td></tr><tr><td>R61</td><td>R104</td><td>R116</td><td>R131</td></tr><tr><td>R65</td><td>R105</td><td>R117/118</td><td>R132</td></tr><tr><td>R76</td><td>R106</td><td>R122</td><td></td></tr><tr><td>R85</td><td>R107</td><td>R123</td><td></td></tr></table>

<table border="1"><tr><td>Total number of categories</td><td>1996</td><td>1997</td><td>1998</td><td>1999</td><td>2000</td><td>2001</td></tr><tr><td></td><td>16</td><td>21</td><td>25</td><td>28</td><td>31</td><td>34</td></tr><tr><td></td><td>+31%</td><td>+19%</td><td>+12%</td><td>+11%</td><td>+10%</td><td></td></tr></table>

## 7 Cumulative number of registered OIML certificates (as at the end of 2000)

Nonautomatic weighing instruments (R 76) ... 397 ≈ 45.2 %

Load cells (R 60/1991) ... 226 ≈ 25.8 %

Load cells (R 60/2000) ... 54 ≈ 6.1 %

Automatic catchweighing instruments (R 51) ... 68 ≈ 7.7 %

Automatic gravimetric filling instruments (R 61) ... 40 ≈ 4.6 %

Fuel dispensers for motor vehicles (R's 117/118) ... 38 ≈ 4.3 %

Gas meters (R 31) ... 18 ≈ 2.0 %

Automatic level gauges (R 85) ... 16 ≈ 1.8 %

Automatic weighing instruments (R 107) ... 8 ≈ 0.9 %

Continuous totalizing automatic weighing instruments (R 50) ... 8 ≈ 0.9 %

Direct mass flow measurement systems (R 106) ... 4 ≈ 0.5 %

Evidential breath analyzers (R 126) ... 1 ≈ 0.1 %

Clinical electrical thermometers (R 115) ... 1 ≈ 0.1 %

Cumulative total, as at the end of 2001 ... 879

<table border="1"><tr><td>1996</td><td>1997</td><td>1998</td><td>1999</td><td>2000</td><td>2001</td></tr><tr><td>226</td><td>318</td><td>452</td><td>582</td><td>736</td><td>879</td></tr><tr><td>+40%</td><td>+42%</td><td>+29%</td><td>+26%</td><td>+19%</td><td></td></tr></table>

244 manufacturers and applicants of measuring instruments from 31 countries have been granted OIML certificates

## 8 Degree of acceptance of OIML certificates by OIML Members

The most recent inquiry on the acceptance of OIML certificates by OIML Members was carried out by the BIML in 2000. Forty-two countries sent responses and the results can be summarized as follows:

- More than 190 certificates were accepted and more than 260 were taken into consideration to facilitate the process of national type evaluation and approval;

Certificates were accepted by 10 Member States and 3 Corresponding Members;

Certificates were taken into consideration by 18 Member States and 4 Corresponding Members.

## 9 Distribution of the OIML Bulletin and revenue from the sale of OIML Publications

<table border="1"><tr><td rowspan="3">Average number of Bulletins distributed quarterly</td><td>1998</td><td>1999</td><td>2000</td><td>2001</td></tr><tr><td>1039</td><td>1044</td><td>1100</td><td>1050</td></tr><tr><td></td><td>+0.5%</td><td>+5.4%</td><td>-4.5%</td></tr><tr><td>... of which Bulletin subscribers</td><td>170</td><td>163</td><td>156</td><td>153</td></tr><tr><td></td><td>-4.1%</td><td>-4.3%</td><td>-1.9%</td><td></td></tr><tr><td>Sales of Publications(FRF)</td><td>160930</td><td>187272</td><td>214010</td><td>249400</td></tr><tr><td></td><td>+16.4%</td><td>+14.2%</td><td>+16.5%</td><td></td></tr></table>

## 10 Connections to and development of the OIML web site (www.oiml.org)

1998: average 500 connections per month

1999: average 1000 connections per month

2000-2001: average 2500 connections per month

The site is regularly updated and contains a Members Area with information on OIML events, meetings, deadlines for replies, etc. Members will soon be able to update their information directly via the new integrated database and a number of other developments are also underway.

Most customers now place orders via the form on the web site and secure online payment methods are being investigated.

## 11 Activities in support of development

Main activities:

OIML Development Council Meeting (24 September 2001, Moscow) with 82 participants;

- Continued activities of Development Council Working Groups on their existing work programmes;

Participation in a first WTO meeting on developing country participation in standard-setting activities;

Contact with the World Bank to establish a meeting to discuss funding issues;

- Contacts with international organisations (such as WTO TBT Committee, ISO DEVCO, UNIDO, UN/ECE, etc.), and regional metrology and legal metrology organisations;

- Contacts with the national legal metrology institutes of a number of developing countries;

- Participation, with UNIDO, in a PTB-UEMOA project in West Africa concerning the development of metrology in the region;

- Prioritisation of OIML technical committees and subcommittees whose work is of interest to developing countries;

- Maintenance of the lists of technical experts and metrology training courses on the Development Council part of the OIML web site. Conversion of these lists into a database.

<div align="center">

# OIML Certificate System: Certificates registered 2002.02-2002.04

</div>

For up to date information: www.oiml.org

The OIML Certificate System for Measuring Instruments was introduced in 1991 to facilitate administrative procedures and lower costs associated with the international trade of measuring instruments subject to legal requirements.

The System provides the possibility for a manufacturer to obtain an OIML certificate and a test report indicating that a given instrument pattern complies with the requirements of relevant OIML International Recommendations.

Certificates are delivered by OIML Member States that have established one or several Issuing Authorities responsible for processing applications by manufacturers wishing to have their instrument patterns certified.

OIML certificates are accepted by national metrology services on a voluntary basis, and as the climate for mutual confidence and recognition of test results develops between OIML Members, the OIML Certificate System serves to simplify the pattern approval process for manufacturers and metrology authorities by eliminating costly duplication of application and test procedures.

![](page=1,bbox=[164, 1024, 1726, 1809])

<div align="center">

# Système de Certificats OIML:

Certificats enregistrés 2002.02-2002.04

</div>

Pour des informations à jour: www.oiml.org

Le Système de Certificats OIML pour les Instruments de Mesure a été introduit en 1991 afin de faciliter les procédures administratives et d'abaisser les coûts liés au commerce international des instruments de mesure soumis aux exigences légales.

Le Système permet à un constructeur d'obtenir un certificat OIML et un rapport d'essai indiquant qu'un modèle d'instrument satisfait aux exigences des Recommandations OIML applicables.

Les certificats sont délivrés par les États Membres de l'OIML, qui ont établi une ou plusieurs autorités de délivrance responsables du traitement des

demandes présentées par des constructeurs souhaitant voir certifier leurs modèles d'instruments.

Les services nationaux de métrologie légale peuvent accepter les certificats sur une base volontaire; avec le développement entre Membres OIML d'un climat de confiance mutuelle et de reconnaissance des résultats d'essais, le Système simplifie les processus d'approbation de modèle pour les constructeurs et les autorités métrologiques par l'élimination des répétitions coûteuses dans les procédures de demande et d'essai.

## INSTRUMENT CATEGORY

CATÉGORIE D'INSTRUMENT

Automatic catchweighing instruments

Instruments de pesage trieurs-étiqueteurs

à fonctionnement automatique

R 51 (1996)

Issuing Authority / Autorité de délivrance Physikalisch-Technische Bundesanstalt (PTB), Germany

R051/1996-DE-1997.01 Rev.1

Types KWE30xx, KPE10xx, KWI30xx and KPI10xx

(Class X(1))

Robert BOSCH GmbH, Geschäftsbereich

Verpackungsmaschinen, Stuttgarter Straße 130,

D-71332 Waiblingen, Germany

R051/1996-DE-1999.05 Rev.1

L2-PTLs-... (Classes Y(a) and Y(b))

Mettler-Toledo (Albstadt) GmbH,

Unter dem Malesfelden 34, D-72458 Albstadt, Germany

Issuing Authority / Autorité de délivrance Centro Español de Metrologia, Spain

R051/1996-ES-2001.01 Automatic catchweighing instrument, type "CP-90", accuracy class Y(a) VARPE CONTROL DE PESO, S.A., Osona, 21 - Poligono Industrial Can Casablancas, Sant Quirze del Vallés, E-08192 Barcelona, Spain

Issuing Authority / Autorité de délivrance Netherlands Measurement Institute (NMi) Certin B.V., The Netherlands

R051/1996-NL1-1998.06 Rev.1 Type C-50 (Class X(1)) BTH, Kuiper 14, NL-5521 DH Eersel, The Netherlands

R051/1996-NL1-2002.02 MB-900B (Class Y(b)) Shinko Denshi Co., Ltd, 3-9-11 Yushima, Bunkyo-ku, Tokyo 113-0034, Japan

## INSTRUMENT CATEGORY

CATÉGORIE D'INSTRUMENT

Metrological regulation for load cells

(applicable to analog and/or digital load cells)

Réglementation métrologique des cellules de pesée

(applicable aux cellules de pesée à affichage

analogique et/ou numérique)

R60(2000)

Issuing Authority / Autorité de délivrance Netherlands Measurement Institute (NMi) Certin B.V., The Netherlands

R060/2000-NL1-2002.01 Rev.1

Types 3410 and 3411 (Class C)

Tedea Huntleigh International Ltd., 5a Hatzoran St.,

Netanya 42506, Israël

## R060/2000-NL1-2002.04

Types SWRC 551 TL and SWRC 551 TF (Class C) Balea, 8, avenue du Grand Chene, Z.A. Les Avants, F-34270 Saint-Mathieu de Tréviers, France

## R060/2000-NL1-2002.05

Type SBH (Class C)

Mettler-Toledo (Changzhou) Scale & System Ltd.,

111 Changxi Road, Changzhou, Jiangsu 213001, China

## R060/2000-NL1-2002.06

IMV1, IMV2 and IMV... (Class C)

Grupo Epelsa, S.L. or EXA, Ctra. Sta. Cruz de Calafell

35 km. 9,400, E-08830 Sant Boi de Llobregat, Barcelona Spain

R060/2000-NL1-2002.07 SBC (Class C) CIBE Srl., Viale Milano, 11, I-21047 Saronno (VA), Italy

R060/2000-NL1-2002.08 Type CPT (Class C) Precia Molen, BP 106, F-07001 Privas cedex, France

## R060/2000-NL1-2002.09

Type BK2 (Class C)

Flintec GmbH, Bahnhofstraße 52-54,

D-74909 Meckesheim, Germany

R060/2000-NL1-2002.10 MTB (Class C) Mettler-Toledo (Changzhou) Scale & System Ltd., 111 Changxi Road, Changzhou, Jiangsu 213001, China

## INSTRUMENT CATEGORY

CATÉGORIE D'INSTRUMENT

R 61 (1996)

Issuing Authority / Autorité de délivrance Netherlands Measurement Institute (NMi) Certin B.V., The Netherlands

R061/1996-NL1-1998.09 Rev.1 Types N-50, B-50 and U-50 (Class X(1)) BTH, Kuiper 14, NL-5521 DH Eersel, The Netherlands

R061/1996-NL1-2002.01

Types CCW-M-****(*)-*/**-**, CCW-EM-****(*)-*/**-**,

CCW-NZ-****(*)-*/**-**, CCW-RZ-****-*/**-**-N,

CCW-DZ-****-*/**-**-N (Class X(1))

Ishida Co., Ltd., 44, Sanno-cho, Shogoin, Sakyo-ku,

Kyoto-city 606-8392, Japan

## INSTRUMENT CATEGORY

CATÉGORIE D'INSTRUMENT

Nonautomatic weighing instruments

Instruments de pesage à fonctionnement

non automatique

R 76-1 (1992), R 76-2 (1993)

Issuing Authority / Autorité de délivrance Danish Agency for Development of Trade and Industry, Division of Metrology, Denmark

R076/1992-DK-2002.01

CUC-Ex (Classes III and III)

Crisplant a/s, P.O. Pedersens Vej 10, DK-8200 Aarhus N, Denmark

Issuing Authority / Autorité de délivrance Centro Español de Metrologia, Spain

R076/1992-ES-1999.01 Rev.1 Nonautomatic, graduated, self-indicating, electronic counter-top weighing instrument, type "PLUS-20" intended for direct sale to the public (Class III) Campesa S.A., Avinguda Cova Solera, 25-29, E-08191 Rubi-Barcelona, Spain

Issuing Authority / Autorité de délivrance Netherlands Measurement Institute (NMi) Certin B.V., The Netherlands

R076/1992-NL1-2001.50 Rev.1

Hytech-6200 (Class III)

Hytech Europe BV, Bramenberg 9-a,

NL-3755 BT EEMNES, The Netherlands

R076/1992-NL1-2002.03 Rev.1 6200,1500 (Class III) Hytech Europe BV, Bramenberg 9-a, NL-3755 BT EEMNES, The Netherlands

R076/1992-NL1-2002.04 SM-200... (Class III) Teraoka Seiko Co., Ltd., 13-12 Kugahara, 5-Chome, Ohta-ku, Tokyo 146-8580, Japan

R076/1992-NL1-2002.05 JCA, JWA -series (Class III) Jadever Scale Co. Ltd., No. 5, Wu-Chuan 2 RD., Wu-Ku Hsiang, Taipei Hsien, R.O.C, Taiwan

R076/1992-NL1-2002.06

Viper ... (Class III)

Mettler-Toledo (Albstadt) GmbH,

Unter dem Malesfelden 34, D-72458 Albstadt, Germany

R076/1992-NL1-2002.07 SM-300... (Class III) Teraoka Seiko Co., Ltd., 13-12 Kugahara, 5-Chome, Ohta-ku, Tokyo 146-8580, Japan

R076/1992-NL1-2002.08 SM-700..(Class III) Teraoka Seiko Co., Ltd., 13-12 Kugahara, 5-Chome, Ohta-ku, Tokyo 146-8580, Japan

## R076/1992-NL1-2002.09

AP series (Class III)

CAS Corporation, CAS Factory # 19 Kanap-ri,

Kwangjeok-myon, Yangju-kun Kyungki-do, Rep. of Korea

## R076/1992-NL1-2002.10

R076/1992-NL1-2002.10

TROOPER (Class III)

Ohaus Corporation, 19A Chapin Road, Pine Brook,

New Jersey 07058, USA

R076/1992-NL1-2002.11 TBF-410MA, TBF-300MA (Class III) Ishida Co., Ltd., 44, Sanno-cho, Shogoin, Sakyo-ku, Kyoto-city 606-8392, Japan

R076/1992-NL1-2002.12 BWB-800MA (Class III) Tanita Corporation (Brand names: Tanita, Rhewa, Wunder), 14-2, 1-Chome, Maeno-cho, Itabashi-ku, Tokyo 147-8630, Japan

R076/1992-NL1-2002.13 Nova-Ⅱ series (Class Ⅲ) Minebea Co. Ltd., Measuring components div., Kuruizawa Factory Miyota-Machi, Kitasakugun Nagano-Ken, Japan

R076/1992-NL1-2002.14 Type 2100 (Class III) Ranger Instruments, 41 Success Street, Acacia Ridge, QLD 4110, Australia

R076/1992-NL1-2002.16 Jeep-Bat (Class III) Mobba S.C.C.L., C/ Colom 6-8, E-08912 Badalona- Barcelona, Spain

## INSTRUMENT CATEGORY

CATÉGORIE D'INSTRUMENT

Multi-dimensional measuring instruments Instruments de mesure multidimensionnels

R129(2000)

Issuing Authority / Autorité de délivrance Netherlands Measurement Institute (NMi) Certin B.V., The Netherlands

R129/2000-NL1-2002.01 MB-900B Shinko Denshi Co., Ltd, 3-9-11 Yushima, Bunkyo-ku, Tokyo 113-0034, Japan

Updated information on OIML certificates:

www.oiml.org

RLMO MEETING

<div align="center">

# Report on the $ 1 1^{th} $ SADCMEL Meeting

</div>

8-9 April 2002 Mahé, Seychelles

BRIAN BEARD, SABS (South Africa)

The 11th SADCMEL and Technical Committee meetings formed part of the annual series of meetings of SADC organizations dealing with Standardisation, Quality Assurance, Accreditation and Metrology (SQAM).

The $ 11^{\mathrm{th}} $ SADCMEL meeting was attended by 41 delegates representing 13 of the 14 SADC countries and observers from Kenya (associate members), NWML (UK), BIML, PTB, UNIDO and COMESA.

## Technical Committee Meetings (8 May 2002)

Technical Committee meetings are normally held prior to the SADCMEL meeting in order to discuss issues that have not been resolved by correspondence. Full reports on activities are then tabled at the main meeting.

TC 1 Packaging and Sale of Goods - discussed outstanding issues in the SADCMEL labelling of goods document.

TC2 Instruments - discussed the almost complete draft of a document including stand alone on requirements for mechanical non self indicating counter scales and beam scales based on the requirements of OIML R 76.

TC4 Training - Comments to a draft document on minimum training requirements for legal metrology practitioners were discussed. Once completed, train the trainer courses will be developed after attending similar courses offered internationally.

## 11th SADCMEL Meeting (9 May 2002)

Mr. Ali Tukai, SADCMEL Chairperson, opened the meeting by welcoming all present. He had a special word of welcome for the international observers.

The meeting agenda and minutes of the $ 1 0^{th} $ SADCMEL meeting were then approved.

Among matters arising it was noted that:

Kenya had formally been accepted as an associate member.

Members had been invited to join SABS subcommittees dealing with legal metrology issues which included the adoption of OIML Recommendations as National Standards, which in turn, could be adopted as Regional Standards if so agreed.

## Addresses by invited guests

Mr. Chris Rosenberg (NWML, UK) gave an overview of the history of legal metrology in the UK and the present activities of the NWML. EU legislation is fast changing in line with the "New Approach" directives and it is important that the NWML be involved and give input to ensure that UK needs are incorporated. Legal metrology legislation is currently being liberalized in the UK and moving from total regulator control to allowing private industry to carry out certain tasks such as verification, and relying on quality systems to prove confidence. The NWML participates in OIML and WELMEC activities including 30 technical committees and hosting several secretariats.

The following points of interest to members were highlighted during question time:

Training courses offered, especially the seminar on the benefits of legal metrology aimed at senior government officials.

The implications of the Measuring Instrument Directive.

ISO 9000 and not ISO 17025 was used to prove competence and quality in private verification companies.

Mr. Attila Szilvassy (BIML) briefly outlined current OIML activities that included the replacement of Mr. Athané by Mr. Magaña as BIML Director and matters discussed at the February OIML Presidential Council Meeting. He also mentioned forthcoming events - the seminar on What will Legal Metrology be in the Year 2020, the CIML and the Development Council meetings - to be organized in France in September-October 2002.

Further he dealt with the requirements for applying for OIML membership as well as membership fees and obligations and rights of Member States and Corresponding Members. He stressed that it was easy and inexpensive (1828 € entry fee plus 914 € subscription fee for the current year) to become a Corresponding Member when compared with the complete set of OIML

documents and services received in return. A document dealing with fees, obligations and rights was distributed.

Letters addressed to SADCMEL by Mr. Bernard Athané as outgoing BIML Director and Mr. Jean-François Magaña, the new BIML Director, were read.

## Report on SQAM funding proposal

A needs analysis within member countries was carried out and a project proposal to secure donor funding for the development of legal metrology infrastructures within the region, has been completed. This project forms part of a greater project covering all SQAM structures (Standards bodies, Accreditation bodies, National Metrology bodies and Legal Metrology bodies).

It appears that the EU will be a likely donor and the proposals will now be edited to reflect EU terminology and give a clear link to SADC policy frameworks. This will require a technical regulation framework acceptable to SADC members and in line with international best practices. It is expected that the editing process and linkage to policies will be completed by September 2002.

## Technical activities

## Packaging of goods

Mr. Beard, TC1 Chairperson, reported on committee activities and the following discussion points were highlighted:

The SADCMEL document on labelling and sale of goods requirements has recently been circulated to industry within member countries; discussions with industry should continue as a matter of urgency in order to accommodate industry requirements and to ensure acceptance.

Members will discuss the need for harmonization of requirements for fresh fruit and vegetables with their Departments of Agriculture.

The TC1 Chairperson mentioned that the 3 CD of revision of OIML R 87, that deals with tolerances, sampling methods and other aspects of the sale of goods, has recently been distributed. There were over 500 comments to the 2 CD and many of these appear to have been incorporated in the latest draft. It appeared however as if several requirements requested by SADCMEL and incorporated in the 2 CD have now been omitted. This is of great concern as it means that due to a lack of consensus there will be no international harmonization on aspects such as a standard temperature at which prepacked liquids should be correct

(packed) or requirements for commodities that are susceptible to moisture loss and therefore weight loss, after packing. It seems that SADCMEL will have to develop regional requirements for such issues.

Members were reminded that comments to 3 CD should be submitted to the TC chairperson by 17 May so that they could be sent to other members for comment and submitted to OIML TC 6 as SADCMEL comments. In addition the document will be discussed with South African industry and comments made to OIML TC 6.

## Instruments

Mr. Zulu of Zambia, TC 2 Chairperson, gave a report on the activities of the committee and various issues were discussed. The following points were highlighted:

The document on requirements for mechanical nonself indicating counter scales will be amended and distributed within industry for comment and industry requirements will be discussed at the next TC meeting.

A target matrix for implementation, including target dates for acceptance of relevant OIML Recommendations by members, has been distributed to members for completion. The target dates are intended to set priorities for adoption of Recommendations in order to establish training and other infrastructural needs. The final date for completion of the matrix was set as 31 May 2002.

## Training

Mr. Molefe of Botswana, TC4 Chairperson, reported that the document on minimum training requirements will be amended and distributed for comment and the revision of OIML D14 will also be followed and used as input when completed.

In connection with the PTB proposal for a regional training course the Regional Coordinator mentioned that after Angola and DRC requested funding to attend a course on the verification of Non Automatic Weighing Instruments, the PTB had suggested holding a regional course that would be more cost effective. The PTB had generously offered to assist with costs and members would be expected to provide counterpart funding to ensure ownership, as follows:

Least developed countries (UN list): 15 %

Other members: 30 %

The course would be offered in South Africa and would include a visit to a weighbridge and practical

testing of single and multi interval electronic scales. The course would be held in July or August and cater for about ten people who could then train others in their respective countries. At the end of the course a PTB representative would hold an evaluation workshop at the PTB's expense to establish needs to start a verification activity (equipment, etc.) and possibly assist with further funding where appropriate. Course arrangements will be made if there is sufficient interest.

Dr Stoll-Malke (PTB) said that he felt that the region would benefit more by holding the course under local conditions and using local expertise. The PTB wanted to assist institutions to get started at a basic level and support self-sustainable functions which is why countries are required to pay a portion of training costs.

## Long term strategy for SADCMEL

Mr. Carstens (SABS) gave a presentation on how he viewed the future role and activities of SADCMEL. He gave an overview of the benefits of Legal Metrology to the economy, including promotion of trade, and stressed the need for harmonized technical requirements. He then mentioned how technical regulations were being dealt with in South Africa and put forward his thoughts on how the harmonisation process should proceed within SADCMEL. Initiatives should be put in place to assist with the uniform interpretation, implementation and maintenance of regulations and he proposed an annual Regional Workshop on Legal Metrology.

Mr. Pamacheche (SADC Secretariat) noted that the information given ties in with overall SADC thinking.

## General

Dr Hengstberger (Regional Coordinator of SADCMET the grouping of National Metrology Laboratories) mentioned that it was important that the SADC Resource Centre for Metrology Education (SRCME) started functioning according to the signed MOU.

It was confirmed that Mr. Beard would be the SADCMEL board member and SADCMEL will give its full support to the SRCME.

## Date and venue of next meeting

Mozambique's offer to host the 12th SADCMEL meeting in late October or early November was accepted unanimously. Malawi and Namibia offered to host future meetings.

## Election of new SADCMEL Chairperson

The SADCMEL chair rotates every two years and the term of office of Mr. Tukai expired in April 2002. Mr. Kimon Zulu of Zambia was elected as chairperson for the next two years.

## Closure

Mr. Tukai closed the meeting after thanking delegates for their input and the regional coordinator for a well organized meeting.

Mr. Zulu as the new chairperson thanked members and delegates for the confidence shown in electing him to chair SADCMEL and promised to give of his best and trusted that he will receive the same loyal support accorded to Mr. Tukai over the last two years.

## Contact details

SADCMEL Chairperson

Mr. Kimon Zulu - Deputy Superintendent Assizer Assize Department

PO Box 30989, Lusaka, Zambia

Tel: +260 1 236062 - Fax: +260 1 222294

E mail: assize@zamnet.zm

SADCMEL Regional Coordinator

Mr. B E Beard - Technical Specialist: Legal Metrology

Policy Development and Implementation

SABS

Private Bag X191, Pretoria, South Africa

Tel: +27 12 4287001 - Fax: +27 12 4286116

E mail: beardbe@sabs.co.za

Web site: www.sadc-sqam.org

![](page=7,bbox=[971, 1976, 1880, 2520])

JOINT MEETING

<div align="center">

# Cooperation with the Metre Convention, ILAC and other International Organizations

</div>

BIML REPORT

On February 27th, the annual coordination meeting between the OIML, the Metre Convention and ILAC was held at the BIPM. Again this year, the meeting served to demonstrate that the three organizations have very similar concerns and priorities, and also that a considerable number of fields were indeed common to all of them: two general issues were identified as being worked on in the three organizations in a similar way and are consequently considered as being important fields for cooperation:

Studies on the economic impact of metrology and accreditation worldwide, especially on the cost to countries of technical barriers to trade, will be the object of mutual information and consultation,

Government awareness of the issues developed by the three organizations, together with coordination with standard-setting bodies and Regional Organizations, are major prerequisites for the joint projects of the three organizations to be successful,

- All three organisations either have or are in the process of agreeing and implementing Mutual Recognition Arrangements/Agreements and the global consistency of these arrangements is an important issue for their coordination.

In addition to the usual items on the agenda (Joint Committee for Guides on Metrology (JCGM) activities, ISO 17011, ISO 9001, etc.), two particular issues were discussed and further joint meetings have been held.

The revision of OIML D1 Law on Metrology is a priority for a number of members of the three organizations, since many countries are revising their own law on metrology, on legal metrology, on conformity assessment, etc. A Law on Metrology is a concern for the three organizations, since it sets the bases for

traceability and consistency of measurements. A joint working group met on February 28th and discussed the working document, which had been drawn up by the OIML (BIML and the USA). Following the incorporation of comments submitted by the joint working group, this working document is now at the status of first committee draft (1 CD) of OIML TC 3 and will shortly be submitted for discussion within the three organizations, so as to progress jointly rather than individually at the next meeting of the joint working group.

The revised D1 will be different from the existing one. While D1 was previously a model law on metrology which was recommended to be adopted in the various countries, the future D1 will consist of fundamental points to be considered when drafting laws on metrology, laws on legal metrology and laws on conformity assessment. These elements will take into account the different specific requirements of the countries, such as the level of economic development, the degree of centralization of the country and the extension of the role of the state compared to that of private bodies.

The second issue of common interest is to promote consistency in the assistance programs to developing countries and to improve the way in which metrology and accreditation are taken into account in these programs. A Joint Committee had been formed, the title of which was initially Joint Committee for Coordinating Assistance to Developing Countries in Metrology. The aim of this Joint Committee is to assist international development agencies, funding organizations and governments to design technical assistance programs which have consistent and comprehensive parts dealing with metrology, legal metrology and accreditation. Another purpose of this Joint Committee is to provide technical assistance bodies with a list of experts whose technical competence is adapted to the tasks required by the programs.

A further meeting was held on 24 April 2002 between the BIPM, ILAC and the OIML to study the ways in which this Joint Committee could be further developed, in association with other international organizations whose activity is complementary to metrology and accreditation (ISO, ISO/CASCO, ISO/DEVCO, IEC, IAF), and with some regional organizations that are interested by this issue (OAS, APEC, SADC, SIM). UNIDO also participated in this meeting, and the OIML was represented by the BIML Director and the Chairperson of the OIML Development Council. All the participants recognized the need to expand the scope of the Joint Committee to include the coordination of technical assistance to developing countries and countries in transition in metrology, accreditation and standardization. A number of activities to be considered by this Joint Committee have been identified and will be discussed at its next meeting in Stockholm on 28 September.

## Forthcoming OIML Publications

The following Recommendations and Document are being finalized at the BIML and it is expected that they will be available before the summer vacation

![](page=9,bbox=[312, 915, 780, 1521])

OIML R 16-1

Edition 2002 (E)

![](page=9,bbox=[331, 2384, 623, 2473])

OIML R 133 Edition 2002 (E)

![](page=9,bbox=[1379, 1108, 1674, 1198])

![](page=9,bbox=[1198, 1724, 1702, 2371])

<div align="center">

# Trilingual dictionary (English-French-German) of the technical terms and idioms used in the field of static and dynamic measurement of quantities of liquids and gases

</div>

DETLEV MENCKE

Based on International Recommendations and Documents of the OIML, ISO Standards and other sources, and compiled by Dr. Detlev Mencke (formerly PTB Braunschweig)

The scope of this dictionary, which contains over 3600 terms and idioms, is a result of the wide scope of the technical area involved. It comprises simple volume measures (bottles, capacity serving measures, casks), fixed storage tanks with automatic level gauges, the different types of volume and mass flowmeters both for liquids and gases, their combination with other devices (gas separators, pumps, valves) to form a measuring system, electronic devices as components of this equipment, modern telecommunication devices, the designations of petroleum products and of other liquids, the terms of metrology, mathematics, mechanical and electrical engineering, finance and typography as well as the test methods and test facilities both for mechanical and electronic devices, etc.

In the translation of the terms, the author has attached the greatest importance to technical equivalence and not to word-for-word correspondence. For example, some years ago the members of the OIML Subcommittee TC 8/SC 3 agreed to regard the terms "Measuring System", "Messanlage" and "Ensemble de Mesurage" as synonyms and that they apply to the combination of all devices needed to carry out a specified measurement of flowing liquids.

The Dictionary is available in the following formats:

- 3.5" disk,

- CD-ROM with autorun,

- Acrobat PDF Files.

The disk contains the following files, which can be opened using Adobe Acrobat Reader:

GEN-2001.PDF Foreword Exceptional features Meaning of the characters Bibliography

DEU-2001.PDF Dictionary part 1 $ ^{*} $ German-English-French

ENG-2001.PDF Dictionary part 2 $ ^{*} $ English-French-German

FRA-2001.PDF Dictionary part 3 $ ^{*} $ French-German-English

*sorted by alphabetic order of the first language

The price for the disk is 40 €, plus shipping costs and bank charges.

The Dictionary is based on the following International Publications:

VIM, VIML, GUM

OIML R 6, R 22, R 29, R 31, R 32, R 45, R 49-1, R 71, R 81, R 85, R 86, R 96, R 105, R 117, R 119, R 120, R 125;

OIML D 4, D 7, D 11, D 25;

ISO 1998-1, 1998-2, 1998-5, 1998-6, 4006;

CEN prEN 14154-1 to -3;

EEC 76/766 + Practical alcohol tables, 92/81, 92/83, COM 566 (MID)

CECOD Vocabulary, I.G.U. Dictionary of the Gas Industry

## Contact address

Dr. Detlev Mencke

c/o Physikalisch-Technische Bundesanstalt

Bundesallee 100

D-38116 Braunschweig

Germany

Tel.: +49 531 592 1363

Fax: +49 531 592 1305

E-mail: detlev.mencke@ptb.de

<div align="center">

# Basic Metrology for ISO 9000 Certification

</div>

G.M.S. DE SILVA Quantum IT LLC, New Jersey, USA

Traceable calibration of test and measurement equipment is a requirement of the ISO 9000 series of standards. Basic Metrology for ISO 9000 Certification provides essential information for the growing number of firms registered for ISO 9000.

Dr. G.M.S. de Silva, who has a lifetime of experience in metrology and quality management fields, condenses that knowledge in this valuable and practical workbook. The book provides a basic understanding of the principles of measurement and calibration of measuring instruments falling into the following fields: Length, Angle, Mass, Pressure, Force, Temperature and AC/DC Electrical quantities. Basic concepts and definitions, ISO 9001 requirements and uncertainty determinations are also included.

- Includes worked examples in the text and solutions to problems which can be compared to real life situations.

- Includes basic metrology principles and data that will be useful to test and calibration personnel in their day to day work.

Contains features of the metrology management structure which an organization needs to set up in order to satisfy ISO 9000 criteria.

## Contact address

Heinemann Publishers

PO Box 382 Oxford OX2 8RU United Kingdom

Tel.: +44 (0)1865 888130

Fax: +44 (0)1865 314029

E-mail: bhuk.orders@repp.co.uk

Web site: www.bh.com

<table border="1"><tr><td>Contents</td></tr><tr><td>Absolute, gauge and differential pressure modes</td></tr><tr><td>Accuracy classes of balances</td></tr><tr><td>Basic concepts</td></tr><tr><td>Calibration of a multifunction calibrator</td></tr><tr><td>Calibration of balances</td></tr><tr><td>Calibration of dimensional standards and measuring instruments</td></tr><tr><td>Calibration of force standards and test instruments</td></tr><tr><td>Calibration of multimeters and other instruments</td></tr><tr><td>Calibration of pressure standards and instruments</td></tr><tr><td>Calibration of thermometers</td></tr><tr><td>Electrical measurement standards</td></tr><tr><td>Evolution of ISO 9000 standards</td></tr><tr><td>Examples of uncertainty calculations</td></tr><tr><td>Force measuring instruments</td></tr><tr><td>Fundamental concepts of measurement</td></tr><tr><td>Industrial thermometers</td></tr><tr><td>Industrial weighing systems</td></tr><tr><td>International Temperature Scale of 1990 (ITS-9O)</td></tr><tr><td>Linear and angular measurements</td></tr><tr><td>Mass and weight</td></tr><tr><td>Mass measurements</td></tr><tr><td>Mass standards - types and classes</td></tr><tr><td>Measurement of angle</td></tr><tr><td>Measurement of force</td></tr><tr><td>Measurement of temperature</td></tr><tr><td>Practical temperature scales</td></tr><tr><td>Pressure measurements</td></tr><tr><td>Pressure measuring instruments</td></tr><tr><td>Primary standards and SI units</td></tr><tr><td>Recommendations of the ISO Guide</td></tr><tr><td>Requirements of ISO 9000 standards for test and measuring equipment</td></tr><tr><td>Secondary and working standards</td></tr><tr><td>SI and other units</td></tr><tr><td>Spinning ball gauge standard</td></tr><tr><td>Thermodynamic scale</td></tr><tr><td>Uncertainty of measurements</td></tr><tr><td>Working standards</td></tr></table>

![](page=12,bbox=[898, 280, 1187, 560])

<div align="center">

# CALL FOR PAPERS

</div>

The South Yorkshire Trading Standards Unit (United Kingdom) has in the past organised several successful conferences on weighing and mass measurement, the most recent of which was held in 2000. Visitors and speakers came from government, calibration organisations and a varied cross-section of industry, representing some twenty countries, not only in Europe, but also the Far East, the USA and Australia.

Another conference is now provisionally scheduled for 17 and 18 June 2003, which will also include a Workshop entitled Uncertainty Budgeting for Mass and Weighing Machine Calibration.

Several demonstrations of new products are also scheduled and a full social programme is planned.

Papers are now being invited for presentation at the conference, and each presentation is scheduled to last about thirty-five minutes. In the first instance abstracts (up to 300 words) should be submitted, together with the proposed title of the paper, and the name and address of the contributor. Abstracts should be submitted to the above address by 31 July 2002.

For speakers representing non-profit making organisations which are based outside the United Kingdom a grant towards travel is offered, and will usually cover the costs of travel to and from the United Kingdom. All speakers receive complimentary conference registration.

Subjects to be included will cover such topics as:

Legal Metrology (including European Legislation)

Mass Metrology and Calibration

Metrology and Quality Assurance

Measurement Control

International Laboratory Accreditation

Computer Applications in the Laboratory

Automation in Calibration

UKAS Laboratory Accreditation

Developments at the National Laboratories

Measurement in the Service Industries

Calibration Procedures

Best Practice Guides

Industrial Weighing Machine Design and Use Magnetic Susceptibility in the Calibration of OIML Weights

Please contact Mr. Doug Palmer (doug@sytsu.co.uk) or Mrs Jenny Bashforth (jenny@sytsu.co.uk) for further details.

Tel. +44 (0)114 246 3491 - Fax +44 (0)114 240 2536

www.sytsu.com

![](page=12,bbox=[1076, 1642, 1831, 2531])

<div align="center">

# European Conference on "Safe Products By Means Of Market Surveillance"

</div>

16-18 October 2002 Berlin, Germany

Safe products are in the interests of all market participants-consumers are concerned about the protection of health and safety, whilst manufacturers wish to guarantee the free movement of merchandise. In relation to this, market surveillance is a fundamental instrument for ensuring that only safe products arrive on the market and that a fair basis for competition is provided for.

In Europe the practice of market surveillance has developed extensively, producing a large pool of experience and know-how in this area. The EU Member states have set up special bodies to carry out market surveillance, and these bodies are increasingly being perceived by manufacturers and those who place products on the market as being instrumental in realising the concept of the European Single Market.

This Conference is aimed at all those who are involved in market activities. Regardless of whether you are a manufacturer, a certifying body, an importer, a merchant, a market scrutiniser, a lawyer, a judge or a consumer, don't miss this opportunity to get involved in the debate.

In order to maintain the same level of market surveillance between the EU Member states, a continual inter-change of experience and know-how is required on matters such as national implementation concepts, practice of enforcement, sanctions and other measures, and risk assessment procedures.

Conference Organisation:

Mr. Klaus Link

Hinte Messe- und Ausstellungs-

GmbH

Griesbachstraße 10,

D-76185 Karlsruhe,

Germany

Tel. +49 (0)721 93133-820 Fax +49 (0)721 93133-810

E-Mail: klink@hinte-messe.de

www.arbeitsschutz-aktuell.info

<div align="center">

# XVII IMEKO World Congress Metrology in the 3rd Millennium

</div>

Dubrovnik, Croatia, June 22-27, 2003

First Announcement and Call for Papers

![](page=13,bbox=[1126, 597, 1739, 1478])

## Abstract submission

Prospective authors are invited to submit Abstracts by September 2, 2002. Extended abstracts (two typewritten A4 pages) should be sent by e-mail (imeko2003@hmd.hr) as an attachment in Adobe Acrobat (*.pdf) format and, mandatory Microsoft Word (*.doc) format, not exceeding 2 Mb.

## The City of Dubrovnik

Dubrovnik is situated in the very south of the Republic of Croatia and its favourable geographical position led to its very successful development based on maritime and trading activities. The city has preserved the beauty of a medieval town and its outstanding cultural and historical monuments have earned it a place on UNESCO's World Heritage List.

General Inquiries

XVII IMEKO Office - Prof. Dr. Mladen Borsic

Croatian Metrology Society

Berislaviæva 8, HR-10000 Zagreb, Croatia

Fax: (+385 1) 48 72 487

E-mail: mladen.borsic@hmd.tel.hr

The OIML is pleased to welcome the following new

## CIML Members

Albania

Mr. Bashkim Koçi

Slovenia Dr. Ivan Skubic

(Saint-Jean-de-Luz, France)

United Kingdom Dr. Jeff Llewellyn

2002. 09.26-27

## OIML Meetings

SEMINAR:

What will legal metrology be in the year 2020?

2002. 09.30-2002.10.04 (Saint-Jean-de-Luz, France)

DEVELOPMENT COUNCIL MEETING 37TH CIML MEETING

October 2002 Delft (The Netherlands) Date to be confirmed

OIML TC 5/SC 1 Electronic Instruments

## Committee Drafts

received by the BIML, 2002.02.01-2002.04.30

<table border="1"><tr><td>Framework for a Mutual Acceptance Arrangement (MAA) on OIML Type Evaluations</td><td>E</td><td>9CD</td><td>TC3/SC5</td><td>USA</td></tr><tr><td>Revision of R87:Net quantity of product in prepackages</td><td>E</td><td>3CD</td><td>TC6</td><td>USA</td></tr><tr><td>Revision of R100:Atomic absorption spectrometers for measuring metal pollutants in water</td><td>E</td><td>1CD</td><td>TC16/SC2</td><td>USA</td></tr><tr><td>Revision of R116:Inductively coupled plasma atomic emission spectrometers for measurement of metal pollutants in water</td><td>E</td><td>1CD</td><td>TC16/SC2</td><td>USA</td></tr><tr><td>Light absorption spectrometers for medical laboratories</td><td>E</td><td>3CD</td><td>TC18/SC5</td><td>Germany</td></tr></table>

www.oiml.org

Stay informed