<div align="center">

# BULLETIN

</div>

DE

![](page=0,bbox=[1339, 384, 1739, 641])

L'ORGANISATION

INTERNATIONALE

DE MÉTROLOGIE LÉGALE

Organe de Liaison entre les Etats-membres

![](page=0,bbox=[99, 1475, 1849, 2389])

BUREAU INTERNATIONAL DE METROLOGIE LEGALE 11. Rue Turgot 75009 PARIS France

<div align="center">

# BULLETIN

de

l'ORGANISATION INTERNATIONALE de MÉTROLOGIE LÉGALE

</div>

## SOMMAIRE

REPUBLIQUE FEDERALE D'ALLEMAGNE — Pattern approval of electromechanical weighing machines with requirements for « operational fault perceptibility » par P. BRANDES et M. KOCHSIEK ... 3

SUISSE — L'électronique dans les instruments de mesurage par P. KOCH ... 17

PAYS-BAS — Technical surveillance of roulette-cylinders par R. MUIJLWIJK ... 21

BIML — Travaux des Secrétariats OIML en 1981 ... 26

BIML — Work of the OIML Secretariats in 1981 ... 31

INFORMATIONS

FRANÇAIS : Nouvel Etat Membre, Nouveaux Membres du Comité, Nomination ... 36

ENGLISH : New Member State, New Members of the Committee, Nomination ... 36

New metrology standards issued by CMEA ... 37

Réunions ... 38

DOCUMENTATION

Centre de Documentation : Documents reçus au cours du 1er trimestre 1982 ... 40

Recommandations Internationales : Liste complète à jour ... 43

Etats membres de l’Organisation Internationale de Métrologie Légale ... 46

Membres actuels du Comité International de Métrologie Légale ... 47

Abonnement annuel :

Europe : 85 F-français

Autres pays : 100 F-français

Chèques postaux : Paris-8 046-24 X

Banque de France, Banque Centrale, Paris : n° 5 051-7

BUREAU INTERNATIONAL DE METROLOGIE LEGALE

11, Rue Turgot — 75009 Paris — France

Tél. 878-12-82 et 285-27-11 Le Directeur : Mr B. ATHANÉ

TELEX : 660870 SVP SERV.-code 1103

<div align="center">

# PATTERN APPROVAL of ELECTROMECHANICAL WEIGHING MACHINES with REQUIREMENTS for " OPERATIONAL FAULT PERCEPTIBILITY " (*)

</div>

P. BRANDES and M. KOCHSIEK, Physikalisch-Technische Bundesanstalt (PTB) Braunschweig

RESUME — Cet article démontre par des exemples comment un instrument électronique de pesage peut être équipé de dispositifs de contrôle prévenant l'opérateur des éventuels défauts de fonctionnement.

SUMMARY - This paper shows by examples how an electronic weighing machine may be equipped with checking devices which signal possible operational defects to the user.

## 1. Introduction, type of faults, principles of checking

In the Federal Republic of Germany, electronic devices incorporated in weighing machines subject to mandatory verification must be designed such that an operational fault (for instance due to a failed component or an error in software) does not lead to an incorrect measurement, or such that the fault is necessarily detected by the operator of the weighing machine. This facility of the electronic equipment is referred to as « operational fault perceptibility 〉 (OFP).

It is indeed not necessary that every type of fault be detected and displayed by incorporated checking facilities, particularly in the case of weighing machines handled by a specially trained operator, for instance class I laboratory balances. On the other hand, technically more sophisticated checking features are required for class III counter-scales as they are handled by different untrained operators. With regard to the operational faults occurring in a weighing machine, the following may be distinguished:

Obvious functional faults can usually be recognized by the operator without difficulty. Among these, are, for instance, mains failures, defect of parts of the indicating device or its total failure, illegible figures, one or several digits of the indication are missing, the indicated values change continuously, or not at all, and so on.

Insignificant faults which do not result in the maximum permissible errors being exceeded, are likewise not considered here since they are without metrological

relevance and are not perceived anyway. Similarly, the simultaneous occurrence of two or more uncorrelated operational faults which make the indication of a fault impossible, need not be detected by checking facilities.

Significant faults are those, leading to incorrect measuring results. They exceed the maximum permissible errors or a specified part thereof, and cannot be recognized by the operator. These faults must be detected by the checking facility and signalized to the operator.

Incorporated checking facilities can operate according to different principles. In the draft of the EC Frame Directive 71/316/EWG a distinction is made between [1] :

- permanent automatic checking during the measurement, the checking level is designated by P ;

- intermittent automatic checking; this is performed between measurements, the checking level is I;

non-automatic checking, this is initiated manually by the operator, this may result in an indication which the operator has to compare with a nominal indication; this checking level is N.

The control measures specified in the following are meant to detect, above all, any kind of failure of the components. The following failures may occur:

## — in analogue components :

interruptions of the connecting lines, short circuits or interruptions within the components, changes in the operating points or in the characteristic curve of the components.

As an example figure 1 shows the operational characteristic of an analogue amplifier. Curve a shows the correlation between the input and output. A failure of the component will lead to curve b which means that the same input results in an incorrect output.

![](page=5,bbox=[750, 1503, 1377, 2008])

<div align="center">

Figure 1

</div>

<div align="center">

Failure of an analogue component

</div>

## in digital components :

interruptions of the connecting lines, defects in the component so that, despite connection, the logical level (high or low) is not reached or maintained. Intermediate stages lead to faulty connection of subsequent components.

These considerations do not distinguish between the different technologies of the components used, which may be transistors, TTL, CMOS technique or microprocessors.

## 2. OFP shown for an electromechanical scale

Fig. 2 shows a block diagram of the electronic device of an electromechanical weighing machine equipped with strain gauge load cells.

![](page=6,bbox=[373, 505, 1465, 1464])

<div align="center">

Figure 2

</div>

<div align="center">

Block diagram of an electronic weighing machine

</div>

The diagram is subdivided into the following functional blocks :

analogue section,

analogue-to-digital converter ADC,

microprocessor/system,

output-section.

The analogue section comprises the preamplifier (AMP) and the Integrator (IN). The analogue-to-digital converter (ADC) includes an oscillator (O), the control logic (CL) and the counter (C). The microprocessor system comprises the multiplexer (Mu), the central processing unit (CPU), the read only memory (ROM), the random access memory (RAM) and the input/output interface (I/O). The output section contains the BCD to 7 segment decoder, driver (DR), display, checking device (check). The output to a printer or data processing system contains a memory (M) and an optocoupler (O).

On the basis of these functional blocks and the components they contain, a short description of the functions will be given, and how the operational fault perceptibility can be realized.

## 2.1. Analogue section

Fig. 3 shows the analogue section of this type of electronic evaluating device. The output voltage of the strain gauge load cell is amplified in the amplifier (AMP).

![](page=7,bbox=[391, 344, 1742, 886])

<div align="center">

Figure 3

</div>

<div align="center">

Analogue section from figure 2

</div>

Additional analogue components may be incorporated for the dead-load-suppression, offset-voltage-suppression, filtering or impedance-conversion (F). In addition, a reference voltage $ U_{\mathrm{Ref}} $ is generated from the supply voltage $ U_{\mathrm{S}} $ . In this example the dual-slope method is used for the analogue-to-digital conversion. An electronic switch (S), an integrator (I), a comparator (C) and as indicated in fig. 8 a counter, an oscillator and the control logic are required for this purpose. Checking circuits, to be described later, can be incorporated in the dotted-line square.

Fig. 4 shows that the integration of the amplified strain gauge output-voltage is carried out during a fixed time $ t_{1} $ . Subsequently the integrating capacitor is discharged against the reference voltage $ U_{\mathrm{Ref}} $ . The comparator then determines when the voltage has reached zero value. During this discharge period, pulses from the oscillator are fed into a counter. The number of pulses is proportional to the measured voltage.

![](page=7,bbox=[555, 1597, 1576, 2223])

<div align="center">

Figure 4

</div>

<div align="center">

Principle of dual slope conversion

</div>

Amplification of the measuring voltage usually takes place with small amplification factors using operational amplifiers with heavy negative feed back. Experience over

many years shows that this circuit layout normally prevents the occurrence of sudden changes as a result of failures, but leads only to slow, gradual changes instead. The components discussed so far, including the comparator, have an analogue function. It is sufficient for these components to check only a single point of the whole working range for operational fault perceptibility.

The testing principle is represented in Figure 5. If for a certain load here 10 kg the readout 10.00 kg is obtained, then the analogue part is considered to be completely free from faults: changes in the characteristics, amplification factors or linearities within the analogue part always result in a change of the test readout. The digital part is checked too, but only for this readout value. Testing cannot be done, however by loading in all cases, since this is not possible for machines with higher maximum loads. Consequently an electrical signal is switched to the input of the amplifier. In the following, using three examples, this control setup will be described.

![](page=8,bbox=[432, 900, 1395, 1590])

The control setup will be inserted in the dotted-line square in front of the amplifier in figure 3.

- In Fig. 7a test voltage $ U_{\mathrm{T}} $ drawn from the supply voltage $ U_{\mathrm{S}} $ is switched to the input of the preamplifier. Figure 6 shows that this test voltage should be chosen such that a readout of 90 % to 100 % of the maximum load of the weighing machine is achieved. If the analogue part is fault-free, then the correct testing figures are shown on the display.

- A fault in the analogue part will produce a change in the testing figures on switching to the testing voltage. Testing must be done for unloaded and zero set balances. This is usually done manually by the operator. He also has to compare the test readout with the nominal value. This value with the tolerances is stamped on a small label fixed near the readout. In this way faults can be recognized by the operator and he is obliged to have the machine serviced when he has detected such a fault. This manual checking of the machine should be performed by the operator several times a day. The testing method corresponds to the level N.

- Similarly in Figure 7b test voltage $ U_{\mathrm{T}} $ is drawn from the supply voltage $ U_{\mathrm{S}} $ and switched to the input of the preamplifier. The load cell output voltage is switched off, however, so that checking can be done, independent of the load, at any arbitrary time. Here testing is also done manually and the operator has to compare test readout with the nominal value. The test corresponds to level N.

![](page=9,bbox=[554, 345, 1576, 1300])

<div align="center">

Figure 6 Checking by test voltage

</div>

- In Figure 7c the mechanical switches of Figure 7b are replaced by electronic switches. If these switches are controlled via the microprocessor system, automatic checking of the analogue part becomes possible. Here too, comparison with a nominal value is necessary, but this can be done by the CPU. The nominal value is then stored in the microprocessor system. Automatic testing in this way corresponds to level I. It can be performed at arbitrary, but predetermined time intervals minutes or hours.

The analogue part only sends out control signals to trigger gates for pulse counting in the subsequently switched counter. If these signals fail due to line interruptions of failure of the controlling component, the readout either changes continually or stays fixed. This can be recognized by the operator. This also holds true if the oscillator frequency should not be stable. In addition, the transfer lines are included in the checking of the analogue part described above.

## 2.2. Transfer line from the dual-slope to the counter via the control logic.

## 2.3. Counter

Oscillator pulses are fed into the counter (Figure 8) as long as the gates of the control logic are open. The counter usually encompasses 4 to 8 decades and works in the binary- or BCD code. It is the first component of the digital part, which should be continuously and automatically tested. A few testing examples shall now be described :

- Doubling of counter and comparison of both outputs in the microprocessor system. This would be a permanent checking of the counter, level P.

![](page=10,bbox=[415, 380, 1513, 2471])

![](page=11,bbox=[429, 326, 1672, 1022])

<div align="center">

Figure 8

</div>

<div align="center">

A-D conversion to diagram figure 4

</div>

- Pulses are drawn from the microprocessor system so that 2 test-values are generated. Figure 9 shows an example with the test-values 6666 and 9999. These values have inverse bit-combinations in the BCD-code. When these test-values are found correct by the CPU, all lines and components between counter and CPU are fault-free.

<table border="1"><tr><td></td><td colspan="4">BCD-code</td><td>decimal-code</td></tr><tr><td>test-value1</td><td>0110</td><td>0110</td><td>0110</td><td>0110</td><td>6666</td></tr><tr><td>test-value2</td><td>1001</td><td>1001</td><td>1001</td><td>1001</td><td>9999</td></tr></table>

<div align="center">

Figure 9

</div>

<div align="center">

Test values for checking of digital components

</div>

If this testing programme is run through before each measuring cycle the checking corresponds to level P.

This testing programme could also be run with larger time intervals, for instance at every load change, or automatically every 5 seconds. This would correspond to level I.

## 2.4. Transfer line from counter to multiplexer.

The transfer lines between these components (Figure 8) can suffer interruptions and must therefore be checked, which can be done by, for instance:

- Dual channel transfer of data with subsequent yield comparison in the CPU.

- During a testing programme before or in between the measurements, test data are transferred such that both logical levels (low and high) occur on all lines. Comparison for correctness by the CPU.

Combined checking together with counter and multiplexer.

## 2.5. Microprocessor system

A microprocessor system as shown in figure 2, essentially comprises a central processing unit (CPU), read-only memory (ROM, PROM), input-output interface, multiplexer, random-access memory (RAM), data bus, address bus and control-lines. In this system the information from the counter is processed according to a given scheme, interim stored and read out, for indicating or recording purposes. The microprocessor system has the additional task of checking itself and all or most of the digital components. All steps of operation are determined by the commands stored in the programme memory (ROM, PROM). These are called up successively from the CPU and carried through. By appropriately linking various commands the microprocessor system can carry out certain working modes, and so the input data are processed. However the functions of the microprocessor system should not be discussed here. In the following, a few methods for checking the microprocessor system are treated; these are discussed as examples separately for each component.

## 2.6. Multiplexer

The Multiplexer is a parallel — serial converter which converts the parallel data from the counter into serial data for injection into the microprocessor system. The data are switched consecutively onto the data bus by the multiplexer and transferred to the microprocessor system. The following checking modes are possible :

- Dual channel transfer using two multiplexers and comparison in the microprocessor system. This corresponds to level P.

- Transfer in a fault-perceptive code with the Hamming-distance of 2 or more. This is a BCD-Code, for example, with a parity-bit. Checking is done in the microprocessor system. This is level P.

- A testing programme is run through before the measuring cycles. This must be set up such that mutually inverse bit combinations are transferred and checked in the microprocessor system. This is also equivalent to level P.

## 2.7. Data and address-busses, control lines

The data-bus need not be specially safeguarded or checked since all data and programme commands flow through it, hence we have multiple utilization. Operational faults are recognized by the operator immediately, for instance because the microprocessor detects the fault and reports failure or because varying or fixed readouts occur. The same is true for the address-bus and the control lines. The programme can only run correctly in the microprocessor system at all if the lines mentioned above are intact.

## 2.8. Read-only memory (ROM, PROM)

We assume that operational faults in the commands will in practically every case produce obvious failures in the microprocessor system, easily recognized by the operator. However, if the constants, tables etc. stored in the programme memory are falsified as a result of a component failure, this cannot always be recognized. An example of this is the command "add the digit 3". As a result of a bit fault this can become the command "add the digit 7"; and so one must ensure that the data used as constants are free of this type of error. Possible solutions are :

- Duplicate storage and comparison of data in the CPU after readout of the data

- Storage of data with parity-bit and checking in the CPU after readout

- Test summation of the total storage content and comparison with a similarly stored nominal value. For the test summation addition without carrying is sufficient. Testing occurs in the microprocessor system.

## 2.9. Random access memory (RAM)

The RAM's must be completely checked since both malfunctions and failures in these components often lead to incorrect measured values. Checking can be done according to one of the following methods:

Before the data are fed in, a test programme is run. Mutually inverse bit patterns are fed in, read out and individually checked. In this way all memory sites can be consecutively checked.

- Feed in of data and immediate readout and comparison in the CPU with the original data (read after write).

- Duplicate storage of data. Comparison for correctness in the CPU after readout.

- Storage of data with parity-bit and checking in the CPU after readout.

- Generation and storage of a test sum and checking in the CPU after readout.

Since, apart from component failures, temporarily effective external disturbances can also cause malfunctions in the RAM, the first two testing methods mentioned may only be used for data which is renewed after every measuring cycle. Operational faults can then be detected by the operator because the indicator flickers. Data which are to be stored for a longer period must always be checked according to one of the last three methods listed. These would for instance apply to data for the zero point, for tare-values or for totalizing.

## 2.10. Central processing unit (CPU)

Comprehensive checking of the CPU is hardly possible because of the complexity of this component. Nevertheless, the essential functions contributing to the determination of weighing results should be checked to some extent. Three possibilities for this kind of testing are shown :

- A testing programme is run through between measurements. Here, fixed values contained in the programme storage are treated to the same numerical operation as the measured values. The result is compared with a nominal value in the CPU.

- Within the testing programme running between measurements essential instructions are checked for correct functioning. Fixed values in the programme storage are added, subtracted, multiplied and divided and the result compared with a nominal value.

- The value fed into the microprocessor system is processed. The result which is the measured value is then processed by inverse operations. The resulting value should be identical with the originally injected value if the CPU is functioning correctly. An example showing multiplication and subsequent division of values for checking purpose is given in fig. 10.

Checking of the external electronic components (counter, multiplexer, indicator, etc.) is increasingly being carried out by the microprocessor system, with the CPU performing the comparisons.

Fig. 11 shows two counters the results of which are compared in a special comparative circuit. A flashing light indicates the operational fault. The comparative circuit can however itself become faulty, so that it may no longer register errors in counter 1 and/or report them. Unknown errors can result. That is why in this kind of circuit an additional manually operated switch is required to simulate an error. On switching, the flashing light must start.

Fig. 12 shows the checking of both counters by the microprocessor system. Initially both counter contents are read into the microprocessor system and stored. They are then subtracted. If the result is zero the programme runs through normally, if not the remaining programme is blocked. This can again be detected by the operator. Thus additional manual checking of the counter comparison is no longer necessary.

This comparative operation in the CPU is also required for checking the CPU itself, the data and programme storage and very often during normal course of programme run-through. Errors in the comparative operation are immediately recognized because the rest of the programme is interrupted in the CPU and the indication is blocked or keeps changing or the flashing light comes on.

![](page=14,bbox=[519, 328, 1335, 1624])

<div align="center">

Figure 10 Check computation

</div>

![](page=14,bbox=[555, 1773, 1279, 2338])

<div align="center">

Figure 11

</div>

<div align="center">

Checking circuit for counter with manual proving

</div>

![](page=15,bbox=[655, 330, 1445, 1482])

<div align="center">

Figure 12

</div>

<div align="center">

Automatic comparison of two counters

</div>

## 2.11. Output of measured value to the indicating device

The output is obtained via an input-output interface in BCD-Code. Conversion then takes place to 7-segment information, the current amplification with driver components and finally indication by light emitting diode display (LED). Individual indicators are activated consecutively and cyclically (multiplex operation). Separate testing of individual components (decoder, driver, indicator element) is difficult and time-consuming, and often this requires additional components. Therefore it is better to set an information link at the end of the component chain and feed information back into the microprocessor system for comparison. This allows all the components in the chain to be checked.

Fig. 13. shows selection of a segment. The 7-segment decoder determines which of the 7 segments shall light up. The decade at which the segments selected by the decoder light up, is determined by the drivers. Checking the indication is usually only possible using the currents flowing through the segments. This is realized by using analogue operational amplifiers, which give logical zero output if the voltage is either less than 1 V (short circuit) or is higher than 2 V (interruption). Only when neither of these two failures occurs and the appropriate segment is alight, the output of the operational amplifier is logical 1. This information is gained from all segments in the same way and fed back into the CPU. There it is coded back into BCD-information and compared with the output value. All components including the indicator are checked in this way. This kind of test needs not encompass all 7 segments, but only 5. Fig. 14 shows that for faults in the segments c or d either

![](page=16,bbox=[495, 348, 1464, 1302])

U $ \leq $ 1 volt = short circuit in LED

U $ \geq $ 2volt = interruption in LED

1 volt < U < 2 volt = LED luminous

<div align="center">

Figure 13 Checking of LED display

</div>

correct or illegible digits are the consequence and so errors are perceptible to the operator.

The use of different indicator elements can occasionally reduce the scope of the necessary checks, since some of the possible errors can be easily detected by the operator. For gas discharge and fluorescent indicators the only control required is whether a current is flowing through the segments or not. The value of the current need not be measured. This can be achieved quite easily using digital components.

Checking becomes even more simple when fluorescent or gas discharge tubes with four or more indicating digits are used in a tube-block with multiplex selection. Here it is sufficient for the information, which is fed back into the microprocessor system for checking, to be tapped off behind the decoder. Faults in the following driver components or indicator elements are recognizable since they affect several indicator digits simultaneously.

## 2.12. Output of the measured values to an auxiliary device (printer, remote indicator)

The output of the measured values often takes place in BCD-Code with parity-bit. More recently the ASCII-code, again with parity-bit, is being increasingly used. Data transfer can occur serially, word-serially/digit-parallel or fully in parallel. The connected auxiliary devices must not influence the electronics of the measuring device in any way, even if they have a short circuit. This is achieved by insertion

![](page=17,bbox=[474, 343, 1633, 1094])

<div align="center">

=obvious fault

</div>

<div align="center">

Figure 14

</div>

<div align="center">

Segment failures leading to obvious faults

</div>

of relays, opto-couplers, driver components, etc. Checking the data is done in the auxilliary device. In some cases an error signal must be fed back, for instance if a secondary indication or a printer is far away from the operator's stand.

## 3. Conclusion

The example described here has demonstrated how Operational Fault Perceptibility (OFP) can be realized, beginning with the load cell via the analogue part, ADC, microprocessor system to the output section. It is quite clear that there are other solutions to the OFP problem. A systematical analysis of OFP requirements is given in [4].

## References

[1] --- Elektronische Einrichtung als Bestand- oder Zubehörteile von Meßgeräten aus Vorschlag für eine Richtlinie des Rates zur Anderung der Richtlinie 71/316/EWG des Rates vom 26-7-1971 zur Angleichung der Rechtsvorschriften der Mitgliedstaaten betreffend gemeinsame Vorschriften über Meßgeräte sowie über Meß- und Prüfverfahren im Amtsblatt der Europäischen Gemeinschaften C 42 vom 15-2-1979. PTB-Mitteilungen 89 C (1979) S. 263-269.

[2] MUHLFELD A, SÜß R. Zur Funktionssicherheit bzw. — Erkennbarkeit bei elektronischen Baugruppen elektromechanischer Meßgeräte PTB-Mitteilungen 88 (1978), S. 328-331.

[3] SÜß R., MÜHLFELD A. Funktionsfehlersicherheit elektronischer Baugruppen in eichpflichtigen Meßgeräten, insbesondere bei nichtselbsttätigen Waagen PTB-Mitteilungen 85 (1975), S. 124-129.

[4] VOLKMANN Chr. U. Survey of the Possibilities to Maintain Correct Measurement through Increased Reliability of Components or through Operational Fault Perceptibility. OIML-Seminar « Electronic Devices Incorporated in Weighing and Liquid and Gas Volume Measuring Instruments 》，Boras 21. - 25. Sept. 1981 PTB-Bericht Me 35, 1981.

<div align="center">

# L'ELECTRONIQUE dans les INSTRUMENTS de MESURAGE (*)

</div>

par P. KOCH

Sous-directeur de l'Office Féderal de Métrologie

SUMMARY The impact of electronics and the subsequent automation of instruments subject to preventive legal action is discussed. Elimination of the influence of possible malfunctions may be reached in two ways : by incorporated self-checking devices or by maintaining a very high quality of the components.

The two ways and their incidence on official approval of instruments are compared in this paper.

RESUME — Le problème posé par l'électronique et l'automation des instruments est discuté dans le cas d'un système juridique préventif. En particulier, quelles sont les possibilités de maintenir la garantie d'eliminer les mesurages erronés ?

La recherche dont l'objectif est l'elimination des erreurs de fonctionnement débouche sur deux options principales. On peut ou bien incorporer aux instruments des circuits supplémentaires exerçant une surveillance logique interne ou bien utiliser des composants de qualité très élevée. On compare les deux termes de cette alternative et on étudie son incidence sur l'approbation officielle des instruments.

## La législation préventive

Un système juridique préventif est caractérisé par le fait que le législateur ne se contente pas de régler ce qui doit être prescrit et de décider ce qui peut être laissé au libre choix des intéressés. Il prend en plus des mesures appropriées visant à faciliter autant que possible l'exécution des prescriptions. Dans le domaine du pesage, il ne fixera pas seulement des normes de précision sur les résultats, il fera en plus en sorte que des balances de la qualité requise, approuvées officiellement, soient disponibles pour des opérations critiques auxquelles elles sont nécessaires.

Tant qu'il s'est agi de balances mécaniques simples, il n'a pas été difficile de surveiller leur bon fonctionnement et de s'assurer qu'elles convenaient bien pour l'emploi prévu. La géométrie de la construction déterminait la linéarité de l'indication et la corrélation entre le poids et le résultat.

La sensibilité, l'amortissement et la détérioration de l'instrument en service dépendaient en bonne partie de la qualité et de la fixation des couteaux et des coussinets. Après avoir vu et apprécié ces détails, l'agent responsable de l'approbation de modèle pouvait être raisonnablement sûr que tout défaut de fonctionnement serait irréversible et se manifesterait par un déréglage permanent et facile à découvrir.

Ces caractéristiques transféraient à la balance la qualité d'un « juge impartial » auquel chacun pouvait se fier même si l'instrument n'avait pas été contrôlé depuis un certain temps.

L'avènement de l'électronique a apporté bien des changements à cette situation. Alors que les balances devenaient plus sensibles, parfois plus précises, plus rapides et plus complexes dans leurs fonctions, leur construction et leur principe de fonctionnement devenaient simultanément plus complexes. Il est devenu difficile de faire des prédictions sur le maintien de leur qualité d' « impartialité » dans l'avenir, plus particulièrement dans le laps de temps séparant une inspection de la suivante.

Comme les pannes en électronique sont souvent de nature intermittente, il est aussi devenu très difficile de s'assurer qu'elles seront décelées lors de l'inspection suivante.

Pour remédier à cela, on a développé deux « philosophies » bien connues : la première préconise une qualité telle de construction qu'une panne puisse être considérée comme « très improbable ». La seconde se base sur l'emploi de fonctions ou de données redondantes de manière à pouvoir déceler les erreurs de premier ordre par corrélation des fonctions identiques ou parallèles.

Il faut faire remarquer ici déjà qu'aucune de ces deux idées ne peut être entièrement réalisée dans le sens strict du raisonnement théorique. Voyons les différents aspects de ces deux systèmes.

## Système redondant

L'objection la plus souvent formulée à l'encontre de cette méthode n'est pas fondée. Il n'est pas nécessaire en effet de doubler toute la chaîne de mesurage. Si cette solution est néanmoins très souvent retenue, c'est qu'elle permet de construire des systèmes ayant une réserve de fonctionnement en cas de panne d'un élément (pensons au co-pilote dans un avion). Mais si nous nous contentons de déceler un défaut sans vouloir le corriger des moyens bien moins coûteux peuvent suffir, comme par exemple des canaux de rétroaction ou des transmissions numériques à contrôle de parité. Si nous voulions corriger ou éliminer un défaut, il faudrait dépasser le dédoublement car on devrait prévoir un système à décision par majorité pour éliminer le canal en panne.

En revanche, il est beaucoup plus malaisé de trouver une réponse à une autre objection qui, heureusement, n'est pas souvent présentée. En langage intuitif, on pourrait la formuler à peu près comme ceci : « il y a forcément un élément de décision qui donne le signal d'acceptation du résultat de mesurage. Mais alors quel est l'élément qui le surveille ? » Cette réflexion nous fait entrer dans un cercle vicieux logique. Je pense, sans pouvoir en donner une preuve irréfutable, que cette objection là est de nature fondamentale. Dans cet ordre d'idées, les mathématiciens connaissent dans les systèmes axiomatiques finis des théorèmes qui semblent conduire dans la même direction. La solution de ce dilemme est d'admettre un élément non surveillé. Cela signifie que sa nature et sa construction doivent nous permettre d'ad mettre de ne pas prendre en considération une défaillance possible. On pourrait par exemple décider que tout élément mécanique à mouvement guidé et contraint atteint la sécurité requise : il ne peut en effet que se casser et cela, c'est définitif.

En généralisant cette idée, on peut aboutir à la notion d'accepter tout élément de surveillance qui ne peut émettre le signal d'acceptation que s'il est en parfait état.

Une troisième objection concerne les transmissions de signaux analogiques, émis dans la plupart des cas par des transducteurs ou des capteurs de forces. Les sorties ne peuvent alors pas être surveillées par les moyens bien connus utilisés pour les informations numériques. Mais cela n'implique heureusement pas qu'il n'y a pas d'autre solution. Pour la trouver, il faut prendre deux faits en considération. D'abord,

nous ne voulons éliminer que les suites des défaillances de premier ordre qui peuvent avoir plusieurs effets mais qui n'ont qu'une cause. Ensuite les éléments qui nous intéressent, transducteurs ou capteurs, sont généralement linéaires.

Si l'on contrôle que le signal émis est correct pour trois valeurs fixes de la grandeur, valeur zéro, maximale et médiane par exemple, il est pratiquement presque impossible que cette condition soit réalisée sans que l'élément en question fonctionne correctement sur toute l'étendue de mesurage.

## Système assurance de qualité

Comme je ne suis pas convaincu par cette méthode, il faut considérer mon argumentation d'un œil critique. Une décision a priori sur le comportement d'un instrument « d'arbitrage » pourrait s'appuyer sur des données statistiques concernant la distribution de fréquence de ses défaillances. Si l'on veut suivre cette voie, il faut alors considérer au moins deux groupes de défaillances : celles qui peuvent être décelées directement et qui sont de ce fait sans importance et celles qui pourraient induire en erreur l'utilisateur de l'instrument.

La distribution des défaillances peut être déterminée à partir d'essais effectués sur les systèmes complets en question. Dans ce cas, il faut mettre à l'épreuve plusieurs systèmes car nous chercherons un temps moyen avant défaillance et, en plus, certaines informations sur ses variations (sur la dispersion de cette valeur).

Si nous voulons nous faire une idée sur une durée en service de 4 ans à 2.000 heures par an, nous devrons probablement mettre chaque instrument à l'essai jour et nuit pendant une année. Il va de soi que nous pourrions chercher à accélérer le vieillissement en créant des conditions d'environnement spéciales; mais là, nous entrons dans le domaine des hypothèses. Nous en créons d'ailleurs aussi en définissant un « usage normal ». Et nous nous fions encore à des hypothèses quand nous admettons que les instruments mis à l'épreuve sont représentatifs de la totalité de la production future.

Mais on peut aussi estimer le temps moyen avant défaillance sur la base de la fiabilité de chacun des composants utilisés. Ces composants doivent avoir chacun une très longue durée de vie moyenne, il est ainsi rarement possible au fabricant de l'instrument de l'apprécier lui-même. Il se servira des informations de son fournisseur. Puisque probablement il ne voudra considérer que les défaillances « graves », il devra faire une analyse des effets possibles pour chacune. Le fonctionnaire qui devra donner l'approbation officielle devra apprécier la documentation relative à toute cette analyse. Ce travail risque d'être d'une importance égale à l'évaluation théorique d'un système redondant. Il n'y a pas de profit du point de vue effort.

La détermination de la fiabilité est une discipline reconnue particulièrement dans les domaines de la fabrication en grandes séries (par exemple les voitures automobiles) et de la construction d'éléments de grande importance (comme par exemple les avions). Mais même dans le domaine de l'aviation on la met en œuvre surtout pour l'évaluation de pièces qui ne peuvent pas être protégées par redondance, comme par exemple un fuselage. Pour la transmission de commandes, le mouvement des gouvernails, pour l'élaboration des éléments nautiques, pour la navigation, pour le pilotage automatique et même pour le pilote humain, on préfère la redondance dès qu'on est utilisateur ou responsable de l'engin.

Il me semble significatif qu'à une discussion d'un groupe de travail OIML sur ce sujet, des partisans « de la qualité » aient refusé d'employer des termes bien définis comme par exemple fiabilité ou « mean time before failure » pour ce qu'ils entendaient réglementer. Mais que fera un métrologiste au service d'une législation préventive face à des termes mal définis ? Il est responsable de la décision d'accepter ou de rejeter un instrument et il doit baser cette décision sur un jugement de valeur du genre : l'instrument conviendra-t-il pour l'usage prévu et fonctionnera-t-il correctement pendant le laps de temps prescrit ?

Pour le fabricant, la situation est différente. Son intention est de fabriquer un nombre considérable d'instruments pendant un laps de temps assez long. Pour sa propre information, il devrait et très probablement il devra faire des essais de fiabilité qu'il est d'ailleurs parfaitement à même de faire. Disposant ensuite de toutes ces informations, il sera pour le moins étonné de constater que des services officiels ne sont pas prêts à lui faire confiance sans autre procédure. Mais moi, fonctionnaire, comment ferais-je la distinction entre des fabricants dignes de confiance et les autres ? Tout au plus, pourrais-je faire confiance à la garantie qu'un fabricant a l'intention de donner pour son produit. L'acheteur d'une balance demandera certainement de pouvoir s'en servir pendant 5 ou même 10 ans (certains vont même plus loin). Où est le fabricant qui serait assez sûr de la qualité de son produit pour le garantir pendant tout ce laps de temps ?

## Conclusions

Voyons de plus près les différences entre un système répressif et un système préventif : Dans un système répressif, le gouvernement ne prend pas la responsabilité des instruments vendus. Il peut donner des directives au sujet de la qualité, et probablement le fera-t-il dans une certaine mesure. Mais normalement, il n'ira pas plus loin. Pour sa part, l'utilisateur est responsable de l'exactitude des mesurages et il lui est souvent possible de demander des dommages au fabricant de l'instrument qui serait à l'origine d'erreurs.

Dans cette situation, le fabricant aura grand intérêt à garder sa bonne renommée. Mais ce sera lui qui décidera de quelle façon faire et il choisira certainement des moyens qui lui sont familiers et qui se trouvent déjà à sa disposition dans son travail. Ainsi, il n'est pas étonnant qu'il pense au contrôle et à l'amélioration de la qualité ; son objectif est de fournir un bon produit. Les difficultés qui surgissent en suivant ce chemin ne se rencontrent qu'au fur et à mesure. On peut essayer d'imaginer les questions auxquelles un fabricant aurait à répondre s'il devait témoigner devant un tribunal sur l'exactitude d'un de ses produits en usage depuis un certain temps et peut-être détruit et qu'il ne lui a pas été possible d'examiner.

La question-clé qui se pose lors de l'approbation d'un instrument dans un système juridique préventif est précisément celle de décider si l'instrument fonctionnera correctement dans un certain avenir sans surveillance.

Si cette décision doit se baser sur des probabilités, celles-ci devront être bien près de 100 %, car elles devront remplir la condition mal définie de « au-delà d'un doute raisonnable ». Une telle façon de faire n'est certes pas exclue, on lui trouve des parallèles par exemple dans les certificats de sécurité des avions, mais la procédure est difficile et chère. Pour cette raison, il semble plus judicieux d'utiliser le concept de la redondance et de la certitude logique. Ce sont des concepts dont la réalisation est plus aisée à démontrer et qui permettent mieux d'apporter la preuve formelle de la sécurité métrologique.

<div align="center">

# TECHNICAL SURVEILLANCE of ROULETTE-CYLINDERS

</div>

par R. MUIJLWIJK Van Swinden Laboratorium van het IJkwezen Delft, NL

![](page=22,bbox=[321, 852, 1549, 1674])

RESUME — Les machines de jeux de hasard sont réglementées dans un certain nombre de pays mais les moyens pour leur vérification technique font souvent défaut.

L'article ci-dessous montre comment aux Pays-Bas le service national de métrologie est arrivé à déterminer les exigences techniques et à développer des moyens de vérification pour des jeux de roulette.

SUMMARY — Games involving money are subject to regulations in a certain number of countries, however, means for technical verification of game machines are missing in most cases.

The following paper shows how in the Netherlands the national metrology service has developed requirements and means for technical verification of roulette cylinders.

## Introduction

In 1976, the National Service of Metrology of the Netherlands was given the task of surveillance of the technical aspects of games of chance in casinos affiliated to the national foundation for casino games (in Dutch : Nationale Stichting Casinospelen, NSC). This task is carried out under the terms of the Games of Chance Act.

Since casinos have existed in other countries for a long time, investigations were carried out in some of these, with a view to make use of the experience gained there. This did not work out, however, because no technical surveillance was carried out anywhere on behalf of the authorities.

As a result, an answer to the questions :

— what properties should a good roulette cylinder have ?

— how can one check on these properties ?

had to be found by starting right from the beginning.

In this paper a survey is given of the gradual establishment of the requirements. The development of suitable measuring tools for which interest has already been shown by casino organizations in Austria and Germany is also described in brief.

## The influence of imperfections of a roulette on the results of the game

The roulette game goes a proper course if the probability of a certain result is within close limits equal to that for each of the other 36 possible results. The result is determined by mechanical means.

It is, therefore, important to establish the admissible tolerances for the accuracy of construction, in other words: which errors in construction may be tolerated without violation of the objective in view?

To this end it must be investigated which influence certain deviations from an otherwise perfect cylinder have on the results.

Variations in the width of partitions have the greatest influence. Once it has been determined which variation in width of the partitions is admissible, other requirements, viz. the maximum tolerable variation in height of the separators and the deviation from perfect balance, can be established easily. By introducing an imperfection, it can be traced on the one hand whether the change can be demonstrated from a statistical analysis of the results of the game, and on the other hand one is enabled to look into the chances of winning and in association into the time one can continue playing a certain amount of money, using a certain system of play.

## Statistical analysis of the results of a game.

If 37 n results are gathered using a perfect cylinder, each individual result will occur about n times. With large numbers, the occurrence of each possible result will be between n-2 $ \sqrt{n} $ and n+ $ 2\sqrt{n} $ with only a small chance for exceptions.

Some examples :

For n=25 (total numbers of results 925; about four days' play), the occurrence of each possible result will normally vary between 25-10=15 and 25+10=35. For n=10000 (the results of about 5 years' play) the occurrence will vary between 10000-200=9800 and 10000+200=10200. Hence a factor 1.04 with normal distribution between highest and lowest number.

If we imagine an otherwise perfect roulette cylinder to have one partition of 1 % greater width than all the others, how many gaming results would we need to be able to pin-point the wider partition positively, using the results ? The answer is : so many as is necessary for 1.01n $ - 2\sqrt{n} $ to be more the n+ $ 2\sqrt{n} $ , i.e. for 0.01n to be more than $ 4\sqrt{n} $ . This implies that n must be more than 160000, which in turn means that only after gaming for 80 years, collecting the results, the

cylinder remaining as at the start, the particular partition could be positively identified. If the larger partition is imagined to be 2 % different in width from the others it would still take no less than 20 years to find the wider partition from examination of the results. Considering the fact that a compartment 2 % too wide can be discerned with the naked eye with not too much difficulty and that technically it is very well possible to remain within these limits in constructing a cylinder, it will be evident that statistics on results cannot be used to provide a criterium when drawing up requirements.

## Time of play approach

If two players play with the same amount of money, using the same pattern, the one favouring for example the number 17 and the other the number 29, then the period they can play until all the money will have gone to the bank should only differ within reasonable limits.

Assuming the roulette cylinder being perfect the odds in favour of the casino amount to 2.7 % when numbers or combinations of numbers are used, and 1.4 % with "single chances " (red or black, even or uneven, high or low).

One partition of a width 1 % in excess of the average reduces the chance of losing for a player playing that number by 1 % to 1.7 %, and the average duration of play for that number is increased by more than 50 %. Compared with playing a partition 1 % narrower than the average, the ratio of duration of play is even more than two to one.

Nevertheless, the differences in duration of play, also with an otherwise perfect cylinder, are still fairly normal as individual variations around the average. With one partition, 2% wider and one 2% narrower, the average ratio of play in both cases is almost 7:1. Even this variation is possible with a perfect cylinder, but so remote that it is no longer acceptable as a variation caused by construction imperfections. It was therefore preferred to limit the variation in width of the partitions to plus or minus 1% of the average. This choice was also influenced by the fact that existing roulette cylinders appeared to meet this requirement, provided special care is taken in mounting the separators.

## The technical requirements

For the width of the partitions 1 % in plus and 1 % in minus means a total variation of 0.5 mm. For the height of the separators also a variation of 0.5 mm is acceptable. This requirement is derived from an estimated average trajectory of a roulette ball towards the partition; the height of the partitions also plays a role in their apparent width as seen from a ball approaching at an angle.

The deviation from perfect balance is only important if the rotating part of the cylinder is not horizontal. Taking into account the admissible error in the width of the partitions the requirement regarding balance was defined so as to make levelling "by eye quite sufficient (from experience it is known that the remaining deviation from the horizontal position will be within 1 degree of arc). According to the position of the partitions the deviation from perfect balance may be 150 g. All cylinders examined so far were well within this limit. This proves that there is no reason whatsoever for cumbersome adjustment of roulette cylinders to a horizontal position with the use of a water-level. Apart from quantitative requirements there are some qualitative requirements with respect to the felt in the partitions and the flatness of the numbers ring. The maximum height of the moving part of the cylinder with respect to the housing is limited to prevent a ball from getting stuck in the rim. Finally provisions were made for the necessary sealing of roulette cylinders.

![](page=25,bbox=[780, 345, 1286, 1202])

<div align="center">

Figure 1

</div>

![](page=25,bbox=[421, 1271, 1667, 2447])

<div align="center">

Figure 2

</div>

## The measuring tools ( $ ^{*} $ )

In order to take the necessary measurements on roulette cylinders, the department for Mechanical Measurements of the Van Swinden Laboratorium developed special measuring tools.

To measure the width of the partitions use is made of a simple dial gauge and a specially designed part with small steel balls pressed into it which enable the positioning of the dial gauge in the partitions in a well-defined way. The readings from repeated measurements of the same partition differ only by a few hundredths of a millimeter. A sketch of the measuring tool is given in figure 1.

The height of the separators, any obliqueness of the axis of the moving part with respect to the housing and the flatness of the numbers ring are checked with a measuring bridge (see figure 2), mounted in the centre of the cylinder. Two dial gauges are placed symmetrically in relation to the axis in order to eliminate the influence of any obliqueness of the axis of the measuring bridge itself, since the sum of the readings of the dial gauges does not depend on small deviations in the direction of this axis.

In the measuring bridge are a radial bearing and a normal ball bearing in the top and one normal ball bearing in the lower part. This appears somewhat overdone for a light construction like this but it also serves as an example of a better bearing than is usually applied in roulettes. The added radial bearing takes up the vertical force in a much more natural way than the usual two axial ball bearings.

## Conclusion

The technical surveillance of roulette-cylinders is now carried out in a rather regular routine. This is done in good cooperation with the casino technicians. This is important because it is those who carry out the daily maintenance. The exchange of experience is of interest to both sides. And ultimately also in the interest of the players.

<div align="center">

# TRAVAUX des SECRÉTARIATS OIML en 1981

</div>

Comme cela a été fait l'année précédente, nous essayons ci-dessous de résumer très brièvement les travaux des Secrétariats Pilotes et Rapporteurs d'après les projets et avant-projets qui ont été reçus par le BIML.

## SP 1 - Terminologie

La première rencontre internationale groupant des représentants du BIPM, de la CEI, de l'ISO et de l'OIML, a eu lieu du 1er au 3 février 1982 au BIPM afin de discuter le premier projet de Vocabulaire International de Métrologie, commun aux organisations concernées.

Le Vocabulaire de Métrologie Légale (VML) a fait l'objet en 1981 d'un troisième avant-projet de révision discuté lors de la réunion tenue les 4 et 5 février 1982 au BIML.

## SP 4 - Mesurage des longueurs, surfaces, angles

Les travaux du SP 4-Sr 4 ont abouti à un projet de Document International soumis pour examen au Secrétariat Pilote et intitulé « Schéma de hiérarchie des instruments de mesurage des longueurs ».

D'autre part, le projet du SP 4-Sr 5 « Schéma de hiérarchie des instruments destinés au mesurage de l'angle » a été accepté par le Secrétariat Pilote et sera prochainement envoyé pour vote aux membres du CIML.

## SP 5 - Mesurage des volumes de liquides

Le Secrétariat-rapporteur SP 5-Sr 4 a élaboré un premier avant-projet intitulé « Seringues médicales non réutilisables ».

Il faut signaler la reprise d'activité, par une réunion à Sinaia, Roumanie, des secrétariats SP 5-Sr 8, Sr 9 et Sr 10 concernant les réservoirs de stockage et de transport principalement des hydrocarbures.

Les compteurs d'eau chaude ont fait l'objet d'un deuxième avant-projet présenté lors de la réunion à Alexandria, USA, en octobre 1981, de la part du SP 5-Sr 16. Ce secrétariat a également terminé le premier projet sur l'évaluation des étalons de débit et des dispositifs utilisés pour procéder à l'essai des compteurs d'eau.

Le travail du SP 5-Sr 20 a débuté par un premier avant-projet concernant les méthodes et dispositifs de vérification de mesurage de liquides.

## SP 7 - Mesurage des masses

Une première réunion du SP 7-Sr 2 a eu lieu au BIML en mars 1981 pour discuter un avant-projet sur les dispositifs électroniques utilisés dans les instruments de pesage. Le deuxième avant-projet fera l'objet d'une réunion au BIML en mai 1982.

Les travaux des SP 7-Sr 4 (pesage non automatique) et SP 7-Sr 5 (pesage automatique) ont également fait l'objet de réunions à Paris en mars 1981. On peut noter que lors de la réunion du Sr 4 concernant la révision de la RI 3, il ne s'est pas dégagé de consensus concernant une réforme profonde de cette Recommandation.

Le Secrétariat-rapporteur SP 7-Sr 8 a fait circuler parmi ses collaborateurs son troisième avant-projet concernant les cellules de pesée.

## SP 11 - Mesurage des pressions

Le Secrétariat-rapporteur SP 11-Sr 3 a établi un troisième avant-projet concernant les manomètres à piston.

## SP 12 - Mesurage des températures

Pour la réunion à Léningrad en mars 1981, le SP 12-Sr 3 a présenté une nouvelle version entièrement modifiée du projet sur les thermomètres électriques à résistance de platine, de cuivre et de nickel. Ce texte est en accord avec les derniers travaux de la CEI.

La révision de la RI 18 sur les pyromètres visuels, à filament disparaissant, fut également discutée à cette réunion. Ce travail est actuellement au stade de deuxième avant-projet.

## SP 14 - Acoustique et vibrations

Les problèmes de pollution sonore furent brièvement touchés lors de la réunion du SP 17 au BIML en avril 1981. Il a été envisagé de référer les problèmes concernant les instruments de mesure dans ce domaine entièrement au SP 14.

Le Secrétariat-rapporteur SP 14-Sr 1 a proposé d'adopter la norme CEI pour les sonomètres et un projet dans ce sens a été soumis au Secrétariat Pilote qui s'est réuni à Braunschweig en février 1982.

## SP 15 - Manifestations optiques de la lumière

Le Secrétariat-rapporteur a terminé et diffusé à ses collaborateurs un troisième avant-projet sur les dioptrimètres.

## SP 17 - Mesurage des pollutions

La première réunion des Secrétariats Pilote et Rapporteurs a eu lieu au BIML en avril 1981 en présence des représentants de l'ISO et de l'IUPAC. Des programmes plus spécifiques de travail pour chaque Secrétariat-rapporteur seront établis à la suite de cette réunion.

## SP 18 - Mesurage des caractéristiques des produits alimentaires

De la réunion qui a eu lieu en octobre 1981 à Paris du Secrétariat-rapporteur SP 18-Sr 1 a résulté un quatrième avant-projet diffusé aux collaborateurs et qui a pour titre « Humidimètres pour grains de céréales et graines oléagineuses ». Cet avant-projet contient également un projet de révision de RI 8.

## SP 19 - Mesurage des caractéristiques des matériaux

Une réunion des collaborateurs du SP 19-Sr 2 « machines d'essai des matériaux » a eu lieu au BIML en février 1981. Depuis cette réunion le Secrétariat a diffusé les avant-projets suivants qui feront l'objet d'une autre réunion au BIML en mai 1982 :

— Spécifications générales pour machines d'essai 2e avant-projet

- Spécifications pour les machines d'essai de traction et de comp 2e avant-projet pression

- Spécifications pour les instruments mesureurs de force utilisés 1er avant-projet pour vérifier les indicateurs de charge des machines d'essai.

Le Secrétariat-rapporteur SP 19-Sr 5 a terminé le premier projet sur les jauges de contrainte qui a été soumis pour examen par le Secrétariat Pilote.

Un premier avant-projet du SP-19-Sr 6 concernant la terminologie des essais de dureté a été diffusé aux collaborateurs et fera prochainement l'objet d'un deuxième avant-projet tenant compte des observations déjà reçues.

## SP 21 - Normalisation des caractéristiques métrologiques des moyens de mesurage

Lors de la réunion prévue à Souchoumi, URSS, en avril 1982 seront discutés les troisièmes avant-projets suivants qui ont été diffusés par les Secrétariats-rapporteurs à leurs collaborateurs durant 1981 :

SP 21-Sr 1 « Instruments de mesurage. Caractéristiques métrologiques générales à normaliser »

SP 21-Sr 2 « Instruments de mesurage. Caractéristiques métrologiques des propriétés dynamiques à normaliser »

SP 21-Sr 4 « Principes de la réglementation des caractéristiques métrologiques des systèmes de mesurage  ».

## SP 22 - Principes du contrôle métrologique

Après une réunion à Bratislava en mai 1981, le Secrétariat-rapporteur SP 22-Sr 5 a diffusé un troisième avant-projet à ses collaborateurs concernant les principes de la surveillance métrologique.

## SP 23 - Méthodes et moyens d'attestation des dispositifs de vérification

Les travaux suivants discutés lors de la réunion à Bratislava sont arrivés au stade de projets de Documents Internationaux :

SP 23-Sr 3 « Documentation des étalons et des dispositifs d'étalonnage »

SP 23-Sr 5 « Principes pour l'établissement des schémas de hiérarchie des instruments de mesure ».

D'autre part, le Secrétariat-rapporteur SP 23-Sr 2 a diffusé à ses collaborateurs un troisième avant-projet concernant les principes de reconnaissance officielle d'utilisation et de conservation des étalons.

## SP 25 - Pays en voie de développement

Les travaux du SP 25-Sr 2 concernant la structure et le fonctionnement d'un Service national de métrologie légale ont été terminés et publiés dans le Bulletin de l'OIML $ N^{\circ} $ 84, septembre 1981.

Un deuxième avant-projet pour un Document International contenant des listes de moyens de vérification destinés à équiper les services nationaux de métrologie a été diffusé aux collaborateurs du SP 25-Sr 3.

## SP 26 - Instruments de mesurage utilisés dans le domaine de la santé publique

Les instruments de mesure bio-électriques selon les travaux du SP 26-Sr 4 ont donné lieu à une réunion au BIML en mai 1981. Le troisième avant-projet sur les électrocardiographes et le deuxième avant-projet sur les électro-encéphalographes, discutés lors de la réunion ont depuis fait l'objet de quelques légères modifications.

Le Secrétariat-rapporteur envisage de considérer comme définitifs les textes ainsi révisés et de les soumettre au Secrétariat Pilote en tant que projets.

## SP 27 - Matériaux de référence

Une réunion des Secrétariats Pilote et rapporteurs a eu lieu à Bakou en avril 1981, ce qui a permis un examen des projets précédemment diffusés ainsi que des comparaisons avec le travail effectué dans le même domaine par le comité REMCO de l'ISO.

## SP 30 - Mesures physico-chimiques

Une réunion des Secrétariats-rapporteurs prévue pour octobre 1981 a dû être annulée à cause d'un nombre insuffisant de participants. Comme plusieurs projets et avant-projets concernant en particulier la conductométrie, l'hygrométrie et la viscosimétrie sont ainsi en attente, on peut espérer qu'une solution pour l'avancement des travaux sera trouvée en 1982.

## SP 31 - Enseignement de la métrologie

Un deuxième avant-projet de Document International concernant les qualifications des Ingénieurs métrologistes a été diffusé aux collaborateurs du SP 31-Sr 1.

A la demande du SP31, le BIML a entrepris une enquête sur les systèmes nationaux de formation des métrologistes de tous niveaux (programmes d'étude, matériel d'enseignement, organisation...).

<div align="center">

# BROCHURES D'INFORMATION EDITEES PAR LE B.I.M.L.

</div>

Les brochures suivantes ayant un caractère purement d'information ont été élaborées et diffusées par le BIML :

— Equipment d'un Service National de Métrologie - Suggestions du BIML, nouvelle édition française, 15 sept. 1981

Fournisseurs d'équipement de vérification, édition bilingue français-anglais, août 1981

- The metrology of hardness scales, Bibliography, (la métrologie des échelles de dureté, en coopération avec IMEKO), août 1981

— Projet de bibliographie sur la vérification du contenu des préemballages, édition bilingue français-anglais, 25 juin 1981

— Equipment mobile pour la vérification des ponts-bascules routiers. édition bilingue français-anglais, 12 janvier 1982

<div align="center">

# WORK of the OIML SECRETARIATS in 1981

</div>

As it was done last year we are below attempting to give an account of the work of OIML Pilot and Reporting Secretariats on the basis of drafts and preliminary drafts received by the BIML.

## SP 1 - Terminology

The International Metrology Vocabulary (VIM) intended to be common to BIPM, IEC, ISO and OIML was the subject of a first meeting of representatives of the organisations concerned at BIPM 1-3 February 1982.

The Vocabulary of Legal Metrology was the subject of a further meeting at BIML 4-5 February 1982 during which the third preliminary draft revision was discussed.

## SP 4 - Lengths, surfaces, angles

The work of SP 4-Sr 4 has resulted in a draft International Document " Hierarchy schemes for length measuring instruments " which is being studied by the Pilot Secretariat.

The SP 4-Sr 5 draft " Hierarchy schemes for angle measuring instruments " has already been approved by the Pilot Secretariat and will soon be sent out to all CIML members for voting and comments.

## SP 5 - Volume of liquids

The reporting secretariat SP 5-Sr 4 has elaborated a first preliminary draft concerning non-reusable medical syringes.

The work of SP 5-Sr 8, Sr 9 and Sr 10 dealing with tanks for storage and transport of hydrocarbon products, was restarted at a meeting in Sinaia, Romania.

Hot water meters the subject of a second preliminary draft by SP 5-Sr 16 was discussed during a meeting in Alexandria, USA in October 1981. This secretariat has also finalized the first draft on the evaluation of flow standards and facilities used for the testing of water meters.

The work of SP 5-Sr20 has started with the issue of a first preliminary draft concerning methods and devices for verification of measuring instruments for liquids.

## SP 7 - Measurement of mass

The first meeting of SP 7-Sr2 took place at BIML in March 1981 during which the first preliminary draft concerning electronic devices used in weighing machines was discussed. The second preliminary draft will be studied during a meeting at BIML in May 1982.

The work of SP 7-Sr 4 (non-automatic weighing machines) and SP 7-Sr 5 (automatic weighing machines) was the subject of meetings in Paris in March 1981. It should be noted that during the meeting of Sr 4 concerning the revision of the International Recommendation No 3 no consensus was obtained as to any radical changes of this Recommendation.

The reporting secretariat SP 7-Sr 8 has distributed to its collaborators the third preliminary project concerning load cells.

## SP 11 - Measurement of pressure

The reporting secretariat SP11-Sr3 has elaborated the third preliminary draft concerning piston pressure gauges.

## SP 12 - Measurement of temperature

For the meeting of SP12-Sr3 in Leningrad in March 1981 a completely revised version of the draft concerning metallic electrical resistance thermometers was distributed. The new draft is in agreement with the recent work of IEC.

The revision by SP 12-Sr 6 of RI 18 concerning optical pyrometers of the disappearing filament type was also discussed at that meeting. This work is now at the stage of a second preliminary draft.

## SP 14 - Acoustics and vibration

The problems of acoustic pollution were dealt with briefly during the meeting of SP 17 at BIML in April 1981. It was considered to refer the problems concerning measuring instruments in this field entirely to SP 14.

The reporting secretariat SP 14-Sr 1 has suggested to adopt the new IEC standard for sound level meters as an OIML recommendation and a draft drawn up accordingly was submitted to the Pilot Secretariat at its meeting in Braunschweig in February 1982.

## SP 15 - Optical manifestations of light

The reporting secretariat has finalized and distributed to its collaborators its third preliminary draft concerning dioptrimeters.

## SP 17 - Measurement of pollution

The first meeting of the pilot and reporting secretariats took place at BIML in April 1981 in the presence of delegates from ISO and IUPAC. As a result of this meeting more specific work programmes of the reporting secretariats will be established.

## SP 18 - Measurement of characteristics of food products

A fourth preliminary draft concerning moisture meters for cereal grains and oil seeds was prepared by SP 18-Sr1 as a result of a meeting in October 1981 in Paris. This preliminary draft contains also a revision of RI 8.

## SP 19 - Measurement of the characteristics of materials

A meeting of the collaborators of SP19-Sr2 took place at BIML in February 1981. Subsequent to this meeting the reporting secretariat has distributed the following preliminary drafts which will be discussed at BIML in May 1982:

- General specifications for materials testing machines 2nd preliminary draft

- Specifications for machines for tension and compression 2nd preliminary draft testing of materials

- Specifications for force measuring instruments used for 1st preliminary draft verifying the load indication of materials testing machines.

The reporting secretariat SP 19-Sr 5 has finalized the first draft concerning metallic strain gauges which was submitted to the pilot secretariat.

The reporting secretariat SP19-Sr6 has distributed to its collaborators the first preliminary draft concerning the terminology of hardness testing. This work will soon be the subject of a second preliminary draft taking into account the comments already received.

## SP 21 - Standardization of metrological characteristics of measuring instruments

The following third preliminary drafts which were distributed during 1981, will be discussed at a meeting in Souchoumi, USSR, in April 1982:

SP21-Sr1 " Measuring instruments. General metrological characteristics subject to standardization "

SP21-Sr2 " Measuring instruments. Metrological characteristics of dynamic properties subject to standardization "

SP21-Sr4 《 Metrological characteristics of measuring systems : Regulation principles 》

## SP 22 - Principles of metrological control

Following a meeting in Bratislava in May 1981, the reporting secretariat SP22- Sr 5 has distributed to its collaborators a third preliminary draft concerning the principles of metrological supervision.

## SP 23 - Methods and means for certification of verification devices

The following subjects discussed during the meeting in Bratislava have reached the stage of draft projects for International Documents:

SP 23-Sr 3 Documentation for standards and calibration devices

SP 23-Sr 5 " Principles for the establishment of hierarchy schemes for measuring instruments

In addition, the reporting secretariat SP 23-Sr 2 has distributed to its collaborators the third preliminary draft entitled " Principles concerning the official recognition, use and conservation of standards ].

## SP 25 - Developing countries

The work of SP25-Sr2 concerning the structure and function of a National Service of Legal Metrology was finalized and published in the OIML Bulletin No 84, September 1981.

The reporting secretariat SP25-Sr3 has distributed to its collaborators a second preliminary draft International Document containing lists of verification equipment required to equip the national metrology services.

## SP 26 - Measuring instruments used in the field of public health

Bioelectrical instruments according to the work of SP26-Sr4 were the subject of a meeting at BIML in May 1981. The third preliminary draft on electrocardiographs and the second preliminary draft on electroencephalographs which were discussed during this meeting have since been slightly modified. The reporting secretariat has proposed to consider the texts thus revised as definite and to submit them as drafts to the pilot secretariat.

## SP 27 - Reference materials

The pilot and reporting secretariats met at Bakou in April 1981. The drafts, previously distributed, were reviewed and compared with the work accomplished by the REMCO committee of ISO.

## SP 30 - Physico-chemical measurements

A meeting of reporting secretariats planned for October 1981 had to be cancelled because of insufficient support. Since several drafts and preliminary drafts concerning in particular conductivity, hygrometry and viscosimetry are therefore pending it is hoped that a solution for the advancement of this work will be found during 1982.

## SP 31 - Teaching of metrology

A second preliminary draft for an International Document concerning the required qualifications for metrology engineers was distributed to the collaborators by the reporting secretariat SP 31-Sr 1.

At the request of SP31 the BIML has undertaken an enquiry on the national systems of education and training of metrologists at all levels (study programmes, teaching aids, planning...).

<div align="center">

# INFORMATION BROCHURES PUBLISHED BY B.I.M.L.

</div>

The following brochures intended mainly as information material have been written and distributed by BIML

- Equipment of a National Metrology Service - Suggestions by BIML, new English edition, 15 September 1981

- Suppliers of verification equipment, bilingual French-English, August 1981

- The metrology of hardness scales - bibliography, (in cooperation with IMEKO), August 1981

- Draft bibliography on the verification of net quantity of prepacked goods, bilingual French-English, 25 June 1981

- Mobile equipment for the verification of road weighbridges, bilingual French- English, 12 January 1982

<div align="center">

# INFORMATIONS

</div>

## NOUVEL ETAT MEMBRE — NOUVEAU MEMBRE DU COMITE

Le Gouvernement du CANADA a déposé le 23 décembre 1981 auprès du Ministère Français des Relations Extérieures son instrument d'adhésion à l'OIML. Cette nouvelle adhésion, devenue effective le 23 janvier 1982, fait du CANADA le 47e Etat Membre de notre Institution.

Monsieur Richard KNAPP, Director of Legal Metrology (Consumer and Corporate Affairs), a été désigné pour représenter son Pays au Comité International de Métrologie Légale. Nous lui présentons nos meilleures salutations de bienvenue, et nous le remercions par avance de la collaboration qu'il voudra bien nous accorder.

C'est aussi pour nous l'heureuse occasion d'adresser nos très vifs remerciements à Monsieur J. QUIGLEY, ancien Directeur de la Métrologie Légale, appelé aujourd'hui à d'autres fonctions, dont le concours décisif a favorisé l'adhésion de son Pays à notre Organisation, ainsi qu'à Monsieur J. ARMSTRONG, qui a exercé les fonctions de Chief, Electricity and Gas Division (Consumer and Corporate Affairs).

## MEMBRES DU COMITE

Nos lecteurs partageront notre joie d'apprendre la nomination de Monsieur F. ROTTER qui vient d'être désigné Président du Bundesamt für Eich- und Vermessungswesen d'AUTRICHE.

Nous adressons à Monsieur ROTTER nos félicitations très sincères et nos remerciements chaleureux pour l'important travail dont il veut bien faire bénéficier l'Organisation en sa qualité de Membre de notre Comité International.

REPUBLIQUE DE COREE — Monsieur KIM Sung-Hwan représentera son Pays au Comité International de Métrologie Légale en remplacement de Monsieur SUH Tae-Huan. Nos salutations de bienvenue et nos remerciements vont à ces deux Personnalités.

## INFORMATION

## NEW MEMBER STATE — NEW COMMITTEE MEMBER

The Government of CANADA has deposited at the French Ministry of Foreign Affairs its Instrument of Accession to OIML on the 23 December 1981. This new accession, which became effective on the 23 January 1982, has made CANADA the 47th Member State of our Institution.

Mr Richard KNAPP, Director of Legal Metrology, Consumer and Corporate Affairs, was nominated as the representative of his country on the International Committee of Legal Metrology. We welcome him most sincerely and thank him in advance for his collaboration in the future.

At the same time, we are pleased to address our thanks to Mr J. QUIGLEY, former Director of Legal Metrology, who was transferred to other duties, and whose unfailing efforts have brought about the accession of his country to our Organization, as well as to Mr J. ARMSTRONG, who was in charge of the Electricity and Gas Division (Consumer and Corporate Affairs).

## COMMITTEE MEMBERS

Our readers will share our pleasure of learning that Mr F. ROTTER was nominated as Chairman of the Bundesamt für Eich-und Vermessungswesen of Austria.

We warmly congratulate Mr ROTTER and thank him for his untiring efforts for the benefit of our Organization as Member of our International Committee.

REPUBLIC OF KOREA Mr KIM Sung-Hwan will represent his country on the International Committee of Legal Metrology replacing Mr SUH Tae-Huan. We extend our welcome and our thanks to both of them.

## LIST OF NEW METROLOGY STANDARDS ISSUED BY CMEA

Nous avons publié dans le N° 83 du Bulletin de l'OIML une liste des normes métrologiques du Conseil d'Assistance Economique et Mutuelle (CMEA). Nous indiquons ci-dessous les titres en anglais des normes métrologiques parues depuis.

We have published in No.83 of the OIML Bulletin a list of metrology standards issued by the Council of Mutual Economic Assistance (CMEA). You will find below an additional list of metrology standards published during 1981.

ST CMEA 3067-81 Metrology. Deformation Reference pressure gauges and vacuum gauges. Technical requirements.

ST CMEA 3068-81 Metrology. Pressure gauges and vacuum gauges with contact devices. Verification methods.

ST CMEA 3069-81 Metrology. Pressure gauges. Remote reading vacuum pressure gauges. Verification methods.

ST CMEA 3071-81 Metrology. Direct current comparators. Verification methods.

ST CMEA 3070-81 Metrology. Recording pressure gauges, pressure vacuum gauges. Verification methods.

ST CMEA 3072-81 Metrology. Reference electrical counters. Verification methods.

ST CMEA 3074-81 Metrology. Pulse generators. Verification methods.

ST CMEA 3073-81 Metrology. Working electrical counters. Verification methods.

ST CMEA 3172-81 Recording electromeasuring instruments for direct conversion and their accessories. General technical requirements and test methods.

ST CMEA 3173-81 Devices for rotating machines vibration measurement. Technical requirements.

ST CMEA 3206-81 Electronic measuring instruments. General technical requirements.

ST CMEA 3138-81 Engineer's dial gauge with 0.01 mm division value. Technical requirements.

## REUNIONS

<table border="1"><tr><td></td><td>Groupes de travail</td><td>Dates</td><td>Lieux</td></tr><tr><td>SP21-Sr1</td><td>Caractéristiques métrologiques normalisées des instruments de mesure lors du mesure des quantités constantes dans le temps</td><td rowspan="3">19-27 avril 1982</td><td rowspan="3">SOUCHOUMI U.R.S.S.</td></tr><tr><td>SP21-Sr2</td><td>Caractéristiques métrologiques normalisées des instruments de mesure lors du mesure des quantités variables dans le temps</td></tr><tr><td>SP21-Sr4</td><td>Caractéristiques métrologiques normalisées des systèmes de mesure</td></tr><tr><td>SP19-Sr2</td><td>Machines d&#x27;essai des matériaux</td><td>11-14 mai 1982</td><td>BIML</td></tr><tr><td>SP7-Sr2</td><td>Mesurage des masses - généralités - dispositifs électroniques</td><td>17-19 mai 1982</td><td>BIML</td></tr><tr><td>SP26-Sr4</td><td>Instruments de mesure bioélectriques</td><td>24-28 mai 1982</td><td>ROSTOV U.R.S.S.</td></tr><tr><td>SP5-Sr1</td><td>Mesurage des volumes de liquides. Terminologie</td><td rowspan="3">8-10 sept. 1982 * (provisoire)</td><td rowspan="3">LONDRES ROYAUME-UNI</td></tr><tr><td>SP5-Sr2</td><td>Schémas de hiérarchie des étalons de volume</td></tr><tr><td>SP5-Sr3</td><td>Mesures de volumes de laboratoires</td></tr><tr><td>SP7-Sr4</td><td>Instruments de pesage à fonctionnement non automatique</td><td>13-15 sept. 1982</td><td>MUNICH REP. FED. D&#x27;ALLEMAGNE</td></tr><tr><td>SP7-Sr5</td><td>Instruments de pesage à fonctionnement automatique</td><td>16 et 17 sept. 1982</td><td>MUNICH REP. FED. D&#x27;ALLEMAGNE</td></tr><tr><td>SP7</td><td>Mesurage des masses</td><td>17 sept. 1982</td><td>MUNICH REP. FED. D&#x27;ALLEMAGNE</td></tr></table>

* Eventuellement reportée à début 1983 pour réunion conjointe avec SP 5 - Sr 20.

<table border="1"><tr><td>SP4</td><td>Mesurage des longueurs, surfaces, angles</td><td></td><td></td></tr><tr><td>SP4-Sr2</td><td>Mesures matérielisées de longueur</td><td>12-15 oct.1982</td><td>BIML</td></tr><tr><td>SP4-Sr3</td><td>Appareils de mesurage de la longueur des tissus, cables et fils</td><td></td><td></td></tr><tr><td>SP6</td><td>Mesurage des volumes de gaz</td><td>oct.1982(provisoire)</td><td>PARISFRANCE</td></tr><tr><td>SP5-Sr8</td><td>Réservoirs de stockage à pression atmosphérique ou sous pression(bacs cylindriques verticaux ou horizontaux, sphères, sphéroïdes)</td><td>sept.-oct.1982(provisoire)</td><td>ROUMANIE</td></tr><tr><td>SP5-Sr9</td><td>Camions et wagons citernes à pression atmosphérique ou sous pression</td><td></td><td></td></tr><tr><td>SP16-Sr2</td><td>Laboratoires secondaires d&#x27;étalonnage en dosimétrie</td><td>oct.-nov.1982(provisoire)</td><td>BUDAPESTHONGRIE</td></tr></table>

<table border="1"><tr><td>Conseil de Développement</td><td>22-23 mars 1982</td><td>BIML</td></tr><tr><td>Dix-huitième Réunion du Comité International de Métrologie Légale</td><td>24-26 mars 1982</td><td>PARIS FRANCE</td></tr><tr><td>Groupe de travail mixte ISO-CEI-BIPM-OIML:Vocabulaire International de Métrologie</td><td>16-18 mars 1982</td><td>ISO GENEVE</td></tr><tr><td>Groupe de travail mixte ISO-CEI-BIPM-OIML:Vocabulaire International de Métrologie</td><td>2-4 juin 1982(provisoire)</td><td>PARIS ou GENEVE</td></tr></table>

<div align="center">

# CENTRE DE DOCUMENTATION

</div>

## Documents reçus au cours du 1er trimestre 1982

BUREAU INTERNATIONAL DES POIDS ET MESURES — BIPM

Rapport BIPM - 81/8 : Formule pour la détermination de la masse volumique de l'air humide (1981)

ORGANISATION INTERNATIONALE DE NORMALISATION — ISO

ISO Guide 30 : Termes et définitions utilisés en rapport avec les matériaux de référence (fr. et angl.)

Rapport d'Activité de l'ISO, 1980-1981 (fr. et ang.)

Recueil de normes ISO 3 (2e édition - 1981) (fr. et ang.)

ISO Normes (en franç. et en angl.) :

ISO 3014-1981 : Carburants d'aviation pour moteurs à réaction - Détermination du point de fumée

ISO 5377-1981 : Produits d'hydrolyse de l'amidon ou de la fécule - Détermination du pouvoir réducteur et de l'équivalent en dextrose - Méthode Lane et Eynon à titre constant

ISO 6246-1981 : Produits pétroliers - Essence automobile et essence aviation - Détermination des gommes actuelles - Méthode d'évaporation au jet

ISO 6569-1981 : Gaz naturel - Analyse rapide par chromatographie en phase gazeuse

COMMUNAUTE ECONOMIQUE EUROPEENNE — CEE

Recapitulatory List of Directives and Proposals for Directives relating to the elimination of Technical Barriers to trade for Industrial Products [August 1979]

COMMONWEALTH SCIENCE COUNCIL CSC

Commonwealth Secretariat

CSC (80) SQC-7 : African Programme on Standardization and Quality Control Report on the First Review Meeting, 23-30 April 1980, Nicosia, Cyprus

CSC (80) SQC-8 : African Programme on Standardization and Quality Control Report of Seminars on Food Standards and Integrated Approach to Standardization, Cyprus, 1980

## ARAB ORGANIZATION FOR STANDARDIZATION AND METROLOGY ASMO

Traduction en langue arabe de :

OIML RI 35 : Material measures of length

OIML RI 52 : Hexagonal weights, ordinary accuracy class, from 100 g to 50 kg

Draft Dictionary of Legal metrology

OIML DI 2 : Legal units of measurement

INTERNATIONAL MEASUREMENT CONFEDERATION IMEKO

Technical Committee TC3, Measurement of force and mass

Weighing Technology (edited by the Polish Federation of Engineering Associations Krakow, Sept. 1980)

## ORGANISATION REGIONALE AFRICAINE DE NORMALISATION — ORAN

Renseignements sur les activités des Etats membres dans le domaine de la normalisation, 1981

## REPUBLIQUE FEDERALE D'ALLEMAGNE

Physikalisch- Technische Bundesanstalt PTB-Bericht : PTB-ME-32 (August 1981) Hardness standard Machines of National Institutes for Metrology (by F. Petik and W. Weiler)

## ETATS-UNIS D'AMERIQUE

National Conference of Standards Laboratories Guidelines for presenting adjunct training courses (by J.T. Martin, Sept. 1980) NCSL Newsletter depuis le N° 3 Vol. 21 Sept. 1981

Health Industry Manufacturers Association - HIMA

1980 Annual Report

Catalogue of Publications, May 1981

## ARGENTINE

Instituto Nacional de Tecnologia Industrial - INTI

Procesamiento optico de informacion - Fundamentos fisico-matematicos de las

tecnicas de filtrado espacial coherente [O.J. Nejamis, 1980]

La luz como una verdadera magnitud visual : principios de su medicion, 1981

(Traduccion de la Publ. CIE N° 41 (TC-1.4) 1978)

## BELGIQUE

Réglementation

Arrêté royal du 9-9-1981 relatif aux trieuses pondérales automatiques de contrôle

et de classement + règlement et erratum

## CUBA

Centro de Informatica Aplicada a la Normalizacion - CINAN

Nouveaux périodiques :

Normas cubanas y extranjeras N° 11, 1981

Informaciones sobre NMCC N° 1 Janv. 1981

## DANEMARK

Dansk Institut for Provning og Justering Takster pr. 1. Januar 1982

## FRANCE

Réglementation

Circulaire n° 81.1.01.640.0.0 du 16-6-1981 : Sous-ensembles électroniques de mesure et d'asservissement pour doseuses pondérales

Arrêté du 3-7-1981 relatif aux Directions interdépartementales de l'Industrie

Décret n° 81-839 du 27-8-1981 : Statut des Ingénieurs des travaux métrologiques

## ROYAUME-UNI DE GRANDE-BRETAGNE ET D'IRLANDE DU NORD

The Institute of Trading Standards Administration

The Centenial Review - A history of the first 100 years of the Institute, 1881-1981

(by D. Johnson and M. Stevenson)

Report of the Joint Industry/Departmental Working Group : Pattern Examination of Weighing and Measuring Equipment (London, 1981)

Metrology, Quality Assurance, Safety and Standards Division

Statutory Instruments 1981 No. 1727 : Weights and Measures - The Measuring Instruments (EEC Requirements) (Amendment) Regulations 1981

SI 1981 N° 1825 : Fees and Charges - The Measuring Instruments (EEC Pattern Approval Requirements) (Fees) (No. 2) Regulations 1981

Tyne and Wear Country Council

Annual Report 1980-81 (Report of the director of Consumer Services for the year ended, 31st March 1981)

British Standards Institution

BS 5179 : Part 1 : 1974 Guide to the operation and evaluation of quality assurance systems - Final inspection system

Part 2 : 1974 Comprehensive inspection system

Part 3 : 1974 Comprehensive quality control system

BS 5333 : 1975 Glossary of Terms used in metrology

## POLOGNE

Polski Komitet Normalizacji, Miar i Jakosci

Dziennik Normalizacji i Miar : Nr 14, 15, 16-1981

Zarzadzenie z dnia 30-6-1981 r. sprawie ustalenia przepisow :

Nr 110 o pojemnikach dokeadniejszych

Nr 111 o tachometrach

Instrukcja Nr 5 z dnia 16-7-1981 r. o sprawdzaniu narzedzi do pomiaru energii elektrycznej

Instrukcja z dnia 31-7-1981 r. o sprawdzaniu :

Nr 6 suwmiarek o zakresie pomiarowym do 1 000 mm z noniuszem 0,05 mm i 0,1 mm

Nr 7 optycznych glowic podzialowych

## SUEDE

Statens provningsanstalt

SPFS 1981 : 12 Föreskrifter om miljöprovningskrav för genomströmningsmätare avsedda för andra vätskor än vatten samt tillsatsutrustning till genomströmningsmätare, 5-10-1981

SPFS 1981 : 13 Föreskrifter om miljöprovningskrav för vagar och vägningsanläggningar avsedda för vägning i detaljhandeln, 5-10-1981

SPFS 1981 : 15 Föreskrifter om ändring i föreskrift (SPFS 1978 : 4) om tillsatsanordninger till genomströmningsmätare för andra vätskor än vatten

SPFS 1981 : 18 Föreskrift om ändring i övergangsföreskrifter för mätdon godkända av kungl Mynt-och Justeringsverket, mm (SPFS 1978 : 26)

## URSS

Gosudarstvennyi Komitet SSSR po Standartam

State system for ensuring the uniformity of measurements :

Gost 8.422-81 : Frequency meters. Methods and means for verification

Gost 8.424-81 : Mass of economic goods transported by railway. Techniques of measurement

Gost 8.427-81 (ST SEV 1710-79) : Standard platinum resistance thermometers. Methods and means of calibration

Gost 8.428-81 (ST SEV 630-77) : Areometers. The values of coefficients of surface tension of liquids

Gost 8.432-81 : Grain and products of processing. Method of carrying out measurements of moisture on model vacuum thermal set

Gost 8.433-81 : State special standard and state hierarchic diagram for variable pressure measuring instruments in the range from $ 1. 1 0^{2} $ to $ 1. 1 0^{6} $ Pa for frequencies from $ 5. 1 0^{-2} $ to $ 1. 1 0^{4} $ Hz, durations from $ 1. 1 0^{-5} $ to 10 s under constant pressure up to $ 5. 1 0^{6} $ Pa

Gost 8.434-81 : Humidity of grain and its processing products. Method of carrying out measurements by dielectric and resistive moisture ranges

Gost 8.437-81 : Systems of information and measurement. Metrological ensurance. General statements

Gost 8.443-81 : Standard instruments for monopulse and modulated pulse laser radiation peak power measurements. Methods and means for verification

Gost 8.446-81 : Meteorological barographs of aneroid type. Methods and means for verification

<div align="center">

# RECOMMANDATIONS INTERNATIONALES

de la

</div>

## CONFERENCE INTERNATIONALE DE METROLOGIE LEGALE

<table><thead><tr><th>R.I. N°</th><th>Secrétariats</th><th>Année d’édition</th></tr></thead><tbody><tr><td>— Vocabulaire de métrologie légale (termes fondamentaux) (édition bilingue français/anglais)</td><td>Pologne</td><td>1978</td></tr><tr><td>1 — Poids cylindriques de 1 gramme à 10 kilogrammes (de la classe de précision moyenne)</td><td>Belgique</td><td>1973</td></tr><tr><td>2 — Poids parallélépipédiques de 5 à 50 kilogrammes (de la classe de précision moyenne)</td><td>Belgique</td><td>1973</td></tr><tr><td>3 — Réglementation métrologique des instruments de pesage à fonctionnement non automatique</td><td>R.F. d’Allemagne et France</td><td>1978</td></tr><tr><td>4 — Fioles jaugées (à un trait) en verre</td><td>Royaume-Uni</td><td>1970</td></tr><tr><td>5 — Compteurs de volume de liquides (autres que l'eau) à chambres mesureuses</td><td>R.F. d’Allemagne et France</td><td>1981</td></tr><tr><td>6 — Prescriptions générales pour les compteurs de volume de gaz</td><td>Pays-Bas et R.F. d’Allemagne</td><td>1978</td></tr><tr><td>7 — Thermomètres médicaux à mercure, en verre, avec dispositif à maximum</td><td>R.F. d’Allemagne</td><td>1978</td></tr><tr><td>8 — Méthode étalon de travail destinée à la vérification des instruments de mesurage du degré d’humidité des grains</td><td>R.F. d’Allemagne</td><td>1970</td></tr><tr><td>9 — Vérification et étalonnage des blocs de référence de dureté Brinell</td><td>Autriche</td><td>1970</td></tr><tr><td>10 — de dureté Vickers</td><td>Autriche</td><td>1970</td></tr><tr><td>11 — de dureté Rockwell B</td><td>Autriche</td><td>1970</td></tr><tr><td>12 — de dureté Rockwell C</td><td>Autriche</td><td>1970</td></tr><tr><td>13 — Symbole de correspondance</td><td>B.I.M.L.</td><td>1970</td></tr><tr><td>14 — Saccharimètres polarimétriques</td><td>R.F. d’Allemagne</td><td>1978</td></tr><tr><td>15 — Instruments de mesure de la masse à l’hectolitre des céréales</td><td>R.F. d’Allemagne</td><td>1970</td></tr><tr><td>16 — Manomètres des instruments de mesure de la tension artérielle</td><td>Autriche</td><td>1970</td></tr><tr><td>17 — Manomètres - vacuomètres - manovacuomètres - indicateurs (instruments usuels)</td><td>U.R.S.S.</td><td>1981</td></tr><tr><td>18 — Pyromètres optiques à filament disparaissant</td><td>U.R.S.S.</td><td>1970</td></tr></tbody></table>

19 — Manomètres - vacuomètres - manovacuomètres - enregistreurs (instruments usuels) U.R.S.S. 1981

20 — Poids des classes de précision $E_1$ $E_2$ $F_1$ $F_2$ $M_1$ de 50 kg à 1 mg Belgique 1973

21 — Taximètres R.F. d'Allemagne 1973

22 — Alcoométrie France 1973

— Tables alcoométriques France 1975

23 — Manomètres pour pneumatiques U.R.S.S. 1973

24 — Mètre étalon rigide pour Agents de vérification Inde 1973

25 — Poids étalons pour Agents de vérification Inde 1977

26 — Seringues médicales Autriche 1973

27 — Compteurs de volume de liquides autres que l'eau — Dispositifs complémentaires R.F. d'Allemagne et France 1973

28 — Réglementation « technique » des instruments de pesage à fonctionnement non-automatique R.F. d'Allemagne et France 1981

29 — Mesures de capacité de service Suisse 1973

30 — Mesures de longueur à bouts plans U.R.S.S. 1981

31 — Compteurs de volume de gaz à parois déformables Pays-Bas 1973

32 — Compteurs de volume de gaz à pistons rotatifs et compteurs de volume de gaz à turbine R.F. d'Allemagne 1973

33 — Valeur conventionnelle du résultat des pesées dans l'air B.I.M.L. 1973

34 — Classes de précision des instruments de mesurage U.R.S.S. 1974

35 — Mesures matérialisées de longueur pour usages généraux Belgique et Hongrie 1977

36 — Vérification des pénétrateurs des machines d'essai de dureté Autriche 1977

37 — Vérification des machines d'essai de dureté système Brinell Autriche 1977

38 — Vérification des machines d'essai de dureté système Vickers Autriche 1977

39 — Vérification des machines d'essai de dureté système Rockwell B,F,T — C,A,N Autriche 1977

40 — Pipettes étalons pour Agents de vérification Inde 1977

41 — Burettes étalons pour Agents de vérification Inde 1977

42 — Poinçons de métal pour Agents de vérification Inde 1977

43 — Fioles étalons graduées en verre pour Agents de vérification Inde 1977

44 — Alcoomètres et aréomètres pour alcool France 1977

<table border="1"><tr><td>45</td><td>— Tonneaux et futailles</td><td>Autriche</td><td>1977</td></tr><tr><td>46</td><td>— Compteurs d’énergie électrique active à branchement direct</td><td>France</td><td>1978</td></tr><tr><td>47</td><td>— Poids étalons pour le contrôle des instruments de pesage de portée élevée</td><td>R.F. d’Allemagne et France</td><td>1978</td></tr><tr><td>48</td><td>— Lampes à ruban de tungstène pour l’étalonnage des pyromètres optiques</td><td>U.R.S.S.</td><td>1978</td></tr><tr><td>49</td><td>— Compteurs d'eau (destinés au mesurage de l'eau froide)</td><td>Royaume-Uni</td><td>1977</td></tr><tr><td>50</td><td>— Instruments de pesage totalisateurs continus à fonctionnement automatique</td><td>Royaume-Uni</td><td>1980</td></tr><tr><td>51</td><td>— Trieuses pondérales de contrôle et trieuses pondérales de classement</td><td>Royaume-Uni</td><td>1980</td></tr><tr><td>52</td><td>— Poids hexagonaux — Classe de précision ordinaire — de 100 grammes à 50 kilogrammes</td><td>Belgique et Royaume-Uni</td><td>1980</td></tr><tr><td>53</td><td>— Caractéristiques métrologiques des éléments récepteurs élastiques utilisés pour le mesurage de la pression</td><td>U.R.S.S.</td><td>$\cdot$</td></tr><tr><td>54</td><td>— Echelle de pH des solutions aqueuses</td><td>U.R.S.S.</td><td>1981</td></tr><tr><td>55</td><td>— Compteurs de vitesse, compteurs mécaniques de distance et chronotachygraphes des véhicules automobiles — Réglementation métrologique</td><td>Pologne</td><td>1981</td></tr><tr><td>56</td><td>— Solutions-étalons, reproduisant la conductivité des électrolytes</td><td>U.R.S.S.</td><td>1981</td></tr><tr><td>57</td><td>— Ensembles de mesurage de liquides autres que l'eau équipés de compteurs de volumes — Dispositions générales</td><td>R.F. d’Allemagne et France</td><td>1982</td></tr></table>

## DOCUMENTS INTERNATIONAUX

adoptés par le

Comité International de Métrologie Légale

<table border="1"><tr><td colspan="3">D.I. N°</td></tr><tr><td>1 — Loi de métrologie</td><td>BIML</td><td>1975</td></tr><tr><td>2 — Unités de mesure légales</td><td>BIML</td><td>1978</td></tr><tr><td>3 — Qualification légale des instruments de mesure</td><td>BIML</td><td>1979</td></tr><tr><td>4 — Conditions d&#x27;installation et de stockage des compteurs d&#x27;eau froide</td><td>Royaume-Uni</td><td>1981</td></tr></table>

Note — Recommandations internationales et Documents internationaux peuvent être acquis au Bureau International de Métrologie Légale, 11, rue Turgot, 75009 PARIS.

<div align="center">

# ORGANISATION INTERNATIONALE

DE MÉTROLOGIE LÉGALE

</div>

BUREAU INTERNATIONAL DE METROLOGIE LEGALE

11. RUE TURGOT - 75009 PARIS - FRANCE

## ETATS MEMBRES

<table border="1"><tr><td>ALGERIE</td><td>INDE</td></tr><tr><td>REP. FEDERALE D&#x27;ALLEMAGNE</td><td>INDONESIE</td></tr><tr><td>REP. DEMOCRATIQUE ALLEMANDE</td><td>IRLANDE</td></tr><tr><td>ETATS-UNIS D&#x27;AMERIQUE</td><td>ISRAEL</td></tr><tr><td>REP. ARABE D&#x27;EGYPTE</td><td>ITALIE</td></tr><tr><td>AUSTRALIE</td><td>JAPON</td></tr><tr><td>AUTRICHE</td><td>LIBAN</td></tr><tr><td>BELGIQUE</td><td>MAROC</td></tr><tr><td>BULGARIE</td><td>MONACO</td></tr><tr><td>CAMEROUN</td><td>NORVEGE</td></tr><tr><td>CANADA</td><td>PAKISTAN</td></tr><tr><td>CHYPRE</td><td>PAYS-BAS</td></tr><tr><td>REP. DE COREE</td><td>POLOGNE</td></tr><tr><td>REP. POP. DEM. DE COREE</td><td>ROUMANIE</td></tr><tr><td>CUBA</td><td>SRI LANKA</td></tr><tr><td>DANEMARK</td><td>SUEDE</td></tr><tr><td>ESPAGNE</td><td>SUISSE</td></tr><tr><td>ETHIOPIE</td><td>REP. UNIE DE TANZA</td></tr><tr><td>FINLANDE</td><td>TCHECOSLOVAQUIE</td></tr><tr><td>FRANCE</td><td>TUNISIE</td></tr><tr><td>ROYAUME-UNI DE GRANDE-BRETAGNE ET D&#x27;IRLANDE DU NORD</td><td>U.R.S.S.</td></tr><tr><td>GRECE</td><td>VENEZUELA</td></tr><tr><td>GUINEE</td><td>YOUGOSLAVIE</td></tr><tr><td>HONGRIE</td><td></td></tr></table>

## MEMBRES CORRESPONDANTS

Albanie - Botswana - Colombie - Equateur - Fidji - Ile Maurice - Irak - Jamaïque - Jordanie Luxembourg - Mali - Nepal - Nouvelle-Zélande - Panama - Philippines - Portugal - Syrie - Trinité et Tobago Turquie

<div align="center">

# ORGANISATION INTERNATIONALE

DE MÉTROLOGIE LÉGALE

</div>

BUREAU INTERNATIONAL DE METROLOGIE LEGALE

11, RUE TURGOT - 75009 PARIS - FRANCE

## MEMBRES

du

<div align="center">

# COMITE INTERNATIONAL de METROLOGIE LEGALE

</div>

Membre à désigner par son Gouvernement

## ALGERIE

## REPUBLIQUE FEDERALE D'ALLEMAGNE

Mr W. MÜHE

Chef des Bureaux Technico-Scientifiques,

Physikalisch-Technische Bundesanstalt,

Bundesallee 100

3300 BRAUNSCHWEIG.

## REPUBLIQUE DEMOCRATIQUE ALLEMANDE

Mr H.W. LIERS

Directeur de la Métrologie Légale,

Amt für Standardisierung, Messwesen

und Warenprüfung,

Fürstenwalder Damm 388

1162 BERLIN.

## ETATS-UNIS D'AMERIQUE

## REPUBLIQUE ARABE D'EGYPTE

Mr A.O. McCOUBREY Associate Director for Measurement Services National Measurement Laboratory Building 221, Room A 363 National Bureau of Standards WASHINGTON, D.C. 20234.

Mr F.A. SOBHY Président, Egyptian Organization for standardization, 2 Latin America Street, Garden City CAIRO.

## AUSTRALIE

Mr T.J. PETRY Executive Director National Standards Commission, P.O. Box 282 NORTH RYDE, N.S.W. 2113.

Bulletin OIML N° 86 - Mars 1982

Mr F. ROTTER

Président,

Bundesamt für Eich- und Vermessungswesen

Arltgasse 35

A-1163 WIEN.

## AUTRICHE

## BELGIQUE

Madame M.L. HENRION

Ingénieur en Chef

Directeur du Service Belge de la Métrologie,

1795 Chaussée de Haecht

B. 1130 BRUXELLES.

## BULGARIE

Mr P. ZLATAREV

Directeur Général du Centre National

de Métrologie

Comité d'Etat pour la Science et le

Progrès Technique

Département à la Normalisation

21, rue du 6 Septembre

1000 SOFIA

## CAMEROUN

Mr E. NDOUGOU

Directeur du Service des Poids et Mesures

Direction des Prix et des Poids et Mesures

Boîte postale 493

DOUALA.

## CANADA

Mr R. KNAPP Director of Legal Metrology Consumer and Corporate Affairs Holland Avenue, Tunney's Pasture Standards Building OTTAWA, Ontario K1A OC9

## CHYPRE

Mr M. EROTOKRITOS Chief Industrial Officer Ministry of Commerce and Industry NICOSIA.

## REPUBLIQUE DE COREE

Mr KIM Sung-Hwan

Chef de la Division Métrologie

Bureau des Services d'Extension

Bureau du Développement Industriel

Ministère du Commerce et de l'Industrie

SEOUL

## REPUBLIQUE POP. DEM. DE COREE

Mr HO SU GYONG Director, Central Metrological Institute, Metrological Committee Committee of the Science and Technology of the State of the D.P.R. of Korea Sosong guyok Ryonmod dong PYONGYANG.

## CUBA

Mr J. OCEGUERA

Directeur, Instituto National

de Investigaciones Metrologicas (INIMET)

Comité Estatal de Normalizacion

Egido 602 entre Gloria y Apodaca

Zona Postal 2

Ciudad de LA HABANA.

## DANEMARK

Mr E. REPSTORFF HOLTVEG

Directeur, Justervaesenet

Amager Boulevard 115

DK 2300 K$\oslash$BENHAVN S.

## ESPAGNE

Membre à désigner par son Gouvernement

Correspondance adressée à

Comision nacional de Metrologia y Metrotecnia

3 calle del General Ibanez Ibero

MADRID-3.

## ETHIOPIE

Mr NEGUSSIE ABEBE Metrologist and Head of Weights and Measures Inspection Section Ethiopian Standards Institution, P.O. Box 2310 ADDIS ABABA.

## FINLANDE

Mr P. KIVALO Chief Director, Technical Inspectorate. Box 204 Lonnratinkatu, 37 SF 00181 HELSINKI 18.

## FRANCE

Mr P. AUBERT

Chef du Service des Instruments de Mesure

Ministère de l'Industrie

2, Rue Jules-César

75012 PARIS.

## ROYAUME-UNI DE GRANDE-BRETAGNE

ET D'IRLANDE DU NORD

Mr G. SOUCH Director, National Weights and Measures Laboratory, Metrology, Quality Assurance, Safety and Standards Division, Department of Trade 26, Chapter Street LONDON SW1P 4NS.

## GRECE

Madame M. GITZENI

Fonctionnaire technique

de la Direction des Poids et Mesures

Direction Générale Technique

Ministère du Commerce

ATHENES

## GUINEE

Mr B. CONDE

Directeur du Service National

de Métrologie Légale,

Ministère du Commerce Intérieur

CONAKRY.

## HONGRIE

Mr M. GACSI

Président, Orszagos Mérésügyi Hivatal,

P.O. Box 19

H-1531 BUDAPEST

## INDE

Mr S. CHANDRASEKHARAN Director (Weights & Measures) Ministry of Civil Supplies Room No.306, B-Wing, Shastri Bhavan NEW DELHI 110001

## INDONESIE

Mr R. HAROEN

Direktur Metrologi,

Departemen Perdagangan, dan Koperasi

Jalan Pasteur 27

BANDUNG.

## IRLANDE

Mr M. FAHY Principal Officer, Department of Trade, Commerce and Tourism Frederik Building, Setanta Centre, South Frederik Street DUBLIN 2.

## ISRAEL

Membre à désigner par son Gouvernement Correspondance adressée à The Controller of Weights, Measures and Standards Ministry of Industry, Commerce and Tourism Palace Building JERUSALEM.

## ITALIE

Mr C. AMODEO Capo dell'Ufficio Centrale Metrico Via Antonio Bosio, 15 00161 ROMA.

## JAPON

Mr M. KAWATA Director General National Research Laboratory of Metrology 1-4, 1-Chome, Umezono, Sakura-Mura, Niihari-Gun IBARAKI 305.

## Bulletin OIML N° 86 - Mars 1982

## LIBAN

Mr M. HEDARI

Chef du Service des Poids et Mesures,

Ministère de l'Economie et du Commerce.

Rue Al-Sourati, imm. Assaf

RAS-BEYROUTH.

## MAROC

Mr M. BENKIRANE

Chef de la Division de la Métrologie Légale

Direction du Commerce Intérieur,

Ministère du Commerce et de l'Industrie.

RABAT.

## MONACO

Mr A. VATRICAN

Secrétaire Général,

Centre Scientifique de Monaco

16, Boulevard de Suisse

MONTE CARLO.

## NORVEGE

Mr K. BIRKELAND Directeur, Det norske justervesen Postbox 6832 ST. Olavs Plass OSLO 1.

## PAKISTAN

Membre à designer par son Gouvernement Correspondance adressée à Pakistan Standards Institution 39-Garden Road, Saddar KARACHI-3.

## PAYS-BAS

Mr A.C. BIJLOO

Directeur,

Dienst van het IJkwezen, Hoofddirectie

Schoemakerstraat 97, Delft. — Postbus 654

2600 AR DELFT.

## POLOGNE

Mr T. PODGORSKI

Président Adjoint,

Polski Komitet Normalizacji, Miar I Jakosci

ul. Elektoralna 2

00-139 WARSZAWA.

## ROUMANIE

Mr I. ISCRULESCU Directeur, Institutul National de Metrologie, Sos Vitan-Birzesti nr. 11 BUCAREST 5.

## REPUBLIQUE DEM. SOCIALISTE DE SRI LANKA

Mr H.L.K. GOONETILLEKE Deputy Commissioner Measurement Standards and Services Division Department of Internal Trade Park Road COLOMBO 5.

## SUEDE

Mr R. OHLON Ingénieur en Chef, Statens Provningsanstalt, P.O. BOX 857 S-501 15 BORAS.

## SUISSE

Mr A. PERLSTAIN

Directeur, Office Féderal de Métrologie,

Lindenweg 50

3084 WABERN/BE.

## REPUBLIQUE UNIE DE TANZANIE

Mr M. KABALO Principal Inspector, Weights & Measures P.O. Box 313 DAR ES SALAAM.

## TCHECOSLOVAQUIE

Mr T. HILL

Président, Urad pro normalizaci a mereni,

Vaclavské namenti c.19

11347 PRAHA 1 NOVE MESTO.

## TUNISIE

Mr F. MERDASSI

Directeur des Entreprises Publiques

Industrielles et de la Planification

Ministère de l'Economie Nationale

1, rue d'Irak

TUNIS.

## U.R.S.S.

Mr L.K. ISSAEV

Chef du Département de Métrologie,

Gosstandart,

Leninsky Prospect 9

117049 MOSCOU.

## VENEZUELA

Mr A. PEREZ GUANCHEZ

Directeur,

Servicio Nacional de Metrologia Legal

Ministerio de Fomento,

Av. Javier Ustariz, Edif. Parque Residencial

Urb. San Bernardino

CARACAS.

## YOUGOSLAVIE

Mr N. BEVK

Ingénieur, Sous-Directeur,

Bureau Féderal des Mesures et Métaux Précieux

Mike Alasa 14

11000 BEOGRAD.

## PRESIDENCE

Président ... K. BIRKELAND, Norvège

1er Vice-Président . . . L.K. ISSAEV, U.R.S.S.

2e Vice-Président . . . A.O. McCOUBREY, U.S.A.

## CONSEIL DE LA PRESIDENCE

K. BIRKELAND, Norvège, Président

L.K. ISSAEV, U.R.S.S., V/Président

A.O. McCOUBREY, U.S.A., V/Président

W. MUHE, Rép. Féd. d'Allemagne

H.W. LIERS, Rép. Dém. Allemande

P. AUBERT, France

H.L.K. GOONETILLEKE, Sri Lanka

G. SOUCH, Grande-Bretagne

A. PERLSTAIN, Suisse

Le Directeur du Bureau International de Métrologie Légale

## BUREAU INTERNATIONAL DE METROLOGIE LEGALE

Directeur B. ATHANE

Adjoint au Directeur S.A. THULIN

Adjoint au Directeur F. PETIK

Ingénieur Consultant A.B. TURSKI

Administrateur Ph. LECLERCQ

## MEMBRES D'HONNEUR (*)

J. STULLA-GOTZ, Autriche — Président du Comité

H. KONIG, Suisse — Vice-Président du Comité

H. MOSER, Rép. Féd. d'Allemagne — Membre du Conseil de la Présidence

F. VIAUD, France — Membre du Conseil de la Présidence

M.D.V. COSTAMAGNA — Premier Directeur du Bureau

V. ERMAKOV, U.R.S.S. — Vice-Président du Comité

A.J. van MALE, Pays-Bas — Président du Comité

[*] Note : Cette liste ne comprend pas les Membres d'Honneur décédés.