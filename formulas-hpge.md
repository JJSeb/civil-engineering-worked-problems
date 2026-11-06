# HPGE Formula Sheet

**Hydraulics · Hydrology · Soil Mechanics**

Core topics covered: fluid properties, hydrostatics, flow, buoyancy, relative equilibrium, hydrodynamics, basic water supply, hydrology, and soil properties, classification, seepage, stresses, and compaction. Use the problem's units, assumptions, and prescribed constants.

**Scope note.** Specialized Water Resources Engineering design, including network and treatment-plant design, pump selection, and storage design, is outside this core sheet. Foundation bearing capacity, slope stability, lateral earth pressure, shear-strength design, and consolidation are also omitted. Coverage of rotational relative equilibrium, advanced open-channel relations, water hammer, and unit-hydrograph methods varies by syllabus; confirm whether these are included.

## 1. Notation and units

- \(g\): gravitational acceleration; commonly \(9.81\,\mathrm{m/s^2}\).
- \(\rho\): mass density, \(\mathrm{kg/m^3}\). \(\gamma=\rho g\): unit weight, usually \(\mathrm{kN/m^3}\).
- Water: use specified values; common approximations are \(\rho_w=1000\,\mathrm{kg/m^3}\) and \(\gamma_w=9.81\,\mathrm{kN/m^3}\).
- \(p\): pressure; \(1\,\mathrm{kPa}=1\,\mathrm{kN/m^2}\). Pressure head is \(p/\gamma\).
- \(Q\): volumetric flow, \(\mathrm{m^3/s}\). \(A\): area. \(V\): mean speed in flow equations; volume when used as a volume symbol.
- \(z\): elevation above a chosen datum. \(h\): depth or head as defined in each section.
- \(SG=\rho/\rho_w=\gamma/\gamma_w\): specific gravity. Mass and weight are different quantities.
- Soil \(w,S_r,n\) are fractions in equations unless a percent sign is shown.

## 2. Fluid properties

### Density, unit weight, specific gravity

\[
\rho=\frac{m}{\mathcal V}
\]

\[
\gamma=\frac{W}{\mathcal V}=\rho g
\]

\[
SG=\frac{\rho}{\rho_w}=\frac{\gamma}{\gamma_w}
\]

Here \(m\) is mass, \(W=mg\) is weight, and \(\mathcal V\) is volume.

### Viscosity

\[
\tau=\mu\frac{du}{dy}
\]

\[
\nu=\frac{\mu}{\rho}
\]

For a Newtonian fluid, \(\tau\) is shear stress, \(\mu\) dynamic viscosity, and \(\nu\) kinematic viscosity.

### Compressibility and surface tension — syllabus check

\[
K=-\mathcal V\frac{dp}{d\mathcal V}
\]

\[
\Delta\mathcal V\approx-\frac{\mathcal V\,\Delta p}{K}
\]

\(K\) is bulk modulus; the volume-change relation is for small pressure changes and nearly constant \(K\).

\[
\Delta p=\sigma\left(\frac{1}{R_1}+\frac{1}{R_2}\right)
\]

\[
h_c=\frac{4\sigma\cos\theta}{\rho g d}
\]

The first is the pressure jump across a curved interface. The second is capillary rise or depression in a circular tube of diameter \(d\). These surface effects may be outside a particular HPGE course's tested scope.

## 3. Hydrostatics

### Pressure variation

\[
\frac{dp}{dz}=-\rho g=-\gamma
\]

\[
p_2-p_1=\gamma(z_1-z_2)
\]

For constant density, pressure increases linearly downward. At depth \(h\) below an atmospheric free surface:

\[
p_g=\gamma h
\]

For layered fluids, add \(\gamma_i\Delta h_i\) for each vertical layer. Pressure is continuous at a fluid interface.

### Manometers

Move from a known point to the unknown point: add \(\gamma_i\Delta h_i\) moving down in fluid \(i\), subtract it moving up, and equate pressure at the same elevation in the same connected fluid. This pressure-step rule handles multi-fluid manometers without a memorized sign convention.

### Hydrostatic force on a plane surface

\[
F_R=\gamma h_c A
\]

\[
h_{cp}=h_c+\frac{I_G\sin^2\theta}{A h_c}
\]

\(h_c\) is the vertical depth of the area centroid, \(A\) is wetted area, \(I_G\) is the centroidal second moment parallel to the free surface, and \(\theta\) is the plate angle from horizontal. \(h_{cp}\) is the vertical center-of-pressure depth. The resultant is normal to the plane.

For distance measured along an inclined plate from the free-surface intersection:

\[
s_{cp}=s_c+\frac{I_G}{A s_c}
\]

\(s_c\) is the centroid distance along the plate. For a horizontal surface, pressure is uniform and the resultant acts through its centroid.

### Curved surfaces

\[
F_H=\text{force on the vertical projection}
\]

\[
F_V=\text{weight of the imaginary fluid above the surface}
\]

Resolve horizontal and vertical components, then combine:

\[
F_R=\sqrt{F_H^2+F_V^2}
\]

\[
\tan\alpha=\frac{F_V}{F_H}
\]

Use a free-body diagram to set the vertical-force direction and imaginary-fluid volume.

## 4. Buoyancy and relative equilibrium

### Buoyancy and flotation

\[
F_B=\rho_f g\mathcal V_{disp}=\gamma_f\mathcal V_{disp}
\]

\[
W_{body}=F_B \qquad (\text{floating equilibrium})
\]

The buoyant force acts through the centroid of displaced fluid. For a homogeneous body floating in one liquid:

\[
\frac{\mathcal V_{sub}}{\mathcal V_{body}}
=\frac{SG_{body}}{SG_{liquid}}
\]

For a fully submerged body, apparent weight is:

\[
W_{app}=W-F_B
\]

### Floating-body initial stability — syllabus check

\[
BM=\frac{I_{wp}}{\mathcal V_{disp}}
\]

\[
GM=KB+BM-KG
\]

Positive \(GM\) indicates initial static stability. \(I_{wp}\) is waterplane second moment about the heel axis; \(B,M,G\) denote buoyancy center, metacenter, and gravity center. This topic may not be in every HPGE preboard scope.

### Translating container

For horizontal \(x\), upward \(z\), and container acceleration \((a_x,a_z)\):

\[
\frac{\partial p}{\partial x}=-\rho a_x
\]

\[
\frac{\partial p}{\partial z}=-\rho(g+a_z)
\]

\[
\frac{dz_s}{dx}=-\frac{a_x}{g+a_z}
\]

The free surface is planar for constant acceleration and \(g+a_z\ne0\). Over depth \(h\), pressure change is \(\Delta p=\rho(g+a_z)h\).

### Rotating container — syllabus check

For steady rigid-body rotation at angular speed \(\omega\):

\[
\frac{\partial p}{\partial r}=\rho\omega^2r
\]

\[
z_s(r)-z_s(0)=\frac{\omega^2r^2}{2g}
\]

The free surface is a paraboloid. Apply volume conservation with the vessel geometry to locate it. Check whether rotating-fluid problems are included in the course.

## 5. Hydrodynamics

### Continuity

\[
Q=AV
\]

\[
\dot m=\rho Q=\rho AV
\]

For steady incompressible flow between two sections:

\[
A_1V_1=A_2V_2
\]

### Bernoulli and energy equation

\[
\frac{p_1}{\gamma}+z_1+\alpha_1\frac{V_1^2}{2g}+h_p
=\frac{p_2}{\gamma}+z_2+\alpha_2\frac{V_2^2}{2g}+h_t+h_L
\]

Each term is head. \(h_p\) is pump head added, \(h_t\) turbine head removed, \(h_L\) loss, and \(\alpha\) the kinetic-energy correction factor. Use the ideal Bernoulli form when losses and machines are negligible; it is commonly applied along a streamline.

### Linear momentum and jet force

\[
\sum\mathbf F=\dot m\left(\mathbf V_{out}-\mathbf V_{in}\right)
\]

For a stationary flat plate that stops the incoming normal velocity of a jet:

\[
F\approx\rho QV
\]

Include pressure, weight, and support forces in the control-volume balance when relevant.

### Orifices and jets

\[
V_{ideal}=\sqrt{2gH}
\]

\[
Q=C_dA_o\sqrt{2gH}
\]

\[
C_d=C_cC_v
\]

For a small sharp-edged orifice from a large reservoir, \(H\) is free-surface-to-opening head and \(A_o\) is opening area. A large vertical opening needs integration over its changing depth head.

### Flow regime indicators

\[
Re=\frac{VD}{\nu}
\]

\[
Fr=\frac{V}{\sqrt{gL}}
\]

\(Re\) compares inertia with viscosity; \(Fr\) compares inertia with gravity. Use pipe diameter for \(D\), and flow depth or hydraulic depth for \(L\) as appropriate. Circular-pipe flow is generally laminar below about \(Re=2300\), turbulent above about \(Re=4000\), with a transition range between.

## 6. Pipe flow and basic water-supply hydraulics

### Pipe area and discharge

\[
A=\frac{\pi D^2}{4}
\]

\[
Q=AV
\]

For a full circular pipe, hydraulic radius is:

\[
R_h=\frac{A}{P}=\frac{D}{4}
\]

Here \(D\) is inside diameter and \(P\) wetted perimeter.

### Darcy–Weisbach and minor losses

\[
h_f=f\frac{L}{D}\frac{V^2}{2g}
\]

\[
\Delta p_f=\rho g h_f
\]

\(f\) is the Darcy friction factor, \(L\) pipe length. For fully developed laminar circular-pipe flow, \(f=64/Re\).

\[
h_m=K_L\frac{V^2}{2g}
\]

\[
h_L=\sum h_f+\sum h_m
\]

\(K_L\) is the loss coefficient for a fitting or other local disturbance. Use the reference velocity associated with that coefficient.

### Basic water demand

\[
Q_{avg}=\frac{Pq_d}{86400}
\]

For population \(P\) in persons and demand \(q_d\) in \(\mathrm{L/(person\,day)}\), \(Q_{avg}\) is in \(\mathrm{L/s}\). Convert consistently if using other units.

\[
Q_{peak}=K_pQ_{avg}
\]

\(K_p\) is the specified peak factor. Demand, fire-flow allowances, and design factors are local inputs, not universal constants. This is a basic demand relation, not a distribution-network design method.

### Water hammer — syllabus check

\[
\Delta p=\rho a\Delta V
\]

\[
\Delta H=\frac{a\Delta V}{g}
\]

These are ideal Joukowsky pressure/head changes for a sufficiently rapid velocity change; \(a\) is pressure-wave speed. Actual transients depend on pipe elasticity, closure time, and system reflections. Check course coverage before prioritizing this topic.

## 7. Open-channel flow

### Section properties and Froude number

\[
Q=AV
\]

\[
R_h=\frac{A}{P}
\]

\[
D_h=\frac{A}{T}
\]

\[
Fr=\frac{V}{\sqrt{gD_h}}
\]

\(P\) is wetted perimeter, \(T\) top width, and \(D_h\) hydraulic depth. Subcritical: \(Fr<1\); critical: \(Fr=1\); supercritical: \(Fr>1\). For a rectangular channel, \(D_h=y\).

### Uniform flow: Chezy and Manning

\[
V=C\sqrt{R_hS_f}
\]

\[
V=\frac{1}{n}R_h^{2/3}S_f^{1/2}
\]

\[
Q=AV
\]

\(S_f\) is friction/energy slope (equal to bed slope for uniform flow), \(C\) Chezy coefficient, and \(n\) Manning roughness. The Manning form shown is SI; use the matching form for other unit systems.

### Specific energy and critical depth

\[
E=y+\alpha\frac{V^2}{2g}
\]

\[
E=y+\alpha\frac{Q^2}{2gA^2}
\]

Specific energy \(E\) is measured above the channel bed. For a rectangular channel with \(\alpha\approx1\):

\[
q=\frac{Q}{b}
\]

\[
y_c=\left(\frac{q^2}{g}\right)^{1/3}
\]

\[
E_c=\frac{3}{2}y_c
\]

These critical-flow relations are included as general hydraulics; verify whether critical-depth problems are in the assigned preboard coverage.

## 8. Hydrology

### Catchment water balance

\[
P=ET+R+\Delta S
\]

Over a stated basin and time period, precipitation \(P\) balances evapotranspiration \(ET\), runoff/outflow \(R\), and storage change \(\Delta S\), subject to imports and other terms. Rainfall depth \(d\) over area \(A\) gives volume:

\[
\mathcal V=dA
\]

Use \(d\) in metres for volume in cubic metres.

### Rainfall intensity and runoff coefficient

\[
i=\frac{d}{t}
\]

\[
C_r=\frac{R_d}{P_d}
\]

\(i\) is average rainfall intensity over duration \(t\); \(C_r\) is event runoff depth divided by rainfall depth. Match depth and duration units.

### Rational method

\[
Q_p=C_r iA
\]

If \(i\) is in \(\mathrm{mm/h}\) and area \(A\) in hectares:

\[
Q_p=0.00278C_riA\qquad(\mathrm{m^3/s})
\]

This estimates peak discharge for a small catchment when rainfall is sufficiently uniform and lasts at least the time of concentration. It does not give the full runoff hydrograph.

### Hydrograph volume

\[
V_R=\int Q(t)\,dt
\]

The area under a direct-runoff hydrograph is runoff volume. Separate baseflow when the question asks for direct runoff.

### Unit hydrograph — syllabus check

\[
Q_{direct}(t)=P_e*U(t)
\]

\(P_e\) is effective rainfall and \(U(t)\) the unit hydrograph; \(*\) denotes convolution. This method assumes linear response and time invariance over the application. Confirm it is included before studying the method in depth.

## 9. Soil mechanics

### Phase relations

\[
V_v=V_w+V_a
\]

\[
V=V_s+V_v
\]

\[
e=\frac{V_v}{V_s}
\]

\[
n=\frac{V_v}{V}=\frac{e}{1+e}
\]

\[
S_r=\frac{V_w}{V_v}
\]

\[
w=\frac{W_w}{W_s}
\]

Here \(V_s,V_w,V_a\) are solid, water, and air volumes; \(W_s,W_w\) are their weights. Air weight is neglected.

\[
S_re=wG_s
\]

\[
G_s=\frac{\rho_s}{\rho_w}
\]

\(e\) is void ratio, \(n\) porosity, \(S_r\) degree of saturation, \(w\) water content, and \(G_s\) solids specific gravity.

### Unit weights and density

\[
\gamma=\frac{G_s+S_re}{1+e}\gamma_w
\]

\[
\gamma_d=\frac{G_s}{1+e}\gamma_w
\]

\[
\gamma_{sat}=\frac{G_s+e}{1+e}\gamma_w
\]

\[
\gamma'=\gamma_{sat}-\gamma_w
\]

\(\gamma,\gamma_d,\gamma_{sat},\gamma'\) are moist, dry, saturated, and submerged unit weights. Use \(\gamma'\) only for saturated soil below the water table.

\[
\rho_d=\frac{\rho}{1+w}
\]

\(\rho_d\) is dry density from bulk density \(\rho\); \(w\) must be a decimal.

### Soil classification and index properties

\[
I_P=w_L-w_P
\]

\[
I_L=\frac{w-w_P}{I_P}
\]

\[
I_C=\frac{w_L-w}{I_P}=1-I_L
\]

\(w_L,w_P\) are liquid and plastic limits; \(I_P\) is plasticity index, \(I_L\) liquidity index, and \(I_C\) consistency index. Use one consistent percent or fraction convention.

For a particle-size distribution curve:

\[
C_u=\frac{D_{60}}{D_{10}}
\]

\[
C_c=\frac{D_{30}^2}{D_{10}D_{60}}
\]

\(D_{10},D_{30},D_{60}\) are particle sizes at 10%, 30%, and 60% finer by mass. Gradation limits and group symbols depend on the specified classification system; use the course's USCS/AASHTO chart and fines tests rather than inferring a group from these two coefficients alone.

### Seepage and hydraulic conductivity

\[
i=\frac{\Delta h}{L}
\]

\[
Q=kiA
\]

\[
v_D=\frac{Q}{A}=ki
\]

\[
v_s=\frac{v_D}{n}
\]

\(k\) is hydraulic conductivity, \(i\) hydraulic gradient, \(A\) gross area normal to flow, \(v_D\) Darcy velocity, and \(v_s\) average seepage velocity through voids. Darcy's law applies to saturated laminar soil flow.

Constant-head test:

\[
k=\frac{QL}{A\Delta h}
\]

\[
k=\frac{V_wL}{At\Delta h}
\]

Falling-head test:

\[
k=\frac{aL}{At}\ln\left(\frac{h_1}{h_2}\right)
\]

Here \(A,L\) are specimen area and length, \(a\) is standpipe area, \(t\) elapsed time, and \(h_1,h_2\) initial and final head differences.

For horizontal layers, flow parallel to bedding:

\[
k_h=\frac{\sum k_iH_i}{\sum H_i}
\]

Flow normal to bedding:

\[
k_v=\frac{\sum H_i}{\sum(H_i/k_i)}
\]

\(H_i,k_i\) are layer thickness and conductivity.

For a two-dimensional flow net, discharge per unit width:

\[
q=kH\frac{N_f}{N_d}
\]

\(H\) is total head loss, \(N_f\) flow channels, and \(N_d\) potential drops. This assumes homogeneous isotropic soil and a properly drawn flow net.

### Total stress, pore pressure, effective stress

\[
\sigma'=\sigma-u
\]

\(\sigma\) is total normal stress, \(u\) pore-water pressure, and \(\sigma'\) effective stress for saturated soil.

Hydrostatic pore pressure below the water surface:

\[
u=\gamma_w h_p
\]

\(h_p\) is depth below the water table (pressure head).

Vertical total stress for horizontal layers:

\[
\sigma_v=\sum_i\gamma_iH_i+q
\]

\(H_i\) and \(\gamma_i\) are layer thickness and applicable moist or saturated unit weight; \(q\) is uniform surface surcharge. Then find effective stress by subtracting pore pressure. Below the water table, the equivalent submerged-weight method may be used for saturated layers.

### Compaction

\[
\gamma_d=\frac{\gamma}{1+w}
\]

Convert water content \(w\) to a decimal. A compaction curve plots dry unit weight against molding water content for a specified compactive effort.

\[
\gamma_{d,max}=\text{maximum dry unit weight}
\]

\[
w_{opt}=\text{water content at }\gamma_{d,max}
\]

These are test-dependent values, not intrinsic constants of the soil.

Zero-air-voids line (theoretical full saturation):

\[
\gamma_{d,ZAV}=\frac{G_s\gamma_w}{1+wG_s}
\]

Also written as \(\gamma_{ZAV}\), this is the theoretical dry unit weight at \(S_r=1\), for the given water content \(w\) and specific gravity of solids \(G_s\). Use \(w\) as a decimal and \(\gamma_w\) in the desired unit-weight units. The corresponding dry density is

\[
\rho_{d,ZAV}=\frac{G_s\rho_w}{1+wG_s}
\]

The measured compaction curve normally lies below the zero-air-voids line. The line is not the laboratory maximum dry unit weight: \(\gamma_{d,\max}\) comes from the compaction test.

**Other saturation levels.** For a specified degree of saturation \(S_r>0\), expressed as a decimal:

\[
\gamma_d=\frac{G_s\gamma_w}{1+\dfrac{wG_s}{S_r}}
\]

To recover saturation from measured dry unit weight and water content, first find \(e\), then use the phase relationship:

\[
e=\frac{G_s\gamma_w}{\gamma_d}-1,\qquad S_r=\frac{wG_s}{e}
\]

**Air voids.** The fraction of the total specimen volume occupied by air is \(n_a=V_a/V\):

\[
n_a=1-\frac{\gamma_d}{\gamma_w}\left(\frac{1}{G_s}+w\right)
\]

Multiply \(n_a\) by 100 for percent air voids. Do not confuse this with the air fraction of the void space, \(V_a/V_v=1-S_r\). A 10% air-voids line is therefore different from a 90% saturation line.

**Example — zero air voids.** If \(G_s=2.70\), \(w=20\%=0.20\), and \(\gamma_w=9.81\,\mathrm{kN/m^3}\):

\[
\gamma_{d,ZAV}=\frac{2.70(9.81)}{1+0.20(2.70)}
=17.20\,\mathrm{kN/m^3}
\]

At this water content, a measured dry unit weight above this value warrants checking the input values, units, and calculations.

Relative compaction:

\[
RC=\frac{\gamma_{d,field}}{\gamma_{d,max,lab}}\times100\%
\]

Compare field and laboratory values from compatible test methods; apply any specified oversize correction.

## 10. Quick checks

- Draw the geometry and set a datum before using pressure, head, or stress equations.
- Keep mass density and unit weight, gauge and absolute pressure, and total and effective stress distinct.
- Convert water content and saturation percentages to fractions before substitution.
- Check assumptions: steady or unsteady, uniform or varied, compressible or incompressible, saturated or unsaturated, and hydrostatic or flowing.
- Carry units through each step and round only the reported result.
