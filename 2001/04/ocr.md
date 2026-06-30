![](page=0,bbox=[182, 217, 266, 303])

<div align="center">

# Editorial

</div>

![](page=0,bbox=[1478, 144, 1809, 562])

Responding to the needs

Jean-François Magaña

The globalization of economies and the opening up of markets are generating increased activity on the part of the OIML. Liaisons with the WTO and other international and regional organizations are becoming increasingly important.

To cater for this evolution, we must rapidly develop and update the necessary Recommendations and Documents, and set up the relevant mutual recognition procedures. Questions relating to developing countries are also becoming a growing priority within the OIML.

The role of regional legal metrology organizations (RLMOs) is a key factor in that they act both as a complement and as a relay for our organization, and so the appropriate coordination mechanisms must be strengthened.

Lastly, developments in technology and especially those in information technology are profoundly transforming the nature of measuring instruments, and thus concern all our fields of work.

With an unchanged number of staff and proportionately constant budget, the BIML has the difficult task of answering these growing needs and, besides continuing to support our Member States and Corresponding Members, promoting the OIML to those countries that are not yet members improving the mutual information flow and, shortly, launching new services related to mutual recognition or prepackage conformity marking.

The use of electronic communication means such as e-mail, electronic documents and our web site has steadily been developed over the past few years, and will most surely be one of the keys in ensuring the success of this evolution. In the future we will most likely see an increased use of online databases, interactive forums and tele-conferencing.

One of the most difficult, yet most vital challenges will be to match the level of excellence achieved by the BIML Immediate Past Director in all the Bureau's actions. The whole team of staff at the BIML is mobilized to accomplish these objectives in the most efficient way possible with the aim of offering all our Members the best possible service.

<div align="center">

# Répondre aux besoins

</div>

La globalisation des économies et l'ouverture des marchés appellent une activité accrue de l'OIML. Les liaisons avec l'OMC et avec les autres organisations internationales et régionales sont d'une importance croissante.

Nous devons rapidement développer et mettre à jour les Recommandations et les Documents nécessaires, et mettre en place des mécanismes de reconnaissance mutuelle. Les questions relatives aux pays en développement tiennent aussi une place croissante dans l'OIML.

Le rôle des organisations régionales de métrologie légale (RLMO) est un élément majeur. Les RLMO sont un complément et un relais de notre organisation et des mécanismes de coordination doivent être approfondis.

Enfin, l'évolution des technologies et le développement des technologies de l'information, transforment profondement la nature des instruments de mesure et concernent tous nos travaux.

Le BIML a la tâche difficile, avec des ressources humaines et financières constantes, de répondre à ces besoins croissants, et en outre d'assurer une présence soutenue auprès des États Membres et Membres Correspondants, de promouvoir l'OIML auprès de pays non encore membres, d'améliorer l'information mutuelle et de mettre bientôt en place de nouveaux services liés au système de reconnaissances mutuelles ou au marquage de conformité des préemballages.

L'utilisation des moyens électroniques de communication (courriers électroniques, documents sur support électronique, site internet) se développe depuis quelques années, et sera certainement une des clés dans cette évolution. L'avenir fera une place accrue aux bases de données en ligne, aux forums interactifs et aux téléconférences.

Maintenir le niveau de qualité que le Directeur sortant assurait sur l'ensemble des missions du Bureau sera une tâche difficile, mais indispensable. Toute l'équipe du BIML est mobilisée pour répondre à tous ces objectifs avec la meilleure efficacité possible et pour apporter aux membres de l'OIML le meilleur service.

UNCERTAINTY

<div align="center">

# Uncertainty of measurements made by calibrated equipment

</div>

JOSÉ BRENES ANDRÉ,

Escuela de Física, University of Costa Rica

In other words, rather than using the standard method known as Ordinary Least Square (OLS), and its result $ m_{xy}=r^{2}/m_{yx} $ (where r = the Pearson correlation coefficient), the Least Normal Squares (LNS) method should be used from the outset since it naturally leads to inversion, giving as a result $ m_{xy}=1/m_{yx}. $ (Caution: this is by no means to be taken as the special case r=1.) This approach allows the user to solve the inversion problem without having to resort to the standard techniques of calculating uncertainties.

The very important problem of finding the best fit line to interpret the readings of any calibrated equipment was addressed in the October 1998 issue of the OIML Bulletin by Dr. Subasinghe, who proposed a way to improve the calculation of uncertainties in such cases. The author of this paper would like to put forward a different approach which eliminates the obstacles encountered since the outset by using the least normal squares, a method which naturally allows the inversion of the independent and dependent variables, thus making it possible to calculate uncertainties using the known equations without having to make any simplifying assumptions. Although the equations derived here are known, the author has devised a simple way of his own to obtain them, which he believes makes the statistical properties associated with such a fit more evident. A practical application using the same GUM data as presented in the October 1998 Bulletin is also presented and discussed.

## Ordinary least square (OLS) fit

The standard technique of the ordinary least square fit can be found in any introductory text, but for the sake of being comprehensive and to allow the reader to compare methods, it is outlined here.

Let $ \left(x_{i},y_{i}\right) $ be a set of N ordered pairs, obtained experimentally. The values on the x-axis are supposed to have a negligible uncertainty. The best fit line will be characterized by that (m,b) which makes

$$
S (m, b) = \Sigma \left(y _ {i} - m x _ {i} - b\right) ^ {2}
$$

a minimum, which leads to:

## Introduction

$$
m _ {x y} = \frac {\sum \left(x _ {i} - X\right) \left(y _ {i} - Y\right)}{\sum \left(x _ {i} - X\right) ^ {2}} \quad b _ {x y} = Y - m _ {x y} X
$$

In metrology, a very important case of a linear fit appears in the equipment calibration process, by using a given standard. A plot of the readings made by the equipment versus that obtained using the standard should give a straight line fit if the instrument is working properly, as Dr. Subasinghe points out in his paper. [1]

Although the author shares Dr. Subasinghe's main view that in the case of a plot of the equipment reading versus the reference equipment reading what is important is to find the uncertainty associated with a predicted x-value corresponding to a given y-value, he believes that rather than proposing a new way to approximate such uncertainty (equation 6 of his paper) the solution lies in finding a way to obtain the slope and intercept of the fit in such a way that, since the start, they fulfill the requirement of inversion.

where $ y_{i} $ and $ x_{i} $ denote the readings on the equipment needing corrections and those of the reference equipment, respectively. X and Y are the centroid of such a set of data points.

The suffix xy denotes that the variable x is considered to have been measured with negligible error, whereas the y variable not. For the case when all the errors have been lumped in the x variable the labels are inverted, and the following equations result:

$$
m _ {y x} = \frac {\sum \left(x _ {i} - X\right) \left(y _ {i} - Y\right)}{\sum \left(y _ {i} - Y\right) ^ {2}}
$$

$$
b _ {y x} = Y - m _ {y x} X
$$

$$
m _ {x y} m _ {y x} = r ^ {2}
$$

## Least normal squares (LNS)

The different approach the author would like to present here is derived from a single tenet: the requirement that the dispersion $ \sum v_{i}^{2} $ (defined in the text below) be a minimum.

We start by shifting all the data values $ y_{i} $ and $ x_{i} $ by their respective centroid values, defining two new variables (u,v) such that $ u_{i}=x_{i}-X $ $ v_{i}=y_{i}-Y $ . It is straightforward to show that U=0, V=0. Regardless of how the slope and intercept are calculated the best fit line has to pass through the centroid.

If the data shows a visible tendency to lie along a line, most of the data points can be encompassed by an imaginary ellipse, which suggests that the coordinates (u,v) should be rotated around the point (X,Y) by an angle $ \alpha $ in a direction such that the variable u-axis will be practically parallel to the major semi-axis of the ellipse, which leads to:

$$
u ^ {\prime} = v \sin \alpha + u \cos \alpha v ^ {\prime} = v \cos \alpha - u \sin \alpha
$$

The value of $ \alpha $ to be used will be that which makes the ellipse minor semi-axis a minimum. In the limiting case where all the points lie exactly on a line, the minor semi-axis will be exactly zero.

It is only natural to equate the dispersion of the u points to the value of the major semi-axis. The fact that the minor semi-axis is perpendicular to this axis is another way of saying that we are considering the distance from each point to the fit line as the value of a line segment starting from the point and ending in the fit line, when such a segment is perpendicular to the fit line.

## Analysis in the （ $ U^{\prime},V^{\prime} $ ）plane

The requirement that $ \sum v^{\prime 2}=\sum(v\cos \alpha-u\sin \alpha)^{2}=\sum\cos^{2}\alpha $ $ (v-u\tan \alpha)^{2} $ be a minimum is the equivalent of making S(m,b) a minimum with respect to m. The intercept b is in this case equal to zero, as can be seen from the proposed v=u tan $ \alpha $ relation.

In Anderson's paper [2], the angle between the line and the u-axis is taken as a parameter, but for other reasons (namely that the angle parameter transforms linearly whereas the m certainly does not). In the discussion that followed this article, P. Sprent states: "... there is a third idea that is unusual: that of considering the angle of inclination of a line to one of the axes rather than the tangent of that angle. I am not clear whether there are many practical advantages in looking at the angle rather than the slope" ([2], p. 20). This is an opinion the author of the present paper does not share.

It is apparent that:

$$
\frac {\mathrm {d} u ^ {\prime}}{\mathrm {d} \alpha} = v ^ {\prime}, \quad \frac {\mathrm {d} v ^ {\prime}}{\mathrm {d} \alpha} = - u ^ {\prime},
$$

from which the requirement of the dispersion $ \sum v^{\prime 2} $ being a minimum transforms to:

$$
\frac {d}{d \alpha} \sum v _ {1} ^ {2} = - 2 \sum v _ {1} u _ {1} = 0
$$

In other words, creation of the $ \left(u^{\prime}, v^{\prime}\right) $ plane is equivalent to making both new variables independent of each other, i.e. have zero correlation.

In [2] P. Sprent minimized $ U=\Sigma(x\cos \phi+y\sin \phi-p)^{2} $ obtaining $ \Sigma[ ( y-Y)-\beta(x-X) ][ x+\beta y ]=0 $ . He drew attention to the fact that in Williams [3] two new variables $ u=[(y-Y)-\beta(x-X)]v=[x+\beta y] $ are defined leading to $ \Sigma uv=0 $ and so "the estimation of the slope $ \beta $ is equivalent to choosing $ \beta $ so that the sample correlation of (u,v) is zero" ([3] p.21).

Taking the derivative again, and forcing the dispersion of $ v^{\prime} $ to be a minimum one finds $ -(\Sigma v^{\prime 2}-\Sigma u^{\prime 2})>0 $ which is another way of saying a > b, as it should be with the major and minor semi-axis. If instead one minimizes the dispersion of $ u^{\prime} $ , one finds that the assignment of signs is reversed, obtaining b > a opposite to our convention.

## Analysis of (U,V) plane

Hence, for coherence we are forced to assign the major semi-axis to the dispersion of the u' and the minor semi-axis to the dispersion of v', from which:

$$
\begin{array}{l} a ^ {2} = \frac {\sum u _ {1} ^ {2}}{N} = \frac {\sum \left(u \cos \alpha + v \sin \alpha\right) ^ {2}}{N} = \frac {\sigma_ {y} ^ {2} + \sigma_ {x} ^ {2}}{2} - \frac {\Delta}{2} \\ b ^ {2} = \frac {\sum v _ {1} ^ {2}}{N} = \frac {\sum \left(v \cos \alpha - u \sin \alpha\right) ^ {2}}{N} = \frac {\sigma_ {y} ^ {2} + \sigma_ {x} ^ {2}}{2} + \frac {\Delta}{2} \\ \end{array}
$$

The expressions using $ \Delta $ are identical to equations (7) in Creasy [4].

We will denominate by $ \phi $ the value of $ \alpha $ , that minimizes b, or maximizes a, since both requirements are fulfilled simultaneously for the same angle, constituting further evidence of the coherence of this approach. This explains quite simply the result that the likelihood of the surface showing a saddle point rather than the absolute minimum as found out by Solari [6].

The above leads to:

$$
\tan 2 \varphi = \frac {2 \sum v u}{\sum \left(u ^ {2} - v ^ {2}\right)}
$$

One can use this last equation to calculate the value of the slope tan $ \phi $ by first finding $ \phi $ and taking its tangent afterwards. However care has to be taken not to forget that there are two different possible values of $ \phi $ (in the range $ - \pi<\phi<\pi $ ) for each value of tan 2 $ \phi $ . Such behavior is more clearly seen if the value of tan $ \phi $ is directly obtained.

Using the facts that tan $ 2 \alpha=2 \tan \alpha /(1-\tan^{2} \alpha) $ and that we constructed the best fit line to be roughly parallel to the ellipse major semi-axis, we are allowed to identify tan $ \alpha $ with the slope m, and hence find:

$$
m _ {x y} = \frac {B _ {x y}}{r} \pm \sqrt {\left(\frac {B _ {x y}}{r}\right) ^ {2} + 1}
$$

where we have set $ B_{xy}=\frac{1}{2}\left\{\left(\sigma_{y} / \sigma_{x}\right)-\left(\sigma_{x} / \sigma_{y}\right)\right\} $ . Notation reminds us that the first index for m refers to the independent variable, and the second to the dependent one.

Madansky [6] wrote: "One should note, though, that some of the papers referred to in Lindley [7] and Zucker [8] derive the least squares estimate of tan 20, where $ \beta=\tan \theta $ , when $ \lambda=1 $ , ..., but do not solve for $ \beta $ using the relation: $ \tan 2 \alpha=2 \tan \alpha /(1-\tan^{2} \alpha) $".

And he continues: "Pearson [9] was one who estimated tan 20 but he argued that the best-fitting straight line for the system of points coincides in direction with the major axis of the correlation ellipse. But the direction of the major axis of the correlation ellipse depends only on sgn $ (\Sigma xy). $ In none of the other papers do I find such an argument."

There are two possible values for $ m_{xy} $ depending on the sign used, which we will call $ m_{xy+} $ and $ m_{xy-} $ Multiplication of both values gives -1 as a result, showing that they refer to two mutually perpendicular lines. Our convention forces us to assign the + sign to that parallel to the major semi-axis, leaving the - sign to that parallel to the minor semi-axis. Madansky [6] presents a very concise analysis of the use of the two signs.

Should we perform this analysis setting $ \sum u^{2} $ to be a minimum, then:

$$
\sum u _ {1} ^ {2} = \sum \left(u \cos \alpha + v \sin \alpha\right) ^ {2} = \sum \left(u + v \tan \alpha\right) ^ {2} \cos^ {2} \alpha
$$

This implies that tan $ \alpha $ is now the negative of the inverse of the previous tan $ \alpha $ , which in turn corresponds to the second root.

We can also start from $ a^{2}>b^{2},\Sigma u^{\prime 2}>\Sigma v^{\prime 2} $ finding:

$$
\sum u v \frac {\cos^ {2} 2 \alpha}{\sin 2 \alpha} > - \sum u v \sin 2 \alpha
$$

Hence, if $ \sum u v>0 $ we have to choose $ \sin 2 \alpha>0 $ which is fulfilled for $ 0<\alpha<\frac{1}{2}\pi $ which is what we obtain if (x,y) are directly related. Similarly, if $ \sum u v<0 $ we have to choose $ \sin 2 \alpha<0 $ which is fulfilled for $ \frac{1}{2}\pi<\alpha<\pi $ which is what we obtain if (x,y) are inversely related. These results are coherent with the fact that with OLS method one finds $ \tan \alpha=\sum v u / \sum u^{2} $ making it evident that the sign of $ \sum v u $ determines whether the data is directly or else inversely related.

The expressions for a $ ^{2} $ and b $ ^{2} $ represent a circle off-centered by $ \frac{1}{2} \left( \sigma_{y}^{2}+\sigma_{x}^{2} \right) $ in each axis, with a radius equal to 2R as given by equation (4) of Creasy [4], who uses this result to examine the confidence limits for the slope. The reader is referred to the original paperfor details.

## Relation to OLS

Let us write:

$$
\tan 2 \alpha = \frac {2 \sum u v}{\sum \left(u ^ {2} - v ^ {2}\right)} = \frac {2 \left(\frac {\sum u v}{\sum u ^ {2}}\right)}{1 - \frac {\sum v ^ {2}}{\sum u ^ {2}}}
$$

Using tan $ 2 \alpha=2 \tan \alpha /(1-\tan^{2} \alpha) $ as a guide, one may be tempted to make the association $ \tan \alpha=\sum v u / \sum u^{2} $ the result obtained when using the OLS method. But then one also has to take:

$$
1 - \tan^ {2} \alpha = 1 - \frac {\sum v ^ {2}}{\sum u ^ {2}} \mathrm {w h i c h l e a d s t o} r ^ {2} = 1
$$

Such is the basis of Kendall's [10] equations (29.21) obtained by imposing certain conditions on the estimators. But from the above it can be seen that such an association can not be made, because it does not solve the quadratic equation. In fact equation (29.22) is basically $ r^{2}=1 $ which does not necessarily follow on from the first association.

Applying the approximation tan $ \beta $ $ \Box \beta $ when $ \beta $ is small one finds that tan 2 $ \phi $ $ \Box 2 $ $ (\Sigma \mathrm{v u} / \Sigma \mathrm{u}^{2}) $ which implies that if the slope is small, the value obtained from the OLS and that obtained from the LNS will be basically the same (as expected) because in the OLS method one uses the differences in the y values which will now be practically perpendicular to the would be best fit line, as required by the LNS.

## Calculation of the intercept

We obtained the value of the slope, but the intercept is still to be found. In the OLS case this is easily found from $ \sum \left( y_{i}-m x_{i}-b\right)=Y-m X-b=0 $ which proves the assertion that the best fit line passes through the centroid.

For the LNS case we can use the equation for the slope to also find the value of b. Let us suppose that a new measurement $ \left(x_{N+1},y_{N+1}\right) $ is made. The new average will equal the old one:

$$
X _ {n e w} = \frac {\sum x + x _ {N + 1}}{N + 1} = \frac {N X + x _ {N + 1}}{N + 1} = X
$$

if and only if $ x_{N+1}=X $ and similarly for variable y. In the (u,v) plane the new data point is (0,0), i.e. the centroid. Because of the form of the tan 2 $ \phi $ equation, its value does not change. Hence, the centroid has to lie on the best fit line, and $ Y=m X-b $ is also valid in the LNS approach.

## Inversion

Basic to our claim is that the results can naturally be inverted, i.e. if we start with $ Y=m_{xy} X+b_{xy} $ or else we start with $ X=m_{yx} Y+b_{yx} $ we will always have $ m_{xy} * m_{yx}=1 $ . Exchanging x and y in the definition of the slope, it can be directly proved that $ B_{xy}=-B_{yx} $ , and that:

$$
m _ {x y} m _ {y x} = \left[ \frac {B _ {x y}}{r} \pm \sqrt {\left(\frac {B _ {x y}}{r}\right) ^ {2} + 1} \right] \left[ \frac {B _ {y x}}{r} \pm \sqrt {\left(\frac {B _ {y x}}{r}\right) ^ {2} + 1} \right] = 1
$$

The sign in front of the square root sign has to be the same in both cases, because all we did was to exchange x and y. Care has to be exercised not to confuse $ m_{yx} $ with the second root obtained from tan 2 $ \phi $ .

This result can also be obtained if one realizes that for a y vs x plot the slope $ m_{xy} $ is tan $ \phi $ , whereas for an x vs y plot the slope $ m_{yx} $ will be tan $ (\pi /2-\phi)=\cot \phi $

## Comparison of both methods

At this point a question arises: why switch from OLS to the alternative method presented here?

Using the same data presented in [1] for Observed temperature vs Reference temperature (Graph 2b:

Calibration plot) (See Table 1), Dr. Subasinghe reports a linear relationship of:

$$
y = 0. 9 9 7 8 x + 0. 2 1 4 5
$$

whereas using the method described here it is found that:

$$
y = 1. 0 0 2 4 5 x + 0. 1 0 4
$$

Although in this case the difference in the values of the slope is small, application of this method to other sets of data shows a more noticeable contrast. Moreover, from the epistemological point of view a method that makes no difference between which of the two variables is the dependent one and gives a single value for the slope is more satisfactory that one that forces the experimenter to make such a decision from personal considerations.

## References

[1] Subasinghe, G.K.N.S. Expression of uncertainty in measurements made by calibrated equipment, OIML Bulletin No. 39 (1998) 18-23

[2] Anderson, T.W. (1976) Estimation of linear functional relationships: Approximate distributions and connections with simultaneous equations in Econometrics, J. R. Stats. Soc 38, 1-36.

[3] Williams, E. (1973) Tests of correlation in multivariate analysis. Bull. Int. Statist. Inst., Proceedings of the $ 39^{\mathrm{th}} $ Session, Book 4, 218-234

[4] Creasy, M.A. (1955) Confidence limits for the gradient in the linear functional relationship, J. Roy. Stats. Soc., 18, 65-69

[5] Solari, M. The maximum likelihood solution of the problem of estimating a linear functional relationship, J. R. Statist. Soc. B, 31 (1969), 372-375

[6] Madansky, A. The fitting of straight lines when both variables are subject to error, Am. Statis. Ass. J. 54 (1959), 173-205

[7] Lindley, D.V. Regression lines and the linear functional relationship, Jour. Royal stat. Soc, Supp, 9, (1947), 219-244

[8] Zucker, L.M., Evaluation of slope and intercept of straight lines, Human Biology, 19 (1947), 231-259

[9] Pearson, K. On lines and planes of closest fit to systems of points in space, Phil. Mag, 2 (1901), 559-572

[10] Kendall, M.G. and Stuart, A. (1977) The advanced theory of statistics, 2, $ 4^{\mathrm{th}} $ edition. London: Griffin

The author welcomes feedback to this article and may be contacted by e-mail: jbrenes@cariari.ucr.ac.cr

CALIBRATION

<div align="center">

# Calibration of weighing instruments and uncertainty of calibration

</div>

TEUVO LAMMI, The Finnish Association of Technology for Weighing, Helsinki, Finland

## Summary

In this paper the calibration of weighing instruments and the uncertainty associated with the calibration results are investigated. The main questions dealt with are:

- In order to judge the calibration results, assume that the user of an instrument has given maximum tolerable errors (MTE's) for the instrument with different loads. With their aid:

- the person performing the calibration can decide how accurately to read the indications;

- he/she can choose weights of sufficient accuracy for the calibration; and

- if the errors of the instrument observed in the calibration are within the MTE's, the probability that the "true" values of the errors are within the MTEs can be given.

- The relationship between the uncertainty of calibration and its components are investigated.

- Besides the uncertainty of calibration, the uncertainty of practical weighing is outlined.

## 1 Introduction

This paper deals with the calibration of weighing instruments and the uncertainty of calibration and an attempt is made to arrive at an uncertainty which can be associated with the results of practical weighing. This is the uncertainty of weighing.

The weighing instruments considered here are nonautomatic, single-interval instruments.

The test procedures used in the calibration and in the evaluation of the uncertainty are based on those given in OIML Recommendation R 76-1 Nonautomatic weighing instruments. Part 1: Metrological and technical

requirements - Tests, 1992. (The references here are to OIML R 76-1 but they could as well be to the European Standard: EN 45501, AC:1993).

The evaluation of the uncertainty is based on the Guide to the expression of uncertainty in measurement (GUM), BIPM, IEC, IFCC, ISO, IUPAC, IUPAP, OIML Corrected & reprinted edition, 1995.

In Section 2 the calibration and the measures to be taken in connection with the calibration are dealt with. In Section 3 the uncertainty, its nature, practical meaning and suitable values are considered. In Section 4 the formula of the uncertainty of calibration and its components are investigated. In Section 5 examples of the application of the formula are given. In Section 6 the uncertainty of weighing is outlined.

## 2 Calibration of weighing instruments

## 2.1 What does calibration signify?

According to the definition of calibration in the International Vocabulary of Basic and General Terms in Metrology (VIM), BIPM, IEC, IFCC, ISO, IUPAC, IUPAP, OIML, 1993, the calibration of a weighing instrument can be interpreted as being the determination of the errors in the indication of the instrument at different test loads (standard weights). The error is the difference between the indication and the value of the corresponding test load (the "true" value of the indication).

## 2.2 Weighing test

For the purpose of this paper a transcription of the "Weighing test" in OIML R 76-1, A.4.4.1 is presented.

## 2.2.1 Checks

Before the weighing test, check the leveling and ensure that electrically powered instruments have been switched on for a period of at least 0.5 h and have reached temperature stability. Preload the instrument to a "large" load and check the function of the instrument. Unload and allow the instrument to recover before the weighing test.

## 2.2.2 Test

Set the indication to zero at no-load. Apply test loads (standard weights, see 2.3.4) from zero up to Max of the

instrument (Max = the maximum weighing capacity) and similarly remove the test loads back to zero. At least five test loads are used. The indication is read at each load.

The first test load should be applied centrally to the load receptor and the subsequent loads should be uniformly distributed on the load receptor around its midpoint.

This is the calibration test (the comparison of the measured values with the "true" values). The results can be presented by a graph with the load on the abscissa axis and the error of the instrument (2.1) on the ordinate axis. This graph is the "weighing curve".

## 2.3 Measures to be taken in connection with calibration

## 2.3.1 Maximum tolerable errors (MTEs) and f

Suppose that the user of the instrument has selected an error f. With its aid he can define the "maximum tolerable errors", MTEs, of the instrument (compare f with e in OIML R 76-1, 3.5). For example, the MTEs can be:

- $ \pm 1 $ f for all the loads, or

- $ \pm 0. 5 $ f for certain "small" loads but $ \pm 1 $ f for larger loads, or

- $ \pm 0. 5 $ f for "small" loads, $ \pm 1 $ f for certain "medium" loads and $ \pm 1. 5 $ f for larger loads.

Instead of 0.5 f,1 f and 1.5 f the values 1 f,2 f and 3 f can be used analogously.

## 2.3.2 Digital rounding errors and f

## A) Indication with a scale interval d smaller than f

With the aid of f one can decide whether or not the digital rounding errors included in digital indications should be eliminated. Without any special measures, the rounding errors are deemed to be eliminated if

$$
f \geq n d \quad (n \geq 5)
$$

where d is the scale interval of the instrument (OIMLR 76-1, T.3.2.2).

## B) Changeover point

Otherwise, the so-called changeover point (obtained after adding successive weights of 0.1 d or 0.2 d) is used to determine the "accurate" indication such as is given in OIML R 76-1, A.4.4.3. (The zero indication is dealt with in this way, too (see also 4.5.2 B). The errors recorded in the calibration should be corrected for the error at zero obtained at the start of the weighing test).

## 2.3.3 Errors of net values

Let us deal with the case where a tare load is placed on the instrument and a tare device is used to set the indication to zero. Thereafter, weighings are performed with the net loads. In order to estimate the errors of the net values we use the weighing curve obtained in the calibration of the instrument. This is done as described below.

![](page=6,bbox=[397, 1865, 1599, 2334])

<div align="center">

Figure 1 The (>) branch of the weighing curve is obtained with increasing loads and the (<) branch with decreasing loads. When a tare load is on the instrument a subtractive tare device (reducing the weighing range for the net loads) is used to set the indication to zero "0".

</div>

Let "0" be the zero indication after operation of the tare device. Plot "0" on the weighing curve so that it corresponds to the tare load (see Figure 1). Draw new coordinates through this zero point "0". From the weighing curve the errors of the net values are obtained in the new coordinates.

## 2.3.4 Standard weights and notes on calibration

## Verified weights

## A) Selection of weights

For the weighing test the standard weights are selected as follows (OIML R 76-1, 3.7.1).

The sum of the absolute values of the maximum permissible errors (mpe's) of the weights ( $ \leq 50 $ kg) shall not be greater than 1/3 of the MTE of the instrument for the applied load.

Weights $ \geq $ 50 kg, such as 500 kg and 1000 kg, are selected so that Max/f of the instrument is less than or equal to the n marked on the weights.

## Calibrated weights

If the indications of the instrument are not corrected for the errors of the weights, the sum of the absolute values of the errors of the weights shall not be greater than 1/3 of the MTE of the instrument for the applied load.

If the indications of the instrument are corrected for the errors of the weights, the sum of the absolute values of the uncertainties of the weights shall not be greater than 1/3 of the MTE of the instrument for the applied load.

Preferably 1/5 should be used instead of 1/3 above (see 4.2.2, Note 1).

## B) Notes on calibration

The calibration should take place at the site where the instrument is used.

If the instrument is to be repaired, serviced or its span adjusted, then before these operations, the development of the properties of the instrument should be inspected by performing the weighing test and the test described in 4.5.1. The results should be documented. After the repair, etc. the instrument can be calibrated.

## 3 Uncertainty of calibration, its nature practical meaning and evaluation

## 3.1 "True" E and value of uncertainty

For a certain load let the error (2.1) of the instrument be E and the value of the uncertainty of calibration U. It shall be such that the interval E $ \pm $ U covers the "true" value of E with a "high" confidence. The "true" value of E is here called the "true" E.

One might think that the larger U is the more confidence could be gained. If U is enlarged deliberately, U can have a "large" confidence, say, " >1 ". However, from the point of view of the measurements the information included in U can even be very poor. On the other hand, if U is rigorously evaluated according to the GUM, U has a confidence <1. It is large enough, and the information is as good as possible. Let us say, U has a physical meaning.

## 3.2 Nature of uncertainty

The uncertainty of calibration of a weighing instrument consists of different components such as the properties of the instrument and the errors of the standard weights used in the calibration. The components are never completely known. So the uncertainty, which depends on the components, is not completely known either. This means that the value of the uncertainty is a realization of a random variable and hence its value cannot be predetermined.

## 3.3 Practical meaning of uncertainty

## 3.3.1 Relationship between E≤ MTE and "true" E≤ MTE

Let us restrict ourselves to the case where the absolute values of the errors E obtained in the calibration are within the MTE's

## E≤MTE

for all the loads. The question is: how well the condition "true” E $ \leq $ MTE can be estimated from E $ \leq $ MTE when U takes on different values?

## A) U $ \leq $ 1/3 x $ \Box $ MTE $ \Box $

If $ \Box E \leq2/3\times\Box M T E $ and U $ \leq1/3\times\Box M T E $ then inserting these values of $ \Box E $ and U in $ \mathrm{E}\pm\mathrm{U} $ (which includes

the “true” E) it is easy to see that $ \square $ “true” $ E \leq \square $ MTE $ \square $ is true.

In general, if $ \square $ E $ \leq \square $ MTE $ \square $ and $ U \leq 1/3 \times \square $ MTE $ \square $ the probability P that the condition $ \square $ “true” $ E| \leq \square $ MTE $ \square $ is true is approximated by the fraction $ \square $ MTE $ \square $ / $ (\square $ MTE $ \square $ +1/3 $ \times $ MTE $ \square $ ). Now $ \square $ MTE $ \square $ is half the length of the interval where the “true” E should be and $ \square $ MTE $ \square $ +1/3 $ \times $ MTE $ \square $ that where it is. If $ U < 1/3 \times \square $ MTE $ \square $ P is greater than the fraction and if $ U=1/3 \times \square $ MTE $ \square $ P equals the fraction. So

$ P \geq \square $ MTE $ \square $ / $ (\square $ MTE $ \square $ +1/3 $ \times $ MTE $ \square $ ) = $ \square $ MTE $ \square $ / (4/3 $ \times $ MTE $ \square $ ) = 75 %

B) $ U < \square $ MTE $ \square $

$ U = k \times \square $ MTE $ \square $ (k < 1). Such as in A) the probability P that the condition $ \square $ “true” $ E \leq \square $ MTE $ \square $ is true is

$ P = \square $ MTE $ \square $ / $ (\square $ MTE $ \square $ +k $ \times $ MTE $ \square $ ) = 1 / (1+k) > 50 % $ (k < 1)

Example: Let the observed E be $ E=+0.4 \times \square $ MTE $ \square $ If $ k=0.9 $ , then the “true” E is in the interval $ E \pm 0.9 \times \square $ MTE $ \square $ (its length is 1.8 $ \times $ MTE $ \square $ ). In order for the condition $ \square $ “true” $ E \leq \square $ MTE $ \square $ to be true, the “true” E should be in the interval from $ -0.5 \times \square $ MTE $ \square $ to $ \square $ MTE $ \square $ the length of which is 1.5 $ \times $ MTE $ \square $ $ (-0.5 \times \square $ MTE $ \square $ = 0.4 $ \times $ MTE $ \square $ $ -0.9 \times $ MTE $ \square $ ). Thus $ P=1.5 \times \square $ MTE $ \square $ / (1.8 $ \times $ MTE $ \square $ ) $ \approx $ 83 %.

C) $ U \geq \square $ MTE $ \square $

$ U = k \times \square $ MTE $ \square $ (k $ \geq 1 $ ). The probability P that the condition $ \square $ “true” $ E \leq \square $ MTE $ \square $ is true is

$ P = \square $ MTE $ \square $ / $ (\square $ MTE $ \square $ +k $ \times $ MTE $ \square $ ) = 1 / (1+k) \leq 50 % $ (k $ \geq 1 $)

## 3.3.2 "Suitable" values of U

Here values of U < MTE are regarded as suitable, i.e., a probability P > 50 % that the condition "true" E $ \leq $ MTE is true is preferred. Values of U $ \leq $ 1/3 x MTE are ideal but may sometimes be difficult to achieve (see 4.2.2, Note 1).

If U $ \geq $ MTE there is a need to take measures to reduce U. It is possible if the instrument is giving service and if errors such as the repeatability and the eccentric errors (4.2 and 4.5.1) of the instrument can be made as small as possible. An alternative is if the values of the MTEs can be increased.

## 3.4 Methods of evaluation of uncertainty

## 3.4.1 Method in principle

The presentation of this method serves as an introduction to the evaluation of the uncertainty.

Imagine that the calibration (the weighing test) is repeated at least five times, each time applying the standard weights to the load receptor so as to produce centric and several kinds of eccentric loading. To simplify the presentation the ambient temperature is supposed to be unchanged during the tests. For each load the standard deviation s and the variance $ s^{2} $ of the errors obtained in the successive tests are calculated. For each different load the variance of the errors of the weights $ u^{2} $ is combined with the corresponding value of $ s^{2} $ respectively （ $ u^{2} $ is calculated as described in 4.4 but now for each load separately). The uncertainty is $ U=2(s^{2}+u^{2})^{1 / 2}. $

## 3.4.2 Practical method

In this method, which is described in Section 4 below the calibration (the weighing test) is performed only once and the different uncertainty components are investigated. With their aid the uncertainty, which is the "tool" for judging the calibration results, is evaluated.

In order to investigate the uncertainty components different tests are performed, e.g., the repeatability test where several weighings are carried out with the same load, and the eccentricity test where weighings are made with the same load in different positions on the load receptor. The results of these tests are the differences between the results of the weighings. They do not show how they relate to some "true" values. Thus the results are test results and not calibration results.

## 4 Relationship between uncertainty of calibration and its components

Here the relationship is given in formula (A) for U and (B) for $ U_{1}. $

The terms in U are related to:

1) the repeatability of the instrument,

2) the rounding errors involved in digital indication if these are not eliminated (2.3.2),

3) the errors in the standard weights used in the weighing test,

4) the errors brought about by possible eccentric positioning of the weights in the weighing test,

5) variations in the zero point, and

6) the effect of temperature variations during the weighing test.

The terms in $ U_{1} $ are related to those given above and to 7a) variations in the indication due to influences such as vibration and disturbances during the weighing test and 7b) irregularities in the weighing curve.

The uncertainty components are 1) to 7b). The components 1), 2) and 3) are the main ones which always have an influence on U except 2) where rounding errors are eliminated. Components 4), 5) and 6) have a real effect on U only if they are powerful enough. Their combined effect is here denoted by the symbol z. The components 7a) and 7b) are denoted by the common symbol w.

The relationship between U (the uncertainty, w = 0) and its components is:

$$
U = 2 r \left[ \left(k _ {n} R\right) ^ {2} + 1 / r ^ {2} (0. 3 d) ^ {2} + u ^ {2} + z ^ {2} \right] ^ {1 / 2}
$$

The relationship between $ U_{1} $ (the uncertainty, $ w\neq0 $ ) and its components is:

$$
\begin{array}{l} U _ {1} = 2 r \left[ \left(k _ {n} R\right) ^ {2} + 1 / r ^ {2} (0. 3 d) ^ {2} + u ^ {2} + z ^ {2} + \right. \\ 1 / r ^ {2} w ^ {2} ] ^ {1 / 2} = \left[ U ^ {2} + 4 w ^ {2} \right] ^ {1 / 2} \\ \end{array}
$$

2 r, $ k_{n} $ , R, d, u, z and w are explained below in points 4.1 to 4.6 (see also Section 5). U is dealt with in 4.1 to 4.6.1 and $ U_{1} $ in Table 1 (4.1) and in more detail in 4.6.2.

## 4.1 Coefficient 2 r and Table 1

2 is the coverage factor (GUM). With its aid the values of U meet the condition of the "high confidence" given at the beginning of 3.1.

r is for nonautomatic single-interval instruments. It assumes the values r = 1, 0.7, 0.4 and 0.3 which are determined on the basis of consideration. How r is used is presented below and in Table 1.

## Meaning of r

Imagine that the weighing range 0 - Max is divided into parts 1 to 3 in which the MTE's (2.3.1) assume different values, e.g., $ \pm0.5 $ f, $ \pm1 $ f and $ \pm1.5 $ f. Each part is associated with a value of r. If there is only one part (MTE $ = \pm1 $ f for all loads), then r = 1. If there are two or three parts, r = 1 for the part with the largest loads and r < 1 for the others. The smaller the loads are in the parts the smaller the values r assumes.

Each part associated with a value of r is also associated with a value of U. For the part with r = 1 let the value of U be $ U_{r=1} $ . Therefore the terms in U are determined with some "large" loads and the values of the terms and r = 1 are used to evaluate $ U_{r=1} $ . For smaller loads the values of U are evaluated with the same values of the terms as above but with a value for r < 1 obtained from Table 1 (see next page).

4. 2 Term $ k_{n} $ R brought about by repeatability R

4. 2.1 R and standard deviation $ k_{n}R $

The repeatability R is the difference between the largest and the smallest results of the weighings in the repeatability test (4.2.2). The standard deviation of all the results is $ k_{n} $ R where n (n $ \geq3 $ ) is the number of the weighings and $ k_{n} $ the coefficient which assumes the following values:

$$
\begin{array}{l} k _ {3} = 0. 5 9 1, k _ {4} = 0. 4 8 6, k _ {5} = 0. 4 3 0, k _ {6} = 0. 3 9 5, k _ {7} = 0. 3 7 0, \\ k _ {8} = 0. 3 5 0, k _ {9} = 0. 3 3 7 \mathrm {a n d} k _ {1 0} = 0. 3 2 5. \\ \end{array}
$$

## Motivation

The values of $ k_{n} $ are adopted from tables giving parameters of the distribution of the range of samples taken from a normal population (range = the difference between the largest and the smallest observation). The repeatability R is deemed to originate from that population, too. Such a table can be found in: Hald. A , "Statistical Tables and Formulas" Willey & Sons, Inc., New York, London, 1952, Table VIII.

## 4.2.2 Repeatability test

The "large" test load $ L_{R} $ is $ L_{R}\geq 0.5 $ x Max. At least five weighings should be performed with $ L_{R} $ in an identical manner. (Suppose that $ k_{n} $ indicates the quality of information obtained from the repeatability test. It is quite stable if n $ \geq 5 $ (see the values of $ k_{n} $)). According to OIML R 76-1, A.4.10, the instrument is set to zero before each weighing or the automatic zero-tracking device shall be in operation (in this case the procedure in 2.3.2 B is not applied to digital zero indications).

The rounding errors included in digital indication of the weighings with $ L_{R} $ should be eliminated. If this is not done and if the result R = 0 is obtained, it should be replaced by R = d (the worst case). However, this value of R can result in values of U, which are too large (see 3.1 to 3.3).

## Note 1

A) Suppose that the MTE's take on the values $ \pm0.5 $ f and $ \pm1 $ f. If 1) R meets the condition R $ \leq $ 0.35 f and 2) the weights for the weighing test are chosen so that 1/5 is used instead of 1/3 (2.3.4 A) and 3) the other uncertainty components are insignificant, then U $ \leq $ 1/3 x $ \Box $ MTE.

B) If the MTE's take on the values $ \pm 0.5 $ f, $ \pm1 $ f and $ \pm1.5 $ f and if R<0.55 f and 2) and 3) above are met, then U $ \leq $ 1/3 x $ \Box $ MTE However, if the weights are chosen so that 1/3 is used, R should be R<0.4 f and 3) above should be met in order that U $ \leq $ 1/3 x $ \Box $ MTE

<table border="1"><tr><td colspan="2">1) Weighing range divided into three parts</td><td>MTE:±0.5f,±1fand±1.5for±1f,±2fand±3f</td></tr><tr><td>Part with MTE=±0.5f or±1f</td><td>r=0.3</td><td rowspan="3">U=2r[(knR)2+1/r2(0.3d)2+u2+z2]1/2</td></tr><tr><td>Part with MTE=±1f or±2f</td><td>r=0.7</td></tr><tr><td>Part with MTE=±1.5f or±3f</td><td>r=1</td></tr><tr><td colspan="2">2) Weighing range divided into two parts</td><td>MTE:±0.5fand±1for±1fand±2for</td></tr><tr><td>Part with MTE=±0.5f or±1f</td><td>r=0.4</td><td rowspan="2">U=2r[(knR)2+1/r2(0.3d)2+u2+z2]1/2</td></tr><tr><td>Part with MTE=±1f or±2f</td><td>r=1</td></tr><tr><td colspan="2">3) One part</td><td>MTE:±1ffor all loads in the weighing range</td></tr><tr><td>MTE=±1f</td><td>r=1</td><td>U=2r[(knR)2+1/r2(0.3d)2+u2+z2]1/2</td></tr></table>

<div align="center">

Table 1 Evaluation of U or $ U_{1} $ for different loads. Single-interval instruments

</div>

Suppose that w = 0. For some "large" loads (4.2 to 4.5) determine a value of $ k_{n} R $ , u and z (d is the scale interval) in U. These values and r obtained according to the MTE's (Table) are inserted in Formula (A) for U. In this way the values of U (w = 0) can be evaluated for loads at which the MTE's takes on different values.

Suppose that w $ \neq $ 0 for some adjacent loads. For these loads the value of U (w = 0) is corrected for w $ \neq $ 0. The corrected value of U equals the value of $ U_{1}=[U^{2}+4 w^{2}]^{1/2} $ (Formula B). More information on w and $ U_{1} $ is given in 4.6.2, Figure 2 and Table 2. If w is $ w \neq 0 $ for almost all the loads in the weighing range either U or $ U_{1} $ is evaluated as described in 4.6.1.

<div align="center">

Note 2

</div>

With the aid of R, variations in some other quantities which have influence on U can be taken into account. Examples are the variations in the hysteresis and that given in 4.6.1. In order to explain the variations in the hysteresis imagine that the weighing test is repeated under the same conditions. It is likely that the location of the weighing curve of each weighing test is slightly different. For a certain load the changes of the locations will indicate the variations in the hysteresis. It should be emphasized that the hysteresis as such cannot be regarded as an uncertainty component but the variations in it can. However, they can be included in R for all the loads so that with the aid of R the variations in the hysteresis can be taken into account without any other measures.

## 4.3 Term 0.3 d brought about by digital rounding errors

d is the scale interval. If the rounding errors in the digital indications noted in the weighing test are eliminated (2.3.2), set $ ( 0.3 \mathrm{~d})^{2}=0 $ . Otherwise 0.3 d, which is the standard deviation of the digital rounding errors, is used to calculate U.

## How to obtain 0.3 d

The digital rounding errors are in the interval （-0.5 d, +0.5 d) or more exactly in the intervals kd $ \pm $ 0.5 d k=0,1,2,...,n; n=Max/d, i.e., in the n+1 intervals （-0.5 d, +0.5 d) around the points kd, k=0,1,2,...,n. The distribution of the rounding errors is uniform (they have the uniform, rectangular distribution). Their standard deviation is 0.5 d/$ \sqrt{3} $ $ \approx $ 0.3 d.

In the formula for U the coefficient of $ ( 0.3\mathrm{d})^{2} $ is $ 1 / r^{2} $ because the effect of the rounding errors is to be kept unchanged when operating with r.

## 4.4 Term u brought about by weights

u is the standard deviation of the errors of the weights for a "large" load $ L_{R W} $ . It corresponds to the load $ L_{R} $ used in the repeatability test. The weights in $ L_{R W} $ can be regarded as a representative sample drawn from the weights used in the weighing test. u assumes different values as given below in points 4.4.1 to 4.4.3.

## 4.4.1 Verified weights

u = 0.4 x (the sum W of the absolute values of the mpe's (2.3.4 A) of the weights in $ L_{Rw} $

## Motivation

All the verified weights are here supposed to be adjusted so that their errors are within the limits $ \pm2/3 $ xmpe. So the actual error of the weights in $ L_{R w} $ can be estimated as being in the interval $ [-2/3 $ W, $ +2/3 $ W]. The error is uniformly distributed in $ [-2/3 $ W, $ +2/3 $ W]. (If there are several weights in $ L_{R w} $ , they may have both positive and negative errors and their sum, the actual error of the weights, can be quite "small". In this case the interval $ [-2/3 $ W, $ +2/3 $ W] could be an upper estimate of the intervals where the actual error can be found). The standard deviation of the actual error of the weights is $ u=2/3 $ W $ /\sqrt{3}\approx0.4 $ W.

## 4.4.2 Calibrated weights

A) Two or more weights are used in $ L_{Rw} $ and the indications of the instrument are not corrected for the errors of the weights

u = 0.6 x (the sum W of the absolute values of the errors of the weights in $ L_{R_{w}} $ )

## Motivation

The actual error of the weights in $ L_{R_{W}} $ is estimated to be in the interval $ [-W,+W] $ . The distribution of the error is of the discrete type. In this

case where two or more weights are used in $ L_{Rw} $ the distribution is approximated by the (continuous) uniform distribution. Thus the standard deviation of the error of the weights is $ u=W / \sqrt{3}\approx 0.6 $ W.

B) Only one weight is used in $ L_{Rw} $ and the indications of the instrument are not corrected for the errors of the weights

u = (the absolute value w of the error of the weight in $ L_{Rw} $ )

## Motivation

The error of the weight is either -w or +w. Their standard deviation u is (their mean is 0 and frequency of appearance 0.5) u = [0.5 (+w-0) $ ^{2} $ + 0.5 $ (-w-0)^{2} $] $ ^{1/2} $ = w.

C) The indications of the instrument are corrected for the errors of the weights

u = 0.5 x (the sum of the absolute values of the uncertainties of the weights in $ L_{Rw} $ )

## Motivation

The uncertainty of a weight multiplied by 0.5 is a standard deviation. Let us call it the "standard deviation of the weight". The sum of the absolute values of the uncertainties of several weights multiplied by 0.5 is an upper limit of the joint standard deviation of the corresponding weights.

## 4.4.3 Effect of air density on weights

If the calibration results of the instruments with Max/f > 50000 (frequently d $ \leq1 $ mg) are obtained at different ambient air densities $ \rho $ （ $ \mathrm{kg / m^{3}} $ ）which differ from the reference density 1.2 $ \mathrm{kg / m^{3}} $ , the results should be corrected for the effect of the air density on the weights.

After the correction the calibration results are equivalent to those which would have been obtained if the air density were 1.2 kg/m $ ^{3} $ . The formula for the effect is given in "Motivation" below. Here the corresponding effect on the load receptor and on the load measuring device is not considered.

The uncertainty component due to the correction is $ ( \mathrm{m} / 8 0 0 0 )^{2} \mathrm{s}_{\rho}^{2} $ . It is added to $ u^{2} $ . So in the formula for U, $ u^{2} $ is replaced by

$$
u ^ {2} + \left(m / 8 0 0 0\right) ^ {2} s _ {\rho} ^ {2}
$$

where u is that given in 4.4.1 or 4.4.2 and m/8000 $ s_{\rho} $ is the standard deviation of the correction of the effect of the air density on the weights, m (kg) is the mass of the weights in $ L_{RW} $ and $ s_{\rho} $ $ (kg/m^{3}) $ the standard deviation due to the variations of the air density $ \rho $ during the weighing test. 8000 $ kg/m^{3} $ is the standard reference density of the weights.

To obtain $ \rho $ the air pressure, the ambient temperature and the relative humidity have to be measured. If the error of the air pressure measured is $ \pm 1 0 $ mbar or $ \pm 5 0 $ mbar, the value of $ s_{\rho} $ is approximately 0.01 $ \mathrm{kg/m^{3}} $ or 0.04 $ \mathrm{kg/m^{3}} $ respectively. At sites where instruments with Max/f > 50 000 are usually used, the variations of the temperature and the relative humidity can influence the third or successive decimal places in the numerical value of $ s_{\rho}. $

## Motivation

According to Archimedes' Principle the effect of the air density on the weights is obtained from the formula: $ (1.2-\rho) \mathrm{m} / 8000 \mathrm{(kg)} $ . From it $ \mathrm{m} / 8000 \mathrm{s}_{\rho} $ is derived.

## 4.5 Term z brought about by three kinds of errors

The term z includes the following errors: $ \Delta_{1},\Delta_{2} $ and $ \gamma L_{R} $ $ \Delta t $ $ \Delta_{1} $ is brought about by eccentric loadings, $ \Delta_{2} $ by the variations in the zero point and $ \gamma L_{R}\Delta t $ by the temperature variations $ \Delta t $ during the weighing test

$$
z ^ {2} = \left(0. 4 \Delta_ {1}\right) ^ {2} + 1 / r ^ {2} \left(0. 2 \Delta_ {2}\right) ^ {2} + \left(0. 2 \gamma L _ {R} \Delta t\right) ^ {2}
$$

## 4.5.1 Largest eccentric error $ \Delta_{1} $

## A) Eccentricity test, $ \varDelta_{1} $ and standard deviation 0.4 $ \varDelta_{1} $

In order to estimate the effect of the weights applied more or less to eccentric positions on the load receptor during the weighing test, the results of the eccentricity test are used here. In this test the same "large" test load (see B below) is successively applied to the eccentric positions (given in OIML R 76-1, A.4.7) and to the middle position of the load receptor. The differences between any indication at the eccentric positions and that at the middle position are determined. The absolute value of the largest difference is $ \Delta_{1} $

If $ \Delta_{1} $ is smaller than $ \Box MTE $ $ \Box(\Delta_{1}<\Box MTE) $ of the instrument for the load used in the eccentricity test, set $ (0.4\Delta_{1})^{2}=0 $ . Otherwise, $ \Delta_{1} $ is used to calculate $ z^{2}. $ 0.4 $ \Delta_{1} $ is the standard deviation of the eccentric effect of the weights during the weighing test (see C and D below).

## B) Test load and corrections

For instruments having not more than four (n $ \leq $ 4) points of support (load cells) the test load is 1/3 x Max. If n > 4, the test load is 1/(n-1) x Max (OIML R 76-1, A.4.7).

All the indications observed in the eccentricity test should be corrected for the error at zero. This should be determined every time just before the test load is applied to the different positions (WELMEC 2, Directive 90/384/EEC: Common Application, 4.5). This is necessary for instruments with Max / f > 10 000. If the accuracy of the zero-setting is $ \leq 0. 2 5 $ f, the indication of instruments with Max / f $ \leq 1 0 0 00 $ can be set to zero before the test load is applied. In addition, the rounding errors included in digital indications should be eliminated.

## C) How to obtain 0.4 $ \varDelta_{1} $

In order to obtain 0.4 $ \Delta_{1} $ imagine n+1 weighings. The first n weighings are performed with the load $ L_{R} $ (4.2.2) at the middle position and the last weighing with the same load but applied to an eccentric position on the load receptor. Except for the position of the load for the last weighing, the weighings are performed as in the repeatability test. The joint variance of the results of the weighings is

$$
1 / n \square (n - 1) s ^ {2} + [ n / (n + 1) ] \left(x ^ {\prime} - m\right) ^ {2} \square
$$

where m is the arithmetic mean of the results of the first n weighings, s $ \approx $ k $ _{n} $ R (4.2.1) their standard deviation and x' is the result of the last weighing. The components of the joint variance are:

$$
\begin{array}{l} 1) \quad [ (n - 1) / n ] s ^ {2} \approx [ (n - 1) / n ] \left(k _ {n} R\right) ^ {2} \\ \mathrm {d u e t o t h e r e p e a t a b i l i t y a n d} \\ \end{array}
$$

$$
\begin{array}{l} 2) \quad [ 1 / (n + 1) ] \left(x ^ {\prime} - m\right) ^ {2} \\ \mathrm {d u e t o t h e e c e c n t r i c l o a d i n g}. \\ \end{array}
$$

During the weighing test the weights are applied to the load receptor as in 2.2.2. The magnitude of the effect of the error brought about by the eccentric positions of the weights can be described by the distance from the center of gravity of the weights to the midpoint of the load receptor. The shorter the distance is the smaller the eccentric effect for a given load. Usually the distance is quite short.

If the load $ L_{R} $ $ \left( \geq0.5 \times\operatorname* {Max} \right) $ in the last weighing above is placed halfway between the midpoint of the load receptor and the position where $ \Delta_{1} $ is obtained in the eccentricity test, $ |x^{\prime}-m| $ (component 2) above) can approximately take on the value $ \Delta_{1} $ (note that in the eccentricity test $ \Delta_{1} $ is obtained with a load which is "much" smaller than $ L_{R} $ ). If $ |x^{\prime}-m| \approx\Delta_{1} $ and n=5, then according to 2) $ [1 / (n+1)] $ $ (x^{\prime}-m)^{2} \approx[1 / (n+1)] \Delta_{1}^{2} \approx(0.4\Delta_{1})^{2} $ . If the load $ L_{R} $ were placed anywhere else on the halfway point between the midpoint of the load receptor and the positions used in the eccentricity test, $ |x^{\prime}-m| $ could take on a value smaller than $ \Delta_{1} $ or it could even be zero.

## D) Effect of $ ( 0. 4 \varDelta_{1} )^{2} $

If the result $ \Delta_{1} $ of the eccentricity test assumes a "large" value $ (\geq\Box MTE\Box) $ for the applied load, then $ (0.4\Delta_{1})^{2} $ could have a significant effect on U, i.e., the results of the weighing test are "highly" dependent on the positions of the weights on the load receptor. On the other hand, if $ \Delta_{1} $ assumes a "small" value $ (<\Box MTE\Box) $ , the results of the weighing test are almost independent of the positions of the weights and thus, one could say that the effect of $ (0.4\Delta_{1})^{2} $ on U is negligible.

## 4.5.2 Difference $ \Delta_{2} $ between zero points

## A) $ \varDelta_{2} $ and standard deviation 0.2 $ \varDelta_{2} $

$ \Delta_{2} $ is the absolute value of the difference between the zero indications at the start and at the end of the weighing test. If $ \Delta_{2} $ is smaller than $ \Box $ MTE $ \Box $ $ (\Delta_{2}<\Box $ MTE $ \Box $ ) for the zero point, set $ (0.2\Delta_{2})^{2}=0 $ . Otherwise $ \Delta_{2} $ is used to calculate $ z^{2} $ . The standard deviation of the variations in the zero point during the weighing test is approximated here with the aid of $ 0.2\Delta_{2} $ .

## Motivation

Assume that $ \Delta_{2} $ consists of the hysteresis and the variations in the zero point. The width of the range of the "pure" variations (without the hysteresis and momentary variations in the zero point ) is guessed to be 0.7 $ \Delta_{2} $ Assuming that the variations in the zero point are independent and uniformly distributed over $ 0. 7 \Delta_{2} $ , the standard deviation of the variations is roughly $ 0. 5 \times0. 7 \Delta_{2} / \sqrt{3}\approx0. 2 \Delta_{2}. $

The coefficient $ 1/ r^{2} $ of $ ( 0. 2 \, \Delta_{2} )^{2} $ in $ z^{2} $ is to keep $ ( 0. 2 \, \Delta_{2} )^{2} $ unchanged when operating with r.

## B) Determination of $ \varDelta_{2} $ when zero-tracking is in operation

If the zero-tracking device is in operation, then with a "small" load which is out of the automatic range of the zero-tracking the indication is noted, and its error is defined to be the error at zero (OIML R 76-1, A.4.2.3.2). This is used to determine $ \Delta_{2} $ in connection with the weighing test.

## 4.5.3 Temperature effect and error $ \gamma L_{R}\Delta t $

## A) $ \gamma L_{R}\Delta t $ and standard deviation 0.2 $ \gamma L_{R}\Delta t $

In $ \gamma $ $ L_{R} $ $ \Delta t $ the symbol $ \Delta t $ denotes the difference between the extreme temperatures during the weighing test. $ L_{R} $ is

the load for the repeatability test (4.2.2) and $ \gamma $ a coefficient so that $ \gamma $ $ L_{R} $ $ \Delta t $ is the error of the instrument due to $ \Delta t $ for the "large" load $ L_{R} $

If $ \Delta t $ meets the conditions for steady ambient temperature $ ^{*} $ , set $ (0.2\mathrm{y}L_{R}\Delta t)^{2}=0 $ . Otherwise, $ 0.2\mathrm{y}L_{R}\Delta t $ is used to calculate $ z^{2} $ taking into account the restrictions in B) below. $ 0.2\mathrm{y}L_{R}\Delta t $ is the standard deviation of the error of the instrument for the load $ L_{R} $ caused by $ \Delta t $ .

How to obtain 0.2 $ \gamma\mathrm{L}_{R}\Delta t $

0. 2 y $ L_{R}\Delta t $ is derived by regarding y $ \Delta t $ as a sum of independent "impulses" y $ \Delta t=\sum y\Delta t_{k} $ (k=1, 2, ..., n). Because n can be regarded as a large number, suppose that the conditions of the Central Limit Theorem (see textbooks of statistics) are met for y $ \Delta t $ and thus it is approximately normally distributed. Then the standard deviation of y $ \Delta t $ is 1/6 x y $ \Delta t\approx 0.2 $ y $ \Delta t $ (the "observed" sum of the impulses is from zero to y $ \Delta t $ ). 0.2 y $ L_{R}\Delta t $ is obtained by multiplying 0.2 y $ \Delta t $ by $ L_{R} $ .

## B) $ \Delta t $ exceeds limits for steady ambient temperature

If $ \Delta t $ exceeds the limits for the steady ambient temperature $ ^{*} $ and if the test has lasted, say, for more than 0.5 h, $ 0.2\mathrm{y}L_{R}\Delta t $ is deemed to have a significant effect on $ z^{2} $ and thus on U. (A weighing instrument using electric power is a heat dissipating device with a housing. The effect of the changes of the ambient temperature on the instrument cannot be regarded as significant until after a sufficient delay).

## 4.6 Term w due to variations in indication and irregularities in weighing curve

The irregularities in the weighing curve can be due to automatic corrections of properties of the instrument. Due to the irregularities the weighing curve may have a zigzag form and the points of the curve (the errors of the instrument) can be difficult to determine accurately enough. Thus, the irregularities could be a source of the uncertainty.

## 4.6.1 Variations in indication and irregularities in weighing curve for several loads

The variations can be brought about by influences such as vibration, draughts, strongly oscillating ambient temperature and electrical disturbances. During the variations an unambiguous reading of the indication may not be possible and thus the variations can have an influence on the uncertainty.

Suppose that due to the variations/irregularities, the repeatability R of the instrument is considerably enlarged. In this case the effect of the variations/ irregularities on the uncertainty U can be obtained with the aid of R without any other measures (see 4.2.2, Note 2). In this case w is deemed to be w = 0 and the values of U (w = 0) (Formula A) are determined. However, if the effect of the variations/irregularities is not included in R, w $ \neq $ 0 and the values of $ U_{1} $ (Formula B) have to be determined for all the loads. The calculation of w is explained in 4.6.2

## 4.6.2 Variations in indication and irregularities in weighing curve for certain loads only

## A) Range $ \varDelta_{3} $ and standard deviation w=0.3 $ \varDelta_{3} $

If the variations in the indication or the irregularities in the weighing curve are noted for some adjacent loads, one range $ \Delta_{3} $ of the variations or of the irregularities is estimated for these loads. For example, if the variations are within $ \pm 2 \mathrm{d} $ , then $ \Delta_{3}=4 \mathrm{d} $ , or if the difference between the limits of the "oscillations" in the weighing curve is $ \Delta_{3} $ , then $ \Delta_{3} $ is the range of the irregularities. In the case mentioned at the end of 4.6.1, one value of $ \Delta_{3} $ should be estimated for the variations/irregularities for all the loads.

w = 0.3 $ \Delta_{3} $ is the standard deviation of the variations/ irregularities. If $ \Delta_{3} < 1 / 3 \times $ MTE, set w = 0. Otherwise, if $ \Delta_{3} \geq 1 / 3 \times $ MTE, the uncertainty U (w = 0) should be corrected for w $ \neq 0 $ for the loads at which w exists. This results in the uncertainty $ U_{1} $ (Formula B). The evaluation of $ U_{1} $ is elucidated in more detail in Figure 2 and Table 2.

## Motivation

Suppose that the variations or the irregularities are uniformly distributed over $ \Delta_{3} $ . Thus, their standard deviation is $ w=0. 5 \times\Delta_{3} / \sqrt{3} $ $ \approx0. 3\ \Delta_{3}. $

In the formula of $ U_{1} $ (Formula B) there is the coefficient $ 1 / r^{2} $ or $ w^{2} $ . This is because w shall be kept unchanged when operating with

## B) Nature of $ \mathrm{U}_{1} $

Frequently, the value of $ U_{1} $ is quite large due to w. For the loads at which w exists it is not possible to perform the calibration accurately enough. To some extent the large values of $ U_{1} $ indicate inadequate protection of the instrument against the influences and factors causing variations and irregularities respectively. $ U_{1} $ is not suitable for the investigations presented in 3.3.

The user of the instrument should pay attention to the existence of the variations or irregularities during practical weighings. They have to be taken into account in the uncertainty of weighing. This is briefly dealt with in Section 6.

## 5 Use of U and examples

## 5.1 Use of U

The same value of U is associated with the two calibration results obtained for a certain load L. One is obtained when the load L is reached by the increasing and the other by the decreasing loads. This is also adapted for use of $ U_{1} $ , if applicable (see Table 2). In order to judge the calibration results, U is used such as is explained in Section 3.

![](page=14,bbox=[251, 1850, 1820, 2288])

<div align="center">

Figure 2 The weighing range 0 - Max is divided into the parts A to B, B to C and C to D. For them the values of the MTEs 0.5 f, 1 f and 1.5 f and the uncertainties U"", U" and U' (w = 0) are given respectively. However, w $ \neq $ 0 is $ w_{1} $ for loads from E to F and $ w_{2} $ from G to H. For these loads the values of the uncertainties U" and U' should be corrected for $ w_{1} $ and $ w_{2} $ respectively, i.e., the values of $ U_{1} $ (Formula B) are determined. For loads from E to C, $ U_{1}=[U^{\prime \prime}{}^{2}+4 w_{1}{}^{2}]^{1/2} $ and from C to F, $ U_{1}=[U^{\prime}{}^{2}+4 w_{1}{}^{2}]^{1/2}. $ For loads from G to H, $ U_{1}=[U^{\prime}{}^{2}+4 w_{2}{}^{2}]^{1/2}. $

</div>

<table border="1"><tr><td>Loads:</td><td>A to B</td><td>B to E</td><td>E to C</td><td>C to F</td><td>F to G</td><td>G to H</td><td>H to D</td></tr><tr><td>Uncertainty:</td><td>U&#x27;&#x27;</td><td>U&#x27;&#x27;</td><td>[U&#x27;&#x27;2+4w12]1/2</td><td>[U&#x27;2+4w12]1/2</td><td>U&#x27;</td><td>[U&#x27;2+4w22]1/2*</td><td>U&#x27;</td></tr></table>

Table 2 Summary of values of uncertainties in Figure 2

Assume that $ w_{1} $ exists both for increasing (E to F) and for decreasing loads (F to E), but for loads from G to H $ w_{2} $ exists for decreasing loads (H to G) only.

$ \ast $ The uncertainty $ U_{1}=[U^{\prime 2}+4 w_{2}^{2}]^{1/2} $ has to be associated with the calibration results which are obtained for decreasing loads H to G. For increasing loads G to H the uncertainty is U' (see also 5.1).

## 5.2 Examples

## 5.2.1 Example 1

In this example the calibration of a vehicle instrument with digital indication is dealt with. The instrument has four load cells, its Max is 20000 kg and d = 10 kg.

The MTEs for the instrument are f=10 kg for loads from 0 to $ \leq 5\ 000 $ kg and 2 f=20 kg for loads over 5000 kg to Max.

For the calibration nine verified weights of 2000 kg one of 1000 kg and two of 500 kg are used. They bear the marking n = 3000, i.e., their maximum permissible errors (mpe's) are $ \pm340 $ g, $ \pm170 $ g and $ \pm85 $ g respectively.

A) Tests (Contrary to recommendations in 2.3.2 and Section 4 all the following tests are performed without eliminating the digital rounding errors)

Both for increasing and decreasing loads the observed errors E are 0 for loads from 0 to $ \leq 5\ 000 $ kg and +10 kg for the loads over 5000 kg.

Weighing test (2.2):

## Repeatability test (4.2):

A vehicle of about 19 000 kg mass is used as the test load $ L_{R} $ . Six weighings are performed. Thus $ k_{n}=k_{6}\approx 0.4 $ . The observed result is R=0 but according to 4.2.2 $ R=d=10 $ kg has to be used. So $ k_{6} $ R=4 kg.

Weights (4.4):

For the load $ L_{RW}=19000 $ kg the sum W of the absolute values of the mpe's of the weights is $ W=9\times 340\mathrm{g}+1\times 170\mathrm{kg}=3\ 230\mathrm{g} $ . According to 4.4.1 $ u=0.4\times 3230\mathrm{g}\approx $ 1.3 kg.

Eccentricity test (4.5.1), zero return (4.5.2) and temperature effect (4.5.3):

The eccentricity test is performed with a load 6 500 kg ( $ \approx1/3 $ x Max). $ \Delta_{1}=10 $ kg $ (< 2 f=20 $ kg). $ \Delta_{2}=0 $ kg $ (< f= $

10 kg) and the slow changes $ \Delta t $ in the temperature were about $ 2^{\circ} \mathrm{C} $ during the weighing test. On this basis set $ z^{2}=(0.4\Delta_{1})^{2}+1 / r^{2}(0.2\Delta_{2})^{2}+(0.2\gamma L_{R}\Delta t)^{2}=0. $

During the weighing test variations in the indication were not noted and thus w=0 (4.6).

## B) Evaluation of U (w=0)

Denote $ z^{2}=0 $ . For loads from 0 to $ \leq 5000 $ kg the uncertainty U is (Table 1, point 2, r=0.4):

$$
U = 2 r \left[ \left(k _ {n} R\right) ^ {2} + 1 / r ^ {2} (0. 3 d) ^ {2} + u ^ {2} \right] ^ {1 / 2} = 2 \times 0. 4 x
$$

$$
[ 4 ^ {2} + 1 / 0. 4 ^ {\cdot 2} (0. 3 \times 1 0) ^ {2} + 1. 3 ^ {2} ] ^ {1 / 2} \approx 7 \mathrm {k g}
$$

For the loads > 5000 kg U is (Table 1, point 2, r = 1) $ U=2 r \left[ \left(k_{n} R\right)^{2}+1 / r^{2} \left(0. 3 \mathrm{d}\right)^{2}+u^{2} \right]^{1 / 2}=2 \times\left[ 4^{2}+\right. $ $ \left(0. 3 \times 1 0\right)^{2}+1. 3^{2}\right]^{1 / 2}\approx1 0 \mathrm{k g} $

## C) Conclusions

Loads from 0 to $ \leq 5\ 000 $ kg, $ \Box MTE\Box=10 $ kg and U=7 kg

The observed errors E are E=0 but actually they are in the range of $ - 5 \mathrm{~ k g} $ to $ + 5 \mathrm{~ k g} $ . The effect of this range is taken into account by using the term $ ( 0. 3 \mathrm{~ d} )^{2} $ in U. $ E \pm U=(0 \pm 7 \mathrm{~ k g}) $ and is within the MTEs for the loads in question. So the values of the "true" E satisfy the condition $ \square $ "true" E $ \square \leq $ $ \square $ MTE $ \square $ The probability P (3.3.1) is 100 %.

## Loads > 5000 kg, $ \Box M T E $ $ \Box = 2 0 $ kg and U = 10 kg

The observed errors E are E= +10 kg but actually they are in the range of +5 kg to +15 kg. This is taken into account by using the term $ ( 0. 3 \mathrm {d} )^{2} $ in U. $ E \pm U=(1 0 \pm 1 0 \mathrm {k g}) $ and is within the MTEs for the loads in question. So the values of the "true" E satisfy the condition $ \square $ "true" E $ \square \leq $ $ \square $ MTE $ \square $ The probability P is 100 %.

## 5.2.2 Example 2

In this example the calibration of a laboratory scale (high accuracy instrument) with digital indication is dealt with. The instrument has one load cell, its Max is 12000 g and d=1 g.

The $ \Box $MTE $ \Box $ for the instrument is f=2 g for all the loads from 0 to Max.

Verified weights 0.5 kg,1 kg,2 kg,5 kg and 10 kg are used. Their OIML accuracy class is $ M_{1}. $

A) Tests (According to the recommendations in 2.3.2 and in Section 4 all the following tests are performed eliminating the digital rounding errors)

Weighing test (2.2):

Both for increasing and decreasing loads the observed errors E are monotonically increasing from 0 to +1.5 g for the loads from 0 to Max respectively.

Repeatability test (4.2):

The 10 kg weight is used as the test load $ L_{R} $ . Six weighings are made. $ R=0. 6 $ g and $ k_{n}=k_{6}\approx 0. 4 $ . Thus $ k_{6} $ R=0.24 g.

Weights (4.4):

$ L_{R w}=1 0 \mathrm{~ k g}. $ The mpe of the 10 kg weight is 500 mg. Thus W=500 mg.According to 4.4.1 u=0.4 $ \times $ 500 mg $ \approx $ 0.2 g.

Eccentricity test (4.5.1), zero return (4.5.2) and temperature effect (4.5.3):

The eccentricity test is performed with a 4 kg load (= 1/3 x Max). Since $ \Delta_{1}=2 \mathrm{~g} $ (= f = 2 g) it is used to calculate $ z^{2}. $ $ \Delta_{2}=0.2 \mathrm{~g} $ (< f = 2 g) and the slow change $ \Delta t $ in the temperature was about $ 1^{\circ} \mathrm{C} $ during the weighing test. On this basis $ z^{2}=\left(0.4\Delta_{1}\right)^{2}+1 / r^{2}\left(0.2\Delta_{2}\right)^{2}+\left(0.2 \mathrm{~y} \mathrm{L}_{R} \Delta t\right)^{2} $ $ =\left(0.4 \Delta_{1}\right)^{2}=0.8^{2}. $

During the weighing test no variations in the indication were noted and thus w=0 (4.6).

## B) Evaluation of U (w=0)

Denote $ ( 0.3 \mathrm{d})^{2}=0 $ . For all the loads from 0 to Max the uncertainty U is (Table 1, point 3, r=1):

$$
\begin{array}{l} U = 2 r \left[ \left(k _ {n} R\right) ^ {2} + u ^ {2} + z ^ {2} \right] ^ {1 / 2} = 2 \times \left[ 0. 2 4 ^ {2} + 0. 2 ^ {2} + 0. 8 ^ {2} \right] ^ {1 / 2} \approx \\ 1. 7 \mathrm {g} \\ \end{array}
$$

## C) Conclusions

The observed errors E are noted to be from 0 to + 1.5 g. Thus E $ \pm $ U can take on values from $ (0\pm 1.7) $ g to $ (1.5\pm 1.7) $ g. For the loads near zero, the value of the

positive "true" E is from 0 to 1.7 g, and at Max it is from 0 to 3.2 g. The positive "true" E should be in the interval 0 to 2 g. For the loads near zero P is P = 100 % but for the Max load P is 2 g/3.2 g $ \approx $ 62 % but increases as the loads decrease.

However, if the eccentric error $ \Delta_{1} $ were adjusted so that $ \Delta_{1} < 2 $ g, its effect could be neglected and the uncertainty would be U = 2r $ [(k_{n} R)^{2}+u^{2}]^{1/2}= 2 \times[0.24^{2}+0.2^{2}]^{1/2}\approx 0.6 $ g. Except for the Max load P is now 100 %.

## 6 Uncertainty of practical weighing

Suppose that a calibrated instrument is used. The uncertainty of its calibration results is now considered to be one part of the uncertainty of practical weighing with the instrument.

Another part can be obtained by performing weighings with a large load in real weighing situations. Either 1) the weighings are made with the same large load several times or 2) with different large loads the results of which are checked with a control instrument.

In case 1) calculate the variance $ s^{2} $ of the results the number n of which is n $ \geq 5 $ . The variance $ s^{2} $ can also be determined by means of the range of the results. Therefore, choose $ k_{n} $ according to 4.2.1 and calculate $ s^{2}\approx(k_{n}x\mathrm{range})^{2}. $

In case 2) calculate the variance $ v^{2} $ of the differences between the results of the loads obtained with the instrument in question and with the control instrument. The number n of the loads weighed should be n $ \geq 5 $ $ v^{2} $ can also be calculated with the aid of the range of the differences.

Both $ s^{2} $ and $ v^{2} $ are assumed to be large compared with $ (k_{n}R)^{2} $ obtained in the repeatability test of the instrument (4.2).

The uncertainty of weighing is approximated by the combination of the uncertainty of calibration and the variance $ s^{2} $ or $ v^{2} $ . The combination is:

$$
\left(\mathrm {U} ^ {2} + 4 \mathrm {s} ^ {2}\right) ^ {1 / 2} \mathrm {o r} \left(\mathrm {U} ^ {2} + 4 \mathrm {v} ^ {2}\right) ^ {1 / 2}
$$

where U (w=0) is the uncertainty of calibration with large loads for which r=1 (4.1). For smaller loads the uncertainty of weighing should be estimated in the same way taking into account r<1 in U for these loads.

If w in 4.6.2 exists during the weighings, its value is determined as explained in 4.6.2 and $ U_{1}=\left(U^{2}+4 w^{2}\right)^{1/2} $ is calculated. This $ U_{1} $ is used instead of U in the above formulae of the uncertainty of weighing. Note that if w is w $ \neq0 $ during the calibration neither it nor the corresponding $ U_{1} $ for the calibration are used in the uncertainty of weighing.

OIML - OVERVIEW

<div align="center">

# The history of the International Organization of Legal Metrology

</div>

BERNARD ATHANE, Director of the International Bureau of Legal Metrology, 1974-2001

## 1 The gestation period, up to 1956

Despite the fact that the International Organization of Legal Metrology is relatively young (it is not yet 50 years old), in fact discussions concerning its establishment started at the dawn of the 20th century.

When the Meter Convention was signed in 1875, participants in the founding Conference referred to National Weights and Measures Offices, which were in fact legal metrology bodies since at that time National Measurement Institutes did not yet exist. It was the opinion of these participants that the harmonization of national measurement standards for the kilogram and the meter would be sufficient to eliminate barriers to trade resulting from divergences in measurement results, but in fact it was quickly realized that this harmonization was far from sufficient. Divergences in measurement results exist not only when primary standards are different, but also when the traceability schemes between primary standards and measuring instruments are different or when the accuracy requirements for measuring instruments and verification procedures are not harmonized. This is why the participants in several General Conferences of Weights and Measures (CGPM) discussed, during the first decades of the 20th century, the possibility of enlarging BIPM responsibilities to cover practical and legal metrology aspects, these being mainly matters of calibration and verification of measuring instruments.

Following decisions made by the CGPM and by the CIPM (International Committee of Weights and Measures) in 1933 and 1935, a first International Conference on Practical Metrology was convened by the French Government in July 1937, in the context of the Paris Exhibition. This Conference, which was attended by representatives from forty countries, was intended to establish a Permanent International Consultative Committee for Practical Metrology acting as an advisory body to the CGPM. Very quickly however, it was decided that the objectives of the Conference should cover "legal

metrology" and the main output of three days of discussions was to create a Provisional Committee of Legal Metrology aimed at preparing the establishment of a permanent international body for legal metrology. The Provisional Committee should have met in Berlin in 1938. Owing to the prevailing international situation, it was only in 1950 in Paris that it was able to meet for the first time, to start developing the layout of a Convention Establishing an International Organization of Legal Metrology. Then during two years the Provisional Committee pursued its activities by correspondence and met again in 1952 in Brussels. This meeting and the intense activity which followed resulted in two essential steps in the life of the OIML:

in 1955, the signature by 24 countries of the Convention Establishing an International Organization of Legal Metrology;

in 1956, the First International Conference of Legal Metrology, held in Paris.

## 2 The OIML Founder Fathers

It is not possible to retrace the history of the OIML without mentioning the names of those who contributed significantly to its establishment and first steps. This is however a difficult task owing to the risk of forgetting specific persons whose names do not explicitly appear in the archives of the OIML although they may have positively influenced - sometimes just at the national level - the existence of the OIML.

To diminish this risk, the names given below are extracted from the addresses delivered at the First OIML International Conference and the attendance list of this Conference.

Amongst the participants in the 1937 Conference on Practical Metrology, those who were able to contribute to further steps were mainly Messrs.:

Kösters (Germany)

Jacob (Belgium)

Nielsen (Denmark)

Viaud and Costamagna (France)

Rauszer (Poland)

Statescu (Rumania)

Volet (Switzerland)

Chatelain (USSR)

Kargacin (Yugoslavia) and

Perard (Director of the BIPM).

The Provisional Committee also benefited from the experience of Messrs. Stulla-Gotz (Austria), Dolimier (France), Idema (The Netherlands) and Zalutsky (USSR).

Most of these names were referred to in various addresses delivered on the occasion of the First OIML Conference. Special emphasis was put on the role of Messrs. Jacob, who chaired the International Committee of Legal Metrology (CIML), and Costamagna, who had acted as Secretary of the 1937 Conference, of the Provisional Committee, of the First Conference and of the CIML, before being appointed Director of the International Bureau of Legal Metrology (BIML).

In addition, the First Conference was attended by a number of "new" persons who subsequently played a role in the development of the OIML, especially Messrs.:

Vieweg (Germany)

Chritiansen (Denmark)

de Artigas (Spain)

Honti (Hungary)

Koch (Norway)

König (Switzerland) and

Bourdoun (USSR).

The Conference was chaired by Mr. Perard with Messrs. de Artigas and Honti as Vice-Presidents. The CIML, chaired by Mr. Jacob, elected Mr. Bourdoun as its First Vice-President.

Most if not all of the persons mentioned above have now passed away. At least three participants in the First Conference are nevertheless still alive. One of them is Mr. Koch, from Norway, who went on to be CIML Member. The other two were members of a unified German Delegation including representatives from both Western and Eastern parts of Germany: those are Messrs. Mühe and Liers who thereafter also represented the Federal Republic of Germany and the Democratic Republic of Germany on the CIML, up to the re-unification of this country.

It should also be noted that two countries which had participated in the 1937 Conference and in the Provisional Committee attended the First Conference as Corresponding Member and Observer respectively: the United Kingdom (represented by Mr. Poppy) and the United States of America (represented by Messrs. Crittenden and then Astin) which joined as Member States in 1962 and 1972 respectively. Other countries became active within the OIML following its establishment: certain of those are mentioned below.

## 3 The first years, 1956-1968

During its first twelve years the OIML simultaneously benefited and suffered from a number of characteristics inherent to its role as defined by the OIML Convention, to the profile of national legal metrology experts, to its membership, and to the economic and political situation which prevailed at this time.

Most of the national legal metrology services in OIML Member States were well established administrations, with relatively numerous technical staff, eager to cooperate at international and, for certain of them, regional levels. For example the regulatory developments within the European Common Market, including the drafting of legal metrology Directives, took place exactly at the same time as the development of the first OIML Recommendations, with practically the same experts from Western European countries working at both levels. Similarly, cooperation within the Council for Mutual Economic Assistance included the development of verification and calibration specifications for measuring devices and the OIML benefited from this activity carried out by Eastern European countries.

However, these beneficial characteristics also had an adverse aspect: the OIML was not really an international body, since most of the human resources were provided by European countries. In addition, Western and Eastern European countries had different views concerning the scope of legal metrology: it was limited to measuring instruments used for trade (and to some extent for medicine, safety and pollution) in Western Europe whereas practically all measuring instruments were covered by mandatory specifications in Eastern Europe. In addition, most of the metrology administrations in this part of the world were included in larger national committees covering standardization and quality control, which in certain cases made the life of legal metrology services somewhat difficult.

The OIML also had to face a problem of acceptance by other international bodies working in fields connected with legal metrology. The cooperation with the bodies of the Meter Convention and the BIPM was nearly non-existent whereas a close cooperation would probably have been useful to promote metrology at the international level. Conflicts appeared mainly with certain standardization spheres; it was considered that OIML work overlapped the responsibilities of ISO/IEC in fields such as the measurement of petroleum products, water meters, electricity meters, gauge blocks, electrical thermometers, etc.

Despite these difficulties the OIML was able to establish its basis and prove its usefulness through its technical output. At the time of the Third OIML Conference held in Paris in 1968, 18 Recommendations had already been approved, 8 were at the level of final drafts and some 33 texts were being developed within the relevant technical secretariats. An extremely important OIML publication had also been approved: the Vocabulary of Legal Metrology (developed under the chairmanship of Mr. Obalski from Poland) which was to remain (together with the IEC Vocabulary) the international basis for metrology terminology up to the issuing, some twenty years later, of the International Vocabulary of Basic and General Terms in Metrology, the

now well known VIM developed through the cooperation of seven international bodies, including ISO, IEC the BIPM and the OIML.

The growth of the OIML during its first twelve years was also made evident by other parameters such as the number of Member States (36 in 1968) and the more frequent meetings of the International Committee which was chaired by Mr. Stulla-Götz (Austria) from 1962 (date of the Second OIML Conference in Vienna) through 1968 and then by Mr. van Male (The Netherlands).

In parallel with its technical activity, the OIML had from its very beginning initiated actions aimed at encouraging the establishment of sound legal metrology resources in Developing Countries. Amongst the main actors of this activity were Representatives of India Indonesia and Morocco (Messrs. Putera and Benkirane acting as CIML Members for Indonesia and Morocco over some twenty years), actively supported by other Member States such as Sri Lanka and Cuba, as well as by more industrialized Members e.g. Germany, France United Kingdom and USSR. Cooperation with UNESCO, UNIDO and ISO/DEVCO was effective and it is unfortunate that at this time the BIPM had not developed any action in favor of development since the needs of Developing Countries in fact cover all aspects of metrology.

## 4 The planning and internationalization period, 1968-1980

participation of certain Member States such as Australia and Japan. This also made OIML work more international and even if most Pilot and Reporting Secretariats continued to be under the responsibility of European Countries, their international working groups gradually became truly international.

A complete restructuring of OIML technical bodies, including new working methods and a strict planning of the work was developed at the initiative mainly of the USSR (represented by Mr. Ermakov as CIML Member). This action, in which the Presidential Council and the BIML actively participated, resulted in decisions made by the Fourth OIML Conference (London, 1972), with an implementation over the period 1973-1974 (i.e. the time at which Mr. Costamagna retired as BIML Director). The new OIML work program, operated by a number of Pilot and Reporting Secretariats, represented a significant growth in the OIML activities which would have exceeded the current possibilities of the Organization without a significant growth in its membership (e.g. the USA in 1972) and in parallel a more active technical

From 1968 it appeared that the OIML work should be reorganized with a view to better utilizing the human and financial resources that the Member States would allocate to this work, coping with the various needs expressed by countries or regions in the field of legal metrology, and diminishing as far as possible the technical conflicts that might exist with other international bodies, especially with ISO.

In order to solve certain conflicts with other international scientific, technical and standardizing bodies as well as with certain regional bodies with legal metrology connected activities, the Fifth OIML Conference (Paris, 1976) which was attended by the Representatives of ten such international and regional bodies, encouraged the development of cooperative agreements which were then implemented (in a rather satisfactory manner) by both the BIML and the OIML Technical Secretariats, under the supervision of the Presidential Council and the CIML.

At the end of the second twelve-year period in the life of the OIML, i.e. at the time of its Sixth Conference (Washington D.C., 1980) the OIML included 46 Member States (two countries, Canada and the People's Republic of China, attending this Conference as observers before joining the OIML as Member States) and 18 Corresponding Members. It had established liaisons with more than 50 international and regional bodies and had issued over 60 publications.

## 5 The globalization, deregulation and regionalization period, 1980-2000

During this period several economic, social and political aspects of our world deeply influenced the life of the OIML. The first symptoms appeared at the beginning of the eighties to become more and more obvious during the nineties. The so-called "globalization" of our world resulted in the obligation for international and regional bodies to increasingly coordinate their activities and carry out their tasks, bearing in mind what is done within other spheres. Much of this coordination is now conducted under the umbrella of the WTO, and especially its TBT Committee which gives the opportunity to ten or so international standard-setting organizations (including ISO, IEC, OIML, etc.) to explain their respective roles and demonstrate to WTO Members that the existing cooperation is effective. In parallel the OIML has developed a closer cooperation with the BIPM (a merger of the two intergovernmental metrology organizations being impossible for the time being) and with ILAC.

The last twenty years have also been an opportunity for many countries to reflect about the need for regulations, especially in technical fields. This evolution appeared clearly in countries which already had a

market-oriented economy, and even more in countries moving from the planned to the market economy. Legal metrology is by definition a regulatory activity and it has been necessary to initiate actions with a view to demonstrating the economic and social role of legal metrology (in connection with that of metrology as a whole) in order to convince Governments that they should continue to support this activity at the national, regional and international levels. A first step was an International Seminar organized in Germany in 1998, with further actions being planned for 2002 or 2003. However, this deregulation tendency connected with economic difficulties in many countries resulted in a significant decrease in the financial resources allocated to national legal metrology services and therefore a decrease in the human resources available within the OIML technical bodies.

The third main aspect (from the point of view of the OIML) was the development of regional activity. This is not specific to legal metrology: scientific metrology, accreditation, standardization and many other activities are also the subject of closer regional cooperation. For the OIML, this resulted in the fact that the already decreasing human resources from Member States had to be shared with regional activities, with a tendency for many people to focus on regional work to the detriment of the international level.

In order to cope with these movements and to maintain worldwide OIML leadership in the field of legal metrology, several important decisions were made by the OIML Conferences in 1984 (Helsinki), 1988 (Sydney), 1992 (Athens), 1996 (Vancouver) and 2000 (London), and by the CIML which, under the chairmanship of Messrs. Birkeland (Norway) from 1980 through 1994, and Faber (The Netherlands) from 1994, met every year (it should be noted that, in response to the increasing rapidity of the events that affected our world, the periodicity of the OIML Conferences was reduced from 6 years to 4 years and that of CIML meetings from two or one and half years to one year).

These decisions mainly dealt with:

the definition of a general long-term policy for OIML activities;

as already mentioned, the participation in the organization, in cooperation with the BIPM, IMEKO and the German PTB, of an International Seminar on the economic and social role of metrology (Braunschweig, June 1998);

are considered as priority topics by a number of OIML Members or the study of which is requested by another international or regional body;

the implementation of a study made by Mr. Birkeland concerning the orientations the OIML should follow, including the development of a medium-term Action Plan;

- a drastic revision of the OIML technical work program in order to focus on those work items which

a restructuring of OIML technical bodies (Technical Committees and Subcommittees) with new work methods (inspired from ISO/IEC rules) in order to introduce better efficiency, rapidity and flexibility in the work;

a new layout for OIML Recommendations to be developed in terms of performance requirements and supplemented by test procedures and a format to report test results;

the definition of new responsibilities for the Presidential Council, to better advise the CIML President and Vice-Presidents;

a restructuring of the OIML Development Council;

the establishment of a certification system (the OIML Certificate System for Measuring Instruments) through which certificates may be issued for types of instruments that meet the requirements specified in the relevant OIML Recommendations;

a re-evaluation of the liaisons between the OIML and international and regional bodies, especially Regional Legal Metrology Organizations;

the development of modern communication and information tools (OIML Bulletin, OIML web site, use of electronic communication means, etc.);

the modernization of work facilities at the OIML headquarters, the International Bureau of Legal Metrology (BIML) the staff of which has remained at practically the same level (9 staff members in 1974, 10 in 2001) whereas its workload has considerably increased during the same period, with more publications, more liaisons with international and regional bodies, more Member States and Corresponding Members, and the quasi systematic use of English and French as working languages whereas only French was used up to the mid-seventies.

As at mid 2001, the OIML has 57 Member States, 51 Corresponding Members, liaisons with over 100 international and regional bodies; the number of publications amounts to more than 160 and that of issued certificates to more than 800.

## 6 At the dawn of the twenty-first century

The division of the life of an international body such as the OIML into well-identified periods of time is of course artificial - or at least subjective. There are

however signals which show that the OIML could now enter a new period of its life with, beyond the necessary continuity, new developments in its role and its activities.

The extension of the certification system to cover initial verification of measuring instruments, the enforcement of mutual acceptance agreements of test results associated with OIML certificates, the international marking of prepacked products, evolutions in the cooperation between the OIML and international and regional bodies, an acceleration in the production of

OIML technical publications and perhaps a new approach in their content, all these developments will probably change the OIML deeply during the next ten years.

At the end of September 2001, a new Director took over the responsibility of leading the BIML in such a way that the OIML will be able to follow the new directions defined by its Members, in order to contribute to better satisfying the needs of our society.

<div align="center">

# OIML Certificate System: Certificates registered 2001.05-2001.07

</div>

For up to date information: www.oiml.org

The OIML Certificate System for Measuring Instruments was introduced in 1991 to facilitate administrative procedures and lower costs associated with the international trade of measuring instruments subject to legal requirements.

The System provides the possibility for a manufacturer to obtain an OIML certificate and a test report indicating that a given instrument pattern complies with the requirements of relevant OIML International Recommendations.

Certificates are delivered by OIML Member States that have established one or several Issuing Authorities responsible for processing applications by manufacturers wishing to have their instrument patterns certified.

OIML certificates are accepted by national metrology services on a voluntary basis, and as the climate for mutual confidence and recognition of test results develops between OIML Members, the OIML Certificate System serves to simplify the pattern approval process for manufacturers and metrology authorities by eliminating costly duplication of application and test procedures.

![](page=22,bbox=[260, 1034, 1816, 1807])

<div align="center">

# Système de Certificats OIML:

Certificats enregistrés 2001.05-2001.07

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

R31/1995-RU-01.01

BK-G 1,6

G. Kromschröder AG, Postfach 2809,

D-49018 Osnabrück, Germany

## INSTRUMENT CATEGORY

CATÉGORIE D'INSTRUMENT

Automatic catchweighing instruments

Instruments de pesage trieurs-étiqueteurs

à fonctionnement automatique

R 51 (1996)

Issuing Authority / Autorité de délivrance Netherlands Measurement Institute (NMi) Certin B.V., The Netherlands

R51/1996-NL1-97.02 Rev.1

Types DACS-W-***-**, BC-W-***-** and

DACS-H-***-** (Class X(1))

Ishida Co., Ltd., 959-1, Shimomagari, Kurita-Gun,

Ritto-cho, Shiga 520-3026, Japan

## INSTRUMENT CATEGORY

CATÉGORIE D'INSTRUMENT

Metrological regulation for load cells

(applicable to analog and/or digital load cells)

Réglementation métrologique des cellules de pesée

(applicable aux cellules de pesée à affichage

analogique et/ou numérique)

R60(2000)

Issuing Authority / Autorité de délivrance National Weights and Measures Laboratory (NWML), United Kingdom

## R60/2000-GB1-01.01

R60/2000-GB1-01.01 Type VC 1600 (Class C1.5 Thames-Side Maywood Ltd., 17 Stadium Way, Tilehust Reading, Berkshire RG30 6BX, United Kingdom

Issuing Authority / Autorité de délivrance Netherlands Measurement Institute (NMi) Certin B.V., The Netherlands

## R60/2000-NL1-01.05 Rev.1

Type CPI (Class C)

Precia S.A., BP 106, F-07001 Privas cedex, France

## R60/2000-NL1-01.06 Rev.1

R60/2000-NL1-01.06 Rev.1 Type 0785 (Class C) Mettler-Toledo Inc., 150 Accurate Way, Inman, SC 29349, USA

## R60/2000-NL1-01.11

## Type 1252 (Class C)

Tedea Huntleigh International Ltd., 5a Hatzoran St., Netanya 42506, Israël

## R60/2000-NL1-01.12

## Type FIT. . . . (Class C)

Hottinger Baldwin Messtechnic Wägetechnik GmbH, Im Tiefen See 45, D-64293 Darmstadt, Germany

## R60/2000-NL1-01.13

Type LC-21 (Class C)

Grupo Epelsa S.L., Ctra. Sta. Cruz de Calafell, 35 km.

9,400, E-08830 Sant Boi de Llobregat, Barcelona, Spain

## R60/2000-NL1-01.14

Type CBS ... (Class C)

Acom Inc., #44-5, Bangchuk-ri, Kasan-myun,

Pocheon-gun, Kyungki-do, Rep. of Korea

INSTRUMENT CATEGORY

CATÉGORIE D'INSTRUMENT

Automatic gravimetric filling instruments

Doseuses pondérales à fonctionnement automatique

R 61 (1996)

Issuing Authority / Autorité de délivrance Physikalisch-Technische Bundesanstalt (PTB), Germany

R61/1996-DE-01.01 Type EWU-010 (Accuracy class Ref (0.2)) Ventomatic SPA, Via G. Marconi 20, I-24030 Valbrembo (Bergamo), Italy

Issuing Authority / Autorité de délivrance Netherlands Measurement Institute (NMi) Certin B.V., The Netherlands

R61/1996-NL1-01.05 Types VB I W1500, VB II W1500 or Special-A (Class X(1)) TBMA Europe B.V., Delfweg 18, 2211 VM Noordwijkenthout, The Netherlands

## INSTRUMENT CATEGORY

CATÉGORIE D'INSTRUMENT

Nonautomatic weighing instruments

Instruments de pesage à fonctionnement

non automatique

R 76-1 (1992), R 76-2 (1993)

Issuing Authority / Autorité de délivrance Physikalisch-Technische Bundesanstalt (PTB), Germany

R76/1992-DE-00.09 Rev.2

Type iso-TEST (Classes I, II, III and IIII)

Sartorius A.G., Weender Landstraße 94-108,

D-37075 Göttingen, Germany

R76/1992-DE-01.01 Type BT... (Classes III and IIII) Bizerba GmbH & Co. KG, Wilhelm-Kraut-Straße 65, D-72336 Balingen, Germany

R76/1992-DE-01.02 Type DISOMAT S (Classes III and IIII) Schenk Process GmbH, Landwehrstraße 55, D-64293 Darmstadt, Germany

Issuing Authority / Autorité de délivrance Netherlands Measurement Institute (NMi) Certin B.V., The Netherlands

R76/1992-NL1-98.03 Rev.1

Type DPS-3600..(Class III)

Teraoka Seiko Co., Ltd., 13-12 Kugahara, 5-Chome,

Ohta-ku, Tokyo 146-8580, Japan

R76/1992-NL1-01.10

Type SM-500. . . (Class III)

Teraoka Seiko Co., Ltd., 13-12 Kugahara, 5-Chome,

Ohta-ku, Tokyo 146-8580, Japan

## R76/1992-NL1-01.11

Types AW-3600, AW-3600CP and AW-3600CP (Class III) Teraoka Seiko Co., Ltd., 13-12 Kugahara, 5-Chome, Ohta-ku, Tokyo 146-8580, Japan

## R76/1992-NL1-01.12

R76/1992-NL1-01.12 Type PS60 (Class III) Mettler-Toledo Inc., 1150 Dearborn Drive, Worthington, Ohio 43085-6712, USA

## R76/1992-NL1-01.13

Type SUP-**S (Class III)

Shang Chuen Weighing Machine Co., Ltd, No. 53,

Liao-Yang 4th St., Taichung City 406, R.O.C., Taiwan

## R76/1992-NL1-01.14

Type FTS-**S (Class III)

Shang Chuen Weighing Machine Co., Ltd, No. 53,

Liao-Yang 4th St., Taichung City 406, R.O.C., Taiwan

## R76/1992-NL1-01.15

Type ASTRA (Class III)

Descom Co., Ltd., 4-12 Wonmi Dong, Wonmi-Ku,

Buchon-City, Kyungki-Do 420-110, Rep. of Korea

## R76/1992-NL1-01.16

(Class III)

Tanita Corporation (Brand names: Tanita, Rhewa),

14-2, 1-Chome, Maeno-cho, Itabashi-ku,

Tokyo 147-8630, Japan

## R76/1992-NL1-01.17 Rev.1

Type BS-series (Class III)

SNOWREX International Co., Ltd., 5F No. 3, Lane 50,

Sec. 3, Nan-Kang Road, Taipei, R.O.C., Taiwan

## R76/1992-NL1-01.18

Type K-serie (Class III)

DIBAL S.A., c/ Astintze Kalea, 24, Poligono Industrial

Neinver, E-48016 Derio (Bilbao-Vizcaya), Spain

## R76/1992-NL1-01.19

Types BM-2 and BM-3 (Class III)

Digital Scales S.A., Poligono Industrial Larrondo,

Beheko Etorbidea, no. 2 Naves 2, 3, 4,

E-48180 Loiu Vizcaya, Spain

## R76/1992-NL1-01.20

Type DS-671 (Class III)

Teraoka Seiko Co., Ltd., 13-12 Kugahara, 5-Chome,

Ohta-ku, Tokyo 146-8580, Japan

## R76/1992-NL1-01.21

Type DS-682 (Class III)

Teraoka Seiko Co., Ltd., 13-12 Kugahara, 5-Chome,

Ohta-ku, Tokyo 146-8580, Japan

## R76/1992-NL1-01.22

Type BM-1 (Class III)

Digital Scales S.A., Poligono Industrial Larrondo,

Beheko Etorbidea, no. 2 Naves 2, 3, 4,

E-48180 Loiu Vizcaya, Spain

R76/1992-NL1-01.23 (Classes II and III) Mettler-Toledo A.G., Im Langacher, CH-8606 Greifensee, Switzerland

R76/1992-NL1-01.24

Type SM-300. . . (Class III)

Teraoka Seiko Co., Ltd., 13-12 Kugahara, 5-Chome,

Ohta-ku, Tokyo 146-8580, Japan

## R76/1992-NL1-01.25

R76/1992-NL1-01.25

Type SM-500... (Class III)

Teraoka Seiko Co., Ltd., 13-12 Kugahara, 5-Chome,

Ohta-ku, Tokyo 146-8580, Japan

## R76/1992-NL1-01.26

Types PG-S, CG and GG (Classes I and II) Mettler-Toledo A.G., Im Langacher, CH-8606 Greifensee, Switzerland

## R76/1992-NL1-01.27

Type DS-788 (Class III)

Teraoka Seiko Co., Ltd., 13-12 Kugahara, 5-Chome,

Ohta-ku, Tokyo 146-8580, Japan

## R76/1992-NL1-01.28

Types BM-2 and BM-3..(Class III)

Digital Scales S.A., Poligono Industrial Larrondo,

Beheko Etorbidea, no. 2 Naves 2, 3, 4,

E-48180 Loiu Vizcaya, Spain

## R76/1992-NL1-01.29

R76/1992-NL1-01.29

Type ECO (Class III)

Grupo Epelsa S.L., Ctra. Sta. Cruz de Calafell, 35 km.

9,400, E-08830 Sant Boi de Llobregat, Barcelona, Spain

R76/1992-NL1-01.30 IW-series (Class III) Ishida Co., Ltd., 44, Sanno-cho, Shogoin, Sakayo-ku, Kyoto-city 606-8392, Japan

![](page=25,bbox=[1619, 1979, 1731, 2033])

## INSTRUMENT CATEGORY

CATÉGORIE D'INSTRUMENT

## Fuel dispensers for motor vehicles

Distributeurs de carburant pour véhicules à moteur

R 117 (1995) [+ R 118 (1995)]

Issuing Authority / Autorité de délivrance Netherlands Measurement Institute (NMi) Certin B.V., The Netherlands

## R117/1995-NL1-01.05

Models BS and EM8 Max=45 L/min (Class 0.5)

Bennett + Sauser Ltd., Refuelling systems, Bielstrasse 80 / PF 40, CH-4503 Solothurn, Switzerland

## R117/1995-NL1-01.06

Models BS and EM8 Max=85 L/min (Class 0.5)

Bennett + Sauser Ltd., Refuelling systems, Bielstrasse 80 / PF 40, CH-4503 Solothurn, Switzerland

## R117/1995-NL1-01.07

Models BS and EM8 Max=120 L/min (Class 0.5)

Bennett + Sauser Ltd., Refuelling systems, Bielstrasse 80 / PF 40, CH-4503 Solothurn, Switzerland

## R117/1995-NL1-01.09

Model Quantium, Harmony

(with PAS-V3 gas elimination device) (Class 0.5)

Tokheim Europe & Africa, Koppens Automatic Fabrieken B.V., Industrieweg 5, 5531 AD Bladel, The Netherlands

## R117/1995-NL1-01.10

Model Quantium, Harmony (with EPZ gas elimination device) (Class 0.5)

Tokheim Europe & Africa, Koppens Automatic Fabrieken B.V., Industrieweg 5, 5531 AD Bladel, The Netherlands

## www.oiml.org

Keep in touch with the OIML

Visit our web site regularly to obtain updated information on:

Meeting Calendar

Forthcoming Events

BIML Contacts

Technical Committees

Development Council

Membership

Publications

Bulletin

Registered Certificates

Liaisons

![](page=27,bbox=[208, 281, 311, 378])

<div align="center">

# 51ème Assemblée Générale

</div>

<div align="center">

# Bratislava (République Slovaque)

25 mai 2001

</div>

MICHEL TURPAIN, Secrétaire Permanent

Le CECIP, Comité Européen des Constructeurs d'Instruments de Pesage, vient de tenir sa 51ème Assemblée Générale à Bratislava en République Slovaque, à l'invitation de la jeune et enthousiaste Fédération Slovaque, UVV SR, Unia Vyrobcov Vah Slovenskej Republiky.

Poursuivant notre ouverture mondiale, après l'invitation d'une délégation chinoise en 2000, nous avons reçu cette année le Président de la "Scale Manufacturers Association" des États-Unis, M. David Castle, permettant un échange de vue avec les quatorze Fédérations du CECIP représentant les pays suivants:

Allemagne, Belgique, Espagne, Finlande, France, Hongrie Italie, Pays-Bas, Pologne, Royaume-Uni, Rép. Slovaque,

Suisse, Rép. Tchèque, Ukraine

L'Assemblée Générale est aussi l'occasion d'inviter des experts ou des personnalités d'organismes internationaux ou européens pour nous faire part de leur politique ou de leur point de vue sur des sujets touchant le pesage. Cette année nous avions l'honneur de recevoir:

Madame Kvetoslava Steinlova de l'Office Slovaque des Étalons, de la Métrologie et des Essais, qui nous a présenté l'Économie Slovaque sur le chemin de l'Union Européenne,

- Monsieur Robert Spurny de l'Institut Slovaque de Métrologie et Monsieur Jozef Orlovský de l'Office Slovaque des Étalons, de la Métrologie et des Essais, qui nous ont présenté La Métrologie des masses en République Slovaque et ses aspects légaux,

Monsieur Mike Koch, Président du Groupe de Travail WG2 au WELMEC, qui nous a présenté Le Projet de Directive sur les Instruments de Mesure (MID),

Monsieur David Castle, Président de l'Association des Industriels du Pesage des États-Unis, qui nous a présenté son Association,

- Monsieur Jean Luc Masset, Directeur Général de Carrefour pour la République Slovaque et la République Tchèque, qui nous a présenté l'Evolution de Carrefour et son approche du marché européen et international.

Toutes les interventions, de grande qualité et très appréciées, touchaient plusieurs thèmes d'actualité, l'ouverture de l'Union Européenne et les attentes d'un pays comme la République Slovaque, la mesure avec ses aspects physiques et sa réglementation, la mondialisation des marchés avec les industriels américains et l'expansion de la grande distribution.

Chaque Fédération a ensuite présenté la situation de l'industrie du pesage dans son pays, avec un tableau récapitulatif détaillant la production d'instruments de pesage en Europe et montrant une stabilité globale de la production par rapport à 1999.

La partie statutaire comprenait comme les autres années:

les rapports d'activité de chaque groupe de travail:

le groupe métrologie légale qui poursuit sa tâche de propositions et d'examens:

- des documents de l'OIML, en particulier la révision des Recommandations touchant les instruments de pesage à fonctionnement automatique,

- des documents de la Commission Européenne,

en particulier le projet de MID,

des documents du WELMEC, European Cooperation in Legal Metrology, en particulier les guides d'harmonisation,

le groupe Affaires et Commerce qui veille à une concurrence saine sur les marchés et aux intérêts des constructeurs et des consommateurs, en particulier dans le projet de MID,

le Bureau qui assure la gestion quotidienne du Comité et son développement en prenant contact avec les Fédérations de constructeurs d'instruments de pesage à travers le monde, amenant de nouveaux membres au CECIP, comme l'Ukraine l'année dernière, en apportant notre expérience aux jeunes Fédérations des pays qui frappent à la porte de l'Union Européenne, en créant des liens avec les Fédérations de Chine, des États-Unis d'Amérique ou du Japon,

l'invitation de la Fédération des Pays-Bas pour recevoir la 52ème Assemblée Générale, le 10 Mai 2002.

Nos amis Slovaques avaient parfaitement organisé cette Assemblée Générale dans le cadre superbe de l'Hôtel de Ville ou Palais de l'Archevêque, dans la Galerie des Glaces, au cœur du quartier historique de Bratislava que nous avons parcouru avec plaisir sous un soleil radieux. Cette journée de travail fut suivie d'une visite du Château qui domine la ville et d'une croisière sur le Danube pour terminer la journée dans une auberge typique en bordure du fleuve. Merci à tous nos amis Slovaques et à l'année prochaine aux Pays-Bas!

![](page=28,bbox=[302, 287, 404, 389])

<div align="center">

# 51 $ ^{st} $ General Assembly

</div>

Bratislava (Slovak Republic) 25 May 2001

MICHEL TURPAIN, Permanent Secretary

CECIP, the European Committee of Weighing Instrument Manufacturers, held its 51 $ ^{st} $ General Assembly in Bratislava, Slovak Republic, at the invitation of the young and enthusiastic Slovak Federation, UVV SR, Unia Vyrobcov Vah Slovenskej Republiky.

In line with CECIP's policy of openness to the world and following the invitation of a Chinese delegation in 2000, this year CECIP's guest was the President of the United States Scale Manufacturers Association, Mr. David Castle, which facilitated an exchange of views between the fourteen CECIP Federations representing the following countries:

Belgium, Czech Republic, Finland, France, Germany Hungary, Italy, Netherlands, Poland, Slovak Republic Spain, Switzerland, Ukraine, United Kingdom

The General Assembly is also an opportunity to invite experts or key individuals from international or European bodies to report on their policies and to share their views on weighing related subjects. This year the Assembly was honored to welcome:

Mrs. Kvetoslava Steinlova from the Slovak Office of Standards, Metrology and Testing, who gave a speech on The Slovak economy on the way towards the European Union,

<div align="center">

Statistiques, Industrie du Pesage (2000)

</div>

Weighing Industry Statistics (2000)

<table border="1"><tr><td rowspan="2">PaysCountry</td><td colspan="2">Production</td><td rowspan="2">Variation/1999</td><td>Export</td><td>Import</td></tr><tr><td>HT Monnaie localeEx VAT local currency</td><td>HT M.EuroEx VAT M.Euro</td><td>Variation/1999</td><td>Variation/1999</td></tr><tr><td rowspan="2">AllemagneGermany</td><td rowspan="2">1325M.DEM</td><td rowspan="2">677</td><td rowspan="2">+3%</td><td>829M.DEM</td><td>477M.DEM</td></tr><tr><td>+14%</td><td>+20%</td></tr><tr><td>BelgiqueBelgium</td><td></td><td></td><td></td><td></td><td></td></tr><tr><td rowspan="2">EspagneSpain</td><td rowspan="2">18079M.ESP</td><td rowspan="2">109</td><td rowspan="2">-17%</td><td>6400M.ESP</td><td>2713M.ESP</td></tr><tr><td>+35%</td><td>-55%</td></tr><tr><td rowspan="2">FinlandeFinland</td><td rowspan="2">150M.FIM</td><td rowspan="2">25</td><td rowspan="2">+7.1%</td><td>28M.FIM</td><td>66.2M.FIM</td></tr><tr><td>+20%</td><td>+11%</td></tr><tr><td rowspan="2">FranceFrance</td><td rowspan="2">1193M.FRF</td><td rowspan="2">182</td><td rowspan="2">-1.8%</td><td>464M.FRF</td><td>782M.FRF</td></tr><tr><td>-1%</td><td>+2.9%</td></tr><tr><td>HongrieHungary</td><td></td><td></td><td></td><td></td><td></td></tr><tr><td rowspan="2">ItalieItaly</td><td rowspan="2">171850M.ITL</td><td rowspan="2">89</td><td rowspan="2">+4.4%</td><td>39360M.ITL</td><td>38050M.ITL</td></tr><tr><td>+4.6%</td><td>+1.7%</td></tr><tr><td rowspan="2">Pays BasNetherlands</td><td rowspan="2"></td><td rowspan="2"></td><td rowspan="2"></td><td></td><td></td></tr><tr><td></td><td></td></tr><tr><td rowspan="2">PolognePoland</td><td rowspan="2"></td><td rowspan="2"></td><td rowspan="2"></td><td></td><td></td></tr><tr><td></td><td></td></tr><tr><td rowspan="2">Rép. SlovaqueSlovak Republic</td><td rowspan="2"></td><td rowspan="2"></td><td rowspan="2"></td><td></td><td></td></tr><tr><td></td><td></td></tr><tr><td rowspan="2">Rép. TchèqueCzech Republic</td><td rowspan="2">383M.CZK</td><td rowspan="2">11.3</td><td rowspan="2">+11.6%</td><td>44M.CZK</td><td>291M.CZK</td></tr><tr><td>+51.7%</td><td>+91.4%</td></tr><tr><td rowspan="2">Royaume-UniUnited Kingdom</td><td rowspan="2">121.6M.GBP</td><td rowspan="2">198</td><td rowspan="2">-5%</td><td>86.28M.GBP</td><td>83.5M.GBP</td></tr><tr><td>-8.53%</td><td>+7.44%</td></tr><tr><td rowspan="2">SuisseSwitzerland</td><td rowspan="2"></td><td rowspan="2"></td><td rowspan="2"></td><td>215.2M.CHF</td><td>71.1M.CHF</td></tr><tr><td>-1.6%</td><td>+8.6%</td></tr></table>

Mr. Robert Spurny from the Slovak Institute of Metrology and Mr. Jozef Orlovsky from the Slovak Office of Standards, Metrology and Testing, who gave a speech on Mass metrology in the Slovak Republic and its legal aspects,

Mr. Mike Koch, WELMEC Working Group 2 Chair, who presented the Draft Measuring Instruments Directive (MID),

Mr. David Castle, President of the United States Scale Manufacturers Association, who presented this Association,

Mr. Jean Luc Masset, Director General of Carrefour for the Slovak Republic and the Czech Republic, who talked about The development of Carrefour and its approach to the European and International markets.

All the presentations were of a high standard and much appreciated, and dealt with a number of topical themes such as the opening up of the European Union, the expectations of countries such as the Slovak Republic, measurements and their physical and statutory requirements, globalization of markets with American industrials and the expansion of the retail sector.

Each Federation then presented the situation of the weighing industry in its country, including a table summarizing weighing instrument production in Europe, which indicates a globally stable situation compared to 1999.

The statutory part included, as in previous years:

activity reports for each working group:

the legal metrology group, which is continuing with its task of coming up with proposals and examinations:

of European Commission documents, especially the draft MID,

of OIML documents, especially the revision of Recommendations dealing with automatic weighing instruments,

of WELMEC (European Cooperation in Legal Metrology) documents, especially harmonization guides,

the Business and Commerce Group, which ensures healthy market competition and which monitors the interests of manufacturers and consumers, especially concerning the draft MID,

the Bureau, which takes care of the day-to-day management of the Committee and of its development by making contact with the Federations of weighing instrument manufacturers throughout the world, bringing on board new CECIP members, such as Ukraine last year, by passing on experience acquired to the younger Federations of those countries that come knocking at the European Union's door, and by creating ties with the Chinese, American or Japanese Federations,

the invitation from the Netherlands to host the $ 52 ^{ \mathrm{nd}} $ General Assembly on 10 May 2002.

CECIP's Slovak friends made a perfect job of organizing this General Assembly in the marvelous surroundings of the Town Hall, Primate's Palace and Mirror Hall in the heart of the historic district of Bratislava where Delegates were able to roam pleasantly in the sun. The day's work was followed by a visit of the Castle which dominates the town and a cruise up the Danube before ending the day in a typical hostel on the river banks. A big "Thank you" to CECIP's Slovak hosts, and see you next year in the Netherlands!

![](page=29,bbox=[548, 1906, 1344, 2278])

OIML MEETING

Berlin, 22 June 2001

BIML

The accuracy class II will be canceled. The error limits of class I will be interpreted in a statistical way, because these errors are not systematic but are of a statistical nature.

Over the past two years, preparatory activity under the leadership of the TC17/SC1 Secretariat (China) included conducting inquiries and sending out questionnaires on the revisions of OIMLR59, R92 and R121, and also on the scope of future activities.

The first Subcommittee meeting was convened and hosted by the PTB (Berlin) on behalf of the Chinese Secretariat on 22 June 2001; the discussion topic was the scheduled revision of R 59 Moisture meters for cereal grain and oilseeds, as the priority project of OIML TC 17/SC 1.

Ten delegates from six P-Members (China, France, Germany, Poland, UK and the USA), one O-Member (Japan) and the BIML attended the meeting, chaired by Dr. G. Scholz (PTB).

Early in the meeting and following brief discussions, the participants agreed that OIML R 59 required substantial revision to reflect new measuring technologies and aspects of actual grain analysis. This was in line with written comments which had been received prior to the meeting, therefore it was decided to hold a general discussion about the aims and scope of this Recommendation as well as about specific topics such as error limits, calibrations and others. Agreement was reached on the following points:

The participants agreed that when considering moisture meters, a distinction shall be made between the meter itself as a physical instrument and the calibrations for different kinds of grain as mathematical models realized in the form of software (or scales or tables for older types of instruments).

Because grain moisture measurements are made for different purposes, it must be clearly stated that this Recommendation applies to measurements in the sphere of legal metrology only, i.e. for commercial transactions.

The Recommendation shall specify that measurements for commercial transactions may only be applied to static samples, i.e. not to continuous flows of grain.

The differentiation between categories A and B shall be eliminated, since this distinction does not improve the Recommendation from a legal metrology point of view.

The Recommendation shall be limited to indirect measuring instruments based on physical methods. It will not be applied to drying methods. The question was left open as to whether drying methods based on infrared or microwave drying should be taken into account.

The Recommendation shall:

- define a minimum sample mass;

- establish rules and fix minimum numbers of samples for the validation of calibrations; and

- provide an interpretation of uncertainty of moisture measurement.

An "initial verification" does not make sense because of the peculiarities of grain moisture measurement, therefore it shall be deleted.

The BIML is requested to contact ISO (TC 34/SC 4) and ICC in order to establish liaisons, for cooperation and exchange of information.

The Recommendation will refer to the importance of the problem of sampling, but will not cover it.

Reference methods will not be covered by the Recommendation.

A new version of the Recommendation will be drafted by a Working Group comprising experts from China, France, Germany, Poland and the USA.

The USA (NIST) will prepare a new version of the first draft revision of R 59.

## WELMEC WG8 Meeting Prague, 19-20 April 2001

GÉRARD LAGAUTERIE, CIML Member - France

Welcome and opening by Mr. Pavel Klenovský, CMI Director

Adoption of the Agenda

Report on the last meeting by Messrs. Lagauterie and Freistetter

A report concerning WG8 activity was distributed to WELMEC Committee members

The outcome of the last meeting on the MID was very useful for Council discussions

Mr. Freistetter reiterated the remaining issues to be discussed concerning Annex I: direct sales, and marking.

## Report on Council work by Mr. Nyström

- Discussions about sub assemblies were quite close to conclusion

The main articles of the Directive and Annex I had been discussed; no major problems had been encountered so far

Cooperation with the Commission was good, though there was no chance of finishing the work under the Swedish presidency

- Contacts with the Parliament rapporteur (questions about reference to the OIML) and with the Social and Economical Council were not posing any particular problems.

## Comments by Mr. Hanekuyk

The political view was that the MID work was too slow and too complicated.

## Sub assemblies

- At the last meeting it had been decided that only utility meters would be concerned. The available proposals were an official German proposal, one

from Mr. Baksteen, another from Mr. Toggweiler and also one from Mr. Lagauterie (based on the German and Mr. Baksteen's proposals). Mr. Toggweiler explained that there was no need for specific provisions, but the group did not agree. Mr. Lagauterie considered that the German proposal clarified the situation but that the aspect of compatibility of elements needed to be dealt with in more depth. In his view, criteria for compatibility must be declared by the manufacturer, checked by the notified bodies and clearly made available to the installers. No conclusions were agreed on and discussion remains open.

## Annex II

After discussions at the Paris meeting it had been confirmed that this Annex was not mandatory. France would propose some changes.

## Examination of instrument-specific Annexes MI-001 to MI-009 and MI-011

Each person responsible for a subgroup in charge of a specific Annex gave a short presentation of the work carried out (participants comments received, open questions, divergences with OIML if any).

The floor was then opened up for reactions and further comments. After discussion the respective results for each of these Annexes were as below.

## MI-001 (Water meters)

The concept of "non-negotiated" transactions is maintained but a more appropriate wording is to be found (Note: this is valid for all Annexes in which the same term is relevant)

The adjective "clean" would be maintained

The suggestion to add 1 % and 3 % in 6/7 was withdrawn since "non-negotiated" was maintained

Definition of Q3 and Q4: the Commission draft was maintained

No specific requirement on external power supply as it already existed in Annex I

Modifications in 3,4,8.1.4 accepted

- Proposed modifications in 8.1.2, 8.1.3 not accepted.

The draft would be modified according to the conclusions of WG8 and submitted to WG8 members for validation. Better wording for "non-negotiated" would be the subject of further discussion.

## MI-002 (Gas meters)

Proposal to replace B + F by B + E rejected

No further discussion on list of assessment procedure: this matter would be discussed at a general level, together with the content of some assessment procedures and in particular about conformity to type

The proposal to introduce class 0.5 % was no longer necessary since the "non-negotiated" concept was maintained (see MI-001)

- Definition: it was decided to replace "quantity" by "volume and/or mass"

- Following the introduction of mass the whole text would be reviewed accordingly

- Energy measurement not included for the time being

- New 7.2.1 and 7.3 to be reconsidered for improvement

- Durability: subgroup may continue to work on a proposal better adapted to electronic utility meters.

## MI-003 (Electricity meters)

- WG8 accepted the proposal to delete transformers

- Only class 1 and 2 were dealt with in the Annex; the introduction of a statement similar to "non negotiated" (see MI-001) could allow Member States to regulate other classes but no clear decision yet on this point

- WG8 agreed that the subgroup could prepare a new draft with less detailed essential requirements concerning EMC

Table 2 to be re-examined.

## MI-004 (Heat meters)

- Comments concerning the applicability of H1 to be discussed at general level (Council or other WG8 meeting)

- All references to standards to be deleted or corresponding provisions to be included clearly bearing in mind the spirit of the "New Approach"

- Significant faults (critical charge values) to be defined for subassemblies

A version presenting both the Commission version and the new proposed version was requested.

MI-005 (Measuring systems for liquids other than water)

8. 1, 8.2 Commission text maintained

- LPG extended to liquefied gases for fuel dispensers

- Editorial: "full charged" instead of "surcharged".

## MI-006 (Automatic weighing instruments)

An alternative proposal was distributed by the PTB together with the subgroup's proposal and an overview of comments

The Chair mentioned that in several letters CECIP and especially AWA had expressed their concern that the draft needed to be further discussed

The person responsible for the subgroup then proposed to work on a new proposal taking into account further comments. He also envisaged an alternative draft with much fewer requirements. Several delegations expressed their agreement with the current proposal and could accept some amendments going in the direction proposed by the PTB but would have reservations concerning a totally different Annex

The subgroup was asked to prepare a new proposal by August.

## MI-007 (Taxi meters)

The paper giving the background to the necessary modifications was commented by Mr. Baksteen; several members expressed their satisfaction and thanked Mr. Baksteen for the excellent job done

- Some members nevertheless needed to check the new draft in detail with their national partners involved in the field of taximeters

- Some editorial modifications were identified but in principle the new proposal for Annex MI-007 was accepted.

## MI-008 (Material measures)

Industry expressed their difficulties concerning the declaration of conformity to accompany each measure of length. It was stressed that this declaration is the way in which the manufacturer takes responsibility. It seemed that it was not possible to diverge in a specific Annex from a requirement concerning the declaration of conformity which is part of the Annexes

about the assessment procedure; other solutions should be found and industry should submit the problem to the Commission and the Council Presidency

- According to the person responsible for this Annex the new definition would exclude dipping measures for tanks. France and the Netherlands expressed the fact that they could have a problem with the exclusion of these measures from the scope

The proposal included the deletion of some assessment procedures. This could not be discussed in WG8 and should be discussed at Council level.

## MI-009 (Dimensional measuring instruments)

The draft included some degree of non conformity with OIML Recommendations. It was concluded that the draft would have to be coherent with the OIML or the differences would have to be justified. The person responsible for the subgroup would contact other members and try to solve the problem.

## MI-011 (Exhaust gas analyzers)

The draft was generally well accepted

- One sentence concerning a test had been deleted as it was not in line with the "New Approach"

- Sweden still needed to examine the draft with national experts

The Netherlands expressed their political problem with the inclusion of this category in the MID.

Special case of MI-010 (Evidential breath analyzers)

- Five countries expressed their national difficulties with the inclusion of this category in the MID. This Annex was not discussed in WG8. Political aspects will be discussed at Council level.

## Future work

- Finalization of specific Annexes

If possible, discussion on Annexes concerning assessment procedures.

Thanks were expressed to CMI for their hospitality and a list of participants was distributed during the meeting.

## WELMEC contact information

Secretary: Lindsay Crawford

E-mail: welmec@nwml.dti.gov.uk

Web site: www.welmec.org

ROAD TRANSPORT

<div align="center">

# Southeast European Cooperative Initiative (SECI) Regional Road Transport Committee

</div>

Istanbul (Turkey), 11-12 June 2001

IAN DUNMILL, BIML

Background

The SECI Regional Road Transport Committee (RRTC) was created to implement the Memorandum of Understanding (MoU) on the Facilitation of International Road Transport of Goods in the SECI region, which was signed in Athens in 1999. The RRTC is composed of representatives of competent authorities of eleven SECI participating States. The Federal Republic of Yugoslavia, which has recently succeeded to most UNECE Transport Agreements and Conventions, has transmitted to the UNECE Secretariat a formal request to become a Party to the MoU.

## Fourth Session

The fourth session of the RRTC was co-chaired by Mrs. Umit Armangil, Ministry of Transport, Turkey, and Mr. Martin Magold, UNECE. It was attended by delegates from Albania, Bosnia and Herzegovina, Bulgaria, Croatia, Greece, Hungary, the Former Yugoslav Republic of Macedonia, Romania and Turkey. A representative of the Federal Republic of Yugoslavia attended as an observer. Representatives of the USA (a SECI supporting State), the Black Sea Economic Cooperation (BSEC), the European Conference of Ministers of Transport (ECMT) and the OIML also attended the meeting.

The Committee has now achieved concrete results in the following areas:

lorries complying with the relevant regulations of the European Community on maximum dimensions and weights are allowed without requiring payment of charges for excess weights and dimensions. The objective is to provide transparency to the transport industry about payment of these charges;

- the identification of roads servicing international traffic (E-Roads) on which international transport

- the preparation of an International Vehicle Weight Certificate aimed at avoiding repetitive weighing of goods road vehicles at each border crossing point (see below). It is planned to include this certificate also into a new Annex 8 to the UNECE Convention on the Harmonization of Frontier Controls of Goods (1985);

- the progressive liberalization and sustainability of international road transport. The Committee has adopted a Joint Statement which provides for the inclusion in existing and new bilateral agreements of a provision allowing for quota-free bilateral and transit road transport to/through their territory for "green" and "greener and safe" lorries (in accordance with ECMT definitions), registered in any of the Parties to the MoU. This should lead to a gradual establishment of free market access for international road transport in the sub-region;

- the maintenance of an International Road Transport Information System containing detailed information on permissible road vehicle weights and dimensions, transportation costs, combined transport services, road transport control and enforcement agencies in the region etc., to facilitate planning of the road transport industry;

- a survey of accession by SECI participating States to the UNECE International Road Transport Agreements;

- a review and study of possibilities for gradual convergence of charging policies for international road transport of goods in SECI participating States as well as for the adoption of relevant European Union standards and ECMT resolutions;

- a review of visa facilitation procedures for professional drivers and promotion of best existing practices.

## International Vehicle Weight Certificate

At its third session, the RRTC had approved in principle a Protocol to the MoU introducing an International Vehicle Weight Certificate (IVWC). This is intended to avoid the current practice of weighing road transport vehicles at every border crossing when they are in transit across the region.

The OIML had been invited to participate in the RRTC to provide independent expertise in the field of road transport vehicle weighing. Ian Dunmill (BIML) briefed the participants on the OIML and the relevant International Recommendations and Draft Recommendations for static and dynamic weighing, as well as providing technical input to the discussions. During this session, the IVWC was adopted in principle, and participants were invited to consult with competent

national authorities on the introduction of the IVWC and in particular to identify, all legal, technical and administrative provisions and procedures that may be affected at the national level by the application of the IVWC. It is proposed to consider the results of these consultations at the next session in October 2001, at which stage the Protocol and its annexed IVWC will be formally adopted and will come into force three months later.

![](page=5,bbox=[749, 813, 1144, 1127])

COMPTE RENDU

EMLMF

<div align="center">

# Réunion des 28-29 juin 2001

</div>

NICOLE RENARD,

Sous-Direction de la Métrologie, France

La troisième réunion du Forum Euro-Mediterranéen de Métrologie Légale (EMLMF) s'est tenue les 28 et 29 juin 2001 à l'Hôtel Aquatis à Poitiers (France); entre temps, un séminaire avait eu lieu à Paris (voir ci-dessous).

## Ouverture

Mme Annabi et M. Lagauterie souhaitent la bienvenue aux participants, qui se présentent et adoptent l'ordre du jour.

## Rapport sur le séminaire tenu à Paris les 30 novembre et 1 $ ^{er} $ décembre 2000

M. Magaña et Mme Annabi expliquent que le but de ce séminaire, organisé par le Ministère Français de l'Industrie sous le patronage de l'OMC, de l'OIML et de l'ONUDI, était de montrer la cohérence et l'importance de la métrologie; le compte rendu sera disponible sur le site Internet de l'EMLMF et les actes seront publiés dans les langues d'intervention.

## État d'avancement des groupes de travail

Les groupes de travail sont formés de personnes en provenance du nord et du sud de la Mediterranée. Les résumés suivants sont donnés:

## I) Formation (M. Wallerus)

- Décision de fusionner le groupe Formation avec le groupe Assistance Technique

- Présentation du dernier projet de questionnaire, sur lequel il est demandé d'ajouter la langue utilisée pour la formation. La version corrigée ne sera pas rediscutée, et M. Wallerus l'enverra par e-mail aux membres du forum pour validation. Il sera disponible sur le site www.dam-germany.de.

- Mme Annabi souhaiterait un catalogue proposant les différentes formations en métrologie légale, mais M. Magaña précise que sur le site Internet du Conseil de Développement de l'OIML, il y a déjà une offre (non exhaustive) de formation.

- Il est prévu un séminaire régional sur la formation, en Tunisie, en octobre ou novembre 2001, mais le groupe Formation ne tiendra pas d'autres réunions.

- II) Reconnaissance des approbations de modele (M. Yahyaoui)

- Décision de fusionner ce groupe avec le groupe Information Mutuelle.

- Le projet de reconnaissance a été initié par M. Lamoumri et repris par son successeur, M. Yahyaoui. M. Magaña recommande une plus grande collaboration avec M. Birdseye et demande d'ajouter dans le répertoire, le nom du correspondant de l'organisme pour les différentes catégories. Un document fourni par M. Ben Hassine est distribué en séance et commenté.

- M. Eggermont souligne que toutes les réglementations vont être modifiées à très court terme. Il en est de même pour la liste des laboratoires qui devront être notifiés. Il conseille que la notion de conformité lors des approbations de modèle soit étendue à la notion de conformité lors de la vérification primitive.

- OIML TC 3/SC 5 travaille sur des reconnaissances mutuelles basées sur les certificats OIML. M. Magaña propose de préparer une liste des approbations délivrées et la mettre sur le site de l'EMLMF. Pour le futur, il faudra suivre les travaux de l'OIML (Mme Annabi les suit au sein du Conseil de Développement).

- M. Lagauterie fait remarquer que gérer les listes d'approbation de modèle peut être lourd pour ce qui concerne les décisions anciennes.

- En conclusion, il est suggéré de favoriser le développement du répertoire des organismes de délivrance d'approbations de modèles, en indiquant le nom des experts concernés, de façon à ce que les pays souhaitant reconnaître des approbations de modèle aient un contact aisé avec l'autorité ayant prononcé l'approbation.

- le questionnaire proposé par M. Magaña est validé, moyennant certaines observations mineures.

## Étude du projet de "Protocole d'accord"

Le projet a été amendé en séance. Après modification par la Sous-Direction de la Métrologie, le texte français amendé sera envoyé aux participants pour être validé. Après validation, le protocole sera soumis à la signature des responsables de métrologie légale de tous les pays susceptibles d'être membres de l'EMLMF, avec pour but d'accomplir cette tâche avant la prochaine réunion. L'existence de l'EMLMF deviendra alors officielle après la signature du protocole d'accord, ce qui n'empêche pas que le Forum s'est réuni à trois reprises de manière informelle, comme l'a précisé Mme Annabi.

## Rapport des organisations en liaison

Pour l'OIML, M. Dunmill présente un rapport sur les points suivants:

- Activités des comités techniques et publications;

- Révision du document D 1 Loi sur la métrologie;

- Accord pour l'acceptation mutuelle (MAA);

- Pré-emballages;

- Rôle des RLMO;

- Documents horizontaux; et

- Organisation d'un atelier sur l'évolution à long terme de la métrologie légale.

MM. Birdseye et Lagauterie présentent aussi les derniers développements au sein de WELMEC (Voir article dans ce Bulletin sur la réunion du WG8).

Il est souhaité une collaboration fructueuse de I'EMLMF avec I'OIML, ainsi qu'avec d'autres organisations régionales.

## Questions diverses

- M. Seiler: Projet de la Commission Européenne sur la formation et la coopération. M. Trombone insiste sur la nécessité de trouver des moyens financiers pour organiser les réunions de l'EMLMF, pour organiser les formations et les coopérations et se propose de contacter la Commission Européenne pour étudier les financements possibles. L'organisme porteur doit avoir une entité juridique et donc ne peut être l'EMLMF; des contacts seront pris avec l'OIML. Mme Annabi propose de contacter la Banque Mondiale.

- M. Frenn: Nouvelle Loi sur la Métrologie: dans certains pays il y a des difficultés pour disposer des infrastructures étatiques pour s'occuper de la métrologie. M. Lagauterie précise que le projet OIML D1 devra tenir compte des moyens modernes applicables à la métrologie (recours aux organismes privés, approbation des systèmes d'assurance de la qualité des fabricants) et prévoira la délégation de certaines activités à des organismes privés, ce qui diminuera le besoin en équipement des administrations.

Des remerciements ont été exprimés à toute l'équipe de la Sous-Direction de la Métrologie ainsi qu'aux participants et il a été rappelé l'adresse du site Internet de l'EMLMF: www.industrie.gouv.fr/metro puis "euroméditerranée" puis "membres". Les mots de passe peuvent être communiqués sur simple demande par courrier électronique à Mme Annabi ou Mme Renard.

Il est proposé que la prochaine réunion se tienne en Belgique (à confirmer), durant la dernière semaine de juin 2002.

## ACCOUNT

## EMLMF

<div align="center">

# Meeting held 28-29 June 2001

</div>

NICOLE RENARD,

Sous-Direction de la Métrologie, France

The third meeting of the Euro-Mediterranean Legal Metrology Forum (EMLMF) was held on 28 and 29 June 2001 at the Aquatis Hotel in Poitiers (France). Since the last meeting a Seminar had been held in Paris (see below).

## Opening

Mrs. Annabi and Mr. Lagauterie welcomed the participants, who introduced themselves and adopted the Agenda.

## Report on the Seminar held in Paris on 30 November and 1 December 2000

Mr. Magaña and Mrs. Annabi explained that the objective of this Seminar, organized by the French Ministry for Industry under the patronage of the WTO, the OIML and UNIDO was to demonstrate the coherence and the importance of metrology; the account will be made available on the EMLMF web site and the speeches will be published in their original languages.

## State of progress of the work groups

The work groups are made up of people from both north and south of the Mediterranean. The following summary reports were given:

## I) Training (Mr. Wallerus)

- Decision to merge the Training group with the Technical Assistance group.

- Presentation of the latest draft questionnaire, on which it was requested that the language used in the training should be added. The corrected version would not be discussed again, and Mr. Wallerus will e-mail it to Forum members for validation. It will be available at www.dam-germany.de.

- Mrs. Annabi would appreciate a catalog giving the various legal metrology training courses, but Mr. Magaña pointed out that on the OIML Development Council web site there is already a (non-exhaustive) listing of courses.

- It is envisaged to hold a regional training seminar in Tunisia in October or November 2001, but the Training group will not be holding any further meetings.

## II) Recognition of type approvals (Mr. Yahyaoui)

- Decision to merge this group with the Mutual Information group.

- The recognition project had been initiated by Mr. Lamoumri and was taken over by his successor Mr. Yahyaoui. Mr. Magaña recommended closer cooperation with Mr. Birdseye and asked that the organization contact person be added to the directory for the various categories. A document supplied by Mr. Ben Hassine was distributed and commented on.

- Mr. Eggermont underlined the fact that all the regulations were going to be modified in the short term. This was also the case for the list of laboratories which will have to be notified. He advised that the notion of conformity in pattern approvals should be extended to the notion of conformity in initial verification.

- OIML TC 3/SC 5 is working on mutual recognitions based on OIML certificates. Mr. Magaña suggested drawing up a list of approvals granted and putting this on the EMLMF web site. In the future OIML work should be followed more closely (Mrs. Annabi follows it for the Development Council).

- Mr. Lagauterie pointed out that managing type approval lists can be heavy going as far as older decisions are concerned.

- As a conclusion, it was suggested that the development of a directory of pattern approval bodies should be encouraged, including the name of the experts concerned, so that countries wishing to recognize pattern approvals may easily enter into contact with the Authority that gave the approval.

- The questionnaire put forward by Mr. Magaña was validated, with certain minor observations.

## Study of the draft MoU

The draft was amended during the meeting. After being modified by the Sous-Direction de la Métrologie the amended French text will be sent to participants for validation, following which the protocol will be submitted for signature by those in charge of legal metrology in all those countries that might become EMLMF members, the objective being to get this done by the time of the next meeting. The existence of the EMLMF would then become official after the MoU is signed - though this has not prevented the Forum from meeting informally on three occasions, as Mrs. Annabi pointed out.

## Report on organizations in liaison

For the OIML, Mr. Dunmill gave a report on the following points:

- TC activities and publications;

- Revision of Document D 1 Law on metrology;

- Mutual acceptance arrangement (MAA);

- Prepackages;

- Role of RLMOs;

- Horizontal documents; and

- The organization of a workshop on the long-term evolution of legal metrology.

Mr. Birdseye and Mr. Lagauterie also presented the latest developments within WELMEC (see article in this Bulletin on the WG8 meeting).

It was hoped that cooperation between the EMLMF and the OIML, as well as with the other regional organizations, would be fruitful.

## Other points

- Mr. Seiler: European Commission draft on training and cooperation. Mr. Trombone insisted on the need to find the financial means to organize EMLMF meetings, to organize training and cooperation projects and volunteered to contact the European Commission to ascertain funding possibilities. The applying body must have a juridical status and cannot therefore be the EMLMF; contacts will be established with the OIML. Mrs. Annabi volunteered to contact the World Bank.

- Mr. Frenn: New Law on Metrology: in certain countries there are difficulties in making national structures available to deal with metrology. Mr. Lagauterie pointed out that the OIML D1 draft will have to take into account modern metrology methods (having recourse to private bodies, manufacturers' quality assurance systems approval) and makes provision for certain activities to be delegated to private bodies, which will reduce administrations' equipment needs.

Thanks were expressed to the Sous-Direction de la Métrologie staff and to the participants, who were reminded of the EMLMF web site address: www.industrie.gouv.fr/metro then "Euro-Mediterranean" then "members". Passwords can be requested by e-mail from Mrs. Annabi or Mrs Renard.

It is proposed to hold the next meeting in Belgium (to be confirmed) during the last week of June 2002.

<div align="center">

# The First Middle East Metrology Conference and Exhibition

</div>

The Ministry of Commerce & Industry - Directorate of Standards and Consumer Protection is organizing the First Middle East Metrology Conference and Exhibition from 6th to 8th May 2002 at the Gulf International Convention Centre, Gulf Hotel, Bahrain.

The event will be held under the patronage of HE Ali Bin Saleh Al Saleh and the Conference Chairman is Mr. Ahmed Isa Bubshait, Assistant Undersecretary for Standards & Consumer Protection, Ministry of Commerce & Industry.

The Ministry of Commerce & Industry has decided to organize this event because there is a crucial need to provide up-to-date information on international metrology and standardization of measurements to the ME commerce, industry and science in preparation for an anticipated strong wave of industrial development in the coming years in the entire Middle East region.

Metrology is the uniform methodology for measurements in natural science and provides the universally accepted norms and standardized rules and regulations for measurement in industry, science, technology and trade.

In simple terms, the manufacturing and trading in goods needs exact and uniform measurements in respect of quantity and quality of raw materials, components, ingredients and production processes which must be universally accepted as the norms and standards for the global exchange of goods and services and form the fundamental basis

## Main Conference topics:

Analytical Measurements

Dimensional Measurements

Data Processing and Telemetry

Environmental & Safety Measurement

Medical Measurements

Precision Engineering

Process Measurements

Legal Metrology

www.mohandis.org

for equal and fair trade and easy exchange of information and technology.

Metrology has probably started with the measurement of time, weight and speed - basic matters that humankind was confronted with from the early days.

Today, metrology is a very complex and truly interdisciplinary science across all human activities and affects everybody's daily life. With high-tech analytical and laboratory equipment combined with high-speed data processing it has become a fast changing discipline that needs constant updating of expertise and application.

The main objective of the First Middle East Metrology Conference & Exhibition is to promote harmonization and standardization in industrial and scientific measurements in the Middle East and to create an annual platform for personal contacts amongst the metrology professionals from the region.

Easy access and a modern business infrastructure provide the right environment for this event to promote Bahrain as the information and services center for the Metrology in Middle East.

The conference will be the ideal forum to promote and foster better understanding and close relationship between government agencies, relevant authorities, science, the industry and the public and will provide better understanding of general metrology and advanced techniques in applied measurement and standardization.

It is expected that about 300 experts especially from Laboratories and Quality Control (QC) in the Oil, Gas and Energy Sector, Petro-Chemical Industry, Aerospace, Medical and the various Sectors of the Manufacturing Industry as well as experts from Governments and Universities will attend the conference, where about 30 acknowledged expert speakers from the Middle East and from leading economies around the world are expected to present their findings and

![](page=9,bbox=[1306, 595, 1649, 933])

papers at specialized sessions during the three conference days.

A call for papers will be sent out to a database of almost 1000 experts from Governments, Universities, Industry and Commerce and the detailed conference program and the individual subjects and list of expert speakers will be available in September 2001.

During the exhibition, about 30 exhibitors are anticipated to provide a window on the latest laboratory measurement and testing equipment as well as services such as equipment calibration, product and process certification, technical assistance and general metrology information.

This highly specialized conference and exhibition must be seen as a valuable investment into future corporate and national development and will therefore be sponsored by the local and regional industry and by the Ministry of Commerce and Industry.

As Chairman of the Organizing Committee, Mr. Ahmed A. Al Shamlan, General Manager of the Bahrain International Exhibition Centre is responsible for the event coordination whilst the Conference Secretariat is at the office of The Bahrain Society of Engineers, where Mr. A. Majeed Al Gassab as the Chairman of the Technical Committee is responsible for the entire technical organization. Invaluable expertise and professional support will be provided by Col. Sameer A. Al Zayani from the Bahrain Defense Force and by Dr. Ebrahim Mohamed from the University of Bahrain.

The OIML is pleased to welcome the following new

CIML Member

Japan:

Dr. Mitsuru Tanaka

## OIML Meeting

November 2001

7-9 TC 9/SC2 Automatic weighing instruments

TEDDINGTON UK

## Committee Drafts

received by the BIML, 2001.05.01-2001.07.31

<table border="1"><tr><td>Pressure transmitters with elastic sensing elements</td><td>E</td><td>1CD</td><td>TC10/SC2</td><td>Russian Federation</td></tr><tr><td>Light absorption spectrometers for medical laboratories</td><td>E</td><td>2CD</td><td>TC18/SC5</td><td>Germany</td></tr><tr><td>Revision ofR33:Conventional value of the result of weighing in air</td><td>E</td><td>1CD</td><td>TC9/SC3</td><td>USA</td></tr></table>

## www.oiml.org

Stay informed

the January 2002 issue of the OIML Bulletin: Read a full account of the September OIML Meetings in Moscow

![](page=10,bbox=[1011, 1959, 1821, 2516])