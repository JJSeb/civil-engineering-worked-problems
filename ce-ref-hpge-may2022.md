# CE REF Volume 5 — May 2022 HPGE

**Questions 1–47 · Worked derivations**

The calculations below use the quantities and diagrams printed with the May 2022 set (printed pp. 412–418). Each answer is checked against the printed key on p. 418. The book's worked pages are pp. 419–435; these explanations independently set out the governing relation and substitutions. Use \(g=9.81\,\mathrm{m/s^2}\), \(\gamma_w=9.81\,\mathrm{kN/m^3}\), and water density \(1000\,\mathrm{kg/m^3}\), unless stated otherwise.

**Source corrections:** Q1 asks for an increase, but climbing to higher altitude reduces pressure; the pressure change is \(-48\) kPa (a 48 kPa decrease), matching the key's magnitude and choice B. Q18's worked page prints the buoy weight as 1,751 kN; the correct unit is **N** (1.751 kN), matching choice C. Q21's key is D and the trajectory calculation confirms 1.883 s. Q42–44 use the stated layering to the clay midpoint; the source worked page's values (and key) agree when computed consistently.

## Hydrostatics and fluid flow

### Q1 — B · 48 kPa (decrease)
Hydrostatic pressure change over an elevation change is \(\Delta p=-\gamma_{air}\Delta z\) when moving upward. Here \(\Delta z=10-6=4\) km and \(\gamma_{air}=12\,\mathrm{N/m^3}\).

\[
\Delta p=-12(4{,}000)=-48{,}000\,\mathrm{Pa}=-48\,\mathrm{kPa}.
\]

The pressure decreases by 48 kPa. **Key check:** B gives 48 kPa as a magnitude; the question's word “increase” is directionally incorrect.

### Q2 — D · 4.72 kPa
For a liquid in an elevator accelerating upward, effective gravity is (g+a), so bottom gauge pressure is \(p=\rho(g+a)h=\gamma_w h(1+a/g)\). With \(h=0.400\) m and \(a=2\,\mathrm{m/s^2}\):

\[
p=9.81(0.400)\left(1+\frac{2}{9.81}\right)=4.72\,\mathrm{kPa}.
\]

**Key check:** D.

### Q3 — A · 1.48 kg lead
Wood volume is \(0.07^2(1.5)=0.00735\,\mathrm{m^3}\); the extra 0.25 m protruding above water leaves \(1.25\) m of the wood submerged. Set upward buoyancy equal to wood plus lead weight, with lead volume \(V_L=m_L/\rho_L\):

\[
\rho_w g(0.07^2)(1.25)=0.65\rho_wg(0.07^2)(1.5)+m_Lg\left(1-\frac{1}{11.2}\right).
\]

Solving gives \(m_L\approx1.48\,\mathrm{kg}\). **Key check:** A.

### Q4 — C · 3.06 m draft
The cement mass is \(6000(40)=240{,}000\) kg. Total supported weight in force units is \(400+240{,}000(9.81)/1000=2754.4\) kN. Displaced-water unit weight is \(1.02(9.81)=10.0062\,\mathrm{kN/m^3}\), and displaced volume is (6(15)d).

\[
d=\frac{2754.4}{10.0062(6)(15)}=3.059\,\mathrm{m}\approx3.06\,\mathrm{m}.
\]

**Key check:** C.

### Q5 — D · 66.22 kN
The vertical triangular gate has base \(b=1.5\) m, height \(h=3\) m, and its horizontal top edge is 2 m below the free surface. Its area is \(A=bh/2=2.25\,\mathrm{m^2}\). The centroid of a triangle is \(h/3=1\) m below its base, so its depth is \(\bar h=3\) m.

\[
F=\gamma_w\bar hA=9.81(3)(2.25)=66.22\,\mathrm{kN}.
\]

**Key check:** D.

### Q6 — A · 0.167 m
For the same triangle, \(I_G=bh^3/36=1.5(3^3)/36=1.125\,\mathrm{m^4}\). The center-of-pressure offset below the centroid is

\[
e=\frac{I_G}{A\bar h}=\frac{1.125}{(2.25)(3)}=0.1667\,\mathrm{m}.
\]

**Key check:** A.

### Q7 — D · 3.167 m
The pressure-center depth below the water surface is centroid depth plus offset:

\[
h_{cp}=3+0.1667=3.167\,\mathrm{m}.
\]

**Key check:** D.

### Q8 — B · 268.4 kN
The rectangular gate is \(2\) m wide by \(3.6\) m high, with top at depth 2 m. Thus \(A=7.2\,\mathrm{m^2}\) and centroid depth \(\bar h=2+3.6/2=3.8\) m.

\[
F=9.81(3.8)(7.2)=268.4\,\mathrm{kN}.
\]

**Key check:** B.

### Q9 — A · 0.284 m
For the same rectangle, \(I_G=bh^3/12=2(3.6^3)/12=7.776\,\mathrm{m^4}\). Its centroid is 3.8 m deep.

\[
e=\frac{7.776}{(7.2)(3.8)}=0.2842\,\mathrm{m}.
\]

**Key check:** A.

### Q10 — B · 4.084 m
Add the 2 m depth of the gate top, the 1.8 m centroid depth below its top, and the 0.284 m center-of-pressure offset:

\[
h_{cp}=2+1.8+0.284=4.084\,\mathrm{m}.
\]

**Key check:** B.

### Q11 — B · 2.35 kN
The triangular gate has base \(0.5\) m and height \(1.2\) m, with its vertex at the surface and base horizontal. Its area is \(0.30\,\mathrm{m^2}\), and centroid depth is \(2h/3=0.8\) m.

\[
F=9.81(0.8)(0.30)=2.354\,\mathrm{kN}\approx2.35\,\mathrm{kN}.
\]

**Key check:** B.

### Q12 — C · 0.10 m
For this triangle \(I_G=bh^3/36=0.5(1.2^3)/36=0.024\,\mathrm{m^4}\).

\[
e=\frac{I_G}{A\bar h}=\frac{0.024}{(0.30)(0.8)}=0.10\,\mathrm{m}.
\]

**Key check:** C.

### Q13 — C · 0.90 m
The free surface passes through the vertex, so the pressure-center depth equals centroid depth plus offset:

\[
h_{cp}=0.8+0.10=0.90\,\mathrm{m}.
\]

**Key check:** C.

### Q14 — A · 4.75 m
For the square plate, \(A=9\,\mathrm{m^2}\), \(I_G=3(3^3)/12=6.75\,\mathrm{m^4}\). The given offset is \(e=0.12\) m, so from \(e=I_G/(A\bar h)\),

\[
\bar h=\frac{6.75}{9(0.12)}=6.25\,\mathrm{m},\qquad h_{top}=6.25-1.5=4.75\,\mathrm{m}.
\]

**Key check:** A.

### Q15 — D · 6.37 m
The pressure center lies \(0.12\) m below the centroid along the plate:

\[
h_{cp}=6.25+0.12=6.37\,\mathrm{m}.
\]

**Key check:** D.

### Q16 — B · 551.8 kN
Use the plate's centroid depth and area from Q14:

\[
F=\gamma_w\bar hA=9.81(6.25)(9)=551.8\,\mathrm{kN}.
\]

**Key check:** B.

### Q17 — D · 88.2%
For a floating homogeneous body, displaced fraction is the body-to-liquid specific-gravity ratio:

\[
\frac{V_{sub}}{V}=\frac{SG_{wood}}{SG_{liq}}=\frac{0.75}{0.85}=0.8824=88.24\%.
\]

**Key check:** D.

### Q18 — C · 1,751 N
The exposed volume is 0.028 m³, which is \(1-0.8824=0.11765\) of total volume. Thus \(V=0.028/0.11765=0.2380\,\mathrm{m^3}\). Buoyant equilibrium gives the buoy weight:

\[
W=SG_{wood}\gamma_wV=0.75(9.81)(0.2380)=1.752\,\mathrm{kN}\approx1{,}751\,\mathrm{N}.
\]

The worked scan labels this result “kN”; its numerical value is in newtons. **Key check:** C, 1,751.

### Q19 — B · 234 N
When fully submerged, the additional downward force required equals the difference between full-displacement buoyancy and the buoy's weight:

\[
F=(SG_{liq}-SG_{wood})\gamma_wV=(0.85-0.75)(9.81)(0.2380)=0.2335\,\mathrm{kN}=234\,\mathrm{N}.
\]

**Key check:** B.

### Q20 — A · 2.5 m
The jet leaves with speed \(v=C_v\sqrt{2gH}=\sqrt{2(9.81)(5)}=9.905\,\mathrm{m/s}\), directed 45° above horizontal. Vertical speed is \(v_y=9.905\sin45^\circ=7.004\,\mathrm{m/s}\). At its apex, \(v_y=0\):

\[
y_{max}=\frac{v_y^2}{2g}=\frac{7.004^2}{2(9.81)}=2.50\,\mathrm{m}.
\]

**Key check:** A.

### Q21 — D · 1.88 s
The 8 m water depth is divided by the diagram into a 5 m head above the orifice and 3 m from the orifice to the tank bottom; the ground is another 1.2 m below the bottom. Thus the ground is 4.2 m below the orifice, so \(y=-4.2\) m. With \(v_y=7.004\,\mathrm{m/s}\),

\[
-4.2=7.004t-\tfrac12(9.81)t^2\quad\Longrightarrow\quad t=1.883\,\mathrm{s}
\]

(positive root). **Key check:** D (1.88 s); the key is confirmed.

### Q22 — C · 13.2 m
Horizontal speed is constant at \(v_x=7.004\,\mathrm{m/s}\), so using Q21's flight time,

\[
x=v_xt=7.004(1.883)=13.19\,\mathrm{m}\approx13.2\,\mathrm{m}.
\]

**Key check:** C.

### Q23 — B · 1.42 m
The trapezoidal section has \(b=6\) m, \(y=1.2\) m, side slope (2H:1V), and top width \(T=6+2(2)(1.2)=10.8\) m. Area \(A=(6+10.8)(1.2)/2=10.08\,\mathrm{m^2}\); velocity \(V=Q/A=20.8/10.08=2.0635\,\mathrm{m/s}\).

\[
E=y+\frac{V^2}{2g}=1.2+\frac{2.0635^2}{2(9.81)}=1.417\,\mathrm{m}\approx1.42\,\mathrm{m}.
\]

**Key check:** B.

### Q24 — C · 0.00112
Wetted perimeter is \(P=6+2\sqrt{2.4^2+1.2^2}=11.366\) m; hydraulic radius \(R=A/P=10.08/11.366=0.887\) m. With \(n=0.015\), Manning's equation gives

\[
V=\frac1nR^{2/3}S^{1/2}\quad\Longrightarrow\quad S=\left(\frac{Vn}{R^{2/3}}\right)^2
=\left(\frac{2.0635(0.015)}{0.887^{2/3}}\right)^2=0.001124.
\]

**Key check:** C (0.00112).

### Q25 — D · 9.78 Pa
For uniform open-channel flow, boundary shear is \(\tau_0=\gamma_wRS\). Use the Q23–24 section data \(R=0.887\) m, \(S=0.001124\), and \(\gamma_w=9810\,\mathrm{N/m^3}\):

\[
\tau_0=9810(0.887)(0.001124)=9.78\,\mathrm{N/m^2}=9.78\,\mathrm{Pa}.
\]

**Key check:** D.

### Q26 — C · 20.1 N
For a stationary plate that turns the jet through 90°, the jet's incoming normal momentum is removed. Nozzle diameter \(D=0.020\) m gives \(A=\pi D^2/4=3.142\times10^{-4}\,\mathrm{m^2}\); \(V=8\,\mathrm{m/s}\), \(\rho=1000\,\mathrm{kg/m^3}\).

\[
F=\rho AV^2=1000\left(\frac{\pi(0.020)^2}{4}\right)(8^2)=20.1\,\mathrm{N}.
\]

**Key check:** C.

### Q27 — B · 5.03 N
The plate moves away at 4 m/s, so jet speed relative to it is \(u=8-4=4\,\mathrm{m/s}\). The mass flow actually intercepted per unit time is \(\rho Au\); force is therefore \(F=\rho Au^2\) for a 90° turn.

\[
F=1000\left(\frac{\pi(0.020)^2}{4}\right)(4^2)=5.03\,\mathrm{N}.
\]

**Key check:** B.

### Q28 — B · 53.1 N
Moving toward the nozzle at 5 m/s makes the relative approach speed \(u=8+5=13\,\mathrm{m/s}\). Then

\[
F=\rho Au^2=1000\left(\frac{\pi(0.020)^2}{4}\right)(13^2)=53.1\,\mathrm{N}.
\]

**Key check:** B.

## Geotechnical engineering

### Q29 — C · 1V:2H
The cited NSCP section states a maximum cut slope of one vertical to two horizontal (50% grade), unless an approved geotechnical report supports a steeper stable slope.

\[
\text{maximum stated slope}=\frac{1V}{2H}.
\]

**Key check:** C.

### Q30 — C · Liquefaction
The described mechanism is cyclic loading that raises pore pressure and removes much of the soil’s effective stress and shear resistance; the soil then behaves temporarily like a fluid.

\[
\text{sudden shaking}\rightarrow u\uparrow\rightarrow \sigma' = \sigma-u\downarrow\rightarrow \text{liquefaction}.
\]

**Key check:** C.

### Q31 — B · 18.6 kN/m³
Moist unit weight relates to dry unit weight by \(\gamma=\gamma_d(1+w)\). With \(\gamma_d=15.5\,\mathrm{kN/m^3}\) and \(w=0.20\):

\[
\gamma=15.5(1.20)=18.6\,\mathrm{kN/m^3}.
\]

**Key check:** B.

### Q32 — D · 24–48 kPa
The printed consistency table assigns the soft range to 0.25–0.50 tsf. Using \(1\,\mathrm{tsf}\approx96\,\mathrm{kPa}\):

\[
q_u=(0.25\text{ to }0.50)(96)=24\text{ to }48\,\mathrm{kPa}.
\]

**Key check:** D.

### Q33 — A · 39.5°
Rankine passive coefficient is \(K_p=(1+\sin\phi)/(1-\sin\phi)\). Rearranging for \(\sin\phi\):

\[
\sin\phi=\frac{K_p-1}{K_p+1}=\frac{4.5-1}{4.5+1}=0.63636,
\qquad \phi=\sin^{-1}(0.63636)=39.5^\circ.
\]

**Key check:** A.

### Q34 — D · 1.1 m
Initial void ratio \(e_0=1.2\); a reduction by one-third of its initial value means \(\Delta e=(1/3)(1.2)=0.4\), hence \(e_f=0.8\). For layer thickness \(H=6\) m:

\[
S=H\frac{e_0-e_f}{1+e_0}=6\frac{1.2-0.8}{2.2}=1.091\,\mathrm{m}\approx1.1\,\mathrm{m}.
\]

**Key check:** D.

### Q35 — A · 262 mm
Normally consolidated clay settlement is \(S=H\frac{C_c}{1+e_0}\log_{10}(p_f/p_0)\). Inputs: \(H=8\) m \(=8000\) mm, \(e_0=1.132\), \(C_c=0.315\), \(p_0=180\) kPa, and pressure increase 120 kPa, so \(p_f=300\) kPa.

\[
S=8000\frac{0.315}{1+1.132}\log_{10}\left(\frac{300}{180}\right)=262.2\,\mathrm{mm}.
\]

**Key check:** A.

### Q36 — A · Void ratio 0.431
Given bulk density \(\rho=1800\,\mathrm{kg/m^3}\), water content \(w=0.12\), and solids density \(\rho_s=2300\,\mathrm{kg/m^3}\), first find dry density \(\rho_d=\rho/(1+w)=1607.14\,\mathrm{kg/m^3}\). With \(G_s=2.3\),

\[
\rho_d=\frac{G_s\rho_w}{1+e}\quad\Longrightarrow\quad e=\frac{2.3(1000)}{1607.14}-1=0.431.
\]

**Key check:** A.

### Q37 — A · 15.76 kN/m³
Use the dry density found in Q36:

\[
\gamma_d=\frac{\rho_dg}{1000}=\frac{1607.14(9.81)}{1000}=15.76\,\mathrm{kN/m^3}.
\]

**Key check:** A.

### Q38 — C · 64%
The phase relation is \(Se=wG_s\). With \(w=0.12\), \(G_s=2.3\), and \(e=0.431\):

\[
S=\frac{wG_s}{e}=\frac{0.12(2.3)}{0.431}=0.640=64.0\%.
\]

**Key check:** C.

### Q39 — A · 290 Pa
For the direct-shear specimen, diameter \(d=50\) mm gives area \(A=\pi d^2/4=1963.5\,\mathrm{mm^2}\). Convert force/area from N/mm² to kPa (multiply by 1000). Data \(P,V)=(134,68.5),(206,105)\) N give normal stresses \(68.24,104.9\) kPa and shear stresses \(34.89,53.48\) kPa. Mohr–Coulomb relation \(\tau=c+\sigma\tan\phi\); the intercept is

\[
c=\frac{(104.9)(34.89)-(68.24)(53.48)}{104.9-68.24}=0.286\,\mathrm{kPa}=286\,\mathrm{Pa}\approx290\,\mathrm{Pa}.
\]

**Key check:** A.

### Q40 — D · 26.9°
The Mohr–Coulomb slope from the same two test pairs is \(\tan\phi=\Delta\tau/\Delta\sigma\):

\[
\phi=\tan^{-1}\left(\frac{53.48-34.89}{104.9-68.24}\right)=26.9^\circ.
\]

**Key check:** D.

### Q41 — A · 255.3 N
The stated pairs are normal force \(P=(134,206)\) N at shear force \(V=(68.5,105)\) N. Linear interpolation/extrapolation gives

\[
P(V)=134+\frac{206-134}{105-68.5}(V-68.5),\qquad P(130)=255.3\,\mathrm{N}.
\]

This matches choice A and the printed key. **Key check:** A.

### Q42 — D · 142.1 kPa effective pressure
At clay mid-height, depth below lake surface is \(z=3+6+5=14\) m. Inputs: water layer 3 m, saturated sand 6 m at \(25\,\mathrm{kN/m^3}\), and clay above midpoint 5 m at \(20\,\mathrm{kN/m^3}\). Total vertical stress is

\[
\sigma_v=9.81(3)+25(6)+20(5)=279.43\,\mathrm{kPa}.
\]

Hydrostatic pore pressure at depth \(z=14\) m is \(u=9.81(14)=137.34\) kPa. Therefore,

\[
\sigma'_v=\sigma_v-u=279.43-137.34=142.09\,\mathrm{kPa}\approx142.1\,\mathrm{kPa}.
\]

**Key check:** D.

### Q43 — C · 137.4 kPa pore pressure
Using the same explicit geometry, clay midpoint is \(3+6+5=14\) m below the lake surface. With a continuous hydrostatic water column,

\[
u=\gamma_wz=9.81(14)=137.34\,\mathrm{kPa}\approx137.4\,\mathrm{kPa}.
\]

**Key check:** C.

### Q44 — C · 279.4 kPa total pressure
Sum total overburden from all layers above the clay midpoint: water \(3\) m, saturated sand \(6\) m at \(25\,\mathrm{kN/m^3}\), and clay \(5\) m at \(20\,\mathrm{kN/m^3}\).

\[
\sigma_v=9.81(3)+25(6)+20(5)=279.43\,\mathrm{kPa}\approx279.4\,\mathrm{kPa}.
\]

**Key check:** C. The corresponding effective and pore pressures satisfy \(279.43=142.09+137.34\) kPa.

### Q45 — B · 198.8 kPa
Use the problem's stated Westergaard equations with \(Q=2.5\,\mathrm{MN}=2500\,\mathrm{kN}\), \(z=2\) m, and \(r=0\). Thus \(N=1/[1+2(0/2)^2]^{1.5}=1\).

\[
P=\frac{0.318QN}{z^2}=\frac{0.318(2500)(1)}{2^2}=198.75\,\mathrm{kPa}\approx198.8\,\mathrm{kPa}.
\]

**Key check:** B.

### Q46 — C · 49.7 kPa
Twice the first depth means \(z=4\) m; the point remains directly below the load, so \(r=0,N=1\). Same \(Q=2500\) kN:

\[
P=\frac{0.318(2500)}{4^2}=49.6875\,\mathrm{kPa}\approx49.7\,\mathrm{kPa}.
\]

**Key check:** C.

### Q47 — A · 12.02 kPa
Use \(z=6\) m, \(r=3\) m, \(Q=2500\) kN. The influence term is

\[
N=\frac{1}{\left[1+2\left(\frac{3}{6}\right)^2\right]^{1.5}}=0.5443.
\]

Then

\[
P=\frac{0.318(2500)(0.5443)}{6^2}=12.02\,\mathrm{kPa}.
\]

**Key check:** A.

[Back to the CE REF coverage index](ce-ref.html).
