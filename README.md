java c
Research School of Finance, Actuarial Studies and Statistics  
Test 1 - Practice Paper C 
STAT3016/6016 - Introduction to Bayesian Data Analysis 
Problem 1 [8 marks]The   Poisson-Gamma   distribution   is   sometimes   used   as   the   sampling   model   assumption   for   observed   count   data that   shows   more   dispersion than predicted under   a   Poisson   model. Consider the   data   model  PoissonGamma(a, b) (i = 1, ..., n). The probability density function of the Poisson-Gamma distribution   is
where   a   > 0   and   b   >   0
Suppose that the parameters   (a,   b) are assigned the joint non-informative prior   distribution   proportional   to   1/(ab)2   .(a)    [1 mark] Is   the   joint   non-informative   prior   distribution   p(a,   b)   /   1/(ab)2                                                                                                                                                                                                                     a
proper   or   improper   prior   distribution? Give   a   reason   for   your   answer.
(b)    [1 mark] Suppose we consider transforming the parameters by taking the natural logarithm of a and   b   respectively. Deﬁne   θ   1    =   loge   a   and   θ2    =   loge   b. Suggest   one   reason   why   such   a   transformation   might   be   of interest.
(c)    [2   marks]   Derive   the   prior   density   in   terms   of   (θ1   ,   θ2). That   is,   ﬁndp(θ1   ,   θ2).    [Hint: you   will   need to   apply   the   method   of transformations   technique   for   a   bivariate   density   to   derive   the joint   prior   density   of the   transformed   parameters]
(d)    [2 marks]   Derive the joint posterior   distribution p(θ1   ,   θ2 jy1, ...,   yn) up   to   a   proportionality   constant   (that   is,   ignoring   any   normalising   constant).
(e)    [1   mark]   The   joint   posterior   density   in   part (d)   is   not   a   standard   density   that   can   be   sampled   directly   from. What   approximation   approach   could   you   use   to   obtain 1000   posterior   draws   of   (θ1   , θ2   )?         (Note,   you   only   need   to   provide   the   name   of   the   approximation   method,   not   describe   how   you   would   implement   it)
(f)    [1    mark]   Suppose   you   have   generated 1000   posterior   draws   of   (θ1   ,   θ2)   from   the   target   posterior de代 写STAT3016/6016 - Introduction to Bayesian Data Analysis Test 1 - Practice Paper CMatlab
代做程序编程语言nsity   derived   in   part   (d).   Describe   how you would   use the   simulated   posterior   sample to   obtain   90%   interval   estimates   for   the   parameters   a   and   b.
Problem 2 [7 marks] In the recent literature, the   Poisson distribution   has   been   used   to   model   COVID-19   death   counts.    Valid   estimation   of   the   death   rate   relies   on   the   availability   of   accurate   data   on   COVID-19   death   counts.    In   some   regions   in   the   world,   the   accuracy   of   reported   COVID-19   death   counts   is   questionable. We   are   going to build a Bayesian model   to   estimate   the   death   rate   parameter   due   to   COVID-19   using   a   Poisson   sampling   model   but   also   allow   for   possible   under-reporting   of death   counts.Let   y1, ...,   yn      be   the   reported   daily   death   counts   for   Region   A   for   n   diferent   days. Let z1   , ...,   zn      be   the   true   (unreported)   death   counts,   the   sampling   model   assumption   is  Pois(λ). (Note, in this question   we   assume   there   is   no   over-reporting   of death   counts, just   under-reporting   so   yi ≤ zi.)
(a)    [2   marks]   Assume   yi      =   zi         (i   =   1, ...,   n).    So   there   is   no   under-reporting   of   death   counts. Deﬁne   a prior   distribution   for   λ   and   derive   the   posterior   distribution   of   λ   with   your   chosen   prior.    (Note,   you   do   not   need   to   provide   speciﬁc   hyperparameter   values   in   your   chosen   prior   assumption).
(b)    [3   marks]   Now   we   want   to   adjust   our   model   for   the   possibility   of   under-reporting. The   true   rate   of under-reporting is not known   but   it   is   assumed that   the   reported   death   count   yi    is   at   least   80%   of the   true   death   count   zi    (for   i =   1, ...,   n).    That   is,   the   under-reporting   rate   is   at   most   20%.
Give   the   posterior   distribution   of   λ   up   to   a   proportionality   constant      (that   is,   ignoring   any   nor-   malising   constant),   under   this   revised   model
(c)    [2    marks]    Describe   in   words   how   we   could   use   the   posterior   distribution   in    (b)   to    predict   the   unobserved   true   death   counts   zi.









         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
