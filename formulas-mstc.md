# MSTC Formula Reference

Mathematics, Statistics, Physics, Surveying, Transportation, and Construction

This reference collects standard relationships for review and preliminary calculations. It is not a substitute for the project specifications, current agency manuals, a code, or a stated examination convention. Keep units consistent, retain signs and significant figures until the final result, and identify whether an answer is exact, approximate, nominal, or code-controlled.

## 1. Calculus and mathematical foundations

### Algebra, geometry, and trigonometry

For a right triangle with legs \(a,b\), hypotenuse \(c\), and acute angle \(\theta\),
\[
c^2=a^2+b^2,\qquad \sin\theta=\frac{\text{opposite}}{c},\quad \cos\theta=\frac{\text{adjacent}}{c},\quad \tan\theta=\frac{\text{opposite}}{\text{adjacent}}.
\]

For any triangle with sides \(a,b,c\) opposite angles \(A,B,C\),
\[
\frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C},\qquad c^2=a^2+b^2-2ab\cos C,
\]

and its area is \(K=\tfrac12 ab\sin C\). Angles in calculus and differential equations are normally in radians.

For a circle of radius \(r\), circumference \(2\pi r\), area \(\pi r^2\); for a cylinder, \(V=\pi r^2h\); for a cone, \(V=\tfrac13\pi r^2h\); for a sphere, \(V=\tfrac43\pi r^3\) and surface area \(4\pi r^2\). For a circular sector of central angle \(\theta\) in radians, arc length is \(s=r\theta\) and area is \(A=\tfrac12r^2\theta\).

### Limits, derivatives, and differentials

The derivative is the instantaneous rate of change:
\[
f'(x)=\lim_{h\to0}\frac{f(x+h)-f(x)}{h}.
\]

Useful rules, for differentiable functions and constants \(c,n\):
\[
\frac{d}{dx}x^n=nx^{n-1},\quad \frac{d}{dx}e^x=e^x,\quad \frac{d}{dx}\ln x=\frac1x,\quad \frac{d}{dx}\sin x=\cos x,\quad \frac{d}{dx}\cos x=-\sin x.
\]
\[
(uv)'=u'v+uv',\qquad \left(\frac uv\right)'=\frac{u'v-uv'}{v^2},\qquad \frac{d}{dx}f(g(x))=f'(g(x))g'(x).
\]

Implicit differentiation treats \(y\) as a function of \(x\). For differentials, a small change satisfies \(dy\approx f'(x)\,dx\); this is a local linear approximation, not generally an exact finite change.

For a function \(y=f(x)\), a stationary point has \(f'(x)=0\) or an undefined derivative. If \(f''(x)>0\) there is a local minimum; if \(f''(x)<0\), a local maximum, subject to the usual differentiability conditions. For two variables, stationary points solve \(f_x=f_y=0\); classify using \(D=f_{xx}f_{yy}-f_{xy}^2\): \(D>0,f_{xx}>0\) minimum; \(D>0,f_{xx}<0\) maximum; \(D<0\) saddle.

### Integration and applications

An antiderivative \(F\) of \(f\) satisfies \(F'=f\). The definite integral gives signed accumulated change:
\[
\int_a^b f(x)\,dx=F(b)-F(a).
\]
\[
\int x^n\,dx=\frac{x^{n+1}}{n+1}+C\ (n\ne-1),\quad \int\frac{dx}{x}=\ln|x|+C,\quad \int e^{ax}\,dx=\frac{e^{ax}}a+C.
\]
\[
\int\sin(ax)\,dx=-\frac{\cos(ax)}a+C,\qquad \int\cos(ax)\,dx=\frac{\sin(ax)}a+C.
\]

Substitution uses \(u=g(x)\), \(du=g'(x)dx\). Integration by parts is
\[
\int u\,dv=uv-\int v\,du.
\]

If (v(t)) is velocity, displacement from \(t_1\) to \(t_2\) is \(\int_{t_1}^{t_2}v(t)dt\); distance traveled is \(\int|v(t)|dt\). If (Q(x)) is a cross-sectional area along a length, volume is \(V=\int Q(x)dx\). The average value of \(f\) over ([a,b]) is \(f_{avg}=\frac1{b-a}\int_a^b f(x)dx\).

For a planar region between \(y=f(x)\) and \(y=g(x)\), area is \(A=\int_a^b[f(x)-g(x)]dx\) when \(f\ge g\). The centroid of a uniform thin area has \(\bar x=A^{-1}\int x\,dA\), \(\bar y=A^{-1}\int y\,dA\).

### Taylor approximation and series

Near \(x=a\),
\[
f(x)\approx f(a)+f'(a)(x-a)+\frac{f''(a)}{2!}(x-a)^2+\cdots.
\]

The first-order approximation is useful for small changes; omitted higher-order terms cause truncation error. Common series (convergent on their stated domains):
\[
e^x=\sum_{n=0}^{\infty}\frac{x^n}{n!},\quad \sin x=\sum_{n=0}^{\infty}\frac{(-1)^n x^{2n+1}}{(2n+1)!},\quad \cos x=\sum_{n=0}^{\infty}\frac{(-1)^n x^{2n}}{(2n)!}.
\]

## 2. Differential equations

An ordinary differential equation \(ODE\) relates an unknown function of one independent variable to its derivatives. The order is the highest derivative. An initial-value problem \(IVP\) gives conditions at one point; a boundary-value problem gives conditions at different points.

### First-order equations

**Separable:** If \(dy/dx=g(x)h(y)\), then
\[
\int\frac{dy}{h(y)}=\int g(x)\,dx+C,
\]

on intervals where division by (h(y)) is valid; constant solutions lost by division must also be checked.

**Linear:** For \(y'+P(x)y=Q(x)\), integrating factor \(\mu=e^{\int P(x)dx}\),
\[
y=\frac{1}{\mu}\left(\int\mu Q(x)\,dx+C\right).
\]

**Exact:** \(M(x,y)dx+N(x,y)dy=0\) is exact when \(M_y=N_x\). Find potential \(\Psi\) such that \(\Psi_x=M,\Psi_y=N\); solution \(\Psi(x,y)=C\).

**Exponential growth/decay:** \(dy/dt=ky\) gives \(y=y_0e^{kt}\). For half-life \(T_{1/2}\), \(k=-\ln2/T_{1/2}\). For logistic growth \(dy/dt=ky(1-y/L)\),
\[
y(t)=\frac{L}{1+Ae^{-kt}},\qquad A=\frac{L-y_0}{y_0},
\]

where \(L>0\) is carrying capacity, \(k>0\), and \(y(0)=y_0\in(0,L)\).

### Second-order linear equations

For constant coefficients \(ay''+by'+cy=0\), solve \(ar^2+br+c=0\). Distinct real roots \(r_1,r_2\): \(y=C_1e^{r_1x}+C_2e^{r_2x}\). Repeated root \(r\): \(y=(C_1+C_2x)e^{rx}\). Complex roots \(\alpha\pm i\beta\):
\[
y=e^{\alpha x}(C_1\cos\beta x+C_2\sin\beta x).
\]

For a forced equation \(ay''+by'+cy=f(x)\), the general solution is homogeneous solution plus one particular solution. If the forcing duplicates a homogeneous term, multiply the trial particular form by \(x\) (or a higher power as needed).

**Undamped/ damped oscillator:** \(mx''+cx'+kx=F(t)\), where \(m\) is mass, \(c\) damping coefficient, \(k\) stiffness, \(F\) applied force. The undamped natural circular frequency is \(\omega_n=\sqrt{k/m}\); frequency \(f_n=\omega_n/(2\pi)\); damping ratio \(\zeta=c/(2\sqrt{mk})\). These assume a linear single-degree-of-freedom model.

### Laplace transform essentials

For \(t\ge0\), \(\mathcal L\{f(t)\}=F(s)=\int_0^\infty e^{-st}f(t)dt\), where the integral converges. Common pairs:
\[
\mathcal L\{1\}=\frac1s,\quad \mathcal L\{t^n\}=\frac{n!}{s^{n+1}},\quad \mathcal L\{e^{at}\}=\frac1{s-a},
\]
\[
\mathcal L\{\sin bt\}=\frac{b}{s^2+b^2},\quad \mathcal L\{\cos bt\}=\frac{s}{s^2+b^2}.
\]

Initial conditions enter through \(\mathcal L\{y'\}=sY-y(0)\) and \(\mathcal L\{y''\}=s^2Y-sy(0)-y'(0)\). Use partial fractions to invert rational transforms.

## 3. Probability and statistics

### Descriptive statistics

For observations \(x_1,\ldots,x_n\),
\[
\bar x=\frac1n\sum_{i=1}^n x_i,\qquad s^2=\frac{\sum_{i=1}^n(x_i-\bar x)^2}{n-1},\qquad s=\sqrt{s^2}.
\]

The sample variance uses (n-1) degrees of freedom as an unbiased estimator of population variance. For a full population, variance is \(\sigma^2=N^{-1}\sum(x_i-\mu)^2\). For grouped data with class midpoint \(m_j\) and frequency \(f_j\), use \(\bar x\approx\sum f_jm_j/\sum f_j\).

Coefficient of variation \(CV=s/\bar x\) (often reported as a percent) compares relative spread and is meaningful for a positive ratio-scale mean. Standard score: \(z=(x-\mu)/\sigma\), or sample-based \(t=(x-\bar x)/s\).

### Probability rules and random variables
\[
P(A^c)=1-P(A),\quad P(A\cup B)=P(A)+P(B)-P(A\cap B),\quad P(A|B)=\frac{P(A\cap B)}{P(B)}.
\]

If independent, \(P(A\cap B)=P(A)P(B)\). Bayes' rule:
\[
P(A_i|B)=\frac{P(B|A_i)P(A_i)}{\sum_jP(B|A_j)P(A_j)}.
\]

For discrete \(X\), \(E[X]=\sum_xxP(X=x)\) and \(\operatorname{Var}(X)=E[X^2]-E[X]^2\). For continuous density (f(x)), \(E[X]=\int xf(x)dx\), with total density integral 1. For independent variables, \(E[X+Y]=E[X]+E[Y]\) and \(\operatorname{Var}(X+Y)=\operatorname{Var}(X)+\operatorname{Var}(Y)\).

### Common distributions

**Binomial:** \(X\sim\operatorname{Bin}(n,p)\), \(P(X=k)=\binom nkp^k(1-p)^{n-k}\), mean \(np\), variance (np(1-p)). Assumes fixed \(n\), independent trials, constant success probability \(p\).

**Poisson:** \(P(X=k)=e^{-\lambda}\lambda^k/k!\), mean and variance \(\lambda\). Models counts over a fixed exposure when events occur independently at a constant average rate. A binomial approximation uses \(\lambda=np\) when \(n\) is large and \(p\) small.

**Normal:** \(X\sim N(\mu,\sigma^2)\); standardize using \(Z=(X-\mu)/\sigma\). A normal approximation to a binomial is commonly reasonable when both \(np\) and (n(1-p)) are sufficiently large; apply continuity correction for integer counts.

### Sampling, confidence intervals, and tests

For sample mean with known population standard deviation, a two-sided \(100(1-\alpha)\%\) confidence interval is
\[
\bar x\pm z_{1-\alpha/2}\frac{\sigma}{\sqrt n}.
\]

If \(\sigma\) is unknown and the population is approximately normal, use \(\bar x\pm t_{1-\alpha/2,n-1}s/\sqrt n\). For a proportion \(\hat p=x/n\), the large-sample interval is approximately \(\hat p\pm z_{1-\alpha/2}\sqrt{\hat p(1-\hat p)/n}\); use a suitable exact or adjusted method for small samples or extreme proportions.

To estimate a mean within margin \(E\), known \(\sigma\): \(n\ge(z_{1-\alpha/2}\sigma/E)^2\), rounded up. For a proportion with planning estimate \(p_0\), \(n\ge z^2p_0(1-p_0)/E^2\); if unknown, \(p_0=0.5\) is conservative.

Test statistic for a one-sample mean: \(z=(\bar x-\mu_0)/(\sigma/\sqrt n)\) if \(\sigma\) known; \(t=(\bar x-\mu_0)/(s/\sqrt n)\) if estimated with normal population assumptions. A p-value is the probability, under the null hypothesis, of a result at least as extreme as observed. Reject \(H_0\) when p-value \(\le\alpha\), per the chosen test; statistical significance does not measure practical importance.

### Regression and correlation

For paired data \((x_i,y_i)\), the least-squares line is \(\hat y=a+bx\), with
\[
b=\frac{\sum(x_i-\bar x)(y_i-\bar y)}{\sum(x_i-\bar x)^2},\qquad a=\bar y-b\bar x.
\]

Pearson correlation is \(r=\frac{\sum(x_i-\bar x)(y_i-\bar y)}{\sqrt{\sum(x_i-\bar x)^2\sum(y_i-\bar y)^2}}\), with \(-1\le r\le1\). Correlation does not establish causation; extrapolation beyond the observed range is risky.

## 4. Numerical methods

Let \(x^*\) denote an exact value and \(\tilde x\) an approximation. Absolute error is \(E_a=|x^*-\tilde x|\); relative error \(E_r=E_a/|x^*|\) when \(x^*\ne0\); percent relative error \(100E_r\%\). For iterative methods, an approximate relative change is \(\left| (x_{k+1}-x_k)/x_{k+1}\right|\).

### Roots of equations

**Bisection:** If continuous \(f(a)f(b)<0\), set \(c=(a+b)/2\), retain the half interval with a sign change, and repeat. After \(n\) halvings, interval width is \((b-a)/2^n\); the midpoint error is at most half that width.

**Newton–Raphson:**
\[
x_{k+1}=x_k-\frac{f(x_k)}{f'(x_k)}.
\]

Converges rapidly near a simple root with a good initial guess, but can diverge if the derivative is small or the starting point is poor.

**Secant:** \(x_{k+1}=x_k-f(x_k)(x_k-x_{k-1})/[f(x_k)-f(x_{k-1})]\). It avoids evaluating the derivative but needs two starting values and a nonzero denominator.

### Interpolation and linear systems

Linear interpolation between \((x_0,y_0)\) and \((x_1,y_1)\):
\[
y(x)\approx y_0+\frac{x-x_0}{x_1-x_0}(y_1-y_0).
\]

Lagrange interpolation through distinct points \((x_i,y_i)\), \(i=0,\ldots,n\):
\[
P_n(x)=\sum_{i=0}^n y_i\prod_{j\ne i}\frac{x-x_j}{x_i-x_j}.
\]

For \(A\mathbf x=\mathbf b\), Gaussian elimination transforms the system to triangular form, then back substitution finds the solution. Partial pivoting improves numerical stability. If \(A\) is nonsingular, \(\mathbf x=A^{-1}\mathbf b\), but directly computing an inverse is usually less efficient than solving the system.

### Numerical differentiation and integration

With equal spacing \(h\), central difference is generally more accurate than one-sided differences:
\[
f'(x)\approx\frac{f(x+h)-f(x-h)}{2h},\qquad f''(x)\approx\frac{f(x+h)-2f(x)+f(x-h)}{h^2}.
\]

Composite trapezoidal rule for \(n\) equal subintervals, \(h=(b-a)/n\):
\[
\int_a^b f(x)dx\approx h\left[\frac{f_0+f_n}{2}+\sum_{i=1}^{n-1}f_i\right].
\]

Composite Simpson's (1/3) rule requires even \(n\):
\[
\int_a^b f(x)dx\approx\frac h3\left[f_0+f_n+4\sum_{i\text{ odd}}f_i+2\sum_{i\text{ even},\,0<i<n}f_i\right].
\]

### Numerical solution of ODEs

For \(y'=f(t,y)\) with step \(h\), explicit Euler is \(y_{n+1}=y_n+h f(t_n,y_n)\). Classical fourth-order Runge–Kutta:
\[
k_1=f(t_n,y_n),\quad k_2=f(t_n+h/2,y_n+hk_1/2),
\]
\[
k_3=f(t_n+h/2,y_n+hk_2/2),\quad k_4=f(t_n+h,y_n+hk_3),
\]
\[
y_{n+1}=y_n+\frac h6(k_1+2k_2+2k_3+k_4).
\]

The step size controls discretization error and stability; halving \(h\) is a useful convergence check.

## 5. Physics and engineering science

Use a consistent unit system. In SI, force \(N=kg\,m/s^2\), work \(J=N\,m\), power \(W=J/s\), pressure \(Pa=N/m^2\). Weight is a force; mass is not. Near Earth's surface, \(W=mg\), with \(g\approx9.81\,m/s^2\) \(or (32.2\,ft/s^2)\); use the value and units specified by the problem.

### Vectors and mechanics

For vector components, \(R_x=\sum F_x\), \(R_y=\sum F_y\); resultant magnitude \(R=\sqrt{R_x^2+R_y^2}\), direction \(\theta=\tan^{-1}(R_y/R_x)\) with quadrant checked. Equilibrium of a particle requires \(\sum\mathbf F=0\); planar rigid-body equilibrium requires \(\sum F_x=0,\sum F_y=0,\sum M=0\).

Kinematics for constant acceleration:
\[
v=u+at,\quad s=ut+\frac12at^2,\quad v^2=u^2+2as,\quad s=\frac{u+v}{2}t.
\]

Here \(u,v\) are initial/final velocity, \(a\) acceleration, \(t\) time, \(s\) displacement. Newton's second law is \(\sum F=ma\). Momentum \(p=mv\); impulse \(J=\int Fdt=\Delta p\). Work \(W=\int\mathbf F\cdot d\mathbf s\); for constant force \(W=Fs\cos\theta\). Kinetic energy \(T=\tfrac12mv^2\); gravitational potential energy near the surface \(V=mgh\); power \(P=dW/dt=\mathbf F\cdot\mathbf v\).

For circular motion, \(v=r\omega\), \(a_n=v^2/r=r\omega^2\), and \(F_n=mv^2/r\). For rotation about a fixed axis, \(\sum M=I\alpha\), rotational kinetic energy \(T=\tfrac12I\omega^2\). Rolling without slipping gives \(v=r\omega\).

### Fluids and pressure

Density \(\rho=m/V\), specific weight \(\gamma=\rho g\), and specific gravity \(SG=\rho/\rho_{water}\). Hydrostatic gauge pressure at depth \(h\) below a free surface is \(p=\rho gh=\gamma h\) for a static, incompressible fluid of uniform density. Absolute pressure \(p_{abs}=p_{gauge}+p_{atm}\).

Continuity for steady flow is \(Q=Av\); for incompressible flow, \(A_1v_1=A_2v_2\). Bernoulli along a streamline for steady, incompressible, inviscid flow without pump/turbine or losses:
\[
\frac p{\gamma}+\frac{v^2}{2g}+z=\text{constant}.
\]

With machine heads and losses, \(p_1/\gamma+v_1^2/(2g)+z_1+h_p-h_t=p_2/\gamma+v_2^2/(2g)+z_2+h_L\). Actual system analysis must include relevant losses and boundary conditions.

### Heat, electricity, and dimensional checks

Sensible heat \(Q=mc_p\Delta T\), where \(c_p\) is specific heat; ideal-gas relation \(pV=mRT\), with absolute temperature and consistent gas constant. Ohm's law \(V=IR\); electrical power \(P=VI=I^2R=V^2/R\). Dimensional consistency is necessary: both sides of an equation must have identical dimensions.

## 6. Engineering economy

Cash-flow factors assume a constant effective interest rate \(i\) per period, end-of-period uniform payments unless otherwise stated, and consistent period units. \(P\) is present worth, \(F\) future worth, \(A\) equal end-of-period amount, \(n\) number of periods.

### Single amounts and uniform series
\[
F=P(1+i)^n,\qquad P=F(1+i)^{-n}.
\]
\[
F=A\frac{(1+i)^n-1}{i},\qquad A=F\frac{i}{(1+i)^n-1}.
\]
\[
P=A\frac{1-(1+i)^{-n}}{i},\qquad A=P\frac{i(1+i)^n}{(1+i)^n-1}.
\]

For a perpetuity, \(P=A/i\) if payments continue indefinitely and \(i>0\). For an annuity due with payments at the beginning of each period, multiply the corresponding ordinary-annuity present- or future-worth factor by ((1+i)).

### Gradients, rates, and comparison

For arithmetic gradient \(G\) beginning with zero extra amount at period 1 and increasing by \(G\) each later period, \(A_G=G[1/i-n/((1+i)^n-1)]\); \(P_G=A_G(P/A,i,n)\). A geometric series \(A_1,A_1(1+g),\ldots\) has present worth \(P=A_1[1-((1+g)/(1+i))^n]/(i-g)\), for \(i\ne g\), where \(A_1\) is the period-1 amount and payments occur at period ends.

Effective annual rate from nominal annual rate \(j\), compounded \(m\) times/year: \(i_{eff}=(1+j/m)^m-1\). Continuous compounding: \(F=Pe^{rt}\). Convert rates and cash-flow periods before using factors. For inflation \(f\), exact real rate \(i_r=(1+i_n)/(1+f)-1\); use either nominal cash flows with nominal rate or real cash flows with real rate.

Net present worth: \(NPW=\sum_{t=0}^n CF_t/(1+i)^t\). Choose the alternative with the greatest positive NPW when alternatives provide equivalent service and all costs/benefits are included. Internal rate of return \(IRR\) solves \(NPW=0\); multiple sign changes can produce multiple or no meaningful IRRs, so NPW comparison is safer for mutually exclusive alternatives. Equivalent annual worth \(EAW=NPW(A/P,i,n)\).

Simple payback is time until cumulative undiscounted net cash flow recovers initial cost; discounted payback discounts each flow first. Neither alone measures value over the full study period. Benefit-cost ratio conventions vary; state whether denominator includes initial and recurring costs.

### Depreciation and replacement

Straight-line depreciation per year: \(D=(C-S)/N\), book value after \(t\) years \(BV_t=C-tD\), with first cost \(C\), salvage \(S\), useful life \(N\). Declining-balance depreciation at rate \(d\): \(D_t=dBV_{t-1}\); double-declining uses \(d=2/N\), subject to salvage and applicable tax rules. These are accounting methods; tax treatment is jurisdiction-specific.

For capitalized cost \(C\), annual operating cost \(O\), salvage \(S\) at year \(n\), an equivalent annual cost is \(EAC=[C-S(P/F,i,n)](A/P,i,n)+O\), if \(O\) is uniform. For replacement studies, compare alternatives over a common study period or use equivalent annual worth with justified lives and service assumptions.

## 7. Surveying

### Units, bearings, and coordinate geometry

Convert \(1^\circ=60'\), \(1'=60''\); radians \(=\text{degrees}\times\pi/180\). A whole-circle azimuth \(A\) is clockwise from north. For line length \(L\), east and north components are \(\Delta E=L\sin A\), \(\Delta N=L\cos A\). Add signed components to obtain coordinates. Check quadrant and angle convention before using trigonometric functions.

For points \((E_i,N_i)\), traverse closure errors are \(e_E=\sum\Delta E\), \(e_N=\sum\Delta N\), linear misclosure \(e=\sqrt{e_E^2+e_N^2}\). Relative precision is total traverse length divided by \(e\). Bowditch correction for line \(i\), length \(L_i\), total length \(L_T\): \(c_{E_i}=-e_E(L_i/L_T)\), \(c_{N_i}=-e_N(L_i/L_T)\); it assumes angular and linear errors are distributed approximately in proportion to length.

Coordinate \(shoelace\) area of a closed polygon:
\[
A=\frac12\left|\sum_{i=1}^{n}(E_iN_{i+1}-E_{i+1}N_i)\right|,
\]

with point (n+1) equal to point 1. The result is horizontal plan area in squared coordinate units.

### Leveling

Height of instrument method: \(HI=RL_{known}+BS\), then \(RL_{point}=HI-FS\) (or (HI-IS)). Rise-and-fall method: \(RL_{next}=RL_{prev}+rise-fall\). Arithmetic check:
\[
\sum BS-\sum FS=RL_{last}-RL_{first}=\sum rise-\sum fall.
\]

Here \(RL\) is reduced level, \(BS\) backsight, \(FS\) foresight, \(IS\) intermediate sight. Apply curvature/refraction and collimation corrections when required by method, distance, and survey precision; do not silently mix vertical datums.

### Distance and angle observations

Horizontal distance from a slope distance \(S\) and vertical angle \(v\) from horizontal: \(D=S\cos v\), vertical difference \(\Delta H=S\sin v\). If zenith angle \(z\) is measured from vertical, \(D=S\sin z\), \(\Delta H=S\cos z\).

For stadia surveying with horizontal sight, distance \(D=Ks+C\), where \(s\) is upper-minus-lower staff intercept, \(K=f/i\) is multiplying constant, \(C=f+d\) additive constant, \(f\) focal length, \(i\) stadia-hair interval, and \(d\) optical-center to instrument-axis distance. Use instrument-specific constants. For inclined sight with vertical angle \(v\), horizontal distance commonly is \(D=Ks\cos^2v+C\cos v\); check the instrument's stadia convention.

### Circular curves and setting out

For a simple circular curve of radius \(R\) and central/deflection angle \(\Delta\) in degrees:
\[
T=R\tan(\Delta/2),\quad L=\frac{\pi R\Delta}{180},\quad LC=2R\sin(\Delta/2),\quad E=R[\sec(\Delta/2)-1],\quad M=R[1-\cos(\Delta/2)].
\]

Here \(T\) is tangent length, \(L\) arc length, \(LC\) long chord, \(E\) external distance, \(M\) middle ordinate. If using a degree of curve defined by arc length \(D_c\) per standard length \(l_s\), \(D_c=180l_s/(\pi R)\); chord-based definitions differ. State the convention.

## 8. Highway and transportation engineering

### Speed, flow, and traffic stream

For a traffic stream, flow \(q=kv\), where \(q\) is vehicles per unit time, density \(k\) vehicles per unit distance, and space-mean speed \(v\). For a uniform stream, time headway \(h\approx1/q\) and spacing \(s\approx1/k\), with consistent units. Capacity and level-of-service criteria depend on the applicable Highway Capacity Manual edition, facility type, and local conditions.

Travel time \(t=d/v\). Average speed over multiple segments is total distance divided by total travel time, not generally the arithmetic mean of segment speeds. For two speeds \(v_1,v_2\) over equal distances, average speed is harmonic mean \(2v_1v_2/(v_1+v_2)\).

### Stopping and passing sight distance

Level-road stopping sight distance with perception-reaction time \(t_r\), speed \(v\), and braking deceleration \(a\):
\[
SSD=vt_r+\frac{v^2}{2a}.
\]

For \(V\) in km/h, \(t_r\) in seconds, \(a\) in \(m/s^2\), convert \(v=V/3.6\) to m/s. A common highway-design form in customary units is \(SSD=1.47Vt_r+V^2/[30(f\pm G)]\) in feet, where \(V\) is mph, \(f\) is longitudinal tire-pavement friction factor, \(G\) is decimal grade (positive upgrade in the denominator; downgrade reduces braking distance). Use agency-prescribed perception time and design friction, not arbitrary values.

Passing sight distance is the sum of perception/initiation, passing, and clearance distances under a specified passing maneuver; use the applicable design manual's equations and assumptions rather than treating a single universal formula as valid.

### Horizontal alignment and superelevation

For a vehicle on a level circular path, lateral acceleration \(a_y=v^2/R\). Approximate equilibrium relation with superelevation \(e\) and side-friction factor \(f\):
\[
e+f=\frac{v^2}{gR}.
\]

With \(V\) in km/h and \(R\) in m, \(e+f=V^2/(127R)\) approximately; with \(V\) in mph and \(R\) in ft, \(e+f=V^2/(15R)\) approximately. These are design relationships; allowable \(e\), \(f\), runoff, and distribution are governed by the relevant road authority.

For a simple circular curve, use the surveying relationships \(T=R\tan(\Delta/2)\), \(L=\pi R\Delta/180\). Station at PC plus arc length gives PT station for arc definition; chord definition requires the stated stationing convention.

### Vertical curves

For a parabolic vertical curve of length \(L\), initial grade \(g_1\), final grade \(g_2\), algebraic grade difference \(A=g_2-g_1\), and distance \(x\) from the curve beginning:
\[
g(x)=g_1+\frac{A}{L}x,\qquad y(x)=y_0+g_1x+\frac{A}{2L}x^2.
\]

Grades are decimal (e.g., 0.02 for 2%) and elevation change and \(L,x\) use the same length units. The high/low point occurs at \(x=-g_1L/A\) if it falls within \(0\le x\le L\) and \(A\ne0\). Crest and sag curve design lengths for sight distance are based on eye/object heights and standards; confirm current agency tables/equations.

### Pavement and transportation quantities

Traffic growth at annual rate \(r\): \(A_n=A_0(1+r)^n\). Cumulative equivalent uniform annual traffic over \(n\) years is \(N=AADT_0\,D\,L\,365\,[(1+r)^n-1]/r\), where \(AADT_0\) is initial average annual daily traffic, \(D\) directional factor, \(L\) design-lane factor, assuming constant compound growth and factors. For \(r=0\), the growth multiplier is \(n\). Equivalent single-axle loads depend on axle-load spectra and the design method; do not infer them from vehicle count alone.

Rigid pavement slab stress, flexible pavement layer thickness, drainage, and structural-number design are method- and standard-specific; use the prescribed design procedure, material inputs, reliability, climate, and traffic loading.

## 9. Construction quantities and estimating

### Basic quantity formulas

Rectangular volume \(V=LWH\); prism \(V=Ah\); cylinder \(V=\pi r^2h\). For a trapezoidal cross-section with parallel widths \(b_1,b_2\), depth \(h\), area \(A=h(b_1+b_2)/2\). For a cut/fill section with side slopes (m:1) horizontal:vertical, bottom width \(b\), and depth \(h\), \(A=bh+mh^2\) for symmetric side slopes on level ground.

Average-end-area earthwork between sections distance \(L\): \(V=L(A_1+A_2)/2\). Prismoidal formula, when mid-area is available and variation is suitably represented:
\[
V=\frac L6(A_1+4A_m+A_2).
\]

For equally spaced sections, apply the composite prismoidal/Simpson rule only where section spacing and even-interval requirements are met. Distinguish bank, loose, and compacted volumes. If swell factor is defined \(S=V_{loose}/V_{bank}\), \(V_{loose}=S V_{bank}\); shrink factor must be explicitly defined because conventions vary.

Concrete quantity is net geometric volume plus separately stated waste/overage allowance. For a slab, \(V=LWH\). For a rectangular column, \(V=bhH\). For a circular column, \(V=\pi d^2H/4\). Subtract openings and avoid double counting intersections per measurement rules.

### Reinforcing steel and formwork

For a round reinforcing bar of diameter \(d\), cross-sectional area \(A_s=\pi d^2/4\), mass per unit length \(w=\rho_s A_s\). In SI with steel density about \(7850\,kg/m^3\), \(w\,[kg/m]\approx0.006165d^2\,[mm^2]\). This is theoretical mass; use the specified bar schedule and standard mass table for procurement.

Bar count for uniform spacing \(s\) over clear distribution width \(W\), with bars at both edges when specified: \(n\approx\lfloor W/s\rfloor+1\); adjust for cover and exact detailing. Total bar length equals sum of cut lengths including hooks, bends, laps, and development only as required by drawings/specification. Formwork contact area is the surface in contact with concrete, not the total concrete surface; measure each face once.

### Productivity and cost estimating

Production rate \(P=Q/T\), where \(Q\) is completed quantity and \(T\) elapsed working time. Duration \(T=Q/P\). Crew production may be limited by the bottleneck activity; account for workday length, utilization, downtime, learning, and site constraints. Unit cost \(C_u=C_{total}/Q\). Direct cost \(C_d=\sum_i q_i c_i\), where \(q_i\) is resource quantity and \(c_i\) unit cost. Add indirect costs, taxes, contingencies, escalation, and markup according to the estimate basis; do not apply markup ambiguously to already marked-up totals.

For equipment with cycle time \(t_c\) minutes, job efficiency \(E\) as a fraction, and bucket/load quantity \(q\), hourly output is approximately \(Q_h=q(60/t_c)E\). A truck fleet estimate should match truck capacity and cycle time to loader production; this simplified expression excludes queueing and changing haul conditions.

## 10. Construction management and project controls

### CPM/PERT scheduling

For activity duration \(d_{ij}\) from event \(i\) to \(j\), forward pass gives earliest event time \(E_j=\max_i(E_i+d_{ij})\). Backward pass gives latest event time \(L_i=\min_j(L_j-d_{ij})\). Activity early start \(ES\), early finish \(EF=ES+d\), late finish \(LF\), late start \(LS=LF-d\). Total float \(TF=LS-ES=LF-EF\); free float \(FF=\min(ES_{successors})-EF\). A critical path is a longest-duration path with zero total float under the adopted network and calendar. Multiple critical paths can exist.

For PERT three-point estimates, optimistic \(a\), most likely \(m\), pessimistic \(b\):
\[
t_e=\frac{a+4m+b}{6},\qquad \sigma_t^2=\left(\frac{b-a}{6}\right)^2.
\]

Project duration variance is approximated by summing activity variances on the critical path only when durations are independent and the critical path is stable. For target time \(T\), \(z=(T-\mu_T)/\sigma_T\) under the normal approximation.

### Earned value and cost/schedule indices

At a status date, \(PV\) is budgeted cost of scheduled work, \(EV\) budgeted cost of completed work, and \(AC\) actual cost of completed work. Cost variance \(CV=EV-AC\); schedule variance \(SV=EV-PV\); cost performance index \(CPI=EV/AC\); schedule performance index \(SPI=EV/PV\). Positive \(CV\) is under budget by this measure; positive \(SV\) means more budgeted work has been earned than planned, not necessarily more calendar time has elapsed.

If performance is expected to continue, estimate at completion \(EAC=BAC/CPI\), where \(BAC\) is budget at completion. If remaining work is expected at original budget rate, \(EAC=AC+(BAC-EV)\). Choose the forecast model that matches the cause and expected persistence of variance.

### Risk, resources, and safety basics

Expected monetary value \(EMV=\sum_i p_iC_i\), where \(p_i\) are mutually exclusive scenario probabilities summing to 1 and \(C_i\) corresponding consequences. A simple risk priority score may multiply likelihood, severity, and detectability rankings, but the score is an ordinal screening device, not a probability or monetary value.

Resource utilization \(U=\text{productive time}/\text{available time}\). Labor productivity is output per labor-hour; labor requirement is quantity divided by productivity. For crews, state whether productivity is per worker-hour or crew-hour.

For a simple fall distance under constant acceleration from rest, \(d=\tfrac12gt^2\); actual fall-protection systems involve arrest distance, deceleration, clearance, anchorage, and jurisdiction-specific requirements. Safety planning must use applicable regulations and manufacturer limits.

## 11. Symbols, units, and use checks

Many symbols are reused with different meanings: \(A\) may mean area, annuity, or grade difference; \(C\) may mean cost, a constant, or a curve quantity; \(g\) may mean acceleration or grade; \(L\) may mean length or latest event time. Read definitions within the relevant section and define every symbol in a submitted solution.

Before finalizing a calculation:

1. Draw a sketch or cash-flow/network diagram when geometry, direction, or timing matters.
2. Convert all inputs to compatible units before substitution; distinguish degrees from radians and mass from force.
3. Check signs, reference datum, direction, timing convention, and whether a quantity is gross or net.
4. Check dimensions and plausible magnitude; retain guard digits and round only the final reported value.
5. State material assumptions and use the applicable current agency/code criteria wherever a design limit is required.