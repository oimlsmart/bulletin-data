![](page=0,bbox=[185, 196, 970, 318])

![](page=0,bbox=[1521, 143, 1855, 565])

Bernard Athané Former BIML Director, 1974-2001

<div align="center">

# Thoughts for the future

</div>

t is always wise to look ahead, but difficult to look further than you can see, Knut Birkeland (CIML Immediate Past-President) used to say, quoting Winston Churchill.

From this point of view, the OIML Seminar 'What Will Legal Metrology Be In 2020' organized by the BIML in September 2002 in conjunction with the 37th CIML Meeting, may constitute either a far-sighted attempt to help the OIML cope successfully with the rapid (and sometimes erratic) changes in our world, or just an agreeable game of prediction without any real consequences since, after all, many of us will be out of the legal metrology circuit within eighteen years.

The fact that I have accepted with pleasure the responsibility of chairing this Seminar shows that I do not consider 2020 as being 'further than we can see'. Legal metrology is, just as measurement standards are, a rather stable activity: it would be a nonsense to change legal metrology requirements too frequently, obliging instrument manufacturers to permanently adapt their production to these changing regulations. On the other hand, legal metrology must constitute a general framework specifying the essential metrological performance of measuring instruments subject to legal control, within which manufacturers may develop new designs, new measurement methods, and commercialize - over appropriate periods of time - instruments that meet the essential requirements.

As clearly shown by the Seminar program, legal metrology and the OIML will face a number of developments during the next ten or twenty years, including:

- technological progress with the development of 'intelligent' instruments that are able to detect and compensate for their own inaccuracies;

- worldwide and regional politico-administrative changes with an increasing globalization of our world and, in parallel, an accelerated development of regional integration;

- financial restrictions on public budgets;

- the need for efficient consumer protection;

- the use of manufacturers' quality systems; and

- participation in the establishment of a global measurement system, while facing the need for ensuring measurement reliability in an increasing number of human activities.

Because of printing deadlines, I am writing this Editorial some weeks before the Seminar takes place - to be precise, at the beginning of August. Let me, however, try to make a rather short-term prediction and repeat my conviction that the output of this event, as a continuation of the planning exercises carried out in the past, will constitute an appropriate basis for the adaptation of the OIML and of legal metrology, at both national and regional levels, to the requirements of our changing world.

UNCERTAINTY OF MEASUREMENT

<div align="center">

# Method for calculating the coverage factor in calibration

</div>

PAWEL FOTOWICZ, General Metrology Division Central Office of Measures, Poland

## 1 Introduction

In accordance with the provisions of the European Cooperation for Accreditation, the expanded uncertainty of measurement in calibration should be expressed for a coverage probability of approximately 95% [1]. In cases where a normal distribution can be attributed to the measurand and the standard uncertainty associated with the output estimate has sufficient reliability, the standard coverage factor k=2 shall be used. The assumption of normal distribution cannot always be easily confirmed. The standard coverage factor k=2 can yield an expanded uncertainty corresponding to a coverage probability different to 95%. The use of approximately the same coverage probability is essential whenever two results of measurement of the same quantity have to be compared, e.g. when evaluating the results of an interlaboratory comparison or assessing compliance with a specification. In these cases, in order to ensure that the value of the expanded uncertainty is quoted corresponding to the same coverage probability as in the normal case, another method has to be employed.

In the reference publication EA-4/02 (supplement 2), two approximation methods for coverage factor calculation are proposed. One method relies on approximation of the output quantity distribution by a rectangular distribution in cases where a dominant contribution in the budget is a quantity having a rectangular distribution. In this situation the coverage factor is k=1.65 for a coverage probability of 95 %. The second method relies on approximation of the output quantity distribution by a trapezoidal distribution in cases where dominant contributions in the budget are two quantities having rectangular distributions. In this situation the coverage factors are from k=1.65 to k=1.9 for a coverage probability of 95 %. The value of the coverage factor depends on the ratio of the uncertainty of the dominant contributions and is given by:

$$
k = \sqrt {\frac {3 (r + 1) ^ {2}}{r ^ {2} + 1}} \left(1 - \sqrt {\left(1 - p\right) \frac {4 r}{(r + 1) ^ {2}}}\right) \quad \mathrm {f o r} 1 \leq r \leq 1 0
$$

where:

p = coverage probability

$$
r = \left| \frac {u _ {1} (y)}{u _ {2} (y)} \right| = \mathrm {r a t i o f t h e d o m i n a n t c o n t r i b u t i o n s}
$$

$$
u _ {1} (y) \mathrm {i} u _ {2} (y) = \mathrm {d o m i n a n t u n c e r t a i n t y c o n t r i b u t i o n s}
$$

These methods do not solve the problem in the general case where there are several contributions in the budget with normal and rectangular distributions having various standard uncertainties, but nondominant terms. In this situation the conditions of the Central Limit Theorem are not met and it cannot be assumed that the distribution of the output quantity is normal. The output quantity distribution is the convolution of rectangular and normal distributions (R $ ^{*}N $ distribution).

## 2 Approximation of the convolution of rectangular and normal distributions by a symmetrical trapezoidal distribution

The coverage factor for a trapezoidal distribution given by (1) can be presented as a function of ratio r, as in Fig.1. It can be illustrated by the curve $ k_{T} $ . If r is the ratio of standard deviations of convolved rectangular and normal distributions, it may show the curve $ k_{RN} $ for the distribution resulting from the $ R^{*}N $ convolution on the basis of the coverage factor value presented in Reference [3]. The difference between values of coverage factors k for the trapezoidal distribution and for the $ R^{*}N $ distribution are small; its variability is presented in Fig. 2. The curve in this Figure shows the difference of coverage factors $ k_{T} $ and $ k_{RN} $ given by:

$$
\delta_ {\mathrm {T}} = \frac {k _ {\mathrm {T}} - k _ {\mathrm {RN}}}{k _ {\mathrm {RN}}} \cdot 100 \%
$$

The deviation $ \delta_{T} $ does not exceed $ \pm1.5\% $ for a coverage probability of 95 %. This approximation can be compared with the one resulting from the traditional standpoint, in other words with the approximation of a coverage factor for $ R^{*}N $ distribution by a coverage factor for normal distribution or for rectangular distribution. This situation is presented in Fig. 3, which represents the functions of coverage factor deviations for $ R^{*}N $ distribution approximated by normal distribution $ (\delta_{N}) $ , by rectangular distribution $ (\delta_{R}) $ and by trapezoidal distribution $ (\delta_{T}) $ . The suitable functions are formulated by:

![](page=2,bbox=[242, 270, 1778, 1207])

<div align="center">

Fig.1 Coverage factor functions for a coverage probability of 95 %

</div>

![](page=2,bbox=[236, 1498, 1793, 2418])

<div align="center">

Fig. 2 Function of deviation $ \delta_{\mathrm{T}} $ for a coverage probability of 95 %

</div>

$$
\delta_ {\mathrm {N}} = \frac {k _ {\mathrm {N}} - k _ {\mathrm {RN}}}{k _ {\mathrm {RN}}} \cdot 100 \%
$$

$$
\delta_ {\mathrm {R}} = \frac {k _ {\mathrm {R}} - k _ {\mathrm {R N}}}{k _ {\mathrm {R N}}} \cdot 100 \%
$$

where:

$ k_{\mathrm{N}} $ = the coverage factor for a normal distribution $ k_{\mathrm{R}} $ = the coverage factor for a rectangular distribution

The above consideration implies the conclusion that the best accurate approximation of the $ R^{*}N $ distribution is a trapezoidal distribution in the range from r=1 to r=10. It should be expected in other ranges of r that the good approximation of the $ R^{*}N $ distribution is a normal distribution for r<1 and a rectangular distribution for r>10.

## 3 Principle of approximation of the distribution and of the coverage factor for output quantity in calibration

On the basis of Reference [3] the coverage factor given by the R*N distribution for a coverage probability of 95 % can change in the range from k = 1.65 to k = 2 (exactly k = 1.96). Those extreme values correspond to the coverage factor given by the rectangular distribution and by the normal distribution. The other value of the coverage factor corresponds to the "intermediary" distribution between the rectangular and normal distributions.

Those "intermediary" distributions are the convolutions of rectangular and normal distributions (R*N distributions) with a different parameter r (ratio of the standard deviation of the rectangular distribution to the standard deviation of the normal distribution). From Fig. 1 it can be noted that the curve $ k_{RN} $ is close to the curve $ k_{T} $ in the range of r from 1 to 10. The trapezoidal distribution is the convolution of two rectangular distributions. This implies the conclusion that each convolution of the rectangular and "intermediary" distributions gives a k function close to the $ k_{RN} $ and $ k_{T} $ functions. Therefore, using an approximation of the convolution of the rectangular and "intermediary" distributions by trapezoidal distribution involves the error of approximation of the coverage factor for this convolution not larger than for the cases where the coverage factor $ k_{RN} $ is approximated by the coverage factor $ k_{T} $ . The "intermediary" distribution may be the convolution of several rectangular and normal distributions. For instance the coverage factors at the coverage probability of 95 %:

- given by the convolution of three identical rectangular distributions is k=1.94 [2],

- given by the convolution of two identical rectangular distributions is k=1.90,and

- given by the convolution of the normal and rectangular distributions with equal standard deviations is k=1.92 [3].

On the basis of this analysis the following principle of approximation of output quantity distribution can be formulated: for the output quantity $ Y=c_{1} X_{1}+\ldots+c_{N} X_{N} $ where all input quantities $ X_{1},\ldots,X_{N} $ are independent and the quantity $ X_{i} $ having a rectangular distribution with the largest contribution $ u_{i}(y)=c_{i} u(x_{i}) $ satisfies the condition:

$$
\left| u _ {i} (y) \right| \geq \sqrt {u _ {\mathrm {c}} ^ {2} (y) - u _ {i} ^ {2} (y)}
$$

the best approximation of the output quantity distribution is a trapezoidal distribution or a rectangular distribution, independently from the distributions of other input quantities. In other cases the best approximation of output quantity distribution is a normal distribution.

The following coverage factor formulae can be deduced:

$$
\begin{array}{l} k = k _ {N} \mathrm {f o r} 0 \leq r < 1 \\ k = k _ {\mathrm {T}} \mathrm {f o r} 1 \leq r \leq 1 0 \\ k = k _ {R} \mathrm {f o r} r > 1 0 \\ \end{array}
$$

where:

$$
r = \frac {\left| u _ {i} (y) \right|}{\sqrt {u _ {\mathrm {c}} ^ {2} (y) - u _ {i} ^ {2} (y)}}
$$

$ u_{i}(y)= $ the largest contribution of the input quantity having a rectangular distribution

$$
k _ {\mathrm {N}} = \mathrm {c o v e r a g e f a c t o r f o r a n o r m a l d i s t r i b u t i o n}
$$

$$
k _ {T} = \mathrm {c o v e r a g e f a c t o r f o r a t r a p e z o i d a l d i s t r i b u t i o n}
$$

$$
k _ {R} = \mathrm {c o v e r a g e f a c t o r f o r a r e c t a n g u l a r d i s t r i b u t i o n}
$$

$$
k _ {\mathrm {T}} = \sqrt {\frac {3 (r + 1) ^ {2}}{r ^ {2} + 1}} \left(1 - \sqrt {\left(1 - p\right) \frac {4 r}{(r + 1) ^ {2}}}\right)
$$

$$
k _ {\mathrm {R}} = \sqrt {3} p
$$

p = coverage probability

## 4 Summary

The method presented for approximating the coverage factor of the convolution of rectangular and normal distributions has been applied. The function of an

![](page=4,bbox=[240, 261, 1781, 1184])

<div align="center">

Fig. 3 Functions of deviations $ \delta_{N} $ $ \delta_{T} $ and $ \delta_{R} $ for a coverage probability of 95 %

</div>

![](page=4,bbox=[242, 1511, 1791, 2436])

<div align="center">

Fig. 4 Function of the error of the approximation method of the coverage factor in calibration

</div>

approximation error of the method defined by the formula is presented in Fig. 4:

$$
\delta = \frac {k - k _ {\mathrm {R N}}}{k _ {\mathrm {R N}}} \cdot 100 \%
$$

The maximum value of the error for the full range of r lies in the range $ \pm2\% $ . Therefore this value of error is not larger than the value of error that occurs when the approximation is made using the normal distribution and consequently coverage factor k=2 at a coverage probability of 95%

The method presented for approximating the output quantity distribution rendered possible an accurate estimation of the coverage factor for many input quantities having normal, rectangular and "intermediary" distributions. The method presented ensures a coverage probability of approximately 95% for expanded uncertainty evaluation in calibration. The method may be applied in procedures for calculating the uncertainty of measurement in calibration.

## References

[1] Expression of the Uncertainty of Measurement in Calibration. Publication Reference EA-4/02, December 1999

[2] Guide to the expression of uncertainty in measurement (GUM), BIPM, IEC, IFCC, ISO, IUPAC, IUPAP, OIML, Corrected & Reprinted Edition, 1995

[3] C.F. Dietrich: Uncertainty, Calibration and Probability. The statistics of Scientific and Industrial measurement. Second edition. Adam Hilger. Bristol, Philadelphia and New York, 1991

SEMINAR 2020

![](page=6,bbox=[731, 246, 1012, 432])

<div align="center">

# The face of legal

</div>

<div align="center">

# metrology in South Africa and its possible influence in Africa supporting the New Program for African Development (NEPAD)

</div>

STUART CARSTENS - Director, Legal Metrology Department, SABS (South Africa)

## 1 Overview and current situation

## 1.1 South Africa

Weights and Measures was introduced in South Africa by the Dutch during their occupation in the 1600's. During the British occupation acts were passed in all the colonies and in 1923 a National Department was established in the Department of Mines and Industry. In 1991 the function was transferred to the SABS.

With this transfer, a decision to develop into legal metrology was made. A position plan was drawn up and submitted to Government and two reviews were undertaken to establish the exact position of legal metrology and make any recommendations deemed necessary.

In South Africa the legal metrology arena is presently only regulated in the trade sphere by the Trade Metrology Act and Regulations. The structure at present is as below.

## 1.1.1 Legal / legislative process

Figure 1 depicts the legislative framework that is used in South Africa; this framework is internationally acceptable. The legislator in South Africa is the Department of Trade and Industry.

Legal metrology obtains its mandate through the SA Constitution, Trade Metrology Act and Regulations and National Measuring Units and Measuring Standards Act. The Regulator is the South African Bureau of

Standards (SABS), which in turn is appointed by the Minister of Trade and Industry as the national responsible body for legal metrology.

## 1.1.2 Administrative processes

## Type Approval

The Type Approval Issuing Authority is the SABS. Type approval testing is also conducted by the SABS in its ISO 17025 accredited test laboratory but test results from competent laboratories are accepted.

## Verification

The verification function is undertaken by private companies accredited by the National Accreditation Body to SABS 0378 which relates ISO 17025 to legal metrology. The approval to verify is granted to these laboratories by the Director of Trade Metrology in terms of the Trade Metrology Act after the accreditation certificates are evaluated to establish conformance to legal metrology requirements.

In South Africa we have not only allowed private companies to perform initial verification, but have also allowed them to do subsequent verification which to the best of our knowledge is not common practice internationally.

The SABS also carries out verification, primarily in areas/types of instruments not serviced by the private sector to ensure a holistic and comprehensive service is provided.

## Calibration of verification standards

The calibration of verification standards may be done by any accredited laboratory (ISO 17025) with an acceptable best measurement capability.

The SABS has five accredited laboratories for calibration of mass and volume verification standards, situated in Pretoria, Cape Town, Durban, Port Elizabeth and Bloemfontein and there are presently four private laboratories that carry out calibration on verification standards of mass and one for volume, besides the National Metrology Laboratory (NML).

## Inspections

Inspection of commodities and measuring instruments is done by the SABS and the inspection function performed by the regional offices is accredited to ISO 17020 by the National Accreditation Body.

This function is undertaken by the regulator on behalf of government. South Africa is at present an OIML Member State and a founder member of SADCMEL.

South Africa is presently actively involved within SADCMEL with the harmonisation of legislation, as required by the SADC Trade Protocol, to enhance cross border trade within the area.

South Africa is also actively involved in the acceptance of OIML Recommendations as South African Technical Regulations to bring us into line with international requirements.

The co-operation will ensure harmonised technical regulations and effective implementation to give effect to the NEPAD aims.

## Training

The functional training is presently done in house as there is no institution that offers a course in legal metrology due to the small numbers being recruited at present. We are currently looking at having courses registered with the South African Qualification Authority. The entrance level for verification officers and inspectors is Grade 12 with maths and science and for Type Approval Officers, a National Diploma.

![](page=7,bbox=[993, 287, 1849, 817])

<div align="center">

Fig. 1 The legislative framework used in South Africa

</div>

## Maintenance of legislation

The regulator advises the Minister on any changes that need to be made to legislation after it has consulted with all role players. Technical Regulations are developed in the form of National Standards in line with WTO requirements. Technical Committees are in place to adopt OIML Recommendations wherever possible.

Matrix 1 gives various administrative processes and the institutions responsible for their implementation, and Figure 2 shows the present administrative processes.

<table border="1"><tr><td></td><td>SABS Regulator</td><td>Private verification laboratories accredited to ISO 17025</td><td>SABS regional offices ISO 17020&amp;17025</td><td>SABS calibration laboratories ISO 17025</td><td>Private calibration laboratories ISO 17025</td></tr><tr><td>Type approval</td><td>$\times$</td><td></td><td></td><td></td><td></td></tr><tr><td>Verification</td><td></td><td>$\times$</td><td>$\times$</td><td></td><td></td></tr><tr><td>Inspection</td><td></td><td></td><td>$\times$</td><td></td><td></td></tr><tr><td>Calibration of verification standards</td><td></td><td></td><td></td><td>$\times$</td><td>$\times$</td></tr><tr><td>International/Regional liaison</td><td>$\times$</td><td></td><td></td><td></td><td></td></tr><tr><td>Training</td><td>$\times$</td><td>$\times$</td><td>$\times$</td><td></td><td></td></tr></table>

Matrix 1 The various administrative processes

## 1.1.3 Economic overview

South Africa is regarded as an emerging first world economy and has a developed country infrastructure in the following areas:

- Telecommunications;

- Electricity (lowest industrial electricity rates in the world);

- Roads and ports;

- Railroad;

- Air transport.

![](page=8,bbox=[122, 850, 1011, 1504])

<div align="center">

Southern African Development Community (SADC) Map

</div>

<table border="1"><tr><td>Present status</td><td>Countries</td></tr><tr><td>Almost no legal metrology legislation or infrastructure</td><td>Angola Lesotho Mozambique</td></tr><tr><td>National legislation (not SADC harmonised) and regulatory control of simple/basic instruments for mass, volume, and length and of goods</td><td>Botswana DRC Malawi Namibia Seychelles Swaziland Tanzania Zambia</td></tr><tr><td>National legislation (not SADC harmonised) and regulatory control (inspection and verification) of more sophisticated instruments for mass, volume and length of goods</td><td>Mauritius South Africa</td></tr></table>

The seven ports handle in the order of 13 000 vessels and 500 million tons of cargo per year.

Matrix 2 SADC - Overview

The value of exports and imports with the EU and SADC are as follows:

- Imports from EU R68 122 million;

- Exports to EU R66 312 million;

- Exports to SADC R14 418 million.

## 1.2 Situational overview in Southern Africa

A map of the Southern African Development Community (SADC) is shown opposite, and the current status of the structures in each country are indicated in Matrix 2.

Most SADC countries still have the legal metrology system originally entrenched in the colonial era with predominantly Central Government control and no use of accredited inspection, verification or conformity assessment bodies.

## 2 Drivers for change

The drivers for change that are indicated below will result in South Africa progressing from the present trade metrology infrastructure to a full legal metrology infrastructure which will result in us including things such as:

- Medical measuring equipment;

- Utility meters;

- Environmental measuring instruments;

- Speed measuring device;

- Breath alcohol measuring devices.

A decision to regulate the whole spectrum of legal metrology was made in principle in 1998 and the SQAM review (Standards, Quality Assurance, Accreditation and Metrology) reaffirmed this decision. A draft of the new Legal Metrology Act is to be submitted to government and it is envisaged that it will be promulgated in 2003.

## 2.1 Standards, Quality Assurance, Accreditation and Metrology (SQAM) Review

The SQAM Review commissioned by the Minister of Trade and Industry was tasked to investigate the status of the four SQAM disciplines and then to make recommendations to the Minister on what interventions need

![](page=9,bbox=[316, 300, 1489, 1297])

<div align="center">

Fig. 2 The present administrative processes in South Africa

</div>

to be taken to bring the SQAM structures within South Africa in line with international norms. The review identified areas in need of attention, the most important being the control of the measuring instruments indicated above.

The SQAM Review made far reaching recommendations for legal metrology, namely:

(i) The creation of an Office for Regulatory Reform. The purpose of this proposed Office is to: (i) review existing approaches for formulation of technical regulations contained in legislation and legislative instruments, and develop a best practice approach for technical regulation formulation; (ii) conduct a comprehensive review of existing technical regulations contained in legislation, including legislation relevant to trade and legal metrology; (iii) require that regulatory impact assessments be compulsory for all future formulation of technical regulations; (iv) establish the principles for any regulatory marks used in South Africa; and (v) monitor any potential abuses of such regulatory marks and conformity assessment marks in both the voluntary and mandatory sectors.

(ii) A legal metrology framework embodying international practices for control of measurements be established by the proposed Office of Regulatory Reform as part of the general framework of technical regulations.

(iii) Responsibility for enforcement of trade metrology be returned to national government, and the function not be devolved to provincial governments until such time as they have the necessary resources to address the responsibilities.

(iv) A Trade Metrology Unit be established within DTI to take responsibility for coordination of the national system of trade metrology, including overall administration of the Trade Metrology System.

(v) The proposed Office of Regulatory Reform to advise on the necessary legislative changes to implement a re-distribution of trade metrology functions.

(vi) OIML Recommendations be adopted wherever applicable to satisfy the provisions of legal (including trade) metrology. Specifications from other sources be used only in exceptional cases

where the OIML Recommendations do not cover particular South African requirements.

(vii) South Africa must continue to participate in the drafting of OIML Recommendations, including attending the international meetings of committees that are drafting Recommendations of direct relevance to South Africa. These national interest activities be funded.

(viii)The proposed Trade Metrology Unit of the DTI undertake an urgent review of funding requirements to restore trade measurement inspection functions in the Provinces, and sufficient funds immediately be allocated by Government to reestablish this function under centralized control.

## 2.2 SADC Protocol on Trade

## Objectives

- To further liberalise intra-regional trade in goods and services.

- To ensure efficient production within SADC.

- To contribute towards the improvement of the climate for domestic cross-border and foreign investment.

- To enhance the economic development, diversification and industrialization of the Region.

- To establish a Free Trade Arena in the SADC Region.

- To achieve the objectives of the SADC protocol the following interventions are needed within the legal metrology arena:

- All technical barriers to trade (TBTs) are to be removed.

- Standards and Technical regulations are to be harmonised.

To ensure that the above is achieved SADC formed a SQAM forum and each discipline formed its own regional organization. The legal metrology cooperation forum SADCMEL was formed in 1996. The other forums are SADMET (NML), SADCSTAN (Standards) and SADCA (Accreditation).

## 2.2.1 SADCMEL

## The aims of SADCMEL are:

- Labelling, tolerances and standard pack sizes for prepackages.

- Requirements for instruments and adherence to OIML Recommendations wherever possible.

(i) Harmonisation of legal metrology legislation to promote and ensure compatibility with international requirements. Specific areas for harmonisation include:

- Instrument verification and calibration techniques.

- Type approval testing and issuing of approval certificates.

(ii) Organisation of training programmes.

(iii) Arranging of inter-comparisons to ensure uniformity.

(iv) Exchange of metrology related information and assistance where possible.

## 2.3 WTO/TBT Agreement

The WTO/TBT agreement requires - amongst others - the following:

(i) Technical regulations be placed on the web for international comment.

(ii) One stop type approval testing by approved test house (OIML MAA scheme).

(iii) Use of international standards as technical regulations wherever possible.

## 2.4 Advance in technology

New techniques require new and expensive test equipment, which may not be economically viable, for each country to purchase. This will involve using management systems to reduce costs to governments and using other countries in the region to perform certain tests for the other SADC members.

## 2.5 Developments in Africa

(i) The development of other trading blocks similar to SADC, Comesa and the East African Union which will all need to be linked if NEPAD is to succeed.

(ii) The dissolving of the OAU and the creation of the African Union.

## 2.6 New Program for African Development (NEPAD)

The New Program for African Development was developed out of the Millennium Africa Project and is

intended to lift Africa out of its present socio-economic plight and to place countries both individually and collectively on a path to sustainable development and at the same time to participate actively in the world economy. To meet the NEPAD objectives it is also important that the socio-political aspects be considered and that countries practice good governance ensuring a sound base on which to build.

The objectives and outcomes are as follows:

## Objectives:

- Eradicate poverty.

- Place countries of Africa both individually and collectively on a path of sustainable growth and development.

- Halt the marginalisation of Africa in the globalisation process.

## Expected outcomes:

- Economic growth and development and increased employment.

- Reduction in poverty.

- Diversification of productive activities, enhanced international competitiveness and increased exports.

- Increased African integration.

To achieve the objectives of NEPAD an action plan was devised encompassing the following:

- Ensuring conditions for sustainable development.

- Identification of sectoral priorities.

- Mobilisation of resources.

- Establishment of new global partnership.

- Implementation of the new partnership for Africa's development.

## 2.6.1 The role of legal metrology in support of SADC/Africa developmental goals (NEPAD)

There are many areas within the NEPAD action plan in which legal metrology will have to play a vital role and they are listed below.

## Energy

Legal metrology needs to become involved in the sale of energy domestically as well as within Africa. Examples of this are the proposed gas pipe line from Mozambique to South Africa and Eskom, the South African electricity supplier's expansion into Africa to utilize energy sources such as Cahora Bassa hydroelectric scheme in Mozambique and to improve the electricity network in Africa using all available resources.

## Transport

Legal metrology's involvement in this area would be to ensure that legislation is in place to control the overloading of vehicles. These technical regulations, which would require weighbridges used for weighing road vehicles to be approved and verified at regular intervals, will ensure the national road network is not damaged due to the overloading of vehicles which is a problem at present. Breath alcohol and speed measurement instruments will also be covered in the proposed regulations. These regulations give confidence in the measurements made, resulting in a reduction in the number of disputes.

## Water and sanitation

The legal metrology involvement in this area will be the instruments used in the sale of water. Domestic water metering is already regulated within South Africa and we will have to concentrate on the pre-pay systems now being developed which include communal standpipes for rural water supply. We foresee this will become the norm in Africa. A standard for electronic pre-pay systems has already been written and these instruments will be approved and verified.

The supply and sale of water in irrigation schemes is also an area which will have to be addressed in a similar manner.

## Health

In this area the involvement is the same as elsewhere namely the creation of technical regulations and the approval and verification of medical instruments.

## Agriculture

Ensure that technical regulations are in place to give confidence in the measurement of agricultural products assuring farmers of a fair deal and creating a sound basis for government to collect excise duties reducing the burden on the fiscus. Instruments for quality related measurements such as moisture meters will be included.

## Environment

This area is a politically sensitive area at the moment due to the pollution generated by industry and if rebates are to be considered as reward for countries who reduce emissions or sanctions are imposed, then legal metrology needs to be involved in the measurement of such emissions.

## Mining

The same applies here as under agriculture.

## Manufacturing

The manufacturing arena is most probably the most important.

The aim of NEPAD is to encourage cross border trade, improve competitiveness. Technical regulations need to be in place to ensure that commodities are correctly filled and that measurements are accurate and traceable to National Standards.

By putting in place a Technical Regulation framework which meets international best practice and ensuring a uniform implementation which will in turn ensure an effective trade measurement system, Legal Metrology Departments in Africa will have assisted greatly in creating a solid basis from which NEPAD can grow.

The same can be said for legal metrology's role in fields such as mining, agriculture, the environment, etc.

It is my belief that without the support of an effective legal metrology framework, NEPAD will have difficulty realizing its objectives.

## 3 The face of legal metrology in South Africa by 2020

With the implementation of the recommendations of the SQAM review, South Africa will have a legal metrology infrastructure that will be able to meet the challenges placed on it by all the different drivers for change mentioned above.

## 3.1 Legal metrology legislative structure and systems

## 3.1.1 Legislative structure

The legislative process will have promulgated a Legal Metrology and Consumer Protection Act and the Technical Regulations required to cover all aspects of Legal Metrology by 2020.

amongst countries to accept instruments type approved in countries with the capability to type approve such instruments.

The legislative framework will be in accordance with the legislative framework shown in Fig.1 which will meet the requirements of the WTO and will be in line with international best practice.

## 3.1.2 Legal metrology system

- In line with the OIML MAA on type approval for certain instruments there will be agreements

- The proposed OIML "I" mark for prepacked goods will be adopted and implemented to promote cross border trade.

- The accreditation system for verification of measuring instruments will be adopted as a means of reducing government's costs of regulating.

3. 1.3 Legal metrology functions (Administrative processes)

## 3.1.3.1 Type approval

- Testing done once in the world (OIML MAA on acceptance of test results).

- SA to participate in OIML Certificate System for a number of instruments within own capabilities.

- If any member states of the SADC are not OIML Members they will have regional, bilateral or multilateral agreements in place to accept results.

- Private laboratories accredited to ISO 17025 or peer reviewed for the applicable tests and approved by the National Regulator will undertake type approval testing.

- The National Regulator will retain the role of issuing authority.

- More use will be made of component approval to allow the mix and match of components to construct instruments according to customer requirements. Compatibility tests and documentation evaluation will be done.

## 3.1.3.2 Verification

Verification will be privatised within South Africa by means of accreditation by the national accreditation body to SABS 0378 which is a standard based on ISO 17025 or current equivalent and tailored for use in legal metrology.

The privatisation of the verification of instrument function reduces the financial burden on the national regulator by reduction of personnel and equipment.

It is also envisaged that, with this accreditation process being applied uniformly throughout Africa using a common legal metrology standard against which accreditation takes place e.g. SABS 0378 (adopted as an African Union Standard) or current equivalent, verification officers will operate across borders where economically viable.

![](page=13,bbox=[437, 330, 1431, 1233])

<div align="center">

Fig. 3 The future administrative processes in South Africa by 2020

</div>

<table border="1"><tr><td></td><td>SABS REGULATOR</td><td>PRIVATE VERIFICATION LABORATORIES ACCREDITED TO ISO 17025</td><td>SABS REGIONAL OFFICES ISO 17025&amp;17025</td><td>SABS CALIBRATION LABORATORIES ISO 17025</td><td>PRIVATE CALIBRATION LABORATORIES ISO 17025</td><td>PROVINCIAL AUTHORITIES</td></tr><tr><td>Type approval</td><td>(X)√</td><td></td><td>√</td><td>√</td><td>√</td><td></td></tr><tr><td>Verification</td><td></td><td>(X)√</td><td>(X)√</td><td></td><td></td><td></td></tr><tr><td>Inspection</td><td></td><td></td><td></td><td></td><td></td><td>√</td></tr><tr><td>Calibration of Verification Standards</td><td></td><td></td><td></td><td>(X)√</td><td>(X)√</td><td>√</td></tr><tr><td>International/Regional liaison</td><td>(X)√</td><td></td><td></td><td></td><td></td><td></td></tr><tr><td>Training</td><td>(X)√</td><td>(X)√</td><td>(X)√</td><td></td><td></td><td></td></tr></table>

(X) = Present

$ \surd $ = Future

Matrix 3 The present and future situations

## 3.1.3.3 Inspections

All inspection bodies such as the SABS and Provincial authorities will be accredited to ISO 17020 or current equivalent, using harmonised legislation in the form of Technical Regulations published as Regional Standards based on OIML Recommendations.

An early warning system to alert other countries of nonconforming product or instruments, will be in place.

## 3.1.3.4 Calibration of verification standards

The calibration of verification standards will be done by laboratories accredited to ISO 17025 and that have an acceptable best measurement capability.

## 3.1.3.5 Training

South Africa through its process of having courses registered at the South African Qualification Authority (SAQA) will have an established training program in place.

## 3.1.3.6 International and regional legislation

South Africa will remain an active member of OIML and SADCMEL.

South Africa will have ensured that the Indian Ocean Legal Metrology Forum (IOLMF) has developed to its full potential and the creation of the South Atlantic Legal Metrology Forum (SALMF) in support of the OIML's aim to have regional organizations in place which will link the whole world.

## 3.1.4 Management processes

- Type approval testing.

The management processes will be in line with international norms. This will be achieved by using ISO standards in management systems and OIML Recommendations.

## 3.1.4.1 ISO17025

- Calibration of verification standards.

Laboratories undertaking the following processes will be accredited to ISO 17025:

## 3.1.4.2 ISO 17020

The following administrative processes will be accredited to ISO 17020:

- Inspection of prepacked goods.

## 3.1.4.3 SABS 0378

- Inspection of measuring instruments.

- Laboratories undertaking the following processes will be accredited to SABS 0378:

- Verification of measuring instruments.

## 3.1.4.4 SAQA (South African Qualification Authority)

All training will be registered with the South African Qualification Authority.

## 3.1.4.5 OIML MAA Scheme

The South African National Responsible Body will partake in the scheme. The SABS Type Approval laboratory and private laboratories will be designated as competent test laboratories.

## 3.1.5 Harmonisation

All legal metrology technical regulations in South Africa will be harmonised with international standards as is expected of OIML Member States.

4 The possible influence of developments in South Africa on SADC and Africa in 2020

The following can be seen as possible areas of influence of SADC and Africa in 2020:

- Legal metrology legislative structures put in place in South Africa could be accepted by other African Union member states.

- SADC member states have harmonised legislation in place.

- Legal metrology regional organizations such as Euro Mediterranean Legal Metrology Forum (EMLMF), Southern African Legal Metrology Cooperation (SADCMEL), Indian Ocean Legal Metrology Forum (IOLMF) and any others formed to include countries not affiliated to the above-mentioned should have finalised harmonisation of legislation in all the areas mentioned as vital to NEPAD's success.

- The administrative and management processes put in place in South Africa, which reduce the cost to government, will be accepted as an effective means of ensuring the effective implementation of legal metrology requirements throughout Africa.

- Type Approval testing be run under the OIML MAA scheme.

- Technical regulations will be published as Regional or African standards in line with OIML Recommendations.

- It is envisaged that there will be several training institutions providing courses in legal metrology such as the Tanzania College of Business Education and the SADC Resources Centre for Metrology Education. A uniform curriculum would be in place to ensure the same standard in all countries. It is additionally envisaged that a distance learning project will also be in place.

will support the ideals of NEPAD in South Africa and could be applied by all members of the African Union.

It is envisaged that the developments mentioned above and the legal metrology structures put in place

SADC will have implemented similar structures to ensure harmonisation of legislation as required by the SADC Trade Protocol.

## 5 Conclusion

South Africa will have an effective trade measurement system underpinned by an internationally acceptable legislative framework. The acceptance of OIML Recommendations as technical regulations and our administrative processes which are managed effectively by the use of ISO management standards will also instil confidence.

It is envisaged that the high ideals of NEPAD which are to ensure that Africa competes as an equal in the global arena will necessitate the African Union member states looking at implementing similar structures.

The advantages to Africa are:

- An international acceptable legal metrology framework.

- Basis for increased export of commodities.

- Confidence in measurements.

- Increased productivity.

- Increased job opportunities.

![](page=15,bbox=[781, 1742, 1111, 2163])

STUART CARSTENS Director, Legal Metrology Department, SABS (South Africa)

SEMINAR 2020

![](page=16,bbox=[730, 283, 1015, 470])

<div align="center">

# Progress and our genius for compromise

</div>

MARTIN BIRDSEYE

Director, International, NWML, United Kingdom

Metrological regulation is done largely by the control of measuring instruments and so it is concerned with the precise disciplines of metrology and engineering. In the development work of the OIML we also find a quite different discipline that depends on judgement and a long-term view of progress rather than a precise solution. In the global harmonisation of legal metrology there are compromises to be made. The acceptable solution is not always the best solution, but it is necessary to find the approach that will meet people's needs and aspirations. It is then possible to move forward, to make some progress.

The scope and power of this method is a major asset that we should be aware of. It is embedded in the Convention and procedures of the OIML.

The theme of this paper is to be the talent we have for reconciling many different national and regional perspectives in our work and the importance of understanding certain issues which could impede our progress. In this case our talents include not only personal abilities and good-will but also our collective, constitutional and procedural assets, and practical engineering logic that can sometimes make the right solution fairly obvious.

We must not ignore the scientific foundations of our work, and the need for technical investigations and development; but it is fair to say that progress in the OIML depends on agreement; that is agreement between Member States. One can see that there is already a high level of agreement on general objectives, but it is not easy to agree on how to attain the objectives. The steps on the way are quite complex. To reach agreement on a complex proposition there has to be a good understanding of the issues, usually involving technical, procedural and also "consequential" factors. Under the heading of consequences we should include, for example, the effects on manufacturers, traders and consumers everyone involved needs time to resolve their national economic and commercial priorities, and, we hope, the needs of their citizens.

So let us examine the means we have for making agreements and see what we might do to improve them. Agreement depends on consensus, together with confidence in the process, and a genuine commitment to implement decisions.

Firstly, agreements cannot be made by votes; there has to be a genuine meeting of minds - a consensus.

There is also a process. We have the means (the machinery) to take what may be no more than an idea from one person's mind and develop it through the structures and procedures of the organisation until we have a global agreement, established in writing. This is quite a remarkable process, and its ongoing success is a major achievement, especially for the facilitating role of the Bureau; but it cannot work well unless all participants are confident in it. We should not be content with structures and procedures until they engender confidence.

Then there must be commitment to the outcome. We are not involved in an academic exercise. Legal metrology is above all practical. Decisions that we make can affect the lives of ordinary people, everywhere. But agreements that do not lead to action may be worse than useless. Without a general commitment to implementation there is not only a denial of benefits to the citizen but also the possibility of establishing unfair advantage. These factors can lead to a justifiable reluctance to reach agreement.

So we need consensus, confidence and commitment.

We should have the courage to examine some of the problems or deficiencies that may inhibit confidence in the process. Then we should examine how things work out in practice, given time, established procedures and good will. What we find is encouraging, so much so that it should give us more confidence in the outcome and thus more commitment to the work.

In a seminar concerned with the future of legal metrology, we should keep in mind that there are two different dimensions or directions to the development work in the OIML, which can broadly be described as technical and procedural. On the one hand we develop Recommendations for control of particular measuring instruments or measurement processes, and on the other hand we develop the tools and machinery to reach agreements, and procedures for implementing them. Sometimes we find that agreement on procedural developments is more difficult, possibly because at this stage in the development of legal metrology, it is more important to us.

Deficiencies in the process may arise not of course from human failings but from the realities of culture politics, history and geography, and often from our eagerness for progress. Occasionally we see:

- Inadequate consultation;

- Cabalistic working groups;

- Apparently "unequal" votes;

- Asynchronous progress;

- Failures in implementation.

Adequate consultation is necessary, at both national and international level, but it is not easy, even in the days of e-mail. However, it is a vital part of reaching a real consensus which carries the confidence of all parties. We must accept that the time involved is considerable even when there are no unnecessary delays. In general, all parties should have an opportunity for consideration and comment and then to examine the comments and suggestions of all the others. We already have rules to this effect in the Directives for OIML Technical Work. Whatever we do to streamline procedures, we should not forget that confidence depends on open debate.

However, complex technical solutions do not generally come from open debate but from hard work in small teams. That is why we have working groups, where individuals can forget national priorities and concentrate on the creation of practical proposals. How far they should go before presenting proposals to their international committees is a matter for judgement, but it seems essential that all participating Member States should be kept informed of progress and be able to contribute as they wish. Unofficial networks can seem to be very effective, but they may be driven by national rather than technical priorities and they will be ineffective in the long-term if all parties are not confident in the outcome.

The term "asynchronous progress" refers to the fact that national and regional legislation must often be developed in a timescale appropriate to local priorities and therefore this is done independently of the OIML work upon which it should ideally be based. This is not always a bad thing. The world of technology and business moves on, and independent economies must react to it in accordance with the best available information, which may or may not be available in the form of the latest OIML Recommendation. Thus the OIML Recommendations must have an ongoing relationship to national and regional legislation. A prime example of the process may be found in the necessarily parallel but asynchronous development of the EU Measuring Instruments Directive (MID).

I have chosen what is possibly a contentious issue, to be the subject of a more detailed discussion. For convenience I call it the problem of "unequal votes".

Unequal votes may appear to be impossible. We have almost an excess of democracy - one country one vote and usually several stages of voting and approval. However, votes appear to be "unequal" if we suspect, for example, that one country, one policy one vote, is effected as: one region, one policy, 14 votes. Our North American friends will recognise this phenomenon, and Europeans colleagues should recognise it. As an intergovernmental organisation, the OIML necessarily works

at the level of sovereign states. The notion of equality among Member States is very important to us. For various reasons it is acceptable, some would say essential, to have equality in this forum, even when there are manifestly huge differences in the economic, demographic and geographical size of the Member States. Where there could be a problem however, is the situation where some of the sovereign Member States find themselves constitutionally linked, so that while retaining their separate votes they might be effectively bound to one policy by common legislative measures. You will of course know that I am talking of the natural concern that other industrialised economies have about the development of the MID in Europe. There may in fact be no real problem here, but it is an issue of fairness and common sense that could threaten our common cause if it is not explained or resolved.

I feel bold enough to raise this issue because, firstly I think that there is some obligation on the Europeans to consider an issue about Europe that concerns their international colleagues, and secondly I see that in practice there are many remedial factors in the situation and we find that the outcome is not as we may have perceived it to be. Thirdly it raises so many other points about how we work that it serves as an agenda for a discussion of the constitutional and procedural strengths of the OIML and a long-term approach to progress.

I am not advocating or contemplating any constitutional change. We can see plenty of examples in the world as a whole where, in spite of there being much greater need and real urgency, the lawyers and political scientists have failed to solve constitutional problems. In Europe we have many ingenious constitutional developments, including QMV - qualified majority voting, but these things are hugely complicated and still evolving after fifty years. Constitutional amendments are not for us here, certainly not in this forum.

That leaves us broadly with three other angles to consider: legal, logical and practical. Having in mind that the answers should all be consistent, and that we have very limited time here, I shall leave aside the legal enquiry for now, consider briefly the logical approach (to see if there may be a real problem) and concentrate on the practical approach. We will be encouraged to find that there are so many practical courses of action, designed to facilitate progress.

Logically, the "unequal votes" problem should only be a real problem if there are practical circumstances where Member States of the EU would be legally constrained by a European Directive to a point of view that is against their own national priorities. If this is not the case then they can make their own policy along with any other Member State. So the question is: could a Member State support a Recommendation that is inconsistent with an existing Directive?

Logically the answer is Yes; because we are talking of a Recommendation, to which there is, according to Article 8 of the Convention, a moral obligation for implementation where possible. That gives exactly the flexibility we need. Note that in practice it is a flexibility over time; it turns the problem of asynchronous development into an advantage. If national and regional legislation must logically follow the OIML Recommendations then, by the nature of development, there will be differences and scope for improvement at each stage.

In the case of the MID, the relevant OIML Recommendations were, quite rightly, the starting point for the specific instrument requirements, but the regulatory procedures have been developed and the performance requirements refined to some extent. This was necessary, where for example, performance requirements were not yet adequately defined by OIML Recommendations. Europeans will not be inhibited from contributing to further improvements developed in the forum of the OIML, which, in turn could eventually be incorporated into European legislation. (Incidentally, in some cases this can be done by a committee procedure and Commission Directives, avoiding the need for negotiating amendments to the main Directive.)

So, by simple logic in application of the most basic principles of the OIML Convention, we can see that "unequal votes" are probably not a real threat to anyone; and, moreover, we have other, more powerful and practical ways of dealing with this kind of problem:

- Common sense;

- Mutual respect;

- Individual responsibility;

- Good faith;

- Engineering solutions;

- Scientific facts;

- A long-term view; and

- Common objectives.

We should look at the ways we work to see how some of these factors are applied, and this will, incidentally, lead us to a view of where we are going - where will legal metrology be in 2020.

First there is a matter of common sense and good faith. A rather unusual, perhaps unique feature of the OIML Convention is that Member States "shall be morally obliged to implement [Conference] decisions as far as possible." What is the legal status of a moral obligation? I think that a moral obligation is less binding but more useful than a legal obligation. Without a legal requirement or a rigid timetable for implementation, Recommendations can more easily be developed to the point where they are universally acceptable and yet still achieve the necessary level of harmonisation in the longterm. In effect they specify the performance requirements and define the direction of development.

Generally speaking, if we decide where we are going then we are more likely to make progress!

The work of the OIML is intrinsically linked to progress. Long-term development goes on regardless of local progress or national priorities. Technical Committees work to develop and revise Recommendations in a well-defined framework that is, in principle, quite independent of legislative projects in individual Member States and regions. As we have seen it is an asynchronous process which may seem inefficient to an impatient or legalistic mind. We can see it as natural that there should be supportive developments at various levels and regions, that are not exactly in phase. Regional development is now fully supported by the OIML - it is a part of the process.

Thirdly we have respect for and confidence in each other. Individuals can always have in their mind a right or logical solution, and this can lead them to the right way of applying national policy; indeed it enables them to contribute to the development of national policy. The normal everyday development procedure of the OIML provides a framework in which these things can happen. A well-structured logical document has a power of its own - national and regional priorities have relatively little influence when the long-term answer is fairly obvious and when the constitutional commitment is one of principle rather than legal observation. In this way individuals and Member States can function as independent voices.

There is also scope for creative compromise at a more technical level. A classic example is the concept of optional classes for specifying limits of error for measuring instruments. In general, where there is a range of requirements or where it is possible that performance will be enhanced by technological development, then the role of an OIML Recommendation is to provide the framework for specification and control of instruments, rather than a rigid prescription. The task then is to define a practical series of accuracy classes upon which Member States can base their legislation and into which manufacturers can aim their products. In effect we aim for harmonisation of development as a means towards harmonisation of regulation.

Technology is increasingly helpful when we seek scope for practical compromise. Software is powerful and memory is so cheap, that flexibility can be built in at very low cost. Thus it can be acceptable to require that a measuring instrument type shall have a range of functionality, enough to satisfy diverse national requirements, without placing a significant burden on the manufacturers. In time we may find that the national requirements are reconciled. One approach may become the norm, but in the meantime the OIML Recommendation will have been serving both or several parties, providing the means to move forward in the most logical direction.

In general our task is always to have a long-term view, to look further ahead to what is really the most efficient solution. Jean Monnet, who inspired the creation of the European Union, said that "major changes can be achieved if men's minds can be directed to the point where their interests converge. That point always exists, but it takes trouble to find it." If we look far enough ahead we can find it. In nearly all of the points I have made in this paper, time is an important factor. We need a long-term view.

The OIML itself could be viewed as a long-term project. "Long-term" because of the factors discussed above, and indeed a "project" because it has well-defined objectives which may ultimately be more or less achieved. To see where we are going in terms of international legal metrology, one might look at the position in some of the Member States where there is already an established structure of consistent metrological regulation. However, one might also find that, as Mr. Birkeland said of many of the Member States, there will still be inadequate co-ordination between the technical disciplines and administrative groupings.

Ultimately, the OIML will need to go on working in three areas:

- To maintain the established operational structures and documentation;

- To develop new machinery in response to the needs of continued technical, economic and social progress; and

- To respond to the continued evolution and rationalisation of government.

Perhaps in this era of globalisation we are at the peak of activity and by 2020 the workload will be declining or almost done. It seems likely that on a scale related to achievement of objectives, we can predict a natural growth curve which will be something like the curve shown in Fig.1 and the corresponding workload could then be represented by the differential of the curve in Fig.2.

So there is a broad peak of activity while all the main global objectives are achieved and this is followed by a lower workrate corresponding to ongoing maintenance

![](page=19,bbox=[972, 281, 1879, 716])

<div align="center">

Fig. 1 Predicted natural growth curve

</div>

![](page=19,bbox=[976, 923, 1877, 1355])

<div align="center">

Fig. 2 Predicted natural growth curve and corresponding workload

</div>

and responding to changes. This is the simplest curve and even so it is not easy to quantify, but it is nevertheless useful in understanding what is likely to happen. We should think hard about the overall timescale and where we are now, on this curve.

I think there is still a long way to go, but in the meantime we should have:

- Confidence in our talent for reconciling national interests;

- Courage to address deficiencies; and

- Commitment to long-term progress.

SEMINAR 2020

![](page=20,bbox=[743, 274, 1028, 461])

<div align="center">

# Pattern approval and pattern compliance in an age of globalisation The Australian approach

</div>

JUDITH BENNETT - Executive Director,

NSC (Australia) and

ADRIAN CASTER - NSC, Australia

## 1 The changing political and economic climate

## 2 Globalisation of legal metrology

The manufacture of legal measuring instruments is becoming concentrated in highly industrialised countries, and increasingly controlled by multinational companies who are supplying the world market. Despite the fact that our client base has 'globalised' we (legal metrology authorities) still operate within our own strict national or 'economic community' boundaries, and impose our own legal and administrative requirements. National pattern approval requirements represent a significant regulatory barrier to international trade. In small markets like Australia, they impose significant costs on manufacturers and reduce market competition and product choice. The net result is an increase in consumer prices and slow adoption of new products and technologies.

This is a situation which will not be tolerated in the global economy of the 21 $ ^{st} $ century. It seems inevitable that we will all be living and working in a climate of economic rationalism and market deregulation. This is a dangerous climate for legal metrology authorities. The fundamental nature of our regulatory role is not well understood by governments or by the community in general, and we are in danger of being dismissed by the younger generation of bureaucrats, as old-fashioned technocrats who create unnecessary barriers to trade.

Unless we, the international legal metrology community, start to respond to the challenges of globalisation and the associated political and economic imperatives, our prospects of surviving until 2020 do not look good.

- Mutual acceptance arrangements for type approval test reports based on OIML Recommendations;

In essence, our proposal is that the OIML needs to make the transition from a 'harmonisation and coordination' approach, to an integrated global system of legal metrology. The globalisation of legal metrology should reflect the globalisation of industry and trade, whilst still respecting the sovereign rights of individual Member States.

The key elements of a global system would be:

- Pattern approval testing by a small number of specialised laboratories, located in major manufacturing countries and regional centres;

- A coordinated international pattern compliance program.

## Mutual Acceptance Arrangements

A "Framework for a Mutual Acceptance Arrangements on OIML Type Evaluation" has been developed by the members of TC 3/SC 5 and has now reached its 9th Committee Draft. This has been a difficult process, but now appears to be close to reaching general acceptance. This will be a watershed decision in the life of the OIML, which will have a major impact on the future operations of all individual Member States and on the BIML.

## Rationalisation of pattern approval facilities

The introduction of mutual acceptance arrangements will inevitably lead to a gradual rationalisation of pattern approval testing laboratories. It is anticipated that a small number of laboratories, located in the major industrialised countries and regional centres, will specialise in providing this industry service, and their reports will be accepted by most other Member States. The main benefits of this approach would be:

- Economies of scale in providing industry testing services;

- A single international testing process, avoiding multiple testing and associated costs and delays for manufacturers;

- Reduction in regulatory barriers to trade;

- Maintenance of a high level of competence and quality systems within specialised laboratories;

- Ability of specialist laboratories to invest in new equipment and keep pace with new technologies.

However, there will be some critical issues to be addressed, in particular:

- The rationalisation of pattern approval testing facilities could mean that many Member States may lose their technical capabilities; and

- A single pattern approval test is unlikely to be acceptable as an adequate basis for international confidence in the long-term performance of an instrument; so

- A 'safety net' will be required, in the form of an international pattern compliance program.

## An international pattern compliance program

For some time, there has been a recognition amongst CIML Members that there is a strong focus of resources on pattern approval testing, but very little focus on ensuring that production instruments conform to type. This leaves the whole system vulnerable to the selection of so-called "gold plated" instruments by manufacturers seeking pattern approval, who often openly acknowledge that they have difficulty in consistently achieving the standard in their production plants. This practice is perpetuated in an environment in which there is little market surveillance on the part of legal metrology authorities. With the implementation of mutual acceptance arrangements, it will become even more important for Member States to ensure that the instruments released onto their markets comply with the appropriate pattern approval standards.

It is apparent that many countries are not in a position to carry out national pattern compliance programs, as such programs are essentially in the public interest and must be funded by government. With the decrease in global industry revenue from pattern approval testing, under an OIML MAA, many national governments will face a critical decision: to pay the full cost of maintaining testing facilities and operating an effective national market surveillance program, or to close their laboratories and to trust in manufacturer declarations that production instruments consistently comply with the approved pattern.

The National Standards Commission has chosen the former option, with the support of the Australian government, because we have a legal responsibility to ensure pattern compliance, and because we believe in the deterrent value of a random surveillance program. However, this is an expensive option. On an international scale, a multiplicity of national compliance programs would be a very inefficient approach - given that many laboratories would be testing the same population of instruments.

Consistent with a global approach to pattern approval, we see the opportunity for a global approach to pattern compliance testing. We propose, for the consideration of Members, that participants in each

Mutual Acceptance Arrangement establish a cooperative pattern compliance program for the instruments which are covered under the MAA. A coordinated program of sampling and testing of instruments, and the sharing of results, would provide an effective global surveillance program at a very small cost to individual Member States.

Of equal importance would be the opportunity for participants to develop joint policies and take collective action against non-compliant manufacturers. The risk of losing global market approval would be a major incentive for manufacturers to deliver compliant products to all markets at all times.

Figure 1 illustrates a possible global approach to pattern approval and pattern compliance by the members of a Mutual Acceptance Arrangement for a single OIML Recommendation. This model assumes that the BIML would employ a Data Manager for each MAA. That person would manage and disseminate information, and use the database to determine a sampling plan for pattern compliance testing. MAA members would pay an annual fee to cover the cost of pattern compliance testing and data management.

We recognise that this proposal is a radical concept, which would require considerable trust between the OIML Member States, and careful planning and design. There may always be some Members who will retain national responsibility for pattern compliance, for legal or strategic reasons. However, with a 2020 horizon in view, we present the global model for debate and consideration by the OIML.

The Australian approach to a national pattern compliance program, and our early experiences, may be of interest in this debate, and are outlined in section 3 below.

![](page=21,bbox=[971, 1796, 1730, 2418])

<div align="center">

Fig.1 A model for 'global' pattern approval and pattern compliance within an OIML Mutual Acceptance Arrangement

</div>

## 3 The Australian experience

## Strategies adopted in 2001

In 2001, the National Standards Commission entered into its first bilateral Mutual Recognition Agreements - with NWML in the UK, NMi in the Netherlands, and the Ministry of Consumer Affairs in New Zealand. The key elements of these agreements are:

- Acceptance of test reports which conform to OIML formats (for the selected instrument categories);

- Mutual confidence in test results based on third party accreditation to ISO/IEC 17025 by a signatory to the ILAC MRA;

- A focus on agreements which will facilitate trade between Australia and its major overseas trading partners, and optimise benefits for Australian manufacturers and importers.

In parallel with the introduction of mutual recognition arrangements, the NSC also announced that it would implement a national pattern compliance program. Our objective in doing this was to make all manufacturers aware that we have an effective market surveillance system in place, and we expect production instruments to meet the approved pattern, whether they are initially tested in Australia or accepted under mutual recognition arrangements.

## Early experiences with mutual recognition arrangements

In the early stages of processing pattern approval applications under our mutual recognition arrangements, we have encountered a number of issues.

- There are slight differences in interpretation and application of OIML requirements between testing laboratories. There is an ongoing need to discuss and resolve points of interpretation, to ensure uniformity of practice, and this is a constructive process for all concerned. However, this experience suggests that the implementation of an OIML MAA could involve a major exercise in clarification and alignment of procedures. It will be important to ensure that agreed interpretations are systematically incorporated into revisions of OIML documents by the relevant Technical Committees.

- It is a practice of some OIML Issuing Authorities to outsource some components of pattern approval testing to third parties, including instrument manufacturers. This practice compounds the problems of uniformity of interpretation and methodology, and raises significant questions of confidence in the capabilities of the third party and the independence of test data. At the present time, the NSC does not accept third party data under its mutual recognition arrangements.

- There are some differences in methods of testing and the design of testing equipment between laboratories. In some cases these can lead to differences in test results and performance evaluations. This is an area which warrants further investigation.

## The design of the Australian pattern compliance program

All pattern approval examinations include tests of an instrument's performance under different influence factors, particularly temperature, humidity, voltage, and electromagnetic radiation. These aspects of performance cannot readily be assessed under normal operating conditions, and problems may go undetected during trade use. The NSC has implemented a systematic pattern compliance testing program to address this issue. The steps in this process were as follows:

- A complete listing was made of all instruments with a current Australian pattern approval, indicating all models included on each approval certificate.

- It was decided that each instrument would be subjected to each of the 'influence factor' tests over a 5-year period. The program commenced with temperature testing, as this was considered to be the most critical.

- A pattern compliance database was designed. This allows for a planned testing schedule to be entered for each instrument, and for the progressive recording and analysis of test results.

- Two non-compliance categories were defined, to assist in interpreting and reporting the findings of the program:

- Minor failure: less than or equal to $ 1. 5 \times M P E $ -

- Major failure: greater than $ 1. 5 \times M P E $

- Consultations were held with manufacturers and agents, to seek their voluntary participation in the program for a trial period. They agreed to supply randomly selected instruments from stock, on request, and we agreed to advise them of the results of the test and discuss any non-compliance issues without penalty.

Early experiences with the pattern compliance program

The program is in its very early stages, and has so far been limited to nonautomatic weighing instruments.

However, some significant issues have already emerged.

- Australia does not have many manufacturers of weighing instruments, so the majority of instruments are imported via local agents. In some cases the local agents have been cooperative, but in some cases we have had to wait for overseas manufacturers to supply a 'suitable' instrument, as stocks are not always held in Australia. This leaves the process open to selection of a 'gold plated' instrument, which defeats the purpose of the program.

- Although this initial program is voluntary, we would expect to take action against non-compliant manufacturers after the trial period. As the majority of instruments are distributed through agents, it will be very difficult to have any impact on instruments already sold into the marketplace, so that any rectification will only apply to new instruments. Unilateral withdrawal of approvals in Australia could prove controversial, and would have limited impact on manufacturers, unless supported by other OIML Members. We are not aware of any simple mechanism for sharing information or taking collective action.

- The results of 27 tests scheduled for stage 1 of the program are shown in Figure 2. In summary:

- 9 instruments complied with the test requirements;

- 9 instruments had a minor failure;

- 1 instrument had a major failure;

- 4 instruments are no longer manufactured; and

- 4 instruments have still not been supplied by manufacturers.

- Incidents of non-compliance have been discussed with the relevant manufacturers. In all cases they were surprised and concerned by the findings, were keen to discuss the results in detail, and have initiated remedial action. This has been a very constructive outcome.

These preliminary findings suggest that there could be a significant level of non-compliance of nonautomatic weighing instruments, particularly at the extremes of the temperature range. The sample size is small and most failures are minor, but this limited evidence is sufficient to justify the ongoing allocation of resources to this work. The program will be extended to other instrument categories, to build an overall understanding of compliance issues and to identify issues which need to be raised with manufacturers, and/or with the relevant OIML Technical Committees.

## 4 Summary

imperatives of the $ 2 1^{\mathrm{s t}} $ century by developing a global system for the pattern approval and pattern compliance testing of legal measuring instruments.

In our view, the International Organization of Legal Metrology should respond to the economic and political

Mutual Acceptance Arrangements will be the first important step in this process. Such arrangements will significantly reduce technical barriers to trade, but are also expected to lead to a major rationalisation of technical facilities, resulting in a few large specialist laboratories in major manufacturing countries and regional centres.

We have proposed, for the consideration by the OIML, that a pattern compliance program be introduced as part of each MAA, to provide an effective market surveillance function for the global marketplace, on a cost-sharing basis. Early Australian experience with pattern compliance testing suggests that such a program is necessary.

<table border="1"><tr><td>Instrument N°</td><td>Pass</td><td>Fail</td><td>Comments</td></tr><tr><td>1</td><td></td><td>×-Major</td><td>Failed-10,TEOZ all Temps</td></tr><tr><td>2</td><td></td><td>×-Minor</td><td>Failed40</td></tr><tr><td>3</td><td>×</td><td></td><td></td></tr><tr><td>4</td><td>×</td><td></td><td></td></tr><tr><td>5</td><td></td><td>×-Minor</td><td>FailedTEOZ20-40</td></tr><tr><td>6</td><td>×</td><td></td><td></td></tr><tr><td>7</td><td></td><td>×-Minor</td><td>FailedTEOZ20-40</td></tr><tr><td>8</td><td></td><td></td><td>No longer made</td></tr><tr><td>9</td><td>×</td><td></td><td></td></tr><tr><td>10</td><td></td><td></td><td>Out of business</td></tr><tr><td>11</td><td></td><td>×-Minor</td><td>FailedTEOZ20-40</td></tr><tr><td>12</td><td></td><td>×-Minor</td><td>Failed-10 and40</td></tr><tr><td>13</td><td></td><td>×-Minor</td><td>Failed-5,+5</td></tr><tr><td>14</td><td></td><td></td><td>No longer made</td></tr><tr><td>15</td><td>×</td><td></td><td></td></tr><tr><td>16</td><td></td><td></td><td>Nothing supplied</td></tr><tr><td>17</td><td></td><td></td><td>Nothing supplied</td></tr><tr><td>18(LC)</td><td></td><td>×-Minor</td><td>FailedMDLOR-10,20</td></tr><tr><td>19(LC)</td><td>×</td><td></td><td></td></tr><tr><td>20</td><td></td><td></td><td>No longer made</td></tr><tr><td>21(LC)</td><td></td><td></td><td>Nothing supplied</td></tr><tr><td>22(LC)</td><td></td><td>×-Minor</td><td>Failed-10,+5</td></tr><tr><td>23(Ind)</td><td>×</td><td></td><td></td></tr><tr><td>24</td><td></td><td>×-Minor</td><td>Failed40 andVmin</td></tr><tr><td>25(Ind)</td><td></td><td></td><td>Nothing supplied</td></tr><tr><td>26</td><td>×</td><td></td><td></td></tr><tr><td>27(Ind)</td><td>×</td><td></td><td></td></tr></table>

<div align="center">

Fig. 2 Results of 27 tests scheduled for stage 1 of the program

</div>

<div align="center">

# OIML Certificate System: Certificates registered 2002.05-2002.07

</div>

For up to date information: www.oiml.org

The OIML Certificate System for Measuring Instruments was introduced in 1991 to facilitate administrative procedures and lower costs associated with the international trade of measuring instruments subject to legal requirements.

The System provides the possibility for a manufacturer to obtain an OIML certificate and a test report indicating that a given instrument pattern complies with the requirements of relevant OIML International Recommendations.

Certificates are delivered by OIML Member States that have established one or several Issuing Authorities responsible for processing applications by manufacturers wishing to have their instrument patterns certified.

OIML certificates are accepted by national metrology services on a voluntary basis, and as the climate for mutual confidence and recognition of test results develops between OIML Members, the OIML Certificate System serves to simplify the pattern approval process for manufacturers and metrology authorities by eliminating costly duplication of application and test procedures.

![](page=24,bbox=[251, 978, 1816, 1804])

<div align="center">

# Système de Certificats OIML:

Certificats enregistrés 2002.05-2002.07

</div>

Pour des informations à jour: www.oiml.org

Le Système de Certificats OIML pour les Instruments de Mesure a été introduit en 1991 afin de faciliter les procédures administratives et d'abaisser les coûts liés au commerce international des instruments de mesure soumis aux exigences légales.

Le Système permet à un constructeur d'obtenir un certificat OIML et un rapport d'essai indiquant qu'un modèle d'instrument satisfait aux exigences des Recommandations OIML applicables.

Les certificats sont délivrés par les États Membres de l'OIML, qui ont établi une ou plusieurs autorités de délivrance responsables du traitement des

demandes présentées par des constructeurs souhaitant voir certifier leurs modèles d'instruments.

Les services nationaux de métrologie légale peuvent accepter les certificats sur une base volontaire; avec le développement entre Membres OIML d'un climat de confiance mutuelle et de reconnaissance des résultats d'essais, le Système simplifie les processus d'approbation de modèle pour les constructeurs et les autorités métrologiques par l'elimination des répétitions coûteuses dans les procédures de demande et d'essai.

## INSTRUMENT CATEGORY

CATÉGORIE D'INSTRUMENT

Automatic catchweighing instruments

Instruments de pesage trieurs-étiqueteurs

à fonctionnement automatique

R 51 (1996)

Issuing Authority / Autorité de délivrance Physikalisch-Technische Bundesanstalt (PTB), Germany

R51/1996-DE-99.05 Rev.2 L2-PTLs-... (Classes Y(a) and Y(b)) Mettler-Toledo (Albstadt) GmbH, Unter dem Malesfelden 34 D-72458 Albstadt, Germany

Issuing Authority / Autorité de délivrance National Weights and Measures Laboratory (NWML), United Kingdom

R51/1996-GB1-02.01 Rev.1 Type Gemini (Classes X(1) and Y(a)) Herbert Industrial Ltd, Smithfield House, Rookwood Way, Haverhill, Suffolk CB9 8PB, United Kingdom

## INSTRUMENT CATEGORY

CATÉGORIE D'INSTRUMENT

Metrological regulation for load cells

(applicable to analog and/or digital load cells)

Réglementation métrologique des cellules de pesée

(applicable aux cellules de pesée à affichage

analogique et/ou numérique)

R60(2000)

Issuing Authority / Autorité de délivrance

Physikalisch-Technische Bundesanstalt (PTB),

Germany

R60/2000-DE-02.01

Type C16.. (Classes C1 up to C5)

Hottinger Baldwin Messtechnic Wägetechnik GmbH,

Im Tiefen See 45, D-64293 Darmstadt, Germany

R60/2000-DE-02.02 HBB..(Class C3) Celtron Technologies Inc.,15F,No.86,Sec.1 Hsin Tai Wu Road, Hsi Tzu, Taipei Hsien, R.O.C, Taiwan

Issuing Authority / Autorité de délivrance Netherlands Measurement Institute (NMi) Certin B.V., The Netherlands

R60/2000-NL1-02.11 IL (Class C) Mettler-Toledo (Changzhou) Scale & System Ltd., 111 Changxi Road, Changzhou, Jiangsu 213001, China

R60/2000-NL1-02.12 SSP1260 (Class C) Mettler-Toledo (Changzhou) Scale & System Ltd., 111 Changxi Road, Changzhou, Jiangsu 213001, China

R60/2000-NL1-02.13 Type SBC (Class C) Mettler-Toledo (Changzhou) Scale & System Ltd., 111 Changxi Road, Changzhou, Jiangsu 213001, China

R60/2000-NL1-02.14 Type SSP1241 (Class C) Mettler-Toledo (Changzhou) Scale & System Ltd., 111 Changxi Road, Changzhou, Jiangsu 213001, China

R60/2000-NL1-02.15 Type LCC11 (Class C) A&D Instruments Ltd., 24 Blacklands Way, Abingdon Business Park, Abingdon, Oxfordshire OX14 1DY, United Kingdom

R60/2000-NL1-02.16 Rev.1

PW15../.. (Classes C and D)

Hottinger Baldwin Messtechnic Wägetechnik GmbH,

Im Tiefen See 45, D-64293 Darmstadt, Germany

R60/2000-NL1-02.17

Type 0805 (Class C)

Mettler-Toledo Inc., 150 Accurate Way, Inman, SC 29349, USA

R60/2000-NL1-02.18 Types 1042 and 1042 Symmetric (Class C) Tedea Huntleigh International Ltd., 5a Hatzoran St. Netanya 42506, Israël

R60/2000-NL1-02.19

Type MP50/xxx (Class C)

GLOBAL Weighing Technologies GmbH, Meiendorfer Str. 205,

D-22145 Hamburg, Germany

R60/2000-NL1-02.20

Type MP51/xxx (Class C)

GLOBAL Weighing Technologies GmbH, Meiendorfer Str. 205,

D-22145 Hamburg, Germany

## INSTRUMENT CATEGORY

CATÉGORIE D'INSTRUMENT

Automatic gravimetric filling instruments

Doseuses pondérales à fonctionnement automatique

R 61 (1996)

Issuing Authority / Autorité de délivrance Physikalisch-Technische Bundesanstalt (PTB), Germany

## R61/1996-DE-02.01

Siwarex A, Siwarex AWS for accuracy class Ref (0.2)

Siemens AG Fürth, Würzburger Str. 121, D-90766 Fürth, Germany

Issuing Authority / Autorité de délivrance National Weights and Measures Laboratory (NWML), United Kingdom

R61/1996-GB1-02.01 Type MX1 (reference accuracy class Ref X(0.5)) Weitek, Via A. Sabin, I-44020 - Gallo - Ferrara, Italy

## INSTRUMENT CATEGORY

CATÉGORIE D'INSTRUMENT

Nonautomatic weighing instruments

Instruments de pesage à fonctionnement

non automatique

R 76-1 (1992), R 76-2 (1993)

Issuing Authority / Autorité de délivrance Physikalisch-Technische Bundesanstalt (PTB), Germany

## R76/1992-DE-99.04 Rev.1

Type DX BI 500 (Classes II, III and I II I Sartorius A.G., Postfach 32 43, D-37070 Göttingen, Germany

## R76/1992-DE-00.09 Rev.4

iso-TEST (Classes I, II, III and I II I)

Sartorius A.G., Weender Landstraße 94-108, D-37075 Göttingen, Germany

R76/1992-DE-01.06 Rev.1

Types DS BI 300; DN BI 300; DQ BI 300; DY BI 300; DZ BI 300

(Class III)

Sartorius A.G., Weender Landstraße 94-108, D-37075 Göttingen,

Germany

R76/1992-DE-01.08 Rev.1

Types BC BL 100, BD BL 200, BF BL 500 (Classes I, II and III)

Sartorius A.G., Weender Landstraße 94-108, D-37075 Göttingen,

Germany

## R76/1992-DE-02.01

Type M2000L (Class III)

ETASIS Elektronik Tarti Aletleri ve Sistemleri San. ve Tic. A.S.,

Uluönder Mahallesi 1. Cadde No: 18, Eskisehir, Turkey

## R76/1992-DE-02.02

Types DX BO 300, DY BO 300 (Classes III and IIII)

Sartorius A.G., Weender Landstraße 94-108, D-37075 Göttingen, Germany

## R76/1992-DE-02.04

Types CE... (Class III)

Bizerba GmbH & Co. KG, Wilhelm-Kraut-Straße 65,

D-72336 Balingen, Germany

R76/1992-DE-02.06

Types ES... (Class III)

Bizerba GmbH & Co. KG, Wilhelm-Kraut-Straße 65,

D-72336 Balingen, Germany

Issuing Authority / Autorité de délivrance Danish Agency for Development of Trade and Industry, Division of Metrology, Denmark

## R76/1992-DK-02.02

PWI (Classes III and IIII)

ESIT Electronics, Mühurdar Cad. No. 91, Kadikoy

TR-81300 Istanbul, Turkey

Issuing Authority / Autorité de délivrance Centro Español de Metrologia, Spain

## R76/1992-ES-02.01

Nonautomatic, graduated, self-indicating, electronic counter-top weighing instrument, type "L" intended for direct sale to the public (Class III)

DIBAL S.A., c/ Astintze Kalea, 24, Poligono Industrial Neinver, E-48016 Derio (Bilbao-Vizcaya), Spain

Issuing Authority / Autorité de délivrance Netherlands Measurement Institute (NMi) Certin B.V., The Netherlands

R76/1992-NL1-02.15 Rev.1

DS-520 (Class III)

Teraoka Seiko Co., Ltd., 13-12 Kugahara, 5-Chome, Ohta-ku,

Tokyo 146-8580, Japan

## R76/1992-NL1-02.17

Type 8434(RN00) (Class III)

Mettler-Toledo (Changzhou) Scale & System Ltd.,

111 Changxi Road, Changzhou, Jiangsu 213001, China

## R76/1992-NL1-02.18

BM-1 (Class III)

Digital Scales S.A., Poligono Industrial Larrondo, Beheko Etorbidea, no. 2 Naves 2, 3, 4, E-48180 Loiu Vizcaya, Spain

## R76/1992-NL1-02.19

LP-II (Class III)

CAS Corporation, CAS Factory # 19 Kanap-ri, Kwangjeok-myon,

Yangju-kun Kyungki-do, Rep. of Korea

## R76/1992-NL1-02.20

BM-2 and BM-3..(Class III) Digital Scales S.A., Poligono Industrial Larrondo, Beheko Etorbidea, no. 2 Naves 2, 3, 4, E-48180 Loiu Vizcaya, Spain

## R76/1992-NL1-02.21

Type AEA (Class I)

ADAM Equipment Co. Ltd., Bond Avenue, Denbigh East

Industrial Estate, Milton Keynes MK1 1SW, United Kingdom

R76/1992-NL1-02.22 Type WAA or WAX (Class I) Radwag Zaklad Mechaniki, 26-600 Radom, ul. Grudniowa 37/39 Poland

Issuing Authority / Autorité de délivrance Gosstandart of Russian Federation, Russian Federation

## R76/1992-RU-02.01

Scale BIIA (Class III)

JSWMC "TENSO-M", 38, Vokzalnaya str, Kraskovo, Lyuberetskii District, Moscow region, 140050, Russian Federation

## R76/1992-RU-02.02

## Scale BII (Class III)

JSWMC "TENSO-M", 38, Vokzalnaya str, Kraskovo, Lyuberetskii District, Moscow region, 140050, Russian Federation

## R76/1992-RU-02.03

Scale BA (Class III) JSWMC "TENSO-M", 38, Vokzalnaya str, Kraskovo, Lyuberetskii District, Moscow region, 140050, Russian Federation

<div align="center">

# Updated information on OIML certificates:

</div>

## INSTRUMENT CATEGORY

CATÉGORIE D'INSTRUMENT

www.oiml.org

## Automatic rail-weighbridges

Ponts-bascules ferroviaires à fonctionnement

automatique

R106(1997)

## Issuing Authority / Autorité de délivrance

Issuing Authority / Autorite de delivrance

Physikalisch-Technische Bundesanstalt (PTB),

Germany

## R106/1997-DE-02.01

SOLAR accuracy classes 0.2; 0.5; 1 and 2

Pfister Waagen GmbH, Statzlinger Straße 70, D-86165 Augsburg, Germany

Issuing Authority / Autorité de délivrance Gosstandart of Russian Federation, Russian Federation

## R106/1997-RU-02.01

Scale BII-30 (Class 0.5 for coupled wagon - Class 0.2 for total train)

Avitec-Plus Ltd., 122, Malisheva str, Yekaterinburg, Sverdlovsk region 620078, Russian Federation

## INSTRUMENT CATEGORY

CATÉGORIE D'INSTRUMENT

## Fuel dispensers for motor vehicles

Distributeurs de carburant pour véhicules à moteur

R 117 (1995) [+ R 118 (1995)]

Issuing Authority / Autorité de délivrance Swedish National Testing and Research Institute AB, Sweden

## R117/1995-SE-02.01

Fuel Dispensers for Motor Vehicles, model Global Star (Class 0.5) Dresser Wayne AB, Limhamnsvagen 109, SE-200 61 LIMHAMN, Sweden

RLMO MEETING

<div align="center">

# 18th WELMEC Committee Meeting

</div>

Vienna, 13-14 June 2002

GABRIELE WESSELY, WELMEC Secretary

The 18th meeting of the WELMEC Committee was held in Vienna, Austria on 13-14 June 2002, hosted by the Federal Office of Metrology and Surveying (BEV).

The Committee was given a warm welcome to Austria by Mr. August Hochwartner (President of the Federal Office of Metrology and Surveying) and Mr. Koprivnikar (Federal Ministry for Economic Affairs and Labor). Mr. Koprivnikar pointed out the important work done by WELMEC to achieve a harmonized European approach to legal metrology and mentioned the tasks to be carried out in the future to make this possible.

Mr. Freistetter welcomed delegates and thanked the Committee for electing him as Chairman. The Committee and the new Chairman both expressed their appreciation to Dr. Bennett for his Chairmanship over eleven years.

The first item on the agenda involved a presentation on the legal metrology structure in Austria. Dr. Arnold Leitner, Director of the Metrology Service at BEV, gave an informative presentation describing the way in which the organization had dealt with the new approach concerning the amendment of the Legal Metrology Act in Austria.

Developments since the founding of WELMEC had made it necessary to update some of the internal procedures and also the membership policy.

Another important point of discussion was the amendment of the WELMEC Type Approval Agreement to include OIML R 129 in Annex 1 of the Type Approval Agreement (and adoption of the amendments to Annex 2 of the Agreement concerning OIML R 129 for Austria, Belgium, Denmark, Germany, Italy, Luxembourg Norway, Switzerland and the United Kingdom).

The Committee also noted the information from Germany to be included in Annex 2 concerning OIML R117 and R118 and instructed Members to send their views on additional groups of measuring instruments to be included in the agreement by 30 September 2002.

basis of the discussions in the meeting - charged with new or additional tasks for the near future.

The WELMEC working groups had been very busy since the last Committee meeting and had been - on the

## Working Group reports

The Committee approved the publication of the WG2 Guide WELMEC 2.3 Guide for Examining Software (Weighing Instruments) and included automatic weighing instruments in the terms of reference, as specified in the Measuring Instruments Directive.

The tasks of WG4 have been included in WG 8's work program, but WG4 has been allocated new activities in relation to general aspects of legal metrology.

WG 5 is preparing a Guide for market surveillance and has also proposed to take the necessary steps to ensure that WELMEC will be accepted as an Administrative Cooperation (ADCO) in the field of nonautomatic weighing instruments.

The main task of WG 6 has been the preparation of additional guides in the field of pre-packaged products and draft guides were presented at the Committee Meeting. Some points were still not finalized in time for the Committee Meeting and so the adoption process will be launched in the near future.

WG7 has been successful in obtaining an EU-funded work project under the EU Growth Program and will now commence the project concerning "MID Software". A very important task awaiting WG 7 is also its responsibility for horizontal questions concerning software, transfer of data and other related questions.

The main task of WG 8 was to contribute to the discussions on the MID in the European Council procedure as a technical forum. This WG had met four times since the last Committee Meeting and has been looking at all the instrument-specific annexes of the MID as well as Annexes I to IV. Now WG 8 has also been given the task of looking at the horizontal issues of the Directive, identifying the need for a harmonized approach, and presenting the results with new terms of reference at the next Committee Meeting.

WG10 had a guide ready for presentation (Guide for the use of an alibi recording device (printer or storage) in measuring systems in liquids other than water) and it was agreed that reaching a consensus will be done by e-mail to shorten the time needed to make this Guide available.

Some very important information concerning the MID was given. The Committee discussions centered on progress in the Council Working Group, the contributions of WG 8 and the future plans under the Danish Presidency.

Mr. Christensen, Danish Chairman of the MID Council Working Group during the Danish Presidency, said he planned to continue the hard work carried out by Spain during their Presidency and four meetings of the Council Working Group were currently planned. His goal is to reach political agreement by November and he

plans to take a new approach to dealing with outstanding matters by regrouping the programs.

The Committee was updated on the situation concerning the application of OIML Recommendations for European purposes. The European Commission has suggested different wording in the text of the MID so that in the amended version the use of OIML documents is facilitated.

In October 2000 the Commission invited applications for EU funding for two-year projects under its Dedicated Call 10/00 Topic IV.34. Three WELMEC

## Amongst others, the following main Decisions were taken during the WELMEC Committee Meeting in Vienna

on 13-14 June 2002:

Thanks to Seton Bennett for his work as Chairman since 1990

Instructs the Members to give their views to the Secretariat about the structure, organization and voting procedures during Committee Meetings of WELMEC by 30 September 2002

Approves the Procedures for WELMEC activities 2002 with slight amendments

Adopts the Member Policy of admitting countries with a signed Europe Agreement as WELMEC Associate Members. Cyprus, Malta and Turkey will be informed about all activities within WELMEC and the policy will be reconsidered during the next Committee Meeting

- Instructs the conveners of Working Groups to send their views to the Secretariat about the working methods and access to the WG meetings by 30 September 2002

Approves the publication of WELMEC Guide 2.3 Guide for Examining Software (Weighing Instruments)

Instructs WG 6 to consider the situation of Associate Members concerning pre-packages

- Instructs Members to send comments on the three draft guides concerning pre-packages by 31 October 2002 and if possible have the drafts agreed by e-mail

$ \diamond $ Instructs the Conveners of WG 2, WG 6 and WG 7 to present a common position concerning the AWI in relation to pre-packages

Instructs WG 10 to finalize the e-mail voting for the Guide for the use of an Alibi Recording Device and submit the result to the Secretariat, and the Secretariat accepts to try to reach a consensus for this Guide by e-mail from the Committee Members

- Instructs the convener of WG 4 to look at general aspects of legal metrology and work out terms of reference to be presented at the next Committee Meeting

- Instructs WG 8 to look at the horizontal issues of the MID, identifying the need for a harmonized approach, starting with module H1 and present this, along with new terms of reference at the next Committee Meeting

- Instructs the Committee Members to evaluate the draft of the Strategy Document and Action Plan presented, and send their comments and remarks to the Secretariat by 30 September 2002

Concerning the WELMEC Type Approval Agreement:

Adopts the amendments to Annex 1 of the Type Approval Agreement to include OIML R 129

Adopts the amendments to Annex 2 of the Type Approval Agreement concerning OIML R 129 for Austria, Belgium, Denmark, Germany, Italy, Luxembourg, Norway, Switzerland and the United Kingdom

Notes the information from Germany to be included in Annex 2 concerning OIML R 117 and R 118

- Instructs the Members to send their views for additional groups of measuring instruments to be included in the agreement by 30 September 2002

Member States applied and are now carrying out their respective projects in parallel, but many countries are involved in each project.

The first project is entitled Uniform test procedures and test report formats for aspirant Notified Bodies under the Measuring Instruments Directive and concerns gas meters, liquid flow meters and taximeters. The second project concerns the MID AWI Thematic Network, mainly focusing on the interpretation of the essential requirements of the MID and concerns automatic catchweighing instruments, front end loaders, utilization of OIML R 76 test results and MID Module H1. The third project concerns MID software and covers the definition and elaboration of software requirements, testing and validation, back tracing of software requirements, future aspects, project co-ordination, dissemination of results and the organization of information days.

Another point was the presentation of an updated strategy document to the WELMEC Committee, and the

Chairman explained that it was his intention to publish this document together with the WELMEC Member Document so that there is only one document on WELMEC strategy and policy. Some Committee Members wanted to make slight amendments to the document, so the Committee was asked by the Chairman to send comments on it to the Secretariat by 30 September 2002 (see Resolution 23). These comments will be considered and a new document presented at the next Committee Meeting to discuss an amended strategy and policy approach in WELMEC.

Representatives from several Observer Organizations also attended the meeting, and the WELMEC Committee heard reports from the OIML, Euromet and the APLMF.

The next Committee Meeting will be held in Madrid on 8-9 May 2003, at the kind invitation of Mr. Robles, of the Centro Español des Metrologia.

![](page=0,bbox=[250, 1342, 1821, 2178])

Delegates attending the 18th WELMEC Committee Meeting

![](page=1,bbox=[208, 354, 309, 453])

<div align="center">

# 52 $ ^{nd} $ General Assembly

</div>

Ermelo, The Netherlands

10 May 2002

MICHEL TURPAIN, Permanent Secretary

CECIP, the European Committee of Weighing Instrument Manufacturers, held its $ 52 ^{n d} $ General Assembly in Ermelo, The Netherlands, at the invitation of the Dutch Federation FHI Weeginstrumenten.

In line with CECIP's policy of openness to the world market and following the invitation of a Chinese delegation in 2000 and the President of the US Scale Manufacturers Association Mr. David Castle in 2001 this year CECIP's guest was Dr. Alexander Korobkin President of the Russian Federation company Massa-K. There were fruitful exchanges between the twelve CECIP Federations representing the following countries:

Czech Republic, Finland, France, Germany, Hungary Italy, Netherlands, Slovak Republic, Spain, Switzerland Ukraine, United Kingdom

The General Assembly is also the opportunity to invite experts or key individuals from international or European bodies to report on their policies and to share their views on weighing-related subjects. This year the Assembly was honored to welcome:

Mr. C. Groeneveld of the FHI Office, who gave a speech on Instrumentation in The Netherlands;

Dr. Jan Basten of NMi, who gave a speech on Legal Metrology in The Netherlands;

Professor Dr. Manfred Kochsiek, OIML Vice-President, who gave a speech on Contributions by international organizations to the global measurement system;

Dr. Klaus Dieter Sommer, Director of the Thuringe Metrology and Verification Authority, who presented Calibration and verification: two procedures with comparable objectives but differing strategies; and

Dr. Alexander Korobkin, President of the Russian Federation company Massa-K, who gave a presentation on The weighing industry in Russia.

Each Federation then presented the situation of the weighing industry in its country, including a table summarizing weighing instrument production in Europe, which indicates a general growth trend in production compared to 2000 with the instigation of the Euro, which required price-computing scales to be replaced both in the field of trade and and in the retail sector.

During the afternoon the statutory part included, as in previous years:

Activity reports for each Working Group:

The Legal Metrology Group, which is continuing with its task of coming up with proposals and examinations:

of OIML documents, especially the revision of Recommendations dealing with automatic weighing instruments;

of European Commission documents, especially the draft MID;

of WELMEC (European Cooperation in Legal Metrology) documents, especially harmonization guides.

The Business and Commerce Group, which ensures healthy market competition and which monitors the interests of manufacturers and consumers, especially concerning the draft MID.

The Bureau, which takes care of the day-to-day management of the Committee and of its development by passing on experience acquired to the younger Federations of those countries that come knocking at the European Union's door, and by creating ties with the Federations of weighing instrument manufacturers around the world, bringing on board new CECIP members, such as Ukraine in 2000, and by creating ties with the Chinese, American, Russian or Japanese Federations.

- Sincere thanks were expressed to Dr. Klaus Wurster for the work he had accomplished during his five years as President, following which a new Bureau was elected comprising:

<table border="1"><tr><td>President</td><td>Tim Cooper
United Kingdom Federation</td></tr><tr><td>Vice-President</td><td>Caroline Obrecht
Swiss Federation</td></tr><tr><td>Vice-President</td><td>Fabio Martignoni
Italian Federation</td></tr><tr><td>Vice-President</td><td>Klaus Wurster
German Federation</td></tr><tr><td>Permanent Secretary</td><td>Michel Turpain
French Federation</td></tr></table>

Our Dutch friends had made an excellent job of organizing this General Assembly in the attractive settings of a superb Conference Center, the Herrlickheijd Van Ermelo. The day's work was followed by a visit to the polders, including a steam pumping works and a trip to the Schokland site. Many thanks to our Dutch friends and see you next year in Switzerland!

<div align="center">

Statistiques, Industrie du Pesage (2001)

</div>

<div align="center">

Weighing Industry Statistics (2001)

</div>

<table border="1"><tr><td rowspan="2">PaysCountry</td><td rowspan="2">ProductionHT(Million Euro)Ex VAT(Million Euro)</td><td rowspan="2">Variation/2000</td><td>Export(Million Euro)</td><td>Import(Million Euro)</td></tr><tr><td>Variation/2000</td><td>Variation/2000</td></tr><tr><td rowspan="2">AllemagneGermany</td><td rowspan="2">727</td><td rowspan="2">+11%</td><td>479</td><td>248</td></tr><tr><td>+8%</td><td>+7%</td></tr><tr><td rowspan="2">EspagneSpain</td><td rowspan="2">121</td><td rowspan="2">+11%</td><td>28</td><td>12</td></tr><tr><td>-36%</td><td>-25%</td></tr><tr><td>FinlandeFinland</td><td></td><td></td><td></td><td></td></tr><tr><td rowspan="2">FranceFrance</td><td rowspan="2">194.5</td><td rowspan="2">+11.2%</td><td>69.5</td><td>136.1</td></tr><tr><td>-1.7%</td><td>+14.2%</td></tr><tr><td>HongrieHungary</td><td></td><td></td><td></td><td></td></tr><tr><td rowspan="2">ItalieItaly</td><td rowspan="2">129.3</td><td rowspan="2">+45.7%</td><td>25.5</td><td>26.5</td></tr><tr><td>+25%</td><td>+35%</td></tr><tr><td>Pays BasNetherlands</td><td></td><td></td><td></td><td></td></tr><tr><td>Rép. SlovaqueSlovak Republic</td><td></td><td></td><td></td><td></td></tr><tr><td rowspan="2">Rép. TchèqueCzech Republic</td><td rowspan="2">11.4</td><td rowspan="2">-5.1%</td><td>1.5</td><td>9.8</td></tr><tr><td>+7%</td><td>+77%</td></tr><tr><td rowspan="2">Royaume-UniUnited Kingdom</td><td rowspan="2">195.3</td><td rowspan="2">+2%</td><td>130.6</td><td>141.7</td></tr><tr><td>-3.9%</td><td>+7.7%</td></tr><tr><td rowspan="2">SuisseSwitzerland</td><td rowspan="2"></td><td rowspan="2"></td><td>153.4</td><td>48.2</td></tr><tr><td>+5.1%</td><td>0%</td></tr><tr><td>UkraineUkraine</td><td></td><td></td><td></td><td></td></tr></table>

CECIP

![](page=2,bbox=[150, 1865, 251, 1965])

52ème Assemblée Générale

Ermelo, Pays-Bas

10 mai 2002

MICHEL TURPAIN, Secrétaire Permanent

Le CECIP, Comité Européen des Constructeurs d'Instruments de Pesage, vient de tenir sa 52ème Assemblée Générale à Ermelo aux Pays-Bas, à l'invitation de la Fédération Hollandaise, FMI Weeginstrumenten.

Après la venue d'une délégation chinoise en 2000, puis celle de M. David Castle, Président de la "Scale Manufacturers Association" des États-Unis en 2001, nous avons reçu cette année le Dr. Alexander Korobkin, Président de la société Massa-K de la Fédération de Russie poursuivant notre politique d'ouverture dans un marché mondial. Des échanges fructueux ont pu se faire avec les douze Fédérations du CECIP représentant les pays suivants:

Allemagne, Espagne, Finlande, France, Hongrie, Italie, Pays-Bas, République Slovaque, République Tchèque, Royaume-Uni, Suisse, Ukraine

L'Assemblée Générale est aussi l'occasion d'inviter des experts ou des personnalités d'organismes internationaux ou européens pour nous faire part de leur politique ou de leur point de vue sur des sujets touchant le pesage. Cette année nous avions l'honneur de recevoir:

Monsieur C. Groeneveld du Bureau FHI, qui nous a présenté L'instrumentation dans les Pays-Bas;

Dr. Jan Basten du NMi, qui nous a présenté La métrologie légale dans les Pays-Bas;

Professeur Dr. Manfred Kochsiek, Vice-Président de I'OIML, qui nous a présenté Les contributions des organisations internationales au système de mesure global;

Dr. Klaus Dieter Sommer, Directeur de l'Autorité de Métrologie et de Vérification de Thuringe, qui nous a présenté Étalonnage et vérification: deux procédures avec des objectifs comparables mais des stratégies différentes; et

Dr. Alexander Korobkin, Président de la société Massa-K de la Fédération de Russie, qui nous a présenté L'industrie du pesage en Russie.

Chaque Fédération a ensuite présenté la situation de l'industrie du pesage dans son pays, avec un tableau récapitulatif détaillant la production d'instruments de pesage en Europe et montrant une croissance générale de la production par rapport à 2000 avec l'arrivée de l'Euro qui a nécessité un renouvellement des balances poids-prix dans le domaine du commerce et de la grande distribution.

La partie statutaire s'est déroulée l'après-midi avec le programme habituel suivant:

- Les rapports d'activité de chaque Groupe de Travail:

Le Groupe Métrologie Légale qui poursuit sa tâche de propositions et d'examens:

- des documents de l'OIML, en particulier la révision des Recommandations touchant les instruments de pesage à fonctionnement automatique;

- des documents de la Commission Européenne, en particulier le projet de Directive sur les Instruments de Mesure;

- des documents du WELMEC (European Cooperation in Legal Metrology), en particulier les guides d'harmonisation.

Le Groupe Affaires et Commerce qui veille à une concurrence saine sur les marchés et aux intérêts des constructeurs et des consommateurs, en particulier dans le projet de Directive sur les Instruments de Mesure.

Le Bureau qui assure la gestion quotidienne du Comité et son développement, en apportant notre expérience aux jeunes Fédérations des pays qui frappent à la porte de l'Union Européenne, en prenant contact avec les Fédérations de constructeurs d'instruments de pesage à travers le monde, amenant de nouveaux membres au CECIP, comme l'Ukraine en 2000, en créant des liens avec les Fédérations de Chine, des Etats-Unis d'Amérique, de Russie ou du Japon.

Après les cinq années de présidence du Dr. Klaus Wurster, qui fut chaleureusement remercié pour le travail accompli, nous avons procédé à l'élection d'un nouveau Bureau dont la composition est la suivante:

<table border="1"><tr><td>Président</td><td>Tim Cooper
Fédération Royaume-Uni</td></tr><tr><td>Vice-Présidente</td><td>Caroline Obrecht
Fédération Suisse</td></tr><tr><td>Vice-Président</td><td>Fabio Martignoni
Fédération Italie</td></tr><tr><td>Vice-Président</td><td>Klaus Wurster
Fédération Allemagne</td></tr><tr><td>Secrétaire Permanent</td><td>Michel Turpain
Fédération France</td></tr></table>

Nos amis hollandais avaient parfaitement organisé cette Assemblée Générale dans le cadre verdoyant d'un superbe centre de congrès, le Herrlickheijd Van Ermelo. Cette journée de travail fut suivie d'une visite des polders, avec une station de pompage à vapeur et découverte du site de Schokland. Merci à nos amis Hollandais et à l'année prochaine en Suisse!

CONTACT INFORMATION:

Mr. Michel Turpain – Permanent Secretary

CECIP

(Comité Européen des Constructeurs d'Instruments de Pesage)

Domaine d'Armainvilliers

4 Impasse François Coli

F-77330 Ozoir La Ferrière, France

E-mail: turpain.cecip@wanadoo.fr

CONFERENCE

<div align="center">

# The First Middle East Metrology Conference and Exhibition

</div>

![](page=4,bbox=[875, 279, 1011, 419])

Bahrain

6-8 May 2002

MAJEED AL GASSAB, Technical Committee Chairman

The Ministry of Commerce & Industry - Directorate of Standards and Consumer Protection - organized the First Middle East Metrology Conference and Exhibition from 6 to 8 May 2002 at the Gulf International Convention Centre, Gulf Hotel, Bahrain. This article summarizes the Panel Discussions held on 8 May.

The Panel Discussion took place on 8 May 2002 at the GICC, Gulf Hotel. The members of the panel included:

- Dr. Stephen Carpenter

- Dr. Hidetaka Imai

- Dr. Eberhard Seiler

- Mr. Vivian Linacre

- Dr. Gerard Faber

- Col. Sameer A. Al Zayani

Col. Sameer opened the discussion by thanking the visiting speakers and delegates for their active participation in the Conference, and said that the Conference Committee was very proud to host this first event in Bahrain. He then invited the keynote speakers to express their comments and suggestions:

Dr. Imai thanked the Ministry of Commerce and Industry and members of the Organizing Committee for their excellent organization of all the presentations. He added that this should encourage regional metrology laboratories to increase local awareness of laboratory services.

Dr. Seiler emphasized that trade with partners around the world must employ systems that were in harmony with international trends, including certificates that were on a par with those used internationally; he praised the efforts made by Bahrain to be the first in initiating this move. He recommended that the region consider joining various international organizations in order to implement international recommendations, since it was easier to look towards neighboring countries to establish a system in a complimentary way. He again emphasized that it was of importance for the private sector to employ the services of local laboratories to both save money and use available resources, thus making Bahrain a focal point on the international scene.

- On behalf of the British Weights and Measures Association (BWMA) Mr. Vivian Linacre thanked the Ministry of Commerce and Industry and the Conference Committee for the opportunity to attend the event. He went on to voice two concerns and one recommendation:

He had observed that there was a lack of education among both the public and clients as to the potential of the science of metrology; he felt that many were unaware of the vast scope of this subject. It was an immense but necessary task to communicate more about this subject to the outside world in the future.

- Secondly, he emphasized that the structures for the administration and pursuit of metrology between officials and regulators were very sophisticated. There was a lack of representation at the technical/practical level, as suggested earlier.

Finally, he recommended that Bahrain should lay the foundation stone for the International Institute of Metrology in order to instigate a future biennial conference on this subject. This Institute would not only be an organization to implement standards for the benefit of an organization but also as a general rule for all technicians and others to become direct members of this organization for the overall benefit of all those involved.

Mr. Gerard Faber thanked the Committee and greatly appreciated the presentations made by the Keynote and other speakers, and made the following recommendations:

- Start the preparations for the $ 2^{\mathrm{n d}} $ Metrology Conference as soon as possible.

- Focus the next Conference on Middle East priorities, but in relation to other countries.

Publicize the next Conference widely, and ensure that there is sufficient awareness as to its outcome and the recommendations it makes, especially

ensuring that the latter are communicated to all government officials and to both the public and private sectors.

- Increase cooperation in the Middle East, and build up strong ties for the next Conference.

- The Middle East countries must play an important role in global metrology.

- The key decision makers should invest in metrology applications on a regional basis and utilize each other's capabilities rather than come up with stand-alone solutions.

Dr. Stephen Carpenter praised the movement on metrology which had started in Bahrain, paving the way towards successful future Conferences. He emphasized the need for efforts to be incorporated regionally within each member state, since the latter have different needs and thus require expertise in regional areas.

He also supported the idea of a biennial Conference on Metrology and to encourage universities to send more students to attend the various presentations.

He encouraged the involvement of the technical vendors and companies dealing with metrology to participate in - and indeed set up - more workshops during the Conference and exchange new ideas and technology.

Col. Sameer closed the session by thanking delegates for their participation and requested them to spread awareness of metrology so that more delegates could participate in future Conferences. He also mentioned that Mrs. Ghaiet-El-Mouna Annabi had recommended the implementation of a regional coordinating office (or regional coordinator) for the OIML to represent the Arab region. He then opened the floor for discussion and delegate questions.

## Delegate questions

## 1. The benefit of being an OIML Member State or Corresponding Member

Mr. Faber replied briefly to this question by saying that in essence, a Member State has voting rights whereas a Corresponding Member does not. Whilst he regretted not having enough time to go into more detail, individual delegates were more than welcome to contact him for more detailed information. Based on this he once again encouraged regional representation at the OIML.

## 2 Conference publicity

Some delegates pointed out that there was a lack of publicity and asked the organizers to ensure maximum publicity for the next Conference, since a large number

of potential participants in Saudi Arabia working in metrology and its applications had received the information too late.

## 3 Regional Metrology Committee

A delegate from the United Arab Emirates suggested that the Technical Committees in GCC countries might assist in the Conference budget by forming a Regional Metrology Committee to address the immediate metrological requirements and needs and also future Conferences.

## 4 Technical papers

A delegate from Bahrain suggested that some of the technical papers could have been modified to provide more knowledge on how to ensure that metrology had the greatest impact and the highest degree of influence on industry.

## 5 Ways to improve measurement standards

Dr. Bruno Vaucher asked that the needs of the region in health and trade measurements be established, and also the possibility of calibration conformance measurements with the involvement of the customer in the process, using existing facilities in improving measurement standards.

## 6 Regional calibration laboratory services

Regional calibration laboratory services should be developed and promoted and an accreditation body established in the region, i.e. to identify a national calibration laboratory by identifying national and regional standards requirements.

To conclude, two recommendations for the future were voiced:

Dr. Vaucher congratulated the Ministry of Commerce and Industry for organizing this First Middle East Metrology Conference and Exhibition and for giving the participants an insight into the different fields and aspects of metrology. His views and suggestions as to the next steps to be taken were:

- To focus on the setting up regionally of a Metrology Institute/Organization with the necessary infrastructure in which Bahrain would be an important partner and could take over the leadership in cooperation and coordination activities (since technical competence is built up by laboratory work, skills and experience).

- To begin by establishing the needs according to the existing or planned industrial production and available services, as well as according to the local

situation in trade, health services, environmental protection or other fields in which measurements are needed.

- To study the possibility of performing calibrations, testing and conformity assessment in order to serve the local needs faster and in a less expensive way than being dependent on geographically distant infrastructures, but also to consider carrying out these measurements for overseas customers and to participate in the "Testing business".

- To build up an accordingly decentralized but practical infrastructure calling on the advice and support of experts having the overview, technical experience and competence in the corresponding fields.

Dr. Seiler made some recommendations for the development of metrology in Bahrain:

- Set up a Metrology Committee under the chairmanship of the Ministry of Commerce and Industry with representatives from the private sector, other Ministries (e.g. Health, The Environment and the Armed Forces) and to set up the task to initiate, supervise and follow-up on the necessary activities.

- Carry out a "Needs assessment" and a survey on existing metrology laboratories in the country.

- Draw up a master plan for the development of metrology.

- Increase contacts/coordination with GSMO and other National Metrology Institutes and Organizations across the world and make use of expert knowledge

Symposium Report

by Roberto Luiz

de Lima Guimarães,

INMETRO

<div align="center">

# INMETRO

</div>

<div align="center">

# International Meeting on Metrology and Quality

</div>

<div align="center">

# - Tools for Competitivity

</div>

![](page=6,bbox=[1640, 1350, 1786, 1557])

9-12 April 2002, Rio de Janeiro

## Introduction

The International Meeting on Metrology and Quality was organized by Inmetro and was attended by 61 experts from 21 European and American countries, in Rio de Janeiro, Brazil.

The Symposium was opened by the Minister of Science and Technology and by the Head of Inmetro, Mr. Armando Mariante. The President of Brazil and the Minister of Development attended the official closing session. The President of Brazil delivered a very impressive speech on the role of Inmetro and the importance of Metrology and Quality for the sustained development of Brazil.

The Symposium was attended by some thousand participants, and 136 parallel sessions were organized on the following themes:

a) Metrology

b) TBT Agreement

c) Conformity Assessment

d) Accreditation

## The Legal Metrology Seminar

The program of Legal Metrology shared a wide variety of information concerning three importants sub-themes:

- Software applied to measuring;

- Ways of performing metrological control; and

## Conclusion

- Measurement in custody transference and legal measurement of petroleum products.

The meeting was an important forum for discussions on Metrology and Quality and represented a positive contribution to develop an integrated view on Metrology and Quality, fostering the cooperation between these two key issues in modern trade and industry.

situation in trade, health services, environmental protection or other fields in which measurements are needed.

- To study the possibility of performing calibrations, testing and conformity assessment in order to serve the local needs faster and in a less expensive way than being dependent on geographically distant infrastructures, but also to consider carrying out these measurements for overseas customers and to participate in the "Testing business".

- To build up an accordingly decentralized but practical infrastructure calling on the advice and support of experts having the overview, technical experience and competence in the corresponding fields.

Dr. Seiler made some recommendations for the development of metrology in Bahrain:

- Set up a Metrology Committee under the chairmanship of the Ministry of Commerce and Industry with representatives from the private sector, other Ministries (e.g. Health, The Environment and the Armed Forces) and to set up the task to initiate, supervise and follow-up on the necessary activities.

- Carry out a "Needs assessment" and a survey on existing metrology laboratories in the country.

- Draw up a master plan for the development of metrology.

- Increase contacts/coordination with GSMO and other National Metrology Institutes and Organizations across the world and make use of expert knowledge

Symposium Report

by Roberto Luiz

de Lima Guimarães,

INMETRO

<div align="center">

# INMETRO

</div>

<div align="center">

# International Meeting on Metrology and Quality

</div>

<div align="center">

# - Tools for Competitivity

</div>

![](page=7,bbox=[1640, 1350, 1786, 1557])

9-12 April 2002, Rio de Janeiro

## Introduction

The International Meeting on Metrology and Quality was organized by Inmetro and was attended by 61 experts from 21 European and American countries, in Rio de Janeiro, Brazil.

The Symposium was opened by the Minister of Science and Technology and by the Head of Inmetro, Mr. Armando Mariante. The President of Brazil and the Minister of Development attended the official closing session. The President of Brazil delivered a very impressive speech on the role of Inmetro and the importance of Metrology and Quality for the sustained development of Brazil.

The Symposium was attended by some thousand participants, and 136 parallel sessions were organized on the following themes:

a) Metrology

b) TBT Agreement

c) Conformity Assessment

d) Accreditation

## The Legal Metrology Seminar

The program of Legal Metrology shared a wide variety of information concerning three importants sub-themes:

- Software applied to measuring;

- Ways of performing metrological control; and

## Conclusion

- Measurement in custody transference and legal measurement of petroleum products.

The meeting was an important forum for discussions on Metrology and Quality and represented a positive contribution to develop an integrated view on Metrology and Quality, fostering the cooperation between these two key issues in modern trade and industry.

SEMINAR PTB

![](page=8,bbox=[825, 275, 889, 338])

<div align="center">

# Introduction to Metrology

</div>

Abidjan, Ivory Coast 4-7 June 2002

DR. ULRICH DIEKMANN, PTB

IAN DUNMILL, BIML

## Introduction

This seminar was a follow-up to the workshop held in Ouagadougou, Burkina Faso in December 2001. It was organised by the Physikalisch-Technische Bundesanstalt (PTB), the West African Economic and Monetary Union (UEMOA) and the Ivory Coast National Laboratory of Testing, Quality, Metrology and Analysis (LANEMA) with support from the local office of the German Development Cooperation (GTZ). It took place at the offices of the International Labour Organization in Abidjan, Ivory Coast and was part of the regional project "Encouragement of metrology and testing systems in West African Countries" financed by the German Federal Ministry for Economic Cooperation and Development (BMZ). This project aims to encourage metrology and testing activities through regional networking so as to contribute to the removal of technical barriers to trade in recipient countries.

## The seminar

The objective of the seminar was to provide an introduction to legal metrology and to brief local decision makers about the role of metrology for economic development and consumer protection.

A total of 37 people participated in the seminar, representing the administrations and industries of the following countries in the region: Benin, Burkina Faso, Ivory Coast, Ghana, Guinea, Guinea-Bissau, Mali, Niger, Senegal and Togo.

## Opening ceremony

The seminar began with a formal introductory session, attended by the Minister of Industry and Promotion of the Private Sector and the German Ambassador to the Ivory Coast, during which the PTB project was presented and an introduction to the OIML was given.

## Training sessions

During the first two days, the following training sessions were given:

Fundamentals of metrology (George G. Koré, LANEMA);

Economic and social tasks of legal metrology (Ian Dunmill, BIML);

Legal metrology legislation and national and international structures (Ian Dunmill, BIML); and

The development of metrology in the European Union - the example of Germany (Wolfgang Kieninger, Stuttgart Weights and Measures Office).

These sessions enabled an exchange of experience, and were considered valuable by the majority of the participants.

## Evaluation of legal metrology questionnaire

Ulrich Diekmann (PTB) presented the results of a questionnaire on legal metrology, which had been circulated following the last meeting in Burkina Faso. As well as giving an idea of each country's mass and volume capabilities, the results of this questionnaire showed that there was generally:

A need for training and improvement of personnel in conducting verifications, particularly for mass;

A need for standards of mass and volume;

A lack of premises and laboratories; and

A need for the establishment of traceability.

## Technical visits

On the third day of the seminar, the participants were able to visit some public and private metrology and testing laboratories, in order to gain an appreciation of the implementation of some of the principles already discussed.

## Future actions

The following future actions were agreed:

A training seminar on mass will be held in Benin in September 2002;

A training seminar on volume will be held in December 2002 in Guinea;

A third workshop will be held in March 2003 in Senegal to examine the progress made within the project;

A questionnaire concerning industrial metrology will be circulated;

A technical working group on mass will be established;

A technical working group or committee will be established to examine the harmonisation of legislation.

## Contact information:

Dr. Ulrich Diekmann, PTB

Tel.: +49 531 592 8224 - Fax: +49 531 592 8225

E-mail: ulrich.diekmann@ptb.de

Ian Dunmill, BIML (id@oiml.org)

The International Metrology Congress is organized every two years by the French College for Metrology and is a meeting place for the exchange of information between people involved in scientific and industrial fields through:

oral presentations and poster sessions

round tables

the exhibition of 45 stands

technical visits

## The aims of the Congress are:

to bring forth and to highlight new techniques of measurement and calibration that have been or are being developed,

to present the evolution of metrology, and its implication in industry, research, environment and safety, economy and quality, at the national and international level.

The Congress currently gathers together more than 600 people from 30 different countries, and from every circle concerned with measurement:

metrologists from companies,

metrologists from calibration, analysis and testing laboratories,

manufacturers and users of metrological equipment,

quality managers,

teachers and researchers.

## Control of measurement, analysis and testing process

economical impacts:

costs optimization

technical aspects:

traceability - measurement uncertainties - interlaboratory comparisons - calibration - verification

quality insurance aspects:

accreditation - training and qualification of staff - competence - certification -

organization of the metrology function

standardization aspects

legal metrology...

![](page=9,bbox=[1268, 901, 1821, 1672])

## Economic fields

agrofood - industry - biology - chemistry - electronics - energy - environment - health - mechanical engineering industry - pharmacy - service providers - transport

## Physical and chemical fields

mass - force - flow - pressure - acceleration - dimensional - electricity - magnetism - time-frequency - temperature - hygrometry - optics - radiometry - photometry - reference material standards - ionizing radiation ...

Papers are selected by a Scientific and Technical Committee and may be presented either in French or in English. Simultaneous translation will be provided.

## Contact information:

Sandrine Gazal - Maison de l'Entreprise - 429 rue de l'Industrie - CS 70003 - 34078 Montpellier Cedex 3 - France

Tel. +33 4 67 06 20 36 - Fax +33 4 67 06 20 35 - E-mail sandrine.gazal@wanadoo.fr

![](page=10,bbox=[279, 282, 799, 1013])

## Milestones in Metrology

NMi Certin B.V.

Pieter van Breugel

Managing Director

## Dear Relations of NMi,

Because of major changes expected in the near future, I strongly believe that a meeting between manufacturers, metrology institutes and regulators is necessary and beneficial for all of us. NMi is organizing such a meeting by means of a congress in the historical city Maastricht, the Netherlands.

One of the major topics will be the introduction of the Measuring Instruments Directive (MID) in Europe which is expected shortly. Questions like, how to meet the requirements of this Directive? How will self verification change? Which new opportunities for test laboratories and manufacturers will appear? will be dealt with. In addition, speakers from other countries or regions are also invited to present new developments. The intention is to present a global view.

This unique congress, with the name 'Milestones in Metrology' is not to be missed. From March 30 through April 2, 2003 participants from all over the world will receive the latest information on global, regional or national developments. Together we will build a clear picture of the near future. It will be very efficient for everybody to update the international vision on metrology, international market access and market surveillance in only two and half days. All this knowledge will be brought to you by interactive presentations, discussions and workshops. During the workshops small groups will discuss cases with experts from all over the world.

Besides the attractive scientific Programme, in the evening Maastricht gives you an excellent opportunity to recover from the daytime activities, visiting the numerous marvelous restaurants and sightseeing the oldest roman town of the Netherlands.

I look forward to meeting you at Milestones in Metrology!

## Congress Language

The official conference language is English.

## Congress Venue: Maastricht Exhibition and Congress Centre

Maastricht Exhibition and Congress Centre (MECC) near the city centre and close to the hospital and University facilities. Hotels will be available within a short walking distance from the MECC. If you would like further information, please fill in the registration form (see web site).

## Maastricht, Congress Site

Situated close to the borders of Belgium and Germany, the Roman city of Maastricht has a cosmopolitan atmosphere. It is the capital of the province 'Limburg' in the southernmost part of the Netherlands. To visit Maastricht is like travelling through time. Walk on Roman cobble stones from 150 BC and visit the halls where the Maastricht Treaty was signed in 1992. Enjoy Maastricht's skyline of church spires and towers and its tree-lined squares. But also be sure not to miss 'In den Ouden Vogelstruys', the Netherlands' oldest pub. We guarantee that Maastricht and its people will delight and charm you.

## Accommodation

Maastricht's lodging facilities are varied and of outstanding quality. Best of all, almost all of the hotels are situated in the city centre. The Organizing Secretariat has reserved rooms in various hotel categories. Hotel rooms are guaranteed until January 30, 2003.

http://www.conferenceagency.com/milestonesinmetrology/homepage.htm

## Programme

March 30, 2003 - Arrival

- Arrival of the congress participants during the afternoon / early evening

- Welcome gathering

- March 31 - April 2, 2003 - Introduction to the MID

- Role of the OIML

- Role of WELMEC

- Role of Notified Bodies

- Role of Manufacturer

- How to comply with the MID?

- Transition Period

- Normative documents / harmonised standards

- Test procedures

## Global Market Access

- OIML Mutual Acceptance Arrangements (MAA's)

- Mutual Recognition Agreements (MRA's) worldwide

- Regional Legal requirements

## Market Surveillance

- Self-verification under the MID

- Metrology College

- Available Training

The OIML is pleased to welcome the following new

CIML Member

Republic of Korea Mr. Lee, Yeon-Jae

## OIML Meeting

21-22 October 2002

Delft (The Netherlands)

OIML TC 5/SC 1 Electronic Instruments

Revision of OIML D 11

www.oiml.org

Stay informed

## Committee Drafts

received by the BIML, 2002.05.01-2002.07.31

Revision of D 11: General requirements for electronic measuring instruments

Revision of R 61-1 and R 61-2: Automatic gravimetric filling instruments

Revision of D 1: Law on Metrology

![](page=11,bbox=[272, 2166, 1125, 2522])

In the January 2003 Edition:

Full accounts of the Saint-Jean meetings