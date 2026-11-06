# November 2021 HPGE

## Questions 1–25

Worked solutions for all 50 November 2021 HPGE questions. Each problem includes the governing relation, substitutions, and answer; ambiguous wording or conflicting data are noted where relevant.

### 1. Pressure from a mercury manometer
**Problem 1:** A conduit containing water is connected to a U-tube manometer open to the atmosphere and containing liquid B with specific gravity 13.6. The open-side liquid level is 125 mm above the conduit tap, and the vertical separation between that level and the water–liquid interface is 375 mm. Find the pressure at the conduit tap in kPa.

<svg class="figure" viewBox="0 0 640 340" role="img" aria-labelledby="manometer-title manometer-desc" xmlns="http://www.w3.org/2000/svg">
  <title id="manometer-title">U-tube manometer connected to a water conduit</title>
  <desc id="manometer-desc">Water conduit A connects to the left leg of a U-tube containing heavy liquid B. The right leg is open to atmosphere at D. C marks the water-heavy-liquid interface; h is the level difference from A to D, and d is the heavy-liquid column between D and C.</desc>
  <rect x="54" y="55" width="165" height="105" rx="30" fill="#e4f2f8" stroke="#34495e" stroke-width="4"/>
  <text x="136" y="103" text-anchor="middle" font-size="22" fill="#243b53">water</text><text x="136" y="132" text-anchor="middle" font-size="24" fill="#243b53">A</text>
  <path d="M219 112 H292 V265 Q292 290 317 290 H412 Q437 290 437 265 V145" fill="none" stroke="#34495e" stroke-width="18" stroke-linejoin="round"/>
  <path d="M228 112 H283 V250" fill="none" stroke="#8cc8df" stroke-width="10"/>
  <path d="M301 258 V265 Q301 281 317 281 H412 Q428 281 428 265 V145" fill="none" stroke="#d7a34b" stroke-width="10"/>
  <path d="M437 145 V54" stroke="#34495e" stroke-width="4"/><text x="457" y="61" font-size="22" fill="#243b53">open</text>
  <circle cx="292" cy="250" r="7" fill="#087e8b"/><text x="253" y="242" font-size="22" fill="#243b53">C</text><text x="449" y="151" font-size="22" fill="#243b53">D</text>
  <line x1="500" y1="112" x2="500" y2="145" stroke="#243b53" stroke-width="2"/><path d="M494 120 L500 112 L506 120 M494 137 L500 145 L506 137" fill="none" stroke="#243b53" stroke-width="2"/><text x="515" y="134" font-size="21" fill="#243b53">h</text>
  <line x1="500" y1="145" x2="500" y2="250" stroke="#243b53" stroke-width="2"/><path d="M494 153 L500 145 L506 153 M494 242 L500 250 L506 242" fill="none" stroke="#243b53" stroke-width="2"/><text x="515" y="205" font-size="21" fill="#243b53">d</text>
  <text x="365" y="318" text-anchor="middle" font-size="18" fill="#72521f">liquid B (SG 13.6)</text>
</svg>

**Solution:** Starting at the open mercury surface, balance pressure down through mercury and up through water to the conduit tap:

\[
p_A=\gamma_w\left[SG_{Hg}d-(h+d)\right]
=9.81[13.6(0.375)-(0.125+0.375)]
=45.13\ \text{kPa}.
\]

**Answer: 45.13 kPa (C).**

### 2. Specific weight of floating timber
**Problem 2:** A wooden prism with a 250 mm by 250 mm cross-section and length 3.00 m floats upright in water inside a cylindrical container of diameter 1.00 m and height 5.00 m, filled to a depth of 3.00 m. Two-thirds of the timber length is above the water. Determine the timber’s specific weight in kN/m³.

**Solution:**


The timber has one-third of its length submerged. For a uniform floating body, submerged volume fraction equals the ratio of its specific weight to water's:

\[
\gamma_t=\frac{1}{3}\gamma_w=\frac{9.81}{3}=3.27\ \text{kN/m}^3.
\]

**Answer: 3.27 kN/m³ (D).**

### 3. Water compression
**Problem 3:** A 1 m³ volume of water experiences a pressure increase of 20 MPa. If water’s bulk modulus is 2,200 MPa, determine the change in volume in m³.

**Solution:**


Bulk modulus gives \(K=\Delta p/(|\Delta V|/V)\). For \(V=1\ \text{m}^3\):

\[
|\Delta V|=V\frac{\Delta p}{K}
=1\frac{20}{2200}=0.00909\ \text{m}^3.
\]

The pressure increase makes the volume decrease.

**Answer: decrease of 0.00909 m³ (B).**

### 4. New velocity head
**Problem 4:** The velocity head at one pipeline section is 5 m. At the next section, the flow velocity is 1.5 times the former velocity. Determine the new velocity head in meters.

**Solution:**


Since velocity head is proportional to velocity squared, increasing velocity by a factor of 1.5 multiplies the head by \(1.5^2\):

\[
h_{v2}=5(1.5)^2=11.25\ \text{m}.
\]

**Answer: 11.25 m (B).**

### 5. Sudden flow stoppage
**Problem 5:** In hydraulics, what is the term for a pressure surge or wave produced when moving fluid is suddenly forced to stop or change direction?

**Solution:**


A rapid change in moving water's velocity produces a pressure surge known as **water hammer**.

**Answer: water hammer (A).**

### 6. Line through open piezometer levels
**Problem 6:** What is the name of the line connecting the highest water levels in a series of vertical open pipes connected to a pressurized flowing pipeline?

**Solution:**


The line joining the elevations of liquid in open piezometer tubes is the **hydraulic grade line**.

**Answer: hydraulic grade line (D).**

### 7. Equivalent water-barometer height
**Problem 7:** At an elevation above sea level, a mercury barometer reads 700 mm. Determine the equivalent water-barometer reading in millimeters.

**Solution:**


At equal pressure, \(\gamma_{Hg}h_{Hg}=\gamma_wh_w\), so:

\[
h_w=13.6(700\ \text{mm})=9520\ \text{mm}.
\]

**Answer: 9,520 mm (C).**

### 8. Atmospheric pressure from the barometer
**Problem 8:** At the elevation where a mercury barometer reads 700 mm, determine the atmospheric pressure in kPa.

**Solution:**


\[
p_{atm}=SG_{Hg}\gamma_wh_{Hg}
=13.6(9.81)(0.700)=93.39\ \text{kPa}.
\]

**Answer: 93.4 kPa (C).**

### 9. Elevation inferred from barometer reading
**Problem 9:** At the elevation where a mercury barometer reads 700 mm, estimate the elevation above sea level under normal atmospheric conditions. Neglect vapor pressure and take the unit weight of air as 12 N/m³.

**Solution:**


The keyed method uses the local barometer pressure directly:

\[
z=\frac{93.39\ \text{kPa}}{0.012\ \text{kN/m}^3}\approx7{,}780\ \text{m}.
\]

**Answer by this method: 7,780 m (B), with a major modeling caveat.** Elevation above sea level should be estimated from the pressure difference between sea level and the site. If sea-level mercury is taken as 760 mm, the stated 700 mm reading represents a 60 mm Hg difference, or about 8.00 kPa; divided by the given air unit weight this is about 667 m. The choices do not include that result, so the keyed method is an approximation that treats local pressure as the whole air-column head.

### 10. Hydrostatic force on a triangular plate
**Problem 10:** A triangular plate 1.20 m high and 2 m wide is submerged vertically in water, with its base at and parallel to the liquid surface. Determine the total hydrostatic force on one side in kN.

<svg class="figure" viewBox="0 0 560 230" role="img" aria-labelledby="triangle-title triangle-desc" xmlns="http://www.w3.org/2000/svg">
  <title id="triangle-title">Vertical triangular plate with its horizontal base at the water surface</title>
  <desc id="triangle-desc">A vertical triangular plate points downward from a horizontal 2 metre base on the free surface. Its height is 1.2 metres; the centroid lies 0.4 metres below the surface.</desc>
  <line x1="90" y1="60" x2="470" y2="60" stroke="#2487a8" stroke-width="4"/><text x="480" y="67" font-size="18" fill="#243b53">free surface</text>
  <polygon points="180,60 380,60 280,190" fill="#d8edf4" stroke="#34495e" stroke-width="4"/>
  <line x1="180" y1="42" x2="380" y2="42" stroke="#243b53" stroke-width="2"/><path d="M187 36 L179 42 L187 48 M373 36 L381 42 L373 48" fill="none" stroke="#243b53" stroke-width="2"/><text x="280" y="32" text-anchor="middle" font-size="20" fill="#243b53">b = 2 m</text>
  <line x1="414" y1="60" x2="414" y2="190" stroke="#243b53" stroke-width="2"/><path d="M408 68 L414 60 L420 68 M408 182 L414 190 L420 182" fill="none" stroke="#243b53" stroke-width="2"/><text x="426" y="130" font-size="20" fill="#243b53">h = 1.20 m</text>
  <circle cx="280" cy="103" r="6" fill="#087e8b"/><text x="292" y="109" font-size="18" fill="#243b53">centroid</text>
</svg>

**Solution:** The triangle's base is at the free surface, its area is \(A=bh/2=1.2\ \text{m}^2\), and its centroid is \(h/3=0.4\ \text{m}\) below that surface:

\[
F=\gamma_w\bar yA=9.81(0.4)(1.2)=4.71\ \text{kN}.
\]

**Answer: 4.71 kN (D).**

### 11. Center-of-pressure offset from centroid
**Problem 11:** For the triangular plate described in Problem 10, determine the distance of the resultant hydrostatic force from the plate’s centroid in millimeters.

**Solution:**


For a triangle with its base at the free surface, \(I_G=bh^3/36\). The centroidal depth is \(\bar y=h/3\), therefore:

\[
e=\frac{I_G}{A\bar y}
=\frac{2(1.2)^3/36}{(1.2)(0.4)}=0.200\ \text{m}.
\]

**Answer: 200 mm below the centroid (A).**

### 12. Center-of-pressure depth
**Problem 12:** For the triangular plate described in Problem 10, determine the depth of the resultant hydrostatic force below the liquid surface in millimeters.

**Solution:**


\[
y_{CP}=\bar y+e=0.400+0.200=0.600\ \text{m}.
\]

**Answer: 600 mm below the surface (B).**

### 13. Buoy volume above liquid
**Problem 13:** A wooden buoy with specific gravity 0.75 floats in a liquid with specific gravity 0.85. What percentage of the buoy’s total volume lies above the liquid surface?

**Solution:**


The submerged fraction is \(SG_b/SG_l=0.75/0.85=0.88235\). Thus the exposed fraction is:

\[
1-0.88235=0.11765\approx11.8\%.
\]

**Answer: 11.8% (A).**

### 14. Buoy weight
**Problem 14:** For the buoy described in Problem 13, the volume above the liquid is 0.045 m³. Estimate the buoy’s weight in kN.

**Solution:**


The exposed volume is 0.045 m³, so total volume is \(0.045/0.11765=0.3825\ \text{m}^3\). Then:

\[
W=SG_b\gamma_wV=0.75(9.81)(0.3825)=2.81\ \text{kN}.
\]

**Answer: 2.81 kN (D).**

### 15. Force to fully submerge the buoy
**Problem 15:** For the buoy described in Problems 13–14, determine the vertical force required to submerge it completely, in kN.

**Solution:**


At full immersion, the additional downward force equals the difference between liquid buoyancy and the buoy's weight:

\[
F=(SG_l-SG_b)\gamma_wV
=(0.85-0.75)(9.81)(0.3825)=0.375\ \text{kN}.
\]

**Answer: 0.375 kN downward (C).**

### 16. Buoyant force on the stone
**Problem 16:** A stone weighs 45 kg in air and has an apparent weight of 30 kg when submerged in fresh water. Determine the buoyant force on the stone in newtons.

**Solution:**


The apparent mass drops by \(45-30=15\ \text{kg}\) on immersion:

\[
F_B=15(9.81)=147\ \text{N}.
\]

**Answer: 147 N (A).**

### 17. Stone volume
**Problem 17:** For the stone described in Problem 16, determine its volume in cubic meters.

**Solution:**


Using fresh-water unit weight \(9810\ \text{N/m}^3\):

\[
V=\frac{F_B}{\gamma_w}=\frac{147}{9810}=0.0150\ \text{m}^3.
\]

**Answer: 0.015 m³ (A).**

### 18. Stone specific gravity
**Problem 18:** For the stone described in Problem 16, determine its specific gravity.

**Solution:**


The stone mass is 45 kg and its displaced water mass is 15 kg:

\[
SG_s=\frac{45}{15}=3.0.
\]

**Answer: 3.0 (D).**

### 19. Velocity in the larger series pipe
**Problem 19:** A water-supply line joins a 5,500 m long, 300 mm diameter pipe to a 3,660 m long, 450 mm diameter pipe, connecting a reservoir to the end of the line. The elevation difference from the reservoir water surface to the center of the 300 mm pipe at the outlet is 45.7 m. Neglect outlet velocity head and other entrance losses; use a friction factor of 0.02 for both pipes. Determine the flow velocity in the larger pipe in m/s.

**Solution:**


Apply Darcy–Weisbach to both series pipes. With \(Q\) common to both, the 45.7 m head difference gives:

\[
45.7=\frac{8fQ^2}{\pi^2g}\left(\frac{L_1}{D_1^5}+\frac{L_2}{D_2^5}\right),
\]

where \((L_1,D_1)=(3660\ \text{m},0.45\ \text{m})\), \((L_2,D_2)=(5500\ \text{m},0.30\ \text{m})\), and \(f=0.02\). This gives \(Q\approx0.106\ \text{m}^3/\text{s}\). Therefore:

\[
v_{450}=\frac{Q}{\pi(0.45)^2/4}\approx0.665\ \text{m/s}.
\]

**Answer: 0.665 m/s (D).**

### 20. Velocity in the smaller series pipe
**Problem 20:** For the series pipeline described in Problem 19, determine the flow velocity in the smaller pipe in m/s.

**Solution:**


The same discharge passes through the 300 mm pipe:

\[
v_{300}=\frac{0.106}{\pi(0.30)^2/4}\approx1.50\ \text{m/s}.
\]

**Answer: 1.50 m/s (A).**

### 21. Series-pipe discharge
**Problem 21:** For the series pipeline described in Problem 19, determine the discharge in m³/s.

**Solution:**


From the head-loss balance in Q19:

\[
Q\approx0.106\ \text{m}^3/\text{s}.
\]

**Answer: 0.106 m³/s (C).**

### 22. Flow in the 600 mm parallel branch
**Problem 22:** A 1,500 mm main carries 2.15 m³/s to a junction, where flow divides between a 300 m long, 1,200 mm branch and a 1,220 m long, 600 mm branch; the branches rejoin and continue through a 1,500 mm pipe. The friction factors for the 1,500 mm, 1,200 mm, and 600 mm pipes are 0.02, 0.022, and 0.024, respectively. Determine the discharge in the 600 mm branch in m³/s.

**Solution:**


For parallel branches, head losses are equal. Let \(Q_{1200}+Q_{600}=2.15\ \text{m}^3/\text{s}\). Using Darcy–Weisbach in discharge form and canceling the common factor \(8/(\pi^2g)\):

\[
\frac{(0.022)(300)Q_{1200}^2}{1.2^5}
=\frac{(0.024)(1220)Q_{600}^2}{0.6^5}.
\]

Solving with continuity gives \(Q_{1200}\approx1.984\) and \(Q_{600}\approx0.166\ \text{m}^3/\text{s}\).

**Answer: 0.166 m³/s (D).**

### 23. Flow in the 1200 mm parallel branch
**Problem 23:** For the parallel-branch system described in Problem 22, determine the discharge in the 1,200 mm branch in m³/s.

**Solution:**


\[
Q_{1200}=2.15-0.166=1.984\ \text{m}^3/\text{s}.
\]

**Answer: 1.984 m³/s (A).**

### 24. Velocity in the 600 mm branch
**Problem 24:** For the parallel-branch system described in Problem 22, determine the velocity in the 600 mm branch.

**Solution:**


\[
v=\frac{Q}{A}=\frac{0.166}{\pi(0.6)^2/4}=0.589\ \text{m/s}.
\]

**Answer: 0.59 m/s (B).**

### 25. Flow in a Hazen–Williams pipeline
**Problem 25:** A single pipeline connects two junctions with pressure heads of 70 m and 45 m. Three parallel pipes between them have dimensions: pipe 1, 300 mm diameter and 3,000 m long; pipe 2, 200 mm diameter and 1,300 m long; and pipe 3, 250 mm diameter and 2,500 m long. Using the Hazen–Williams formula with C = 110 for all pipes, determine the flow in pipe 1 in m³/s.

**Solution:**


The junction head difference is 25 m. For SI units,

\[
h_f=\frac{10.67LQ^{1.85}}{C^{1.85}D^{4.87}}.
\]

With \(L=3000\ \text{m}\), \(C=110\), and \(D=0.30\ \text{m}\), setting \(h_f=25\ \text{m}\) yields \(Q\approx0.0967\ \text{m}^3/\text{s}\).

**Answer: 0.097 m³/s (B).**

## Questions 26–50

### 26. Flow in the 200 mm parallel branch
**Problem 26:** For the parallel pipeline described in Problem 25, determine the flow in pipe 2 in m³/s.

**Solution:**


Each parallel branch has a 25 m head loss. Hazen–Williams gives

\[
Q=\left(\frac{h_fC^{1.852}D^{4.87}}{10.67L}\right)^{1/1.852}.
\]

For \(C=110\), \(D=0.20\ \text{m}\), and \(L=1300\ \text{m}\), \(Q_2=0.0523\ \text{m}^3/\text{s}\).

**Answer: 0.052 m³/s (D).**

### 27. Flow in the 250 mm parallel branch
**Problem 27:** For the parallel pipeline described in Problem 25, determine the flow in pipe 3 in m³/s.

**Solution:**


With the same 25 m head loss, \(D=0.25\ \text{m}\), and \(L=2500\ \text{m}\):

\[
Q_3=\left(\frac{25(110)^{1.852}(0.25)^{4.87}}{10.67(2500)}\right)^{1/1.852}
=0.0660\ \text{m}^3/\text{s}.
\]

**Answer: 0.066 m³/s (B).**

### 28. Head loss through the channel reach
**Problem 28:** Water flows at 12 m³/s in an almost level rectangular channel 3 m wide. Over a 5 m reach, the depth increases gradually from 1.0 m to 1.1 m. Determine the head loss in meters.

**Solution:**


For a level bed, the energy loss equals the decrease in depth plus the decrease in velocity head. With \(Q=12\ \text{m}^3/\text{s}\), \(b=3\ \text{m}\), and depths 1.0 m and 1.1 m:

\[
v_1=\frac{12}{3(1.0)}=4.00\ \text{m/s},\qquad
v_2=\frac{12}{3(1.1)}=3.636\ \text{m/s},
\]

\[
h_L=(1.0-1.1)+\frac{4.00^2-3.636^2}{2g}
=0.0415\ \text{m}.
\]

**Answer: 0.042 m (A).**

### 29. Energy-grade-line slope
**Problem 29:** For the channel reach described in Problem 28, determine the energy-grade-line slope.

**Solution:**


Over the 5 m reach,

\[
S_E=\frac{h_L}{L}=\frac{0.0415}{5}=0.00830.
\]

**Answer: 0.0083 (C).**

### 30. Manning roughness coefficient
**Problem 30:** For the channel reach described in Problem 28, determine the channel roughness coefficient.

**Solution:**


At depths 1.0 m and 1.1 m, the section areas are \(A_1=3.00\), \(A_2=3.30\ \text{m}^2\), and the hydraulic radii are

\[
R_1=\frac{3.00}{3+2(1.0)}=0.600\ \text{m},\qquad
R_2=\frac{3.30}{3+2(1.1)}=0.635\ \text{m}.
\]

Using the mean-section conveyance with the energy slope from Q29,

\[
Q=\frac{\sqrt{S_E}}{2n}\left(A_1R_1^{2/3}+A_2R_2^{2/3}\right),
\]

which gives \(n\approx0.0172\).

**Answer: 0.017 (D).**

### 31. Groundwater rise and bearing capacity
**Problem 31:** If flooding causes the groundwater table in a soil formation to rise, what generally happens to the soil’s bearing capacity?

**Solution:**


A rising water table reduces effective stress and can lower the available soil shear resistance.

**Answer: bearing capacity decreases (C).**

### 32. Factor that does not define soil bearing capacity
**Problem 32:** Which condition does not affect the bearing capacity of supporting soil: soil unit weight, load imposed on the soil, groundwater-table position, or footing embedment depth?

**Solution:**


Soil unit weight, groundwater level, and footing embedment affect bearing capacity. Applied load is compared with capacity in design; it does not determine the soil's capacity.

**Answer: load imposed on the soil (B).**

### 33. Dry unit weight
**Problem 33:** Determine the dry unit weight of soil with void ratio 0.50 and solids specific gravity 2.5, in kN/m³.

**Solution:**


\[
\gamma_d=\frac{G_s\gamma_w}{1+e}
=\frac{2.5(9.81)}{1+0.50}=16.35\ \text{kN/m}^3.
\]

**Answer: 16.35 kN/m³ (C).**

### 34. Unconfined compressive strength and cohesion
**Problem 34:** An unconfined compression test on a clay specimen 50 mm in diameter records a failure load of 250 N. Estimate the clay’s cohesion strength in kPa.

**Solution:**


For a 50 mm diameter specimen,

\[
A=\frac{\pi(0.050)^2}{4}=1.9635\times10^{-3}\ \text{m}^2,
\quad q_u=\frac{250}{A}=127.3\ \text{kPa}.
\]

For saturated clay in an unconfined test, \(c_u=q_u/2=63.7\ \text{kPa}\).

**Answer: 63.7 kPa (C).**

### 35. Offset needed to limit tunnel stress
**Problem 35:** A subway tunnel is to be built 10 m below ground. A vertical point load of 10 MN acts at the surface. Using Boussinesq’s point-load theory, determine the minimum radial distance between the load line and tunnel alignment so that vertical stress at tunnel level is no more than 5% of the stress directly below the load.

**Solution:**


For a point load, the Boussinesq stress ratio at equal depth is

\[
\frac{\sigma_z(r)}{\sigma_z(0)}=\left[1+(r/z)^2\right]^{-5/2}.
\]

Set this ratio to 0.05 at \(z=10\ \text{m}\):

\[
r=10\sqrt{0.05^{-2/5}-1}=15.2\ \text{m}.
\]

The smallest offered distance that meets the limit is **16 m (B)**.

### 36–38. Soil phase relationships
**Problem 36:** In its natural state, soil has moisture content 32%, unit weight 16 kN/m³, and solids specific gravity 2.50. Determine the degree of saturation in percent.
**Problem 37:** For the soil described in Problem 36, determine the void ratio.
**Problem 38:** For the soil described in Problem 36, determine the dry unit weight in kN/m³.

**Solution:**


Given \(w=0.32\), \(\gamma=16\ \text{kN/m}^3\), and \(G_s=2.50\):

\[
\gamma_d=\frac{\gamma}{1+w}=\frac{16}{1.32}=12.12\ \text{kN/m}^3,
\]

\[
e=\frac{G_s\gamma_w}{\gamma_d}-1
=\frac{2.50(9.81)}{12.12}-1=1.023,
\qquad
S=\frac{wG_s}{e}=0.782.
\]

**Answers:** Q36, \(S=78.2\%\) (C); Q37, \(e=1.02\) (C); Q38, \(\gamma_d=12.1\ \text{kN/m}^3\) (A).

### 39–41. Permeability of layered soil
**Problem 39:** A three-layer soil profile has (from top to bottom) thicknesses 4.0 m, 3.0 m, and 5.0 m, with permeabilities 2.1×10⁻⁴, 3.6×10⁻², and 4.2×10⁻⁵ cm/s, respectively. Determine the equivalent horizontal permeability in cm/s.
**Problem 40:** For the three-layer soil profile described in Problem 39, determine the equivalent vertical permeability in cm/s.
**Problem 41:** For the three-layer soil profile described in Problem 39, estimate vertical flow per square meter when the hydraulic gradient is 0.50.

**Solution:**


The scanned table gives thicknesses \(h=(4,3,5)\ \text{m}\) and permeabilities \(k=(2.1\times10^{-4},3.6\times10^{-2},4.2\times10^{-5})\ \text{cm/s}\). The first exponent is faint; reading it as \(-4\) matches the printed key and the following vertical-flow result.

For flow parallel to layers,

\[
k_h=\frac{\sum h_i k_i}{\sum h_i}
=\frac{4(2.1\times10^{-4})+3(3.6\times10^{-2})+5(4.2\times10^{-5})}{12}
=0.00909\ \text{cm/s}.
\]

**Q39 answer: 0.0091 cm/s (B).**

For flow perpendicular to layers,

\[
k_v=\frac{12}{4/(2.1\times10^{-4})+3/(3.6\times10^{-2})+5/(4.2\times10^{-5})}
=8.68\times10^{-5}\ \text{cm/s}.
\]

For one square meter and gradient 0.50, using \(1\ \text{m}^2=10^4\ \text{cm}^2\):

\[
Q=k_viA=(8.68\times10^{-5})(0.50)(10^4)
=0.434\ \text{cm}^3/\text{s}=1.56\ \text{L/h}.
\]

**Q40 answer: \(0.000087\) cm/s (D); Q41 answer: 1.562 L/h (B).**

### 42–44. Consolidated-drained triaxial test
**Problem 42:** A consolidated-drained triaxial shear test on consolidated clay has chamber confining pressure 240 kPa and deviator stress 450 kPa. Determine the friction angle in degrees.
**Problem 43:** For the consolidated-drained triaxial test described in Problem 42, determine shear stress on the failure plane in kPa.
**Problem 44:** For the consolidated-drained triaxial test described in Problem 42, determine normal stress on the plane of maximum shear in kPa.

**Solution:**


The stated confining stress and deviator stress give \(\sigma_3=240\ \text{kPa}\) and \(\sigma_1=240+450=690\ \text{kPa}\). Assuming the zero-cohesion failure envelope used by the source,

\[
\sin\phi=\frac{\sigma_1-\sigma_3}{\sigma_1+\sigma_3}
=\frac{450}{930},\qquad \phi=28.9^\circ.
\]

The Mohr-circle center and radius are \(C=(690+240)/2=465\ \text{kPa}\) and \(R=(690-240)/2=225\ \text{kPa}\). Hence \(\tau_f=R\cos\phi=197\ \text{kPa}\), while the normal stress on the maximum-shear plane is \(C=465\ \text{kPa}\).

**Q42: 28.9° (D is the nearest choice, 29.4°); Q43: 197 kPa (A is nearest, 194.4 kPa); Q44: 465 kPa (B and D are equally close at 460 and 470 kPa).** The source's worked solution substitutes 250 kPa and 440 kPa instead of the stated 240 kPa and 450 kPa; this changes its angle and center stress and explains its disagreement with the given data. The keyed Q42 letter follows that substituted-data solution.

### 45. Seepage below the dam
**Problem 45:** Below a dam, soil permeability is 3 m/day and upstream water is 30 m above downstream water. A flow net has 10 potential drops and 4 flow channels. Determine seepage per meter width of dam in liters per minute.

**Solution:**


With hydraulic conductivity \(k=3\ \text{m/day}\), head difference \(H=30\ \text{m}\), four flow channels and ten potential drops:

\[
q=kH\frac{N_f}{N_d}=3(30)\frac{4}{10}=36\ \text{m}^3/\text{day per m}.
\]

Converting to liters per minute gives \(36(1000)/(24\cdot60)=25\ \text{L/min per m}\).

**Answer: 25 L/min per meter width (D).**

### 46. Uplift pressure at the heel
**Problem 46:** For the dam and flow net described in Problem 45, the dam base is founded 1 m below ground. Determine uplift pressure at the heel in kPa.

**Solution:**


The upstream pressure is \(9.81(30)=294.3\ \text{kPa}\). With ten equal potential drops, one drop is 29.43 kPa. The heel lies one drop below the upstream boundary:

\[
p_{heel}=294.3-29.43=264.9\ \text{kPa}.
\]

**Answer: 265 kPa (A).**

### 47. Uplift force per meter of dam
**Problem 47:** For the dam and flow net described in Problems 45–46, the heel-to-toe distance is 25 m and there are 8 potential drops between them. Determine uplift force per meter width and per meter length of dam in kN.

**Solution:**


The 25 m base spans eight of the ten potential drops, leaving one drop on each side of the base. The pressure heads at heel and toe are therefore 27 m and 3 m. The uplift-pressure diagram is trapezoidal:

\[
U=\gamma_w\left(\frac{27+3}{2}\right)(25)
=9.81(15)(25)=3679\ \text{kN per meter of dam}.
\]

**Answer: 3,679 kN/m (A).**

### 48. Uniform bearing pressure under the footing
**Problem 48:** A circular footing 4 m in diameter supports a column load of 1,800 kN. Determine the bearing pressure exerted on the soil in kPa.

**Solution:**


The footing area is \(A=\pi(2)^2=12.566\ \text{m}^2\). Thus

\[
q=\frac{1800}{12.566}=143.2\ \text{kPa}.
\]

**Answer: 143 kPa (B).**

### 49. Vertical stress 6 m below the footing center
**Problem 49:** For the footing described in Problem 48, use the given Boussinesq relation for a flexible circular area under uniform load to determine vertical stress 6 m below the footing center in kPa.

**Solution:**


Using the supplied circular-load relation with \(r=2\ \text{m}\), \(z=6\ \text{m}\):

\[
N=[1+(2/6)^2]^{3/2}=1.171,
\quad
p=143.2(1-1/N)=20.9\ \text{kPa}.
\]

**Answer: 20.94 kPa (D).**

### 50. Depth where stress is one-tenth of base pressure
**Problem 50:** For the footing described in Problem 48, determine the depth below its center where vertical pressure falls to one-tenth of the pressure at the footing base.

**Solution:**


Set \(p/q=0.10\), so \(1-1/N=0.10\) and \(N=1/0.9\):

\[
[1+(2/z)^2]^{3/2}=1/0.9
\quad\Longrightarrow\quad
z=\frac{2}{\sqrt{(1/0.9)^{2/3}-1}}=7.41\ \text{m}.
\]

**Answer: 7.41 m (C).**
