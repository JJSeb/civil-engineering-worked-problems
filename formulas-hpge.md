# HPGE Formula Reference

Hydraulics, hydrology, water supply, and geotechnical engineering

This is a compact, equation-first reference. Check units, datum, sign convention, flow regime, soil drainage condition, and stated assumptions before substituting. A formula does not replace a free-body diagram, flow profile, or soil profile.

## 1. Common notation and unit conventions

- \(g\): gravitational acceleration, commonly \(9.81\,\mathrm{m/s^2}\).
- \(\rho\): mass density, \(\mathrm{kg/m^3}\); \(\gamma=\rho g\): unit weight, \(\mathrm{N/m^3}\) or \(\mathrm{kN/m^3}\).
- For water near ordinary temperatures, use the problem's specified values; common approximations are \(\rho_w=1000\,\mathrm{kg/m^3}\) and \(\gamma_w=9.81\,\mathrm{kN/m^3}\).
- \(p\): pressure, \(\mathrm{Pa=N/m^2}\); \(1\,\mathrm{kPa}=1\,\mathrm{kN/m^2}\). Pressure head is \(p/\gamma\), in metres of the referenced fluid.
- \(Q\): volumetric flow rate, \(\mathrm{m^3/s}\); \(\dot m=\rho Q\): mass flow rate. \(A\): area; \(V\): volume; \(v\) or \(U\): mean/particle speed as context specifies.
- \(z\): elevation above a selected datum. Gauge pressure is relative to local atmospheric pressure; absolute pressure is \(p_{abs}=p_{gauge}+p_{atm}\).
- \(SG=\rho/\rho_w=\gamma/\gamma_w\): specific gravity relative to water. Use consistent force and mass units; mass is not weight.
- In soil mechanics, stresses and unit weights are often reported in \(\mathrm{kPa}\) and \(\mathrm{kN/m^3}\); lengths must still be consistent when calculating volume or permeability.

## 2. Fluid properties

### Density, unit weight, and specific gravity

\[
\rho=\frac{m}{V},\qquad \gamma=\frac{W}{V}=\rho g,\qquad SG=\frac{\rho}{\rho_w}=\frac{\gamma}{\gamma_w}
\]

Here \(m\) is mass and \(W=mg\) is weight. For a mixture, density is total mass divided by total volume; do not average specific gravities unless the volume/mass basis justifies it.

### Viscosity

\[
\tau=\mu\frac{du}{dy},\qquad \nu=\frac{\mu}{\rho}
\]

For a Newtonian fluid, shear stress \(\tau\) is proportional to the velocity gradient normal to the layer. \(\mu\) is dynamic viscosity (Pa·s), and \(\nu\) is kinematic viscosity \(\mathrm{m^2/s}\). Viscosity depends on temperature.

### Compressibility and bulk modulus

\[
K=-V\frac{dp}{dV}=\rho\frac{dp}{d\rho},\qquad \Delta V\approx-\frac{V\,\Delta p}{K}
\]

The bulk modulus \(K\) is positive for compression. The linear approximation is for small pressure changes and approximately constant \(K\).

### Surface tension and capillarity

\[
\Delta p=\sigma\left(\frac{1}{R_1}+\frac{1}{R_2}\right),\qquad h_c=\frac{4\sigma\cos\theta}{\rho g d}
\]

The first relation is the Young–Laplace pressure jump across a curved interface; \(R_1,R_2\) are principal radii and \(\sigma\) is surface tension. The capillary rise/depression \(h_c\) is for a circular tube of diameter \(d\), wetting angle \(\theta\), and static meniscus. Positive \(h_c\) denotes rise when \(\cos\theta>0\).

### Vapor pressure

Vapor pressure \(p_v\) is the saturation pressure at the fluid temperature. Cavitation can occur where local absolute pressure approaches \(p_v\); compare absolute pressures, not gauge pressures.

## 3. Hydrostatics

### Pressure variation in a static fluid

\[
\frac{dp}{dz}=-\rho g=-\gamma,\qquad p_2-p_1=\gamma(z_1-z_2)
\]

For a constant-density fluid, pressure increases linearly with depth. At depth \(h\) below a free surface exposed to atmosphere, \(p_g=\gamma h\). In layered immiscible fluids, sum \(\gamma_i\Delta h_i\) across each layer. Pressure is continuous across an interface; the pressure gradient changes with density.

### Manometers

For any connected static manometer, move from a known pressure point to the target: add \(\gamma_i\Delta h_i\) when moving downward in fluid \(i\), subtract it when moving upward. Equate pressures at the same elevation within the same continuous fluid. This pressure-step method works for multiple fluids and avoids memorizing a single sign-sensitive layout formula.

### Resultant on a plane surface

\[
F_R=\gamma h_c A,\qquad h_{cp}=h_c+\frac{I_G\sin^2\theta}{A h_c}
\]

For a plane area fully or partly submerged in a static homogeneous liquid, \(h_c\) is the vertical depth of its area centroid, \(A\) is area, \(I_G\) is the second moment of area about the centroidal axis in the plane and parallel to the free surface, and \(\theta\) is the angle between the plate and the horizontal free surface. \(h_{cp}\) is the vertical depth of center of pressure. For a vertical plate \(\theta=90^\circ\); for a horizontal plate the pressure is uniform and \(h_{cp}=h_c\). The resultant acts normal to the surface.

For a plane inclined at angle \(\theta\), distance along the plane from the free-surface intersection to the pressure center is \(s_{cp}=s_c+I_G/(A s_c)\), where \(s_c\) is the centroid distance along the plate. Use the actual wetted shape for \(A\), centroid, and \(I_G\).

### Curved surfaces

\[
F_H=\text{hydrostatic force on the vertical projection},\qquad F_V=\text{weight of the imaginary fluid above the curved surface}
\]

Resolve horizontal and vertical components separately; their lines of action pass through the corresponding projected-area pressure center and the centroid of the imaginary fluid volume, respectively. Then \(F_R=\sqrt{F_H^2+F_V^2}\) and \(\tan\alpha=F_V/F_H\). Choose the imaginary-fluid volume and vertical-force sign from a free-body diagram.

### Buoyancy and flotation

\[
F_B=\rho_f gV_{disp}=\gamma_f V_{disp},\qquad W_{body}=F_B\quad\text{(floating equilibrium)}
\]

The buoyant force acts upward through the centroid of displaced fluid (center of buoyancy). For a homogeneous floating body in one liquid, \(V_{sub}/V=SG_{body}/SG_{liquid}\). For a fully submerged body, apparent weight is \(W_{app}=W-F_B\). A body floats if its average density is below the liquid density.

### Floating-body stability

\[
BM=\frac{I_{wp}}{V_{disp}},\qquad GM=KB+BM-KG,\qquad M_R\approx W(GM)\sin\phi
\]

For a small angular heel \(\phi\), \(I_{wp}\) is the second moment of the waterplane area about the heel axis; \(B\), \(M\), and \(G\) are centers of buoyancy, metacenter, and gravity. Positive \(GM\) gives initial static stability. The righting-moment approximation assumes small heel and an unchanged waterplane regime.

## 4. Relative equilibrium

Relative equilibrium means fluid has no motion relative to a translating or rotating container. Use effective body acceleration in the fluid momentum balance.

### Container with constant translational acceleration

For \(x\) horizontal and \(z\) upward, container acceleration components \(a_x,a_z\):

\[
\frac{\partial p}{\partial x}=-\rho a_x,\qquad \frac{\partial p}{\partial z}=-\rho(g+a_z),\qquad \frac{dz_s}{dx}=-\frac{a_x}{g+a_z}
\]

The free surface \(z_s\) is planar if acceleration is constant and \(g+a_z\ne0\). In an elevator accelerating upward, pressure change over depth \(h\) is \(\Delta p=\rho(g+a_z)h\); when accelerating downward, replace \(g+a_z\) accordingly. The fluid may lose contact with the container if effective gravity becomes zero or reverses.

### Rigid-body rotation about a vertical axis

\[
\frac{\partial p}{\partial r}=\rho\omega^2r,\qquad \frac{\partial p}{\partial z}=-\rho g,\qquad z_s(r)-z_s(0)=\frac{\omega^2r^2}{2g}
\]

Here \(\omega\) is constant angular speed. The free surface is a paraboloid. The relation assumes steady rigid-body rotation and a connected liquid surface; use volume conservation and vessel geometry to locate the free surface.

## 5. Hydrodynamics

### Continuity

\[
\dot m=\rho AV=\text{constant},\qquad Q=AV,\qquad A_1V_1=A_2V_2\quad\text{(incompressible, steady)}
\]

For a control volume, conservation of mass is \(\frac{d}{dt}\int_{CV}\rho\,dV+\int_{CS}\rho\mathbf V\cdot\mathbf n\,dA=0\). For one-dimensional average flow, \(V\) denotes section-average velocity.

### Bernoulli and energy equation

\[
\frac{p_1}{\gamma}+\alpha_1\frac{V_1^2}{2g}+z_1+h_p-h_t
=\frac{p_2}{\gamma}+\alpha_2\frac{V_2^2}{2g}+z_2+h_L
\]

Heads are in metres of flowing fluid. \(h_p\) is pump head added, \(h_t\) is turbine head removed, \(h_L\) is total head loss, and \(\alpha\) corrects kinetic-energy flux (often near 1 for turbulent flow; \(\alpha=2\) for fully developed laminar pipe flow). This steady-flow energy equation is for incompressible flow between sections; include machines and losses. The ideal Bernoulli equation follows when \(h_p=h_t=h_L=0\), and is commonly applied along a streamline to inviscid flow.

### Linear momentum and jet forces

\[
\sum\mathbf F=\dot m(\mathbf V_{out}-\mathbf V_{in})
\]

For steady one-inlet/one-outlet flow with uniform section velocities, this is the control-volume linear-momentum equation. Include pressure, weight, support, and reaction forces with consistent vector signs. For a jet striking a stationary flat plate normally and leaving with no normal velocity, the force magnitude is approximately \(F=\rho QV\); actual force depends on the outgoing velocity components.

### Orifices and nozzles

\[
V_{ideal}=\sqrt{2gH},\qquad Q=C_dA_o\sqrt{2gH},\qquad C_d=C_cC_v
\]

For a small sharp-edged orifice discharging from a large reservoir to atmosphere, \(H\) is the free-surface-to-orifice head, \(A_o\) is opening area, and \(C_d\) is discharge coefficient. The ideal velocity neglects losses; coefficients account for contraction and velocity effects. For a large vertical opening, integrate the depth-varying velocity or use the appropriate integrated relation.

### Dimensionless flow parameters

\[
Re=\frac{VD}{\nu},\qquad Fr=\frac{V}{\sqrt{gL}},\qquad We=\frac{\rho V^2L}{\sigma}
\]

Use a characteristic length \(D\) (pipe diameter for pipe flow) in Reynolds number, and the relevant depth or hydraulic depth \(L\) in Froude number. These compare inertial effects with viscous, gravity, and surface-tension effects, respectively. For circular pipes, laminar flow is generally \(Re\lesssim2300\), turbulent flow generally \(Re\gtrsim4000\); the transition range is not sharply predictable.

## 6. Pipe flow

### Pipe geometry and discharge

\[
A=\frac{\pi D^2}{4},\qquad Q=AV,\qquad R_h=\frac{A}{P}=\frac{D}{4}\quad\text{(full circular pipe)}
\]

Here \(D\) is inside diameter, \(P\) wetted perimeter, and \(R_h\) hydraulic radius.

### Darcy–Weisbach loss

\[
h_f=f\frac{L}{D}\frac{V^2}{2g},\qquad \Delta p_f=\rho g h_f
\]

This is the Darcy friction factor \(f\) (not the Fanning factor), for steady fully developed pipe flow. \(L\) is pipe length. In laminar circular-pipe flow \(f=64/Re\). In turbulent flow determine \(f\) from Moody chart/Colebrook or a stated approximation, using relative roughness \(\epsilon/D\).

### Minor losses and total system head

\[
h_m=K_L\frac{V^2}{2g},\qquad h_L=\sum h_f+\sum h_m
\]

Each loss coefficient \(K_L\) corresponds to its fitting, entrance, exit, valve, or area change and the associated reference velocity. Do not double-count a component when a tabulated equivalent length is used.

### Pipes in series and parallel

- Series: same \(Q\) through each segment; total head loss is the sum of segment losses.
- Parallel branches between common junctions: equal head loss between the junctions; branch discharges sum to total discharge.
- For a circular pipe with Darcy–Weisbach and constant \(f\), \(h_f\propto LQ^2/D^5\). This proportionality is not exact if \(f\) changes appreciably with Reynolds number or roughness.

### Hydraulic power

\[
P_{hyd}=\rho gQH,\qquad P_{shaft}=\frac{\rho gQH}{\eta}
\]

Here \(H\) is pump head and \(\eta\) is pump/motor efficiency appropriate to the requested shaft or input power. Use SI units to obtain watts.

### Water hammer (rapid valve change)

\[
\Delta p=\rho a\Delta V,\qquad \Delta H=\frac{a\Delta V}{g}
\]

Joukowsky's relation gives the ideal pressure/head rise for a sufficiently rapid change in velocity; \(a\) is pressure-wave speed. Pipe elasticity, air, closure time, and system reflections can change the actual transient.

## 7. Open-channel flow

### Section properties and basic relations

\[
Q=AV,\qquad R_h=\frac{A}{P},\qquad D_h=\frac{A}{T},\qquad Fr=\frac{V}{\sqrt{gD_h}}
\]

Here \(P\) is wetted perimeter, \(T\) is top width, and \(D_h\) is hydraulic depth. Subcritical flow has \(Fr<1\), critical flow \(Fr=1\), and supercritical flow \(Fr>1\). For a rectangular channel, \(D_h=y\), the flow depth.

### Uniform-flow equations

\[
V=C\sqrt{R_hS_f},\qquad V=\frac{1}{n}R_h^{2/3}S_f^{1/2},\qquad Q=AV
\]

The first is Chezy's equation and the second Manning's equation in SI form. \(S_f\) is energy/friction slope (equal to bed slope for uniform flow), \(C\) is Chezy coefficient, and \(n\) is Manning roughness. Manning's customary US-unit constant differs; use the version matching units. These empirical relations assume approximately steady, uniform flow and suitable roughness characterization.

### Specific energy and critical flow

\[
E=y+\alpha\frac{V^2}{2g}=y+\alpha\frac{Q^2}{2gA^2}
\]

Specific energy \(E\) is measured above the channel bed. At critical flow, \(Q^2T/(gA^3)=1\) when \(\alpha\approx1\). For a rectangular channel:

\[
y_c=\left(\frac{q^2}{g}\right)^{1/3},\qquad E_c=\frac{3}{2}y_c,\qquad q=\frac{Q}{b}
\]

Here \(b\) is channel width and \(q\) is discharge per unit width. The last relation assumes a rectangular prismatic channel and negligible velocity-distribution correction.

### Energy and momentum in a channel

\[
z_1+y_1+\alpha_1\frac{V_1^2}{2g}=z_2+y_2+\alpha_2\frac{V_2^2}{2g}+h_L
\]

The specific-force (momentum) function for a prismatic channel section is

\[
M=\frac{Q^2}{gA}+A\bar y
\]

where \(\bar y\) is the depth of the section centroid below the free surface. Across a short hydraulic jump, bed elevation is unchanged and losses may be large, but momentum is often approximately conserved: \(M_1=M_2\). For a rectangular channel with \(Fr_1>1\):

\[
\frac{y_2}{y_1}=\frac{1}{2}\left(\sqrt{1+8Fr_1^2}-1\right)
\]

This sequent-depth relation assumes a horizontal rectangular channel and hydrostatic pressure distributions on both sides.

## 8. Hydrology

### Water balance and rainfall depth

\[
P=ET+R+\Delta S
\]

Over a defined basin and time period, precipitation \(P\) is balanced by evapotranspiration \(ET\), total runoff/outflow \(R\), and change in storage \(\Delta S\), subject to any imports/exports and measurement conventions. A rainfall depth \(d\) over area \(A\) gives volume \(V=dA\) when \(d\) is in metres.

### Rainfall intensity and runoff coefficient

\[
i=\frac{d}{t},\qquad C_r=\frac{R_d}{P_d}
\]

Rainfall intensity \(i\) is depth per duration (often \(\mathrm{mm/h}\)); \(C_r\) is an event runoff coefficient relating runoff depth to rainfall depth under a simplified event model. It depends on land cover, soil, slope, antecedent moisture, and storm duration.

### Rational method for peak discharge

\[
Q_p=C_r iA
\]

In SI units, if \(i\) is in mm/h and \(A\) in hectares, \(Q_p=0.00278C_riA\) in \(\mathrm{m^3/s}\). The method estimates peak runoff for a small catchment when rainfall intensity is approximately uniform over the area and sustained for at least the time of concentration; it does not directly give a runoff hydrograph or event volume.

### Runoff hydrograph and unit hydrograph

\[
V_R=\int Q(t)\,dt,\qquad Q_{direct}(t)=P_e*U(t)
\]

The area under a direct-runoff hydrograph is runoff volume. \(P_e\) is effective rainfall and \(U(t)\) is the unit hydrograph; the convolution relation assumes linearity and time invariance over the application period. Keep rainfall-excess duration and unit-hydrograph duration consistent.

### Population and water-demand projections

Arithmetic increase:

\[
P_n=P_0+nI_a
\]

Geometric increase:

\[
P_n=P_0(1+r)^n
\]

Incremental increase (constant average first difference \(I_a\) and average second difference \(I_d\)):

\[
P_n=P_0+nI_a+\frac{n(n+1)}{2}I_d
\]

Here \(P_0\) is current population, \(n\) is the number of projection periods, \(I_a\) is average increase per period, \(r\) is fractional growth per period, and \(I_d\) is average incremental increase. Projection methods are empirical; compare more than one method and follow the specified planning horizon and jurisdictional criteria.

## 9. Water supply and distribution

### Demand and design flow

\[
Q_{avg}=\frac{Pq_d}{86400},\qquad Q_{max,d}=K_dQ_{avg},\qquad Q_{max,h}=K_hQ_{avg}
\]

With \(P\) persons and per-capita demand \(q_d\) in L/person/day, \(Q_{avg}\) is in L/s. \(K_d\) and \(K_h\) are the applicable maximum-day and peak-hour factors. Use locally specified demand, losses, fire flow, and design criteria; peak factors are not universal constants.

### Storage accounting

\[
V_{useful}=V_{equalization}+V_{fire}+V_{emergency}
\]

This is a planning decomposition, not a universal sizing formula. Equalization storage is found from the cumulative difference between supply and demand over time; avoid adding components that a governing standard treats as overlapping or unavailable simultaneously.

### Distribution hydraulics and pumps

Use continuity at junctions and the pipe energy equation with Darcy–Weisbach and minor losses (Section 6). For a pump between suction and discharge sections, pump head is the rise in total head, including pressure, velocity, and elevation heads and any losses. Hydraulic pump power is \(P=\rho gQH\); divide by overall efficiency to obtain required input power.

### Pump affinity laws (same pump, similar operating regime)

\[
\frac{Q_2}{Q_1}=\frac{N_2}{N_1},\qquad
\frac{H_2}{H_1}=\left(\frac{N_2}{N_1}\right)^2,\qquad
\frac{P_2}{P_1}=\left(\frac{N_2}{N_1}\right)^3
\]

Here \(N\) is rotational speed. These approximate similarity relations assume the same impeller diameter and fluid, and operation in a comparable region; actual system operating point is set by intersection of pump and system curves.

## 10. Soil mechanics

### 10.1 Phase relations

For a soil element, let \(V_s,V_w,V_a\) denote volumes of solids, water, and air; \(V_v=V_w+V_a\) is void volume and \(V=V_s+V_v\). Let \(W_s,W_w\) be weights of solids and water (air weight is neglected).

\[
 e=\frac{V_v}{V_s},\quad n=\frac{V_v}{V}=\frac{e}{1+e},\quad S_r=\frac{V_w}{V_v},\quad w=\frac{W_w}{W_s}
\]

\[
S_re=wG_s,\qquad G_s=\frac{\rho_s}{\rho_w}
\]

Here \(e\) is void ratio, \(n\) porosity, \(S_r\) degree of saturation (fraction), \(w\) water content (fraction), and \(G_s\) solids specific gravity. The identity \(S_re=wG_s\) follows from the phase definitions.

\[
\gamma=\frac{W}{V}=\frac{G_s+S_re}{1+e}\gamma_w,\quad
\gamma_d=\frac{W_s}{V}=\frac{G_s}{1+e}\gamma_w,\quad
\gamma_{sat}=\frac{G_s+e}{1+e}\gamma_w
\]

For saturated soil, \(S_r=1\) and \(w=e/G_s\). Buoyant/submerged unit weight for saturated soil is \(\gamma'=\gamma_{sat}-\gamma_w\). Do not use saturated unit weight above the groundwater table unless the soil is saturated there.

### 10.2 Index and consistency relations

\[
I_P=w_L-w_P,\qquad I_L=\frac{w-w_P}{I_P},\qquad I_C=\frac{w_L-w}{I_P}=1-I_L
\]

Here \(w_L,w_P\) are liquid and plastic limits, \(I_P\) plasticity index, \(I_L\) liquidity index, and \(I_C\) consistency index. Limits and water content must use the same percentage/fraction convention. These consistency indices apply to fine-grained soils with defined Atterberg limits.

### 10.3 Permeability and seepage

Darcy's law for saturated laminar flow through soil:

\[
Q=kiA,\qquad v_D=\frac{Q}{A}=ki,\qquad v_s=\frac{v_D}{n}
\]

Here \(k\) is hydraulic conductivity, \(i=\Delta h/L\) hydraulic gradient, \(A\) gross cross-sectional area normal to flow, \(v_D\) Darcy/discharge velocity, and \(v_s\) average seepage velocity through voids. For saturated soil flow, Darcy's law is generally valid at low pore velocities; \(k\) depends on both soil and fluid.

Constant-head test:

\[
k=\frac{QL}{A\Delta h}=\frac{V_wL}{At\Delta h}
\]

Falling-head test:

\[
k=\frac{aL}{At}\ln\left(\frac{h_1}{h_2}\right)
\]

Here \(L\) and \(A\) describe the specimen, \(a\) is standpipe area, \(t\) is elapsed time, and \(h_1,h_2\) are initial and final head differences. Use consistent units and a representative saturated specimen.

Equivalent conductivity for horizontal layering (flow parallel to layers):

\[
k_h=\frac{\sum k_iH_i}{\sum H_i}
\]

For vertical flow normal to horizontal layers:

\[
k_v=\frac{\sum H_i}{\sum(H_i/k_i)}
\]

Here \(H_i,k_i\) are layer thickness and conductivity. These are idealized steady saturated results for continuous layers.

For a flow net, approximate discharge per unit width through a homogeneous isotropic soil mass:

\[
q=kH\frac{N_f}{N_d}
\]

Here \(H\) is total head loss, \(N_f\) number of flow channels, and \(N_d\) number of potential drops. The relation assumes a properly drawn curvilinear-square net and two-dimensional seepage.

### 10.4 Total, pore-water, and effective stress

\[
\sigma'=\sigma-u,\qquad u=\gamma_w h_p
\]

Terzaghi's effective-stress relation applies to saturated soil under the usual soil-mechanics assumptions. \(\sigma\) is total normal stress, \(u\) pore-water pressure, \(\sigma'\) effective normal stress, and \(h_p\) pressure head above the point. In a hydrostatic profile, pore pressure is zero at the water table and increases by \(\gamma_w\) times depth below it.

For horizontal soil layers, vertical total stress at depth \(z\) is

\[
\sigma_v=\sum_i\gamma_iH_i+q
\]

where \(H_i\) is thickness above the point, \(\gamma_i\) the applicable moist or saturated unit weight, and \(q\) an applied uniform surcharge. For saturated layers below the water table, calculate \(\sigma'_v\) either as \(\sigma_v-u\) or sum the buoyant unit weights below the water table plus moist weights above; the two methods should agree.

### 10.5 Consolidation and settlement

One-dimensional primary consolidation settlement of a normally consolidated clay layer:

\[
S_c=\frac{C_cH}{1+e_0}\log_{10}\left(\frac{\sigma'_0+\Delta\sigma'}{\sigma'_0}\right)
\]

For overconsolidated clay that remains below preconsolidation stress:

\[
S_c=\frac{C_rH}{1+e_0}\log_{10}\left(\frac{\sigma'_0+\Delta\sigma'}{\sigma'_0}\right)
\]

If final stress exceeds preconsolidation stress \(\sigma'_p\):

\[
S_c=\frac{H}{1+e_0}\left[C_r\log_{10}\left(\frac{\sigma'_p}{\sigma'_0}\right)+C_c\log_{10}\left(\frac{\sigma'_0+\Delta\sigma'}{\sigma'_p}\right)\right]
\]

Here \(H\) is compressible layer thickness, \(e_0\) initial void ratio, \(C_c\) compression index, \(C_r\) recompression/swelling index, \(\sigma'_0\) initial effective vertical stress at the representative layer depth, and \(\Delta\sigma'\) stress increase. Use base-10 logarithms as defined for these indices. These formulas assume one-dimensional primary consolidation and a suitable representative stress increment; divide thick layers into sublayers when stress varies materially with depth.

\[
T_v=\frac{c_vt}{H_{dr}^2},\qquad S_t=U S_{final}
\]

Here \(T_v\) is time factor, \(c_v\) coefficient of consolidation, \(H_{dr}\) longest drainage path, \(U\) average degree of consolidation (fraction), and \(S_t\) settlement at time \(t\). For 0–about 60% consolidation, \(T_v\approx\frac{\pi}{4}U^2\); for higher \(U\), \(T_v\approx-0.933\log_{10}(1-U)-0.085\). Single drainage uses \(H_{dr}=H\); double drainage uses \(H_{dr}=H/2\) for a uniform layer drained at top and bottom.

### 10.6 Compaction

\[
\gamma_d=\frac{\gamma}{1+w},\qquad \gamma_{d,max}=\text{maximum dry unit weight at }w_{opt}
\]

Here \(w\) is water content as a decimal. The compaction curve relates dry unit weight to molding water content for a specified compactive effort; \(w_{opt}\) and \(\gamma_{d,max}\) are test-dependent, not intrinsic constants.

Zero-air-voids (theoretical full-saturation) line:

\[
\gamma_{d,ZAV}=\frac{G_s\gamma_w}{1+wG_s}
\]

Actual compaction points should lie below this ideal line. Relative compaction is

\[
RC=\frac{\gamma_{d,field}}{\gamma_{d,max,lab}}\times100\%
\]

Compare field and laboratory values using the specified test method and correction for oversize particles when applicable.

### 10.7 Shear strength

Mohr–Coulomb failure criterion:

\[
\tau_f=c'+\sigma'_n\tan\phi'
\]

For drained/effective-stress analysis, \(c'\) is effective cohesion, \(\sigma'_n\) is effective normal stress on the plane, and \(\phi'\) is effective friction angle. For a total-stress undrained analysis of saturated clay, a common \(\phi=0\) idealization is \(\tau_f=s_u=c_u\); use the test-appropriate total-stress parameters and do not mix total and effective stress parameters.

Mohr circle for principal stresses \(\sigma_1\ge\sigma_3\):

\[
\sigma_{avg}=\frac{\sigma_1+\sigma_3}{2},\qquad R=\frac{\sigma_1-\sigma_3}{2}
\]

At failure under Mohr–Coulomb conditions, the triaxial-compression relation is

\[
\sigma'_1=\sigma'_3\frac{1+\sin\phi'}{1-\sin\phi'}+\frac{2c'\cos\phi'}{1-\sin\phi'}
\]

For cohesionless soil, \(c'=0\). Here compression is taken positive and stresses are effective for the primed equation. Select drained or undrained parameters consistent with drainage and loading time.

### 10.8 Lateral earth pressure (basic limit states)

For level backfill, vertical smooth wall, homogeneous cohesionless soil, and Rankine assumptions:

\[
K_a=\tan^2\left(45^\circ-\frac{\phi'}{2}\right),\qquad
K_p=\tan^2\left(45^\circ+\frac{\phi'}{2}\right),\qquad K_0\approx1-\sin\phi'
\]

Active and passive limiting lateral effective stresses at depth \(z\) are \(\sigma'_{h,a}=K_a\sigma'_v\) and \(\sigma'_{h,p}=K_p\sigma'_v\). At-rest \(K_0\) is an approximate relation for normally consolidated soil; overconsolidation and stress history matter. Add hydrostatic water pressure separately to total lateral pressure.

For a vertical wall retaining level cohesionless backfill of height \(H\), with uniform surcharge \(q\):

\[
P_a=\frac12K_a\gamma'H^2+K_aqH
\]

The triangular soil-weight component acts \(H/3\) above the base; the uniform-surcharge component acts \(H/2\) above the base. Use submerged unit weight \(\gamma'\) below groundwater and add water pressure independently. This expression excludes wall friction, sloping backfill, cohesion, and layered-soil complications.

## 11. Calculation checks

- Draw the geometry and state the datum before using pressure, energy, stress, or settlement equations.
- Distinguish mass density from unit weight, gauge pressure from absolute pressure, total stress from effective stress, and Darcy velocity from seepage velocity.
- Convert water content and saturation percentages to fractions when substituted into phase equations.
- Check whether a relation assumes steady, uniform, incompressible, fully developed, saturated, drained, undrained, or small-deformation behavior.
- Preserve significant figures through the calculation; round only the reported result and keep units attached.
