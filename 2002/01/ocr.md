![](page=0,bbox=[183, 218, 266, 304])

<div align="center">

# Editorial

</div>

![](page=0,bbox=[1521, 141, 1852, 564])

Looking ahead...

Gerard Faber CIML President

am writing this Editorial at the beginning of November 2001 but by the time you read it, we will already have celebrated the New Year. Between now and then many events might occur (or might have occurred) but let me assume that these few words are still valid!

First of all, let me take this opportunity to present to you my very best wishes for 2002. May it be a fruitful year for metrology and a happy one for your own personal life.

Together with the Presidential Council and the BIML we are now evaluating and implementing the results of the CIML Meeting in Moscow. Looking back to this event and concentrating only on selected items, I have some observations which I would like to share with you.

From time to time, be it inside or outside the meeting room, discussions about priorities arise. More specifically, the question arises as to whether the OIML should concentrate more on our traditional task of creating Recommendations, or whether we should rather allocate more time to undertaking new tasks which require less technically and more politically oriented decisions to be made. My answer would be: we have to do both! Of course the technical work has to go on and hopefully even be accelerated, but the status of legal metrology is changing in many parts of the world and the OIML - as a key global organization - has to have a say in this. I eagerly look forward to the OIML Workshop Legal Metrology in the Year 2020 in the autumn of this year, as I am sure that many new and innovative ideas will come out of it.

On a more general level, we will increasingly have to pay attention to matters of long term strategy, and continue the studies instigated by our former President Knut Birkeland.

Without such studies, in my view it is impossible to draw up sound action plans. However, we do now have an Action Plan - it is well thought out, up-to-date and you can read it in this issue of the Bulletin.

As discussed in Moscow, the role of RLMOs is becoming increasingly important. As a global organization we have to define our position. I believe that ongoing and intense cooperation between the OIML and the regions is profitable for both, but that the structure of this cooperation has to be improved. I hope that, in 2002, the CIML will approve proposals of how to work together in the most effective and fruitful way.

The comment has been made to me that the Development Council meeting closely resembled part of the CIML Meeting with almost the same delegations. There must be alternative ways to organize this important work more efficiently and perhaps in a less formal manner in order to arrive at practical results as soon as possible. I certainly intend to discuss this with the Chairperson of the Development Council and with the Presidential Council and I hope that I can present some firm proposals to you during this year's CIML Meeting.

Last but not least, looking back to the "Farewell" reception organized for our former Director Bernard Athané, I would like to take this opportunity to express on behalf of all readers of the Bulletin our deepest thanks to Bernard for his enormous contribution to our organization during more than 25 years. The CIML was indeed proud to appoint him CIML Honorary Member! At the same time we offer to the new BIML Director Jean-Francois Magaña our wholehearted support and wish him all success in his new responsibilities.

LINEAR REGRESSION

<div align="center">

# A different means of obtaining a best fit line

</div>

JOSÉ BRENES ANDRÉ Escuela de Física, University of Costa Rica

The best fit line is a common tool in metrological analysis fundamentally during the calibration process at any level. It is regularly used by assuming that all the uncertainties can be loaded onto the independent variable, a practice that can now be considered as the standard method for its widespread use. A way to derive the least square fit is presented, and applied to several special cases. A comparison between the results thus obtained and those predicted by the ordinary least square are discussed.

## Ordinary Least Square (OLS) from a physical point of view

The Ordinary Least Square (OLS) procedure is usually presented in a rather mathematical way, whereby the sum of the squares of the uncertainties of each point $ S ( m,b)=\Sigma( y-m x-b)^{2} $ is set to a minimum by the right choice of the slope m and the intercept b of a straight line, considered as the best fit line, i.e. the appropriate derivatives are taken and set equal to zero:

$$
\frac {\partial S (m , b)}{\partial m} = \frac {\partial}{\partial m} \sum (y - m x - b) ^ {2} = - 2 \sum (y - m x - b) (x) = 0
$$

$$
\frac {\partial S (m , b)}{\partial b} = \frac {\partial}{\partial b} \sum (y - m x - b) ^ {2} = - 2 \sum (y - m x - b) = 0
$$

If $ \Delta= ( y-m x-b) $ is considered as a deformation of a spring of constant unity, it would play the role of a force acting in an externally fixed predefined direction, the y direction in this case. Then the two conditions $ \sum\Delta=0 $ and $ \sum x\Delta=0 $ are recognized as the translational and the rotational conditions for a body to be in equilibrium. Based on these ideas the author has built a mechanical device that shows these analogies, which act as an analogue computer.

This method can also be applied to deduce the best fit line obtained by the LNS method, and eventually expanded to deduce the structural line, which includes the other best fit methods as special cases.

## Derivation of Least Normal Squares (LNS)

To do that let us start by making the translation $ u=x-X $ and $ v=y-Y $ where (X,Y) are the coordinates of the centroid. Because of the translational equilibrium condition the best fit line in the (u,v) plane has to pass through the origin, and hence passes through the centroid $ Y=m X+b. $

![](page=1,bbox=[1026, 857, 1647, 1343])

Figure 1

$$
d = l \cos \beta = (u - w \cos \varphi) \sin \varphi = u \sin \varphi - v \cos \varphi
$$

$$
z + w = l \sin \beta + v / \sin \varphi = v \sin \varphi + u \cos \varphi
$$

Using Fig.1 in the special case $ \phi+\beta=\pi/2 $ we can deduce, by simple geometrical arguments, the lever arm and the torque respectively for each data point (u,v), which correspond to a rotation. This is the starting point the author used in the paper Uncertainty of measurements of calibrated equipment to deduce the LNS equation from other points of view.

The translational equilibrium condition gives, as expected:

$$
\sum \Delta = \sum (u \sin \varphi - v \cos \varphi) = 0 \quad \sum u = 0 \quad \sum v = 0
$$

This is another way of saying that the intercept in the (u,v) plane is the origin. The rotational equilibrium condition gives $ \sum \left( u \operatorname{s i n} \phi- v \operatorname{c o s} \phi\right) \left( v \operatorname{s i n} \phi+ u \operatorname{c o s} \phi\right)=0 $ in turn, from which one easily finds:

$$
\tan 2 \varphi = \frac {2 \sum v u}{\sum \left(u ^ {2} - v ^ {2}\right)}
$$

The inversion property of the LNS can also be deduced from physical arguments. By definition, we took the force to be the distance from the data point to the best fit line. Hence we can define a force along the u axis $ F_{u} $ and another along the v axis $ F_{v} $ . This is the $ \lambda=1 $ case, which allows the best fit line to be inverted, a property very useful from the metrological point of view.

Figure 2 shows that the components of both forces along the perpendicular to the best fit line have to be equal, and hence (taking note of the directions):

$$
\left(m _ {1} y _ {i} + b _ {1} - x _ {i}\right) \sin \varphi = \left(- m _ {0} x _ {i} - b _ {0} + y _ {i}\right) \cos \varphi \quad m _ {0} = \frac {\sin \varphi}{\cos \varphi}
$$

from which $ m_{0} m_{1}=1. $

![](page=2,bbox=[238, 889, 1006, 1360])

We now apply the main ideas to the most general $ \phi+\beta\neq\pi/2 $ case, for which $ I_{0}=w+z $ , $ v=w\sin\phi $ and $ I=u-w\cos\phi $ .

Translational equilibrium requires:

$ \sum I \sin \phi = \sum ( u \sin \phi - v \cos \phi)=0 $ as obtained in the special case of LNS, whereas rotational equilibrium leads to $ \sum I_{0} I \sin \phi=0. $

Since this is a general deduction, the equation z = l $ \omega $ is introduced, where $ \omega $ is a factor to be defined afterwards. With the help of this equation one finds:

$$
\sum \left(u \sin \varphi - v \cos \varphi\right) \left(l \omega + v / \sin \varphi\right) = 0
$$

A little algebraic manipulation leads to:

$$
\sum v ^ {2} - \sum u ^ {2} \frac {\left(\omega \sin^ {2} \varphi\right)}{\left(l - \omega \cos \varphi\right) \cos \varphi} = \sum u v \frac {\left(l - 2 \omega \cos \varphi\right) \sin \varphi}{\left(l - \omega \cos \varphi\right) \cos \varphi}
$$

Aside from having an impressive form, this equation includes the factor $ \omega $ which still has to be defined. We can give it a more "friendly" form by defining:

$$
\lambda = \frac {\left(\omega \sin^ {2} \varphi\right)}{\left(l - \omega \cos \varphi\right) \cos \varphi}
$$

and re-write equation (1) as:

$$
\frac {\sum y ^ {2} - \lambda \sum u ^ {2}}{2 \sum u v} = \frac {\tan^ {2} \varphi - \lambda}{2 \tan \varphi}
$$

$$
\tan^ {2} \varphi + \left(\frac {\lambda \sum u ^ {2} - \sum v ^ {2}}{\sum u v}\right) \tan \varphi - \lambda = 0
$$

where tan $ \phi $ is the required slope.

At this point it may be interesting to look back at the OLS case. Let us start with the relationship $ \tan \phi=\sum v^{2} / \sum u v=r \sigma_{y} / \sigma_{x} $ and use it to calculate:

$$
\tan 2 \varphi = \frac {2 \tan \varphi}{1 - \tan^ {2} \varphi} = \frac {2 \left(\frac {r \sigma_ {y}}{\sigma_ {x}}\right)}{1 - \left(\frac {r \sigma_ {y}}{\sigma_ {x}}\right) ^ {2}}
$$

which is a quadratic that needs to be solved for tan $ \phi $ Not surprisingly the root with the plus sign reproduces $ r \, \sigma_{y} / \sigma_{x} $ but that for the minus sign gives $ -\sigma_{x} / r\sigma_{y} $ which is the slope of the best fit if we take the y axis as having null uncertainty.

## Statistics behind equation (4)

Although this is a more friendly looking formula one still has the problem of how $ \lambda $ (or $ \omega $ for that matter) relates to the statistical part of the problem. To overcome this objection one can, following and using Kendall's notation and numbering [1], start with:

$$
\xi_ {i} = x _ {i} + \delta_ {i}
$$

$$
\eta_ {i} = y _ {i} + \varepsilon_ {i}
$$

$$
y _ {i} = \alpha_ {0} + \alpha_ {1} x _ {i}
$$

$$
(a) \quad E (\xi) = \mu
$$

$$
\mathrm {E} (\eta) = \alpha_ {0} + \alpha_ {1} \mu
$$

$$
s _ {\xi} ^ {2} = \sigma_ {\delta} ^ {2} + \sigma_ {x} ^ {2}
$$

(d)

$$
s _ {\eta} ^ {2} = \sigma_ {\varepsilon} ^ {2} + \alpha_ {1} ^ {2} \sigma_ {x} ^ {2}
$$

(e)

$$
\alpha_ {1} \sigma_ {x} ^ {2} = s _ {\xi \eta}
$$

Kendall, using maximum likelihood arguments and restricting $ \sigma^{2} $ to be non-negative, obtained the set of six inequalities (29.20), from which he finds (29.21):

$$
\left(s _ {\eta} ^ {2} - \sigma_ {\varepsilon} ^ {2}\right) = \alpha_ {1} s _ {\xi \eta} \quad \alpha_ {1} \left(s _ {\xi} ^ {2} - \sigma_ {\delta} ^ {2}\right) = s _ {\xi \eta}
$$

These correspond to equations (1) and (2) in Madansky's [2] paper, who warns the reader that "neither (1),(2),(3),nor (4) are maximum likelihood estimates of $ \beta $". It is interesting to read that "If $ \sigma_{\delta}^{2} $ is known then: $ \alpha_{1}=s_{\xi\eta} / \left(s_{\xi}^{2}-\sigma_{\delta}^{2}\right) $". Note these are different values obtained depending if one knows $ \sigma_{\varepsilon}^{2} $ or $ \lambda $ . But how does mathematics know which case is involved?

Dividing the numerator and the denominator of equation (3) by N, the number of data, one can associate:

$$
\frac {\sum v ^ {2}}{N} = s _ {\eta} ^ {2} = \sigma_ {\varepsilon} ^ {2} + \alpha_ {1} ^ {2} \sigma_ {x} ^ {2}
$$

$$
\frac {\sum u ^ {2}}{N} = s _ {\xi} ^ {2} = \sigma_ {\delta} ^ {2} + \sigma_ {x} ^ {2}
$$

$$
\frac {\sum u v}{N} = s _ {\xi \eta}
$$

$$
\alpha_ {1} = \tan \varphi
$$

Because $ \alpha^{2}-\lambda_{-}\neq0 $ equation (4) can be re-written as:

$$
\theta = \frac {\alpha^ {2} - \lambda}{2 \alpha} = \frac {\left(\sigma_ {\varepsilon} ^ {2} + \alpha_ {1} ^ {2} \sigma_ {x} ^ {2}\right) - \lambda \left(\sigma_ {\delta} ^ {2} + \sigma_ {x} ^ {2}\right)}{2 s _ {\xi \eta}} = \frac {\sigma_ {x} ^ {2} \left(\alpha_ {1} ^ {2} - \lambda\right) - \left(\lambda \sigma_ {\delta} ^ {2} - \sigma_ {\varepsilon} ^ {2}\right)}{2 s _ {\xi \eta}}
$$

Several alternatives are possible. For instance if:

$$
\left(\lambda \sigma_ {\delta} ^ {2} - \sigma_ {\varepsilon} ^ {2}\right) = 0
$$

one finds the usual definition of $ \lambda $ , for which case equation (4) turns into:

$$
\alpha_ {1} ^ {2} s _ {\xi \eta} + \alpha_ {1} \left(\lambda s _ {\xi} ^ {2} - s _ {\eta} ^ {2}\right) - \lambda s _ {\xi \eta} = 0 \text {a n d} \alpha_ {1} \sigma_ {x} ^ {2} = s _ {\xi \eta}
$$

If on the other hand $ \sigma_{\varepsilon}^{2}=R\alpha_{1}^{2}\sigma_{x}^{2} $ and $ \sigma_{x}^{2}=R\sigma_{x}^{2} $ , then $ \alpha_{1}\sigma_{x}^{2}(1+R)=s_{\xi\eta} $ , no definition of $ \lambda $ is possible and $ \alpha_{1}^{2}=\sigma_{\varepsilon}^{2} / \sigma_{x}^{2} $ , which is equation (4) of Lindley [3], obtained from maximum likelihood arguments (and heavily objected to by him).

Several comments can now be made referring to the way in which the structural equation are deduced here. First, equation (4) was obtained from physical and geometrical arguments, without imposing any restrictions on any of the estimators used, avoiding the objection posed by Kendall (equation 29.8), Lindley [3], and Solari [4] that "in fact no maximum likelihood solution exists for this problem" (Robertson [5], page 357). Second, there is no need to study all the different possibilities between the estimators, as was to objected by Kendall (equation 29.17) and by Birch [6]. Third, rather than be amazed as Birch was for cases (v) and (vi) of his paper where he writes "It is notable that the formula for $ \alpha_{1} $ is the same as that for $ \alpha_{1} $ in case (i)", with this derivation it is only natural that it has to be so.

Last but not least, the fact that equation (29.27) can only be obtained from geometrical considerations, that (29.19) (c) and (d) leads to (29.19) (e) and to an expression for $ \lambda $ , suggests that the structural line has a deeper meaning than initially supposed.

Several special cases are reproduced if one uses geometry to find the value of $ \omega $ , equation (2) to find the value of $ \lambda $ , and equation (5) to evaluate $ \sigma $ . Such three special cases are presented in Table 1.

It is worth noting that Lindley writes: "In many applications it will be known that the two errors (in x and y) are about the same order of magnitude. This might imply that $ \lambda $ lies between $ k^{-1} $ and k for suitable k, when quite strong results about the posterior distribution of $ \theta $ can be made by the methods of Section 4", which seems to be in the line of $ \omega $ , which in turn is related to $ \lambda $

<table border="1"><tr><td>Description</td><td>ω</td><td>λ</td><td>σ</td><td>Tan φ</td></tr><tr><td>OLS along y-axis</td><td>1/ cosφ</td><td>∞</td><td>$\sigma_{\varepsilon}^{2}=0$</td><td>$\sum uv/\sum u^{2}$</td></tr><tr><td>LNS, lines perpendicular</td><td>Cosφ</td><td>1</td><td>$\sigma_{\delta}^{2}=\sigma_{\varepsilon}^{2}$</td><td></td></tr><tr><td>OLS along x-axis</td><td>0</td><td>0</td><td>$\sigma_{\delta}^{2}=0$</td><td>$\sum v^{2}/\sum uv$</td></tr></table>

Table 1

## Comparison of both methods

The author has applied both methods to several sets of points, and compared the results predicted by each of them. Although he grants from the start that the sets used are very unlikely to appear in any real measurement, the two methods do not have any in-built supposition that prevent us from applying them to such point distribution.

Four distributions will be studied, composed of the following points:

Case A (1,1) (-1,1)

Case B (1,-1) (1,1)

Case C (1,1) (-1,1) (-1,-1) (1,-1)

$$
\mathrm {C a s e D} (1, 2) (1, - 2) (- 1, - 2) (- 1, 2)
$$

The distributions are presented in Table 2 showing the intermediate values necessary to calculate tan 2 $ \phi $ of the LNS, as well as the value of the slope m obtained by the OLS.

<table border="1"><tr><td>Case</td><td>$\sum u^{2}$</td><td>$\sum v^{2}$</td><td>$\sum uv$</td><td>$\phi$</td><td>m</td></tr><tr><td>A</td><td>2</td><td>0</td><td>0</td><td>0</td><td>0</td></tr><tr><td>B</td><td>0</td><td>2</td><td>0</td><td>$\pi/2$</td><td>0/0</td></tr><tr><td>C</td><td>4</td><td>4</td><td>0</td><td>0/0</td><td>0</td></tr><tr><td>D</td><td>16</td><td>4</td><td>0</td><td>$\pi/2$</td><td>0</td></tr></table>

<div align="center">

Table 2

</div>

It can be seen that for Case A both methods give the expected null slope of a horizontal line.

Should we deal with a vertical line (Case B) the ordinary method gives an undefined value, rather than the expected $ \infty $ , obtained by the LNS.

For the four corners of a square (Case C) the ordinary method gives a null slope, not recognizing the symmetry of the distribution, put in evidence by the LNS result of 0/0.

If the square is deformed to a rectangle with its larger side on the horizontal (not shown), both methods give a null slope, as expected. But if its larger side is vertical (Case D) this difference is not accounted for by the ordinary method (m = 0 again) as it is by the LNS $ \phi=\pi/2). $

Due to the fact that the structural equation seems to give more reasonable results than the OLS method commonly used, the author would like to propose that the LNS method be considered as an alternative method to carry out line fitting. To further support this claim, he would like to draw attention to the odd situation that occurs when the OLS is used: mainly, that two different results for the slope are obtained when the OLS method is used (see for example [7]), which can be avoided if the LNS method is used from the start, for it intrinsically allows for inversion.

## Conclusion and proposal

Although there exists some contradiction between studies done by Lakshminarayanan and Gunst [8] who suggest that some 200r data points are required to obtain slope values within 1% (r = number of times every point is replicated), and Robertson [5] who writes "We see from these results that for sensible parameter values n does not need to be large to make the first-order

approximations good enough for practical purposes", the fact is that today it is very common to take the data points digitally with the help of a given (and probably not very expensive) interface with a PC. Hence the number of data points may not now be a problem even in small laboratories in developing countries.

## References

[1] Kendall, M.G. and Stuart,A. The advanced theory of Statistics, 2, Chap 29, London: Griffin.

[2] Mandansky, A. The fitting of straight lines when both variables are subject to error, Am. Statis. Ass. J. 54 (1959) 173-205

[3] Lindley, D.V. and El-Syyad, G.M. The Bayesian estimation of a linear functional relationship, J. Roy. Statis.Soc 30 (1968) 190-202

[4] Solari, M. The Maximum likelihood solution of the problem of estimating a linear functional relationship, J. Roy Statis. Soc 31 (1969) 372-375.

[5] Robertson, C. Large-sample theory for the linear structural relation, Biometrika (1974), 61, 2, pp. 353-359

[6] Birch, M.W. A note on the maximum likelihood estimation of a linear structural relationship, Am. Statis.Ass. J. 59, (1964) 1175-1178

[7] Berkson, J. Are there two regressions?, J. Am. Statis. Ass. 45 (1950) 164-180.

[8] Lakshminarayanan, M and Gunst, R. Estimation of parameters in linear structural relationships: Sensitivity to the choice of the ratio of error variances, Biometrika (1984) 71, 3, pp. 569-573

The author may be contacted by e-mail: jbrenes@cariari.ucr.ac.cr

FLUID MEASUREMENT

<div align="center">

# Some practical aspects regarding the traceability of systems measuring large quantities of fluids

</div>

ION FLORIAN CRETU

Head of Measuring Systems Laboratory, National Institute of Metrology, Bucharest, Romania

## Abstract

Ensuring the traceability of systems measuring large quantities of fluids gives rise to a series of problems. Solving these requires data analysis using methods which are generally infrequently used in metrological activity.

This paper analyzes some theoretical aspects of the way in which current normative documents deal with the uncertainty problems specific to large systems, and emphasizes the need for a more careful definition of the "reference" notion when dealing with traceability, resulting from a practical approach.

Finally, examples of solutions to some of the problems encountered in estimating uncertainty and ways of diagnosing improper functioning modes are also presented.

## Introduction

Current systems that measure quantities of fluids using computing micro-systems, either built into the components or autonomous, have two functions: the main measurement function is complemented by the capacity to transfer and analyze large amounts of data using techniques which are easily accessible to those having only limited knowledge of the field. It therefore becomes possible to control systems comprising many components, situated hundreds or even thousands of kilometers away, thus providing important technological and financial benefits.

A number of normative documents deal with these problems [1-6] but sometimes only in a general way, and sometimes geared towards the components.

These benefits to the user can be outweighed if they do not pertain to the main purpose, which is the traceable measurement of a certain amount of fluid, with a certain degree of uncertainty.

In this paper the author analyzes some problems specific to large systems (i.e. ones which measure large quantities of fluids), from the point of view of traceability and uncertainty.

## Traceability

Traceability is a property of the result of a measurement that allows this result to be viewed in relation to "stated references" through a series of comparisons, each of them being characterized by a determined uncertainty (VIM 6.10, 1993).

When applying this definition to systems that measure large quantities of fluids, some practical aspects need to be addressed:

a) It is difficult (and sometimes impossible) to devise experiments to calibrate the primary transducers (such as the orifice flow transducers in systems that measure large volumes of gases) to flow or volume (mass) standards.

b) When the final result desired by the user is the volume of fluid in standard conditions, this result is an output of the whole system, obtained by correcting the measurement output of the primary transducer. Sometimes, the system cannot be checked as a whole.

c) When the final result is the fluid mass, the correction is no longer necessary but the uncertainty in the density of the fluid can have an important impact on the general uncertainty of the system. In such a way, the metrological control of the devices that measure the density or composition of the gases becomes an important issue.

d) When the final result is the fluid energy, the same problem must be solved related to the calorific value of the fluids.

When the above-mentioned problems concern the system structure the sets of rules provided by the reference documents (forms, limits, relations) may be applicable, even though they do not belong to the same (physical) class as the main measurand.

For example, an orifice device for measuring the amounts of natural gas can be traced to:

- ISO 5167 [2] for converting flow to pressure difference;

- AGA 8 [6] for converting the flow (volume) of gas from working conditions to standard conditions.

These facts lead to the necessity for the user to perform a precise, even though indirect, estimate of the uncertainty.

A system such as the one described above can produce an uncertainty parameter of 0.7-1.0 % in the case of correctly solving the environmental problems for secondary and tertiary devices (Fig.1), when choosing the optimal excursion interval for the working point (dynamic ratio).

Sometimes, much smaller values of this parameter are needed. The obvious solution to the problem would be the use of a system having a more efficient and more traceable primary transducer, based on a different principle. However, such a system might be expensive, and the transducer more difficult to control, leading to reduced accessibility for most users.

A second solution might be the subsequent use of the data recorded during its use, in order to establish a maintenance policy, thus achieving a better coherence of the systems from a certain technological area [8], [9]. Even though this solution is not simple and implies systematic actions at the level of the working procedures, it is preferred by users since it uses data collected anyway for management needs. In the final part of this paper the author presents an example that uses such a solution.

A system for measuring the volume of oil products with a positive displacement (PD) meter is traceable to:

- The volume standard, through calibrations usually done on site, using a prover or a master meter;

- API - MPMS Chapter 11.1 [4] for correcting the volume from the working conditions to the standard conditions.

It is to be noted that the two traceability references are different: the volume standards are physical entities, while the reference for corrections comprises calculus methods or tables.

The calibration or verification methods were elaborated according to this separation of references. For a volume meter, the calibration method has as a goal the determination of the meter factor (MF) through the direct comparison of the volume meter's measurements with those of the standard, while the same fluid flows through both devices.

The volume correction is actually done using a subsystem that contains secondary and tertiary elements. For oil volume measurement there are normative references [7] that deal with all the problems related to the correction.

For the system as a whole, there are prescriptions stressing different issues [1]. An important aspect to be mentioned is the fact that for pipeline measurements, systems with a 0.3% overall uncertainty are recommended, but it is necessary to use volume transducers with an error limit of 0.2% , covering most of the system uncertainty.

![](page=6,bbox=[384, 1559, 1670, 2429])

<div align="center">

Fig.1 Schematic of a system for measuring the amount of fluid

</div>

Once these goals are fixed, one needs to analyze from a practical point of view which conditions need to be imposed on both the components and on the system as a whole, in order for the desired performance to be achieved. Additionally, the reliability of this performance to varying technological parameters, system parameters and influence quantities needs to be ascertained.

Under such circumstances, it is useful to note that about 2/3 of the system uncertainty is due to the meter, and that for the majority of commercial meters there are non-negligible dependencies of the measured flowrate, temperature and viscosity.

Among such dependencies, the flowrate issue is usually resolved by the flow computer [10] through the linearization procedure. Correcting for temperature and viscosity dependence when measuring large quantities of fluid is more difficult, implying a lack of precise knowledge about the fluid properties under discussion Practically, such problems can be solved in additional steps, through repeated calibrations under different circumstances and a systematic analysis of the outputs of the system associated with laboratory data (function of densities or viscosities vs. temperature).

## Uncertainty

As presented above, when it is impossible from a practical point of view to devise experiments to characterize a system as a whole, the system uncertainty is the only indicator for its traceability and the quality of the measurements made using the system.

As both the cost of the system and the quality of its main function are determined by its uncertainty, estimating this parameter becomes extremely important, leading to the need to establish a standard form for the estimation method and associate the result with a confidence level.

All the regulations issued by national or international institutions deal with the problem of estimating the uncertainty, but in order to correctly apply the recommendations a thorough classification and interpretation is needed. These regulations can deal with the uncertainty of:

- the whole system;

- a part of a system (for example, the volume correction sub-system);

- a device belonging to the system (for example, the volume meter).

The recommendation for estimating the uncertainty can have different forms:

- an equation to be used for calculations;

- an interval suitable for different conditions;

- a precise value.

- Or it may have different destinations:

- limits that have to be respected under certain circumstances;

- reference values or intervals.

The procedure for calculating the composed uncertainty can be:

- through quadratic addition;

- through linear addition of the component parts;

- a combination of the first two.

Table 1 presents a synthesis of the prescriptions regarding the five most important international normative documents in the field.

<div align="center">

Table 1 Synthesis of the prescriptions regarding the five most important international normative documents in the field of composed uncertainty

</div>

<table border="1"><tr><td>Characteristic</td><td>Criterion</td><td>OIML R 117</td><td>ISO 5167</td><td>CEN TC 237</td><td>API Ch.21/1</td><td>API Ch.21/2</td></tr><tr><td rowspan="3">Goal</td><td>System</td><td>×</td><td>×</td><td></td><td></td><td></td></tr><tr><td>Sub-system</td><td>×</td><td></td><td>×</td><td>×</td><td>×</td></tr><tr><td>Component</td><td>×</td><td></td><td></td><td></td><td></td></tr><tr><td rowspan="3">Form</td><td>Equation</td><td></td><td>×</td><td>×</td><td>×</td><td>×</td></tr><tr><td>Interval</td><td>×</td><td></td><td></td><td></td><td></td></tr><tr><td>Punctual</td><td>×</td><td>×</td><td>×</td><td>×</td><td>×</td></tr><tr><td rowspan="2">Destination</td><td>Limit</td><td>×</td><td>×</td><td>×</td><td>×</td><td>×</td></tr><tr><td>Reference</td><td>×</td><td>×</td><td></td><td></td><td></td></tr><tr><td rowspan="3">Addition method</td><td>Quadratic</td><td></td><td>×</td><td></td><td>×</td><td>×</td></tr><tr><td>Absolute value, linear</td><td></td><td></td><td>×</td><td></td><td></td></tr><tr><td>Composed</td><td>×</td><td></td><td></td><td></td><td></td></tr></table>

The five documents define an extremely valuable system of criteria for solving practical problems such as pattern approvals, comparisons of measurement systems, or determining the influence of a component of a system on the uncertainty of the whole system.

One of the important issues to be discussed here is the addition method for the partial uncertainties in order to determine the uncertainty of the whole system meaning the uncertainty with which the quantity of fluid is measured. This value needs to be associated with a confidence level.

The published literature recommends quadratic addition in the case of the non-correlated components with normal distribution, or the addition of the absolute values for those situations where the components are non-randomly distributed. These addition methods, resulting from the practical experience of well-established laboratories, rely on the careful analysis of the physical phenomena and are geared towards obtaining the uncertainty level of the system with only a small computational effort. At the present time and considering the developments of computational techniques, such considerations are no longer of importance.

It is important to stress, however, that the level of confidence (usually 95 %) is assumed and specific to a normal distribution of the components. Such a condition is not always fulfilled.

A more realistic hypothesis is the assumption that, in the case where the component of the system is a transducer, the measured value can be found with equal probability in the interval delimited by its maximum permissible error ( $ \pm $ MPE), around the conventionally true value. In such a way, a device can be modeled using a random number generator for uniform distributed values.

The algorithm of the system can be written in a code that can be executed within a short time period. Each run of the program uses as input data randomly generated numbers (distributed uniformly, or, if needed, according to any other kind of distribution). The code is run a large number of times in order to ensure the stability of the distribution of the result (the corrected volume). By analyzing the results, one can obtain a high "hit rate" (for example 95 %) when defining the uncertainty of the system at the working point.

This estimation technique, relying on the Monte Carlo method, allows the user to obtain results in a very short time - in the order of seconds for today's computers.

An important advantage of this method is the fact that, when graphically representing the histogram of the results, one can obtain an intuitive estimate of the balance of the system at a certain working point.

The results (the uncertainty of the systems) obtained with this method were compared to those obtained

through quadratic addition. The maximum differences between the two uncertainty estimates are less than 12% (1.12% with 95% confidence level using the Monte Carlo method vs. 1% using the quadratic addition method).

## Examples

## 1 The instrumental uncertainty of an orifice system for measuring the flowrate (volume) of gas

Figure 2 presents the schematic of a station measuring the flowrate (volume) of gas using a sensor with a flange tap orifice connected to two instrument assemblies (primary and test). The estimation of the volume of gas is done according to ISO 5167 and AGA 8 GROSS 2 [2], [6]. Table 2 presents the main characteristics of the secondary (transducers) and tertiary (flow computer) elements of the primary system.

For performing the calculations, the uncertainty of the primary sensor (and associated uncertainties) and that of the secondary and tertiary systems were separated. The calculations were made for a known gas (Amarillo, [6]).

By applying the statistical model of analyzing the uncertainty of the secondary and tertiary elements described above, the data set whose histogram is presented in Fig. 3 is obtained. The following important features are as follows:

a) The flat flow histogram is mainly due to the preponderance of one of the partial uncertainties (the pressure difference);

![](page=8,bbox=[1069, 1889, 1822, 2429])

<div align="center">

Fig.2 Schematic of a station for measuring the amounts of natural gas

</div>

<div align="center">

Table 2 Main characteristics of the secondary (transducers) and tertiary (flow computer) elements of the primary system

</div>

<table border="1"><tr><td rowspan="2">Element</td><td rowspan="2">Interval</td><td colspan="2">Accuracy</td><td rowspan="2">Working point</td></tr><tr><td>class</td><td>type</td></tr><tr><td>Differential pressure transducer</td><td>0 to 37kPa</td><td>0.1</td><td>%FSD</td><td>6kPa</td></tr><tr><td>Static pressure transducer</td><td>0 to 35bar</td><td>0.1</td><td>%FSD</td><td>25bar</td></tr><tr><td>Temperature transducer</td><td>-20 to 80℃</td><td>0.25</td><td>℃</td><td>20℃</td></tr><tr><td>Flow computer</td><td>Configurable</td><td>0.1</td><td>%</td><td></td></tr></table>

b) The uncertainty estimated through statistical modeling (0.39 % at a 95 % confidence level) is 10 % larger than that estimated through quadratic addition (0.34 %). The difference can be explained by the relatively flat shape of the histogram.

c) The height of the green rectangles indicates the level of uniform distribution. Their position on the x-axis represents the values of uncertainty at a 95% confidence level.

If the assumption of a uniform distribution of the input data on the interval of the error limits is correct, then the distribution of the output data (the gas flowrate) under standard conditions is a direct consequence of this assumption. Therefore, the estimated value of the uncertainty associated with a level of confidence is the best measure of the accuracy of the ensemble.

This kind of estimation can easily be achieved for any working point and can lead to an optimal choice for the characteristics of the secondary and tertiary elements of the system.

## 2 Tests for a central(ized) system

A centralized system is composed of two measuring stations on a natural gas transport pipe without ramifications (Fig.4). When functioning normally, the two stations indicated the same volume of gas over long time scales. On short time scales, differences could appear due to perturbations of short duration.

Through data analysis, it was ascertained that while each system offered coherent information individually, there was a consistent difference of about 0.1% between stations.

At a second analysis level, it became apparent that a density difference existed between the measurements made by two stations (Fig. 5).

Finally, at a third level of analysis performed by auditing the activity in the laboratories of both stations

![](page=9,bbox=[976, 815, 1880, 1350])

<div align="center">

Fig. 3 Histogram of a test on the secondary and tertiary devices

</div>

![](page=9,bbox=[971, 1490, 1880, 1883])

<div align="center">

Fig. 4 Schematics of a centralized system

</div>

![](page=9,bbox=[972, 2014, 1882, 2458])

<div align="center">

Fig. 5 Diagram of the evolution of the relative density of a natural gas

</div>

![](page=10,bbox=[102, 286, 1005, 618])

<div align="center">

Fig. 6 A calibration scheme using a master meter

</div>

![](page=10,bbox=[105, 759, 1001, 1352])

<div align="center">

Fig. 7 Diagram presenting the evolution of the MF of a spiral gear meter as a function of temperature

</div>

it was found that an error existed in calibrating the chromatograph of one station.

Such tests are devised as a function of the configuration of the system and, in most cases, are performed automatically. The users are only informed of the results and, sometimes, of the possible correction methods [8], [9].

## 3 Dynamic ratio

The dynamic ratio is defined as the ratio between the maximum and the minimum flowrates, provided that the uncertainty of the system is lower than a pre-defined limit:

$$
r = \frac {Q _ {\max}}{Q _ {\min}}
$$

For systems measuring volumes of natural gas, the maximum value of this ratio is recommended to be 10,

and sometimes 15. For an orifice device using a single differential pressure transducer (frequently, the second transducer exists but is used to increase the reliability of the system), functioning at a constant pressure, the maximum value of this ratio is usually 3, with an uncertainty of around 1 %. The most frequently used solution for performing measurements with large dynamic ratios is the splitting of the gas flowrate and the use of multiple, parallel measuring systems.

Of course, there are solutions using two or three differential pressure transducers with single primary transducers, but here the reliability is slightly less.

It useful to mention that the maximum value of the dynamic ratio very much depends on the conditions secured for the secondary elements. In most cases the secondary and tertiary devices are placed in a temperature-controlled environment.

In cases where the environmental influence on the primary transducer is significant, it is difficult to correct the result of the measurement for such influences. Figure 6 presents a schematic for calibrating a volume meter for oil products in working conditions. Generally, such a set-up allows the determination of an average meter factor (MF) for a small interval of flowrate variation, but only at the fluid's temperature.

Figure 7 presents the variation curves of the MF, as a function of temperature and flowrate. As can be seen from this figure, the temperature influence is 0.1 %/10 $ ^{\circ} \mathrm{C} $ , while the flowrate influence is about 0.2 %/r = 2.

Usually, flow computers can correct for the influence of the flowrate, but not for that of temperature. As a consequence, the temperature will considerably influence the uncertainty of the system.

As a correction method, a MF for a temperature interval is sometimes associated, leading to the need to adapt the calibration frequency, and hence to an increase in the measurement cost. Consequently, there are strong connections between the dynamic ratio variations in environmental conditions and the cost of the measurement, leading to the need for metrological assurance.

When dealing with large systems, from the practical point of view (tests, pattern approvals, parameter estimations, analysis and diagnosis) there are situations in which obtaining measurement results with controlled uncertainty requires techniques specific only to these particular systems. The development of the means of extracting information is extending the currently accepted notion of a system. The use of models in order to analyze metrological resources is already a common and essential practice.

This paper has attempted to anticipate several specific aspects of this evolution, as they have emerged from the practical experience of the author.

## Bibliography

[1] OIML R 117: Measuring systems for liquids other than water, 1995

[2] ISO 5167-1: Measurement of fluid flow by means of pressure differential devices. Amendment 1, 1998

[3] Manual of Petroleum Measurement Standards, Chapter 21: Flow measurement using electronic metering systems. Section 1 Electronic gas measurement. API - AGA, 1993

[4] Manual of Petroleum Measurement Standards. Chapter 21: Flow measurement using electronic metering systems. Section 2 Electronic liquid volume measurement using positive displacement and turbine meters. API, 1998

[5] Gas volume electronic conversion devices. CEN/TC/237/WG4, 1995

[6] Compressibility factors of natural gas and other related hydrocarbon gases. AGA 8, 1994

[7] Petroleum measurement tables vol. 7-10. ASTM D 1250

[8] Richard Rans: Real time measurement, coordination of information processing from the field meter to the bill- $ 2^{\mathrm{nd}} $ Symposium on fluid flow measurement. Calgary, 1990

[9] Richard Rans: Timely accurate measurement information; management of data collection, maintenance and publication of measurement information. $ 4^{\mathrm{th}} $ Symposium on fluid flow measurement. Calgary, 1998

[10] I. F. Cretu: Flow computer verification. OIML Bulletin Vol. XL no. 1, 1999

![](page=11,bbox=[431, 1408, 763, 1817])

ION FLORIAN CRETU Head of Measuring Systems Laboratory National Institute of Metrology Bucharest, Romania

The author welcomes comments on this paper these may be sent by e-mail to:

cretu@inm.ro

Development Council Meeting

RLMO Meeting

36th CIML Meeting

Moscow (Russian Federation)

24-27 September 2001

At the invitation of the Government of the Russian Federation, three meetings were held at the Intourist Hotel, located in central Moscow.

![](page=12,bbox=[1010, 667, 1730, 1735])

The OIML Development Council met for a full day on Monday 24 September,

A meeting of Regional Legal Metrology Organizations was held during the morning of Tuesday 25 September, and

The International Committee of Legal Metrology held its Thirty-Sixth Meeting from 25 through 27 September.

MOSCOW 2001

<div align="center">

# Development Council

</div>

<div align="center">

# 24 September 2001

</div>

REPORT BY CHRIS PULHAM, BIML

The OIML Development Council met on Monday 24 September 2001 at the Intourist Hotel. A summary of the meeting is given in this issue of the Bulletin, and the full Minutes will be published separately.

## Report and discussion on activities since the 2000 meeting (Item 1)

A report drawn up by the BIML was distributed (reproduced in full later in this article).

Discussion was then opened on events that had occurred over the last year. Mr. Magaña called for those who had submitted details of training courses and who had volunteered to act as experts in the field of metrology training, to send all relevant information to the BIML for it to be updated on the web site.

![](page=13,bbox=[102, 1892, 1009, 2518])

## Agenda

Participation

Opening

Roll call

Approval of the agenda

1 Report and discussion on activities since the 2000 meeting of the Development Council (London, UK)

1.1 WTO meeting on developing country participation in standard-setting activities

2 Reports from Working Groups

2.1 WG 1 – Training

2.2 WG 2 – Information

2.3 WG 3 – Equipment

2.4 Discussion of terms of reference for Working Groups

3 Reports by representatives of Regional Legal Metrology Organizations

3.1 Asia-Pacific Legal Metrology Forum (APLMF)

3.2 South-East European Cooperation in Quality, Standardization, Accreditation and Metrology

3.3 Euro-Asian Cooperation of National Metrological Institutions (COOMET)

3.4 Euro-Mediterranean Legal Metrology Forum (EMLMF)

3.5 Indian Ocean Legal Metrology Forum (IOLMF)

3.6 Southern African Development Community Legal Metrology Cooperation (SADCMEL)

3.7 Inter-American Metrology System (SIM) – Legal Metrology Working Group

3.8 European Cooperation in Legal Metrology (WELMEC)

4 Proposal for the 2002 – 2003 work program

5 Information on current projects

5.1 UNIDO - OIML - PTB

6 Information on special activities of Members

7 Other matters

8 Next meeting

9 Conclusion and closure of the meeting

Commenting on point 4 of this report, Mr. Magaña said the objective was to identify obstacles and difficulties that developing countries faced in implementing standards, for example budget constraints, language difficulties, etc.

Mr. Birch suggested that a study could be carried out to ascertain which standards would be applicable to developing countries, beginning by identifying both the products they need and the scope of local requirements before these countries attempt to meet such requirements.

Mr. Magaña commented that ISO now works almost exclusively using electronic documents, the advantage being that this modern communication means can speed up standard-setting activity and costs much less than international traveling, but he was aware of the fact that Internet access is not yet available in every country in the world. This question was also raised concerning OIML TC/SC work and will be considered by the BIML over the coming months. Mr. Boudissa felt that maybe another three or five years would be necessary before each country had access to the Internet. He therefore suggested that for the moment, paper copies of relevant documents would still be needed. Mr. Magaña agreed and confirmed that the CIML would be examining this point in more detail during its meeting later in the week.

On the question of financing, Mr. Boudissa inquired as to what progress had been made. Mr. Dunmill informed participants that the meeting with the World Bank that had been scheduled for 13 September had had to be postponed, but that it would be rescheduled as soon as possible; he confirmed that the World Bank is interested in standard-setting activities and metrology. Mr. Magaña reiterated that the World Bank financing project is looking promising and Mr. Hocine (Algeria) informed participants that he had already visited the World Bank in April - he confirmed that discussions were very encouraging and positive.

Mr. Dunmill noted that the EC also takes standardizing activity into account, but not so much as far as metrology is concerned - one key role of the Development Council would therefore be to increase the EC's awareness of metrology. The Development Council is also in regular contact with UNIDO, and discussions are progressing.

An important issue for the Development Council is the progress of OIML D1 Law on Metrology. Mr. Klenovsky asked about progress and wondered what the BIPM/ILAC impact would be on the progress of this Document. Mr. Magaña responded that OIML TC 3 would be examining the Draft and Mr. Ehrlich confirmed this.

Mr. Dunmill confirmed that general awareness of metrology is increasing, a comment echoed by Mr. Birch, who said that establishing legal metrology services in developing countries should be a priority.

## Reports from Working Groups (Item 2)

On the subject of WG 1 Training, Dr. Wallerus confirmed that the revision of OIML D14 was a priority activity. He reported that he has transformed D14 into a five column table including editorial comments, new objectives, new tasks for verification officers, time needed to accomplish these tasks, references to existing documents, etc. He awaits new proposals, all of which will be integrated into the new Draft.

A Russian Delegate gave a summary of the history of D14 and suggested recognizing different levels of training, including software training and the need to differentiate between different categories of legal metrology training personnel, and encouraged additional professional training. He felt that D14 was a good basis, and the Russian Federation has used it for legal metrology personnel training and for verification operations. He enquired about training for accredited and certified personnel, which he felt should be included.

Mr. Birch commented that developing competence and consistency is not necessarily inherent in OIML publications, but that competence building increases consistency. He wondered about the possibility of accrediting training institutes to essential requirements and felt that competence and training would help the global measurement system. He also said that languages used in training is a widespread problem and that local languages should always be used where possible to overcome this hurdle.

Mr. Vichenkov then gave a summary of progress of Working Group 2 Information over the last year. WG 2 was launched in 2000, and a questionnaire was distributed via the BIML. The results of this were reported in London and proved that a number of countries need information on metrology especially the Law on Metrology, metrological supervision and control. Many expressed concern about computerized databases. For example the VNIIMS has a certain experience in the use of databases and offered to make its own structure available for translation into other languages to use as a basis. A forum could be created for WG 2 for additional ideas to be put forward.

Eleven OIML Member States participate in WG 2. Various questionnaires and surveys have already been

## OIML Development Council Working Groups - Terms of Reference

## WG1 Training (Germany)

Terms of reference:

- Review of International Document D 14 Training of legal metrology personnel, which was published in 1989 and is currently being revised to ensure that uniform training modules are used and that the competency of the training bodies is assured;

- Development of a system of training modules using existing work;

- Cooperation with regional bodies, in particular the Asia Pacific Legal Metrology Forum; and

- Mutual information about planned courses, including the exchange of teaching materials and experience so as to ensure a uniform quality of training.

## WG2 Information (Russian Federation)

Terms of reference:

- To identify the specific needs and requirements of developing countries and in the field of information and documentation on legal metrology and related areas (such as testing, certification, quality management, accreditation, etc.);

- To assist developing countries in formulating these needs;

- To provide a forum for the exchange of knowledge, information and documentation; and

- To advise the Development Council on the policy related to these issues.

## WG3 Equipment (Russian Federation)

Terms of reference:

- To study the needs of developing countries in the fields of

- planning and equipping metrology laboratories,

- comparison and verification of national measurement standards;

- To offer advice and information for national metrology services concerning potential suppliers of metrological equipment and to maintain a database on this subject;

- To examine proposals on metrological equipment subject to assistance projects in relevant national and regional organizations;

- To prepare information related to metrological equipment.

sent out with a view to preparing technical assistance documents and information centers worldwide. Mr. Vichenkov suggested the idea of producing a catalogue of actual measuring instruments that have received OIML certificates. Such instruments are widely used in developing countries. A catalogue could indicate traceability to reference standards including international standards and Mr. Vichenkov felt that this work could contribute to a better recognition of OIML certificates and hence lower technical barriers to trade.

Mr. Magaña felt it would be advantageous to circulate information on such studies in the various regions to other regions. For example the Asia-Pacific region carried out a grain moisture study with Germany. If this information was publicized, it could quite possibly help other regions and individual countries.

Secondly, Mr. Magaña pointed out that developing countries often need pattern approval information in

other countries; these countries may be interested in developing countries' reactions to such instruments arriving in developing countries. The BIML could help in such information exchanges but these should be initiated by Members.

Mr. Vichenkov said he would submit ideas in writing to the BIML as and when new proposals came forward.

On the subject of databases, Mr. Vaucher said that METAS is setting up a database of normative documents, catalogues of approved instruments, legal requirements, etc. It was expected that this would be operational in December 2002. He felt that it is important to exchange information between the various legal metrology actors. He agreed that a forum could be a good information transmission media and invited Mr. Vichenkov to make use of the METAS forum.

Mrs. Annabi suggested that Messrs. Vichenkov and Vaucher might consider working together in close cooperation to harmonize such information together.

Reporting on WG 3 Equipment, Mr. Ragulin said that equipment should be chosen by order of priority, depending on specific local needs. A questionnaire has been drawn up and will be circulated once it has been translated, and an 85-page book sets out recommendations on choosing, setting up and installing measuring instruments.

There was general consensus that additional proposals are needed to define equipment needs.

Following a review by Mr. Magaña of the current objectives and terms of reference for the Working Groups (see insert), under Item 3 very brief reports were given by representatives of Regional Legal Metrology Organizations.

The APLMF identified information, training and workshops as being key areas together with the harmonization of legislation and administration.

COOMET suggested that RLMOs should contribute to the development and implementation of OIML Recommendations and Documents.

SADCMEL has an active Technical Committee studying the question of training, the objective being to promote trade within the region, and set up local "train the trainer" courses.

Under Item 4 Proposal for the 2002-2003 work program, the key points were:

- To ensure that OIML TC/SC work is followed by the Development Council for all areas of relevance to it;

- To work with liaison organizations to ensure funding for developing countries (e.g. the World Bank, the EC, UNIDO and the WTO group on access for developing countries to standard-setting organizations);

- To regularly update the OIML Development Council web site, including training courses and lists of experts;

- To establish links to organizations that offer training; and

- To translate the Development Council web site into Spanish.

Under Item 5.1, UNIDO/OIML/PTB cooperation participants were informed that funding had been obtained in 2001 to finance West African countries' activities.

## Meeting conclusions (Item 9)

In line with discussions held during the Development Council meeting on Monday 24 September 2001 the following recommendations are made for consideration and future action:

1 The Council reviewed the Working Groups' terms of reference and recommended that the BIML consult Development Council members to update the composition thereof.

- Switzerland will contribute its experience to Russia in the tasks of WG2 Information.

- The Chairperson of the Development Council and the BIML are instructed by the Council to follow the progress of the 3 WGs, who are invited to communicate between each other.

- The WGs are each invited to organize a meeting before the next Development Council meeting.

2 The WGs are asked to take into account the work of RLMOs concerning training, information and equipment in order to avoid any overlapping in their programs.

3 The Council requests its Chairperson to contact various bodies who may be able to finance legal metrology activities in developing countries, notably the World Bank, the European Commission and the Islamic Development Bank.

4 The Council recommends its Chairperson and the BIML to continue to work with the World Trade Organization and UNIDO on projects concerning legal metrology.

5 The Council calls on RLMOs to designate their representatives to form a Development Council "Think Tank". Where no representative is designated, the RLMO Chairperson will by default be considered as the representative.

6 The Council asked its Chairperson and the BIML to assist in the participation of Developing Countries in the work of TCs and SCs.

7 The Council requests CIML Members to send recent information to the BIML to regularly update information on the OIML web site concerning experts and training.

8 The Council requests the BIML to continue to develop the web site.

9 The Council underlines the importance of ensuring that Developing Countries have ready access to the Internet (and therefore e-mail and associated computer technologies).

## OIML Development Council Work Program Report

The colored, indented text at the beginning of each section is taken from the proposals given at the last Development Council meeting which took place in London on 11 October 2000.

## 1 Technical work

"The Development Council should continue to participate actively in the revision of D1 Law on Metrology and to maintain and increase its interest in certain important Technical Committees and Subcommittees so as to ensure that the interests of developing countries are taken into account. The list which the BIML had prepared of high priority projects could be used to establish priorities for the Development Council."

The US secretariat for TC 3 sent a working document proposal for a "Law on metrology" to the BIML on 2 February 2001. This was discussed at the joint OIML/BIPM/ILAC meeting held at the BIML on 21 February 2001 and a joint working group has been established to advance work on the document. The OIML is represented by Jean-Francois Magaña, Ghaiet-El-Mouna Annabi and Charles Ehrlich.

## Actions:

- A revised working document is currently being considered by the joint working group prior to being circulated within TC 3.

- The working document will later be examined to see whether it fulfils the needs identified for developing countries, particularly in the light of the UNIDO-OIML-PTB project (see 6 below).

- Having examined the list of high priority and priority projects established by the BIML, it has been decided that the Development Council will take a particular interest in the work of the following TCs/SCs:

- TC 3 Metrological control;

- TC 6 Prepackaged products;

- TC 7/SC4 Measuring instruments for road traffic;

- TC 9/SC3 Weights;

- TC 11/SC1 Resistance thermometers;

- TC12 Instruments for measuring electrical quantities;

- TC 16/SC1 Air pollution;

- TC 16/SC 3 Pesticides and other toxic pollutant substances.

## 2 Web site

"This could be further improved during the year and it is hoped that a Spanish version would also become available. Mr. Dunmill appealed to delegates to assist in keeping the information on experts and training courses up to date."

The Development Council part of the OIML web site has been completely revised. All nominated metrology experts are now available in a database on the site and can be searched by language spoken, by region or by subject. All training courses notified to the BIML are also now present on the site, again searchable by language, by subject or by country.

## Actions:

- The training and experts lists have been transferred to a database system on the web site to make searching for information easier;

- The BIML intends to provide a page of links to training establishments in order to provide more up-to-date information on training courses available;

- The site will be translated into Spanish as soon as possible, in order to make information on the Development Council more widely accessible;

- The BIML will make regular efforts to ensure that the information on experts and training courses is kept up to date.

## 3 Training courses

"The Development Council needs to examine the possibilities for "validation" of training courses."

For the moment, details of the training courses recommended by CIML Members will be placed in a database available through the Development Council web site. It is not considered to be the role of the OIML to "validate" courses, although the use of external accreditation systems would be useful.

## 4 External liaisons and funding

"Mr. Dunmill explained that useful contacts had been made during the last year, but that other points on the work program had needed to be put in place before funding for any specific projects could be sought. It was therefore hoped that these activities could be pursued during the coming year."

Useful contacts were made last year with the World Bank and with the United Nations Economic Commission for Africa, which need to be followed up this year.

In addition, the possibilities for closer cooperation with, for example, ISO DEVCO and the BIPM could be examined. The WTO has also initiated a series of informal meetings on the subject of developing country participation in standard-setting activities. The first meeting, which was held on 23 January 2001, was very useful and could lead to interesting developments, particularly in the area of funding.

## Actions:

- The BIML has requested that these Working Groups provide updates on progress on their work programs at the Development Council meeting.

- The terms of reference and work programs of the Working Groups will be examined at the Development Council meeting to ensure that they still meet the needs of Development Council members.

- The BIML will follow up existing contacts and establish others, where possible, with organizations of interest to the Development Council.

- The BIML has provided information to the WTO following the meeting of 23 January 2001, and will continue to participate actively in this initiative. Another meeting may be held before the end of the year.

- A meeting with the World Bank had been organized for 13 September, which had to be cancelled. Efforts to organize meetings with the World Bank and with the European Commission will be continued.

## 5 Working Groups

The three Working Groups on Training (Germany), Information (Russian Federation) and Equipment (Russian Federation) are following their established work programs.

- The Working Group information on the Development Council web site will continue to be updated whenever possible.

## Actions:

## 6 UNIDO-OIML-PTB project in African LDCs

The BIML sent a request for information on the existing metrology infrastructure to the seven countries which may benefit from this project (Benin, Burkina Faso, Cameroon, Guinea, Mozambique, Tanzania, Uganda) in October 2000. Information has now been received from Benin, Burkina Faso, Cameroon, Guinea and Mozambique. This has been forwarded to UNIDO and the PTB and it is proposed to hold a meeting to discuss the next steps in this project.

## Actions:

- A meeting between the three organizations will be held as soon as possible.

There have also been discussions about another project in certain West African countries, although a proposed initial meeting and presentation of the proposals to the Economic Community of West African States (ECOWAS) in early September had to be cancelled. The BIML will continue to follow developments.

36TH CIML MEETING

<div align="center">

# Opening address by Mr. V. Hristenko

</div>

Deputy Prime Minister of the Government of the Russian Federation

(Speech delivered by Mr. Podufalov, Director Department of Culture, Education and Science Government of the Russian Federation)

## Ladies and Gentlemen,

On behalf of the Government of the Russian Federation I am delighted to be able to personally welcome you to this CIML Meeting, which is taking place in Russia for the very first time.

We consider the fact that you have chosen our country to hold this year's meeting of your distinguished organization - the International Organization of Legal Metrology - firstly as a sign of Russia's role and achievements in contributing to the founding and development of the OIML, and secondly as the stimulus for future activity on the part of Russia in the field of legal metrology.

![](page=19,bbox=[103, 1930, 1008, 2517])

![](page=19,bbox=[1419, 287, 1821, 862])

Russian legal metrology has its origins in the tenth century. Today, Russia is on the way towards full integration in the world economy, is experiencing a transition to free market mechanisms and has the objective to join the WTO; we are paying particular attention to developing and strengthening international cooperation, including cooperation in the framework of international and regional organizations.

Over the past few years OIML activities have resulted in the need for international legal metrology cooperation to become more and more efficient. This cooperation, which was and still is the key component for creating new legislation, affects economic development in a large number of countries all over the world.

The development and implementation of harmonized documents for testing and verifying measuring instruments which are under governmental control and supervision is an extremely important element of the global system of economic cooperation.

Taking into account the significant role of ensuring accurate measurement results for the realization of commercial and scientific relations, Russia is endeavoring to maintain metrological liaisons with as many countries in the world as possible since the consequences of legal metrology are of particular significance for such fields as trade, health, environmental protection and safety.

I am also pleased to confirm that it is of course in the interest of our country to continue to develop and reinforce our efforts aimed at promoting and participating in all OIML activities.

I would like to wish CIML Members and all the participants of the 36th CIML Meeting a very successful meeting, and we look forward to a longstanding fruitful cooperation in the future concerning OIML activities.

36TH CIML MEETING

<div align="center">

# Opening address by Mr. Voronin

</div>

President of the Gosstandart of Russia

Dear Participants in the 36th Meeting of the International Committee of Legal Metrology, Dear representatives of international regional and national organizations, Ladies and Gentlemen,

It is an honor for me to welcome you in the name of the State Committee for Standardization and Metrology of the Russian Federation to this CIML Meeting, which is being held for the first time in our country.

![](page=20,bbox=[1327, 283, 1729, 861])

Legal metrology in Russia has a long history, starting out with the Tsar monitoring weights and measures in the X century - in fact the Church had responsibility for carrying out this surveillance. This limited scope of legal metrology gradually gained ground thanks to Peter the Great's reforms in the XVIII century and to the ukases of the Tsar in 1835 and 1842, up to the time of D. Mendeleev. From 1899 on, verification took on importance nationally through a network of verification chambers, one of which gave rise to the current VNIIMS which celebrated its hundredth anniversary last year.

In 1938 a certain ideology was established in the URSS in the field of measurements (units, standards, tests, verification, surveillance). Essential conditions were instigated in order to adopt a systemic approach to this problem. A national metrology service was formed to ensure the uniformity of measurements in the country.

The Gosstandart of Russia was entrusted with certain powers by the Government of the Russian Federation to represent Russia on the CIML. The Gosstandart much appreciates the activities of this international intergovernmental organization and regards cooperation between the OIML and Russian metrological institutions, other bodies, researchers and experts as being of high importance.

The OIML, including the International Committee of Legal Metrology, has done a very creative job and this has caused both the Organization's international standing and prestige to be elevated and also the efficiency of its activities to be increased.

Let me quote a few examples:

- a modern international legal metrology cooperation infrastructure has been established and functions under the aegis of the OIML;

- the organization and the legislation of metrological activities in OIML Member States and in other countries around the world are established on the basis of OIML Documents and Recommendations, thus reflecting the modern tendencies and perspectives of economic and social evolutions. It is not purely fortuitous if the European Union is planning on making reference to OIML Documents and Recommendations in its directives on measuring instruments;

- the OIML Certificate System is becoming more and more widespread, including in Russia, which has led to a reduction in the costs involved in reverifying imported measuring instruments and also a reduction in the time needed for them to be put into use by the national economic authorities.

These aspects, and many others, have allowed OIML activity to reach a remarkable level of success in the fields of industrial product quality, consumer protection and the elimination of technical barriers to trade. This activity therefore constitutes an element of technical regulation in OIML Members States.

As far as Russia is concerned, the Gosstandart of Russia metrological institutes, and first and foremost the All-Russian Scientific Research Institute of Metrological Service (VNIIMS), are participating in OIML activities.

And as you also know, Russian researchers and experts have always played (and continue to play) an active role in the work of key OIML bodies as well as within the CIML and the BIML, including the roles of CIML Vice President and First Vice President. These specialists have participated in finding solutions to OIML policy problems and to the development and setting up of the long term policy. Despite communication difficulties between the managing and legislative bodies in the context of market relations, we have strived to maintain our level of participation in the management of OIML technical bodies at the same level (34 %). As a result, over 15 % of published international Documents and Recommendations include contributions from Russian authors.

Nowadays we are seeing a growing tendency that the scope of legal metrology activities is broadening out at national level due to the emergence of new fields in which state regulation is very present (in analytical chemistry, electromagnetic compatibility, in the games market, etc.), as well as at international level given the process of globalization in trade, industry or information.

All of this gives rise to the need for strict requirements as concerns the compatibility of metrological prescriptions, and leads to compatibility in the field of

conformity evaluation. This is why we support the idea of creating a global measurement system that standardizes these measurements.

Mutual confidence in the context of metrological activities is becoming increasingly important and is obtained thanks to accreditation, inter-laboratory comparisons, the creation of quality systems by way of participation in mutual recognition agreements, and more efficient working methods at regional level.

These goals and perspectives are defined by the OIML for the XXI century. The Gosstandart of Russia, its researchers and experts - our colleagues - who are working in the field of industry, science and the economy will actively participate in OIML related matters with a view to resolving a number of legal metrology problems with the ultimate aim of providing solutions to topical questions concerning the economic and social development of the world community.

To conclude my brief speech may I wish all Members of the International Committee of Legal Metrology and all the participants in this distinguished OIML forum a fruitful outcome to their busy work schedule; may I also wish you health and success in your furthering of metrology and international cooperation!

Thank you very much for your attention.

![](page=21,bbox=[681, 1457, 1401, 2519])

<div align="center">

# Opening address by Gerard J. Faber

</div>

President, International Committee of Legal Metrology

Ladies and Gentlemen, Dear Colleagues,

It is indeed my pleasure to welcome you to the opening of this 36th Meeting of our Committee and I thank you in advance for your participation which, I am sure, will be as positive and fruitful as usual.

This CIML Meeting starts in the wake of two other important meetings which many of you have attended: a meeting of the OIML Development Council and a meeting of the Regional Legal Metrology Organizations. Mrs. Annabi, for the Development Council, and myself for the RLMOs, will report on the output of both meetings, which may have significant consequences for the work and the future direction and development of our Organization.

It is now already nearly a year since our Eleventh Conference, and one of our main duties this week will be to look at how the decisions of that Conference have been or are being implemented. In particular, we will have to examine the progress already made in two very

![](page=22,bbox=[252, 1775, 820, 2520])

important areas, the Mutual Acceptance Arrangement and the international marking of prepacked products, and make sure that they are on the right track and will come to a successful conclusion in due course.

Last but not least, this CIML Meeting takes place at a crucial period in the life of the BIML - and therefore of the OIML as a whole: as you are of course aware, Mr. Magaña is taking over as Director of the BIML from Mr. Athané. On your behalf I have been carefully looking at the situation in order to be sure that this transition is happening in the best possible manner for the benefits of the OIML.

These are, my dear Colleagues, the most important topics that we will have to examine and/or decide upon during this meeting. For some of them I intend to say some introductory words on the occasion of this opening address. However, according to tradition, I would like to start with some words concerning our new Members.

As you know, during the past twelve months the number of OIML Member States has remained unchanged. Concerning the Corresponding Members, there were several changes with the accessions of Benin, Cambodia, Comores, Gabon, Malta and Uzbekistan, and the delisting of Colombia, Ecuador and Malawi, for not having paid their annual subscriptions over a number of years. Therefore, globally, the number of OIML Member States and Corresponding Members has slightly increased since our last meeting.

Concerning the composition of our Committee, a number of changes occurred with the appointment of the following new CIML Members:

- Mrs. Bennett, for Australia,

- Mr. Koreshkov, for Belarus,

- Mr. Lagauterie, for France,

- Mr. Chun Haeng Cho, for the Republic of Korea,

- Mr. Tanaka, for Japan.

It is my pleasure to welcome all these new CIML Members, amongst whom three had already attended our London meetings, and to thank them in advance for their participation in our work.

This week I received a letter from Mr. Li Chuanqing from the People's Republic of China announcing that he will have to leave the CIML because of changes in his responsibilities and that he will be replaced by Mr. Wang Qinping, Vice-Minister of AQSIQ. Furthermore I have been informed that at the end of the month, Mr. Bennett from the United Kingdom will also have to leave the CIML because of his appointment as Deputy Director of the NPL. After his departure, Mr. Birdseye will act as UK CIML Member until such time as an official decision is taken concerning this position. So may I take this opportunity to congratulate Mr. Li and

Mr. Bennett for their new responsibilities, and to thank them for the role they have played in the OIML and especially their outstanding role in the Presidential Council. It is of course with pleasure that I welcome the new Members, Mr. Wang and, for the time being at least, Mr. Birdseye and I wish them much success in their new role as Committee Members.

Slightly under a year ago the Eleventh Conference made a number of important decisions concerning the OIML Long Term Policy, technical activities, liaisons with other international and regional institutions, and of course the budget for the next four years and other financial matters. During our CIML Meeting all these points will be carefully examined under the various items of our agenda. I do not intend to elaborate on these immediately. I would just like to assure you that all your discussions and suggestions will be carefully examined by the Presidential Council and by the Bureau and will serve as a basis for directing - or even on some occasions re-directing - the relevant OIML activities. I may predict, for example, that the relationship between the OIML and certain European bodies will give rise to very interesting discussions. Please feel free to express your views and possibly your criticisms!

The situation within the BIML will also be covered by an item on our agenda and you will have the possibility to ask your questions on this occasion. Just as an introduction let me say that I have considered it to be of the highest priority for me to carefully monitor the transition between Mr. Athané and Mr. Magaña. I can report to you that I consider that Mr. Magaña has so far been able to devote most of his time to policy matters and to external liaisons. In parallel, Mr. Athané has continued to exercise his responsibilities as Director while making sure that his successor was informed step by step of all the aspects of the BIML life. I have multiplied the contacts with the BIML by e-mail or telephone, but also through frequent visits during which I had the opportunity to discuss either with

Messrs. Athané and Magaña together, or only with one of them and more particularly with Mr. Magaña in order to exchange with him views concerning the future developments of the OIML and its Bureau. I must say that I am fully satisfied with the way the transition is taking place but I will of course be ready to listen to your own views. The transition period will end tomorrow on the occasion of the OIML reception and on Thursday morning, for the closing session of our meeting, Mr. Magaña will sit at this table as the new BIML Director.

These are, my dear Colleagues, the introductory remarks that I wanted to make on this occasion. However, before closing my opening address, I think it is appropriate to look a little more towards the future. As you know, during the London CIML Meeting, I was reelected President of the CIML for a limited three year additional term. Therefore a new President will have to be elected on the occasion of the 38th CIML meeting, within two years' time. Such an election has to be prepared well in advance in order to identify possible candidates, to inform the CIML about these candidacies and to decide about the election procedure. As current CIML President I have of course a strong responsibility in preparing the election of my successor and I will ask the Presidential Council to assist me in this respect. It is clear however that you are all also deeply concerned and therefore I invite all those of you who may have proposals to offer to contact me privately before the 37th CIML meeting next year so that, during the meeting, I can already give some relevant information. Be sure that I will consider very seriously any suggestions I receive.

So, at the end of my opening address, may I ask the BIML Director to proceed with the roll-call of participants before we embark on the various items on our agenda.

Thank you for your attention, and may I wish you a very successful meeting.

![](page=23,bbox=[633, 1997, 1443, 2519])

<div align="center">

# Moscow, 25-27 September 2001

</div>

REPORT BY CHRIS PULHAM, BIML

The International Committee of Legal Metrology was convened by its President, Mr. Gerard Faber, and met from 25th through 27th September 2001 in the conference room of the Intourist Hotel, Moscow.

Opening addresses were given by Mr. Podufalov, on behalf of the Russian Government, Mr. Voronin, Chairman of Gosstandart and Gerard Faber, CIML President. These are printed in full in this Bulletin.

Forty-seven CIML Members were present or represented out of fifty-seven and it was established that the statutory quorum of three-quarters was therefore reached. Following the approval of the minutes of the 35th CIML Meeting (Item 1) Mr. Faber reviewed the decisions and resolutions of the Eleventh Conference (Item 2) and commented on the extent to which they were being implemented, or if not yet implemented then which actions the Committee still had to carry out, especially on the occasion of this 36th Meeting. The Committee expressed its satisfaction for the progress that had already been made.

The Committee then examined the 1999-2002 Action Plan and its extension to cover the period 2003-2004 (Item 3). Mr. Athaney recalled the process that had been followed to review the initial Action Plan and to consider extending it to cover the period 2003-2004 in line with the decision of the Eleventh Conference. This process had involved the Bureau, the Presidential Council and all CIML Members and had resulted in a final draft Action Plan being submitted to this 36th CIML Meeting for comments, together with a draft Resolution submitted for approval by the CIML. The Action Plan is published in this issue of the Bulletin, and constitutes the basis for OIML strategy in the coming years.

Since Mr. Faber had already given detailed information concerning membership in his opening address (see earlier), under Item 4 only brief additional points were brought up concerning the situation of certain OIML Members. However, Mr. Magaña reported that Malaysia and Vietnam had informed the Bureau that

they were considering upgrading their membership to Member State, but no final decisions had yet been made. Certain other Corresponding Members were also considering doing likewise but it was too early to give more detailed information at this stage.

It was also reported that unfortunately some countries were experiencing difficulties in paying their contributions, though the BIML is pleased to advise that at the time of writing this account, a large proportion of these outstanding contributions has been received. Two countries are still late in paying and payment deadlines were fixed in such a way as to grant adequate time for these Members to settle their accounts.

To summarize the discussions on financial matters (Item 5), the Committee adopted the Auditor's report for 2000; this document will be submitted to the Twelfth Conference. Mr. Athané reported that the financial situation of the Organization was globally quite healthy; the budget would be adhered to with no problem. Mr. Magaña spoke about the January 2002 changeover to the Euro and a new presentation of BIML accounts in order to better estimate the operational costs of the various bodies constituting the OIML and those of the various products and services provided by the Bureau (web site, publications, overheads, etc.). He explained that a new pricing policy concerning OIML publications and services would be implemented in January 2002 (see the separate booklet inserted in this edition) and that the BIML is currently working on a project to enable customers to purchase and download OIML publications directly via the web site, including credit card payment online.

Mr. Faber reminded participants that the role of the Presidential Council (Item 6) is to help the President prepare discussions at the CIML level, it being understood that the Council does not actually take any decisions by itself. In 2001, the Presidential Council met in February and then in September in order to review the output of the Eleventh Conference and $ 3 5^{\mathrm{th}} $ CIML meeting and to prepare the decisions which might be made during the $ 3 6^{\mathrm{th}} $ CIML Meeting. The composition of the Council is printed on the inside front cover of each Bulletin.

Introducing Item 7 BIML Staff, Mr. Athané reminded the participants that the BIML currently comprises ten members of staff including the new and the former Directors, two Assistant Directors, one Administrator, one Engineer, one Editor, two Secretaries and one Office clerk. A second Office clerk retired in August 2000 but has not yet been replaced in order to allow Mr. Magaña to reconsider the BIML staff situation globally and to possibly appoint an additional person if necessary.

Mr. Magaña added that he was currently considering the global missions of the BIML and would

draw conclusions concerning the BIML staff and its qualification following this 36th CIML Meeting. For the time being he had made no decision concerning the position which was vacant since August 2000. However, he was progressively re-qualifying the responsibilities of the two Secretaries in order to free up more of the technical staff's time to focus on more strategic tasks. He noted that there was also an increasing need for expertise in the field of computers and internet; a specific application example was to improve and modernize the OIML web site to cater for TC/SC forums and document exchanges. For the time being experts would be hired to carry out specific tasks over fixed periods of time before defining the permanent staffing needs of the Bureau.

Attila Szilvassy's contract as BIML Assistant Director was renewed for a period of five years from September 2002 - in fact by unanimous vote. Mr. Faber congratulated Mr. Szilvassy who expressed his gratitude to the Committee for its decision and affirmed his willingness to continue to serve the OIML in the best possible way.

Brief information was then given concerning the transition period between the two Directors - it was confirmed that the hand-over was perfectly orchestrated and that Mr. Athané would take on the role of Advisor to the Director from October 2001 through December 2002. A written report describing the BIML activities from October 2000 through September 2001 was then distributed; this report is published later in this edition.

A written report on Item 8 Technical activities prepared by the BIML was handed out and presented by Mr. Issaev, who reported an increase in the global volume of OIML technical activities compared with previous years. He evoked the situation of certain vacant TCs/SCs, those for which the number of

![](page=25,bbox=[103, 1924, 1009, 2520])

P-members was below the minimum specified by the Directives for the Technical Work, and finally those that were facing temporary difficulties in their work.

Mr. Szilvassy said that thirty-two committee drafts had been developed since October 2000, which was significantly more than during any other preceding years; in addition, a number of TCs/SCs had been reactivated over the past eighteen months. All these elements proved that the OIML technical activity was improving.

Other key points were:

- Priority and high priority projects have been identified and listed - this list was endorsed by the Committee and would be published and posted on the OIML web site;

- There is an urgent need to accelerate the work on the revision of D1 Law on Metrology and that of D11 Electronic Instruments;

- Papers should be developed on measurement uncertainty, software and the statistical methods to be used in legal metrology controls;

- It was most critical to find a Member State who would volunteer to undertake responsibility for TC13 Acoustics and Vibration owing in particular to the rapid progress in the development or revision of IEC Standards.

Mr. Szilvassy indicated that information on OIML activities was now systematically available on the OIML web site in the form of a database.

The Committee approved the following four draft Recommendations:

- Non-invasive sphygmomanometers. Part 1: Mechanical; Part 2: Automated (Revision of R 16);

- Liquid-in-glass thermometers (R 133);

- Water meters intended for the metering of cold potable water. Part 2: Test methods (R 49-2);

- Heat meters. Part 1: General requirements; Part 2: Pattern approval and initial verification tests (Revision of R 75).

Mr. Magaña explained that the Bureau was developing a number of information technology tools and activities with the aim of accelerating OIML technical work and facilitating Members' participation therein, for example by introducing the use of Internet-based discussion forums for TC/SC project work.

He also advised that BIML correspondence would soon be sent by e-mail, though parallel snail-mailing would continue for as long as necessary.

An increasing number of OIML Publications may already be downloaded from the OIML web site, especially all those connected with the Certificate System. Within a few months all OIML Publications will be

available as PDF files - the BIML has noted that additionally, an increasing number of customers request electronic versions rather than paper documents. To facilitate purchases of these publications, an online purchasing system using credit cards is being developed on the OIML web site.

Commenting on the possibility of using Internetbased video-conferencing, Mr. Magaña said that for the time being the Bureau was at a very experimental stage, using simple and inexpensive facilities for internal use only. Over time though, it may prove possible to use this kind of technology for online technical meetings.

Another idea put forward by Mr. Magaña would be for each TC/SC secretariat to use a web site from which the working papers would be available. Comments from members of the TC/SC would be sent to the site directly and would be immediately available to the secretariat and the other members.

Mr. Dunmill mentioned that the Directives for the Technical Work are being revised by the Bureau since the existing Directives had been in place since 1993 and many working methods had changed. The revision had also been made necessary by the output of the WTO/TBT Agreement, the changes in the relationship between TCs and connected SCs, and evolutions in the kind of papers developed by TCs/SCs. The various forms published at the end of the Directives would also soon be made available in electronic format to make their use easier by TCs/SCs (for example when preparing their annual reports) and to standardize their format. It was also necessary to take into consideration the changes that had occurred since 1993 in the corresponding ISO/IEC working methods while considerably simplifying these methods in order to make their implementation by OIML TCs/SCs easier.

Mr. Boudissa suggested that CD-ROMs could also be used by the Bureau as an alternative to the Internet for those countries that are not yet connected up to the net; Mr. Magaña agreed with this proposal.

A written report prepared by the BIML on the OIML Certificate System for Measuring Instruments (Item 9) was distributed and commented by Mr. Kochsiek. After outlining its history he gave information concerning developments over the last twelve months, including the interaction between the System and the Mutual Acceptance Arrangement. He also gave statistics concerning certificates already issued, categories of instruments to which the System applies, Issuing Authorities and Applicants. Finally, he explained that the paper describing the operational rules of the System was being revised, with a new version expected for mid 2002 following a postal consultation of CIML Members. The scope of the System would be enlarged in two directions: (i) the certification of types of modules and (ii) the certification of types of families (of instruments or of modules). These actions were also foreseen in the

Action Plan (published in this Bulletin). In addition the revision of the operational rules of the System would create a shift in responsibilities from the CIML Members to the Issuing Authorities, plus it will contain new provisions for the identification of the certified types. Mr. Ehrlich commented that certain points would probably be clarified when examining the state of progress of the MAA under item 10. However, it should be kept in mind that the MAA paper was a framework for the development of specific acceptance agreements that would remain of a non-binding nature to a large extent.

Mr. Szilvassy pointed out that a database of certificates had already been posted on the OIML web site and that it was possible to find information concerning all registered certificates, Applicants, Issuing Authorities and applicable Recommendations.

The Committee decided that two newly approved Recommendations (R16 Sphygmomanometers and R133 Liquid-in-glass thermometers) would become applicable within the System as soon as published.

Opening discussions on Item 10 Mutual Acceptance Arrangement (MAA) Mr. Ehrlich said that the advantage of the MAA will be to provide for a mechanism for examining testing laboratories at a deeper level than currently existed with the Certificate System. Only a summary of discussions is given in this Bulletin, since a more detailed account is published in the official Minutes of the Meeting which may be downloaded from the OIML web site.

As co-secretariat of OIML TC 3/SC 5 on conformity assessment, Mr. Ehrlich reviewed the progress of the work which had been ongoing for almost four years to develop an arrangement through which test data obtained in legal metrology testing laboratories in one OIML Member State would be accepted and used by responsible bodies in other OIML Member States, either towards the issuing of national type approval certificates in these other countries or at least towards obtaining some other authorization to market and sell the corresponding instruments in such countries. Such an arrangement would complement the OIML Certificate System and would benefit manufacturers of measuring instruments by eliminating the requirements for duplicative tests. He pointed out that the MAA would be an arrangement among issuing authorities or other national responsible bodies, not among governments, testing laboratories or CIML Members.

Mr. Ehrlich explained how it would be possible to implement the concept and obtain confidence among the participants in the competence of the various testing laboratories without incurring excessive costs and without creating "clubs" that would exclude certain countries. To this end the 8 CD had been supplemented by a checklist (currently at the stage of 2 CD) intended for issuing authorities and testing laboratories carrying

out OIML type evaluations. The MAA would serve as the framework for developing a set of signed documents each being referred to as "declaration of mutual confidence" for a given category of measuring instruments covered by an OIML Recommendation implemented within the OIML Certificate System. As already mentioned the signature of a declaration of mutual confidence would not create any binding obligation with the exception that once a participant had accepted the test data, these data would have the same legal value as if they emanated from the participant's test laboratories.

The process would include notifying the BIML of the interest of a given country in signing a declaration for a particular type of instrument. The BIML would then notify all CIML Members. An ad-hoc committee on participation review (with the BIML as secretariat) would coordinate the assessment of participating testing laboratories and prepare a report discussing the evaluation of the competences of those laboratories. The BIML would also facilitate the operation of the system including the processing of possible appeals. This committee would be comprised of experts appointed by and representing issuing authorities or national responsible bodies.

Mrs. Bennett said that Australia was strongly in support of the objective of achieving general agreement amongst OIML issuing authorities for the mutual acceptance of test data and appreciated the work developed under the US secretariat. Australia had decided to proceed with bilateral agreements with certain of its trading partners, including the Netherlands and the United Kingdom; Mr. Ehrlich noted that bilateral agreements could indeed facilitate the development of the OIML MAA.

Mr. Kildal asked for information concerning the degree of cooperation with ILAC and whether a parallel cooperation with IAF already existed or would exist in the future. In fact IAF was establishing an international MRA on product certification which could help the OIML in establishing a system that would be less costly if it benefited from the IAF system.

Mr. Ehrlich replied that there was no direct cooperation between TC 3/SC 5 and ILAC and that no direct interaction of ILAC or IAF in the operation of the OIML MAA was anticipated. Mr. Kildal asked whether or not the implementation of the system would create extra costs for the BIML and therefore for the OIML Member States.

Mr. Ehrlich admitted that there would be extra costs for the BIML, but that these would be more or less independent from the solution chosen for competence assessment. Mr. Bennett expressed his appreciation for the progress made in the $ 8^{\mathrm{th}} $ draft compared with the previous one.

Mr. Vaucher said that he was still convinced that the MAA was necessary and urgent. He also appreciated the fact that it was drafted in a much simpler way than before, which would facilitate its implementation at reasonable costs without preventing any country from participating. He also suggested that the scope of the draft should be enlarged so that not only the test reports should be recognized but also the evaluation of these test reports, i.e. the OIML certificates or declarations of conformity.

Mr. Boudissa recognized that the proposed system would save a lot of time and money and facilitate commercial transactions amongst countries by avoiding overheads and duplication of tests. However, from the point of view of developing countries there were problems since the system would be accessible only for those countries that possess the necessary test resources and checking facilities as well as technological expertise. In developing countries these facilities and this knowledge did not yet exist, which could prevent them from participating in the system. He therefore suggested that the OIML could organize training seminars on all the aspects linked with mutual acceptance so that the future participation of these countries in the system would be positive.

Mr. Ehrlich appreciated this proposal and suggested Mr. Boudissa might like to express his view in a written form for easier examination by TC 3/SC 5.

Mr. Sinyangwe said that the topic was very interesting for developing countries that do not manufacture measuring instruments (and therefore do not issue OIML certificates) but that have to import such instruments from industrialized countries. He asked how these developing countries might fit into the system.

Mr. Ehrlich replied that in his opinion the MAA would be most useful for those countries that possess test facilities. Therefore developing countries having no facilities to evaluate test data should limit themselves to the acceptance of OIML certificates. However there could be an educational role, for example through the participation in the evaluation committee.

Mr. Magaña noted that while the MAA contained a mechanism to build confidence between signatories it would also increase confidence in certificates. Therefore a country that had no facilities to issue certificates could nevertheless declare its confidence in the certificates issued by other countries. This would be a kind of "unilateral" declaration.

Concerning the issue of legal liability, Mr. Birch noted that the issuing authorities would assume legal liability for the test data they receive; in the case of declarations of mutual confidence the CIML Members, when signing, would assume legal liability for the issuing authorities.

To conclude this discussion, Mr. Faber thanked Mr. Ehrlich and TC 3/SC 5 for the work that had been

accomplished. He also said that he was convinced of the need to rapidly develop the MAA since the acceptance of test data was an obvious necessity.

Mr. Ehrlich introduced Item 11 IQ mark for prepackaged goods with a general review of the status of revision of R 87 Net content of packages which initially contained an annex proposing the establishment of an IQ mark. Many comments had been received from TC 6 members concerning the $ 2^{\mathrm{nd}} $ committee draft revision of R 87 and, based on these comments, a $ 3^{\mathrm{rd}} $ draft was expected to be distributed by December 2002.

The Presidential Council of February 2001 had decided that the IQ mark itself should no longer be a part of R 87 but rather an independent paper which should specify the requirements to be met by packers to have the packages they produced certified for conformity with R 87. This work would start (initially at the level of a small working group of the Presidential Council) when the revision of R 87 is completed.

Mr. Zhagora pointed out that "IQ" was already used as the abbreviation for "intelligence quotient". Mr. Ehrlich said that he would examine whether this may create any confusion and if so he would try to find another abbreviation for the OIML mark.

Mr. Birch said that he was disappointed by the delay in establishing the IQ mark since it would respond to a clear demand from manufacturers. He asked to what extent industry had been requested to comment on the draft in addition to national legal authorities, but Mr. Ehrlich replied that as far as he knew comments received were only from CIML Members; he did not know to which extent these CIML Members had consulted their national manufacturers.

Mrs. Annabi then reported on Item 12 Development Council meeting and Mr. Faber gave an account of the RLMO meeting - both these summaries are published separately.

Under Item 13 reports were given on Liaisons with international and regional institutions.

Meter Convention/ILAC/OIML. Mr. Faber evoked the joint meeting that had been held at the BIML in February 2001, with 14 persons representing the three organizations. The activities carried out within each organization and within the Joint Committee for Guides in Metrology over the last twelve months were reviewed with a view to identifying those that might influence, or be influenced by, the activities of one or the two other organizations: CIPM MRA, ILAC MRA, CIPM/ILAC MoU, OIML MAA, accreditation of laboratories that perform legal metrology evaluations and tests, development of a model law of metrology (for which a joint working group was established), assistance to developing countries in the establishment of sound metrology, legal metrology and accreditation bodies (identified as a priority action for which ILAC and the OIML would establish a joint working group with, in the future, a

participation expected from the BIPM), organization of an international seminar to follow up the 1998 Braunschweig seminar, coordinated input to ISO 17011 in order to make this standard acceptable to national metrology institutes. It was finally decided that the next Meter Convention/ILAC/OIML meeting would be held at the BIPM in February 2002.

WTO. Mr. Magaña mentioned the numerous contacts with the WTO/TBT Committee which included active participation in meetings, including the seminars on the occasion of which the "international standardsetting organizations" explain their objectives, demonstrate how they fulfill the relevant WTO rules and develop mutual information; in addition special attention was drawn to developing countries in order to facilitate their participation in the preparation of international standards. There had also been more recent and specific cooperation in the assistance to developing countries in the field of metrology and legal metrology, with a regional seminar held in Paris at the end of 2000 and a paper being prepared for the attention of the WTO which seemed to be now quite conscious of the role of metrology in trade and willing to support the OIML initiatives with a view to promoting metrology with various international and regional funding bodies.

European Union bodies. Mr. Magaña reminded the participants that at the 35th CIML Meeting information had been given concerning the development of the MID and what was envisaged at that time as "OIML Normative Documents" to give presumption of conformity with the essential requirements of the MID Since then, EU Commission Representatives had clearly indicated that such presumption would be given by the OIML Recommendations themselves without any need for additional papers to be drawn up by the OIML.

Concerning CEN and CENELEC, Mr. Magaña explained that contacts resulted from the fact that the MID provided for two kinds of presumption of conformity: OIML Recommendations and European

![](page=28,bbox=[972, 1928, 1880, 2520])

harmonized standards to be developed by CEN/CENELEC following mandates delivered by the EU Commission. It was therefore appropriate to ensure that this would not result in too much competition between the OIML and CEN/CENELEC.

Mr. Faber confirmed that the Presidential Council had examined to what extent the OIML, as an international legal metrology body, should pay attention to the activity of regional standardization bodies and what the role of the Bureau should be in this connection.

As a general rule for the future, a distinction should be made between two types of agreements: (i) agreements limited to exchange of information, which should be concluded by the directors/general secretaries of both organizations without the need to consult the CIML, and (ii) agreements containing more than a simple exchange of information, which should discussed and approved by the CIML. A policy paper governing liaisons between the OIML and other international and regional bodies would be drawn in time for the next CIML Meeting.

Both Mr. Kildal and Mr. Vaucher expressed their appreciation for the BIML's role in promoting the implementation of OIML Recommendations at the European level. It was the responsibility of the OIML to harmonize metrological and technical requirements and it was therefore in its interest to have OIML Recommendations recognized by the European Union; at the same time this would avoid other organizations developing standards containing perhaps conflicting requirements which would then have to be harmonized.

Mr. Magaña commented that the OIML was facing a kind of challenge in so far as in the field of standardization, the prevailing standard was the one that was developed most rapidly. The OIML had to accelerate its working methods in order to develop or revise its Recommendations more rapidly.

![](page=29,bbox=[103, 1924, 1008, 2518])

Moving on to the next item on the agenda, both Mr. John Birch and Mr. Bernard Athané were appointed CIML Honorary Members under Item 14. Mr. Faber commented that Mr. Birch had for a long time been an outstanding CIML and Presidential Council Member and he had proved his ability to participate very actively in practically all discussions, whatever the subject. He had also demonstrated to the Committee and to the Council that it was necessary to think not only along technical lines but also in terms of strategy and policy.

Mr. Faber also congratulated Mr. Athané for his contribution to the development of metrological science and his action as BIML Director, and a reception was given by the OIML on Thursday 27 September evening during which Mr. Athan'e's nomination was celebrated.

The question of future CIML meetings was discussed under Item 15. The Committee decided to hold its 37th Meeting in France around late September or early October 2002, organized by the BIML under the supervision of the CIML President and his Council. Then Mr. Tanaka officially invited the Committee to hold its 38th Meeting in Kyoto in 2003, on the occasion of the centenary of the establishment of the Japanese legal metrology institute. The Committee expressed its gratitude to Mr. Tanaka for this invitation which it accepted in principle, noting that a final decision would have to be taken during the 37th Meeting. In addition to the longstanding Israeli invitation, an invitation had also been received from Germany concerning the 39th CIML Meeting to be held in connection with the Twelfth Conference in 2004. The Committee decided to consider the Israeli invitation as the first option and the German one as the second option, the final decision having to be made in 2002.

Under Item 16 Other matters Mr. Magaia gave information concerning the proposed lectures he had received for the workshop Legal metrology in 2020. There was however not sufficient time to organize this workshop in February 2002 as initially planned. He therefore proposed that the workshop should be held in September or October 2002 in connection with the 37th CIML Meeting. The Committee agreed with this proposal and Mr. Magaia added that there was still time to put forward additional lectures and that the Presidential Council would make the final selection from amongst all those submitted.

The decisions and resolutions (Item 17) were adopted by the Committee during its last session on Thursday 27 September. As this was the first time that Mr. Magaña was participating as BIML Director, Mr. Faber expressed his strong support and wishes for a successful carrier in his new role. He also reiterated his words of thanks to Mr. Athané for his longstanding management of the BIML.

Mr. Magaña thanked Mr. Faber and all CIML Members for their confidence, and expressed his

recognition to Mr. Athané and to the three other BIML staff members present for their assistance and support.

In closing the meeting, Mr. Faber expressed his most sincere thanks to the Russian Hosts, to the two Directors and BIML Staff, and the two CIML VicePresidents and all Members of the Presidential Council for their help. He also thanked the team of interpreters and last but not least all the participants in the $ 36^{\mathrm{th}} $ CIML Meeting, including Observers from Corresponding Members and RLMOs and especially CIML Members for their fruitful participation in discussions and decisions making.

To conclude Mr. Faber invited all CIML Members to meet again in France next year.

Mr. Issaev, on behalf of the Russian Authorities, expressed his pleasure for having hosted this CIML Meeting and invited the participants to the technical and other visits for which they had registered.

## Meeting of Regional Legal Metrology Organizations

The RLMO meeting was organized in connection with, but not as a part of, the 36th CIML Meeting. The complete report of the RLMO meeting is attached to the Minutes of the 36th CIML Meeting. The conclusions of the RLMO meeting were presented to the Committee which, after some minor amendments, considered them as an acceptable basis for the development of an OIML policy paper. The final conclusions are as follows:

## Exchange of information concerning RLMOs

Each RLMO presented the main aspects of its activities. The following issues were highlighted:

- Need to improve the mutual information and coordination between the RLMOs concerning the development of training materials.

- Need to identify those skills and facilities which are present in only a few countries.

- Interest in trying to associate consumers in the work of RLMOs.

- Need to make funding organizations aware of the work of RLMOs.

- Need that each OIML Member be a member of at least one RLMO.

## Participation of RLMOs in OIML work

- How could the RLMOs associate non OIML Members in OIML technical work?

- How should the specific needs of a region be represented and taken into account in the work of TCs/SCs?

- It was concluded that RLMOs might be - and should be listed as organizations in liaison in the different TCs/SCs which would allow their needs to be expressed as such and not only as comments from one country, and would give them the possibility to be represented by a non-OIML member should they so wish.

- It was also concluded that RLMOs could facilitate the implementation of OIML Recommendations and should

probably play an important role in the implementation of the future MAAs.

## Relations between RLMOs

- It was noted that there was a strong need to improve communication between the RLMOs in order to coordinate actions, avoid duplication of work, avoid deviations in the interpretation of OIML Recommendations and share experience.

- A meeting should be organized each year with the Chairpersons and/or nominated representatives of the RLMOs, the CIML President, the Chairperson of the Development Council and the BIML Director acting as facilitator.

- The BIML should distribute all relevant information among the different RLMOs and provide means for facilitating mutual information.

## Relations between RLMOs and the Development Council

- The RLMOs and the Development Council should have close interconnections in order to avoid overlapping of work (in particular in the field of training) and to ensure good coordination and complementarity of the actions carried out.

## RLMOs and training issues

- This matter had already been dealt with in connection with the various items above.

## Conclusion

- The BIML was instructed to prepare a policy paper concerning the position of RLMOs in the OIML, this paper being examined by the CIML President and the Presidential Council in time for the next CIML Meeting.

Réunion du Conseil de Développement

Réunion des RLMO

36ème Réunion du CIML

Moscou (Fédération de Russie)

24-27 septembre 2001

À l'invitation du Gouvernement de la Fédération de Russie, trois réunions se sont tenues à l'Hôtel Intourist, situé dans le centre de Moscou.

![](page=1,bbox=[987, 577, 1730, 1667])

Le Conseil de Développement de l'OIML s'est réuni pendant une journée complète le lundi 24 septembre,

Une réunion des Organisations Régionales de Métrologie Légale s'est tenue durant la matinée du mardi 25 septembre, et

Le Comité International de Métrologie Légale a tenu sa Trente-sixième Réunion du 25 au 27 septembre.

MOSCOU 2001

<div align="center">

# Conseil de Développement

</div>

<div align="center">

# 24 septembre 2001

</div>

COMPTE RENDU PAR CHRIS PULHAM, BIML TRADUCTION PAR LAURENCE LICHTIG

Le Conseil de Développement de l'OIML s'est réuni le lundi 24 septembre 2001 à l'Intourist Hotel. Un résumé de la réunion est publié dans ce numéro du Bulletin, et un compte rendu complet sera publié séparément.

## Rapport et discussion sur les activités entreprises depuis la réunion de 2000 (Point 1)

Un rapport rédigé par le BIML est distribué (reproduit en entier ci-après dans cet article).

La discussion s'engage ensuite sur les événements qui ont eu lieu l'année précédente. M. Magaña demande aux personnes qui ont donné des détails sur des cours de formation et qui se sont portées volontaires en tant qu'experts dans le domaine de l'enseignement de la métrologie, d'envoyer au BIML toutes les informations afférentes pour leur mise à jour sur le site web.

M. Magaña commente le point 4 de ce rapport en disant que l'objectif est d'identifier les obstacles et les difficultés que rencontre les pays en développement dans la mise en application des normes, par exemple les contraintes budgétaires, les difficultés linguistiques, etc.

M. Birch suggère qu'une étude soit entreprise pour déterminer quelles normes sont applicables aux pays en développement, en commençant par identifier à la fois les produits dont ils ont besoin et l'étendue des exigences locales avant que ces pays ne tentent de satisfaire à ces exigences.

M. Magaña explique que l'ISO travaille maintenant presque exclusivement sur des documents électroniques, l'avantage étant que ce moyen de communication moderne peut accélérer l'activité de normalisation et coûte bien moins cher que les voyages internationaux, mais dit aussi qu'il est conscient du fait que l'accès à l'Internet n'est pas encore possible dans tous les pays du monde. Cette question est également soulevée au sujet

## Ordre du jour

Participation

Ouverture

Appel des Délégués

Approbation de l’ordre du jour

1 Rapport et discussion sur les activités entreprises depuis

la réunion du Conseil de Développement de 2000

(Londres, Royaume-Uni)

1.1 Réunion de l’OMC sur la participation des pays en développement

aux activités de normalisation

2 Rapports des Groupes de Travail

2.1 WG 1 – Formation

2.2 WG 2 – Informations

2.3 WG 3 – Équipement

2.4 Discussion des termes de référence pour les Groupes de Travail

3 Rapports des représentants des Organisations Régionales

de Métrologie Légale

3.1 Forum de Métrologie Légale de l’Asie-Pacifique (APLMF)

3.2 Coopération du Sud-Est de l’Europe en Qualité, Normalisation,

Accréditation et Métrologie

3.3 Coopération Euro-Asiatique des Instituts Nationaux de Métrologie

(COOMET)

3.4 Forum Euro-Méditerranéen de Métrologie Légale (EMLMF)

3.5 Forum de Métrologie Légale de l’Océan Indien (IOLMF)

3.6 Coopération en Métrologie Légale de la Communauté

Sud-Africaine de Développement (SADCMEL)

3.7 Système de Métrologie Inter-Américain (SIM) –

Groupe de Travail de Métrologie Légale

3.8 Coopération Européenne en Métrologie Légale (WELMEC)

4 Proposition pour le programme de travail 2002–2003

5 Informations sur les projets en cours

5.1 ONUDI – OIML – PTB

6 Informations sur les activités spéciales des Membres

7 Autres questions

8 Prochaine réunion

9 Conclusion et clôture de la réunion

du travail des TC/SC de l'OIML et sera examinée par le BIML dans les mois à venir. M. Boudissa pense qu'il faudra peut-être attendre trois à cinq ans pour que chaque pays ait accès à l'Internet. Il suggère par conséquent que pour le moment, les documents papiers soient encore utilisés. M. Magaña approuve cette intervention et confirme que le CIML examinera ce point plus en détail au cours de sa réunion qui se tiendra plus tard dans la semaine.

Sur la question du financement, M. Boudissa demande si des progrès ont été accomplis. M. Dunmill informe les participants que la réunion avec la Banque Mondiale prévue pour le 13 septembre a dû être reportée, mais qu'une nouvelle date sera fixée dès que possible; il confirme que la Banque Mondiale s'intéresse aux activités de normalisation et de métrologie. M. Magaña rappelle que le projet de financement de la Banque Mondiale est prometeur et M. Hocine (Algérie) informe les participants qu'il a déjà rendu visite à la Banque Mondiale en avril et confirme que les discussions qui ont eu lieu étaient très encourageantes et positives.

M. Dunmill fait remarquer que la Commission Européenne s'intéresse aussi aux activités de normalisation, mais pas autant à la métrologie - l'un des rôles clés du Conseil de Développement serait par conséquent d'augmenter l'intérêt de la Commission Européenne pour la métrologie. Le Conseil de Développement entretient également des contacts réguliers avec I'ONUDI, et les discussions progressent.

Un sujet important pour le Conseil de Développement est la progression du travail sur le D1 de l'OIML Loi de Métrologie. M. Klenovský demande où en est le travail et quel serait l'impact de BIPM/ILAC sur la progression de ce Document. M. Magaña répond que le TC 3 OIML va examiner ce Projet, ce qui est confirmé par M. Ehrlich.

M. Dunmill confirme que l'on peut constater une augmentation de l'intérêt général pour la métrologie dans le monde, commentaire repris par M. Birch, qui ajoute que la mise en place de services de métrologie légale dans les pays en développement devrait être une priorité.

## Rapports des Groupes de Travail (Point 2)

Sur le sujet de la Formation (WG 1), Dr. Wallerus confirme que la révision de OIML D 14 est une priorité. Il rapporte qu'il a transformé le D 14 en tableau de cinq colonnes comprenant des commentaires rédactionnels, de nouveaux objectifs, des tâches nouvelles pour les

fonctionnaires chargés de la vérification, le temps nécessaire à l'accomplissement de ces tâches, des références aux documents existants, etc. Il attend de nouvelles propositions qui seront toutes intégrées dans le nouveau Projet.

Un Délégué russe résume l'histoire du D 14 et suggère une reconnaissance des différents niveaux de formation, y compris la formation en matière de logiciels et la nécessité de faire la différence entre les diverses catégories de personnels enseignant la métrologie légale, et encourage le développement de la formation professionnelle. Il pense que le D 14 est une bonne base que la Fédération de Russie a utilisée pour former du personnel de métrologie légale et pour des opérations de vérification. Il s'enquiert de la formation de personnel accrédité et certifié, qui selon lui devrait être incluse.

M. Birch répond que le développement de la compétence et de la cohérence n'est pas nécessairement inherent aux publications de l'OIML, mais que le développement de la compétence augmente la cohérence. Il s'interroge sur la possibilité d'accréditer des instituts de formation aux exigences essentielles et pense que la compétence et la formation aideraient le système global de mesure. Il explique aussi que les langues utilisées pour la formation constituent un problème général et que les langues locales devraient toujours être utilisées autant que possible pour surmonter cet obstacle.

M. Vichenkov fait ensuite le résumé du travail entrepris par le Groupe de Travail 2 Informations depuis un an. WG 2 a été créé en 2000, et un questionnaire a été diffusé par le BIML. Les résultats de ce questionnaire ont été communiqués à Londres et ont montré qu'un certain nombre de pays ont besoin d'informations sur la métrologie, en particulier la Loi de métrologie, la surveillance et le contrôle métrologiques. Nombreux sont ceux qui ont exprimé leur préoccupation concernant des bases de données informatisées. Par exemple le VNIIMS a une certaine expérience de l'utilisation de bases de données et offre de rendre sa propre structure disponible comme base après traduction dans d'autres langues. Un forum pourrait être créé pour proposer d'autres idées au WG 2.

Onze États Membres de l'OIML participent au WG 2. Divers questionnaires et enquêtes ont déjà été envoyés dans le but de préparer des documents d'aide technique et des centres d'information dans le monde entier. M. Vichenkov suggère l'idée de créer un catalogue des instruments de mesure existants ayant déjà reçu des certificats OIML. De tels instruments sont largement utilisés dans les pays en développement. Un catalogue pourrait indiquer la traçabilité à des étalons de référence y compris des étalons internationaux et

## Groupes de Travail du Conseil de Développement de l'OIML - Termes de Référence

## WG 1 Formation (Allemagne)

Termes de référence:

- Réexamen du Document International D 14 Formation du personnel de métrologie légale, qui a été publié en 1989 et qui est actuellement révision pour s'assurer que des modules de formation uniformes sont utilisés et que la compétence des organismes de formation est assurée;

- Développement d'un système de modules de formation utilisant le travail existant;

- Coopération avec les organismes régionaux, en particulier le Forum de Métrologie Légale de l'Asie-Pacifique; et

- Informations mutuelles sur les cours prévus, y compris l'échange de matériel d'enseignement et d'expérience afin d'assurer une qualité identique de formation.

## WG 2 Informations (Fédération de Russie)

Termes de référence:

- Identifier les besoins spécifiques et les exigences des pays en développement et dans le domaine de l'information, de la documentation sur la métrologie légale et dans les domaines connexes (tels que les essais, la certification, la gestion de la qualité, l'accréditation, etc.);

- Aider les pays en développement à formuler ces besoins;

- Organiser un forum pour l'échange de connaissances, d'informations et de documentation; et

- Conseiller le Conseil de Développement sur la politique à adopter concernant ces problèmes.

## WG 3 Équipement (Fédération de Russie)

Termes de référence:

- Étudier les besoins des pays en développement dans les domaines de

- l'organisation et l'équipement de laboratoires de métrologie,

- la comparaison et la vérification des étalons nationaux de mesure;

- Fournir des conseils et des informations aux services de métrologie nationale concernant des fournisseurs potentiels d'équipement métrologique et maintainir une base de données sur ce sujet;

- Examiner les propositions relatives à l'équipement métrologique sujet aux projets d'aide dans les organisations nationales et régionales concernées;

- Préparer des informations concernant l'équipement métrologique.

M. Vichenkov pense que ce travail pourrait contribuer à une meilleure reconnaissance des certificats OIML et par là diminuer les barrières techniques au commerce.

M. Magaña pense qu'il serait avantageux de faire circuler des informations sur de telles études de région à région. Par exemple la région Asie-Pacifique a organisé une étude sur l'humidité des céréales avec l'Allemagne. Si ces informations étaient publiées, il est fort possible qu'elles pourraient aider d'autres régions et certains pays individuels.

Deuxièmement, M. Magaña signale que les pays en développement ont souvent besoin d'informations sur les approbations de modèles existant dans d'autres pays; ces pays peuvent être intéressés par les réactions de pays en développement à certains instruments arrivant chez eux. Le BIML pourrait aider à l'échange de telles informations mais cette action devrait être engagée par les États Membres.

M. Vichenkov propose d'écrire au BIML pour soumettre des idées au moment où de nouvelles propositions seraient faites.

Sur le sujet des bases de données, M. Vaucher explique que METAS est en train de mettre au point une base de données de documents normatifs, de catalogues d'instruments approuvés, d'exigences légales, etc. Ces bases de données devraient être opérationnelles en décembre 2002. Il pense qu'il est important d'échanger des informations entre les divers acteurs de la métrologie légale. Il approuve l'idée d'un forum qui serait un bon moyen de transmission des informations et invite M. Vichenkov à utiliser le forum METAS.

Mme Annabi suggère que MM. Vichenkov et Vaucher puissent envisager de travailler ensemble en étroite coopération pour harmoniser de telles informations.

M. Ragulin fait un rapport sur WG 3 Équipement, en disant que l'équipement devrait être choisi par ordre de priorité, selon les besoins locaux spécifiques. Un questionnaire a été rédigé et sera distribué une fois traduit, et un ouvrage de 85 pages présente des recommandations sur le choix, l'assemblage et l'installation d'instruments de mesure.

Tout le monde est d'accord sur le fait que des propositions supplémentaires sont nécessaires pour définir des besoins en équipements.

M. Magaña passe en revue les objectifs et les termes de référence actuels du Groupe de Travail (voir encart), et sous le Point 3 de très brefs rapports sont effectués par les représentants d'Organisations Régionales de Métrologie Légale.

L'APLMF identifie l'information, la formation et les ateliers comme points clés ainsi que l'harmonisation de la législation et de l'administration.

COOMET suggère que les RLMO contribuent au développement et à la mise en place des Recommandations et des Documents de l'OIML.

SADCMEL possède un Comité Technique actif qui étudie la question de la formation, l'objectif étant de promouvoir le commerce dans la région, et organiser des cours locaux de "formation des formateurs".

Au Point 4 Proposition pour le programme de travail pour 2002-2003, les points clés sont:

- Travailler avec les organisations en liaison pour assurer le financement des pays en développement (par exemple la Banque Mondiale, la Commission Européenne, l'ONUDI et le groupe de l'OMC sur l'accès des pays en développement aux organisations de normalisation);

- S'assurer que le travail des TC/SC OIML est suivi par le Conseil de Développement dans tous les domaines qui le concernent;

- Mettre régulièrement à jour le site web du Conseil de Développement de l'OIML, y compris les cours de formation et les listes d'experts;

- Établir des liens avec les organisations qui proposent des formations; et

- Traduire en espagnol le site web du Conseil de Développement.

Au Point 5.1, coopération ONUDI/OIML/PTB, les participants sont informés que des fonds ont été obtenus en 2001 pour financer les activités de pays d'Afrique occidentale.

M. Magaña et M. Dunmill font un résumé des conclusions du Conseil de Développement comme suit.

## Conclusions de la réunion (Point 9)

Suite aux discussions qui se sont tenues pendant la réunion du Conseil de Développement lundi 24 septembre 2001 les recommandations suivantes sont adoptées en vue d'une réflexion et d'une action future:

1 Le Conseil revoit les termes de référence des Groupes de Travail et recommande au BIML de consulter les membres du Conseil de Développement pour mettre à jour leur composition.

- La Suisse fera part de son expérience à la Russie pour les tâches du WG2 Informations.

- Le Conseil demande à la Présidente du Conseil de Développement et au BIML de suivre les progrès des 3 WG, qui sont invités à prendre contact les uns avec les autres.

- Chaque WG est invité à organiser une réunion avant la prochaine réunion du Conseil de Développement.

2 Il est demandé aux WG de prendre en compte le travail des RLMO concernant la formation, l'information et l'équipement afin d'éviter tout chevauchement dans leurs programmes.

3 Le Conseil demande à sa Présidente de prendre contact avec divers organismes qui soient en mesure de financer les activités de métrologie légale dans les pays en développement, notamment la Banque Mondiale, la Commission Européenne et la Banque de Développement Islamique.

4 Le Conseil recommande à sa Présidente et au BIML de continuer à travailler avec l'Organisation Mondiale du Commerce et l'ONUDI sur des projets concernant la métrologie légale.

5 Le Conseil demande aux RLMO de désigner leurs représentants pour former un "Comité de réflexion" du Conseil de Développement. Quand aucun représentant n'est désigné, il sera admis que la RLMO est représentée par son Président.

6 Le Conseil demande à sa Présidente et au BIML d'aider les pays en développement à participer au travail des TC et SC .

7 Le Conseil demande aux Membres du CIML d'envoyer au BIML des informations récentes pour mettre à jour régulièrement le site web de l'OIML concernant les experts et la formation.

8 Le Conseil demande au BIML de continuer à développer le site web.

9 Le Conseil souligne l'importance de s'assurer que les pays en développement ont un accès facile à l'Internet (et par conséquent l'e-mail et les technologies informatiques associées).

<div align="center">

# Conseil de Développement OIML

Rapport du Programme de Travail

</div>

Le texte en couleur et en retrait au début de chaque section est extrait des propositions faites lors de la dernière réunion du Conseil de Développement qui s'est tenue à Londres le 11 octobre 2000.

## 1 Travail technique

"Le Conseil de Développement devrait continuer à participer activement à la révision de D 1 Loi de Métrologie et maintainir et augmenter l'intérêt qu'il porte à certains Comités Techniques et Sous-Comités de sorte que les intérêts des pays en développement soient pris en compte. La liste des projets de première priorité que le BIML a préparée pourrait être utilisée pour étabir des priorités pour le Conseil de Développement."

Le secrétariat des US du TC 3 a envoyé au BIML le 2 février 2001 une proposition de document de travail pour une "Loi de Métrologie". Ce document a été discuté lors de la réunion commune OIML/BIPM/ILAC qui s'est tenue au BIML le 21 février 2001 et un groupe de travail commun a été mis en place pour avancer le travail sur le document. L'OIML est représenté par Jean-François Magaña, Ghaïet-El-Mouna Annabi et Charles Ehrlich.

## Actions:

- Un document de travail révisé est actuellement examiné par le groupe de travail commun avant d'être diffusé au sein de TC 3.

- Le document de travail sera ensuite examiné pour voir s'il répond aux besoins identifiés pour les pays en développement, en particulier à la lumière du projet ONUDI-OIML-PTB (voir 6 ci-dessous).

- Après examen de la liste des projets de première priorité et de priorité établis par le BIML, il a été décidé que le Conseil de Développement porterait un intérêt particulier au travail des TC/SC suivants:

- TC3 Contrôle métrologique;

- TC 6 Produits préemballés;

- TC 7/SC 4 Instruments de mesure pour la circulation routière;

- TC 9/SC 3 Poids;

- TC 11/SC 1 Thermomètres à résistance;

- TC 12 Instruments de mesure des grandeurs électriques;

- TC 16/SC1 Pollution de l'air;

- TC 16/SC 3 Pesticides et autres substances polluantes toxiques.

## 2 Site web

"Celui-ci pourrait être amélioré cette année et on espère qu'une version espagnole sera bientôt disponible. M. Dunmill demande aux délégués de l'aider en mettant régulièrement à jour les informations sur les experts et les cours de formation."

La partie du site web de l'OIML qui concerne le Conseil de Développement a été complètement révisée. Les noms de tous les experts en métrologie proposés sont maintainant disponibles sur une base de données sur le site et peuvent être recherchés par langue parlée, par région ou par sujet. Tous les cours de formation signalés au BIML sont maintainant également présents sur le site, classés également par langue parlée, par sujet ou par pays.

## Actions:

- Les listes de formations et d'experts ont été transférées vers un système de bases de données sur le site web pour faciliter la recherche d'informations;

- Le BIML projette de fournir une page de liens avec les établissements de formation afin de fournir plus d'informations mises à jour sur les cours de formation disponibles;

- Le site sera traduit en espagnol dès que possible, afin de rendre plus largement accessible l'information sur le Conseil de Développement;

- Le BIML fera des efforts réguliers pour s'assurer que les informations sur les experts et les cours de formation soient tenues à jour.

## 3 Cours de formation

"Le Conseil de Développement doit examiner les possibilités d'une "validation" des cours de formation".

Pour le moment, les détails des cours de formation recommandés par les Membres du CIML seront placés dans une base de données accessible par le site web du Conseil de Développement. Ce n'est pas le rôle de l'OIML de "valider" les cours, bien que l'utilisation de systèmes externes d'accréditation serait utile.

## 4 Liaisons externes et financement

"M. Dunmill explique que des contacts utiles ont été pris l'année dernière, mais que d'autres points du programme de travail ont dû être mis en place avant que le financement d'un projet spécifique soit obtenu. Il est donc à espérer que ces activités se poursuivent pendant l'année à venir".

Des contacts utiles ont été pris l'année dernière avec la Banque Mondiale et avec la Commission Économique des Nations Unies pour l'Afrique, ce qui devrait être poursuivi cette année.

De plus, les possibilités de coopération plus étroite avec, par exemple, ISO DEVCO et le BIPM pourraient être examinées. L'OMC a également lancé une série de réunions informelles sur le sujet de la participation des pays en développement dans les activités de normalisation. La première réunion, qui s'est tenue le 23 janvier 2001, a été très utile et pourrait conduire à des développements intéressants, en particulier dans le domaine du financement.

## Actions:

- Le BIML va poursuivre les contacts existants et en établir d'autres, là où c'est possible, avec des organisations d'intérêt pour le Conseil de Développement.

- Le BIML a fourni des informations à l'OMC suite à la réunion du 23 janvier 2001, et continuera à participer activement à cette initiative. Une autre réunion pourra se tenir avant la fin de l'année.

- Une réunion avec la Banque Mondiale avait été prévue le 13 septembre, mais a dû être annulée. Des efforts pour organiser des réunions avec la Banque Mondiale et la Commission Européenne seront poursuivis.

## 5 Groupes de Travail

Les trois Groupes de Travail sur la Formation (Allemagne), l'Information (Fédération de Russie) et l'Équipement (Fédération de Russie) poursuivent le programme de travail déjà prévu.

## Actions:

- L'information sur les Groupes de Travail sur le site web du Conseil de Développement continuera à être mis à jour autant que possible.

- Le BIML a demandé que ces Groupes de Travail communiquent des informations mises à jour sur leur progression au niveau de leur programme de travail lors de la réunion du Conseil de Développement.

- Les termes de référence et les programmes de travail des Groupes de Travail seront examinés lors de la réunion du Conseil de Développement pour s'assurer qu'ils satisfont toujours aux besoins des membres du Conseil de Développement.

## 6 Projet ONUDI-OIML-PTB dans les pays les moins développés d'Afrique

Le BIML a envoyé en octobre 2000 une demande d'informations sur l'infrastructure actuelle de la métrologie aux sept pays qui peuvent bénéficier de ce projet (Bénin, Burkina Faso, Cameroun, Guinée, Mozambique, Tanzanie, Ouganda). Les informations ont été maintenant reçues du Bénin, du Burkina Faso, du Cameroun, de Guinée et du Mozambique. Elles ont été adressées à l'ONUDI et au PTB et proposition a été faite de tenir une réunion pour discuter des nouvelles étapes de ce projet.

## Actions:

- Une réunion entre les trois organisations se tiendra dès que possible.

Des réunions ont également eu lieu au sujet d'un autre projet dans certains pays d'Afrique occidentale, bien qu'une proposition initiale de réunion et qu'une présentation de propositions faites à la Communauté Économique des États d'Afrique Occidentale (ECOWAS) au début du mois de septembre aient dû être annulées. Le BIML continuera à suivre ces développements.

36ÈME RÉUNION DU CIML

<div align="center">

# Allocution d'ouverture par Mr. V. Hristenko

</div>

Vice Premier Ministre du Gouvernement de la Fédération de Russie

(Discours délivré par Mr. Podufalov, Directeur, Département de la Culture, de l'Éducation et de la Science, Gouvernement de la Fédération de Russie)

Mesdames, Messieurs,

J'ai le grand plaisir de vous accueillir personnellement, au nom du Gouvernement de la Fédération de Russie, à cette Réunion du CIML qui se tient en Russie pour la première fois.

Nous regardons le fait que vous ayez choisi notre pays pour tenir la réunion annuelle de votre éminente organisation - l'Organisation Internationale de Métrologie Légale - première comme un signe du rôle de la Russie et de sa contribution à la création et au développement de l'OIML, et deuxièmement comme un encouragement pour l'activité future de la Russie dans le domaine de la métrologie légale.

La métrologie légale en Russie a débuté au dixième siècle. Aujourd'hui, la Russie prend le chemin d'une complète intégration dans l'économie mondiale, est en

![](page=8,bbox=[1419, 287, 1821, 862])

![](page=8,bbox=[101, 1879, 1009, 2519])

train de vivre une transition vers les mécanismes du libre échange et a pour objectif de rejoindre I'OMC; nous nous intéressons particulièrement au développement et au renforcement de la coopération internationale, y compris la coopération dans le cadre des organisations internationales et régionales.

Durant ces quelques dernières années, les activités de l'OIML ont résulté en un besoin grandissant d'une coopération de plus en plus efficace dans le domaine de la métrologie légale. Cette coopération, qui était et qui est toujours la composante clé de toute nouvelle législation, influence le développement économique dans de nombreux pays du monde.

Le développement et la mise en place de documents harmonisés pour l'essai et la vérification des instruments de mesure sous contrôle et sous surveillance gouvernementaux sont des éléments extrêmement importants du système global de coopération économique.

En raison du rôle significatif que joue la garantie de résultats de mesure précis dans l'établissement des relations commerciales et scientifiques, la Russie s'efforce de maintenir des liaisons métrologiques avec le plus grand nombre possible de pays du monde, dans la mesure où les conséquences de la métrologie légale sont particulièrement importantes dans des domaines tels que le commerce, la santé, la protection de l'environnement et la sécurité.

J'ai également le plaisir de confirmer qu'il est bien sûr dans l'intérêt de notre pays de continuer à développer et à renforcer nos efforts pour promouvoir toutes les activités de l'OIML et pour y participer.

J'aimerais souhaiter un plein succès aux Membres du CIML et à tous ceux qui participent à sa 36ème Réunion, et nous espérons une coopération durable et fructueuse à l'avenir en ce qui concerne les activités de l'OIML.

<div align="center">

# Allocution d'ouverture par Mr. Voronin

</div>

Président du Gosstandart de Russie

Chers participants à la 36ème Réunion du Comité International de Métrologie Légale,

Chers représentants des organisations internationales, régionales et nationales,

Mesdames, Messieurs,

C'est un honneur pour moi de vous souhaiter la bienvenue au nom du Comité d'État de la Fédération de Russie pour la Normalisation et la Métrologie à cette réunion du CIML tenue pour la première fois dans notre pays.

La métrologie légale en Russie possède une longue histoire, en commençant par la surveillance par le Tsar des poids et mesures au Xème siècle, cette surveillance étant assumée par l'Église. Ce petit domaine de métrologie légale s'est progressivement développé grâce aux réformes de Pierre le Grand au XVIIIème siècle et aux ukases du Tsar en 1835 et 1842 jusqu'à l'époque de D. Mendéléev. La vérification en Russie à partir de 1899 a acquis son importance nationale par le biais d'un réseau de chambres de vérification. L'une d'elles a été à l'origine de l'actuel VNIIMS, dont le centième anniversaire a été célébré l'année dernière.

L'année 1938 a vu s'établir en URSS une certaine philosophie dans le domaine des mesurages (unités, étalons, essais, vérification, surveillance). Des conditions indispensables ont été mises en œuvre pour adopter une approche systémique vis-à-vis de ce problème. Un service métrologique national a été mis en route pour assurer l'uniformité des mesurages dans le pays.

Muni de certains pouvoirs par le Gouvernement de la Fédération de Russie pour représenter le pays au CIML, le Gosstandart de Russie appréciie hautement les activités de cette institution internationale intergouvernementale et attache beaucoup d'importance à la coopération entre l'OIML et les instituts métrologiques russes et d'autres organismes, savants et experts.

L'OIML, y compris le Comité International de Métrologie Légale, a fait un grand travail de création qui a permis de renforcer les positions et le prestige internationaux de cette Organisation, et d'augmenter l'efficacité de ses activités.

Citons à titre d'exemples:

- une infrastructure moderne de coopération internationale en métrologie légale est établie et fonctionne sous l'égide de l'OIML;

- l'organisation et la légalisation des activités métrologiques sont établies sur la base des Documents et des Recommandations de l'OIML dans les pays membres de l'OIML et dans d'autres pays du globe, reflétant ainsi les tendances et les perspectives modernes de l'évolution économique et sociale. Ce n'est pas un hasard si l'Union Européenne envisage de faire référence, dans ses directives concernant les instruments de mesure, aux Documents et aux Recommandations de l'OIML;

- le Système de Certificats OIML devient de plus en plus répandu, y compris en Russie, ce qui permet de réduire considérablement les frais occasionnés par la re-vérification des instruments de mesure importés et de réduire les délais de leur mise en application par les autorités économiques nationales.

Ces aspects et beaucoup d'autres ont permis à l'activité de l'OIML d'atteindre des succès remarquables dans les domaines de la qualité des produits industriels, de la protection des consommateurs et de l'elimination des barrières techniques au commerce. Cette activité constitue donc un élément de réglementation technique dans les pays membres de l'OIML.

En ce qui concerne la Russie, les instituts métrologiques du Gosstandart de Russie, et en premier lieu l'Institut national de recherche du service métrologique (VNIIMS), participent aux activités de l'OIML.

![](page=9,bbox=[1151, 1940, 1554, 2519])

Vous n'ignorez pas non plus que les savants et les experts de notre pays ont pris et prennent une part active aux travaux des organismes dirigeants et au travail de l'OIML, ainsi qu'au sein du CIML, du BIML, y compris à travers les rôles de Vice-Président et de premier Vice-Président du CIML. Ces spécialistes ont participé à la solution des problèmes de politique de l'OIML, à la mise au point et à l'implantation d'une politique à long terme. Malgré les difficultés de transmission entre les instances de gestion et les instances législatives dans le contexte des relations de marché, nous nous sommes efforcés de maintenir notre participation à la gestion des organismes techniques de l'OIML au même niveau (34 %). Par conséquent, la part de Documents et Recommandations internationaux mis au point avec le concours des auteurs russes dépasse 15 %.

De nos jours, on ressent de plus en plus une tendance à élargir le domaine d'activités en matière de métrologie légale au niveau national, du fait de l'apparition de nouveaux domaines où se fait sentir la réglementation de l'État (au niveau de la chimie analytique, de la compatibilité électromagnétique, du marché des jeux, etc.), ainsi qu'au niveau international étant donné les processus de globalisation dans le commerce, l'industrie ou l'information.

Ceci requiert des exigences strictes au niveau de la compatibilité des prescriptions métrologiques, et entraîne une compatibilité dans le domaine de l'évaluation de

conformité. C'est pourquoi nous soutenons l'idée de création d'un système global de mesurages qui permettrait d'uniformiser les mesurages.

La confiance mutuelle dans le cadre des activités métrologiques devient d'une importance majeure. Elle est obtenue grâce à l'accréditation, à la comparaison interlaboratoire, à la création des systèmes qualité par le biais de la participation aux accords de reconnaissance réciproque, et à un travail plus efficace au niveau régional.

Ces missions et ces perspectives sont définies par l'OIML pour le XXIème siècle. Le Gosstandart de Russie, ses savants et ses experts, nos collègues travaillant dans le domaine de l'industrie, de la science et de l'économie participeront activement à la coopération dans le cadre de l'OIML, pour résoudre de multiples problèmes de métrologie légale visant, en fin de compte, à résoudre les questions d'actualité de l'évolution économique et sociale de la communauté mondiale.

En conclusion de mon bref exposé, je me permits de souhaiter aux Membres du Comité International de Métrologie Légale, à tous les participants de ce haut forum de l'OIML une mise en oeuvre efficace de leur programme très chargé; je leur souhaite santé et succès au profit du développement de la métrologie et de la coopération internationale!

Merci de votre aimable attention!

![](page=10,bbox=[410, 1616, 1660, 2518])

<div align="center">

# 36ÈME RÉUNION DU CIML

</div>

<div align="center">

# Discours d'ouverture par Gerard J. Faber

</div>

Président, Comité International de Métrologie Légale

Mesdames, Messieurs, Chers Collègues,

C'est avec grand plaisir que je vous accueille à l'ouverture de cette 36ème Réunion de notre Comité, et je vous remercie d'avance de votre participation qui, j'en suis sûr, sera aussi positive et fructueuse que d'habitude.

Cette Réunion du CIML succède à deux autres réunions importantes auxquelles nombre d'entre vous ont assisté: la réunion du Conseil de Développement OIML et la réunion des Organisations Régionales de Métrologie Légale. Mme Annabi, pour le Conseil de Développement, et moi-même, pour les RLMO, ferons un rapport sur le résultat de ces deux réunions, qui peuvent avoir des conséquences importantes pour le travail, la direction et le développement futurs de notre Organisation.

Une année s'est presque écoulée depuis notre Onzième Conférence, et l'une de nos tâches cette semaine est d'examiner la façon dont les décisions de cette Conférence ont été ou sont mises en application. En particulier, nous aurons à étudier les progrès déjà effectués dans deux domaines très importants,

![](page=11,bbox=[299, 1880, 790, 2517])

l'Arrangement d'Acceptation Mutuelle et le marquage international des produits pré-emballés, et à nous assurer qu'ils sont sur la bonne voie et s'acheminent vers une conclusion heureuse en temps voulu.

Enfin, cette Réunion du CIML a lieu pendant une période cruciale de la vie du BIML - et par conséquent de l'OIML toute entière: comme vous le savez déjà bien sûr, M. Magaña remplace M. Athané à la Direction du BIML. En votre nom j'ai étudié attentivement la situation afin d'être sûr que cette période de transition se déroule de la meilleure manière possible pour l'OIML.

Voici, mes chers Collègues, les points les plus importants que nous aurons à examiner et/ou sur lesquels nous aurons à prendre des décisions au cours de cette réunion. En ce qui concerne certains de ces points, j'aimerais dire quelques mots en guise d'introduction à l'occasion de ce discours d'ouverture. Cependant, selon la tradition, j'aimerais commencer par évoquer la situation de nos nouveaux Membres.

Comme vous le savez, pendant les douze derniers mois, le nombre des États Membres de l'OIML est resté le même. Pour les Membres Correspondants, quelques changements sont intervenus avec l'adhésion du Bénin, du Cambodge, des Comores, du Gabon, de Malte et de l'Ouzbékistan, et la radiation de la Colombie, de l'Équateur et du Malawi, qui n'ont pas payé leurs souscriptions annuelles depuis plusieurs années. Ce qui veut dire que, globalement, le nombre des États Membres et des Membres Correspondants de l'OIML a légèrement augmenté depuis notre dernière réunion.

Au sujet de la composition de notre Comité, des changements sont intervenus avec la nomination des nouveaux Membres suivants du CIML:

- Mme Bennett, pour l'Australie,

- M. Koreshkov, pour le Bélarus,

- M. Lagauterie, pour la France,

- M. Chun Haeng Cho, pour la République de Corée,

- M. Tanaka, pour le Japon.

C'est avec le plus grand plaisir que j'accueille tous ces nouveaux Membres du CIML, trois d'entre eux ayant déjà assisté aux réunions de Londres, et que je les remercie à l'avance de leur participation à notre travail.

Cette semaine j'ai reçu une lettre de M. Li Chuanqing de la République Populaire de Chine annonçant qu'il devrait quitter le CIML en raison de changements intervenus dans ses responsabilités et qu'il serait remplacé par M. Wang Qinping, Vice-Ministre de AQSIQ. Par ailleurs j'ai été informé qu'à la fin du mois, M. Bennett, du Royaume-Uni, devra également quitter le CIML en raison de sa nomination en tant que Directeur Adjoint du NPL. Après son départ, M. Birdseye reprendra le poste de Membre du

CIML pour le Royaume-Uni jusqu'à ce qu'une décision officielle soit prise concernant ce poste. Je profite donc de cette occasion pour féliciter M. Li et M. Bennett pour leur nouvelle responsabilité, et de les remercier du rôle qu'ils ont joué au sein de l'OIML, en particulier un rôle exceptionnel au sein du Conseil de la Présidence. C'est bien entendu avec le plus grand plaisir que j'accueille les nouveaux Membres, M. Wang et, pour le moment du moins, M. Birdseye, et je leur souhaite beaucoup de succès dans leur nouveau rôle en tant que Membres du Comité.

Il y a presque un an, la Onzième Conférence a pris un certain nombre de décisions importantes concernant la Politique à Long Terme de l'OIML, les activités techniques, les liaisons avec les autres institutions internationales et régionales, et bien sûr le budget pour les quatre années à venir et les autres questions financières. Au cours de la Réunion du CIML, tous ces sujets seront soigneusement examinés sous les divers points de notre ordre du jour. Je n'ai pas l'intention de revenir plus en détails sur ces points immédiatement, mais j'aimerais simplement vous assurer que toutes vos discussions et suggestions seront attentivement examinées par le Conseil de la Présidence et par le Bureau et serviront de base pour diriger - ou même à certaines occasions "re-diriger" - les activités de l'OIML concernées. Je peux d'ores et déjà prédire, par exemple, que les relations entre l'OIML et certains organismes européens donneront lieu à des discussions très intéressantes. N'hésitez pas à exprimer vos opinions et peut-être aussi vos critiques!

La situation au sein du BIML sera également abordée par un point de notre ordre du jour: ce sera pour vous l'occasion de poser des questions. Je tiens simplement à vous dire en guise d'introduction que j'ai considéré qu'il était pour moi de la plus haute priorité

![](page=12,bbox=[101, 1900, 1011, 2520])

de diriger avec attention la transition entre M. Athané et M. Magaña. Je peux déjà vous informer que je pense que M. Magaña a été jusqu'à présent en mesure de consacrer la plupart de son temps à des questions de politique et de liaisons externes. Parallèlement, M. Athané a continué d'exercer ses responsabilités de Directeur tout en s'assurant que son successeur était informé point par point de tous les aspects de la vie du BIML. J'ai multiplié les contacts avec le BIML par e-mail ou par téléphone, mais également par de fréquentes visites au cours desquelles j'ai eu l'occasion de m'entretenir soit avec MM. Athané et Magaña ensemble, soit seulement avec l'un d'entre eux et plus particulièrement avec M. Magaña afin d'échanger avec lui des vues concernant les développements futurs de l'OIML et de son Bureau. Je dois dire que je suis pleinement satisfait de la façon dont la transition se déroule mais je serai bien sûr prêt à entendre vos propres points de vue. La période de transition prendra fin demain à l'occasion de la réception de l'OIML et jeudi matin, lors de la session de clôture de notre réunion, M. Magaña siégera à cette table en tant que nouveau Directeur du BIML.

Voici, mes chers Collègues, les remarques préliminaires que je voulais faire à cette occasion. Cependant, avant de clore mon discours d'ouverture, je pense qu'il serait approprié de se tourner un peu plus vers l'avenir. Comme vous le savez, pendant la Réunion du CIML à Londres, j'ai été réélu Président du CIML pour une période supplémentaire limitée à trois ans. Par conséquent il faudra élire un nouveau Président à l'occasion de la 38ème réunion du CIML, d'ici deux ans. Une telle élection doit être préparée longtemps à l'avance afin d'identifier les candidats qui se présenteront, d'informer le CIML sur ces candidatures et de décider de la procédure d'élection. En tant qu'actuel Président du CIML, j'ai bien sûr une importante responsabilité dans la préparation de l'élection de mon successeur et je demanderai au Conseil de la Présidence de m'aider à ce niveau. Il est clair cependant que vous êtes aussi profondément concernés et c'est pourquoi j'invite tous ceux d'entre vous qui auraient des propositions à faire de me contacter personnellement avant la 37ème réunion du CIML l'an prochain, afin que, pendant la réunion, je puisse déjà donner des informations pertinentes. Soyez sûrs que je tiendrai compte très sérieusement de toutes les suggestions qui me seront faites.

Ainsi, pour conclure cette allocution, puis-je demander au Directeur du BIML de procéder à l'appel des participants avant de nous lancer dans la discussion des divers points de l'ordre du jour.

En vous remerciant de votre attention, je vous souhaite une réunion très fructueuse.

<div align="center">

# Moscou, 25-27 septembre 2001

</div>

COMPTE RENDU PAR CHRIS PULHAM, BIML

TRADUCTION PAR LAURENCE LICHTIG

Le Comité International de Métrologie Légale, à l'invitation de son Président, M. Gerard Faber, s'est réuni du 25 au 27 septembre 2001 dans la salle de conférence de l'Intourist Hotel, à Moscou.

Les allocutions d'ouverture sont faites par M. Podufalov, de la part du gouvernement russe, M. Voronin, Président du Gosstandart et Gerard Faber, Président du CIML. Ces discours sont publiés intégralement dans ce numéro du Bulletin.

Quarante-sept Membres du CIML sur un total de cinquante-sept sont présents ou représentés et il est par conséquent établi que le quorum statutaire des trois-quarts est atteint. Suite à l'adoption du compte rendu de la 35ème Réunion du CIML (Point 1) M. Faber passe en revue les décisions et résolutions de la Onzième Conférence (Point 2) et commente leur degré de mise en oeuvre, ou sinon, quelles actions le Comité doit encore entreprendre, en particulier à l'occasion de cette 36ème Réunion. Le Comité exprime sa satisfaction pour les progrès qui ont déjà été effectués.

Le Comité examine ensuite le Plan d'Action 1999-2002 et son extension à la période 2003-2004 (Point 3). M. Athané rappelle le processus suivi pour réexaminer le Plan d'Action initial et pour envisager son extension à la période 2003-2004 en accord avec la décision de la Onzième Conférence. Ce processus a impliqué le Bureau, le Conseil de la Présidence et tous les Membres du CIML et a abouti à un projet final de Plan d'Action qui est soumis à cette 36ème Réunion du CIML pour commentaires, en même temps qu'un projet de Résolution soumis à l'approbation du CIML. Le Plan d'Action est publié dans ce numéro du Bulletin, et constitue la base de la stratégie de l'OIML pour les années à venir.

M. Faber ayant déjà donné des informations détailées sur la participation à I'OIML dans son allocution d'ouverture (voir plus haut), au Point 4, seuls de brèves informations supplémentaires sont données sur la

situation de certains Membres de l'OIML. Cependant, M. Magaña annonce que la Malaisie et le Vietnam ont informé le Bureau qu'ils envisagent d'élever leur participation au statut d'État Membre, mais qu'aucune décision finale n'a encore été prise. Certains autres Membres Correspondants envisagent également d'accéder au statut d'État Membre, mais il est trop tôt pour donner plus d'informations à ce stade.

Il est aussi annoncé que malheureusement certains pays ont des difficultés à s'acquitter du paiement de leurs cotisations, bien que le BIML soit heureux de déclarer qu'au moment de rédiger ce rapport, une large part de ces arriérés a été réglée. Deux pays sont encore en retard dans leur paiement et des dates limites ont été fixées, afin de permettre à ces Membres de disposer d'un délai suffisant pour mettre leurs comptes à jour.

Pour résumer les discussions sur les questions financières (Point 5), le Comité adopte le rapport comptable pour 2000; ce document sera soumis à la Douzième Conférence. M. Athané annonce que la situation financière de l'Organisation est globalement plutôt bonne; le budget sera respecté sans difficulté. M. Magaña évoque le passage à l'Euro en janvier 2002 ainsi qu'une nouvelle présentation des comptes du BIML afin de mieux estimer les coûts opérationnels des divers organes constitutifs de l'OIML et ceux des divers produits et services proposés par le Bureau (site web, publications, frais divers, etc.). Il explique qu'une nouvelle politique de prix concernant les publications et les services de l'OIML sera mise en place en janvier 2002 (voir le fascicule séparé inséré dans ce numéro du Bulletin) et que le BIML travaille actuellement sur un projet qui permette aux clients d'acheter et de télécharger les publications OIML directement à partir du site web, y compris le paiement en ligne par carte de crédit.

M. Faber rappelle aux participants que le rôle du Conseil de la Présidence (Point 6) est d'aider le Président à préparer les discussions au niveau du CIML, étant entendu que le Conseil ne prend en fait aucune décision de lui-même. En 2001, le Conseil de la Présidence s'est réuni en février et en septembre afin de réexaminer les résultats de la Onzième Conférence et de la 35ème réunion du CIML et de préparer les décisions qui seront prises pendant la 36ème Réunion du CIML. La composition du Conseil figure à l'intérieur de la page de couverture de chaque Bulletin.

Pour introduire le Point 7 Personnel du BIML, M. Athané rappelle aux participants que le BIML comprend actuellement dix membres du personnel à savoir le nouveau et l'ancien Directeurs, deux Adjointes au Directeur, un Administrateur, un Ingénieur, un Rédacteur, deux Secrétaires et un Employé de Bureau. Un deuxième Employé de Bureau est parti à la retraite en août 2000 mais n'a pas encore été remplacé afin de permettre à M. Magaña de revoir globalement la situa-

tion du personnel du BIML et de recruter éventuellement une personne supplémentaire si nécessaire.

M. Magaña ajoute qu'il envisage actuellement de revoir les missions globales du BIML et tirera ses conclusions au sujet du personnel du BIML et ses qualifications à l'issue de cette 36ème Réunion du CIML. Pour le moment il n'a pris aucune décision concernant le poste resté vacant depuis août 2000. Cependant, il va progressivement augmenter les responsabilités des deux Secrétaires afin de permettre au personnel technique de disposer de plus de temps pour se concentrer sur des tâches plus stratégiques. Il souligne qu'un besoin croissant se fait sentir d'une personne qualifiée dans le domaine de l'informatique et d'Internet; un exemple spécifique d'application consiste à améliorer et à moderniser le site web de l'OIML pour prendre en compte les besoins des TC/SC en matière de forums de discussion et d'échanges de documents. Pour le moment il envisage d'engager des spécialistes qui entreprendraient des tâches spécifiques sur des périodes précises avant de définir les besoins permanents en personnel du Bureau.

Le contrat de M. Attila Szilvássy en tant qu'Adjoint au Directeur est renouvelé pour une période de cinq ans à compter de septembre 2002 - ce qui est décidé à l'unanimité. M. Faber félicite M. Szilvássy qui remercie le Comité pour sa décision et affirme son désir de continuer à servir l'OIML du mieux qu'il pourra.

Une brève information est donnée concernant la transition entre les deux Directeurs - il est confirmé que la passation de pouvoirs a été parfaitement orchestrée et que M. Athané jouera le rôle de Conseiller auprès du Directeur de la période d'octobre 2001 à décembre 2002. Un rapport écrit décrivant les activités du BIML d'octobre 2000 à septembre 2001 est ensuite distribué; ce rapport est publié plus loin dans ce numéro du Bulletin.

![](page=14,bbox=[101, 1909, 1009, 2518])

Un rapport écrit préparé par le BIML sur le Point 8 Activités techniques est distribué et présenté par M. Issaev, qui souligne l'augmentation du volume global des activités techniques de l'OIML comparé aux années précédentes. Il mentionne la situation de certains TC/SC vacants, de ceux pour lesquels le nombre de membres-P est en-dessous du minimum spécifié par les Directives pour le Travail Technique, et enfin de ceux qui rencontrent des difficultés temporaires dans leur travail.

M. Szilvássy explique que trente-deux projets de comités ont été élaborés depuis octobre 2000, ce qui est nettement supérieur au résultat de n'importe quelle année précédente; de plus, un certain nombre de TC/SC ont été réactivés au cours des dix-huit derniers mois. Tout ceci prouve que l'activité technique de l'OIML s'améliore.

Les autres points clés sont:

- Les projets prioritaires et de haute priorité sont identifiés et une liste en est dressée - cette liste est approuvée par le Comité et sera publiée et affichée sur le site web de l'OIML;

- Un besoin urgent se fait sentir d'accélérer les révisions du D 1 Loi de Métrologie et du D 11 Instruments électroniques;

- Des documents doivent être élaborés sur l'incertitude de mesure, les logiciels et les méthodes statistiques à utiliser dans les contrôles de métrologie légale;

- Il est urgent de trouver un État Membre volontaire pour assumer la responsabilité du TC 13 Acoustique et vibrations étant donné en particulier les progrès rapides dans l'élaboration ou la révision des Normes CEI.

M. Szilvássy indique que les informations sur les activités de l'OIML sont maintenant systématiquement disponibles sur le site web de l'OIML sous la forme de base de données.

Le Comité approuve les quatre projets de Recommandations suivants:

- Sphygmomanomètres noninvasifs. Partie 1: Mécaniques; Partie 2: Automatisés (Révision de la R 16);

- Thermomètres à liquide en verre (R 133);

- Compteurs d'eau destinés au mesurage de l'eau potable froide. Partie 2: Procédures d'essai (R 49-2);

- Compteurs d'énergie thermique. Partie 1: Exigences générales; Partie 2: Essai d'approbation de modèle et de vérification primitive (Révision de la R 75).

M. Magaña explique que le Bureau met en place un certain nombre d'outils et d'activités sur les technologies d'information dans le but d'accélérer le travail technique de l'OIML et donc de faciliter la participation des Membres, par exemple en introduisant l'utilisation de forums de discussion basés sur Internet pour les thèmes de travail des TC/SC.

Il informe également l'assemblée que la correspondance du BIML sera bientôt effectuée par e-mail, tout en conservant les moyens plus lents de communication pendant aussi longtemps que nécessaire.

Un nombre croissant de publications de l'OIML peut déjà être télécharge du site web de l'OIML, en particulier toutes celles qui sont liées au Système de Certificats. D'ici quelques mois toutes les publications de l'OIML seront disponibles en format PDF - le BIML note que par ailleurs, un nombre croissant de clients demande des versions électroniques plutôt que des documents papier. Pour faciliter l'achat de ces publications, un système d'achat en ligne utilisant les cartes de crédit est en train d'être mis en place sur le site web de l'OIML.

Évoquant la possibilité d'organiser des vidéoconférences basées sur Internet, M. Magaña explique que pour l'instant le Bureau en est à un stade très expérimental, utilisant des installations simples et peu coûteuses seulement à usage interne; mais par la suite il sera probablement possible d'utiliser ce genre de technologie pour des réunions techniques en ligne.

Une autre proposition de M. Magaña serait de mettre à la disposition de chaque secrétariat de TC/SC un site web où les documents de travail seraient disponibles. Les commentaires des membres des TC/SC seraient envoyés directement sur le site et seraient immédiatement disponibles pour le secrétariat et les autres membres.

M. Dunmill fait remarquer que les Directives pour le Travail Technique sont actuellement en cours de révision par le Bureau car les Directives actuelles existent depuis 1993 et beaucoup de méthodes de travail ont changé. La révision est également devenue nécessaire du fait du résultat de l'Accord OMC/TBT, des changements intervenus dans les relations entre les TC et les SC en liaison, et de l'évolution du genre de documents élaborés par les TC/SC. Les divers formulaires publiés à la fin des Directives deviendraient également disponibles en format électronique pour faciliter leur utilisation par les TC/SC (par exemple lors de la préparation de leurs rapports annuels) et pour uniformiser leur format. Il est également nécessaire de prendre en considération les changements intervenus depuis 1993 dans les méthodes de travail correspondantes d'ISO/CEI tout en simplifiant considérablement ces méthodes de façon à rendre plus facile leur mise en application par les TC/SC de l'OIML.

M. Boudissa suggère que des CD-ROM pourraient également être utilisés par le Bureau comme alternative à l'Internet pour les pays qui ne sont pas encore connectés au net; M. Magaña approuve cette proposition.

Un rapport écrit préparé par le BIML sur le Système de certificats OIML pour les instruments de mesure (Point 9) est distribué et commenté par M. Kochsiek.

Après avoir exposé brièvement son histoire, il donne des informations concernant les développements intervenus depuis les douze derniers mois, y compris l'interaction entre le Système et l'Arrangement d'Acceptation Mutuelle. Il donne aussi des statistiques concernant les certificats déjà délivrés, les catégories d'instruments auxquelles s'applique le Système, les Autorités de Délivrance et les Demandeurs. Enfin, il explique que le document décrivant les règles de fonctionnement du Système est en cours de révision, avec une nouvelle version attendue pour le milieu de l'année 2002 après consultation postale des Membres du CIML. Le champ du Système sera élargi dans deux directions: (i) la certification des types de modules et (ii) la certification des types de familles (d'instruments ou de modules). Ces actions sont également prévues dans le Plan d'Action (publié dans ce Bulletin). De plus la révision des règles de fonctionnement du Système créera un glissement de responsabilités des Membres du CIML vers les Autorités de Délivrance, et il contiendra aussi de nouvelles dispositions pour l'identification des modèles certifiés. M. Ehrlich explique que certains points seront probablement clarifiés lors de l'examen de l'état d'avancement du MAA au point 10. Cependant, il faut garder en tête que le MAA est un cadre pour le développement d'accords d'acceptation spécifiques qui garderont dans une large mesure une nature non obligatoire.

M. Szilvássy fait remarquer qu'une base de données de certificats a déjà été placée sur le site web de l'OIML et que l'on peut y trouver des informations concernant tous les certificats enregistrés, les Demandeurs, les

![](page=15,bbox=[1043, 1655, 1650, 2519])

Autorités de Délivrance et les Recommandations applicables.

Le Comité décide que deux Recommandations approuvées récemment (R 16 Sphygmo-manomètres et R 133 Thermomètres à liquide en verre) deviendront applicables au Système dès leur publication.

M. Ehrlich ouvre la discussion sur le Point 10 Arrangement d'Acceptation Mutuelle (MAA) en disant que l'avantage du MAA sera de fournir un mécanisme d'examen des laboratoires d'essais à un niveau plus élevé que ce qui existe actuellement avec le Système de Certificats. Un simple résumé des discussions est donné dans ce Bulletin, dans la mesure où un exposé plus détaillé est publié dans le Compte Rendu officiel de la Réunion, qui peut être téléchargé du site web de l'OIML.

En tant que co-responsable du secrétariat du TC 3/SC 5 sur l'évaluation de conformité, M. Ehrlich passe en revue la progression du travail qui est en route depuis bientôt quatre ans pour mettre au point un arrangement grâce auquel des données d'essais obtenues dans des laboratoires d'essais de métrologie légale d'un État Membre puissent être acceptées et utilisées par des organismes responsables d'autres États Membres de l'OIML, soit pour délivrer des certificats nationaux d'approbation de modèles dans ces autres pays soit au moins pour obtenir un autre type d'autorisation pour mettre sur le marché et vendre les instruments correspondants dans ces pays. Un tel arrangement complètait le Système de Certificats OIML et avantagerait les constructeurs d'instruments de mesure en éliminant la nécessité d'essais répétitifs. Il fait remarquer que le MAA sera un arrangement entre Autorités de Délivrance ou autres organismes nationaux responsables, mais pas entre gouvernements, laboratoires d'essais ou Membres du CIML.

M. Ehrlich explique comment il sera possible de mettre en oeuvre le concept et d'obtenir la confiance des participants dans la compétence des divers laboratoires d'essais sans encourir des coûts excessifs et sans créer des "clubs" qui excluraient certains pays. À cette fin le 8ème CD a été complété par une liste de contrôle (actuellement au stade de 2ème CD) à l'usage des Autorités de Délivrance et des laboratoires d'essais organisant des évaluations de modèles OIML. Le MAA servira de cadre pour élaborer une série de documents signés portant chacun le nom de "déclaration de confiance mutuelle" pour une catégorie donnée d'instruments de mesure couverts par une Recommandation OIML mise en application dans le cadre du Système de Certificats OIML. Comme déjà mentionné, la signature d'une déclaration de confiance mutuelle ne créera pas d'obligation, avec l'exception qu'une fois qu'un participant a accepté les données d'essais, ces données auront la même valeur légale que si elles provenaient des laboratoires d'essais du participant.

Le processus comprendra une notification du BIML de l'intérêt d'un pays donné de signer une déclaration pour un type particulier d'instrument. Le BIML avisera ensuite tous les Membres du CIML. Un comité ad-hoc d'examen de participation (le BIML jouant le rôle de secrétariat) coordonnera l'évaluation des laboratoires d'essais participants et préparera un rapport discutant de l'évaluation des compétences de ces laboratoires. Le BIML facilitera également le fonctionnement du système, y compris le traitement de réclamations éventuelles. Ce comité sera constitué d'experts nommés par et représentant les Autorités de Délivrance ou les organismes nationaux responsables.

Mme Bennett intervient pour dire que l'Australie soutient fermement l'objectif de parvenir à un accord général entre Autorités de Délivrance de l'OIML pour l'acceptation mutuelle de données d'essais et qu'elle apprécie le travail entrepris par le secrétariat US. L'Australie a décidé de procéder à des accords bilatéraux avec certains de ses partenaires commerciaux, y compris les Pays-Bas et le Royaume-Uni; M. Ehrlich fait remarquer que les accords bilatéraux peuvent effectivement faciliter le développement du MAA de l'OIML.

M. Kildal demande des informations concernant le degré de coopération avec ILAC et si une coopération parallèle avec IAF existe déjà ou existera à l'avenir. En fait IAF est en train d'établir un MRA international sur la certification des produits qui pourrait aider l'OIML à établir un système moins coûteux si l'Organisation profitait du système IAF.

M. Ehrlich répond qu'il n'existe pas de coopération directe entre le TC 3/SC 5 et ILAC et qu'aucune interaction directe d'ILAC ou d'IAF dans le fonctionnement du MAA OIML n'est prévue. M. Kildal demande si la mise en place du système occasionnera des coûts supplémentaires pour le BIML et par là-même pour les États Membres de l'OIML.

M. Ehrlich admet que cela occasionnera au BIML des coûts supplémentaires, mais que ces dépenses seront plus ou moins indépendantes de la solution choisie pour l'évaluation des compétences. M. Bennett exprime son appréciation pour le progrès accompli dans le 8ème projet comparativement au précédent.

M. Vaucher dit qu'il est encore convaincu que le MAA est nécessaire et urgent. Il apprécie également le fait qu'il a été rédigé d'une façon beaucoup plus simple qu'auparavant, ce qui facilitera sa mise en application à des coûts raisonnables sans empêcher aucun pays d'y participer. Il suggère aussi que le champ d'action du projet soit élargi de sorte que non seulement les rapports d'essai soient reconnus, mais également l'évaluation de ces rapports d'essai, c'est-à-dire les certificats OIML ou les déclarations de conformité.

M. Boudissa reconnaît que le système proposé économisera beaucoup de temps et d'argent et facilitera

les transactions commerciales entre pays en évitant les frais divers et la multiplication des essais. Cependant, un problème se pose pour les pays en développement dans la mesure où le système sera accessible seulement aux pays qui possèdent les ressources nécessaires aux essais et les installations de vérification ainsi que les compétences technologiques. Dans les pays en développement ces équipements et cette compétence n'existent pas encore, ce qui peut les empêcher de participer au système. M. Boudissa suggère par conséquent que I'OIML organise des séminaires de formation sur tous les aspects liés à l'acceptation mutuelle de sorte que la participation future de ces pays au système soit positive.

M. Ehrlich appréciée cette proposition et suggère à M. Boudissa d'exprimer cette opinion par écrit pour qu'elle puisse être examinée par le TC 3/SC 5.

Mr. Sinyangwe explique que ce sujet est très intéressant pour les pays en développement qui ne fabriquent pas d'instruments de mesure (et par conséquent ne délivrent pas de certificats OIML) mais qui doivent importer ces instruments en provenance de pays industrialisés. Il demande comment ces pays en développement pourront s'insérer dans le système.

M. Magaña fait remarquer que le MAA contient un mécanisme qui d'une part instaure la confiance entre ses signataires et d'autre part augmente la confiance dans les certificats. Par conséquent un pays qui n'a pas les moyens de délivrer des certificats peut néanmoins déclarer sa confiance dans les certificats délivrés par les autres pays. Ce serait une sorte de déclaration "unilatérale".

M. Ehrlich répond qu'à son avis le MAA sera très utile pour les pays qui possèdent des installations pour effectuer des essais. Par conséquent les pays en développement ne possédant pas d'installations pour évaluer les données d'essais devront se limiter à l'acceptation de certificats OIML. Cependant on pourrait envisager pour ces pays un rôle éducatif, par exemple par la participation au comité d'évaluation.

En ce qui concerne la question de la responsabilité légale, M. Birch explique que les Autorités de Délivrance assumeront cette responsabilité légale pour les données d'essais qu'elles reçoivent; pour ce qui est des déclarations de confiance mutuelle, ce sont les Membres du CIML, lors de la signature, qui assumeront la responsabilité légale au nom des Autorités de Délivrance.

En guise de conclusion à cette discussion, M. Faber remercie M. Ehrlich et le TC 3/SC 5 pour le travail qu'ils ont accompli. Il déclare également qu'il est convaincu de la nécessité de développer rapidement le MAA car l'acceptation des données d'essais est d'une nécessité évidente.

M. Ehrlich aborde le Point 11 Marque IQ pour les produits préemballés en évoquant la révision de la R 87

Contenu net des préemballages, qui à l'origine contenait une annexe proposant l'établissement d'une marque IQ. Plusieurs commentaires ont été reçus des membres du TC 6 concernant la révision du 2ème projet de comité de la R 87 et, sur la base de ces commentaires, il est prévu un 3ème projet qui sera distribué en décembre 2002.

Le Conseil de la Présidence réuni en février 2001 a décidé que la marque IQ elle-même ne fera plus partie de la R 87, mais sera l'objet d'un document indépendant qui spécifiera les exigences à satisfaire par les emballeurs, pour que les paquets qu'ils produisent soient certifiés conformes à la R 87. Ce travail commencera (au début au niveau d'un petit groupe de travail du Conseil de la Présidence) quand la révision de la R 87 sera terminée.

M. Zhagora fait remarquer que "IQ" est déjà utilisée comme abréviation de "quotient intellectuel". M. Ehrlich répond qu'il réfléchira sur la confusion que cela peut entraîner et, le cas échéant, il essayera de trouver une autre abréviation pour la marque OIML.

M. Birch declare qu'il est déçu par le retard pris à établir la marque IQ, car elle répond à une demande très nette de la part des fabricants. Il demande si l'on a recherché les commentaires de l'industrie concernant le projet, en plus de ceux des autorités légales nationales, mais M. Ehrlich répond que, pour autant qu'il sache, les commentaires reçus l'étaient seulement des Membres du CIML; il ne sait pas jusqu'à quel point ces Membres du CIML ont consulté leurs fabricants nationaux.

Mme Annabi fait ensuite un rapport sur le Point 12 Réunion du Conseil de Développement, et M. Faber effectue un compte rendu sur la réunion des RLMO - ces deux résumés sont publiés séparément.

Au Point 13 des informations sont données sur les Liaisons avec les institutions internationales et régionales.

Convention du Mètre/ILAC/OIML. M. Faber évoque la réunion commune qui s'est tenue au BIML en février 2001, avec 14 personnes représentant les trois

![](page=17,bbox=[974, 1914, 1880, 2518])

organisations. Les activités entreprises au sein de chaque organisation et au sein du Joint Committee for Guides in Metrology depuis les douze derniers mois sont passées en revue dans le but d'identifier celles qui peuvent influencer, ou être influencées par, les activités d'une ou des deux autres organisations: CIPM MRA, ILAC MRA, CIPM/ILAC MoU, OIML MAA, l'accréditation des laboratoires qui effectuent des évaluations et des essais de métrologie légale, le développement d'une loi modèle de métrologie (pour laquelle un groupe de travail commun a été établi), l'aide aux pays en développement dans la mise en place d'organismes appropriés de métrologie, de métrologie légale et d'accréditation (identifiée comme action prioritaire pour laquelle ILAC et l'OIML établiront un groupe de travail commun avec, à l'avenir, une participation attendue du BIPM), l'organisation d'un séminaire international pour donner suite au séminaire de Braunschweig de 1998, une contribution coordonnée à ISO 17011 afin de rendre cette norme acceptable aux instituts métrologiques nationaux. Il est enfin décidé que la prochaine réunion Convention du Mètre/ ILAC/OIML se tiendra au BIPM en février 2002.

OMC. M. Magaña fait état des nombreux contacts avec le Comité OMC/TBT et de la participation active aux réunions, y compris les séminaires à l'occasion desquels les "organisations internationales de développement des normes" expliquent leurs objectifs, la façon dont elles satisfont aux règles de l'OMC qui les concernent et développement l'information mutuelle; de plus une attention spéciale est portée aux pays en développement, afin de faciliter leur participation à la préparation des normes internationales. Une coopération plus récente et spécifique s'est établie pour l'aide aux pays en développement dans le domaine de la métrologie et de la métrologie légale, avec un séminaire régional qui s'est tenu à Paris à la fin de l'année 2000, et un document préparé à l'attention de l'OMC, qui semble

![](page=18,bbox=[105, 1886, 1012, 2519])

être maintenant très consciente du rôle de la métrologie dans le commerce et désireuse de soutenir les initiatives de l'OIML dans le but de promouvoir la métrologie grâce à divers organismes de financement internationaux et régionaux.

Organismes de l'Union Européenne. M. Magaña rappelle aux participants que lors de la 35ème Réunion du CIML des informations avaient été données concernant le développement de la MID et ce qui était alors envisagé comme "Documents Normatifs OIML" pour donner une présomption de conformité aux exigences essentielles de la MID. Depuis lors, les Représentants de la Commission de l'Union Européenne ont clairement indiqué que cette présomption serait donnée par les Recommandations OIML elles-mêmes sans qu'il soit nécessaire pour l'OIML de rédiger des documents supplémentaires.

Concernant CEN et CENELEC, M. Magaña explique que les contacts résultent du fait que la MID permet deux genres de présomption de conformité: les Recommandations OIML et les normes européennes harmonisées, développées par CEN/CENELEC suite à des mandats délivrés par la Commission de l'Union Européenne. Il est par conséquent approprié de s'assurer que cela ne résulta pas en trop de compétition entre l'OIML et CEN/CENELEC.

M. Faber confirme que le Conseil de la Présidence a examiné dans quelle mesure l'OIML, en tant qu'organisme international de métrologie légale, devrait se préoccuper de l'activité des organismes régionaux de normalisation, et quel serait le rôle que le Bureau aurait à jouer à ce sujet.

Comme règle générale pour l'avenir, il faut opérer une distinction entre deux types d'accords: (i) les accords limités à des échanges d'informations, qui doivent être conclus par les directeurs/secrétaires généraux des deux organisations, sans qu'il soit besoin de consulter le CIML, et (ii) les accords contenant plus qu'un simple échange d'informations, qui doivent être discutés et approuvés par le CIML. Un document politique régissant les liaisons entre l'OIML et d'autres organismes régionaux et internationaux sera rédigé en temps voulu pour la prochaine Réunion du CIML.

M. Kildal et M. Vaucher expriment tous deux leur appréciation pour le rôle joué par le BIML pour promouvoir la mise en application des Recommandations OIML au niveau européen. C'est la responsabilité de l'OIML d'harmoniser les exigences métrologiques et techniques, et il est par conséquent dans son intérêt que les Recommandations OIML soient reconnues par l'Union Européenne; cela éviterait en même temps que d'autres organismes élaborent des normes contenant peut-être des exigences conflictuelles qu'il faudrait ensuite harmoniser.

M. Magaña explique que l'OIML rencontre un genre de défi constitué par le fait que, dans le domaine de la

normalisation, la norme qui prévaut est celle qui a été élaborée le plus rapidement. L'OIML doit accélérer ses méthodes de travail afin de développer ou de réviser ses Recommandations plus rapidement.

Au point suivant de l'ordre du jour (Point 14), M. John Birch et M. Bernard Athané sont tous deux nommés Membres Honoraires du CIML. M. Faber explique que M. Birch a été pendant longtemps un remarquable Membre du CIML et du Conseil de la Présidence et qu'il a fait preuve de compétence en participant très activement à pratiquement toutes les discussions, quel qu'en soit le sujet. Il a également démontré au Comité et au Conseil qu'il était nécessaire de penser non seulement en termes de technique mais également en termes de stratégie et de politique.

M. Faber félicite également M. Athané pour sa contribution au développement de la science métrologique et son rôle en tant que Directeur du BIML, et une réception a été offerte par l'OIML le jeudi 27 septembre au soir au cours de laquelle la nomination de M. Athané a été célébrée.

La question des prochaines réunions du CIML est discutée au Point 15. Le Comité décide de tenir sa 37ème Réunion en France autour de fin septembre/début octobre 2002, organisée par le BIML sous la supervision du Président du CIML et de son Conseil. Puis M. Tanaka invite officiellement le Comité à tenir sa 38ème Réunion à Kyoto en 2003, à l'occasion du centenaire de la création de l'institut japonais de métrologie légale. Le Comité remercie M. Tanaka pour son invitation qu'il accepte en principe, mais annoncant qu'une décision finale devra être prise au cours de la 37ème Réunion. En plus de l'invitation de longue date d'Israël, une invitation a été également faite par l'Allemagne pour la 39ème Réunion du CIML qui se tiendra en même temps que la Douzième Conférence en 2004. Le Comité décide de considérer l'invitation israélienne comme première option et l'invitation allemande comme seconde option, la décision finale devant être prise en 2002.

Au Point 16 Autres questions M. Magaña donne des informations concernant les propositions de présentations qu'il a reçues pour l'atelier Métrologie légale en 2020. On ne dispose pas d'assez de temps pour organiser cet atelier en février 2002 comme prévu initialement. Il propose par conséquent que l'atelier se tienne en septembre ou en octobre 2002 conjointement avec la 37ème Réunion du CIML. Le Comité approuve cette proposition et M. Magaña ajoute que l'on dispose d'assez de temps pour proposer des lectures supplémentaires et que le Conseil de la Présidence fera une sélection finale à partir de toutes celles qui ont été soumises.

Les décisions et résolutions (Point 17) sont adoptées par le Comité durant sa dernière session jeudi 27 septembre. Comme c'est la première fois que

M. Magaña participe à la Réunion du CIML en tant que Directeur du BIML, M. Faber lui exprime son soutien énergique et ses vœux de réussite pour sa nouvelle carrière. Il réitère également ses remerciements à M. Athané pour avoir assuré la direction du BIML pendant de si longues années.

M. Magaña remercie M. Faber et tous les Membres du CIML pour leur confiance, et exprime sa reconnaissance à M. Athané ainsi qu'aux trois autres membres du personnel du BIML présents à cette réunion, pour leur aide et leur soutien.

En clôturant la réunion, M. Faber adresse ses remerciements les plus sincères aux hôtes russes, aux deux Directeurs ainsi qu'au Personnel du BIML présent, et aux deux Vice-Présidents du CIML et à tous les Membres du Conseil de la Présidence pour leur aide. Il remercie aussi l'équipe d'interprêtes et, enfin et surtout tous les participants à la 36ème Réunion du CIML, c'est-à-dire les Observateurs issus des Membres Correspondants et des RLMO et particulièrement les Membres du CIML, pour leur participation fructueuse aux discussions et aux prises de décision.

Pour conclure, M. Faber invite tous les Membres du CIML à se réunir à nouveau en France l'an prochain.

M. Issaev, au nom des Autorités russes, exprime le plaisir qu'il a éprouvé à accueillir cette Réunion du CIML et invite les divers participants aux visites techniques ou autres pour lesquelles ils se sont inscrits.

![](page=19,bbox=[972, 1846, 1880, 2518])

<div align="center">

# Réunion des Organisations Régionales de Métrologie Légale

</div>

<table><tr><td>a réunion des RLMO a été organisée en maison avec, mais non comme une partie de la 36ème Réunion du CIML. Le rapport complet de la réunion des RLMO est joint au Compte Rendu de la 36ème réunion du CIML. Les conclusions de la réunion des RLMO ont été présentées au Comité qui, après quelques amendements mineurs, les a considérées comme base acceptable pour l’élaboration d’un document de politique de l'OIML. Les conclusions définitives sont les suivantes:</td></tr><tr><td>Échanges d’informations sur les RLMO</td></tr><tr><td>Chaque RLMO a présenté les aspects principaux de ses activités. Les points suivants ont été soulignés:</td></tr><tr><td>• Besoin d’améliorer l’information mutuelle et la coordination entre les RLMO en ce qui concerne le développement de moyens de formation.</td></tr><tr><td>• Besoin d’identifier les connaissances et moyens qui ne sont disponibles que dans un nombre limité de pays.</td></tr><tr><td>• Intérêt à essayer d’associer les consommateurs aux travaux des RLMO.</td></tr><tr><td>• Besoin d’informer les organismes de financement des activités des RLMO.</td></tr><tr><td>• Besoin pour tout État Membre de l'OIML d’être membre d’au moins une RLMO.</td></tr><tr><td>Participation des RLMO aux travaux de l'OIML</td></tr><tr><td>• Comment les RLMO peuvent-elles associier des pays non membres de l'OIML aux travaux techniques de l'OIML?</td></tr><tr><td>• Comment les besoins spécifiques d’une région peuvent-ils être présentés et pris en considération dans les travaux des TC/SC?</td></tr><tr><td>• Il a été conclu que les RLMO peuvent - et doivent - s’inscrire comme organisations en liaison des différents TC/SC ce qui leur permettrait d’exprimer leurs besoins en leur propre nom et non seulement comme commentaires d’un pays, et leur donnerait la possibilité d’être représentées par des pays non membres de l'OIML si elles le souhaitent.</td></tr><tr><td>• Il a aussi été conclu que les RLMO peuvent faciliter la mise en application des Recommandations OIML et devraient jouer un rôle important dans la mise en application des futurs MAA.</td></tr><tr><td>Relations entre les RLMO</td></tr><tr><td>• Il a été noté qu’il y avait un important besoin d’améliorer la communication entre les RLMO afin de coordonner leurs actions, d’éviter les doubles travaux, d’éviter des différences dans l’interprétation des Recommandations OIML et de partager les expériences.</td></tr><tr><td>• Il convient d’organiser annuellement une réunion des Présidents et/ou représentants désignés des RLMO, le Président du CIML, la Présidente du Conseil de Développement et le Directeur du BIML comme coordinateur de la réunion.</td></tr><tr><td>• Le BIML devra faire circuler toutes les informations appropriées entre les diverses RLMO et fournir des moyens pour faciliter l’information mutuelle.</td></tr><tr><td>Relations entre les RLMO et le Conseil de Développement</td></tr><tr><td>• Les RLMO et le Conseil de Développement doivent entretenir des liens étroits afin d’éviter les recouvments de travaux (en particulier dans le domaine de la formation) et assurer une bonne coordination et complémentarité des actions effectuées.</td></tr><tr><td>RLMO et questions de formation</td></tr><tr><td>• Ce sujet a déjà été traité en liaison avec les divers questions ci-dessus.</td></tr><tr><td>Conclusions</td></tr><tr><td>• Le BIML a été chargé de préparer un document de politique sur la position des RLMO vis-à-vis de l’OIML, ce document étant examiné par le Président du CIML et le Conseil de la Présidence en temps utile pour la prochaine réunion du CIML.</td></tr></table>

## Relations entre les RLMO

<div align="center">

# OIML Certificate System: Certificates registered 2001.08-2001.10

</div>

For up to date information: www.oiml.org

The OIML Certificate System for Measuring Instruments was introduced in 1991 to facilitate administrative procedures and lower costs associated with the international trade of measuring instruments subject to legal requirements.

The System provides the possibility for a manufacturer to obtain an OIML certificate and a test report indicating that a given instrument pattern complies with the requirements of relevant OIML International Recommendations.

Certificates are delivered by OIML Member States that have established one or several Issuing Authorities responsible for processing applications by manufacturers wishing to have their instrument patterns certified.

OIML certificates are accepted by national metrology services on a voluntary basis, and as the climate for mutual confidence and recognition of test results develops between OIML Members, the OIML Certificate System serves to simplify the pattern approval process for manufacturers and metrology authorities by eliminating costly duplication of application and test procedures.

![](page=21,bbox=[172, 1036, 1735, 1807])

<div align="center">

# Système de Certificats OIML:

Certificats enregistrés 2001.08-2001.10

</div>

Pour des informations à jour: www.oiml.org

Le Système de Certificats OIML pour les Instruments de Mesure a été introduit en 1991 afin de faciliter les procédures administratives et d'abaisser les coûts liés au commerce international des instruments de mesure soumis aux exigences légales.

Le Système permet à un constructeur d'obtenir un certificat OIML et un rapport d'essai indiquant qu'un modèle d'instrument satisfait aux exigences des Recommandations OIML applicables.

Les certificats sont délivrés par les États Membres de l'OIML, qui ont établi une ou plusieurs autorités de délivrance responsables du traitement des

demandes présentées par des constructeurs souhaitant voir certifier leurs modèles d'instruments.

Les services nationaux de métrologie légale peuvent accepter les certificats sur une base volontaire; avec le développement entre Membres OIML d'un climat de confiance mutuelle et de reconnaissance des résultats d'essais, le Système simplifie les processus d'approbation de modèle pour les constructeurs et les autorités métrologiques par l'elimination des répétitions coûteuses dans les procédures de demande et d'essai.

## INSTRUMENT CATEGORY

CATÉGORIE D'INSTRUMENT

Diaphragm gas meters

Compteurs de gaz à parois déformables

R 31 (1995)

Issuing Authority / Autorité de délivrance Gosstandart of Russian Federation, Russian Federation

R31/1995-RU-01.02 Types NPM (G 1,6; G 2,5; G 4) and NPMT (G 1,6; G 2,5; G 4) JSC Gazdevice, 142717, Asherino, Moscow Region Russian Federation

R31/1995-RU-01.03 Types NP (G 1,6; G 1,6T; G 2,5; G 2,5T; G 4; G 4T) JSC Gazdevice, 142717, Asherino, Moscow Region Russian Federation

## INSTRUMENT CATEGORY

CATÉGORIE D'INSTRUMENT

Automatic catchweighing instruments

Instruments de pesage trieurs-étiqueteurs

à fonctionnement automatique

R 51 (1996)

Issuing Authority / Autorité de délivrance Physikalisch-Technische Bundesanstalt (PTB), Germany

R51/1996-DE-01.02 WK 50 (accuracy class Y(b))

Pfreundt GmbH & Co. KG, Ramsdorfer Strasse 10,

D-46354 Südlohn, Germany

Issuing Authority / Autorité de délivrance Danish Agency for Development of Trade and Industry, Division of Metrology, Denmark

R51/1996-DK-01.01 WBC-F (Class Y(a)) Crisplant a/s, P.O. Pedersens Vej 10, DK-8200 Aarhus N Denmark

Issuing Authority / Autorité de délivrance Netherlands Measurement Institute (NMi) Certin B.V., The Netherlands

R51/1996-NL1-01.02 Type AL ... (Class Y(a) or Y(b))

Grupo Epelsa, S.L., Ctra. Sta. Cruz de Calafell, 35 km.

9,400, E-08830 Sant Boi de Llobregat, Barcelona, Spain

R51/1996-NL1-01.03 W-9000 automatic (Class Y(a) or Y(b)) Welvaarts weegsystemen, De Tweeling 4, 5215 MC's-Hertogenbosch, The Netherlands

R51/1996-NL1-01.04 CW-107 (Class Y(a)) E + E Nederland B.V., Dorpsstraat 6, 4012BG Kerk-Avezaath, The Netherlands

## INSTRUMENT CATEGORY

CATÉGORIE D'INSTRUMENT

Metrological regulation for load cells

(applicable to analog and/or digital load cells)

Réglementation métrologique des cellules de pesée

(applicable aux cellules de pesée à affichage

analogique et/ou numérique)

R60(2000)

Issuing Authority / Autorité de délivrance National Weights and Measures Laboratory (NWML), United Kingdom

Type VC 1600 (Class C1.5) Thames-Side Maywood Ltd., 17 Stadium Way, Tilehurst, Reading, Berkshire RG30 6BX United Kingdom

Issuing Authority / Autorité de délivrance Netherlands Measurement Institute (NMi) Certin B.V., The Netherlands

R60/2000-NL1-01.15 Rev.1 Mark-29 (Class C) Weigh-tronix Inc., 1000 Armstrong Drive, Fairmont MN 56031-1000, USA

R60/2000-NL1-01.16

MV (Class C)

Grupo Epelsa, S.L., Ctra. Sta. Cruz de Calafell, 35 km.

9,400, E-08830 Sant Boi de Llobregat, Barcelona, Spain

R60/2000-NL1-01.17 3530 (Class C) Tedea Huntleigh Europe Ltd., 37 Portmanmoor Road, Cardiff CF24 5HE, United Kingdom

R60/2000-NL1-01.18 Type 3410 (Class C) Tedea Huntleigh International Ltd., 5a Hatzoran St., Netanya 42506, Israël

R60/2000-NL1-01.19

1330 (Class C)

Tedea Huntleigh International Ltd., 5a Hatzoran St.,

Netanya 42506, Israël

## INSTRUMENT CATEGORY

CATÉGORIE D'INSTRUMENT

Automatic gravimetric filling instruments

Doseuses pondérales à fonctionnement automatique

R 61 (1996)

Issuing Authority / Autorité de délivrance

Physikalisch-Technische Bundesanstalt (PTB),

Germany

R61/1996-DE-01.02 SW-100 (accuracy class Ref (0.2)) ROVEMA Verpackungsmaschinen GmbH, Industriestrasse 1, D-35463 Fernwald, Germany

## INSTRUMENT CATEGORY

CATÉGORIE D'INSTRUMENT

Nonautomatic weighing instruments

Instruments de pesage à fonctionnement

non automatique

R 76-1 (1992), R 76-2 (1993)

Issuing Authority / Autorité de délivrance

Physikalisch-Technische Bundesanstalt (PTB),

Germany

## R76/1992-DE-01.03

Seca Meß- und Wiegetechnik or Vogel & Halke GmbH & Co., Hammer Steindamm 9 - 25, D-22089 Hamburg, Germany

## R76/1992-DE-01.04

## Types M985 (Class III)

Seca Meß- und Wiegetechnik or Vogel & Halke GmbH & Co., Hammer Steindamm 9 - 25, D-22089 Hamburg, Germany

## R76/1992-DE-01.05

## Types M336 (Class III)

Seca Meß- und Wiegetechnik or Vogel & Halke GmbH & Co., Hammer Steindamm 9 - 25, D-22089 Hamburg, Germany

R76/1992-DE-01.06

Types DY BI 300; DS BI 300; DN BI 300; DQ BI 300

(Class III)

Sartorius A.G., Weender Landstraße 94-108,

D-37075 Göttingen, Germany

R76/1992-DE-01.07

EL...M (Classes II and III)

Bizerba GmbH & Co. KG, Wilhelm-Kraut-Straße 65,

D-72336 Balingen, Germany

Issuing Authority / Autorité de délivrance Danish Agency for Development of Trade and Industry, Division of Metrology, Denmark

R76/1992-DK-01.02 Types 200,205,210 or 220 (Class III) Cardinal Scale Manufacturing Co.,203 East Daugherty St., Webb City, Missouri 64870, USA

Issuing Authority / Autorité de délivrance National Weights and Measures Laboratory (NWML), United Kingdom

R76/1992-GB1-00.04 Rev.1 NCR 7872 (Class III) NCR Corporation, 2651 Satellite Blvd, Duluth Georgia 30096, USA

Issuing Authority / Autorité de délivrance Netherlands Measurement Institute (NMi) Certin B.V., The Netherlands

R76/1992-NL1-01.31 SM-300... (Class III) Teraoka Seiko Co., Ltd., 13-12 Kugahara, 5-Chome, Ohta-ku, Tokyo 146-8580, Japan

## R76/1992-NL1-01.32

Type DS-688... (Class III)

Teraoka Seiko Co., Ltd., 13-12 Kugahara, 5-Chome,

Ohta-ku, Tokyo 146-8580, Japan

## R76/1992-NL1-01.33

Type DS-470... (Class III)

Teraoka Seiko Co., Ltd., 13-12 Kugahara, 5-Chome,

Ohta-ku, Tokyo 146-8580, Japan

## R76/1992-NL1-01.34

## IW-series (Class III)

Ishida Co., Ltd., 44, Sanno-cho, Shogoin, Sakyo-ku Kyoto-city 606-8392, Japan

## R76/1992-NL1-01.35

Type ECO (Class III)

Grupo Epelsa, S.L., Ctra. Sta. Cruz de Calafell, 35 km. 9,400, E-08830 Sant Boi de Llobregat, Barcelona, Spain

## R76/1992-NL1-01.37

Type CI 2000 (Class III or IIII) CAS Corporation, CAS Factory # 19 Kanap-ri, Kwangjeok-myon, Yangju-kun Kyungki-do, Rep. of Korea

## R76/1992-NL1-01.38

FX, MC, B, G, BK, HL, or S-series (Class III) GEC Avery Berkel Limited, Foundry Lane, Smethwick Warley, West Midlands B66 2LP, United Kingdom

## INSTRUMENT CATEGORY

CATÉGORIE D'INSTRUMENT

## Fuel dispensers for motor vehicles

Distributeurs de carburant pour véhicules à moteur

## R 117 (1995) [+ R 118 (1995)]

Issuing Authority / Autorité de délivrance National Weights and Measures Laboratory (NWML), United Kingdom

## R117/1995-GB1-98.03 Rev.1

Fuel dispenser for motor vehicles, Tasuno Sunny-Rex (Class 0.5)

Tatsuno Corporation, 200 Iijima-cho, Sakae-ku Yokohama, Kanagawa-pref. 244-8501, Japan

Issuing Authority / Autorité de délivrance Swedish National Testing and Research Institute AB, Sweden

R117/1995-SE-01.01

Global Century (Class 0.5)

Dresser Wayne AB, Box 30049, SE-200 61 MALMÖ,

Sweden

<div align="center">

# OIML TC 8/SC 5 Meeting

</div>

Water Meters

Brussels, 9 October 2001

JIM WILLIAMSON, TC 8/SC 5 Secretary

Ameeting of OIML TC 8/SC 5 Water meters was hosted by Mr. R. Eggermont at the Metrology Department, Ministry of Economic Affairs, Brussels on 9 October 2001. The meeting, which was chaired by Dr Michael Reader-Harris, was attended by 27 delegates, representing 11 countries.

## Progress on R 49: Water meters intended for the metering of cold potable water

## Part 1: Metrological and technical requirements

Since the previous meeting of the Subcommittee in November 2000, an addendum listing the current editions of IEC standards referenced in R 49-1 had been prepared by WG3 under the convenorship of Mr. J. Goulding, and subsequently issued by the BIML to warn members of forthcoming changes to R 49-1.

Since then, WG3 had also prepared an amendment to R 49-1 Annex A, introducing updated requirements for performance tests of water meters with electronic devices, based on the current issues of IEC standards. The amendment was subjected to a postal vote by SC 5 and had received almost unanimous support; at the meeting some corrections were applied to it. The Secretary is to send the amendment to the BIML as soon as possible and the BIML will decide whether to issue the new Annex A as a separate amendment or have it incorporated into a new edition of R 49-1.

## Part 2: Test methods

After the SC 5 meeting in November 2000, an SC 5 vote was initiated to decide whether R 49-2 should be submitted for voting by the CIML in September 2001 or delayed for one year until the amendment to R 49-1 was agreed on.

In parallel with this vote, an SC 5 P-member vote on the R 49-2 committee draft showed that a majority was

in support of the document, which was forwarded to the BIML and sent to CIML Members for postal vote. The CIML voted by a majority to accept it and comments were received from six Member States - these were taken into account in a revised draft of R 49-2, presented to the CIML for voting at its 36th Meeting. The draft was approved by a majority of the CIML Members, who had also been informed by the Bureau that the requirements for performance tests for meters with electronic devices would be subsequently updated to bring them into line with the proposed amendment to R 49-1.

As the draft of R 49-2 has now been approved by the CIML, SC 5 has nominated a small ad-hoc group to edit R 49-2 to incorporate the changes resulting from the amendment to R 49-1. Following this, the draft is to be sent to SC 5 for postal vote and comments. If the draft is accepted by the Subcommittee, it will be forwarded to the BIML for final editing and publication.

The following time scale was agreed on:

- Mr. Williamson would modify R 49-2, introducing the changes resulting from the amendment to R 49-1, together with the corrections agreed at this meeting and send it to the other members of the ad-hoc group, Mr. Goulding and Dr. Mencke, by 22 January 2002, for comment.

- After further consultation with the ad hoc group if required, the Secretary would send a finalized draft to OIML TC 8/SC 5 for postal vote and comment by 22 February 2002 . The closing date for voting would be 22 May 2002. If the vote is affirmative, the Secretary would forward the draft R 49-2 to the BIML for publication.

## Part 3: Test report format

It was agreed that this document requires further work to bring it into line with Parts 1 and 2. However, it was recognized that R 49-3 cannot be finalized before the texts of Parts 1 and 2 are complete. The Secretary was asked to update the existing CD as far as possible, in parallel with the changes to Parts 1 and 2, working to the following timescale:

- The new committee draft to be sent to the ad hoc group by 22 April 2002 for comment.

- Following this the CD would be sent to TC 8/SC 5 by 5 July 2002 for voting, with a closing date for voting of 5 September 2002.

- The draft, with any further editing that may be required, would then be sent to the BIML for a CIML postal vote and thereafter for publication if accepted.

## Future work of the Subcommittee

The opinion of the members was sought regarding the need to update R 72 Hot water meters and on requirements for cold water combination meters (for which there are no existing OIML prescriptions).

Initially a poll was taken of the delegates to find out which of the countries already had national legislation on hot water meters, with the following results:

- Countries with existing legislation on hot water meters: Austria, Belgium, Brazil, China, Denmark, France, Germany, Japan, Netherlands;

- Countries with no legislation on hot water meters: UK, USA.

- Under OIML rules, a postal vote of P-members will be initiated to find out if there is an interest in updating R 72. The vote will be drafted as a multiple questionnaire with the following options:

- Withdraw R 72;

- Leave R 72 unchanged;

- Revise and update R 72 as an independent Recommendation;

- Update and integrate the requirements for hot water meters with R 49;

- Other options.

A similar vote will be taken to ascertain whether there is a need for prescriptions for combination meters.

Note: If the Subcommittee requires new work to be carried out on hot water meters and combination meters then it is likely that there will be a need to produce an initial draft (a working document) and for a Working Group to take on the task. Member States were asked to give some advance consideration to the possibility of its delegates participating in this work, should the need arise.

## Secretary of SC 5

Dr. Alan Paton (Flow Centre, NEL, UK) was introduced as the Secretary designate of OIML TC 8/SC 5, due to the retirement of Mr. Williamson in December 2002. However, Mr. Williamson will continue with his secretarial duties in a transitional period during the coming year, in order to complete the work required on R 49-1, -2 and -3.

## Next meeting of OIML TC 8/SC 5

As the outcome of the vote on R 72 Hot water meters and work on combination meters will influence the main future workload of the Subcommittee it was decided not to set a meeting date until that outcome is known. The Secretariat will correspond with members regarding a date and venue for the next meeting. Member States in a position to offer a venue are invited to contact the Secretary.

Contact Information

MR. JIM WILLIAMSON

Secretary, OIML TC 8/SC 5

NEL Flow Centre, East Kilbride

Glasgow G75 OQU, Scotland

Tel.: +44 (0)1355 272089

Fax: +44 (0)1355 272449

e-mail: jwilliamsn@nel.uk

<div align="center">

# Automatic instruments for weighing road vehicles in motion - Part B

</div>

Teddington, 7-9 November 2001

PAUL DIXON, NWML (TC 9/SC 2 Secretariat)

Attendance: 21 delegates representing: Australia, Austria, People's Republic of China, Czech Republic, France, Germany Japan, Netherlands South Africa, Sweden, United Kingdom, United States of America and the BIML.

Chairman: Martin Birdseye, NWML (International Director)

## Main discussion topics:

Scope and application of the Recommendation

On-site verification methods

Determination of "accepted reference value" for axle load

Installation requirements

Accuracy classes and the specification of errors

Use of statistical techniques

Test methods (number and type of vehicles, number of test runs)

## 1 Background

Due to the metrological and practical difficulties associated with determining a static reference axle load for verification purposes a decision was made in 1998 to split the development of the Recommendation into two parts, thus enabling the development of Part A Total vehicle weighing to progress without being delayed by the difficulties associated with the axle load which could be dealt with separately in Part B.

## 2 Introduction to the meeting

As Part A is now nearing completion (see below), a decision was made to hold a meeting to start the development process for Part B. A Working Document

was produced by the Secretariat and circulated to the Subcommittee prior to the meeting for review. The Working Document outlined proposals for solutions to the difficulties associated with the axle load. The main aim of the meeting was to achieve a consensus on these proposals which would then enable a first Committee Draft Recommendation to be prepared.

Opening the meeting, Ian Dunmill (BIML) gave an update on the progress of the development of Part A. The Draft Recommendation had successfully negotiated the recent postal consultation and ballot of CIML Members and will therefore be submitted for approval by the CIML at its 37th Meeting in September/October 2002. He used the Memorandum of Understanding, signed by the Southeast European Cooperative Initiative (SECI) on the road transport of goods, as an example of the immediate need for Part A. There is still a requirement for a Recommendation to cover axle loads (Part B), but its development should not delay the approval of Part A.

Opening the discussion on Part B, Martin Birdseye outlined the approach that should be followed for its development. This should entail the development of Part B as a stand-alone Recommendation which would cover both total vehicle weight (incorporating the requirements from Part A) and axle load. Mr Dunmill indicated that if this approach was agreed Part B would supersede Part A, as the requirements for total vehicle weight would be duplicated. Part A could then be withdrawn and Part B issued as a new Recommendation or, alternatively, Part B could be issued as a revision to Part A, i.e. as a second edition.

## 3 Summary of decisions

Below is a brief summary of the main decisions that were reached during the meeting.

## 3.1 Scope and application

Part B should be developed as a stand-alone Recommendation, incorporating both total vehicle weight and axle load.

The Recommendation will be applicable to trade and enforcement applications.

The Recommendation will be applicable to instruments where the operating speed range (Max and Min speeds) is specified by the manufacturer and marked on the instrument.

The instrument must be installed in a "controlled weighing area" to ensure that the accuracy requirements can be durably met. Instruments will not be

permitted to be installed directly into or onto a normal road surface.

Wheel loads will not come under the scope of this Recommendation.

## 3.2 On-site verification methods

Static verification with weights will only be applied when the instrument incorporates a static weighing mode. It will not be applied to instruments that utilise "strip sensors". All instruments will be verified using pre-weighed reference vehicles.

## 3.3 Determination of "accepted reference value" for axle loads

The only traceable quantity is the (reference) total vehicle weight which must be obtained on a full draught static weighbridge. The "accepted reference value" for the axle loads will be the mean axle loads determined during the dynamic weighing tests with vehicles. The error for axle load will be specified in terms of the maximum permissible deviation of an axle load from its respective mean axle load value.

However, for enforcement applications, an additional test will be incorporated using a two-axle rigid vehicle which will be weighed statically to obtain static reference axle load values. During dynamic testing, the difference between the dynamic axle load and the static reference axle load must be within a specified maximum permissible error. This test will be included to provide the best possible evidence (confidence) that the instrument can correctly measure axle loads.

## 3.4 Installation requirements

Two different sets of requirements will be specified:

Where only the total vehicle weight is required, i.e. for trade use or enforcement of total vehicle weight overload, the requirements for the installation will be as specified in Part A. This will remain as informative guidance only.

Where the axle loads are required, i.e. for the enforcement of axle overload, mandatory requirements will be specified.

## 3.5 Accuracy classes and the specification of errors

For total vehicle weight, the accuracy classes and maximum permissible errors will be as specified in Part A.

For axle loads (enforcement applications), instruments will be divided into six accuracy classes (A, B, C, D, E and F).

There will be two different errors applicable to axle loads which will be dependent upon the test method (reference vehicle type).

i) For dynamic tests utilising the two-axle rigid reference vehicle, a maximum permissible error will be specified for the difference between the dynamic axle load and the static reference axle load.

ii) For dynamic tests utilising all other types of reference vehicles, the maximum permissible deviation of the axle load from its respective mean axle load will be specified.

A relationship between the accuracy classes for total vehicle weight and the accuracy classes for axle load will be specified.

## 3.6 Statistical techniques

The Recommendation will not incorporate statistical techniques in the method for calculating or specifying errors.

## 3.7 Test methods

The number and type of vehicles and the number of test runs required for type approval and initial verification testing of the instrument will be as specified in Part A.

## 4 Next steps

Excellent progress was made during the meeting on solving the metrological and practical difficulties associated with the axle load that had previously led to the splitting of the Recommendation. Due to the level of consensus that was reached at the meeting, it is envisaged that significant progress can now be made on the development of the Recommendation. The Secretariat intends to prepare a first Committee Draft Recommendation by the end of December 2001 for circulation to the SC.

<div align="center">

# International meeting on "New challenges to legal metrology in Europe"

</div>

Berlin, 7-8 November 2001

HARTMUT APEL, PTB, Brauschweig, Germany

![](page=29,bbox=[972, 279, 1880, 872])

On November 7 and 8, 2001, an international meeting on metrology was held at the Congress Centre of the Federal Ministry of Economics and Technology. The topic was New challenges to legal metrology in Europe, and the event was jointly organized by the Physikalisch- Technische Bundesanstalt (PTB) and the Federal Ministry of Economics and Technology (BMWi).

Globalization, deregulation and harmonization of the European measuring instrument market on the basis of a separate Measuring Instruments Directive (MID) will lead to changes in the classical structures of legal metrology, which have up to now largely been tailored to suit domestic needs.

Measures such as "accreditation" and "certification of quality management systems" go hand in hand with the growing requirement for the free circulation of goods. Activities of legal metrology, e.g. initial verification, which have to date been the task of government agencies, are to be entrusted also to manufacturers and private test laboratories. The harmonization of European standards and the requirements of international standards in the field of QM systems also increasingly determine the area regulated by law. In view of the liberalization of trade, new regulatory mechanisms must be developed for market surveillance in order to ensure consumer protection.

In view of these structural changes, the purpose of the meeting was to discuss the changes in metrology and legal metrology services resulting from these

developments on the international level, to exchange information and know-how, and to map out possible strategies to be applied in the future.

The meeting was opened by Prof. Dr. E. Gobel, PTB President. In his speech Dr. A. Tacke, Undersecretary of the BMWi, set out the basic principles of legal metrology and its importance for consumer protection and fair competition. Another fourteen speakers spoke about "Metrology and politics", "Metrology and international standardization", "Metrology and international development", and expressed their points of view as regards the new legal bases and the challenges of verification technology. Attila Szilvassy, BIML Assistant Director, reported on "International developments in legal metrology and the OIML".

The meeting was attended by 230 persons, filling the meeting room to capacity. Over 50 participants were from outside Germany and came from 26 different countries. All the presentations were given in German, even by the six speakers invited from abroad, amongst whom a guest from China. For the members of the "Legal Metrology" working group within the framework of the regional organization "European-Asian Cooperation of National Metrological Institutions" (COOMET) who had come to Berlin, the presentations were simultaneously translated into Russian.

All the presentations given will be compiled into separate conference proceedings.

![](page=29,bbox=[836, 2306, 1079, 2526])

AFRICAN REGIONAL WORKSHOP

<div align="center">

# Checking the net content in prepackages

</div>

Tunis, Tunisia 29 October-2 November 2001

GHAiET-EL-MOUNA ANNABI

Ministry of Commerce, Tunis

Workshop entitled Checking the net content in prepackages was held in Tunis from 29 October to 2 November 2001, jointly organized by the Tunisian Ministry of Commerce - Sous-Direction de la Métrologie Légale - and the PTB.

The main objectives of this Workshop were:

- To allow certain African French-speaking countries to benefit from similar workshops organized by the German Academy of Metrology (DAM - Munich) and dealing with legal metrology activities;

- To promote legal metrology in developing countries as a strategy of the OIML Development Council;

- To familiarize inspectors of national legal metrology services with regulations, measuring principles, statistical methods and test procedures regarding prepackages (OIML and Tunisian requirements for net content and labeling of prepackages).

Lectures on measurement principles, measurement and statistical methods, types of measuring instruments to be used, international requirements and Tunisian regulations, as well as practical work at the verification office and on site provided an excellent opportunity for participants to become acquainted with most of the metrological aspects of prepackage controls.

The teaching staff was composed of specialists from the Ministry of Commerce who were ready to discuss problems the participants may face in their respective countries. Manufacturers of NAWIs also presented their software for prepackage controls.

Twenty participants were selected from Benin, Burkina Faso, Republic of Djibouti, Morocco, Algeria and Tunisia, all these countries already having legal requirements for prepackages or starting work in this field. The participants felt that the knowledge gained at the Workshop would be useful for upgrading the quantity and the quality of prepackage controls in their respective countries.

## Workshop program

## Official welcome

Presentation of the Workshop concept Introduction of participants and lecturers

## Legal metrology in Tunisia

Motives of introduction of regulations regarding prepackages; Prepackages as part of the legal system; Infrastructure of legal metrology in Tunisia; Enforcement bases (checks, fees, punishment of offences).

## Basic statistics

Statistical distributions; Mean value; Standard deviation; Confidence interval; Basic requirements for statistical tests.

## Prepackages

Bases, definitions; Legal bases in Tunisia; OIML Recommendations.

## Labeling of prepackages

Net contents, price basis, information by the manufacturer; Difference between Tunisian regulations and OIML Recommendations.

## Requirements for net contents

Length, number of pieces, mass, volume, varying nominal quantity.

Test methods, sampling schemes Operating characteristics, single sampling scheme / double sampling scheme.

Prepackage control by public authorities checking of prepackages in trade With the importer; With the manufacturer (commodities are taken from stock or production).

Measuring containers / test by templates (German requirements)

## Determination of density

By using displacement method for liquids, metal and glass pycnometers, densimeters; Determination of density of aerosols.

Periodic controls by manufacturer Obligation to keep records; Suitable measuring instruments.

Presentation of weighing instruments and software for prepackage controls with practical lectures

Prepackage control with a manufacturer (noodles) Taking commodities from production; Checking records.

## OIML

Introduction to the tasks of the OIML, relevant OIML Recommendations, Documents, Members.

Tasks and activities of the OIML Development Council

Evaluation and official farewell

## Thirty-Sixth Meeting of the International Committee of Legal Metrology Item 7.2: BIML Activities (October 2000 - September 2001)

Below is a summary of BIML activities since the last CIML Meeting; this report was distributed in Moscow.

<table border="1"><tr><td>Subject</td><td>Activities</td></tr><tr><td>Follow-up of the Eleventh Conference and of the 35th CIML Meeting</td><td>- Editing and distribution of the Decisions and Resolutions (combined booklet for the Conference and CIML Meeting)
- Editing and distribution of the Minutes (separate booklets for the Conference and for the CIML Meeting)
- Implementation of the Decisions and Resolutions (see detailed information below under the various headings)</td></tr><tr><td>Preparations for the 36th CIML Meeting</td><td>- Preparations in close connection with GOSSTANDART and VNIIMS
- Information to invited countries and regional organizations (RLMOs); editing and distribution of administrative, financial and technical papers to be examined and/or discussed (see more detailed information below); design and printing of the informative brochure</td></tr><tr><td>Presidential Council</td><td>- Organization of a meeting in Paris (February 2001); preparation of reports on the various aspects of OIML activities of interest to the Council; publication of the Council meeting report in the OIML Bulletin
- Development of a short-term action plan for the Presidential Council
- Preparations for a meeting in Moscow in September 2001
- Multiple contacts with the CIML President and Vice-Presidents</td></tr><tr><td>Development Council</td><td>- Editing and distribution of the Minutes of the London meeting
- Working meetings with the Chairperson of the Development Council; contacts with the secretariats of the DC working groups
- Development of the DC (and working group) work programs
- Preparations for the Moscow meeting
- Liaisons with ISO/DEVCO/CASCO, UNIDO, WTO, etc.
- Contacts with national bodies offering assistance to developing countries (DAM-Germany, PTB-Germany, SDM-France, ESM-France, NSC-Australia, NWML-UK, VNIIMS-Russia, etc.)</td></tr><tr><td>OIML Policy</td><td>- Assessment of activities for 2000 (with distribution to OIML Members and publication in the OIML Bulletin and on the web site)
- Updating of the 1999-2002 Action Plan and extension to cover the period 2003-2004 for submission to the 36th CIML Meeting</td></tr><tr><td>Technical Committees and Subcommittees</td><td>- Annual reports: distribution to CIML Members and publication of a synthesis in the OIML Bulletin; reports to the Presidential Council and the CIML
- Establishment of a list of high priority and priority projects
- Implementation of OIML Recommendations: finalization of the quadrennial inquiry and preparation of the report
- Examination of the situation of, and contact with, numerous TCs/SCs
- Participation in the work of certain TCs/SCs (see participation in meetings below)
- Active participation in the work of TC 3 (revision of D 1) and in that of TC 3/SC 5 (MAA and OIML Certificate System) for which the BIML is Co-Secretariat
- Liaison between certain TCs/SCs and international and regional bodies
- Postal inquiries concerning a number of drafts; distribution of four draft Recommendations for approval by the CIML at its 36th Meeting
- Updating of papers (state of progress, etc.) related to TCs/SCs; establishment of a list of contact persons; permanent updating of information posted on the OIML web site
- Starting the review of the Directives for the technical work</td></tr></table>

<table border="1"><tr><td>Participation in OIML technical meetings</td><td>-TC8/SC5(Paris,November2000)
-TC3/SC5working group on uncertainty(Paris,November2000andMay2001)
-TC17/SC1(Berlin,June2001)</td></tr><tr><td>Certification</td><td>-Registration ofOIML certificates;information toOIML Members;list of certificates published in theOIML Bulletin and on theweb site
-Development and distribution ofa2CD revision of the document ontheOIML Certificate System(TC3/SC5)
-Reports for thePresidential Council andCIML
-Follow-up of conformity assessment,quality management,certificationand accreditation and other activities withinIAF,ILAC,ISO/IEC,WTO,UN/ECE,EA,etc.</td></tr><tr><td>Technical publications</td><td>-Editing,posting on theweb site,printing and distributing ofR49-1,R60,R65,R129,R130andR131,and theVIML(in most casesEnglish andFrench versions);preparing forprintingR81(AnnexD),R132andD27</td></tr><tr><td>OIML Bulletin</td><td>-Production offourissues
-New design
-Proof-reading and author approval ofall articles before publication,now almost exclusivelybye-mail
-Preparation ofreports and information for publication in theBulletin
-Nowonline ontheOIMLweb site
-Ever wideningscope oforiginal contributions</td></tr><tr><td>Communication andweb site</td><td>-Website improved,expanded and regularlyupdated;newpagesadded
-NewhighspeedInternetconnection
-Online publication orderingfacility
-Preliminarywork ononlinepaymentofOIMLPublications(securepaymentbycreditcard)
-Development ofe-mailcommunicationinpreference topaperwherepossible
-Modernization oftheBIMLdesktoppublishingcomputerequipment
-Internalnetworking ofBIMLcomputers
-Preparationunderwayofa newBIMLdatabaseincorporatingallMemberdetails,TC/SCtechnicalactivities,publications,pricing,etc.
-RegularupdateoftheBlueBrochureAnnexes
-UpdatingofOIMLPosters</td></tr><tr><td>Liaisonswithinternationalinstitutions(includingparticipationinmeetings)</td><td>-ISODEVCOandOpenSession(Beijing,October2000)
-ILACGeneralAssembly(Washington,November2000)
-WTO/UNIDO/SDM/OIMLSeminarfordevelopingcountries(Paris,November2000)
-JCGMWG1&amp;2(Paris,November2000andMay2001)
-UN/ECEWorkingParty(Geneva,November2000)
-WTOTBTCommitteemeetings,includingmeetingsspecifictointernationalstandard-settingorganizationsandtodevelopingcountries(Geneva,January,MarchandJune2001)
-JointBIPM/ILAC/OIMLmeeting(BIML,February2001)</td></tr><tr><td>Liaisonswithregionalinstitutions(includingparticipationinmeetings)</td><td>-SADCMEL(Arusha,November2000,Maseru,April2001)
-WELMECCommitteeMeeting(Dublin,May2001),WELMECWG8meetings(Paris,December2000andFebruary2001)
-EMLMF(Poitiers,June2001)
-SouthEastEuropeanCooperationonvehicleweighing(Istanbul,June2001)</td></tr><tr><td>ParticipationinmeetingsorganizedbyOIMLMembers</td><td>-Metrologia2000(SaoPaulo,December2000)
-NISTcentenary(Gaithersburg,March2001)
-SymposiumonMetrology(Queretaro,May2001)
-InaugurationofMETASnewbuildingandEurometmeeting(Wabern,May2001)</td></tr><tr><td colspan="2">Note:Miscellaneousinformationandvisitsfrom/toOIMLMembersareno longersystematicallymentionedinordertomaintainthisreportasshortaspossible.</td></tr></table>

![](page=3,bbox=[62, 89, 209, 219])

<div align="center">

# What will Legal Metrology be in the Year 2020?

</div>

![](page=3,bbox=[1654, 13, 1953, 332])

Legal metrology must not only react to profound changes in the needs of society, technology, administrative organization, political structures and priorities, but it must also adapt to international globalization.

In September 2002 the OIML will be organizing a Workshop related to the long term fundamental evolution of legal metrology. This

Workshop will be open to OIML Member States and Corresponding Members, other interested organizations and representatives from industry; it will allow participants to exchange views on the major trends in legal metrology and to consider these views in the context of their own national policy. Some of the issues which will be addressed are listed below.

## Scope of legal metrology

New fields of measurement are developing in trade, safety, the environment and law enforcement. In parallel, many countries are endeavoring to reduce both State intervention and the number of regulations in force. What will be the implications on regulations resulting from these two contradictory considerations?

## New technologies and information technologies

New technologies make it possible to record and process measurement results in remote databases, and so measuring instruments may become just one of the functions of complex systems. What will remain of the current notions related to such instruments and how should legal metrology adapt to this? Will manufacturers of measuring instruments still exist as such?

## Role of the State

A general trend in many countries is to contract most technical activities out to specialized independent bodies while the authorities play a role of orientation, monitoring and surveillance. What will a legal metrology department look like in twenty years?

## Future of legal metrology technical bodies

Legal metrology bodies in charge of technical evaluations are increasingly private or semi-private. At the same time, mutual recognitions result in a reduction in their volume of activity and in their specialization. Will these bodies become trans-national? Will they be replaced by an international network of technical bodies? What will be the consequences of this evolution? How will States monitor these bodies?

## Conformity assessment and market surveillance

Due to the technical evolution of instruments and to the development of quality assurance procedures, conformity assessment of instruments is achieved partially by means of third party evaluation and partially from the liability of the manufacturer. A third party ensures more impartiality, whereas the manufacturer may assure a better control over the conformity. How will this balance evolve?

What should State market surveillance activities be, and what should be placed under surveillance?

The BIML has received a number of papers which would be well-suited for presentation in this Workshop; the final selection will be carried out by the Presidential Council in February 2002 and updated information will be included on the OIML web site as and when available. The dates and venue have been arranged in line with the 37th CIML Meeting:

26-27 September 2002 Saint-Jean-de-Luz (South-West France)

![](page=3,bbox=[1448, 2442, 1744, 2686])

ACTION PLAN REVISED VERSION, NOVEMBER 2001

OIML LONG-TERM POLICY: 1999-2002 ACTION PLAN with preliminary extension to 2003-2004

Implementation of the Braunschweig International Seminar (June 1998), of the Birkeland Report and of discussions held at the $ 33 ^{rd} $ , $ 34^{th} $ , $ 35^{th} $ and $ 36^{th} $ CIML Meetings and at the Eleventh OIML Conference

![](page=4,bbox=[697, 2248, 1057, 2546])

ORGANISATION INTERNATIONALE

DE MÉTROLOGIE LÉGALE

INTERNATIONAL ORGANIZATION OF LEGAL METROLOGY

OIML LONG-TERM POLICY: 1999-2002 ACTION PLAN with preliminary extension to 2003-2004

Implementation of the Braunschweig International Seminar (June 1998), of the Birkeland Report and of discussions held at the $ 33 ^{rd} $ $ 34^{th} $ $ 35^{th} $ and $ 36^{th} $ CIML Meetings and at the Eleventh OIML Conference

FIRST ISSUED BY THE BIML: April 2000 REVISED VERSION ISSUED BY THE BIML: November 2001

## Contents

Introduction ... 3

A - Facilitation of trade of measuring instruments ... 4

B - Promotion of acceptance of measurement results in international trade ... 6

C - Promotion and development of legal metrology in OIML Member States ... 8

D - Structural improvements ... 9

Bureau International de Métrologie Légale 11, rue Turgot - 75009 Paris - France

Telephone: 33(0)148781282 and 42852711

Fax: 33(0)142821727

E-mail: biml@oiml.org

Internet: www.oiml.org

<div align="center">

# Introduction

</div>

Defining the OIML Long-term policy is the responsibility of the Conference, but implementing the Conference decisions is that of the Committee. In this connection, 1998 was marked by two important events, both in line with the decisions made by the Tenth OIML Conference in Vancouver:

- the International Seminar on The Role of Metrology in Economic and Social Development, organized in June 1998 in Braunschweig through close cooperation between the BIPM, IMEKO, the OIML and the German Physikalisch-Technische Bundesanstalt, and referred to during the $ 33 ^{rd} $ CIML Meeting in October 1998 in Seoul;

- the examination of the Birkeland Report and discussion of its recommendations during the $ 33 ^{rd} $ CIML Meeting.

In line with the decisions made by the CIML at its $ 33 ^{rd} $ Meeting, the CIML President - assisted by his Council and by the BIML - developed a draft 1999-2002 Action Plan which was finalized and approved by the CIML at its $ 34 ^{th} $ Meeting (1999) before being endorsed by the Eleventh OIML Conference (2000) which "requested the CIML to monitor its implementation and to extend it as far as necessary in order to cover the 2002-2004 period".

At its 35th Meeting (2000) the CIML requested its President, the Presidium and the Presidential Council to monitor the Conference's decisions and to report back to the next CIML Meeting.

A Draft Revision 1 (March 2001) was drawn up based on the discussions within the Presidential Council and taking into account the actual state of progress of the various actions; it was distributed to CIML Members on 2001.05.15 for examination.

Based on the comments received, a Draft Revision 2 was submitted for approval by the CIML at its $ 36^{\mathrm{th}} $ Meeting, on the occasion of which the following Resolution was adopted:

The International Committee of Legal Metrology

CONSIDERING the decision of the Eleventh Conference concerning the OIML long-term policy;

CONSIDERING the draft revision 2 of the 1999-2002 Action Plan with preliminary extension to 2003-2004;

CONSIDERING the comments expressed by certain CIML Members;

INSTRUCTS the BIML, under the supervision of the CIML President, to publish this new Action Plan taking into account the comments received and to distribute it to all OIML bodies concerned, for implementation, and to interested international and regional institutions, for information;

INSTRUCTS the CIML President to report on the implementation of this Action Plan at future CIML Meetings;

INSTRUCTS the CIML President and his Council to reflect about any necessary extension of this Action Plan so as to fully cover the period 2003-2004, and to prepare a draft with a view to its approval by the CIML at its 37th Meeting.

This Revised Version of the Action Plan dated November 2001 has been published by the BIML in application of the above CIML Resolution.

## Note concerning the list of actions

The actions have been classified according to four categories corresponding to:

a) three fundamental aims of the OIML, i.e.:

- to facilitate trade of measuring instruments;

- to develop confidence in an international legal metrology system that would promote mutual acceptance of measurement results in international trade (bulk measurements, prepacked products, etc.), reduce disputations and minimize transaction costs, including the removal of conflicting interests between involved parties (buyer, seller, customer, etc.); and

- to promote and develop legal metrology in all OIML Member States as a universal activity implying all ministerial departments and administrations responsible for activities with an economic or social impact;

and

b) necessary structural improvements within the OIML.

However, a certain degree of overlap may exist between these four categories.

On the following pages, each action is briefly described and supplemented by information concerning:

- the person(s) or body(ies) responsible for undertaking it (being understood that in many cases the CIML will be responsible for final approval);

- the expected start date;

- the expected date by which the action should be completed (with "-" for permanently ongoing or long-term actions).

Within each of the four categories, objectives have in addition been sub-divided and actions have been numbered to facilitate their implementation.

## A - Facilitation of trade of measuring instruments

## Objectives and actions

A.1 To improve and accelerate the technical activity of TCs/SCs and increase participation of OIML Members

## A.1.1 To revise the Directives for the technical work in order to:

a) improve the quality and rapidity of the work, provide for the development of "horizontal" papers to be implemented by TCs/SCs in order to solve in a harmonized manner problems of general interest (software, etc.), improve the format of test reports, develop the use of modern communication methods (e-mail, web sites for TCs/ SCs, etc.);

b) better fulfill the rules of the WTO TBT Code of good practice for the preparation, adoption and application of standards in so far as they apply to OIML work;

c) include requirements for reference standards, traceability, uncertainties, software testing, etc. in test procedures;

d) include formats for verification and inspection (in addition to current test report formats); and

e) develop a fast track for amending existing Recommendations.

A.1.2 To prepare a short summary of the essential rules of the Directives for easy and permanent use by secretariats and members of TCs/SCs.

A.1.3 To carefully review the work programs of TCs/SCs and establish priorities, especially by taking into consideration the needs of developing countries (mainly TCs 3, 4 and 6), the necessity to develop the OIML Certificate System and the importance of reacting rapidly to requests from Regional Legal Metrology Organizations (RLMOs) (e.g. electronic taximeters) and more generally the economic and social impacts of OIML Recommendations. To examine the work programs of other international bodies, particularly in order to identify fields where certain OIML Recommendations could be developed with reference to existing publications of such bodies.

A.1.4 To urge CIML Members to increase their countries' participation in TC/SC activities even in fields where their services are not directly responsible. (Also connected with the revision of the Guide for CIML Members).

A.1.5 To accelerate the activity on software associated with measuring instruments with participation and implementation by other TCs and SCs concerned in order to identify for which instruments software is most important.

<table border="1"><tr><td>Responsible person/body</td><td>Start in</td><td>Complete by</td></tr><tr><td>BIML+TCs/SCs concerned(e.g.:TC3/SC5 for uncertainties)</td><td>Already started</td><td>April2002</td></tr><tr><td>BIML</td><td>April2002</td><td>June2002</td></tr><tr><td>Presidential Council</td><td>Already started</td><td>-</td></tr><tr><td>CIML President</td><td></td><td>Completed(but this is also a permanent action)</td></tr><tr><td>TC5/SC2+TCs/SCs concerned</td><td>Already started</td><td>-</td></tr></table>

## A - Facilitation of trade of measuring instruments (cont'd)

## Objectives and actions

A.2 To develop the OIML Certificate System in order to better respond to the needs of manufacturers and users of measuring instruments, and to those of legal metrology services, in particular in the following directions:

a) certification of types of modules of measuring instruments;

b) certification of families of types of measuring instruments or modules;

c) acceptance of OIML certificates in connection with the agreements provided for under B.1.1 below; and

d) certification of individual measuring instruments or modules.

<table border="1"><tr><td>Responsible person/body</td><td>Start in</td><td>Complete by</td></tr><tr><td>TC 3/SC 5</td><td></td><td></td></tr><tr><td></td><td>Already started</td><td>2002</td></tr><tr><td></td><td>Already started</td><td>2002</td></tr><tr><td></td><td>See B.1.1</td><td></td></tr><tr><td></td><td>2002</td><td>-</td></tr><tr><td></td><td colspan="2">To be started as soon as the current revision of the document on the OIML Certificate System for Measuring Instruments is completed</td></tr></table>

## B - Promotion of acceptance of measurement results in international trade

<table border="1"><tr><td>Objectives and actions</td><td>Responsible person/body</td><td>Start in</td><td>Complete by</td></tr><tr><td>B.1 To develop procedures for acceptance or equivalence agreements</td><td></td><td></td><td></td></tr><tr><td>B.1.1 To develop a system of acceptance of test results based on agreed capability.</td><td>TC 3/SC 5</td><td>Already started</td><td>a.s.a.p</td></tr><tr><td>B.2 To favor the accreditation of legal metrology laboratories with a view to achieving acceptance of test results</td><td></td><td></td><td></td></tr><tr><td>B.2.1 To develop, in close cooperation with IAF, ILAC and ISO, annexes to (i) ISO 17025 and (ii) ISO/IEC Guide 65 to facilitate uniform implementation of these guidelines by(i) legal metrology laboratories (and thus promoting their accreditation in the testing of instruments according to OIML requirements) and(ii) legal metrology services responsible for type approval and verification.</td><td>TC 3/SC 5</td><td>Already started</td><td>2002</td></tr><tr><td>B.2.2 To establish, regularly update and publish on the OIML web site a register of laboratories performing testing for type approval, with mention of, according to cases:fields(OIML Recommendations)for which they have been appointed or notified,and by whom;measurement capabilities,information on traceability,etc.;if they are accredited,by whom and for what;andhave they participated in peer review exercises?etc.</td><td>BIML</td><td>Already started</td><td>2002</td></tr></table>

- have they participated in peer review exercises? etc.

## B.3 To facilitate acceptance of test results by evidencing the equivalence of test procedures

B.3.1 To promote the organization (preferably at regional level) of intercomparisons concerning:

a) testing standards and equipment, in order to prove their equivalence;

b) the testing of measuring instruments, in order to prove that participating legal metrology laboratories may implement OIML requirements uniformly.

Discrepancies found in such intercomparisons should, according to cases, result in:

- clarifying OIML requirements;

- improving the traceability systems, test equipment, test procedures, etc. of certain laboratories;

- suggesting the development of specific supplementary comparisons by the BIPM and/or regional metrology bodies; and

- develop training activities.

- to stimulate RLMOs to organize intercomparisons;

- to develop a basic document describing objectives and procedures of intercomparison;

- to coordinate intercomparison activities amongst regions;

- to publish the results; and

- to draw conclusions concerning OIML technical activities and general policy.

## B - Promotion of acceptance of measurement results in international trade (cont'd)

<table border="1"><tr><td></td><td>Objectives and actions</td><td>Responsible person/body</td><td>Start in</td><td>Complete by</td></tr><tr><td>B.4</td><td>To promote the international trade of prepacked products according to OIML requirements</td><td></td><td></td><td></td></tr><tr><td>B.4.1</td><td>To review/develop OIML requirements concerning the net content of prepacked products and their checking for conformity.</td><td>TC6</td><td>Already started</td><td>2002</td></tr><tr><td>B.4.2</td><td>To develop an OIML system for marking prepacked products which meet OIML requirements.</td><td>TC6</td><td>Already started</td><td>2003/2004</td></tr><tr><td>B.4.3</td><td>To examine the possibility of setting up a system to establish confidence in measurement results at national level(e.g.for consumer protection)and international level(development of international trade-bulk measurements, prepacked products-,protection of emerging economies).</td><td>Presidential Council</td><td>2002</td><td>-</td></tr></table>

## C - Promotion and development of legal metrology in OIML Member States

<table border="1"><tr><td>Objectives and actions</td><td>Responsible person/body</td><td>Start in</td><td>Complete by</td></tr><tr><td>C.1 To demonstrate the importance of legal metrology and to identify the basis of legal metrology and its specific place amongst other aspects of metrology and related activities</td><td></td><td></td><td></td></tr><tr><td>C.1.1 a) To study(in close relations with ministries concerned in various OIML Member States and with international and regional economic and trade organizations)the economic impact of legal metrology and the cost to international trade resulting from inefficient and non-harmonized legal metrology systems, including a risk analysis.</td><td>Presidential Council(with the assistance of experts)</td><td>Already started</td><td>a.s.a.p.</td></tr><tr><td>b) To develop resources(papers, videos, etc.) evidencing the role of legal metrology in economic and social development,in order to help CIML Members promote legal metrology at national level.</td><td>Presidential Council,BIMLand other bodies concerned</td><td>-</td><td>-</td></tr><tr><td>c) To develop papers showing the interconnection and differences between legal metrology and other metrological activities(calibration,applied metrology,industrial aspects,etc.)</td><td>Presidential Counciland BIML</td><td>1) November 2001:Ask CIML Members to provide BIML with lectures/papers already delivered/published at national/regional levels2) In 2002:Define which papers should be developed by the CIML(articles in the Bulletin,International Documents,etc.)</td><td>-</td></tr><tr><td>C.1.2 To urgently review OIML D1,Law on Metrology and other related publications.</td><td>TC3</td><td>Already started</td><td>a.s.a.p.</td></tr></table>

## D - Structural improvements

<table border="1"><tr><td></td><td>Objectives and actions</td><td>Responsible person/body</td><td>Start in</td><td>Complete by</td></tr><tr><td colspan="5">D.1 To facilitate and improve the work of CIML Members</td></tr><tr><td colspan="2">D.1.1 To revise the Guide for CIML Members focusing on their responsibilities in organizing their countries&#x27; participation in OIML technical activities, in the OIML Certificate System and in the mutual recognition agreements developed within the OIML.</td><td>BIML and Presidential Council</td><td></td><td>Completed</td></tr><tr><td colspan="5">D.2 To improve the effectiveness of the Presidential Council</td></tr><tr><td colspan="2">D.2.1 To review the terms of reference for the Presidential Council, its composition, periodicity of meetings and information given to the CIML concerning discussions held within the Council.</td><td>CIML President</td><td></td><td>Completed</td></tr><tr><td colspan="5">D.3 To improve the activity of the BIML</td></tr><tr><td colspan="2">D.3.1 a) To carefully examine the global responsibilities of the BIML (including providing assistance in technical work) and evaluate the necessary human resources.b) To define a distribution of the work which would permit the BIML Director to devote most of his time to external affairs (strategy and policy, public relations, liaisons with other international and regional organizations) in addition to management matters, without devoting too much time to internal affairs.c) To examine the opportunity to hire experts for specific tasks and periods.</td><td>BIML, Presidium, Presidential Council,CIML, Conference</td><td>Already startedAlready startedAlready started</td><td>--</td></tr><tr><td colspan="5">D.4 To improve cooperation between the OIML and Regional Legal Metrology Organizations (RLMOs)</td></tr><tr><td colspan="2">D.4.1 a) To develop a policy paper concerning certain aspects of OIML/RLMO interactions.b) To identify the role of RLMOs as complementary to that of the OIML; to assess whether RLMOs implement OIML work; to promote regional cooperation, making it possible for all OIML Members to participate in one or more RLMOs should they so wish; to issue a directory of RLMOs and a paper describing regional cooperation.</td><td>Presidential Council and BIMLPresidential Council</td><td>-</td><td>2002Already started</td></tr><tr><td colspan="2">D.4.2 To officially invite RLMOs to CIML Meetings(in addition to OIML Conferences).</td><td>CIML President</td><td>Already started</td><td>-</td></tr><tr><td colspan="2">D.4.3 To invite relevant RLMOs to attend Presidential Council meetings.</td><td>CIML President</td><td>Already started</td><td>-</td></tr><tr><td colspan="2">D.4.4 To invite relevant RLMOs to attend Development Council meetings.</td><td>Development Council Chairperson</td><td>Already started</td><td>-</td></tr></table>

Note to D.4.3 and D.4.4: "Relevant" refers to RLMOs which are carrying out activities that may contribute to OIML work

## D - Structural improvements (cont'd)

<table border="1"><tr><td></td><td>Objectives and actions</td><td>Responsible person/body</td><td>Start in</td><td>Complete by</td></tr><tr><td colspan="5">D.5 To improve cooperation between the OIML and other international and regional bodies</td></tr><tr><td colspan="5">D.5.0 General
To develop a policy paper governing liaisons between the OIML and other international and regional bodies.</td></tr><tr><td colspan="5">D.5.1 Meter Convention
To identify with representatives of the Meter Convention(CIPM and BIPM) matters which should preferably be solved through joint actions; to establish appropriate mechanisms for action.</td></tr><tr><td colspan="5">D.5.2 WTO
To continue to have contacts with the WTO, with a view to identifying those OIML activities which may contribute to WTO/TBT Committee goals; to develop these activities in cooperation with - and possibly with the support of - the WTO/TBT Committee; to examine whether other WTO activities could be connected with OIML responsibilities.</td></tr><tr><td colspan="5">D.5.3 ILAC
To establish meetings (periodical or not) with representatives of ILAC with a view to:
• obtaining their assistance in implementing accreditation in legal metrology;
• offering OIML participation or assistance in certain ILAC activities.</td></tr><tr><td colspan="5">D.5.4 IAF
To convene a joint IAF/OIML meeting in order to identify activities of common interest, especially in fields connected with the accreditation of legal metrology services as certifying bodies.</td></tr><tr><td colspan="5">D.5.5 ISO/IEC and other international and regional standardization bodies
a) To clarify the differences between international/regional written standards and OIML Recommendations.
b) To reexamine the 1979 agreement concerning the ways for ISO/IEC and the OIML to deal with matters of common interest and to propose amendments if appropriate.
c) To examine the possibility for the OIML to work with reference to the publications of ISO/IEC and others, when appropriate.
d) To develop joint activities in specific fields (e.g. developing countries).</td></tr><tr><td colspan="5">D.5.6 JCGM
To monitor and develop OIML participation in JCGM activities</td></tr><tr><td></td><td></td><td>CIML President,BIML and other</td><td>Already started</td><td>-</td></tr></table>

<table border="1"><tr><td>CIML President,BIML and other appropriate bodies</td><td>Already started</td><td>-</td></tr></table>

## D - Structural improvements (cont'd)

<table border="1"><tr><td></td><td>Objectives and actions</td><td>Responsible person/body</td><td>Start in</td><td>Complete by</td></tr><tr><td>D.5.7</td><td>European Commission and CEN/CENELEC</td><td></td><td></td><td></td></tr><tr><td></td><td>To maintain links with the European Commission, CEN and CENELEC to make sure that OIML Recommendations are appropriately implemented within the EU and to review the OIML/CEN and OIML/CENELEC agreements as far as necessary from the point of view of the OIML.</td><td>CIML, CIML President, Presidential Council &amp; BIML</td><td>Already started</td><td>-</td></tr><tr><td>D.5.8</td><td>WHO</td><td></td><td></td><td></td></tr><tr><td></td><td>To reestablish links with the WHO and identify matters of common interest.</td><td>CIML President, TC 18 and BIML</td><td>2001</td><td>-</td></tr><tr><td>D.5.9</td><td>Consumer associations</td><td></td><td></td><td></td></tr><tr><td></td><td>To identify consumer associations, at international and regional levels, likely to cooperate with the OIML.</td><td>CIML President and BIML</td><td>2001</td><td>-</td></tr><tr><td>D.5.10</td><td>Various international and regional bodies</td><td></td><td></td><td></td></tr><tr><td></td><td>To make a survey on those international and regional bodies having activities in which legal metrology may play a role, including industry associations (manufacturers and users of measuring instruments).</td><td>CIML President and BIML</td><td>Already started</td><td>-</td></tr><tr><td>D.6</td><td>To improve the operation of the Development Council</td><td></td><td></td><td></td></tr><tr><td>D.6.1</td><td>To create more effective interaction between the Development Council and the Presidential Council, with a view to(i) discussions within the Development Council being influenced by general strategy discussions within the Presidential Council and(ii) actions proposed by the Development Council being examined by the Presidential Council before submission to the CIML.</td><td>CIML President, Development Council Chairperson and BIML</td><td></td><td>Completed</td></tr><tr><td>D.6.2</td><td>To reestablish the Development Council long-term work program.</td><td>Development Council Chairperson and Members and BIML</td><td></td><td>Completed</td></tr><tr><td>D.6.3</td><td>To develop links between the Development Council and various other international and regional bodies including RLMOs, the WTO, UNIDO, ISO and also with development bodies (World Bank, etc.) which should be more aware of the importance of legal metrology.</td><td>Development Council Chairperson and BIML</td><td>Already started</td><td>-</td></tr><tr><td>D.6.4</td><td>To establish a database of experts within the OIML for use by UNIDO, UNDP, etc.</td><td>BIML</td><td>Already started</td><td>-</td></tr><tr><td>D.6.5</td><td>To develop the Development Council web site.</td><td>Development Council Chairperson and BIML</td><td>Already started</td><td>-</td></tr></table>

## D - Structural improvements (cont'd)

<table border="1"><tr><td></td><td>Objectives and actions</td><td>Responsible person/body</td><td>Start in</td><td>Complete b</td></tr><tr><td colspan="5">D.7 Training: to facilitate harmonized development of legal metrology training systems in OIML Member States and to make training facilities available for OIML Members that do not have such systems</td></tr><tr><td>D.7.1 To review/develop recommended training programs for the various levels of responsibilities within national legal metrology services.</td><td>Development Council WG 1</td><td>Already started</td><td>-</td><td></td></tr><tr><td>D.7.2 To publish lists of schools, universities, etc. which provide such training courses and which are open to foreign trainees.</td><td>BIML</td><td>Already started</td><td>-</td><td></td></tr><tr><td>D.7.3 To coordinate the development (by countries or regions) of training material (written syllabus, videos, etc.) and their use by other countries/regions.</td><td>Presidential and Development Councils, together with funding agencies</td><td>Already started</td><td>-</td><td></td></tr><tr><td>D.7.4 To contact donor agencies or countries with a view to facilitating the use of these training facilities by developing countries.</td><td>BIML</td><td>Already started</td><td>-</td><td></td></tr><tr><td>D.7.5 To consider the development of a legal metrology training network and validation (certification) of legal metrology training courses.</td><td>Presidential Council</td><td>2001</td><td>-</td><td></td></tr><tr><td colspan="5">D.8 Public relations; promotion of OIML activities</td></tr><tr><td>D.8.1 To review the OIML general information brochure.</td><td>BIML</td><td>2002</td><td>2002</td><td></td></tr><tr><td>D.8.2 To develop leaflets presenting specific aspects of OIML activities.</td><td>BIML</td><td>2002</td><td>2002</td><td></td></tr><tr><td>D.8.3 To develop the OIML web site by introducing for example work programs, progress of technical work, information on meetings, content of the most recent OIML Bulletins, etc.</td><td>BIML</td><td>Already started</td><td>-</td><td></td></tr><tr><td>D.8.4 To encourage OIML Members to publish OIML publications translated into their national languages.</td><td>BIML</td><td>Already started</td><td>-</td><td></td></tr><tr><td>D.8.5 To reflect about the opportunity to have OIML Publications available on the web, either free of charge for everybody or free for legal metrology services of OIML Members, liaisons institutions, etc. and against payment for others (and perhaps to reduce the amount of printed publications).</td><td>Presidential Council and BIML</td><td>Already started</td><td>2002</td><td></td></tr><tr><td>D.8.6 To pursue the promotion and dissemination of the OIML Bulletin.</td><td>BIML</td><td>Already started</td><td>-</td><td></td></tr></table>

<div align="center">

# Forthcoming event: Announcement

</div>

Traceability and uncertainty are important elements of measurement results and for this reason they are given greater emphasis in ISO/IEC 17025 than in Guide 25. The main objective of this Workshop is to share experiences and to develop guidance on how these requirements can be met in a cost-effective manner.

After reviewing these requirements, the first session will concentrate on the experience gained using the second edition of the EURACHEM/CITAC Guide "Quantifying Uncertainty in Analytical Measurement" with particular emphasis on the use of validation data in uncertainty estimation. Working Groups will consider such topics as practical examples of uncertainty evaluation, design of validation studies to provide uncertainty data and experience on implementation of ISO/IEC 17025. In addition, topics not covered in the current edition of the EURACHEM/CITAC Guide, such as evaluation of uncertainty near detection limits and in qualitative analysis will be discussed, together with current work being carried out to update the GUM.

The second session will cover the EURACHEM/CITAC Draft Guide on Measurement Traceability, giving practical guidance on how to establish the traceability of results obtained using existing methods. Selection and use of reference materials for establishing traceability will be discussed, as will the international work being carried out under the auspices of the BIPM to provide traceability to the SI.

It is proposed to hold Working Groups on traceability for existing methods, traceability and method development, selection and use of reference materials, accreditation and the development of an international traceability system.

![](page=16,bbox=[1111, 1223, 1294, 1288])

Eurachem

![](page=16,bbox=[1724, 1207, 1785, 1315])

Workshop on Measurement Traceability and Uncertainty in Analytical Chemistry

Meeting the Requirements of ISO/IEC 17025

Culture and Convection Centre

Luzern / Switzerland

Introductory Lectures: June 16, 2002

Workshop: June 17-18, 2002

First Circular Workshop Programme Call for Posters

Register on line at

www.workshop2002.ch

![](page=16,bbox=[1561, 1610, 1783, 2039])

In co-operation with:

![](page=16,bbox=[1117, 2171, 1277, 2230])

![](page=16,bbox=[1293, 2164, 1389, 2251])

![](page=16,bbox=[1749, 2178, 1792, 2232])

The OIML is pleased to welcome the following new

CIML Members

Bulgaria

Mr. Ivelin Burov

Mr. Wang Qinping

China

United Kingdom

(Saint Jean de Luz, France)

Mr. Martin Birdseye

2002. 09.26-27

## OIML Meetings

SEMINAR:

What will legal metrology be in the year 2020?

2002. 09.30-2002.10.04

(Saint Jean de Luz, France)

DEVELOPMENT COUNCIL MEETING

37TH CIML MEETING

RLMO MEETING

## Committee Drafts

received by the BIML, 2001.08.01-2001.10.31

<table border="1"><tr><td>Framework for a Mutual Acceptance Arrangement on OIML type evaluations</td><td>E</td><td>8CD</td><td>TC3/SC5</td><td>USA</td></tr><tr><td>OIML Certificate System for Measuring Instruments</td><td>E</td><td>2CD</td><td>TC3/SC5</td><td>USA+BIML</td></tr><tr><td>Revision of D9: Principles of metrological supervision</td><td>E</td><td>2CD</td><td>TC3/SC2</td><td>Czech Republic</td></tr></table>

## www.oiml.org

Stay informed

The Editors of the OIML Bulletin

and the BIML staff wish all

of our Members and Readers

a very happy and prosperous

New Year for 2002.