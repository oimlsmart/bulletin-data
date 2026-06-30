ISSN 0473-2812

BULLETIN

DE

![](page=0,bbox=[1363, 395, 1767, 653])

[

![](page=0,bbox=[193, 750, 326, 884])

RGANISATION

INTERNATIONALE

DE METROLOGIE LÉGALE

![](page=0,bbox=[110, 1486, 1882, 2401])

<div align="center">

# BULLETIN de

</div>

<div align="center">

# I'ORGANISATION INTERNATIONALE de MÉTROLOGIE LÉGALE

</div>

## SOMMAIRE

ALLEMAGNE – Personal computers as part of measuring instruments subject to verification

by U. GROTTKER and J. GLIMM ... 3

ALLEMAGNE – Computers used as auxiliary measuring devices in legal metrology

by R. OHL ... 10

ROYAUME-UNI – Examination and testing of peripheral equipment

connected to non-automatic weighing instruments

by P.D. EDWARDS and P.C. KNOWLES ... 18

Air humidity and air density determinations in metrology laboratories

by S.A. THULIN ... 32

INFORMATIONS

Literature (in English) ... 40

Réunions OIML/Meetings ... 43

DOCUMENTATION

Publications ... 44

États membres de l'Organisation Internationale de Métrologie Légale ... 51

Membres actuels du Comité International de Métrologie Légale ... 52

Adresses des Services des Membres Correspondants ... 57

Europe : 175 F-français

Abonnement pour 1991 :

Autres pays : 230 F-français

Chèques postaux : Paris 8 046-24 X

Banque de France : B.P. 140-01 - 75049 Paris Cedex 01

Comptes Courants, Banques Étrangères, Compte n° 5051-7

BUREAU INTERNATIONAL DE MÉTROLOGIE LÉGALE

11, Rue Turgot - 75009 Paris - France

Tél. 33 1 48 78 12 82 Le Directeur : Mr B. ATHANÉ

et 42 85 27 11 Téléfax : 33 1 42 82 17 27

Télex : 234 444 SVP SERV F ATTN OIML

<div align="center">

# PERSONAL COMPUTERS as PART of MEASURING INSTRUMENTS SUBJECT to VERIFICATION

</div>

by U. GROTTKER and J. GLIMM Physikalisch-Technische Bundesanstalt

SUMMARY - This paper was presented at the OIML seminar "Weighing in Braunschweig" 15-18 May 1990.

The authors review the problems associated with the pattern evaluation of measuring instruments connected to personal computers as regards metrological reliability, data security and protection against manipulations.

They also describe a prototype of data security kernel for personal computers developed at PTB.

## 1. The problem

It is not only for economical reasons that users and manufacturers alike want personalcomputers (PCs) to become more and more part of modern measuring instruments but also, because:

- the cost-benefit-relation is good,

- parameters of the measuring instrument can be easily adapted to different applications, and

- the PC can also be used for any other than legal metrology purposes at the same time.

This very fact shows the tradeoff in granting pattern approval to software-controlled measuring instruments: as manifold functions of such instruments can be, as manifold are ways of manipulation too. The test engineer (approval officer) must decide, which of the rather complex PC-functions can be tolerated and stay open for use and which facilitate manipulations and therefore must be technically blocked. The test engineer must have profound knowledge of PChardware and software in order to be able to make appropriate decisions.

This PC-related problems is a new part of the general question: how can metrological requirements be met by software-controlled measuring instruments, i.e. how reliable is the hardware and especially, how reliably can metrological data subject to verification be processed by the PC.

But from the legal metrology point of view it is not possible to allow free user programmability of measurement functions subject to verification. Once certified, these functions must not be changed or overruled by false or intended operation.

Assuming, there exist requirements to answer these questions it is often difficult to actually test and verify during pattern approval whether these requirements have been met. Because of the realization of measuring functions by software means it is necessary to rethink or extend the pattern approval procedure.

2. Requirements on Personal-Computers as part of measuring instruments

## 2.1 Metrological reliability

Answers to the question which levels of metrological reliability and protection against manipulations are necessary for a software-controlled measuring instrument subject to verification certainly depend on its class of application.

In general, measurement tasks in legal metrology split up in three significantly different classes of application [1], [2]:

- repeatable measurements

- nonrepeatable measurements

- noninterruptable measurements

They are necessary because they are governed by significantly different characteristics. For non-automatic weighing instruments two options are open for repeatable measurements:

- incorporation of checking facilities

- highly reliable equipment design

both popping up overall metrological system reliability to an appropriate or required level (though undefined yet).

In other metrological application classes different, i.e. more sophisticated or more complicated measures must be taken, e.g. switch off gasoline pump or activate (automatically) redundancy to maintain required uninterrupted system operation in case of failures, to achieve sufficient metrological reliability.

Metrological reliability dealing with software related problems is called software reliability. This is the probability of failure-free operation of a computer program for a specified period of time. Critical to understanding the significance of software reliability is the distinction between the event of a "failure" and the status of a "fault". Any beginning of a situation where a program does not function so as to meet user needs is a failure, whereas a fault is the actual defect in the program code that causes the failure.

The reliability of a program is affected by three factors: introduction of unintentional faults, removal of faults, and the way the software is being used [3]. Reliability of a program first can be improved if the programmer considers certain rules of good programming practice in constructing the software. Moreover the software should be tested exhaustively and faults should be removed before the software is distributed or used until the failure rate falls below a certain limit.

Requirements for software reliability have not been defined by PTB yet. Concerning the approval procedure up to now, software reliability was left out of consideration. Measuring instruments will be more and more complex and the significance of the standard testing method - the

black-box test - decreases. The objective should be to achieve the same quality level of the pattern approval procedure with complex instruments as with conventional ones. This in some cases seems possible only by verifying their software. Since this is very costly a compromise must be found between quality of verification and cost. The extent of the verification should depend on:

- the possible consequences of a malfunction of the measuring instrument, distinguishing personal harm and property damage

- the requirements on a conventional measuring instrument of the same type

- the required protection level against manipulations

- the functional characteristics of the instrument.

## 2.2 Data security, protection against manipulations

Main concerns with software-controlled (programmable) measuring instruments in legal metrology are hacking, intrusion and manipulation, leading to change or deletion of measurement data or altering program code. A probabilistic approach answering the question: "How many erroneous measurement results versus time because of manipulation may be expected?" does not seem to be possible at the moment. Human intuition and phantasy for breaking protection means can hardly be quantified.

It has been generally recognized that any protection measures against manipulations can be overcome by intelligent hacking. But protection against intentional (criminal) attacks is not the aim of regulations in the legal metrology area. On the other hand, operators of measuring instruments must be prevented to bypass protection measures easily by using standard software tools or even by unintentional false operation.

In order to determine and test the security level of measuring equipment in a practical way, a prototype of a measuring instrument with PC has been designed and constructed during a R&D- project in PTB. Guideline in constructing the protection hard- and software were five general requirements derived from the German Law of Verification, dealing with protection against loss of data and/or manipulation of program code. They may form a general basis for pattern approval procedures of software-controlled measuring instruments in legal metrology.

A catalogue of requirements for software-controlled measuring instruments could read as follows:

1) Make sure that measurement data stored anywhere in the computer system cannot be falsified.

It covers protecting measures during runtime of certified programs as well as measures to protect data stored on floppy disks or during transmission in open networks. Manipulating, changing, deleting or adding data must be either prevented or at least marked in the dataset. Deleting of the hole dataset does not need to be prevented if one deals with repeatable measurements.

In an open computer-system like a PC, data can be falsified indirectly e.g. by changing a program. Therefore more requirements are necessary:

2) Make sure that approved, certified, or licensed software cannot be altered accidently or on purpose.

Again different measures are needed when running approved programs and during storage e.g. on a floppy disc.

3) Make sure that relevant measurement data can be accessed, processed, transmitted or displayed and safely stored in mass storage devices by approved programs only.

4) On a multi-tasking and/or multi-user system: Make sure that the relevant approved program gains highest priority. It must be ready for being called at any instant of time and must run without disturbance or interruption from other programs.

5) Make sure that measurement output data on a display unit be marked clearly as "verified measurement results".

## 3. Description of the PTB prototype

In PTB, a data security kernel for personal-computers has been developed according to the above mentioned requirements. The special features of the kernel are:

- program modules subject to verification can be loaded with high protection against manipulation,

- combinations of normal functions and functions subject to verification are possible,

- all metrological data security requirements are met on a high level in all operating phases.

Nevertheless the user of the PC does not need to dispense with the main normal functions of the PC. The kernel allows that the PC is:

- almost freely applicable for normal purposes other than legal metrology even when functions subject to verification are active at the same time,

- freely applicable for normal purposes when no functions subject to verification are active.

When running, programs and data are protected by additional hardware (Fig. 1). On the PC-board there is a program memory for firmware containing:

- software for controlling the hardware on the board,

- software for loading a program module subject to verification and for encrypting and decrypting data and programs,

- software for controlling the display layout.

The address decoder in figure 1 watches memory areas which are reserved for programs and data subject to verification. If it detects a program running in such an area it triggers the mode switch and turns the computer into a verified mode. Only in this mode the interrupt trigger is inhibited if a write access to a reserved data area occurs. Else an interrupt is sent to the CPU on every write operation in a reserved memory area. The interrupt-service-routine which in this case displays a message and turns the computer into its non-verified mode, is part of the firmware.

![](page=7,bbox=[1609, 2719, 1845, 2773])

![](page=8,bbox=[344, 387, 1602, 1118])

<div align="center">

Fig.1 - Master controller of the data security system

</div>

![](page=8,bbox=[386, 1234, 1527, 2300])

<div align="center">

Fig. 2- Generation of a loadable program module subject to verification

</div>

Using a CPU adapter gains highest priority for the interrupt signal. A timer triggers the control software cyclically for polling the measuring values refreshing the display etc.

Even if the computer is in the non-verified mode and the display is used for other than legal metrology purposes, a message is being displayed to prevent the observer from being deceived by a falsified screen format.

This hardware unit cannot directly prevent data or programs from being falsified during storage on floppy or hard disk. But it is required that any falsification is at least traceable afterwards. For this reason additional protection measures are necessary. In the prototype an authentification method based on the RSA algorithm [4] is applied.

As an example which was realised during a research & development project with the PTB prototype, the step by step procedure of generating and approving a protected loadable program module with a modern encryption method could read as follows (Fig. 2):

1) The manufacturer submits the compiled program code to PTB.

2) PTB would apply the RSA algorithm to the program code by means of a secret key and generate an electronic signature.

3) The manufacturer would distribute the protected program together with the electronic signature to his customers.

4) The program module subject to verification could only be started, if it were authentical. This would be verified by the data security kernel consisting of the above described hardware and firmware.

The decryption software would use another key, which would not have to be kept secret. This public key would then be applied to the electronic signature just before starting the program module subject to verification.

## 4. Conclusion

New technology in measuring instruments subject to verification requires rethinking and extending the pattern approval procedures in legal metrology. The valuation of measuring instruments with personal computers is possible today, but there are not so many experiences yet. It is not possible, however, to calculate a characteristic value for the level of data security against manipulations. The methods to calculate such values for software reliability are uncertain compared to those for hardware reliability. An objective of future R&D work is to rationalize the valuation of software-controlled measuring instruments using software tools based on artificial intelligence.

## References

[1] J. Glimm

Über die Zuverlässigkeit eichpflichtiger Meßgeräte (On Reliability of Measuring Instruments Subject to Verification),

in German

PTB-Mitteilungen 93 (1983) 1, pp. 15-20

[2] J. Glimm, U. Grottker Zuverlässigkeit von Komponenten für Meßsysteme im gesetzlichen Meßwesen (Reliability of Subsystems for Measuring Systems in Legal Metrology), in German VDI-Berichte (of TTZ'89) No 771 (1989), pp. 121-131

[3] J.D. Musa, A. Iannino, K. Okumoto Software Reliability - Measurement, Prediction, Application McGraw Hill, Singapore 1987

<div align="center">

# COMPUTERS USED AS AUXILIARY MEASURING DEVICES IN LEGAL METROLOGY

</div>

by R. OHL Physikalisch-Technische Bundesanstalt

SUMMARY - This article is based on a paper presented at the OIML seminar "Weighing in Braunschweig" 15-18 May 1990. It deals with the legal requirements applicable to interfaces used to connect computers and other auxiliary measuring devices to main measuring instruments and refers in the discussion to the provisions of OIML R 76-1 (1988). This Recommendation is presently being revised and supplemented in line with the proposals by the author.

## 1. Introduction

Communication and data technology are becoming more and more important in weighing. As far as legal metrology is concerned requirements to be met by metrological guarantee and manipulation security must be regarded in addition to reasonable application. In the Federal Republic of Germany measuring instruments and auxiliary devices are subject to mandatory verification if they are used for legal purposes; therefore, e.g. auxiliary programmable control computers and computer managed data storages must be examined along with the interfaces and communication devices. The security level to be maintained for weighing instruments so far must be considered.

This is a contribution to the discussion of typical problems arising when measuring systems are to be approved for verification. Developing measuring instruments subject to mandatory verification, into modular systems with components connected via interfaces, some of which are programmable, presupposes that these systems meet special requirements with regard to reliability and safety against inadmissible manipulation. Some of the results obtained at the PTB will be described here.

A survey will first be given of the legal regulations in the Federal Republic of Germany governing mandatory verification and exemptions from mandatory verification for auxiliary measuring devices. They will be explained by the example of a weighing system. The requirements to be met by interfaces will then be dealt with and the related test criteria described.

![](page=12,bbox=[325, 379, 1586, 1150])

<div align="center">

Fig. 1 - Example of interface connecting measuring instrument and auxiliary measuring device

</div>

## 2. Terminology

## Peripheral interface

The term "peripheral interface" (ISO 7498 and DIN 44 302) covers all specified physical, electrical and logic functions at the interchange point which allow measuring instruments and subassemblies or auxiliary measuring devices to be connected (Fig. 1).

## Non-interacting auxiliary measuring devices

An auxiliary measuring device is considered non-interacting in the sense of the German verification law when the interface on the measuring instrument used to couple the instruments is non-interacting, i.e. it does not affect the measured values in the measuring instrument.

## Inadmissible influences

There is an inadmissible influence if the interface allows measurement values to be falsified or can release functions which falsify the measurement value.

## Correctness and safety of data transmission

Data transmission is considered correct if the data transmitted by the interface correspond to the measurement data or signals in the measuring instrument subject to mandatory verification, the interfaces meet the same standards and detection and correction of transmission errors are possible.

## 3. Legal bases for the treatment of auxiliary measuring devices

## 3.1 The International Recommendation OIML R 76-1

Clause 5.4.4 of the OIML Recommendation for non-automatic weighing instruments (R 76-1) provides that a weighing instrument may be coupled with external equipment via an interface. The equipment concerned may be computers or even programmable instruments. It is required that in spite of the connection of external equipment, the electronic weighing instrument shall continue to function correctly and its metrological functions shall not be influenced. The problem of how to judge and test the correct function of the weighing instrument and ascertain whether its metrological function remains uninfluenced leads to the problem of appraising the interface of an electronic weighing instrument. The test method and the criteria have not yet been described in OIML R 76-1. In the following a solution to the treatment of interfaces and auxiliary devices will be described.

## 3.2 Legal regulations in the Federal Republic of Germany

To be able to put into practice the requirements, which auxiliary measuring devices must meet, regulations have been drawn up on the basis of German laws, which have been published as PTB Requirements for interfaces and auxiliary measuring devices (PTB-A 50.1 [4]). Reference will be made here only to the most important legal aspects.

In the Federal Republic, legal metrology is, among other things, subject to the following prescriptions and regulations:

- Metrology and Verification Act [2]

- Verification Ordinance [3]

- Appendice to the Verification Ordinance

- PTB Requirements

- PTB Directives

- PTB Testing Instructions

- Verification Instructions

The Metrology and Verification Act provides special legal requirements for many measuring instrument categories, for example, mandatory verification when these instruments are used for special purposes, e.g. in the field of medicine, in official transactions or commercial dealings. Among other things, the Appendices to the Verification Ordinance state the maximum permissible errors on verification. PTB Requirements describe, for example, criteria for the testing of measuring instrument categories at pattern approval.

Other regulations, such as the PTB Testing Instructions, Directives and Verification Instructions specify the test procedures and describe the equipment to be used for testing, or they are administrative regulations.

The most important aim of the verification system is to protect the citizen from false measurement values in order to prevent injustice, health hazards and loss of property. Section 9 of the Metrology and Verification Act therefore requires correctness and sufficient durability of the measuring instrument as the prerequisites for their being approved for verification. Measuring certainty covers both the long-term behaviour and the safety against operating errors and inadmissible manipulation of the measuring instrument.

According to section 5 of the Metrology and Verification Act, auxiliary measuring devices are in general equivalent to measuring instruments which means that they are subject to mandatory verification when they are used in transactions for which the use of verified measuring instruments has been prescribed. Under certain conditions (for example, section 9 Verification Ordinance), in the case of non-interaction, auxiliary indicating devices, printers, memories, processing devices, additional evaluation instruments, however, are exempted from mandatory verification; in contrast to this, auxiliary measuring devices are always subject to mandatory verification if an unpermitted interaction between them and the measuring instrument is possible.

![](page=14,bbox=[454, 1023, 1585, 2025])

The Measuring Instrument is subject to mandatory verification

The Printer (or Storage) is approved and verified

All additional auxiliary devices are exempt from mandatory verification in the case of non-interaction on the measuring instrument

<div align="center">

Fig. 2 - Weighing system as an example of the exemption from mandatory verification of auxiliary devices under German law

</div>

## 3.3 Auxiliary measuring devices exempted from mandatory verification

It will be explained by the example of a weighing system (Fig. 2) how auxiliary measuring devices are treated under verification law. A modern weighing system often consists of several individual components.

In Fig. 2, the measuring instrument subject to mandatory verification is represented by individual components: by a transducer which converts the physical input quantity into an electric analog or digital quantity, by an electronic evaluating device with processes this quantity, and by an indicating device (primary or main indicating device) which displays the measured value. Auxiliary measuring devices are all instruments which are not essential to determine the measurement value. Among these are, for example, the printer, the secondary indicating device, the measurement data store and the connection to a programmable computer.

Exemptions from mandatory verification for auxiliary measuring devices are of particular importance for the setting-up of measuring systems. Section 9 of the Verification Ordinance specifies details, among other things for commercial transactions. Auxiliary measuring devices for commercial use as shown in Fig.1 are exempted if correctness and the possibility of checking the measured values are ensured by means of verified printers or memories and if they are operated via non-interacting interfaces.

As to the auxiliary measuring devices, a distinction is made between those which may exert an influence on the measuring instrument and those which are non-interacting. Only noninteracting auxiliary measuring devices may be exempted from mandatory verification. The same condition applies to the significant case if non-verified auxiliary devices are to be connected for use outside mandatory verification.

## 4. Treatment of interfaces upon pattern approval

The approval of a measuring instrument equipped with an interface is based on the respective appraisal criteria (durability, maximum permissible errors on verification) defined in the Appendix to the Verification Ordinance, in the PTB Requirements for the respective measuring instrument category and in the PTB Requirements for interfaces.

The test of peripheral interfaces covers the checking of the electric properties, galvanic isolation, the control lines and the transmission protocol as well as the instructions which can be transmitted via the interface. In the following the test criteria for peripheral interfaces are summarized.

## 4.1 Non-interacting Interfaces

To judge whether the interface is non-interacting, the interface is used as input for various influences whose effects on the measuring instrument are checked. The tests are:

In group 1, all interface circuits are alternately connected with one another. In addition, a positive and negative test voltage of 30 V is directly applied to the interface terminals, the interface mass serving as reference potential.

The tests according to group 2 are carried out by discharge of 150 pF via 150 $ \Omega $ . The respective loads are directly applied to the interface terminals. The mass of the measuring instrument, for example the protective conductor, serves as reference for these tests.

The tests according to group 3 are carried out with $ U_{\mathrm{eff}}=10\mathrm{V} $ in the range below 150 kHz and with $ U_{\mathrm{eff}}=1\mathrm{V} $ above 150 kHz. In this group, according to IEC 801, part 5 (draft), coupling is made either capacitively with the mass of the interface serving as reference, or inductively via a network.

- Climatic and EMC influences:

No separate test of the interface.

- Transmission control (e.g. transmission protocol, procedure, handshake signals): No inadmissible influence on the measuring instrument and on the sequence of measurements.

- Instrument control: All control functions (e.g. instrument control lines, instrument instructions, short-circuit and no-load operation of the transmission lines) and their effects on the measuring instrument must be permissible for non-interacting interfaces. The functions and effects permissible in the individual case of the interface depend on the category of measuring instrument and must meet the essential requirements.

## 4.2 Correctness and safety of data transmission

To judge the correctness, the interface is used as input and output of various influences whose effect on the measuring instrument and on the auxiliary measuring device is checked. The requirements are:

## Design:

Electrical properties must correspond with those of the auxiliary measuring device or be in compliance with the standard; transmission codes must be identical.

- Instrument control lines and instrument instructions:

Proper function, no inadmissible change of interface features (for example, switch off parity, switch over instruction set or transmission control).

## Correctness of data:

Agreement of data at the interface with the measured value in the measuring instrument subject to mandatory verification.

## Safety of transmission

Agreement between transmission controls in the measuring instrument and in the auxiliary measuring device. Sufficient transmission reliability owing to type of protocol, inherent redundancy, error detection and correction mechanisms, safety precautions on the instrument program level (for example: format and plausibility tests).

To ensure efficient testing of the interfaces, proved standard electrical properties and transmission protocols should be used, as they are described in international and German standards and in the PTB Directives 50.10 and 50.20. Upon pattern approval, the instructions and instrument controls important for judging non-interaction can then be checked much more easily and quickly than would be the case with differing or unknown interfaces.

<div align="center">

Table 1 - Testing of interfaces

</div>

<table border="1"><tr><td rowspan="3">classification</td><td colspan="4">The use of the interface</td></tr><tr><td colspan="2">in transactions requiring the use of verified measuring instruments</td><td>outside mandatory verification</td><td>none</td></tr><tr><td>A1</td><td>A2</td><td>B</td><td>C</td></tr><tr><td>correctness test</td><td>passed</td><td>passed</td><td>not tested or failed</td><td>not tested or failed</td></tr><tr><td>interaction test</td><td>failed</td><td>passed</td><td>passed</td><td>not tested or failed</td></tr><tr><td>exchangeability of auxiliary measuring devices</td><td>acc. to pattern approval certificate</td><td>acc. to pattern approval certificate</td><td>optional</td><td>none</td></tr><tr><td>protection upon verification</td><td>protected</td><td>non-protected</td><td>non-protected</td><td>protected</td></tr><tr><td>example of marking on the case</td><td>none</td><td>none</td><td>not for use in mandatory verification</td><td>none</td></tr></table>

A - in transactions requiring the use of verified measuring instruments

B - outside mandatory verification

C - no use planned

## 4.3 Classification of auxiliary measuring devices on the basis of the interface

To decide how interfaces are to be treated at pattern evaluation, it must be checked whether the use of the respective interface specified in the application is permissible. "Non-interaction" and "correctness" are the criteria on which this decision is to be based. Three cases (A,B,C) must be distinguished; they are dealt with in the following (cf. Table 1).

## 4.3.1 Auxiliary measuring devices subject to mandatory verification (case A)

Concerned are all interfaces of the measuring instrument for which the application for pattern approval provides the connection of auxiliary measuring devices (e.g. printers, indicating devices, memories etc.) or subassemblies subject to mandatory verification.

Non-interaction of the interface must have been tested, the correctness test must have been passed. The pattern approval certificate and the instructions for use of the measuring instrument, subassembly or auxiliary measuring device must clearly specify the devices which may be operated at the respective interface.

Regarding the treatment at verification, a distinction is made between two groups, depending on the interaction behaviour:

In the case of interacting interfaces (A1), the interconnection between instruments must be protected against changes. If the interface is not used, it must be sealed.

In the case of non-interacting interfaces (A2), the interconnection must not be protected, nor must it be sealed when the interface is not used.

## 4.3.2 Auxiliary measuring devices not subject to mandatory verification (case B)

Concerned are all interfaces of the measuring instrument for which the application for pattern approval provides the connection of auxiliary measuring devices not subject to mandatory verification (e.g. in-plant data processing, recording etc.), or of auxiliary measuring devices exempted from mandatory verification.

Only non-interacting interfaces may be used to connect auxiliary measuring devices not subject to mandatory verification. When interactions are detected, it is to be proceeded in accordance with case A1 or case C.

The requirements for non-interaction of the interface must have been met. The correctness of the interface is not tested. In the pattern approval certificate of the measuring instrument, the interface must be described as being "non-interacting", and the note "correctness not tested" or the like should be included. The interface must be suitably marked on the case by a note clearly comprehensible to the user. At verification, the interconnection must not be protected nor must it be sealed when the interface is not used.

## 4.3.3 Interfaces which have not been tested (case C)

Concerned are all interfaces of the measuring instrument which, according to the application for pattern approval, are not used and are not, therefore, to be tested, or such interfaces which neither meet the requirements for non-interaction nor those for correctness.

In the pattern approval certificate, they must be referred to as "not tested" and must not be used. Interfaces which have not been referred to in the pattern approval certificate or which have been described as "not tested" must be sealed at verification.

## 5. Conclusions

This article is an attempt to depict the problems which arise in connection with the measuring set-up and the evaluation of the results when pattern approval is to be granted, and of possible solutions to these problems. The intention is to initiate an exchange of experience on an international level.

## References

[1] OIML R 76-1 "Non-automatic weighing instruments", Edition 1988.

[2] Metrology and Verification Act, Extract from Federal Law Gazette, Part I, 1985, pages 411 to 422.

[3] Verification Ordinance (Weights and Measures Regulations) dated August 12, 1988 in the version of its promulgation in the Federal Law Gazette No. 43, Part I, pages 1657-1684.

[4] PTB-Requirements (PTB-A) 50.1, 50.10 and 50.20, edited by the Physikalisch-Technische Bundesanstalt.

<div align="center">

# The EXAMINATION and TESTING of PERIPHERAL EQUIPMENT CONNECTED to NON-AUTOMATIC WEIGHING INSTRUMENTS

</div>

by P.D. EDWARDS and P.C. KNOWLES National Weights and Measures Laboratory, Teddington, U.K.

SUMMARY - This paper, presented at the OIML seminar Weighing in Braunschweig, 15 18 May 1990, describes the examination and testing techniques currently employed in the United Kingdom to approve peripheral equipment such as electronic cash registers, point of sale terminals, micro computers and main frame computers connected to non-automatic weighing instruments for retail and industrial installations.

## 1. Introduction

The advent of modern technology over the last twenty years has changed the role played by non-automatic weighing instruments. Today's supermarkets, hypermarkets, and industrial processes require weighing instruments, individually or networked, to be linked to peripheral equipment such as electronic point of sale (EPoS) terminals and micro and mainframe computers to enable speedy updates of commodity data (product name, price, date etc.), transaction totalising, printing of receipts and invoices, and the collection of management data. Peripheral equipment such as bar-code laser scanners, cheque writers, magnetic card readers, receipt or tally roll printers and cash tills will not be discussed here although many of the aspects of examination and testing are the same.

The purpose of this paper is to describe the examination and testing techniques currently employed in the United Kingdom to approve peripheral equipment such as EPoS terminals and computers linked to non-automatic weighing instruments and to discuss the effect of the impending changes which are likely to result from the "new approach" directives and European Standards.

It should be noted that the word "examination" used throughout this paper is the United Kingdom equivalent to the internationally accepted word "evaluation".

## 2. Types of peripheral equipment

Before discussing the techniques employed in examination and testing of such peripheral equipment, it is worthwile describing some of the previously mentioned combinations of weighing instruments and peripheral equipment that are submitted to The National Weights and Measures Laboratory for national approval.

## 2.1 Electronic point of sale (EPoS) terminal

These electronic terminals are the latest stage in the development of the electronic cash register (ECR) and represent the more sophisticated use of data handling techniques both within the terminal itself and in communication with other terminals and management computer systems.

In general, a terminal will consist of an electronic control unit, printer, keyboard, operator's and purchaser's displays and a cash drawer. In addition, the control unit may also communicate with weighing instruments and other peripheral equipment.

Depending upon the type of weighing instrument, the terminal may perform transaction totalising, display of certain transaction data, receipt printing etc., as well as a considerable amount of management data.

The terminal may be a stand-alone installation or connected in a network of like equipment through a communication link, with one being designated the "master" and the other "slaves". The updating of transaction data is carried out on the "master" and subsequently downloaded to the "slaves" thus providing identical data for all terminals.

Terminals installed in supermarkets and hypermarkets are usually part of the customer checkout system. There can be a large number of terminals in one installation which are networked to a "rear of store" computer for management functions such as price updates, totals collection and stock control.

The terminal software provides the operation of the hardware and the program which defines the presentation of the transaction data both on the display and the receipt ticket.

The weighing instrument can be either weight-only or price-computing in which case the presentation of transaction data for display on the terminal will vary. With weight-only instruments, the unit price and price-to-pay are displayed on the terminal while price-computing instruments only the price-to-pay needs to be displayed.

The "rear of store" computer may be connected to the store's main computer (or store controller) by a hard-wired communication link or to the store's Head Office computer via a MODEM link.

## 2.2 Industrial systems

In an industrial installation non-automatic weighing instruments can be connected to computers which supply information on the transactions (i.e. weighing records and invoicing). In this situation the computer is generally considered to be used for trade purposes.

The computer can be linked to other computers either by hard-wired or MODEM links.

Where the computer is not used for trade purposes and is solely for management purposes then the output port from the weighing instruments to the computer must be clearly marked: "For management purposes only", and statutory conditions are laid down in the certificate of approval.

![](page=21,bbox=[285, 411, 1683, 2417])

<div align="center">

Fig. 2 - Price computing instruments linked to EPoS terminals and computers

</div>

<div align="center">

Fig. 1 - Weight-only instruments linked to EPoS terminals and computers

</div>

## 3. Current UK regulations and guidelines

All type examinations in the United Kingdom are carried out under the provisions of section 12 of the Weights and Measures Act 1985. Under this Act, Regulations are made by Parliament from time to time relating to various aspects and types of weighing and measuring instruments.

The current Regulations [1] for non-automatic weighing instruments came into force in the United Kingdom in November 1988.

To coincide with the making of the new Regulations, NWML revised its Design Assessment Guidelines for both non-automatic retail and industrial weighing instruments [2] and [3]. As the name implies, the purpose of these is to act as a guide to the requirements that are applied when judging the suitability for use for trade of patterns submitted for approval under the Act and to be used as a checklist by the manufacturer before the equipment is submitted to NWML for examination. The guidelines are not mandatory and are neither exhaustive nor irrevocable. Amendments and additions can be made, after giving due notice, to reflect new technology and changing circumstances. This mirrors to a degree the "New Approach" adopted by the European Communities. A résumé of the guidelines relating to weighing instruments linked to peripheral equipment is given below:

## 3.1. Retail instruments linked to EPoS terminals and computers

Figures 1 and 2 present data flow charts for both weight-only and price-computing instruments linked to EPoS terminals. These figures illustrate various configurations, the simplest being that of a weighing instrument linked to a terminal only. Also included is the case where the weighing instrument is linked to the terminal which itself is linked to a controller or mainframe computer.

The main requirement applied to both weight only and price computing instruments is that the connection between the weighing instrument, including the EPoS terminal and the associated peripheral equipment (bar code scanner, magnetic card reader etc.), and the local or remote computer/controller is suitably isolated thereby ensuring that there is no malfunction of the weighing instrument arising from electrical interference.

In addition, a comparison control or a safeguard must be provided where weight data (or transaction data) is processed, reproduced or in any way presented by the computer. This includes the EPoS terminal where the application program is downloaded from the computer. The comparison control or safeguard must occur after formatting of the price computation, display and printout data and may take one of several forms such as:

(i) the weight information (or transaction information) to be printed on the EPoS terminal is compared with the weight information, (or transaction information) transmitted from the weighing instrument in which case the printout of all related transaction data must be inhibited, if there is any disparity, or

(ii) there is an associated tally roll printer in use with the weighing instrument designed and arranged to retain details of each weighing operation. The printouts on the EPoS terminals must contain sufficient information about each weighing operation to allow meaningful comparison with the relevant information on the tally roll. The tally roll record should be kept for at least a week, or

(iii) there is an associated printer in use with the weighing instrument. This printout must be either presented to the purchaser of affixed to the goods.

![](page=23,bbox=[369, 427, 1530, 932])

<div align="center">

Fig. 3 - Industrial instruments linked to computers Configuration 1

</div>

![](page=23,bbox=[394, 1745, 1544, 2069])

<div align="center">

Fig. 4 - Industrial instruments linked to computers Configuration 2

</div>

## 3.2 Industrial instruments linked to computers

The weighing instrument linked to a computer must be of approved design and have a suitably isolated interface. All transaction data produced by, or derived from, the computer must contain sufficient information about each weighing to allow meaningful comparison with the weighing record without resort to computer produced records. The basic principle is that any documentation used for trade must be traceable to data provided by a fully examined and tested data recorder.

The most common configuration is for the weighing instrument to be linked to an approved tally roll printer and ticket printer driven via the computer (Figure 3). Weight data are sent to the printer which adds other transaction data, either from records or via a keyboard, to the ticket, e.g. purchaser, product, delivery details etc. Suitable interlocks are provided to inhibit the transmission of trade weight data to the computer if the tally roll is disabled in any manner, e.g. offline, shortage of paper, disconnection of power or data lines. The weight data are accompanied by a unique identity, usually a six-digit consecutive number, which is retained on all trade documents produced by or from the computer, including invoices. Where it is impracticable to include all the weight values and their associated consecutive numbers (because of the number of weighings "bulked up") there must be a suitable legend on the document to indicate the route back to the tally roll record. This may be via the original ticket but more usually through a summary (lot) sheet accompanying a group of items.

A second configuration (Figure 4) has an approved and examined ticket printer driven directly from the weight indicator, in which case the tally roll printer is not a requirement. All documentation produced downline from the computer must contain the necessary information to indicate the route to trace back to the original ticket.

The tally roll records must be retained for a specified period, usually six months. Where the consecutive identity numbering is of an insufficient size to prevent "roll over" in a few months then a 12 month period is required.

The tally roll printer is normally a continuous paper roll with a take-up spool but "fan-fold" stationery is also acceptable. Consideration would also be given to the use of an "electronic tally roll" but this needs to be retained within the examined weighing equipment and readable via the weighing equipment. It must not be readily possible (within reason) to modify, corrupt or destroy the record. The use of removable "floppy discs" would not be deemed equivalent.

With the rapidly increasing number of computer-linked systems used for trade, examination of every system with the multiplicity of different computers, printers and software would be impracticable. Approval is therefore given, after appropriate examination of a small number of systems or simulated systems, to permit the linking of any computer subject to a number of conditions which are specified in the Certificate of Approval. A typical set of conditions are presented in Appendix I.

The printing of a second ticket of the same type is inhibited until the weight has returned to zero unless either:-

(i) the ticket has the same consecutive number and is a duplicate (to replace damaged tickets) or

(ii) the ticket is of a type which can be attached directly to the goods.

The computer architecture must be such that if weight data are continuously received by the computer, for say control purposes (such as the control of a cut-off or an alarm system), it must not be possible for the data to be stored or printed or used for trade in any way.

A system designed for non-attendant operation i.e. driver-operated (without a weighman) via a keyboard or "swipe" card must have additional safeguards provided to ensure the load (vehicle) is wholly on the load receptor and the system correctly zeroed before the start of the weighing cycle. In this case the computer and auxiliary items are tested in full as if the whole system was the weighing machine and such systems are specifically excluded from general approvals.

## 4. Examination and testing of peripheral equipment

The examination and testing procedures are basically the same for all types of peripheral equipment.

The extent to which the peripheral equipment needs to be evaluated will depend initially upon the purpose of use for the data generated by the equipment, on the type of interface with the weighing equipment and, in the case of industrial equipment, the type of operation controlled or monitored. As previously stated, a computer linked to retail weighing instruments is usually either used for management purposes (i.e. PLU creation or editing and management collection) or for the transfer of trade information between weighing machines while a computer linked to weighing instruments in an industrial installation is generally used for trade purposes.

It is generally the case that the weighing instrument linked to the peripheral equipment has previously been examined and approved as suitable for use for trade. Therefore the metrological and electrical functions of the instrument have already been thoroughly tested. However, further electrical testing when linked to peripheral equipment is needed. The main examination relates to ensuring that the software and interlinking of the EPoS/computer complies with the requirements of the guidelines outlined in section 3.

## 4.1 Software and interlinking examination

There are two main stages to the examination of the software and interlinking equipment. During the consultative stage, before any prototype hardware has been produced, the examiner will study the design and software specification to advise of any characteristics that will not meet the regulations and guidelines. Further consultations take place at suitable stages during the design of the prototype system.

Once the design has been finalised the pattern is registered and submitted to NWML for type approval.

The software and hardware are examined to ensure that the following features are acceptable:-

(a) operational features

(b) price-to-pay calculations

(c) format of displays

(d) format of receipt printing

(e) format of invoice printing

(f) special features.

For a networked system (either master/slave or computer controlled), it is essential that all instruments on the network are trading using the same transaction data (item price/unit price). Therefore, any updating of the transaction data must have certain safeguards to ensure that all instruments on the network are inhibited from trading until the updating has been completed. As each instrument is updated it can be brought back onto line.

For computer-linked systems, the procedures for product file creation and the collection of management data are examined.

## 4.2 Electrical testing

Electrical testing is carried out on the complete system to ensure there is no corruption of the weight or transaction data transmitted from the weighing instrument to the terminal or computer.

The testing investigates the effects of interference of the electrical supply, electrostatic discharge and electromagnetic fields as outlined in Appendices II and III.

During each test, all functions of the weighing instrument and the peripheral equipment are checked by carrying out transactions to ensure there has been no corruption of the weight, unit price, price-to-pay, display and receipt details. The testing can either be carried out at the laboratories of NWML or, for the larger systems, at the premises of the submitter.

It is important that all the peripherals connected to the weighing instrument including the connecting cables are subjected to the interference. For instance, when carrying out tests with interference induced into the main power supplies, care must be taken to ensure that all the peripheral equipment is powered from that supply.

The electrostatic discharge is applied to and radiated around each part of the peripheral equipment.

The radio-frequency interference tests are carried out, if possible, in the anechoic chamber of NWML using a swept frequency generator. All the equipement including any computer, if considered to be used for trade purposes, is subjected to the interference. If it is not possible to conduct the tests in the chamber, then hand-held radio transceivers operating at discrete frequencies are used.

## 5. OIML R 76

The OIML International Recommendation does not provide any detail with regards to the examination and testing of peripheral equipment linked to non-automatic weighing machines. However, the following paragraphs have implications for such equipment:

## 5.1 Paragraph 2.4 of R 76 Application of requirements

"The requirements of the Recommendation apply to all devices performing the relevant functions, whether they are incorporated in an instrument or manufactured as separate units

<table border="1"><tr><td>Examples are:</td><td>load-measuring devices</td></tr><tr><td></td><td>indicating devices</td></tr><tr><td></td><td>printing devices</td></tr><tr><td></td><td>preset tare devices</td></tr><tr><td></td><td>price-calculating devices</td></tr></table>

However, devices that are not incorporated in the instrument may, by national legislation, be exempted from the requirements for special applications".

All the devices quoted in the above examples are suitable for mounting in housings separate from that containing the weighing instrument but connected to the weighing instrument. Therefore, they could be considered to be peripheral equipment and as such are subject to the requirements of the Recommendation.

Exemption from any of the requirements does not apply when external influences have a direct bearing on the performance of that equipment and where functional integrity needs to be maintained.

## 5.2 Paragraph 5.4.4 of R 76

"An electronic instrument may be equipped with an interface permitting the coupling of the instrument to external equipment. When external equipment is connected, the electronic instrument shall continue to function correctly and its metrological functions shall not be influenced."

The above requirement permits the coupling of peripheral equipment to a weighing instrument through a suitable interface providing that the metrological and operational integrities of the instrument are maintained.

The operational integrity depends upon the transfer of data, both input and output while the metrological integrity is achieved by suitable isolation of the peripheral equipment. Without suitable isolation, correct functioning and operation of the instrument cannot be guaranteed.

This poses a few questions. What is suitable isolation? Opto-isolation or transformer isolation? How is this checked? Can it be checked by examination of the design or by testing? Both opto and transformer isolation have been successfully used for many years.

## 5.3 Discussion

Most EPoS terminals present primary information as defined by paragraph 4.15.1 of R 76 and are therefore subject to a complete pattern examination procedure.

These primary indications are presented on both the displays of the EPoS terminal and the associated printer.

In evaluating the operation of both the weighing instrument and the EPoS terminal, it will be important to ensure that the requirements of paragraph 4.1.2 regarding security and fraudulent use etc. are met.

It is the view in the UK that it is important to establish the way in which the display of transaction data is presented not only on the weighing instrument but also on the terminal to ensure that there are no characteristics likely to facilitate fraudulent use.

To illustrate this the following are examples of the way in which the terminal and the weighing instrument should function to achieve a satisfactory solution:-

(i) Where a weight-only instrument is connected to a peripheral device which indicates the price-to-pay based on a single instantaneous value of weight (like a printout) then the weight indicated may only remain displayed if the transaction data remains correct. The weight indicator should blank or indicate zero whichever is appropriate if the instrument is used to perform other transaction related functions. To accept further transaction data the instrument must see zero either prior to each transaction or at the start of each new set of transactions (i.e. new purchaser).

(ii) Where a price-computing instrument is connected to a peripheral device which indicates the price-to-pay based on a single instantaneous value of weight (like a printout) then the unit price may only remain displayed if the transaction data (including the price-to-pay on the peripheral device) remains correct. The unit price indicator should indicate zero if the peripheral device is used to perform other transaction related functions.

From the above remarks, it is clear the International Recommendation is open to interpretation and the comments presented are the views of the United Kingdom. To ensure a harmonised approach in the application of the Recommendation, it is important for all countries to have the same degree of understanding as to which peripheral equipement is to be covered by type approval and which equipment can be accepted as being outside the requirement.

This issue is partially clarified by an observation made at the beginning of Annex 1 of the EC "New Approach" Directive which states [5], [6]:

"Where an instrument includes or is connected to more than one indicating or printing device used for the applications listed in Article 1(2)(a), those devices which repeat the results of the weighing operation and which cannot influence the correct functioning of the instrument shall not be subject to the essential requirements if the weighing results are printed or recorded correctly and indelibly by a part of the instrument which meets the essential requirements and the results are accessible to both parties concerned by the measurement. However, in the case of instruments used for direct sales to the public, display and printing devices for the vendor and the customer must fulfil the essential requirements".

If this observation is accepted as part of the International Recommendation, then the use of peripheral equipment for industrial purposes is clarified. However, for instruments used for direct sales to the public, it remains unclear as to the type of instruments that are within the scope of the requirements.

As this Recommendation will form the basis of the harmonised standard, it is particularly imperative for the countries within the EC that a clear understanding of the exact nature and extent of peripheral equipment covered by this Recommendation is achieved within the next twelve months. This is to ensure that at least this area of possible misunderstanding does not cause a problem in the application of type approval under the "New Approach" Directive.

## References

[1] "The Weighing Equipment (Non-automatic Weighing Machines) Regulations 1988." SI 1988 N $ ^{\circ} $ 876 as amended. HMSO. May 1988.

[2] "Design Assessment Guidelines, Non-automatic Industrial Weighing Equipment". NWML Publication 0341, April 1988.

[3] "Design Assessment guidelines, Non-automatic Retail Weighing Equipment". NWML Publication 0342, June 1988.

[4] "Non-automatic Weighing Instruments". OIML R 76, 1988.

[5] "Proposal for a Council Directive on the harmonisation of the laws of the Member States relating to non-automatic weighing instruments". Commission of the European Communities, COM(88)780 final - SYN 174, Brussels, 10 February 1989.

[6] "Draft Common Position Adopted by the Council on... with a view to the adoption of a Directive on the harmonisation of laws of the Member States relating to non-automatic weighing instruments", The Council, European Communities, 10084/1/89, Brussels, 18 December 1989.

<div align="center">

# APPENDIX I - INDUSTRIAL INSTRUMENTS LINKED TO COMPUTERS

</div>

## TYPICAL OPERATING REQUIREMENTS AND CONDITIONS

1. There shall be a unique consecutive number generated by the indicator associated with each weight sent to the computer. "Unique" in this context means that it shall not be repeated within one year. The consecutive number, including where relevant the date, shall not be capable of readily being reset.

2. A number of weighing systems may be connected to a common computer, in which case the consecutive number shall identify the particular weighing system in use and the system shall be appropriate to the method in use. Examples are given below.

2. 1 Two to four weighbridges used as "in" and "out" weighbridges with only one "in" and one "out" in use at a time, e.g. others as spares in the event of breakdowns or maintenance and controlled from one weigh hut.

2. 2 A row of weighbridges used to fill different grades of similar products, e.g. oils, flour, etc.

2. 3 A number of similar production flow lines operating as a manufacturing unit.

3. Data sent from the computer or associated keyboard to the indicator shall be limited to:

3. 1 requests for data

3. 2 print commands

3. 3 data acknowledgement

3. 4 entry of a tare

3. 5 operation of set points.

Commands for 3.1, 3.2 and 3.4 may be initiated but not acted upon when motion is detected. The instrument shall respond without noticeable delay when stable equilibrium is achieved. A delay not exceeding three seconds may be permitted to allow adequate time for data communication at low baud rates, or if the line is busy with other data.

4. 1 There shall be a ticket produced for each weighing, first and second weights used to produce a "NET" weight may both be recorded on a common ticket.

In those cases where a number of similar items are assembled into lots, e.g. a pallet, then the provision of a summary ticket giving details of the pallet load will be considered if appropriate to the type of operation.

4. 2 The ticket shall, inter alia:

4. 2.1 have all weight related data in characters not less than 2.5 mm high and without slashed zeros.

4. 2.2 have the correct units of measurement in full or with the following symbols: t, kg, g, lb.

4. 2.3 indicate the consecutive number of each weighing.

4. 2.2 identify the place of weighment.

4. 2.5 have other data clearly separated from the weight data and where such data includes conversion factors these must be stated. e.g. milk xxx kg/litre xxx litres.

4. 2.6 carry clearly and prominently the statement: "A tally roll record of this weight is retained for six months", or suitable equivalent wording.

4. 2.7 be clear and unambiguous.

4. 2.8 it shall not be possible to initiate a second printout for the same weighing operation, e.g. there must be a weight disturbance of at least 30 d. In the case of a weighbridge the disturbance may be 30 d or 400 kg whichever is the lesser.

There may be exceptions of this where:

4. 2.8.1 the second ticket is clearly a duplicate of the first ticket e.g. multileaf with different colour headings or marked duplicate.

4. 2.8.2 where the ticket is in the form of labels to be attached to the item being weighed.

4. 3 where totalising facilities are provided, other than for management purposes, the indication shall return to within the zero setting range before a further printout can be initiated except in the case of a change from Net or Gross or first to second weight or the converse. In these cases the condition shall only apply between printouts of the same type, e.g. Net.

5. Where a stored "weighed tare or first weight" is used then the consecutive number of that weight and the date of weighment must be shown on the relevant documents. Stored weighed tares are only valid for 10 days from the date of weighments.

6. The computer may have additional printer(s) or terminals connected to the system for other purposes.

7. The computer may be connected to a further remote computer.

8. 1 Disconnection of the tally-roll power supply, data line or shortage of paper shall inhibit data transmission to the computer.

8. 2 Where weight information is sent to the computer solely to provide control of a process, e.g. control a cut off, then there may be exceptions to paragraph 1 above provided that the architecture of the circuit and software is such that the information cannot be stored, printed or passed on to another computer and is used solely for controlling a (process) operating function. In such cases weight data used for printing etc must be separately addressed.

9. The weight display on the indicator shall be clearly visible and readable by the operator in the normal operating position.

The use of the VDU to display weight is only permitted:

9. 1 where it forms part of the text of a multi-line display, e.g. ticket format displayed on a CRT, and the weight data is the same height as the text, and

9. 2 where the digits/figures are not more than 6 mm in height.

10 The computer shall not be used to control:

10. 1 functions affecting the operation of the weighing system, e.g. zero setting devices, barriers to control the position of a vehicle on a weighbridge etc.

10. 2 a set point or set points designed to fill to a predetermined fixed value e.g. an automatic filling machine filling to the same value. The system may be used to fill, approximately, to an entered value.

10. 3 filling systems where the filling feed is attached to the container being filled, e.g. hoses attached to a road tanker on a weighbridge unless

10. 3.1 the interconnection of the hose is so counterbalanced as not to influence the weighing result, and print out shall be inhibited if the resultant NET weight is less than 200 d or

10. 3.2 there is a permanently displayed notice with the legend: "THE FILLING HOSE MUST BE DISCONNECTED BEFORE TAKING ANY WEIGHT VALUE", and the system is interlocked to prevent the weight value being printed or stored whilst the hose(s) are connected.

<div align="center">

# APPENDIX II - EQUIPMENT IMMUNITY TO ELECTRICAL DISTURBANCES

</div>

## 1. POWER SUPPLY

No malfunction of any weighing equipment shall be caused by the following disturbances:

(a) Variation of the power supply voltage from minus 15 % to plus 10 % of the nominal value.

(b) Variation of the power supply frequency from minus 2 % to plus 2 % of the nominal value.

(c) Power supply interruptions to any level down to and including:

(i) Zero voltage for 10 ms or less

(ii) 50 % of nominal voltage for 20 ms or less

(iii) 80 % of nominal voltage for 50 ms or less

(d) Common-mode randomly-phased transient over voltages of either polarity to the following specification $ ^{*} $

<table border="1"><tr><td>Amplitude not more than</td><td>Rise time not less than</td><td>Half amplitude duration not more than</td><td>Repetition rate not more than</td></tr><tr><td>500V</td><td>5ns</td><td>100ns</td><td>12Hz</td></tr><tr><td>1000V</td><td>25ns</td><td>1μ</td><td>single shots</td></tr><tr><td>1500V</td><td>35ns</td><td>3μ</td><td>single shots</td></tr></table>

Where "single shots" are specified it must be noted that susceptibility is established first by repetitive (not more than 12 Hz) testing and then single shots are used to determine the practical significance of any susceptibility found.

## 2. ELECTROSTATIC DISCHARGE

No malfunction of any weighing equipment shall be caused by:—

Electrostatic discharges of up to 6 kV with energy up to 2 mJ and a repetition rate not more than 0.1 Hz, on any metal or other conductive surface,

(i) on the equipment

(ii) in the vicinity of the equipment.

![](page=1,bbox=[1539, 2711, 1837, 2768])

1. The purpose of the tests is to provide evidence that the instrument is immune for any field strength up to and including 10 V/m randomly keyed on and off, for any

- frequency within the specified range

- polarisation and orientation

- mode of operation

- configuration of its sub-units and associated cables as may be appropriate for the intended application of the instrument or system

- length of signal cables, control cables, interconnecting cables, power cables and mains cables up to the maxima that are reasonably expected to be used for the intended application of the instrument or system.

2. Tests would normally be expected to be carried out in a screened room with suitable absorbers for the range of frequencies used.

3. The method and procedure used shall at least ensure that

- the field is kept as near to 10 V/m as possible $ ^{**} $

- reflections are minimised

- nulls and peaks are avoided

- test results are obtained for horizontal and vertical polarisations or alternatively at the most sensitive orientation bearing in mind that the sensitivity can vary with frequency

- the sweep rate is such that it allows the instrument or system to respond to any possible influence of the field. The minimum dwell time is not to be less than one second. (For digital test equipment not less than 0.99 s).

- cable lengths are the maxima that are reasonably expected to be used in the intended application of the instrument or system

- cables shall not be coiled but laid as far as possible in straight lines. Where not completely possible the cables should be placed non-inductively in the available space.

- the frequency intervals shall not be larger than

<table border="1"><tr><td>1kHz from 100kHz to</td><td>2MHz</td></tr><tr><td>10kHz from 2MHz to</td><td>20MHz</td></tr><tr><td>100mHz from 20MHz to</td><td>220MHz</td></tr><tr><td>500mHz from 220MHz to 1000MHz</td><td></td></tr></table>

<div align="center">

- spot checks shall be carried out at the following frequencies (MHz) keyed on and off for the same polarisations as used for the sweep.

</div>

<table border="1"><tr><td>0.1</td><td>0.16</td><td>0.2</td><td>0.25</td><td>0.3</td><td>0.4</td></tr><tr><td>0.6</td><td>0.8</td><td>1</td><td>1.2</td><td>1.4</td><td>1.6</td></tr><tr><td>2.5</td><td>4</td><td>6</td><td>10</td><td>13</td><td>16</td></tr><tr><td>20</td><td>27</td><td>35</td><td>40</td><td>60</td><td>80</td></tr><tr><td>100</td><td>120</td><td>144</td><td>150</td><td>160</td><td>180</td></tr><tr><td>200</td><td>250</td><td>300</td><td>350</td><td>400</td><td>435</td></tr><tr><td>500</td><td>600</td><td>700</td><td>800</td><td>934</td><td>1000</td></tr></table>

The frequencies in bold-type are permitted for industrial purposes and for special applications in the medical and telecommunications fields. The additional tests are necessary to assure the stability of the specimen used in such environments. The duration of each test at a particular test frequency shall be as long as the normal lapse of time necessary for the collection and the processing of the data by the instrument or system for the particular mode of operation.

<div align="center">

# AIR HUMIDITY and AIR DENSITY DETERMINATIONS in METROLOGY LABORATORIES

</div>

by S.A. THULIN Bureau International de Métrologie Légale

SUMMARY - In a number of metrology and testing laboratories not involved in the most exacting scientific work, there is anyway frequently need for determining the relative humidity to an accuracy approaching one percent and sometimes the density of air to about a tenth of a percent.

This can be done quickly by very simple formulas and instruments such as a wet and dry bulb hygrometer using a small table of saturation vapour pressures of water and a pocket calculator.

This article, mainly addressed to laboratory technicians, discusses the influences of the psychrometric coefficient, the pressure and temperature measurements on the accuracy of such determinations.

## 1. Measuring instruments

The most commonly used precision instrument for measuring the humidity of ambient air is the wet and dry bulb hygrometer (psychrometer) of the Assman design (Fig. 1). This type of instrument supplied by a number of firms manufacturing meteorological instruments is very economic and requires simply that the two mercury thermometers used are identical and calibrated to 0.1 $ ^{\circ} \mathrm{C} $ or better. The air speed of the incorporated ventilator should be at least 2.5 m/s. Furthermore the wet bulb must be kept clean from grease or oil film. The cotton sleeve which surrounds the wet bulb must thus have been adequately cleaned by washing and uniformly wetted by pure (or distilled) water. Instructions for the appropriate use of psychrometers are given in the Guide WMO No.8 edited by the World Meteorological Organization [1].

The other instrument required for air humidity measurements and especially for air density measurements is a good barometer. The most convenient instrument then is an aneroid barometer with high resolution (two turns of pointer or digital) and an accuracy of 0.1 % such as supplied by firms manufacturing instruments for aviation. This barometer should, however, be regularly calibrated or simply checked to a reference mercury barometer.

Finally for the air density measurements the ambient air temperature should be measured to 0.1 $ ^{\circ} \mathrm{C} $ using one or more calibrated thermometers, each having its bulb or sensor duly protected from radiation by one or two shields thermally insulated from the bulb but allowing free circulation of the air.

![](page=4,bbox=[668, 329, 1291, 1517])

<div align="center">

Fig. 1 - The Assman hygrometer

</div>

## 2. Computation of air humidity

The most commonly used empirical formula for computing the relative humidity of air using wet and dry bulb hygrometers can be written

$$
U = \frac {e _ {w} - A P \left(t - t _ {w}\right)}{e _ {t}} \times 1 0 0
$$

where :

U = relative humidity (RH) in %

t = dry bulb temperature in $ ^{\circ} \mathrm{C} $

$ t_{w} $ = wet bulb temperature in $ ^{\circ} \mathrm{C} $

$ e_{w} $ = saturation vapour pressure of water at temperature $ t_{w} $

$ e_{t} $ = saturation vapour pressure of water at temperature $ t $

P = ambient pressure in Pa

$ A=\mathrm{psychrometric\ coefficient\ in\ K^{-1}} $ (WMO reference value: $ 6. 2 \cdot 1 0^{-4} \mathrm{~ K}^{-1} $)

## 2.1. Saturation vapour pressures

The values of the saturation vapour pressures $ e_{w} $ and $ e_{t} $ can be found from Table 3 which is an abridged version of a table published in 1976 by Wexler [2] where we have for reasons of simplification omitted the decimals without rounding. The temperatures used are those of the IPTS-68 scale. This table can however also be used with thermometers calibrated in terms of the new temperature scale ITS-90 as the differences between ITS-90 and IPTS-68 attain only 0.01 $ ^{\circ} \mathrm{C} $ at 40 $ ^{\circ} \mathrm{C} $ . Air temperatures can in fact hardly be measured to that accuracy.

It is more important to note that the values in the table, in order to be independent of the ambient pressure, refer to the pure phase i.e. to the equilibrium pressure over a surface of pure water.

The effective saturation vapour pressure in moist air is however higher as the air-water vapour mixture is not a perfect gas. The resulting relative humidity content will thus be higher and pressure dependent. At the usual ambient laboratory pressures and temperatures the multiplier, or so-called enhancement factor, is approximately f=1.004 which generally leads to an increase in relative humidity less than 0.2 % and therefore can be ignored for current relative humidity determinations of ambient air but is appropriate to take into account in accurate determinations of the air density.

## 2.2. The psychrometric coefficient A

The psychrometric coefficient A depends basically on the construction of the psychrometer i.e. on bulb diameter, air speed, properties of radiation shields, means of wetting, etc.

For Assman psychrometers, and also for whirling psychrometers, this coefficient was for a long time chosen to be 6.6 or $ 6. 7 \cdot 1 0^{-4} \mathrm{~ K}^{-1} $ and several psychrometric tables for meteorological purposes were based on these values.

The World Meteorological Organization advises in its Guide [1] that the much lower value of $ 6. 2 \cdot1 0^{-4} \mathrm{~ K}^{-1} $ represents a better compromise for well ventilated psychrometers. This coefficient deduced from work by Wylie and Lalas [3] [4] on the WMO reference psychrometer may typically apply to psychrometers with bulb diameters of about 5 mm equipped with suitable radiation shields and submitted to air speeds of 3 m/s or more.

It remains that there is always some uncertainty about which value to apply for the particular psychrometer used taking into account its practical operating conditions.

The influence of variations in the coefficient A is fortunately small and affects mainly the low relative humidity values. If for instance the coefficient A = 6.5 $ \cdot10^{-4} $ K $ ^{-1} $ applies, which is about 5 % higher than the reference value A = 6.2 $ \cdot10^{-4} $ K $ ^{-1} $ , this will correspond to a difference in the computed value of relative humidity which for the level of U = 10 % is - 2.1 % at 10 $ ^{\circ} $ C, - 1.6 % at 20 $ ^{\circ} $ C and - 1.0 % at 40 $ ^{\circ} $ C. For the level of U = 50 % these variations are reduced to approximately the half (see Table 1).

The use of the old psychrometric tables based on $ A=6. 7 \cdot 1 0^{-4} \mathrm{~ K}^{-1} $ should however be avoided unless there is experimental evidence that this coefficient really applies such as could possibly be the case for poorly ventilated psychrometers.

The presence and polish of the radiation shields usually have a rather important effect on the value of A. It is important to note [4] that organic surface layers on the wet bulb simply formed by contact with the hands can increase the psychrometric coefficient by up to 10 %. As previously mentioned it is thus necessary that clean materials are used for the sleeve and that the thermometer bulbs are suitably cleaned.

<div align="center">

Table 1 - Differences of the computed values in percent relative humidity for various psychrometric coefficients with respect to the WMO reference value $ A=6. 2 \cdot 1 0^{-4} \mathrm{~ K}^{-1} $

</div>

<table border="1"><tr><td rowspan="2">U%</td><td colspan="4">t=10℃</td><td colspan="4">t=20℃</td><td colspan="4">t=40℃</td></tr><tr><td>6.2</td><td>6.35</td><td>6.5</td><td>6.7x10-4K</td><td>6.2</td><td>6.35</td><td>6.5</td><td>6.7x10-4K</td><td>6.2</td><td>6.35</td><td>6.5</td><td>6.7x10-4K</td></tr><tr><td>10</td><td>0</td><td>-1.1</td><td>-2.1</td><td>-3.5</td><td>0</td><td>-0.8</td><td>-1.6</td><td>-2.3</td><td>0</td><td>-0.4</td><td>-1.0</td><td>-1.7</td></tr><tr><td>50</td><td>0</td><td>-0.6</td><td>-1.1</td><td>-1.8</td><td>0</td><td>-0.4</td><td>-0.8</td><td>-1.4</td><td>0</td><td>-0.2</td><td>-0.4</td><td>-0.7</td></tr><tr><td>90</td><td>0</td><td>-0.1</td><td>-0.2</td><td>-0.4</td><td>0</td><td>-&lt;0.1</td><td>-0.1</td><td>-0.2</td><td>0</td><td>-&lt;0.1</td><td>-0.1</td><td>-0.1</td></tr></table>

## 2.3. Influence of the barometric pressure

The formula shows that the barometric pressure P has the same relative influence on U as variations in A. Its measurement is therefore also not so critical.

Variations in the mean pressure of up to 5 % will in fact not create differences in the computed relative humidity of more than 1 % at the level of U=50 %.

It is however extremely rare that the barometric pressure varies with such a high amount as $ \pm5\% $ at a given location.

The determination of relative humidity at meteorological stations is therefore frequently done by applying a mean value of P for the determination of relative humidity. In metrology laboratories the measurement of P to 1 % permits however to eliminate the uncertainty component of pressure origin in the computation of the relative humidity.

## 2.4. Influence of errors in temperature measurements

The influence of errors in the measurement of the temperatures t and $ t_{w} $ are summarized in Table 2 for an increase of 0.1 $ ^{\circ} \mathrm{C} $ in t and $ t_{w} $ respectively.

<div align="center">

Table 2 - Differences in percent relative humidity for an increase of $ 0. 1 \, \mathrm{^o C} $ in t and $ t_{w} $

</div>

<table border="1"><tr><td rowspan="2">U%</td><td colspan="2">t=10℃</td><td colspan="2">t=20℃</td><td colspan="2">t=40℃</td></tr><tr><td>t+0.1</td><td>tw+0.1</td><td>t+0.1</td><td>tw+0.1</td><td>t+0.1</td><td>tw+0.1</td></tr><tr><td>10</td><td>-0.6</td><td>+0.9</td><td>-0.3</td><td>+0.6</td><td>-0.1</td><td>+0.3</td></tr><tr><td>50</td><td>-0.8</td><td>+1</td><td>-0.6</td><td>+0.7</td><td>-0.3</td><td>+0.4</td></tr><tr><td>90</td><td>-1.2</td><td>+1.2</td><td>-0.8</td><td>+0.8</td><td>-0.6</td><td>+0.6</td></tr></table>

If the calibration or observation errors of both thermometers are the same in magnitude and sign, the effect on U will be negligible.

Even if the thermometers have been accurately calibrated, we may anyway suppose that random errors of observation typically attain 0.1 $ ^{\circ} \mathrm{C} $ for each thermometer corresponding to $ 0.14 \,^{\circ} \mathrm{C} $ in the standard deviation of the temperature uncertainty component which by comparison with the values in Table 2 leads to a corresponding uncertainty in relative humidity of about $ \Delta U_{T}=1\% $ at t=20 $ ^{\circ} \mathrm{C}. $

## 2.5. Estimation of the global uncertainty of measurements with the Assman psychrometer

It is somewhat hazardous to make an estimate of the resulting uncertainty of relative humidity measurements made by a psychrometer as it depends both on the effective value of the psychrometric coefficient and on the practical accuracy of the wet and dry bulb temperature measurements. Some uncertainty may also originate from the simplified formula itself. The psychrometric coefficient is in fact slightly dependent on the ambient temperature though this effect may be neglected at room temperatures.

A well cleaned and well ventilated Assman psychrometer should however, according to the survey in section 2.2 and Table 1, generally allow measurements with an intrinsic uncertainty of $ \Delta U_{j}=1\% $ at a relative humidity of U=50 %.

If the ambient pressure has been measured to an accuracy of 1 % we may neglect the pressure uncertainty component in U. The global uncertainty including the temperature measurements could then for the level of U= 50 % and temperatures between +10 and + 40 $ ^{\circ} \mathrm{C} $ be estimated to

$$
\sqrt {\Delta U _ {i} ^ {2} + \Delta U _ {T} ^ {2}} = \sqrt {1 ^ {2} + 1 ^ {2}} = 1. 4 \%
$$

This value should preferably be considered as a standard deviation applicable only to very good temperature observations with commercial Assman psychrometers comprising duly verified thermometers.

## 3. Computation of the density of air

In some metrology work where it is necessary to take into account air buoyancy it may not be satisfactory simply to use the standardized value of 1.2 kg/m $ ^{3} $ estimated to represent fairly closely the mean value of air density at sea level and $ 20^{\circ} \mathrm{C} $

This is in particular the case at elevated laboratories where the mean air pressure may be much lower than at sea level. The variation with altitude is in fact on the mean about-12 Pa/m up to 1000 m and about-11 Pa/m between 1000 and 2000 m.

The reference pressure at a laboratory located at an altitude of 1 500 m would thus be around 84 500 Pa instead of 101 325 Pa which is the standardized reference pressure originally meant to represent the mean value at sea level.

If we want to determine the density of air with reasonable accuracy we must anyway measure the barometric pressure at the time of the experiment.

The difficulties of applying appropriate buoyancy corrections in comparisons of platinumiridium kilogram standards with stainless steel standards or more generally with weights having a density close to the standardized value of 8000 kg/m $ ^{3} $ , induced BIPM and the great national laboratories to adopt, upon suggestion by Jones [5], a standardized procedure for the computation of the density of air [6].

The formula used is based on a supposed standard composition of the air, the respective molar mass of these constituants, the adopted value of the general gas constant, the water vapour contribution, the gas compressibility factor, the enhancement factor etc. The practical reproducibility of this so-called BIPM formula is estimated to about 0.01 %.

The procedure for determining the various factors to be used in this formula may at a first sight look somewhat lengthy. As already proposed by Jones [5], one may however under defined laboratory conditions simplify by using fixed values for the gas compressibility factor and the enhancement factor. Furthermore, as it may not be possible to appreciate the amount of carbon dioxide in the air one may with some lack of accuracy neglect the corresponding correction term and suppose that the molar content of $ \mathrm{C O_{2}} $ is 0.0004 or 0.04 %, which is the mean value used in the composition of the standard air on which the original formula is based.

These simplifications may typically be used in the range of temperatures from 15 to 30 $ ^{\circ} \mathrm{C} $ and barometric pressures between 80 000 and 110 000 Pa (800 to 1 100 mbar) whereby the mean compressibility factor can be taken as Z=0.9996 and the mean enhancement factor $ f=1.004 $ . The use of these mean values reduces the formula for the air density simply to

$$
\rho = \frac {3 . 4 8 4 9 2 \cdot 1 0 ^ {- 3}}{2 7 3 . 1 5 + t} \left(P - 0. 3 7 9 5 e _ {t} \frac {U}{1 0 0}\right)
$$

where as before

t = ambient temperature in $ ^{\circ} \mathrm{C} $

P = barometric pressure in Pa

$ e_{t}= $ water vapour saturation pressure in Pa

U = relative humidity in %.

<div align="center">

Table 3 - Saturation vapor pressure over water (IPTS-68)

</div>

<table border="1"><tr><td rowspan="2">Temp.℃</td><td>.0</td><td>.1</td><td>.2</td><td>.3</td><td>.4</td><td>.5</td><td>.6</td><td>.7</td><td>.8</td><td>.9</td></tr><tr><td>Pa</td

It will be found that at $ t=20^{\circ} \mathrm{C} $ and U=50 % the following uncertainties each contribute to an uncertainty of 0.1 % in the density of the air

<table border="1"><tr><td>temperature</td><td>0.3℃</td></tr><tr><td>pressure</td><td>100Pa(1mbar)</td></tr><tr><td>relative humidity</td><td>10%</td></tr></table>

The temperature of the air can usually be measured and maintained to about 0.1 $ ^{\circ} \mathrm{C} $ for a certain period of time and the relative humidity measured and controlled to about 3 %.

The pressure component of the formula is in practice more difficult to manage. Though a precision barometer easily allows pressure measurements to better than 1 mbar, the main difficulty is to maintain the pressure constant to this accuracy during the time of an experiment.

Air density determinations to 0.1 % or better therefore usually have no practical meaning in air-conditioned rooms and precision mass comparators or similar equipment involving accurate air density corrections usually have to be protected from draught and installed in special constant pressure cabinets or containers.

## References

[1] Guide to meteorological instruments and methods of observation, WMO Guide No.8, Fifth edition 1983 published by the Secretariat of the World Meteorological Organization, Avenue Giuseppe-Motta, 1211 Geneva, Switzerland.

[2] Wexler A. : Vapor pressure formulation for water in range 0 to $ 1 0 0 \, ^ {\circ} \mathrm{C} $ , a revision. Journal of Research of the NBS, Vol. 80A p. 775-785, 1976.

[3] Wylie R.G. and Lalas T.: The WMO Psychrometer Division of Applied Physics Technical Paper No.3, C.S.I.R.O. Australia, 1981.

[4] Wylie R.G. and Lalas T. : Detailed determination of the psychrometer coefficient for the wet cylinder in a transverse air stream and an analysis of its accuracy Division of Applied Physics Technical Paper No.7, C.S.I.R.O. Australia, 1981.

[5] Jones F.E. : The air density equation and the transfer of the mass unit Journal of Research of the NBS, Vol. 83 p. 419-428, 1978.

[6] Giacomo P. : Equation for the determination of the density of moist air (1981). Metrologia 18, p. 33-40, 1982.

<div align="center">

# LITERATURE

</div>

Temperature measurements

T.J. QUINN: Temperature, 2nd edition 1990, 495 pages, published by Academic Press, London and San Diego.

This important book is written by the Director of BIPM, an eminent specialist on the subject. The first edition published in 1983 is now updated to include a full description on the new International Temperature Scale (ITS-90) which came into effect on 1 January 1990, replacing the still commonly used International Practical Temperature Scale of 1968 (IPTS-68).

The new scale intended to imitate more closely the thermodynamic scale is characterized by a greater number of temperature ranges which are overlapping thus requiring a greater number of interpolation formulae. The ambition to get closer to the "scientific truth" involves some complications which may be a reason why the word "practical" was dropped in the new designation. The details of the temperature ranges, defining fixed points, means of interpolation and remaining inconsistancies and uncertainties are largely dealt with in the chapter on Temperature Scales of the book.

A long chapter is devoted to the Measurement of Thermodynamic Temperature, experiments which provide us with the temperature values of the fixed points which thus are basically identical in the two scales. The various methods of gas thermometry, acoustic thermometry, magnetic thermometry, dielectric constant and refractive-index gas thermometry and total radiation thermometry are explained for the scientists interested in research on these subjects.

The practical metrologist is however not forgotten. About fifty pages describe the construction and operation of Fixed Points and Comparison Baths. The chapter on Resistance Thermometry and the one on Thermocouples both include information and references concerning sensors used in industry. The chapter on Radiation Thermometry, based largely on the author's own research, deals extensively with the properties of radiation sources including cavities and tungsten ribbon lamps used for calibration of radiation thermometers.

Finally the classical Mercury-in-Glass Thermometry is also briefly dealt with in the last chapter of the book. Each chapter contains a very large bibliography. Details of ITS-90 and tables of differences between this scale and previous temperature scales are given in an appendix. Other appendices include standardized tables of EMF for thermocouples and the mathematics for constructing such tables.

The metrologist concerned with calibration of precision thermometers will certainly greatly appreciate this book which helps him to better understand and apply the rather complicated ITS-90.

BIPM: Supplementary information for the International Temperature Scale of 1990, published December 1990, 177 pages, available from Bureau International des Poids et Mesures, 92312 Sèvres, France.

This document replaces an earlier version concerning the previous temperature scales IPTS-68 and EPT-76 and is mainly addressed to scientists who attempt to construct the most rigorous version of ITS-90 in their laboratories. It deals for instance with the realization of the triple point of water, the triple point of mercury, melting points of gallium, freezing points of indium, tin, zinc, aluminium, silver, gold, copper and the cryogenic fixed points. The correct use and the properties of standard platinum resistance thermometers are discussed and information relative to helium vapour pressure scales, gas thermometry and radiation thermometry as applied to ITS-90 is also included.

The introductory chapter explains the historical background of the various temperature scales. The new ITS-90 is illustrated schematically for easy understanding, see Figure 1 below. This chapter gives estimates of uncertainty which show that for the fixed points the reproducibility of ITS-90 in the ranges of 0 to 600 $ ^{\circ} \mathrm{C} $ is on the mean fifty times better than that of the thermodynamic determinations. The official corrected text describing ITS-90 is reproduced in an appendix.

BIPM: Techniques for approximating the International Temperature Scale of 1990, 1st edition, published July 1990, 205 pages.

This monograph which like the one above has been compiled by the Comité Consultatif de Thermométrie, states in its foreword "The approximations to the International Temperature Scale of 1990 described here provides levels of accuracy that are quite adequate for the great majority of thermometric requirements, and in general do so with greater convenience or at lower cost than would be the case in realising the ITS-90 itself".

In order words this publication should be more useful to the practical metrologist then the Supplementary Information for ITS-90 summarized above. It thus gives details about the properties and construction of simplified fixed points, uniform-temperature enclosures, resistance thermometers, thermocouples and gives advice about the appropriate handling of these instruments.

The chapter on resistance thermometers gives however a somewhat negative picture of the stability of industrial platinum resistance sensors which may not be justified for all types of construction especially at temperatures below 300 $ ^{\circ} \mathrm{C} $ . The various international standards for such sensors are summarized, including OIML R 84.

## Advice to the laboratory technician

All the above literature on thermometry constitutes with its references a very valuable library for the metrologist working in a calibration laboratory. It is however appropriate to say a word of caution: do not confuse reproducibility with uncertainty in its most rigorous meaning i.e. the approach to the truth or true temperature. Temperature measurements in the field are influenced by so many other factors than the accuracy and calibration of the thermometer itself. A common mistake is simply to consider that it is only necessary to ensure good thermal contact of the sensor with the medium, the temperature of which shall be determined. It is in practice

equally important to prevent, or at least to take into account, thermal conduction through the leads or the protective tube of the sensor as well as other convection and radiation effects. The considerable time constant of some industrial thermometers may be another source of error.

When applying radiation thermometry in industry the problems of reflexions from other heat sources and the selection of sensors with appropriate spectral absorption bands are also frequently not sufficiently considered.

Laboratory calibration of thermometers under the same environmental conditions as in their practical use would be a goal which however rarely can be realised.

![](page=13,bbox=[439, 915, 1532, 1464])

![](page=13,bbox=[419, 1507, 1530, 1844])

<div align="center">

Fig. 1 - Schematic representation of the ranges, sub-ranges and interpolation instruments of ITS-90

</div>

## REUNIONS OIML MEETINGS

<table border="1"><tr><td></td><td>Groupes de travail
Working Groups</td><td>Dates
Date</td><td>Lieux
Place</td></tr><tr><td>SP 11</td><td>Mesure des pressions
Measurement of pressure</td><td>5-7 Juin/June 1991</td><td>PRAGUE
TCHÉCOSLOVAQUIE/
CZECHOSLOVAKIA</td></tr><tr><td>SP 11-Sr 3</td><td>Balances manométriques
Pressure balances</td><td></td><td></td></tr><tr><td>SP 5D-Sr 1</td><td>Compteurs et ensembles de mesure de liquides autres que l'eau à chambres mesureuses ou à turbine
Meters and measuring systems for liquids other than water with measuring chambers or with turbines</td><td>28-31 Octobre/October 1991</td><td>PARIS-LA DÉFENSE
FRANCE</td></tr><tr><td>SP 5D-Sr 7</td><td>Méthodes et dispositifs de vérification des instruments de mesure de liquides
Methods and devices for the verification of measuring instruments for liquids</td><td>25-27 Nov./November 1991</td><td>TOKYO
JAPON</td></tr><tr><td>SP 5D-Sr 9</td><td>Compteurs vortex
Vortex meters</td><td></td><td></td></tr><tr><td colspan="2">26e réunion du Comité International de Métrologie Légale
26th Meeting of the International Committee of Legal Metrology</td><td>7-9 Octobre/October 1991</td><td>PARIS
FRANCE</td></tr><tr><td colspan="4">Note: Liste à jour fin mai 1991
List as per end of May 1991</td></tr></table>

![](page=14,bbox=[1693, 2731, 1949, 2787])

## PUBLICATIONS

Vocabulaire de métrologie légale 1978

Vocabulary of legal metrology

Vocabulaire international des termes fondamentaux et généraux de métrologie 1984

International vocabulary of basic and general terms in metrology

Dictionnaire des essais de dureté (français, anglais, allemand, russe) 1991

Hardness testing dictionary (French, English, German, Russian)

## RECOMMANDATIONS INTERNATIONALES INTERNATIONAL RECOMMENDATIONS

R 1 — Poids cylindriques de 1 g à 10 kg (de la classe de précision moyenne)

Cylindrical weights from 1 g to 10 kg (medium accuracy class)

1973

R 2 — Poids parallélépipédiques de 5 à 50 kg (de la classe de précision moyenne)

Rectangular bar weights from 5 to 50 kg (medium accuracy class)

1973

R 4 — Fioles jaugées (à un trait) en verre

Volumetric flasks (one mark) in glass

1970

R 5 — Compteurs de liquides autres que l'eau à chambres mesureuses

Meters for liquids other than water with measuring chambers

1981

R 6 — Dispositions générales pour les compteurs de volume de gaz

General provisions for gas volume meters

1989

R 7 — Thermomètres médicaux (à mercure, en verre, avec dispositif à maximum)

Clinical thermometers (mercury-in-glass, with maximum device)

1978

R 9 — Vérification et étalonnage des blocs de référence de dureté Brinell

Verification and calibration of Brinell hardness standardized blocks

1970

R 10 — Vérification et étalonnage des blocs de référence de dureté Vickers

Verification and calibration of Vickers hardness standardized blocks

1970

R 11 — Vérification et étalonnage des blocs de référence de dureté Rockwell B

Verification and calibration of Rockwell B hardness standardized blocks

1970

R 12 — Vérification et étalonnage des blocs de référence de dureté Rockwell C

Verification and calibration of Rockwell C hardness standardized blocks

1970

R 14 — Saccharimètres polarimétriques

Polarimetric saccharimeters

1978

R 15 — Instruments de mesure de la masse à l'hectolitre des céréales

Instruments for measuring the hectolitre mass of cereals

1970

R 16 — Manomètres des instruments de mesure de la tension artérielle (sphygmomano-

mètres)

Manometers for instruments for measuring blood pressure (sphygmomanometers)

1970

![](page=15,bbox=[1508, 2727, 1863, 2777])

R 18 — Pyromètres optiques à filament disparaissant 1989

Visual disappearing filament pyrometers

R 20 — Poids des classes de précision $E_1$ $E_2$ $F_1$ $F_2$ $M_1$ de 50 kg à 1 mg 1973

Weights of accuracy classes $E_1$ $E_2$ $F_1$ $F_2$ $M_1$ from 50 kg to 1 mg

R 21 — Taximètres 1973

Taximeters

R 22 — Tables alcoométriques internationales 1975

International alcoholometric tables

R 23 — Manomètres pour pneumatiques de véhicules automobiles 1973

Tyre pressure gauges for motor vehicles

R 24 — Mètre étalon rigide pour agents de vérification 1973

Standard one metre bar for verification officers

R 25 — Poids étalons pour agents de vérification 1977

Standard weights for verification officers

R 26 — Seringues médicales 1973

Medical syringes

R 27 — Compteurs de volume de liquides (autres que l'eau). Dispositifs complémentaires. 1973

Volume meters for liquids (other than water). Ancillary equipment

R 29 — Mesures de capacité de service 1973

Capacity serving measures

R 30 — Mesures de longueur à bouts plans (calibres à bouts plans ou cales-étalons) 1981

End standards of length (gauge blocks)

R 31 — Compteurs de volume de gaz à parois déformables 1989

Diaphragm gas meters

R 32 — Compteurs de volume de gaz à pistons rotatifs et compteurs de volume de gaz à turbine 1989

Rotary piston gas meters and turbine gas meters

R 33 — Valeur conventionnelle du résultat des pesées dans l'air 1973

Conventional value of the result of weighing in air

R 34 — Classes de précision des instruments de mesurage 1974

Accuracy classes of measuring instruments

R 35 — Mesures matérialisées de longueur pour usages généraux 1985

Material measures of length for general use

R 36 — Vérification des pénétrateurs des machines d'essai de dureté 1977

Verification of indenters for hardness testing machines

R 37 — Vérification des machines d'essai de dureté (système Brinell) 1977

Verification of hardness testing machines (Brinell system)

R 38 — Vérification des machines d'essai de dureté (système Vickers) 1977

Verification of hardness testing machines (Vickers system)

R 39 — Vérification des machines d'essai de dureté (systèmes Rockwell B, F, T - C, A, N) 1977

Verification of hardness testing machines (Rockwell systems B, F, T - C, A, N)

R 40 — Pipettes graduées étalons pour agents de vérification 1977

Standard graduated pipettes for verification officers

R 41 — Burettes étalons pour agents de vérification 1977

Standard burettes for verification officers

R 42 — Poinçons de métal pour agents de vérification 1977

Metal stamps for verification officers

R 43 — Fioles étalons graduées en verre pour agents de vérification 1977

Standard graduated glass flasks for verification officers

R 44 — Alcoomètres et aréomètres pour alcool et thermomètres utilisés en alcoométrie 1985

Alcoholometers and alcohol hydrometers and thermometers for use in alcoholometry

R 45 — Tonneaux et futailles 1977

Casks and barrels

R 46 — Compteurs d'énergie d'électrique active à branchement direct (de la classe 2) 1978

Active electrical energy meters for direct connection (class 2)

R 47 — Poids étalons pour le contrôle des instruments de pesage de portée élevée 1978

Standard weights for testing of high capacity weighing machines

R 48 — Lampes à ruban de tungstène pour l'étalonnage des pyromètres optiques 1978

Tungsten ribbon lamps for calibration of optical pyrometers

R 49 — Compteurs d'eau (destinés au mesurage de l'eau froide) 1977

Water meters (intended for the metering of cold water)

R 50 — Instruments de pesage totalisateurs continus à fonctionnement automatique 1980

Continuous totalising automatic weighing machines

R 51 — Trieuses pondérales de contrôle et trieuses pondérales de classement 1985

Checkweighing and weight grading machines

R 52 — Poids hexagonaux. Classe de précision ordinaire de 100 g à 50 kg 1980

Hexagonal weights. Ordinary accuracy class, from 100 g to 50 kg

R 53 — Caractéristiques métrologiques des éléments récepteurs élastiques utilisés pour le mesurage de la pression. Méthodes de leur détermination 1982

Metrological characteristics of elastic sensing element used for measurement of pressure. Determination methods

R 54 — Échelle de pH des solutions aqueuses 1981

pH scale for aqueous solutions

R 55 — Compteurs de vitesse, compteurs mécaniques de distances et chronotachygraphes des véhicules automobiles - Réglementation métrologique 1981

Speedometers, mechanical odometers and chronotachographs for motor vehicles. Metrological regulations

R 56 — Solutions-étalons reproduisant la conductivité des electrolytes 1981

Standard solutions reproducing the conductivity of electrolytes

R 57 — Ensembles de mesurage de liquides autres que l'eau équipés de compteurs de volumes. Dispositions générales 1982

Measuring assemblies for liquids other than water fitted with volume meters. General provisions

![](page=17,bbox=[1594, 2734, 1848, 2774])

R 58 — Sonomètres

Sound level meters 1984

R 59 — Humidimètres pour grains de céréales et graines oléagineuses

Moisture meters for cereal grains and oilseeds 1984

R 60 — Réglementation métrologique des cellules de pesée

Metrological regulations for load cells 1991

R 61 — Doseuses pondérales à fonctionnement automatique

Automatic gravimetric filling machines 1985

R 62 — Caractéristiques de performance des extensomètres métalliques à résistance

Performance characteristics of metallic resistance strain gauges 1985

R 63 — Tables de mesure du pétrole

Petroleum measurement tables 1985

R 64 — Exigences générales pour les machines d'essai des matériaux

General requirements for materials testing machines 1985

R 65 — Exigences pour les machines d'essai des matériaux en traction et en compression

Requirements for machines for tension and compression testing of materials 1985

R 66 — Instruments mesureurs de longueurs

Length measuring instruments 1985

R 67 — Ensembles de mesurage de liquides autres que l'eau équipés de compteurs de volumes. Contrôles métrologiques

Measuring assemblies for liquids other than water fitted with volume meters.

Metrological controls 1985

R 68 — Méthode d'étalonnage des cellules de conductivité

Calibration method for conductivity cells 1985

R 69 — Viscosimètres à capillaire, en verre, pour la mesure de la viscosité cinématique

Glass capillary viscometers for the measurement of kinematic viscosity 1985

R 70 — Détermination des erreurs de base et d'hystérésis des analyseurs de gaz

Determination of intrinsic and hysteresis errors of gas analysers 1985

R 71 — Réservoirs de stockage fixes. Prescriptions générales

Fixed storage tanks. General requirements 1985

R 72 — Compteurs d'eau destinés au mesure de l'eau chaude

Hot water meters 1985

R 73 — Prescriptions pour les gaz purs CO, CO₂, CH₄, H₂, O₂, N₂ et Ar destinés à la préparation des mélanges de gaz de référence

Requirements concerning pure gases, CO, CO₂, CH₄, H₂, O₂, N₂ and Ar intented for the preparation of reference gas mixtures 1985

R 74 — Instruments de pesage électroniques

Electronic weighing instruments 1988

R 75 — Compteurs d'énergie thermique

Heat meters 1988

Bulletin OIML - N° 123 - Juin 1991 47

R 76 — Instruments de pesage à fonctionnement non automatique

Non-automatic weighing instruments

Partie 1 : Exigences métrologiques et techniques - Essais 1988

Part 1 : Metrological and technical requirements - Tests

Partie 2 : Rapport d'essai de modèle 1988

Part 2 : Pattern evaluation report

R 77 — Ensembles de mesurage de liquides autres que l'eau équipés de compteurs de volumes. Dispositions particulières relatives à certains ensembles

Measuring assemblies for liquids other than water fitted with volume meters.

Provisions specific to particular assemblies

R 78 — Pipettes Westergren pour la mesure de la vitesse de sédimentation des hématies 1989

Westergren tubes for measurement of erythrocyte sedimentation rate

R 79 — Étiquetage des préemballages 1989

Information on package labels

R 80 — Camions et wagons-citernes 1989

Road and rail tankers

R 81 — Dispositifs et systèmes de mesure de liquides cryogéniques (comprend tables de masse volumique pour argon, hélium, hydrogène, azote et oxygène liquides)

Measuring devices and measuring systems for cryogenic liquids (including tables of density for liquid argon, helium, hydrogen, nitrogen and oxygen)

R 82 — Chromatographes en phase gazeuse pour la mesure des pollutions par pesticides et autres substances toxiques 1989

Gas chromatographs for measuring pollution from pesticides and other toxic substances

R 83 — Chromatographe en phase gazeuse équipé d'un spectromètre de masse et d'un système de traitement de données pour l'analyse des polluants organiques dans l'eau

Gas chromatograph/mass spectrometer/data system for analysis of organic pollutants in water

R 84 — Capteurs à résistance thermométrique de platine, de cuivre ou de nickel (à usages techniques et commerciales)

Resistance-thermometer sensors made of platinum, copper or nickel (for industrial and commercial use)

R 85 — Jaugeurs automatiques pour le mesurage des niveaux de liquide dans les réservoirs de stockage fixes 1989

Automatic level gauges for measuring the level of liquid in fixed storage tanks

R 86 — Compteurs à tambour pour alcool et leurs dispositifs complémentaires 1989

Drum meters for alcohol and their supplementary devices

R 87 — Contenu net des préemballages 1989

Net content in packages

R 88 — Sonomètres intégrateurs-moyenneurs 1989

Integrating-averaging sound level meters

R 89 — Électroencéphalographes - Caractéristiques métrologiques - Méthodes et moyens de vérification

Electroencephalographs - Metrological characteristics - Methods and equipment for verification

R 90 — Électrocardiographes - Caractéristiques métrologiques - Méthodes et moyens de vérification

Electrocardiographs - Metrological characteristics - Methods and equipment for verification

![](page=19,bbox=[1620, 2684, 1852, 2780])

R 91 — Cinémomètres radar pour la mesure de la vitesse des véhicules

Radar equipment for the measurement of the speed of vehicles

1990

R 92 — Humidimètres pour le bois - Méthodes et moyens de vérification: exigences générales

Wood-moisture meters - Verification methods and equipment: general provisions

1990

R 93 — Frontofocomètres

Focimeters

1990

R 95 — Bateaux-citernes - Prescriptions générales

Ships' tanks - General requirements

1990

R 96 — Bouteilles récipients-mesures

Measuring container bottles

1990

R 97 — Baromètres

Barometers

1990

R 98 — Mesures matérialisées de longueur à traits de haute précision

High-precision line measures of length

1991

R 99 — Instruments de mesure des gaz d'échappement des véhicules

Instruments for measuring vehicle exhaust emissions

1991

R 100 — Spectromètres à absorption atomique pour la mesure des polluants métalliques dans l'eau

Atomic absorption spectrometers for measuring metal pollutants in water

1991

R 101 — Manomètres, vacuomètres et manovacuomètres indicateurs et enregistreurs

Indicating and recording pressure gauges, vacuum gauges and pressure-vacuum gauges

(*)

DOCUMENTS INTERNATIONAUX

INTERNATIONAL DOCUMENTS

D 1 — Loi de métrologie

Law on metrology

1975

D 2 — Unités de mesure légales

Legal units of measurement

1978

D 3 — Qualification légale des instruments de mesure

Legal qualification of measuring instruments

1979

D 4 — Conditions d'installation et de stockage des compteurs d'eau froide

Installation and storage conditions for cold water meters

1981

D 5 — Principes pour l'établissement des schémas de hiérarchie des instruments de mesure

Principles for the establishment of hierarchy schemes for measuring instruments

1982

D 6 — Documentation pour les étalons et les dispositifs d'étalonnage

Documentation for measurement standards and calibration devices

1983

D 7 — Évaluation des étalons de débitmétrie et des dispositifs utilisés pour l'essai des compteurs d'eau

The evaluation of flow standards and facilities used for testing water meters

1984

D 8 — Principes concernant le choix, la reconnaissance officielle, l'utilisation et la conservation des étalons

Principles concerning choice, official recognition, use and conservation of measurement standards

D 9 — Principes de la surveillance métrologique

Principles of metrological supervision

D 10 — Conseils pour la détermination des intervalles de réétalonnage des équipements de mesure utilisés dans les laboratoires d'essais

Guidelines for the determination of recalibration intervals of measuring equipment used in testing laboratories

D 11 — Exigences générales pour les instruments de mesure électroniques

General requirements for electronic measuring instruments

D 12 — Domaines d'utilisation des instruments de mesure assujettis à la vérification

Fields of use of measuring instruments subject to verification

D 13 — Conseils pour les arrangements bi- ou multilatéraux de reconnaissance des résultats d'essais, approbations de modèles et vérifications

Guidelines for bi- or multilateral arrangements on the recognition of test results, pattern approvals and verifications

D 14 — Formation du personnel en métrologie légale - Qualification - Programmes d'étude

Training of legal metrology personnel - Qualification - Training programmes

D 15 — Principes du choix des caractéristiques pour l'examen des instruments de mesure usuels

Principles of selection of characteristics for the examination of measuring instruments

D 16 — Principes d'assurance du contrôle métrologique

Principles of assurance of metrological control

D 17 — Schéma de hiérarchie des instruments de mesure de la viscosité des liquides

Hierarchy scheme for instruments measuring the viscosity of liquids

D 18 — Principes générales d'utilisation des matériaux de référence certifiés dans les mesurages

General principles of the use of certified reference materials in measurements

D 19 — Essai de modèle et approbation de modèle

Pattern evaluation and pattern approval

D 20 — Vérifications primitive et ultérieure des instruments et processus de mesure

Initial and subsequent verification of measuring instruments and processes

D 21 — Laboratoires secondaires d'étalonnage en dosimétrie pour l'étalonnage des dosimètres utilisés en radiothérapie

Secondary standard dosimetry laboratories for the calibration of dosimeters used in radiotherapy

D 22 — Guide sur les instruments portatifs pour l'évaluation des polluants contenus dans l'air en provenance des sites de décharge de déchets dangereux

Guide to portable instruments for assessing airborne pollutants arising from hazardous wastes

1984

1984

1984

1986

1986

1986

1989

1986

1986

1988

1988

1990

1991

(*) Publication en cours d'impression/Publication being printed.

Note — Ces publications peuvent être acquises au / These publications may be purchased from Bureau International de Métrologie Légale, 11, rue Turgot, 75009 PARIS.

![](page=22,bbox=[89, 346, 318, 499])

## ÉTATS MEMBRES

<table border="1"><tr><td>ALGÉRIE</td><td>INDONÉSIE</td></tr><tr><td>ALLEMAGNE</td><td>IRLANDE</td></tr><tr><td>ARABIE SAOUDITE</td><td>ISRAËL</td></tr><tr><td>AUSTRALIE</td><td>ITALIE</td></tr><tr><td>AUTRICHE</td><td>JAPON</td></tr><tr><td>BELGIQUE</td><td>KENYA</td></tr><tr><td>BRÉSIL</td><td>LIBAN</td></tr><tr><td>BULGARIE</td><td>MAROC</td></tr><tr><td>CAMEROUN</td><td>MONACO</td></tr><tr><td>CANADA</td><td>NORVÈGE</td></tr><tr><td>RÉP. POP. DE CHINE</td><td>PAKISTAN</td></tr><tr><td>CHYPRE</td><td>PAYS-BAS</td></tr><tr><td>RÉP. DE CORÉE</td><td>POLOGNE</td></tr><tr><td>RÉP. POP. DÉM. DE CORÉE</td><td>PORTUGAL</td></tr><tr><td>CUBA</td><td>ROUMANIE</td></tr><tr><td>DANEMARK</td><td>ROYAUME-UNI DE GRANDE-BRETAGNE
ET D'IRLANDE DU NORD</td></tr><tr><td>ÉGYPTE</td><td>SRI LANKA</td></tr><tr><td>ESPAGNE</td><td>SUÈDE</td></tr><tr><td>ÉTATS-UNIS D'AMÉRIQUE</td><td>SUISSE</td></tr><tr><td>ÉTHIOPIE</td><td>TANZANIE</td></tr><tr><td>FINLANDE</td><td>TCHÉCOSLOVAQUIE</td></tr><tr><td>FRANCE</td><td>TUNISIE</td></tr><tr><td>GRÈCE</td><td>U.R.S.S.</td></tr><tr><td>HONGRIE</td><td>YOUGOSLAVIE</td></tr><tr><td>INDE</td><td></td></tr></table>

## MEMBRES CORRESPONDANTS

Albanie - Bahrein - Bangladesh - Barbade - Botswana - Burkina Faso - Colombie - Costa Rica - Équateur - Fidji Ghana - Hong Kong - Irak - Islande - Jordanie - Koweit - Libye - Luxembourg - Malaisie - Mali - Maurice - Mexique Népal - Nouvelle-Zélande - Oman - Panama - Pérou - Philippines - Sénégal - Seychelles - Syrie - Trinité et Tobago Turquie -Venezuela

<div align="center">

# MEMBRES

</div>

du

<div align="center">

# COMITÉ INTERNATIONAL de MÉTROLOGIE LÉGALE

</div>

## ALGÉRIE

Membre à désigner par son Gouvernement

Correspondance adressée à

Office National de Métrologie Légale

1, rue Kaddour Rahim Hussein Dey

ALGER

## ALLEMAGNE

Mr M. KOCHSIEK

Directeur

Physikalisch-Technische Bundesanstalt,

Bundesallee 100 - Postfach 3345

3300 BRAUNSCHWEIG.

TP 49-531-592 80 10 FAX 49-531-592 40 06

TX 9-52 822 PTB

TG Bundesphysik Braunschweig

## ARABIE SAOUDITE

Mr KHALED Y. AL-KHALAF

Director General

Saudi Arabian Standards Organization

P.O. Box 3437

11471 RIYADH

TP 966-1-479 33 32 FAX 966-1-479 30 63

TX 40 16 10 saso sj

TG giasy

## AUSTRALIE

Mr J. BIRCH

Executive Director

National Standards Commission,

P.O. Box 282

NORTH RYDE, N.S.W. 2113.

TP 61-2-888 39 22 FAX 61-2-888 30 33

TX AA 23144

## AUTRICHE

Mr R. GALLE

Director of the Metrology Service

Gruppe Eichwesen

Bundesamt für Eich- und Vermessungswesen

Postfach 20

Arltgasse 35

A-1163 WIEN.

TP 43-222-92 16 27 FAX 43-222-92 44

TX 115 468 bevwn

## BELGIQUE

Mr H. VOORHOF

Inspecteur Général

Inspection Générale de la Métrologie

24-26, rue J.A. De Mot

B-1040 BRUXELLES

TP 32-2-233 61 11 FAX 32-2-230 83 00

TX 20 627 COM HAN

## BRÉSIL

Mr D.C. MOCSANYI

Président, INMETRO

Praça Mauá N° 7, 11 Andar

20081 RIO DE JANEIRO

TP 55-21-233 0286

TX 2134599 IMNQ BR

## BULGARIE

Mr V. TZAREVSKI

Vice-Président

Comité de normalisation, certification et métrologie

21, rue du 6 Septembre

1000 SOFIA

TP 359-2-8591 FAX 359-2-801402

TX 22 570 DKS BG

TG techprogress

## CAMEROUN

Mr S. NOUMSI

Sous-Directeur des Poids et Mesures

Direction des Prix, Poids et Mesures

Ministère du Développement Industriel et Commercial

BP 501

YAOUNDÉ

TP 237-22 31 16 et 237-23 26 17

TX 82-68 à Yaoundé

## CANADA

Mr R.G. KNAPP

Director, Legal Metrology Branch

Consumer and Corporate Affairs

207, rue Queen

OTTAWA, Ontario K1A OC9

TP 1-613-952 0655 FAX 1-613-952 1736

TX 053 3694

## RÉPUBLIQUE POPULAIRE DE CHINE

Mr BAI JINGZHONG

Deputy Director General

State Bureau of Technical Supervision

P.O. Box 2112

BEIJING 100009

TP 86-1-44 43 04 FAX

TX 210209 SBTS CN

TG 1918 Beijing

![](page=23,bbox=[1645, 2734, 1834, 2769])

## CHYPRE

Mr G. TSIARTZAZIS

Controller of Weights and Measures

Ministry of Commerce and Industry

NICOSIA

TP 357-2-40 34 41 FAX 357-2-36 61 20

TX 2283 MIN COMIND

TG Mincommind Nicosia

## RÉPUBLIQUE DE CORÉE

Mr SON BOCK-GILL

Director of Metrology Division

Bureau of Standards

Industrial Advancement Administration

2, Chungang-dong

KWACHON-CITY, KYONGGI-DO 427-010

TP 82-2-503 79 28 FAX 82-2-503 79 41

TG KOREA IAA

TX 28456 FINCEN K

## RÉPUBLIQUE POP, DÉM. DE CORÉE

Mr DJEUNG KI TCHEUL

Directeur de l'Institut Central de Qualité

et de Métrologie auprès du Comité National

de la Science et de la Technologie

Arrondissement de Sadong

PYONGYANG

TG standard

## CUBA

Membre à désigner par son Gouvernement

Correspondance adressée à:

Mr Acosta Alemany

Comite Estatal de Normalizacion

Egido 610 e/Gloria and Apodaca

HABANA Vieja

TP 53-7-62-1503, 62-1504, 62-2892

TX 512236 CENDH

TG CEN HAVANA

## DANEMARK

Mr Ove E. PETERSEN

Senior Executive Engineer

Division of Metrology

National Agency of Industry and Trade

Tagensvej 135

DK-2200 COPENHAGEN N

TP 45-31-85 10 66 FAX 45-31-81 70 68

TX 15768 INDTRA DK

## ÉGYPTE

Mr M. HILAL

Président,

Egyptian Organization for Standardization

and Quality Control

2 Latin America Street, Garden City

CAIRO.

TP 20-2-354 97 20 FAX 20-2-355 78 41

TX 93 296 EOS UN

TG TAWHID

## ESPAGNE

Membre à désigner par son Gouvernement

Correspondance adressée à :

Centro Espanol de Metrologia

c/ del alfar s/n

28760 TRES CANTOS (Madrid)

TP 34-1-803 33 03 FAX 34-1-803 11 78

TG 47254 CEME E

Bulletin OIML - N° 123 - Juin 1991

## ÉTATS-UNIS D'AMÉRIQUE

Mr S.E. CHAPPELL

Chief, Standards Management Program

Office of Standards Services

National Institute of Standards and Technology

Admin. 101, A625

GAITHERSBURG, Maryland 20899

TP 1-301-975 40 24 FAX 1-301-963 28 71

TX 197674 NBS UT

## ÉTHIOPIE

Mr Yohannes AFEWORK

Head of Technical Service

Ethiopian Authority for Standardization

P.O. Box 2310

ADDIS ABABA.

TP 251-1-15 04 00 et 15 04 25

TX 21725 ETHSA ET

TG ETHIOSTAN

## FINLANDE

Madame U. LÄHTEENMÄKI

Director of Metrology Department

Technical Inspection Centre

Box 204

SF 00181 HELSINKI

TP 358-0-61 671 FAX 358-0-6167 467

TG TEKTARTOS HKI

## FRANCE

Mr Ph. BERTRAN

Sous-Directeur de la Métrologie

S.A.R.T. Ministère de l'industrie et de l'aménagement

du territoire

22, rue Monge

75005 PARIS

TP 33-1-46 34 49 61 FAX 33-1-46 34 49 62

## GRÈCE

Mr A. DESIS

Technical Officer

Directorate of Weights and Measures

Ministry of Commerce

Canning Sq.

10181 ATHENS

TP 30-1-36 14 168 FAX 30-1-364 26 42

TX 21 67 35 DRAG GR et 21 52 82 YPEM GR

## HONGRIE

Mr D. BELEDI

Président, Országos Mérésügyi Hivatal,

P.O. Box 19

H-1531 BUDAPEST

TP 36-1-1567 722 FAX 36-1-1550 598

TX 22-4856 OMH

TG HUNGMETER Budapest

## INDE

Mr S. HAQUE

Director, Weights & Measures

Ministry of Food and Civil Supplies

Weights and Measures Unit

12-A, Jam Nagar House

NEW DELHI 110 011

TP 91-11-38 53 44

TX 31 61962 COOP IN

TG POORTISAHAKAR

## INDONÉSIE

Mr G.M. PUTERA

Director of Metrology

Directorate General of Domestic Trade

Departemen Perdagangan

Jalan Pasteur 27

40171 BANDUNG.

TP 62-22-50 597 et 50 695

TX 28 176

## IRLANDE

Mr J. LOWE

Assistant Secretary

Department of Industry and Commerce

Frederick Building, Setanta Centre,

South Frederick Street,

DUBLIN 2.

TP 353-1-61 44 44 FAX 353-1-67 95 710

TX 93478

TG TRADCOM Dublin

## ISRAEL

Mr. A. RONEN Controller of Weights, Measures and Standards Ministry of Industry and Trade P.O.B.299 JÉRUSALEM 91002 TP 972-2-27 241

## ITALIE

Mr C. AMODEO

Capo dell'Ufficio Centrale Metrico,

Via Antonio Bosio, 15

00161 ROMA.

TP 39-6-348 78 34

## JAPON

Mr S. HATTORI

Director General

National Research Laboratory of Metrology

1-4, Umezono 1-Chome, Tsukuba

IBARAKI 305.

TP 81-298-54 41 49 FAX 81-298-54 41 35

TX 03652570 AIST

TG KEIRYOKEN TSUCHIURA

## KENYA

Mr P.A. AYATA

Director of Weights and Measures

Weights and Measures Department

Ministry of Commerce

P.O. Box 41071

NAIROBI

TP 254-2-50 46 64/5

TG ASSIZERS, Nairobi

## LIBAN

Membre à désigner par son Gouvernement

Correspondance à adresser à

Service des Poids et Mesures,

Ministère de l'Économie et du Commerce,

Rue Al-Sourati, imm. Assaf

RAS-BEYROUTH.

TP — 34 40 60

## MAROC

Mr M. BENKIRANE

Chef de la Division de la Métrologie Légale

Direction de l'Industrie

5, rue Errich, Immeuble A, Quartier Tour Hassan

RABAT.

TX 31816 M

## MONACO

Mr A. VEGLIA

Ingénieur au Centre Scientifique de Monaco

16, Boulevard de Suisse

MC 98000 MONTE CARLO

TP 33-93-30 33 71

## NORVÈGE

Mr K. BIRKELAND

Directeur Général

Service National de Métrologie

Postbox 6832 St. Olavs Plass

0130 OSLO 1

TP 47-2-20 02 26

## PAKISTAN

Mr M. ASAD HASAN

Director

Pakistan Standards Institution

39-Garden Road, Saddar

KARACHI-74400.

TP 92-21-772 95 27

TG PEYASAI

## PAYS-BAS

Mr J.A.J. BASTEN

Directeur, Ijkwezen bv

Nederlands Meetinstituut nv

Postbus 654

2600 AR DELFT.

TP 31-78 33 23 00

TX 38 373 IJKWZ NL

## POLOGNE

Mr Z. REFEROWSKI

Vice-Président

Polski Komitet Normalizacji, Miar i Jakosci

ul. Elektoralna 2

00-139 WARSZAWA.

TP 48-22-20 54 34 FAX 48-22-20 83 78

TX 813 642 PKN

TG PEKANIM

## PORTUGAL

Mr J.N. CARTAXO REIS

Service de la Métrologie

Instituto Português da Qualidade

Rua Prof. Reinaldo dos Santos

Lote 1378

1500 LISBOA

TP 351-1-78 61 58

TX 65744 METROQ P

## ROUMANIE

FAX 351-1-78 1980

Mr D. STOICHITOIU

Directeur de la Métrologie d'État

Commission Nationale de Normalisation,

Métrologie et Qualité

21, Boulevard Nicolae Balcescu

BUCAREST 1

TP 40-0-13 16 05 FAX 40

TX 011 355 IGS R

## ROYAUME-UNI

Mr S. BENNETT

Director

National Weights and Measures Laboratory

Stanton Avenue

TEDDINGTON, Middlesex TW 11 OJZ

TP 44-81-943 72 72 FAX 44-81-943 72 70

TX 931213043 (WM G)

## SRILANKA

Mr H.L.R.W. MADANAYAKE

Deputy Commissioner of Internal Trade

Measurement Standards and Services Division

Department of Internal Trade

101, Park Road

COLOMBO 5.

TP 94-1-83 261

## SUEDE

Mr R. OHLON

Ingénieur en Chef, Statens Provningsanstalt.

P.O. BOX 857

S-501 15 BORÅS.

TP 46-33-16 50 00 FAX 46-33-13 55 02

TX 36252 TESTING S

## SUISSE

Mr O. PILLER

Directeur, Office Fédéral de Métrologie

Lindenweg 50

CH- 3084 WABERN

TP 41-31-59 61 11 FAX 41-31-59 62 10

TG OFMET

## TANZANIE

Mr A.H.M. TUKAI

Commissioner for Weights and Measures

Weights and Measures Bureau

Ministry of Industries and Trade

P.O. Box 313

DAR ES SALAAM

TP 64046/64797/64808

TX 41 689 INDIS

## TCHÉCOSLOVAQUIE

Mr M. CIBAK

Advisor of the Director

Czechoslovak Institute of Metrology

L. Novomeskeho 4

842 55 BRATISLAVA

TP 42-7-329 820 et 329 865

TX 92786 METR

TG METR BRATISLAVA

## TUNISIE

Mr Ali BEN GAID

Président Directeur Général

Institut National de la Normalisation

et de la Propriété Industrielle

Boîte Postale 23

1012 TUNIS BELVEDERE

TP 216-1-785 922

TX 13 602 INORPI

## U.R.S.S.

Mr V.I. PUSTOVOIT

Vice-Président

Gosstandart

Leninsky Prospect 9

117049 MOSCOU.

TP — 236 40 44

TX 411 378 GOST

TG Moskva-Standart

FAX 216-1-781 563

## YOUGOSLAVIE

## TP = téléphone

Mr Z.M. MARKOVIC

Head of International Cooperation

Federal Bureau of Measures and Precicious

Metals

Mike Alasa 14

11000 BEOGRAD.

TP 38-11-18 37 36 FAX 38-11-620 134

TX 11 020 YUZMBG

## FAX = telécopie (teléfax)

Les numéros sont en général indiqués pour le régime automatique international à l'exception des numéros qui sont précédés d'un trait.

The call numbers are generally indicated for international automatic dialling except where the local number is preceded by a dash.

TG = télégramme TX = télex

Pour tout télex ou télégramme, il est nécessaire d'indiquer le nom de la personne et sa qualité.

For all telex or telegrams it is necessary to indicate name of person and occupation.

## PRÉSIDENCE

Président K. BIRKELAND, Norvège

Vice-Président ... S.E. CHAPPELL, U.S.A.

Vice-Président N...

## CONSEIL DE LA PRÉSIDENCE

K. BIRKELAND, Norvège, Président

K. BIRKELAND, Norvege, President

S.E. CHAPPELL, U.S.A., V/Président M. KOCHSIEK, Allemagne

J. BIRCH, Australie R.G. KNAPP, Canada

BAI JINGZHONG, Rép. Pop. de Chine Ph. BERTRAN, France

V.I. PUSTOVOIT, U.R.S.S. S. BENNETT, Royaume-Uni

Le Directeur du Bureau International de Métrologie Légale

## BUREAU INTERNATIONAL DE MÉTROLOGIE LÉGALE

Directeur B. ATHANÉ

Adjoint au Directeur S.A. THULIN

Adjoint au Directeur F. PETIK

Ingénieur Consultant W.H. EMERSON

Ingénieur E. WEBER

Administrateur Ph. LECLERCQ

## MEMBRES D'HONNEUR

H. MOSER, Allemagne - Membre du Conseil de la Présidence

V. ERMAKOV, U.R.S.S. - Vice-Président du Comité

A.J. van MALE, Pays-Bas - Président du Comité

A. PERLSTAIN, Suisse - Membre du Conseil de la Présidence

W. MUEHE, Allemagne - Vice-Président du Comité

H.W. LIERS, Allemagne - Membre du Conseil de la Présidence

<div align="center">

# ADRESSES DES SERVICES DES MEMBRES CORRESPONDANTS

</div>

## ALBANIE

Directeur

Drejtoria e Standardeve dhe e Mjeteve

Matëse (DSMA)

në Komisionin e Planit të Shtetit

TIRANA

## BAHREIN

The Responsible of Metrology Standards and Metrology Section Ministry of Commerce and Agriculture P.O. Box 5479 MANAMA

## BANGLADESH

Director General Bangladesh Standards and Testing Institution 116-A Tejgaon Industrial Area DHAKA 1208

## BARBADE

Director Barbados National Standards Institution Culloden Road St. Michael BARBADOS W.I.

## BOTSWANA

The Permanent Secretary Division of Weights and Measures Department of Commerce and Consumer Affairs Private Bag 48 GABORONE

## BURKINA FASO

Direction Générale des Prix

Ministère du Commerce

et de l'Approvisionnement du Peuple

BP 19

OUAGADOUGOU

## COLOMBIE

Superintendencia de Industria y Comercio Centro de Control de Calidad y Metrologia Cra. 37 No 52-95, 4° piso BOGOTA D.E.

## COSTA RICA

Oficina Nacional de Normas y Unidades

de Medida

Ministerio de Economia y Comercio

Apartado 10 216

SAN JOSE

## ÉQUATEUR

The Director General

Instituto Ecuatoriano de Normalizacion

Calle Baquerizo Moreno No 454

entre 6 de Diciembre y Almagro

Casilla No 3999

QUITO

## Bulletin OIML - N°123 - Juin 1991

## FDJJ

The Chief Inspector of Weights and Measures Ministry of Economic Development, Planning and Tourism Government Buildings P.O.Box 2118 SUVA

## GHANA

Ghana Standards Board

Kwame Nkrumah Conference Centre

(Tower Block - 2nd Bay, 3rd Floor)

P.O. Box M-245

ACCRA

## HONG-KONG

Commissioner of Customs and Excise (Attn. Trading Standards Investigation Bureau) Tokwawan Market & Government Offices 165, Ma Tau Wei Road 11/F., Kowloon HONG KONG

## IRAK

Planning Board

Central Organization for Standardization

and Quality Control

P.O.B.13032

Al Jadiria

BAGHDAD

## ISLANDE

The Director

Weights and Measures in Iceland

Loggildingarstofan

Sidumula 13

P.O. Box 8114

128 REYKJAVIK

## JORDANIE

Directorate of Standards Ministry of Industry and Trade P.O.Box 2019 AMMAN

## KOWEIT

The Under Secretary Ministry of Commerce and Industry Department of Standards and Metrology Post Box No 2944 KUWAIT

## LIBYE

The Director General National Centre for Standardization and Metrology (N.C.S.M.) P.O.Box 5178 TRIPOLI

## LUXEMBOURG

Le Préposé du Service de Métrologie Administration des Contributions Rue des Scillas 2529 HOWALD

## MALAISIE

The Acting Director of Standards Standards and Industrial Research Institute of Malaysia P.O. Box 35, Shah Alam SELANGOR

## MALI

Le Directeur Général des Affaires Économiques

(Service des Poids et Mesures)

BP 201

BAMAKO

## NOUVELLE-ZELANDE

## MAURICE

The Permanent Secretary Ministry of Trade and Shipping (Division of Weights and Measures) New Government Centre PORT LOUIS

## MEXIQUE

Direccion General de Normas

Secretaria de Comercio y Fomento Industrial

Sistema Nacional de Calibracion

Ave. Puente de Tecamachalco no. 6 - Planta Baja

Lomas de Tecamachalco, Seccion Fuentes

53950 NAUCALPAN DE JUAREZ

## NÉPAL

The Chief Inspector Nepal Bureau of Standards and Metrology P.B.985 Sundhara KATHMANDU

The Manager Trade Measurement Unit Ministry of Consumer Affairs P.O.Box 1473 WELLINGTON

The Director General for Specifications and Measurements Ministry of Commerce and Industry P.O.Box 550 MUSCAT

## OMAN

Le Directeur

Comision Panamena de Normas Industriales

y Tecnicas

Ministerio de Comercio e Industrias

Apartado 9658

PANAMA 4

## PANAMA

## PÉROU

The Director General

ITINTEC Instituto de Investigacion Tecnologica

Industrial y de Normas Tecnicas

Av. Guardia Civil No. 400

LIMA 41

## PHILIPPINES

The Director Product Standards Agency Ministry of Trade and Industry Trade & Industry Building 361 Sen. Gil J. Puyat Avenue Makati, Metro Manila PHILIPPINES 3117

## SÉNÉGAL

Monsieur le Directeur

Institut Sénégalais de Normalisation

Ministère du Plan et de la Coopération

DAKAR

## SEYCHELLES

The Director Seychelles Bureau of Standards P.O.Box 648 VICTORIA

## SYRIE

The General Director The Syrian Arab Organization for Standardization and Metrology P.O.Box 11836 DAMASCUS

## TRINITÉ ET TOBAGO

The Director Trinidad and Tobago Bureau of Standards P.O.Box 467 PORT OF SPAIN

## TURQUIE

Monsieur le Directeur Général

Service du Contrôle de la Qualité et des Mesures

Sanayi ve Ticaret Bakanligi

Ölçüler ve Kalite Kontrol Genel

Müdürlügü

ANKARA

## VENEZUELA

Le Directeur

Direccion General de Tecnologia

Servicio Nacional de Metrologia

Ministerio de Fomento,

Av. Javier Ustariz, Edif. Parque Residencial

Urb. San Bernardino

CARACAS.

