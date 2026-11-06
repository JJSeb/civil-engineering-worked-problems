# November 2021 MSTC (Questions 1–69)

[← All problem sets](ce-ref.html)

## Questions 1–10

### 1. Inverse-square light intensity

**Problem:** Light intensity varies inversely with the square of distance from its source. At 2 ft, the intensity is 80 foot-candles. Find the distance at which the intensity is 5 foot-candles.

**Solution:** For inverse-square variation,

\[
I=k/x^2
\]

. The scan gives $I=80$ foot-candles at $x=2$ ft, hence $k=80(2^2)=320$. At $I=5$, $x=\sqrt{320/5}=8$ ft. **Answer: 8 ft (C).**

### 2. Endangered-species estimate

**Problem:** The estimated endangered-species count is modeled by \(y=1883/[1+7.892(1.097^{-t})]\), where \(t\) is years after 1980. Compare the model estimate for 2020 with the actual 2007 count of 1,137 species. How many more does the model estimate for 2020?

**Solution:** The printed model is

\[
y=\dfrac{1883}{1+7.892(1.097^{-t})}
\]

, with \(t\) years after 1980. For 2020,

\[
t=40
\]

, giving

\[
y\approx1576
\]

. The table gives 1137 for 2007, so

\[
1576-1137=439
\]

. **Answer: 439 (A).** A subtraction line has a typo (1337); the stated result uses 1137.

### 3. Roofers working together

**Problem:** An experienced roofer can complete a house in 26 hours, while a beginner needs 39 hours for the same house. How long will they take working together?

**Solution:** Their combined rate is

\[
1/26+1/39=5/78
\]

 house/h. Thus

\[
t=1/(5/78)=15.6
\]

 h. **Answer: 15.6 h (C).**

### 4. Falling object from the Millau Viaduct

**Problem:** The Millau Viaduct is 1,125 ft above the river. An object is dropped from its top, with height modeled by \(h(t)=-16t^2+1125\) ft when air resistance is neglected. Find its height after 6 seconds.

**Solution:** The scan gives

\[
h(t)=-16t^2+1125
\]

 ft. At

\[
t=6
\]

 s,

\[
h=1125-16(36)=549
\]

 ft. **Answer: 549 ft (A).**

### 5. Insurance commission — key conflict

**Problem:** A salesperson earns 2% of the face value of permanent insurance and 1% of the face value of term insurance. Find the commission on Php200,000 of term insurance and Php100,000 of permanent insurance.

**Solution:** The stated rates give

\[
0.01(\mathrm{Php}\,200{,}000)+0.02(\mathrm{Php}\,100{,}000)=\mathrm{Php}\,4{,}000
\]

. **Computed answer: Php4,000 (A).** The printed key says **B (Php5,000)**, which does not follow from the stated policy amounts and commission rates; the source's worked calculation also gives Php4,000.

### 6. Rational solutions

**Problem:** Find all rational roots of \(3x^4+14x^3+14x^2-8x-8=0\).

**Solution:** For

\[
f(x)=3x^4+14x^3+14x^2-8x-8
\]

, substitution verifies

\[
f(-2)=0
\]

 and

\[
f(-2/3)=0
\]

, the rational pair listed in choice D. **Answer: D.**

### 7. Gompertz model

**Problem:** A hospital network has a steady population of 1,000 hospitals. Five hospitals switched to the new electronic claims format in year 1 and 70 switched in year 2. Assuming a Gompertz curve \(D=Le^{-ce^{-dt}}\), determine the parameter \(c\).

**Solution:** The scan gives

\[
L=1000
\]

, with 5 hospitals switched in year 1 and 70 more in year 2, so cumulative

\[
D_1=5
\]

 at

\[
t=1
\]

 and

\[
D_2=75
\]

 at

\[
t=2
\]

. For

\[
D=Le^{-ce^{-dt}}
\]

, take logs twice:

\[
A=\ln[\ln(L/D)]=\ln c-dt
\]

. Then

\[
A_1=1.66739
\]

,

\[
A_2=0.95176
\]

,

\[
d=A_1-A_2=0.71563
\]

, and

\[
\ln c=A_1+d=2.3830
\]

. Thus

\[
c=10.8376
\]

. **Answer: C.**

### 8. Logistic parameter

**Problem:** A protozoan population follows the logistic model \(y=k/(1+be^{-cx})\), with \(c=1.1244\), \(k=105\), and time \(x\) in days. If the initial population is 3, find \(b\).

**Solution:** For

\[
y=k/(1+be^{-cx})
\]

, put

\[
x=0
\]

,

\[
y=3
\]

, and

\[
k=105
\]

:

\[
3=105/(1+b)
\]

, so

\[
b=34
\]

. **Answer: 34 (D).**

### 9. Matching lighthouse flashes

**Problem:** One lighthouse flashes red, white, green, white, red in successive 1-second intervals, repeating every 6 seconds. A second shows the same color sequence in 2-second intervals, repeating every 12 seconds. If both begin together, what fraction of time do they display the same color?

**Solution:** Over the 12-second common cycle, compare the colors over each 1-second interval. They match during 0–1 s (red), 3–4 s (white), 7–8 s (white), and 11–12 s (white): 4 s total. Thus the fraction is

\[
4/12=1/3
\]

. **Computed answer: B (1/3).** The printed key and worked solution say A (1/6), but omit three white-on-white intervals.

### 10. Freeway distance on a grid

**Problem:** A city grid has north–south streets and east–west avenues spaced 850 ft apart. Find the straight freeway distance from 25th Street and 8th Avenue to 115th Street and 64th Avenue, in miles.

**Solution:** The endpoint differences are

\[
115-25=90
\]

 streets and

\[
64-8=56
\]

 avenues:

\[
\sqrt{90^2+56^2}=106
\]

 blocks. At 850 ft/block,

\[
106(850)/5280=17.06
\]

 mi. **Answer: 17 mi (A).**

## Questions 11–20

### 11. Triangle angles

**Problem:** In a triangle, the largest angle is 80° greater than the smallest, and the remaining angle is 10° greater than the smallest. Find all three angles.

**Solution:** Let the smallest angle be \(x\). The angles are \(x\),

\[
x+10^\circ
\]

, and

\[
x+80^\circ
\]

. Thus

\[
3x+90^\circ=180^\circ
\]

, so the angles are

\[
30^\circ,40^\circ,110^\circ
\]

. **Answer: D.**

### 12. Bridge length by triangulation

**Problem:** To determine a bridge span \(AB\), a surveyor measures a 280 m line from point A to point C at right angles to \(AB\). The measured angle \(ACB\) is 49°50′. Find the bridge length \(AB\).

**Solution:** The 280 m perpendicular offset is opposite the bridge length, and the angle at C is

\[
49^\circ50'
\]

. Thus

\[
\tan(49^\circ50')=AB/280
\]

, so

\[
AB=280\tan(49^\circ50')=331.73
\]

 m. **Answer: A.**

### 13. Refraction at a water surface

**Problem:** A spotlight beam strikes a pond at an incidence angle of 24.5°. Using Snell’s law, find the refracted angle in water, given refractive indices \(n=1.00\) for air and \(n=1.33\) for water.

**Solution:** Snell's law gives

\[
n_a\sin\theta_i=n_w\sin\theta_r
\]

. With

\[
n_a=1.00
\]

,

\[
n_w=1.33
\]

, and

\[
\theta_i=24.5^\circ
\]

,

\[
\theta_r=\sin^{-1}(\sin24.5^\circ/1.33)=18.2^\circ
\]

. **Answer: D.**

### 14. Tower height

**Problem:** From point A, the angle of elevation to a tower top is 19.9°. Point B is 50 ft closer to the tower, where the elevation angle is 21.8°. Find the tower height.

**Solution:** Let the horizontal distance from the nearer point B to the tower be \(x\), and tower height \(h\). Then

\[
h=x\tan21.8^\circ=(x+50)\tan19.9^\circ
\]

; solving gives

\[
h\approx191
\]

 ft. **Answer: C.**

### 15. Circle inscribed in a sector

**Problem:** A circular sector has radius 24 m and area \(96\pi\,\mathrm{m^2}\). A smaller circle inside it is tangent to both radial sides and the curved edge. Find the smaller circle’s radius.

**Solution:** Sector area is

\[
96\pi\,\mathrm{m^2}
\]

, and

\[
96\pi=\tfrac12(24)^2\theta
\]

, so

\[
\theta=\pi/3=60^\circ
\]

. The small circle's center lies on the angle bisector; tangency gives

\[
\sin30^\circ=r/(24-r)
\]

, hence

\[
r=8
\]

 m. **Answer: D.**

### 16. Flagstaff height

**Problem:** A point on the ground in a square courtyard of area 160,000 ft² observes three equal-height flagstaffs at consecutive corners A, B, and C. Their elevation angles are 45°, 60°, and 60°, respectively. Find each flagstaff height in meters.

**Solution:** Let the square side be

\[
s=\sqrt{160{,}000}=400
\]

 ft and place consecutive corners at

\[
A=(0,0),B=(400,0),C=(400,400)
\]

. The equal

\[
60^\circ
\]

 angles at B and C imply the observer O is equidistant from B and C, so its y-coordinate is 200 ft. If O=(x,200), the

\[
45^\circ
\]

 view at A gives

\[
h^2=x^2+200^2
\]

; the

\[
60^\circ
\]

 view at B gives

\[
h^2=3[(x-400)^2+200^2]
\]

. Solving yields the physically relevant

\[
x\approx317.16
\]

 ft and

\[
h\approx375
\]

 ft. Convert:

\[
375(0.3048)=114.3
\]

 m. **Answer: B (114.32 m).**

### 17. Triangle side lengths

**Problem:** A triangle has perimeter 93 cm. Two sides are equal, and the third side is 9 cm longer than either equal side. Find the longest side.

**Solution:** Let the two equal sides be \(x\) and the third be

\[
x+9
\]

. From

\[
2x+(x+9)=93
\]

,

\[
x=28
\]

 cm, so the longest side is

\[
37
\]

 cm. **Answer: A.**

### 18. Zooming photograph

**Problem:** A rectangular satellite photograph initially covers 5 km by 7 km. As the camera zooms out, both its length and width increase at 2 km/s. How long until its area is at least five times the initial area?

**Solution:** Both dimensions increase at

\[
2\,\mathrm{km/s}
\]

, so

\[
A(t)=(5+2t)(7+2t)
\]

 and the original area is

\[
35\,\mathrm{km^2}
\]

. Set

\[
(5+2t)(7+2t)=175
\]

; the positive root is

\[
t=3.63
\]

 s. **Answer: C.**

### 19. Map scale

**Problem:** A topographic map has scale 1 cm = 40 m and contour interval 1.0 m. Adjacent contours are 15 mm apart on the map. Find the ground slope as a percentage.

**Solution:** The map distance 15 mm is 1.5 cm, representing

\[
1.5(40)=60
\]

 m on the ground. With a 1.0 m contour interval,

\[
S=(1/60)(100\%)=1.667\%
\]

. **Answer: C.**

### 20. Washer area

**Problem:** A washer has outer radius \(R\) and hole radius \(r\). Express its cross-sectional area as a polynomial and factor the polynomial completely.

**Solution:** Area

\[
=\pi R^2-\pi r^2=\pi(R-r)(R+r)
\]

. **Answer: B.**

## Questions 21–30

### 21. Pyramid cut into equal weights

**Problem:** A square-based pyramid is 15 m high and has mass 4,000 kg. At what distance above its base should a plane parallel to the base cut it so that the resulting two solids have equal weight?

**Solution:** For similar pyramids, volume is proportional to the cube of the height. The top pyramid must have half the original volume, so its height is

\[
15/\sqrt[3]{2}
\]

. The cut's distance above the base is

\[
15-15/\sqrt[3]{2}=3.10
\]

 m. **Answer: B.**

### 22. Moon surface area

**Problem:** The Moon’s radius is 1,080 miles. Use the sphere relation \(r=\sqrt{A/(4\pi)}\) to find its surface area, rounded to the nearest square mile.

**Solution:** For a sphere of radius

\[
1080
\]

 mi,

\[
A=4\pi r^2=4\pi(1080)^2\approx14{,}657{,}415
\]

 mi². **Answer: B.**

### 23. Perpendicular path to the ball's trajectory

**Problem:** On a coordinate football field, each unit is 1 m. Pepe is at \(P=(35,-20)\), and the ball’s path from a corner kick is \(y=(4/3)x\). Find the equation of the path Pepe should run so that it intersects the ball’s path at a right angle.

**Solution:** The ball's line has slope

\[
4/3
\]

, so a perpendicular path has slope

\[
-3/4
\]

. Through

\[
P=(35,-20)
\]

, its equation is

\[
y+20=-\tfrac34(x-35)
\]

. **Answer: B.**

### 24. Paraboloid focus

**Problem:** A satellite-TV dish is a finite paraboloid 12 m in diameter and 2 m deep. Find the distance from the dish’s center to its focus.

**Solution:** For a parabolic cross-section,

\[
x^2=4fy
\]

. The rim radius is 6 m at depth 2 m, so

\[
36=4f(2)
\]

, giving focal distance

\[
f=4.5
\]

 m. **Answer: B.**

### 25. Vector magnitude and direction

**Problem:** Find the magnitude and direction of the vector \((-5,-5)\).

**Solution:** For vector

\[
(-5,-5)
\]

,

\[
r=\sqrt{(-5)^2+(-5)^2}=5\sqrt2
\]

. It lies in quadrant III, so

\[
\theta=225^\circ=5\pi/4
\]

. **Answer: C.**

### 26. Minimum-area open box

**Problem:** An open-top rectangular box has base length twice its width and volume 1.78 m³. Find the width that minimizes its surface area.

**Solution:** Let width be \(w\), length

\[
2w
\]

, and height \(h\). Volume gives

\[
2w^2h=1.78
\]

, and open-top area is

\[
S=2w^2+6wh=2w^2+5.34/w
\]

. Setting

\[
dS/dw=4w-5.34/w^2=0
\]

 gives

\[
w=1.101
\]

 m. **Answer: A (1.10 m).**

### 27. Maximum trough volume

**Problem:** A 25 ft long trough has isosceles-triangle ends with equal sides 5 ft long. Find the top width of each triangular end that maximizes the trough volume.

**Solution:** For top width \(b\), the isosceles triangle height is

\[
\sqrt{5^2-(b/2)^2}
\]

; its area is

\[
A=\tfrac12b\sqrt{25-b^2/4}
\]

. Maximizing area (and thus fixed-length trough volume) gives

\[
b=5\sqrt2=7.07
\]

 ft. **Answer: D (7.1 ft).**

### 28. Falling water level in cone

**Problem:** Water drains from an inverted right circular cone, 10 m high with base radius 4 m, into a right circular cylinder of radius 6 m and height 8 m. The outflow is 15 m³/min. Find the rate at which the water level falls in the cone when its water depth is 5 m.

**Solution:** Similar triangles give

\[
r/h=4/10=0.4
\]

, so

\[
V=\tfrac13\pi(0.4h)^2h
\]

. Differentiate:

\[
dV/dt=0.16\pi h^2(dh/dt)
\]

. At

\[
h=5
\]

 m and

\[
dV/dt=-15\,\mathrm{m^3/min}
\]

,

\[
dh/dt=-15/[0.16\pi(25)]=-1.19\,\mathrm{m/min}
\]

. **Answer: C.**

### 29. Instantaneous velocity

**Problem:** A ball dropped from the Vista of Mines View Park has height \(s=-4.9t^2+119.2\), with \(s\) in meters and \(t\) in seconds. Find its instantaneous velocity at \(t=3\) s.

**Solution:** From

\[
s=-4.9t^2+119.2
\]

,

\[
v=ds/dt=-9.8t
\]

; at 3 s,

\[
v=-29.4
\]

 m/s. **Answer: B.**

### 30. Power climbing a hill

**Problem:** Find the power needed for a 1,500 kg car to climb a 10° hill at a steady 80 km/h against a retarding force of 750 N.

**Solution:** At steady speed, the engine must overcome the component of weight down the slope and the stated 750 N resistance:

\[
F=mg\sin10^\circ+750=1500(9.81)\sin10^\circ+750=3303\,\mathrm N.
\]

The speed is

\[
80/3.6=22.22\,\mathrm{m/s}
\]

, so

\[
P=Fv=73.4\,\mathrm{kW}
\]

. Converting with

\[
1\,\mathrm{hp}=0.746\,\mathrm{kW}
\]

 gives

\[
98.4\,\mathrm{hp}
\]

. **Answer: D (98.5 hp).**

## Questions 31–40

### 31. Loss of gravitational potential energy

**Problem:** A 5.00 kg box starts down a 5.00 m incline at 10.0 m/s. The incline angle is 30° and the friction coefficient is 0.200. Find the loss of the box’s gravitational potential energy.

**Solution:** The box drops vertically by

\[
5\sin30^\circ=2.5
\]

 m. The potential-energy change is

\[
\Delta PE=mg(h_f-h_i)=-5(9.81)(2.5)=-122.6\,\mathrm J
\]

. **Answer: D (−123 J).** Friction and initial speed do not affect this gravitational potential-energy change.

### 32. Isothermal air-compression power

**Problem:** Find the theoretical horsepower required to compress 2.8 m³ of air per minute isothermally from atmospheric pressure (0.101 N/mm²) to a gauge pressure of 0.7 N/mm² (8.01 bar absolute).

**Solution:** For ideal isothermal compression,

\[
P=p_1\dot V\ln(p_2/p_1)
\]

. Use inlet absolute pressure

\[
p_1=0.101\,\mathrm{MPa}
\]

, outlet absolute pressure

\[
p_2=8.01\,\mathrm{bar}=0.801\,\mathrm{MPa}
\]

, and inlet flow

\[
\dot V=2.8/60=0.04667\,\mathrm{m^3/s}
\]

:

\[
P=(0.101\times10^6)(0.04667)\ln(0.801/0.101)=9.75\,\mathrm{kW}.
\]

**Answer: A (9.7 kW).**

### 33. Monthly pump power and maintenance cost

**Problem:** A replacement sewage pump rated at 200 hp costs 320,000, has annual maintenance of 5,000, electrical efficiency 0.85, and expected life of 14 years. It operates 400 hours per year; electricity costs 4.0 per kWh, and 1 hp = 0.746 kW. Assuming no salvage value, find the monthly power and maintenance cost.

**Solution:** The electrical input is

\[
200(0.746)/0.85=175.53\,\mathrm{kW}
\]

. Annual energy cost is

\[
175.53(400)(\mathrm{Php}\,4)=\mathrm{Php}\,280{,}848
\]

. Add annual maintenance of Php5,000 and divide by 12:

\[
C_m=(280{,}848+5{,}000)/12=\mathrm{Php}\,23{,}820.67\text{/month}.
\]

Rounded to the printed value, **Answer: D (Php23,820.50).** The prompt asks for monthly operating power and maintenance cost; it does not ask to include capital recovery.

### 34. Refinery capacity-cost estimate

**Problem:** A small refinery is estimated to cost Php190 million for capacity 2 million barrels per year. Using capacity-cost exponent 0.57, estimate cost per barrel of annual capacity for facilities rated 1 million and 3 million barrels per year.

**Solution:** The capacity exponent table gives

\[
n=0.57
\]

 for a small refinery. Scale total cost using

\[
C_1=C_2(Q_1/Q_2)^n
\]

, with

\[
C_2=Php190
\]

 million at

\[
Q_2=2
\]

 million barrels/year. Then divide each estimated total cost by its capacity:

\[
\frac{C}{Q}=\mathrm{Php}\,95(2/Q)^{0.43}.
\]

This gives approximately Php128, Php95, and Php80 per barrel/year for capacities 1M, 2M, and 3M. **Answer: C.**

### 35. At least one defective in a sample

**Problem:** A shipment of 100 memory cards contains 5 defective cards. Five cards are sampled without replacement. Find the probability that at least one sampled card is defective.

**Solution:** Use the complement: all five are good. Sampling without replacement gives

\[
P(\ge1\text{ defective})=1-\frac{\binom{95}{5}}{\binom{100}{5}}=0.231\text{ (approximately)}.
\]

**Answer: A (0.23).**

### 36. Flood probability — key conflict

**Problem:** Annual rainfall is normally distributed with mean 50 in and standard deviation 4 in. Rainfall above 57 in causes flooding. Find the probability of flooding in a randomly selected year.

**Solution:** Standardize the 57-inch threshold:

\[
z=(57-50)/4=1.75
\]

. The upper tail is

\[
P(Z>1.75)\approx0.0401
\]

. **Calculated probability: 0.0401.** No option matches; the printed key indicates D (0.401), ten times the normal-tail result.

### 37. Relay reliability

**Problem:** A message passes from terminal A to terminal B only if relays \(R_1,R_2,R_3,R_4\) all close. Their respective closing probabilities are 0.5, 0.7, 0.8, and 0.8, and they operate independently. Find the probability the message gets through.

**Solution:** The statement says the message passes if all four relays are closed. With independent relay probabilities

\[
0.5,0.7,0.8,0.8
\]

,

\[
P=0.5(0.7)(0.8)(0.8)=0.224.
\]

**Answer: A (0.224).**

### 38. Tennis-set sequence

**Problem:** Elmer wins a prize if he wins at least two consecutive sets in a three-set series. He may choose Father–Champion–Father or Champion–Father–Champion. His win probabilities are 80% against his father and 40% against the club champion. Which order gives the greater probability of winning the prize?

**Solution:** For Father–Champion–Father, the chance of at least two consecutive wins is

\[
0.8(0.4)+0.4(0.8)-0.8(0.4)(0.8)=0.384
\]

. For Champion–Father–Champion it is

\[
0.4(0.8)+0.8(0.4)-0.4(0.8)(0.4)=0.512
\]

. Choose the second sequence. **Answer: D.** The scan duplicates one option label, but D states Champion–Father–Champion with probability 0.512.

### 39. Traverse azimuth

**Problem:** A small-site traverse was measured with a 20-second theodolite and a chain, with angles of equal precision. The azimuth of \(AB\) is 54°10′. The field angles, adjustments, adjusted angles, and distances are: A: 52°26′, −1′, 52°25′, 322.52; B: 53°05′, −1′, 53°04′, 265.25; C: 74°32′, −1′, 74°31′, 267.66. The angle sum changes from 180°03′ to 180°00′ after adjustment. Determine the azimuth or bearing of line \(CA\).

**Solution:** The adjusted triangle angles are A=52°25′, B=53°04′, C=74°31′, and azimuth AB=54°10′. Reverse to get BA=234°10′. Taking the triangle interior at B gives BC=234°10′−53°04′=181°06′; thus CB=1°06′. At C, the direction CA is

\[
1^\circ06'−74^\circ31'=−73^\circ25'
\]

, or

\[
286^\circ35'
\]

 modulo 360°. **Answer: B (286°35′).**

### 40. Wave height from steepness

**Problem:** A tropical typhoon has estimated wind speed 140 km/h and produces a storm surge in a coastal town. The wave period is 7.47 s, water depth is 9 m, and steepness is 0.14. Find the wave height.

**Solution:** For a deep-water wave, the source uses

\[
\lambda=gT^2/(2\pi)
\]

. With

\[
T=7.47
\]

 s,

\[
\lambda=87.123
\]

 m and

\[
H=S\lambda=0.14(87.123)=12.20
\]

 m. **Answer by the source method: C.** **Caution:** the question also gives depth 9 m, which is not deep water for this wavelength (deep-water criterion is approximately

\[
d\ge\lambda/2
\]

). Using the finite-depth dispersion equation instead gives about

\[
H=8.75
\]

 m, not among the choices; the keyed choice relies on the deep-water approximation despite the stated depth.

## Questions 41–50

### 41. Typhoon wave velocity — source approximation

**Problem:** Typhoon Odette passes over open ocean with water depth 150 m. Estimate the wave-propagation velocity in km/h.

**Solution:** The calculation treats a deep-water wave at the boundary

\[
d=\lambda/2
\]

, so

\[
\lambda=2(150)=300
\]

 m. Deep-water celerity is

\[
v=\sqrt{g\lambda/(2\pi)}=\sqrt{g(150)/\pi}=21.64
\]

 m/s, or

\[
77.9
\]

 km/h. **Answer: C.** This is an approximation based on the deep-water threshold; the question itself does not provide a period or wavelength.

### 42. Basic and standard time

**Problem:** A time study of health-insurance requests handled by BPO agents in Cebu records an average of 7 minutes. The observed worker is rated at 90%, and the firm’s allowance factor is 8%. Find the basic time and standard time.

**Solution:** Basic time is observed time times performance rating:

\[
7(0.90)=6.30
\]

 min. With an 8% allowance on standard time,

\[
T_s=6.30/(1-0.08)=6.85
\]

 min. **Answer: B (6.30 min; 6.85 min).**

### 43. Cleaning crew standard time

**Problem:** A hotel cleaning contractor is determining standard time for a room-cleaning operation. The allowance is 15%. For “Empty bins,” seven observed times in minutes are 1.00, 0.90, 0.75, 1.20, 1.40, 0.60, and 0.80, with rating 0.90. For “Vacuum Floor,” the times are 3.00, 4.50, 3.50, 3.00, 3.75, 4.25, and 4.25, with rating 1.25. Find the standard time for the complete operation.

**Solution:** Average observed time for “Empty bins” is

\[
(1.00+0.90+0.75+1.20+1.40+0.60+0.80)/7=0.95
\]

 min; normal time is

\[
0.95(0.90)=0.855
\]

 min. Average for “Vacuum Floor” is

\[
(3.00+4.50+3.50+3.00+3.75+4.25+4.25)/7=3.75
\]

 min; normal time is

\[
3.75(1.25)=4.6875
\]

 min. Total normal time is 5.5425 min. With 15% allowance, standard time is

\[
5.5425/(1-0.15)=6.521
\]

 min. **Answer: D.**

### 44. Wheel-loader production

**Problem:** Estimate hourly loose-volume production of a 2.68 m³ wheel loader moving average sand and gravel from a pit to a stockpile. The one-way haul distance is 61 m, effective grade is 6%, bucket fill factor is 1.00, and job efficiency is 50 min/h. The basic cycle times (articulated wheel loader / track loader) are 0.35/0.30 min for loose material, 0.50/0.35 min for average material, and 0.65/0.45 min for hard material. Use the haul-plus-return travel-time chart, which gives travel time by one-way distance and effective grade.

**Solution:** Basic cycle time for average material is 0.50 min. From the low-resolution travel chart, 61 m one-way distance at 6% grade gives about 0.30 min for haul and return, so the cycle is about 0.80 min. Effective cycles per hour are

\[
50/0.80=62.5
\]

, and production is

\[
2.68(62.5)=167.5
\]

 loose m³/h. **Answer: C (168 Lm³/h).** The chart reading is approximate.

### 45. Increased unit-cost matrix

**Problem:** A unit-cost matrix for wood, siding, and roofing has purchase costs (6, 4, 2) and delivery costs (1, 1, 0.5), respectively. If the supplier raises both purchase and delivery costs by 10%, find the new unit-cost matrix.

**Solution:** A 10% increase multiplies every purchase and delivery cost by 1.10:

\[
1.10\begin{bmatrix}6&4&2\\1&1&0.5\end{bmatrix}
=\begin{bmatrix}6.6&4.4&2.2\\1.1&1.1&0.55\end{bmatrix}.
\]

**Answer: D.**

### 46. Hydraulic-excavator production

**Problem:** Find the expected loose-volume production per hour of a small hydraulic excavator. Heaped bucket capacity is 0.57 m³, fill factor 0.95, job efficiency 50 min/h, average cut depth 4.3 m, maximum cut depth 6.1 m, and swing angle 90°. Use cycle output 250 cycles/60 min and swing-depth factor 1.00.

**Solution:** Use the provided relation

\[
P=C\,S\,V\,B\,E
\]

: 250 cycles/h, swing-depth factor 1.00, bucket capacity 0.57 m³, fill factor 0.95, and efficiency

\[
50/60
\]

. Thus

\[
P=250(1.00)(0.57)(0.95)(50/60)=112.8
\]

 Lm³/h. **Answer: A (113 Lm³/h).**

### 47. Toll-booth queue delay

**Problem:** During morning peak, traffic arrives upstream of a toll plaza with three booths, each serving one vehicle every 6 seconds. In successive 10-minute periods from 7:00 to 8:00, arrivals are 200, 400, 500, 250, 200, and 150 vehicles (cumulative totals 200, 600, 1,100, 1,350, 1,550, and 1,700). Use a queuing diagram to find total delay.

**Solution:** Three booths each serve one vehicle every 6 s, for a combined capacity of 30 vehicles/min. Using each 10-minute arrival interval and the cumulative arrival/service curves, the queue at interval ends is 0, 100, 300, 250, 150, and 0 vehicles. The area under the queue curve is

\[
D=\frac{10}{2}[(0+100)+(100+300)+(300+250)+(250+150)+(150+0)]
=8000\,\mathrm{vehicle\!\cdot min}=133.3\,\mathrm{vehicle\!\cdot h}.
\]

**Answer: A (133 veh·h).**

### 48. Two-way traffic progression — key conflict

**Problem:** A grid has north–south block length 140 m and east–west block length 240 m. The desired progression speed is 50 km/h east–west. Determine actual two-way progression speeds in both orientations, rounding cycle lengths to the nearest 5 seconds. Use \(C=2NL/s\).

**Solution:** The hint gives

\[
C=2L/s
\]

, where \(L\) is block length and

\[
s=50/3.6=13.89
\]

 m/s. For the 140 m North–South block,

\[
C=20.16
\]

 s, rounded to 20 s; speed is

\[
(2L/C)(3.6)=50.4
\]

 km/h. For the 240 m East–West block,

\[
C=34.56
\]

 s, rounded to 35 s; speed is

\[
(2L/C)(3.6)=49.4
\]

 km/h. None of the listed pairs gives both values. **Printed key: C (50.4, 43.2 km/h); the East–West value conflicts with the stated cycle method.**

### 49. Concrete unit mixes

**Problem:** One concrete unit mix contains 136 kg gravel, 95 kg sand, 42.5 kg Portland cement, and 22.5 kg water, plus 5% entrained air. Find the number of mixes needed for a retaining wall measuring 28.6 m × 1.22 m × 0.305 m. Aggregates are non-porous. True and bulk specific gravities are: gravel 2.60 and 1.76; sand 2.65 and 1.68; cement 3.25 and 1.50.

**Solution:** Wall volume is

\[
28.6(1.22)(0.305)=10.642\,\mathrm{m^3}
\]

. Absolute non-air batch volume is

\[
V_b=\frac{136}{2.60(1000)}+\frac{95}{2.65(1000)}+\frac{42.5}{3.25(1000)}+\frac{22.5}{1000}=0.12373\,\mathrm{m^3}.
\]

With 5% air, yield per mix is

\[
0.12373/0.95=0.13025\,\mathrm{m^3}
\]

, so

\[
10.642/0.13025=81.7
\]

 mixes. **Answer: A (81.7 unit mixes).**

## Questions 50–69

### 50. Hazard

**Problem:** What term describes circumstances or deviations from standard conditions that could permit an accident or incident?

**Solution:** The stem describes circumstances or deviation from standard conditions that could permit an accident. “Hazard” is the broad term for such a potentially harmful circumstance; an unsafe act would be a person's behavior. **Answer: A (hazard), matching the key.**

### 51. Coastal-engineering environmental factor

**Problem:** Identify the single most important environmental factor in the broad field of coastal engineering.

**Solution:** The scan asks for the single most important environmental factor in coastal engineering. Of the choices, **wave** is the intended factor. **Answer: D.**

### 52. Concrete curing

**Problem:** Name the construction operation that prevents moisture loss during early concrete hardening, maintains a temperature favorable to hydration, and protects concrete from damage by later construction activities.

**Solution:** Preventing moisture loss while maintaining a temperature that supports hydration and protects the concrete during early hardening describes curing. **Answer: A.**

### 53. Risk

**Problem:** What term combines the likelihood of a hazardous event in specified circumstances and period with the severity of resulting harm to people, property, or the environment?

**Solution:** Risk combines the likelihood of a hazardous event with the severity of its consequences. **Answer: C.**

### 54. Coastal-defense design condition

**Problem:** What is the worst condition to consider when designing coastal-defense works?

**Solution:** The governing severe case is the combined unusually high water level and severe wave action. **Answer: D.**

### 55. Gravity waves

**Problem:** Wind friction transfers energy to the water and moves its particles; gravity restores them toward their original positions. What are these waves called?

**Solution:** Wind transfers energy to water; gravity is the restoring force that returns displaced particles toward equilibrium. Those are gravity waves. **Answer: D.**

### 56. Traffic-capacity parameter

**Problem:** Between traffic volume and density, which is the more accurate parameter of traffic capacity, and why?

**Solution:** Density is vehicles per unit roadway length, which is the quantity tied to cars occupying a given length of road. Volume (flow) is vehicles per unit time. **Answer: B (density).** The wording “more accurate parameter” is imprecise, but the stated reason identifies density.

### 57. Safe design for construction

**Problem:** Which items are concepts of safe construction design? I. Design of the structure to be built. II. Subsystems included in the structure, such as electrical, mechanical, and plumbing. III. Equipment used to build the structure. IV. On-site facilities such as man lifts, elevators, concrete batch plants, rock-crushing or gravel-processing facilities, and asphalt plants. V. Construction manpower.

**Solution:** The keyed set is I, III, IV, and V: the structure, construction equipment, on-site facilities, and construction manpower. The listed subsystems in II concern the completed building's services rather than the construction-safety elements intended by this question. **Answer: D, matching the key.**

### 58. Concrete shrinkage

**Problem:** What concrete phenomenon reduces volume as concrete hardens, is greater in wet mixes, and has its effects limited by curing and prolonged moistening after placement?

**Solution:** The reduction in concrete volume as it hardens, especially in wetter mixes, is shrinkage; curing helps limit its effects. **Answer: D.**

### 59. Tack coat — key conflict

**Problem:** What is the name of the single initial bituminous application to an existing bituminous, Portland-cement-concrete, or block surface or base?

**Solution:** The single initial bituminous application to an existing bituminous, Portland-cement-concrete, or block surface is a tack coat (A). A prime coat is applied to an untreated granular base. **Correct term: A.** The printed key says B (prime coat), conflicting with the definition and choices.

### 60. Ideal road capacity

**Problem:** What is the ideal road capacity in vehicles per hour?

**Solution:** The conventional ideal capacity used in the item is 2,000 vehicles per hour. **Answer: B.**

### 61. PERT time estimates

**Problem:** Which statements describe estimation of expected activity times in a PERT network? I. It uses three estimates. II. It gives greatest weight to the most-likely estimate. III. It is motivated by the beta distribution.

**Solution:** PERT uses three time estimates, weights the most-likely estimate most heavily, and is based on a beta-distribution model for activity times. All three statements are true. **Answer: D (all of the above).**

### 62. Material-response categories

**Problem:** What are the four major categories of material properties that describe responses to external stimuli such as heat, wind, and gravity loads?

**Solution:** The broad categories listed are mechanical, thermal, electrical, and chemical properties. **Answer: B.**

### 63. Vertical-angle measurement — key conflict

**Problem:** For measuring vertical or zenith angles, assess these practices: I. Level the instrument. II. Sight with the vertical crosshair. III. Sight exactly on the target. IV. Observe in direct and reverse positions. Which are valid standard practices?

**Solution:** For a reliable vertical/zenith-angle observation, level the instrument, use the vertical crosshair, sight the target, and observe in direct and reverse faces. All four practices are valid. **Best answer: C (all of the above).** The printed key gives B, omitting the valid target-sighting step.

### 64. PERT completion probability — key conflict

**Problem:** Which statements describe calculating the probability that a PERT critical path is complete by time \(T\)? I. Activity times are statistically independent. II. Total critical-path time is approximately beta distributed. III. Standard deviations for all network activities are required.

**Solution:** The usual calculation assumes independent activity times and approximates the critical-path total duration as normal; it uses the expected path time and the path variance. Thus statement I is supported, while statement II (beta distribution for the total path time) is false and III overstates the required information. **Best answer: A (I only).** The printed key gives D, which does not follow the standard method.

### 65. Reliability

**Problem:** What is the probability that a mechanism functions satisfactorily, either on a given occasion for intermittent brief use or over a specified period for continuous operation?

**Solution:** Reliability is the probability that a mechanism functions satisfactorily for a specified occasion or time interval. **Answer: C.**

### 66. Soil-compaction objectives

**Problem:** Compaction applies energy to soil to compress air voids and raise dry density. Assess these objectives: I. Minimize settlement. II. Increase load-bearing capacity. III. Increase soil stability. IV. Reduce water penetration. V. Protect a slope that will drain water away. Which are objectives of proper compaction?

**Solution:** Proper compaction minimizes settlement, increases bearing capacity and stability, and reduces water penetration (statements I–IV). Statement V is not a general compaction objective. **Answer: B.**

### 67. Rail thrust without superelevation

**Problem:** When a train travels on a curve without superelevation, where does it exert thrust?

**Solution:** On a curve, the train's outward centrifugal action presses the flange against the inner face of the outer rail. **Answer: D, matching the key.**

### 68. Critical path

**Problem:** Among all paths through a network, how is the critical path characterized?

**Solution:** The critical path is the path with the greatest expected duration through the network. **Answer: A.**

### 69. Normal-curve statements

**Problem:** Which statements are true? I. Every symmetric histogram has a single peak. II. Every symmetric bell-shaped curve is normal. III. Every normal curve is bell-shaped and symmetric.

**Solution:** A symmetric histogram need not have one peak, and a symmetric bell-shaped curve need not be normal. A normal curve is bell-shaped and symmetric, so only statement III is true. **Answer: C.**

[← All problem sets](ce-ref.html)
