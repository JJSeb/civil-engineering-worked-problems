# MSTC Formula Reference

Mathematics, Statistics, Physics, Surveying, Transportation, and Construction

A quick formula review for the listed preboard coverage: calculus, differential equations, engineering data analysis, numerical methods, physics, engineering economics, construction surveying and layout, highway/transportation, and quantity surveying. Check units, signs, assumptions, and the convention stated in each problem. Use applicable agency criteria where a design limit is required.

## 1. Calculus and mathematical foundations

### Geometry and trigonometry

For a right triangle with legs \(a,b\), hypotenuse \(c\), and angle \(\theta\):

\[
 c^2=a^2+b^2,\qquad
 \sin\theta=\frac{\text{opposite}}{c},\qquad
 \cos\theta=\frac{\text{adjacent}}{c},\qquad
 \tan\theta=\frac{\text{opposite}}{\text{adjacent}}.
\]

For any triangle, with side \(c\) opposite angle \(C\):

\[
 \frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C},\qquad
 c^2=a^2+b^2-2ab\cos C.
\]

\[
 K=\frac12 ab\sin C.
\]

Circle: circumference \(2\pi r\), area \(\pi r^2\). Sector angle \(\theta\) must be in radians:

\[
 s=r\theta,\qquad A=\frac12r^2\theta.
\]

### Derivatives and optimization

Derivative as instantaneous rate of change:

\[
 f'(x)=\lim_{h\to0}\frac{f(x+h)-f(x)}{h}.
\]

Common derivatives:

\[
 \frac{d}{dx}x^n=nx^{n-1},\qquad
 \frac{d}{dx}e^x=e^x,\qquad
 \frac{d}{dx}\ln x=\frac1x.
\]

\[
 \frac{d}{dx}\sin x=\cos x,\qquad
 \frac{d}{dx}\cos x=-\sin x.
\]

Product, quotient, and chain rules:

\[
 (uv)'=u'v+uv',\qquad
 \left(\frac uv\right)'=\frac{u'v-uv'}{v^2},\qquad
 \frac{d}{dx}f(g(x))=f'(g(x))g'(x).
\]

For a small change, \(dy\) estimates the change in \(y=f(x)\):

\[
 dy\approx f'(x)\,dx.
\]

A stationary point satisfies \(f'(x)=0\) (or the derivative is undefined). If \(f''>0\), it is a local minimum; if \(f''<0\), a local maximum, subject to the usual tests and domain.

### Integration and applications

Definite integral and antiderivative:

\[
 \int_a^b f(x)\,dx=F(b)-F(a),\qquad F'(x)=f(x).
\]

Common integrals:

\[
 \int x^n\,dx=\frac{x^{n+1}}{n+1}+C\quad(n\ne-1),\qquad
 \int\frac{dx}{x}=\ln|x|+C.
\]

\[
 \int e^{ax}\,dx=\frac{e^{ax}}a+C,\qquad
 \int\sin(ax)\,dx=-\frac{\cos(ax)}a+C,\qquad
 \int\cos(ax)\,dx=\frac{\sin(ax)}a+C.
\]

Substitution: \(u=g(x)\), \(du=g'(x)dx\). Integration by parts:

\[
 \int u\,dv=uv-\int v\,du.
\]

If \(v(t)\) is velocity, displacement is the signed integral; distance uses absolute speed. If \(Q(x)\) is cross-sectional area along a length, volume is its integral.

\[
 \Delta s=\int_{t_1}^{t_2}v(t)\,dt,\qquad
 d=\int_{t_1}^{t_2}|v(t)|\,dt,\qquad
 V=\int_a^b Q(x)\,dx.
\]

Average value and area between curves:

\[
 f_{avg}=\frac{1}{b-a}\int_a^b f(x)\,dx,\qquad
 A=\int_a^b[f(x)-g(x)]\,dx\quad(f\ge g).
\]

### Approximation and series

First- and second-order Taylor approximations near \(x=a\):

\[
 f(x)\approx f(a)+f'(a)(x-a),
\]

\[
 f(x)\approx f(a)+f'(a)(x-a)+\frac{f''(a)}{2}(x-a)^2.
\]

The first omitted term estimates truncation error when the series behaves well near the point.

## 2. Differential equations

An ordinary differential equation (ODE) relates a function of one independent variable to its derivatives. Its order is the highest derivative present. An initial-value problem gives conditions at one point.

### First-order equations

**Separable:** for \(dy/dx=g(x)h(y)\), separate variables and integrate where \(h(y)\ne0\). Check constant solutions separately.

\[
 \int\frac{dy}{h(y)}=\int g(x)\,dx+C.
\]

**Linear:** for \(y'+P(x)y=Q(x)\), the integrating factor is \(\mu=e^{\int P(x)dx}\).

\[
 y=\frac1\mu\left(\int\mu Q(x)\,dx+C\right).
\]

**Exponential growth or decay:** \(k\) is the constant growth rate and \(y_0=y(0)\).

\[
 \frac{dy}{dt}=ky,\qquad y=y_0e^{kt}.
\]

For half-life \(T_{1/2}\):

\[
 k=-\frac{\ln 2}{T_{1/2}}.
\]

### Second-order equations

For constant coefficients, solve the characteristic equation \(ar^2+br+c=0\).

\[
 ay''+by'+cy=0.
\]

Distinct roots \(r_1,r_2\):

\[
 y=C_1e^{r_1x}+C_2e^{r_2x}.
\]

Repeated root \(r\): \(y=(C_1+C_2x)e^{rx}\). Complex roots \(\alpha\pm i\beta\):

\[
 y=e^{\alpha x}(C_1\cos\beta x+C_2\sin\beta x).
\]

For a forced equation, general solution = homogeneous solution + one particular solution. If a trial term duplicates a homogeneous term, multiply the trial by \(x\).

## 3. Engineering data analysis

### Descriptive statistics

For data \(x_1,\ldots,x_n\), the sample mean and sample standard deviation are:

\[
 \bar x=\frac1n\sum_{i=1}^n x_i,
\]

\[
 s=\sqrt{\frac{\sum_{i=1}^n(x_i-\bar x)^2}{n-1}}.
\]

Use \(n-1\) for sample variance; for a full population of size \(N\), use \(N\) and population mean \(\mu\). Grouped-data mean, with class midpoint \(m_j\) and frequency \(f_j\):

\[
 \bar x\approx\frac{\sum f_jm_j}{\sum f_j}.
\]

Coefficient of variation compares relative spread; it is most useful for positive ratio-scale data.

\[
 CV=\frac{s}{\bar x}\times100\%.
\]

### Probability and distributions

Complement, union, and conditional probability:

\[
 P(A^c)=1-P(A),\qquad
 P(A\cup B)=P(A)+P(B)-P(A\cap B).
\]

\[
 P(A\mid B)=\frac{P(A\cap B)}{P(B)}.
\]

For independent events, \(P(A\cap B)=P(A)P(B)\). Bayes' rule:

\[
 P(A_i\mid B)=\frac{P(B\mid A_i)P(A_i)}{\sum_jP(B\mid A_j)P(A_j)}.
\]

Expected value and variance for a discrete random variable:

\[
 E[X]=\sum_x xP(X=x),\qquad
 \operatorname{Var}(X)=E[X^2]-E[X]^2.
\]

Binomial \(X\sim\operatorname{Bin}(n,p)\):

\[
 P(X=k)=\binom nkp^k(1-p)^{n-k},\qquad E[X]=np,\qquad \operatorname{Var}(X)=np(1-p).
\]

Poisson count with mean \(\lambda\):

\[
 P(X=k)=\frac{e^{-\lambda}\lambda^k}{k!},\qquad E[X]=\operatorname{Var}(X)=\lambda.
\]

Normal variable \(X\sim N(\mu,\sigma^2)\), standardized to \(Z\):

\[
 Z=\frac{X-\mu}{\sigma}.
\]

### Estimation and regression

Approximate confidence interval for a mean when population standard deviation \(\sigma\) is known:

\[
 \bar x\pm z_{1-\alpha/2}\frac{\sigma}{\sqrt n}.
\]

If \(\sigma\) is unknown and data are approximately normal, replace \(z\sigma\) with \(t_{n-1}s\). A p-value is assessed against the chosen significance level \(\alpha\); statistical significance does not by itself show practical importance.

Least-squares line for paired data \((x_i,y_i)\):

\[
 \hat y=a+bx.
\]

\[
 b=\frac{\sum(x_i-\bar x)(y_i-\bar y)}{\sum(x_i-\bar x)^2},\qquad
 a=\bar y-b\bar x.
\]

Correlation measures linear association; it does not establish causation. Avoid unsupported extrapolation.

## 4. Numerical methods

For exact value \(x^*\) and approximation \(\tilde x\):

\[
 E_a=|x^*-\tilde x|,\qquad
 E_r=\frac{E_a}{|x^*|}\quad(x^*\ne0).
\]

Percent relative error is \(100E_r\%\).

### Roots and interpolation

Bisection requires continuous \(f\) and opposite signs at the interval ends. The midpoint and interval width after \(n\) halvings are:

\[
 c=\frac{a+b}{2},\qquad
 w_n=\frac{b-a}{2^n}.
\]

Newton-Raphson iteration:

\[
 x_{k+1}=x_k-\frac{f(x_k)}{f'(x_k)}.
\]

It may fail if the initial guess is poor or the derivative is near zero.

Linear interpolation between \((x_0,y_0)\) and \((x_1,y_1)\):

\[
 y(x)\approx y_0+\frac{x-x_0}{x_1-x_0}(y_1-y_0).
\]

### Numerical differentiation and integration

With equal step \(h\), central differences:

\[
 f'(x)\approx\frac{f(x+h)-f(x-h)}{2h},
\]

\[
 f''(x)\approx\frac{f(x+h)-2f(x)+f(x-h)}{h^2}.
\]

Composite trapezoidal rule, \(h=(b-a)/n\):

\[
 \int_a^b f(x)\,dx\approx h\left[\frac{f_0+f_n}{2}+\sum_{i=1}^{n-1}f_i\right].
\]

Composite Simpson's one-third rule requires even \(n\):

\[
 \begin{aligned}
 \int_a^b f(x)\,dx&\approx\frac h3\Bigg[f_0+f_n\\
 &\qquad+4\sum_{i\text{ odd}}f_i\\
 &\qquad+2\sum_{i\text{ even},\,0<i<n}f_i\Bigg].
 \end{aligned}
\]

### Numerical solution of ODEs

For \(y'=f(t,y)\), explicit Euler step of size \(h\):

\[
 y_{n+1}=y_n+h f(t_n,y_n).
\]

Use a smaller step to check sensitivity and convergence.

## 5. Physics

Use compatible units. In SI, \(1\,\mathrm N=1\,\mathrm{kg\,m/s^2}\), \(1\,\mathrm J=1\,\mathrm{N\,m}\), and \(1\,\mathrm W=1\,\mathrm{J/s}\). Weight is a force; mass is not. Near Earth's surface, \(W=mg\), with \(g\approx9.81\,\mathrm{m/s^2}\).

### Mechanics

Forces in components and equilibrium:

\[
 R_x=\sum F_x,\qquad R_y=\sum F_y,\qquad
 R=\sqrt{R_x^2+R_y^2}.
\]

\[
 \sum F_x=0,\qquad \sum F_y=0,\qquad \sum M=0.
\]

Constant-acceleration motion, with initial velocity \(u\), final velocity \(v\), acceleration \(a\), time \(t\), and displacement \(s\):

\[
 v=u+at,\qquad s=ut+\frac12at^2.
\]

\[
 v^2=u^2+2as,\qquad s=\frac{u+v}{2}t.
\]

Newton's second law, momentum, and impulse:

\[
 \sum F=ma,\qquad p=mv,\qquad J=\int F\,dt=\Delta p.
\]

Work and energy:

\[
 W=Fs\cos\theta,\qquad T=\frac12mv^2,\qquad V_g=mgh.
\]

Power for a force acting along velocity:

\[
 P=\mathbf F\cdot\mathbf v.
\]

Circular motion at radius \(r\), speed \(v\), angular speed \(\omega\):

\[
 v=r\omega,\qquad a_n=\frac{v^2}{r},\qquad F_n=m\frac{v^2}{r}.
\]

### Fluids, heat, and electricity

Density \(\rho\), specific weight \(\gamma\), and hydrostatic gauge pressure at depth \(h\):

\[
 \rho=\frac mV,\qquad \gamma=\rho g,\qquad p=\rho gh=\gamma h.
\]

Continuity for steady incompressible flow:

\[
 Q=Av,\qquad A_1v_1=A_2v_2.
\]

Bernoulli equation along a streamline for steady, incompressible, inviscid flow with no machine head or losses:

\[
 \frac p\gamma+\frac{v^2}{2g}+z=\text{constant}.
\]

Sensible heat, ideal gas, Ohm's law, and electric power:

\[
 Q=mc_p\Delta T,\qquad pV=mRT.
\]

\[
 V=IR,\qquad P=VI=I^2R=\frac{V^2}{R}.
\]

Use absolute temperature in the ideal-gas relation. Keep both sides of every equation dimensionally consistent.

## 6. Engineering economics

Use one effective interest rate \(i\) per period and match it to the cash-flow period. \(P\) = present worth, \(F\) = future worth, \(A\) = equal end-of-period payment, \(n\) = number of periods.

### Single amounts and uniform series

\[
 F=P(1+i)^n,\qquad P=\frac{F}{(1+i)^n}.
\]

\[
 F=A\frac{(1+i)^n-1}{i},\qquad
 P=A\frac{1-(1+i)^{-n}}{i}.
\]

Capital recovery and sinking-fund factors:

\[
 A=P\frac{i(1+i)^n}{(1+i)^n-1},\qquad
 A=F\frac{i}{(1+i)^n-1}.
\]

For a perpetuity, \(P=A/i\) when \(i>0\). An annuity due shifts each payment one period earlier; multiply the ordinary-annuity factor by \((1+i)\).

### Comparing alternatives

Net present worth (NPW), for cash flow \(CF_t\) at time \(t\):

\[
 NPW=\sum_{t=0}^{n}\frac{CF_t}{(1+i)^t}.
\]

Compare equivalent alternatives over a consistent study period. Internal rate of return sets \(NPW=0\); multiple cash-flow sign changes can give misleading IRR results.

Effective annual rate from nominal annual rate \(j\), compounded \(m\) times per year:

\[
 i_{eff}=\left(1+\frac jm\right)^m-1.
\]

Straight-line depreciation per year, with first cost \(C\), salvage value \(S\), and useful life \(N\):

\[
 D=\frac{C-S}{N}.
\]

## 7. Construction surveying and layout

### Bearings, coordinates, and traverse

Convert angles: \(1^\circ=60'\), \(1'=60''\), and radians = degrees \(\times\pi/180\). Whole-circle azimuth \(A\) is measured clockwise from north. For line length \(L\):

\[
 \Delta E=L\sin A,\qquad \Delta N=L\cos A.
\]

Sum signed components to compute coordinates. Traverse misclosure and linear error:

\[
 e_E=\sum\Delta E,\qquad e_N=\sum\Delta N,
\]

\[
 e=\sqrt{e_E^2+e_N^2}.
\]

Bowditch corrections for line \(i\) of length \(L_i\), total traverse length \(L_T\):

\[
 c_{E_i}=-e_E\frac{L_i}{L_T},\qquad
 c_{N_i}=-e_N\frac{L_i}{L_T}.
\]

### Leveling and distance

Height of instrument (HI) method: \(RL\) = reduced level, \(BS\) = backsight, \(FS\) = foresight, \(IS\) = intermediate sight.

\[
 HI=RL_{known}+BS,\qquad
 RL_{point}=HI-FS.
\]

Leveling arithmetic check:

\[
 \sum BS-\sum FS=RL_{last}-RL_{first}.
\]

For slope distance \(S\) and vertical angle \(v\) from horizontal:

\[
 D=S\cos v,\qquad \Delta H=S\sin v.
\]

Check angle reference, signs, and datum before calculating elevations.

### Areas and setting out curves

Coordinate area of a closed polygon (shoelace formula), with point \(n+1\) equal to point 1:

\[
 A=\frac12\left|\sum_{i=1}^{n}
 (E_iN_{i+1}-E_{i+1}N_i)\right|.
\]

For simple circular curve radius \(R\), central angle \(\Delta\) in degrees, tangent \(T\), and arc length \(L\):

\[
 T=R\tan\left(\frac\Delta2\right),\qquad
 L=\frac{\pi R\Delta}{180}.
\]

Long chord \(LC\), external distance \(E\), middle ordinate \(M\):

\[
 LC=2R\sin\left(\frac\Delta2\right),
\]

\[
 E=R\left[\sec\left(\frac\Delta2\right)-1\right],\qquad
 M=R\left[1-\cos\left(\frac\Delta2\right)\right].
\]

## 8. Highway and transportation

### Traffic flow and travel time

Flow \(q\), density \(k\), and space-mean speed \(v\) must use compatible units:

\[
 q=kv.
\]

Travel time is distance divided by speed. Average speed is total distance divided by total time; for equal-distance trips at two speeds, use the harmonic mean.

\[
 t=\frac dv,\qquad
 v_{avg}=\frac{2v_1v_2}{v_1+v_2}\quad\text{(equal distances)}.
\]

### Stopping distance and horizontal curves

Level-road stopping sight distance, with speed \(v\), perception-reaction time \(t_r\), and braking deceleration \(a\):

\[
 SSD=vt_r+\frac{v^2}{2a}.
\]

Use \(v\) in length per time and consistent units for \(a\). For \(V\) in km/h, convert with \(v=V/3.6\) m/s.

Approximate horizontal-curve relation, with superelevation \(e\), side-friction factor \(f\), speed \(v\), and radius \(R\):

\[
 e+f=\frac{v^2}{gR}.
\]

For \(V\) in km/h and \(R\) in metres:

\[
 e+f\approx\frac{V^2}{127R}.
\]

Allowable values and detailed design criteria depend on the governing road authority.

### Vertical alignment and traffic growth

For a parabolic vertical curve of length \(L\), initial grade \(g_1\), final grade \(g_2\), and distance \(x\) from its beginning, grades are decimals:

\[
 A=g_2-g_1,\qquad
 g(x)=g_1+\frac{A}{L}x.
\]

Elevation \(y_0\) at the beginning of the curve:

\[
 y(x)=y_0+g_1x+\frac{A}{2L}x^2.
\]

Traffic growth at annual rate \(r\) for \(n\) years:

\[
 A_n=A_0(1+r)^n.
\]

Cumulative traffic multiplier for constant compound growth:

\[
 G_n=\frac{(1+r)^n-1}{r},\qquad G_n=n\quad(r=0).
\]

Pavement structural design and detailed transportation planning require the specified method and local inputs; vehicle count alone does not determine axle loading or pavement thickness.

## 9. Quantity surveying and construction quantities

### Areas and volumes

Rectangular volume, prism, cylinder, and trapezoidal area:

\[
 V=LWH,\qquad V=Ah,\qquad V_{cyl}=\pi r^2h.
\]

\[
 A_{trap}=\frac h2(b_1+b_2).
\]

For symmetric cut/fill side slopes \(m\!:\!1\) (horizontal:vertical), bottom width \(b\), and depth \(h\):

\[
 A=bh+mh^2.
\]

Average-end-area and prismoidal earthwork volumes over distance \(L\):

\[
 V_{AEA}=\frac L2(A_1+A_2),
\]

\[
 V_{prism}=\frac L6(A_1+4A_m+A_2).
\]

Distinguish bank, loose, and compacted volume. If swell factor is defined as \(S=V_{loose}/V_{bank}\):

\[
 V_{loose}=S V_{bank}.
\]

### Quantity takeoff and estimating

Concrete quantity is net geometric volume; state any waste allowance separately. Subtract openings and avoid double-counting intersections. Formwork quantity is the area in contact with concrete.

Production rate \(P\), quantity \(Q\), time \(T\), and unit cost \(C_u\):

\[
 P=\frac QT,\qquad T=\frac QP.
\]

\[
 C_u=\frac{C_{total}}{Q},\qquad
 C_d=\sum_i q_i c_i.
\]

Here \(C_d\) is direct cost, \(q_i\) resource quantity, and \(c_i\) unit cost. Add indirect costs, taxes, contingency, and markup according to the stated estimate basis.

## 10. Symbols, units, and calculation checks

Symbols are reused: \(A\) may mean area, annuity, or grade difference; \(g\) may mean gravity or road grade; \(L\) may mean length. Use each section's definitions.

1. Sketch geometry, directions, or cash flows when they matter.
2. Convert units before substitution; distinguish degrees from radians and mass from force.
3. Check signs, datum, reference direction, and gross versus net quantities.
4. Check dimensions and plausible magnitude; round only the final result.
5. State assumptions and use the required agency criteria for design limits.
