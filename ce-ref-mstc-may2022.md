# May 2022 MSTC (Questions 1–55)

[← All problem sets](index.html)

Worked solutions for all 55 May 2022 MSTC questions. Faint values, ambiguous wording, and key conflicts are flagged. Q45 is derived from the stated inputs using the standard pile-driving relation.

## Questions 1–10

### Q1 — Stock allocation
**Problem:** An investment firm must place Php100,000 in stocks A and B. Stock A returns 15% annually, but no more than Php50,000 may be invested in it; the more stable stock B returns 10%. How should the funds be divided to earn Php13,000 per year?

**Solution:** The budget and target-return equations are \(A+B=100{,}000\) and \(0.15A+0.10B=13{,}000\). Substituting \(B=100{,}000-A\) gives \(A=60{,}000\), above the Php50,000 cap. At the cap, the return is \(0.15(50{,}000)+0.10(50{,}000)=\text{Php12,500/year}\). **No feasible allocation meets the target; keyed D violates the cap.**
### Q2 — Rope cuts; wording ambiguity
**Problem:** A 213-ft rope is to be cut into three pieces, each 2 ft longer than the previous piece. Where should the cuts be made?

**Solution:** Let the lengths be \(x,x+2,x+4\) ft. Then \(3x+6=213\), so the pieces are 69, 71, and 73 ft. The cut positions from one end are 69 ft and \(69+71=140\) ft. **Key A (69 and 73) lists the end-piece lengths, not cut positions; wording is imprecise.**
### Q3 — Ball dropped downward
**Problem:** A ball is thrown downward from a 180-ft building at 20 ft/s. Its height after t seconds is h = −16t² − 20t + 180. How long until it reaches the ground?

**Solution:** Set the stated height to ground level: \(-16t^2-20t+180=0\). Multiplying by \(-1\) gives \(16t^2+20t-180=0\), so the positive root is \(t=[-20+\sqrt{20^2-4(16)(-180)}]/[2(16)]=2.79\text{ s}\). **Answer: B.** The alternative root form \([-20-\sqrt{11920}]/(-32)\) would apply to \(-16t^2+20t+180=0\); that sign conflicts with the prompt’s downward initial velocity.
### Q4 — Starbucks store model conflict
**Problem:** The question gives the model f(x) = 115x² + 117x + 3963 and asks for the value in 2004, with x interpreted relative to year 2000. What value does the model predict?

**Solution:** For 2004, \(x=2004-2000=4\). Thus \(f(4)=115(4)^2+117(4)+3963=6{,}271\). **This differs from keyed 6,721 and the listed choices.**
### Q5 — Radioactive material
**Problem:** After a nuclear accident, radioactive debris enters the atmosphere and may affect the milk supply. The percentage of radioactive material in raw milk after t days is modeled by y = 100(2.7)^(−t/14). Estimate the percentage after 30 days. The exponent is faint in the scan.

**Solution:** Using the faint exponent as transcribed, \(y=100(2.7)^{-30/14}=14.3\%\). The choices are 6%, 7%, 4%, and 5%, none matching. **Key check D (5%); exponent is faint and expression/options conflict.**
### Q6 — Gable triangle
**Problem:** A house has a triangular gable end with two 42-ft sides meeting at an angle of 115°. Find the gable’s area.

<svg viewBox="0 0 340 165" role="img" aria-label="Schematic isosceles triangular gable with two 42 foot sides and a 115 degree obtuse included angle at the apex" xmlns="http://www.w3.org/2000/svg"><path d="M35 112 L305 112 L170 26 Z" fill="#edf4f7" stroke="#17324d" stroke-width="3"/><path d="M150 40 Q170 67 190 40" fill="none" stroke="#087e8b" stroke-width="2"/><text x="154" y="61" font-size="14">115°</text><text x="72" y="76" font-size="14">42 ft</text><text x="234" y="76" font-size="14">42 ft</text><text x="112" y="151" font-size="12" fill="#617182">Schematic; not to scale</text></svg>

**Solution:** For two 42-ft sides with included angle 115°, \(A=\tfrac12 ab\sin C=\tfrac12(42)(42)\sin115^\circ=799\text{ ft}^2\). **Answer: A.**
### Q7 — Relative ship bearing
**Problem:** Two ships leave port at the same time. One sails N 23° E at 11 mph and the other S 67° E at 15 mph. After one hour, what is the bearing from the second ship to the first?

<svg viewBox="0 0 330 190" role="img" aria-label="Schematic east north plot of port and two ship positions with relative bearing north 31 degrees west" xmlns="http://www.w3.org/2000/svg"><path d="M35 155 H305 M55 175 V25" stroke="#617182" stroke-width="2"/><text x="300" y="174" font-size="12">E</text><text x="40" y="25" font-size="12">N</text><circle cx="55" cy="155" r="4" fill="#17324d"/><circle cx="105" cy="72" r="5" fill="#17324d"/><circle cx="195" cy="120" r="5" fill="#b36b00"/><path d="M195 120 L105 72" stroke="#087e8b" stroke-dasharray="5 4" stroke-width="2"/><text x="111" y="69" font-size="12">Ship 1</text><text x="201" y="120" font-size="12">Ship 2</text><text x="92" y="179" font-size="11" fill="#617182">Schematic; points from stated courses</text></svg>

**Solution:** Take east/north as positive axes. After 1 h, \(\mathbf r_1=(11\sin23^\circ,11\cos23^\circ)=(4.30,10.12)\text{ mi}\), while \(\mathbf r_2=(15\sin67^\circ,-15\cos67^\circ)=(13.81,-5.86)\text{ mi}\). Thus \(\mathbf r_1-\mathbf r_2=(-9.51,15.98)\text{ mi}\), giving bearing \(\tan^{-1}(9.51/15.98)=30.8^\circ\) west of north: **N31°W (A).**
### Q8 — Mountain height from two stations
**Problem:** A surveyor observes a mountain from a transit 1.5 m above the ground at two stations 1,200 m apart on level ground. The elevation angles are 51° and 38°. Find the mountain height above ground level.

<svg viewBox="0 0 430 270" role="img" aria-label="Schematic mountain survey: farther station at left observes 38 degrees, nearer station at right observes 51 degrees, stations 1200 metres apart" xmlns="http://www.w3.org/2000/svg"><path d="M28 245 H400 M54 245 V20 M154 245 V20 M334 245 V20" stroke="#17324d" stroke-width="2"/><path d="M58 240 L334 18 M158 240 L334 18" stroke="#087e8b" stroke-width="2"/><path d="M54 240 H334" stroke="#8797a4" stroke-dasharray="5 4"/><path d="M79 240 A25 25 0 0 0 74 225 M179 240 A25 25 0 0 0 173 220" fill="none" stroke="#b36b00" stroke-width="2"/><text x="80" y="228" font-size="13">38°</text><text x="181" y="222" font-size="13">51°</text><text x="33" y="264" font-size="11">Far station</text><text x="134" y="264" font-size="11">Near station</text><text x="91" y="258" font-size="12">1200 m</text><text x="340" y="27" font-size="12">Peak</text><text x="40" y="18" font-size="10" fill="#617182">Schematic; horizontal/vertical scales differ</text></svg>

**Solution:** Let \(x\) be the horizontal distance from the nearer station to the peak’s vertical foot, and \(H\) the rise above instrument level. Then \(H=x\tan51^\circ=(x+1200)\tan38^\circ\). Eliminating \(x\), \(H=1200\tan51^\circ\tan38^\circ/(\tan51^\circ-\tan38^\circ)=2{,}552.3\text{ m}\) above instrument level. Add the stated 1.5-m instrument height: mountain height \(\approx2{,}553.8\text{ m}\), or \(2{,}554\text{ m}\) above ground. **Answer B.**
### Q9 — Three-point mountain geometry
**Problem:** In mountainous terrain, a geologist measures two points B and C, 928 m apart. The elevation angle from B to mountain top A is 47°10′; the angles of elevation from C to B and from C to A are 8°40′ and 32°30′, respectively. If C is at elevation 1,621 m, find A’s elevation.

**Solution:** The available transcription does not establish the horizontal ordering of A, B, and C, and the sight angles do not support the earlier claimed triangle angle \(138^\circ50'\). Therefore the elevation of A cannot be uniquely reconstructed from these notes. **Key check B (2,847 m) is not independently derived; a clearer source figure/wording is required.**
### Q10 — Belt around small shaft and pulley
**Problem:** A 20-in belt connects a very small motor shaft to a pulley whose center is 4 in from the shaft. Treat the shaft as a point. If 8.5 in of belt contacts the pulley, find the pulley radius to the nearest tenth of an inch.

**Solution:** The transcribed values are belt length 20 in, center distance 4 in, and contact arc 8.5 in, with the shaft treated as a point. The arc relation \(s=R\theta\) is insufficient without the wrap angle, which depends on the exact tangent geometry and meaning of the stated belt length. **Key check D (2.13 in) is not independently verifiable; diagram/data are faint.**
### Q11 — Equidistant path (parabola)
**Problem:** A ship must follow a path equidistant from a point 9 km north of a harbor port and a due-east line located 3 km south of that port. Taking the port as the origin, find the path’s equation.

<svg viewBox="0 0 330 190" role="img" aria-label="Coordinate sketch of upward-opening parabola with focus 9 kilometres north of port, vertex 3 kilometres north, and horizontal directrix 3 kilometres south" xmlns="http://www.w3.org/2000/svg"><path d="M40 120 H300 M170 175 V20" stroke="#617182" stroke-width="2"/><path d="M40 150 H300" stroke="#b36b00" stroke-width="2" stroke-dasharray="5 4"/><path d="M95 22 Q170 100 245 22" fill="none" stroke="#087e8b" stroke-width="3"/><circle cx="170" cy="40" r="5" fill="#17324d"/><circle cx="170" cy="90" r="4" fill="#087e8b"/><text x="178" y="43" font-size="12">Focus (0,9)</text><text x="178" y="94" font-size="12">Vertex (0,3)</text><text x="43" y="166" font-size="11">Directrix y=−3 km</text><text x="180" y="117" font-size="11">Port (0,0)</text><text x="245" y="117" font-size="10" fill="#617182">x²=24(y−3)</text></svg>

**Solution:** With port at \((0,0)\), focus \((0,9)\) km and directrix \(y=-3\) km, the vertex is \((0,3)\) and \(p=6\) km. The vertical-axis parabola is \(x^2=4p(y-3)=24(y-3)\), or \(\boxed{x^2-24y+72=0}\). **Answer A.**
### Q12 — Baseball distance rate
**Problem:** A baseball diamond is a 90-ft square. A player runs toward first base at 30 ft/s. When the player is halfway to first, at what rate is the distance to second base changing?

<svg viewBox="0 0 300 170" role="img" aria-label="90 foot square baseball diamond with runner halfway to first and distance to second base" xmlns="http://www.w3.org/2000/svg"><path d="M55 135 L215 135 L215 25 L55 25 Z" fill="#f6f1e5" stroke="#17324d" stroke-width="3"/><circle cx="135" cy="135" r="6" fill="#b36b00"/><path d="M135 135 L215 25" stroke="#087e8b" stroke-dasharray="5 4" stroke-width="2"/><text x="69" y="128" font-size="12">45 ft</text><text x="182" y="81" font-size="12">y</text><text x="217" y="29" font-size="12">Second</text><text x="45" y="157" font-size="11" fill="#617182">Schematic 90-ft square</text></svg>

**Solution:** Let \(x\) be distance from home and \(y\) distance to second base. The square diamond gives \(y^2=(90-x)^2+90^2\); differentiation gives \(2y\,dy/dt=-2(90-x)dx/dt\). At \(x=45\) ft, \(y=45\sqrt5\) ft and \(dx/dt=30\) ft/s, hence \(dy/dt=-6\sqrt5=-13.4\text{ ft/s}\). **Distance decreases at 13.4 ft/s; keyed C gives magnitude.**
### Q13 — Maximum gutter capacity
**Problem:** A 12-cm-wide rectangular metal sheet is formed into a rain gutter by turning up both sides perpendicular to the base. How high should the sides be turned to maximize the gutter’s capacity?

<svg viewBox="0 0 300 125" role="img" aria-label="Gutter cross section formed by turning up two sides of a 12 centimetre sheet" xmlns="http://www.w3.org/2000/svg"><path d="M45 35 V92 H255 V35" fill="#edf4f7" stroke="#17324d" stroke-width="4"/><text x="52" y="68" font-size="12">x</text><text x="237" y="68" font-size="12">x</text><text x="108" y="80" font-size="12">12 − 2x</text><text x="105" y="118" font-size="11" fill="#617182">Cross-section schematic</text></svg>

**Solution:** If each side is turned up by \(x\) cm, the base is \(12-2x\) cm and area per unit length is \(A=x(12-2x)\). Since \(A'=12-4x=0\) gives \(x=3\) cm and \(A''=-4<0\), this is a maximum. **Answer B.**
### Q14 — Particle velocity
**Problem:** A particle’s position is x = 2t² + 3 and y = t⁴ in the xy-plane. Find the x-component of its velocity at t = 5.

**Solution:**

The x-velocity is \(v_x=dx/dt=d(2t^2+3)/dt=4t\). At \(t=5\) s, \(v_x=20\) position-units/s. **Answer C; position units are not specified in the prompt.**
### Q15 — Time near top of jump
**Problem:** A basketball player’s height is h(t) = −16t² + 16Tt feet, where T is the total jump duration. For T = 1 s, how long is the player at or above 75% of the maximum jump height?

**Solution:** At \(T=1\) s, \(h=-16t^2+16t\) ft; its maximum occurs at \(t=0.5\) s and is 4 ft. Solve \(h=0.75(4)=3\): \(-16t^2+16t=3\), giving \(t=0.25,0.75\) s. Duration is \(0.50\) s. **Answer C.**
### Q16 — Cooling model
**Problem:** A cake is 300°F when removed from an oven and 200°F three minutes later. Using Newton’s cooling model, formulate its temperature as a function of time and determine how long it takes to reach room temperature, 70°F.

**Solution:** Newton cooling: \(T=70+(300-70)e^{-kt}\). From \(T(3)=200\), \(k=\ln(230/130)/3=0.1902\text{ min}^{-1}\). Thus \(T(t)=70+230e^{-0.1902t}\ ^\circ\!F\). The exponential is positive for every finite \(t\), so it approaches 70°F without reaching it exactly. **Key B matches the model; no finite time reaches the exact target.**
### Q17 — Temperature gradient; faint expression
**Problem:** Temperature in a rectangular box is approximated by a function of position. A mosquito at (1/2, 1, 1) wants to cool as quickly as possible. In what direction should it move? The temperature expression and box bounds are unreadable in the scan.

**Solution:** Temperature decreases fastest along \(-\nabla T\). For the missing field \(T(x,y,z)\), evaluate \(\mathbf d=-\nabla T(1/2,1,1)\); normalize if a unit direction is requested. The field is unreadable, so a numerical vector cannot be calculated. **Key check A only; clearer source needed.**
### Q18 — Mean value; faint expression
**Problem:** Find the mean value of the stated function over the stated interval using the mean value for integrals. The function and interval bounds are too faint to read reliably.

**Solution:** The mean value is \(f_{avg}=\frac1{b-a}\int_a^b f(x)\,dx\). The function and interval limits are not legible in the available transcription, so a numeric result cannot be justified. **Key check B only; clearer source needed.**
### Q19 — Expected insurance claim
**Problem:** An insurer charges Php60,000 annually for car insurance and pays Php100,000 for a minor accident or Php500,000 for a major accident. The annual probabilities are 0.2 for a minor accident and 0.05 for a major accident. What amount can the company expect to make per policy?

**Solution:** Expected annual claims are \((0.20)(\text{Php100,000})+(0.05)(\text{Php500,000})=\text{Php45,000}\). Expected gain after the Php60,000 premium is \(60,000-45,000=\text{Php15,000 per policy-year}\). **Key D (Php35,000) conflicts with the stated probabilities.**
### Q20 — Present worth of escalating maintenance
**Problem:** Maintenance for an engine is expected to cost $1,555 at the end of year 1, increasing by $35 each year for the following years. At 6% interest, how much should be set aside now to cover the eight-year maintenance period? The problem lists P/A = 6.2098, A/F = 0.1010, F/A = 9.897, and P/G = 19.8445.

**Solution:** For an eight-year arithmetic gradient, \(P=A_1(P/A,i,8)+G(P/G,i,8)\). Using \(A_1=\$1,555\), \(G=\$35\), \(i=6\%\), and supplied factors 6.2098 and 19.8445: \(P=1555(6.2098)+35(19.8445)=\$10,350.8\approx\$10,351\). **This conflicts with the choices/key ($1,697); source inputs or factor application appear inconsistent.**
### Q21 — Buy or rent dump truck
**Problem:** A contractor can buy a dump truck for Php800,000 or rent one for Php1,189 per truck per day. The truck’s salvage value after its 5-year useful life is Php100,000, and annual maintenance costs Php20,000. At 14% annual interest, how many days per year must it be used to justify buying it?

**Solution:** Buying is justified when annual ownership cost does not exceed rent: \(A=800{,}000(A/P,14\%,5)-100{,}000(A/F,14\%,5)+20{,}000\). With factors 0.291284 and 0.151284, \(A\approx\text{Php237,898/year}\). Break-even use is \(237,898/1,189\approx200.1\) days/year. **About 200 days; nearest choice C.**
### Q22 — House price with inflation
**Problem:** A house costs Php1,000,000 in 1991. If annual inflation is 6%, what would the same model cost in 1996?

**Solution:** There are \(1996-1991=5\) periods. \(F=P(1+i)^n=\text{Php1,000,000}(1.06)^5=\text{Php1,338,226}\). **Answer B.**
### Q23 — Car spring compression
**Problem:** A family of four has a total mass of 200 kg and steps into a 1,200-kg car, compressing its spring by 3 cm. Assuming a single spring, how much lower will the car sit when loaded with 300 kg instead of 200 kg?

<svg viewBox="0 0 320 160" role="img" aria-label="Schematic side-by-side spring supports showing 3 centimetres compression under 200 kilograms and 4.5 centimetres under 300 kilograms" xmlns="http://www.w3.org/2000/svg"><path d="M25 135 H295 M55 55 H145 M185 75 H275" stroke="#17324d" stroke-width="3"/><path d="M100 55 V65 L89 72 L111 79 L89 86 L111 93 L89 100 L111 107 L100 114 V135 M230 75 V82 L219 89 L241 96 L219 103 L241 110 L219 117 L241 124 L230 131 V135" fill="none" stroke="#087e8b" stroke-width="3"/><text x="47" y="40" font-size="12">200 kg: 3 cm</text><text x="176" y="60" font-size="12">300 kg: 4.5 cm</text><text x="73" y="155" font-size="11" fill="#617182">Same spring and baseline; schematic</text></svg>

**Solution:** For the same spring, the 200-kg supported load causes 3-cm compression, so \(k=200g/0.03\). At 300 kg, \(x=300g/k=0.045\text{ m}=4.5\text{ cm}\), or an additional 1.5 cm lower than at 200 kg. **Answer C, treating the stated masses as supported loads.**
### Q24 — Spring constant from falling ball
**Problem:** A 2.60-kg ball falls from rest through 55 cm before striking a vertical coiled spring and compressing it by 15 cm. Find the spring stiffness k.

<svg viewBox="0 0 320 170" role="img" aria-label="Ball falls 55 centimetres onto a spring and compresses it 15 centimetres" xmlns="http://www.w3.org/2000/svg"><path d="M55 20 V145 H270" stroke="#17324d" stroke-width="3" fill="none"/><circle cx="145" cy="36" r="14" fill="#dce9e7" stroke="#17324d" stroke-width="2"/><circle cx="145" cy="87" r="14" fill="#dce9e7" stroke="#17324d" stroke-width="2"/><path d="M130 101 V114 L119 121 L141 128 L119 135 L141 142 L130 150" fill="none" stroke="#087e8b" stroke-width="3"/><text x="178" y="58" font-size="12">55 cm fall</text><text x="178" y="124" font-size="12">15 cm compression</text><text x="83" y="165" font-size="11" fill="#617182">Schematic from stated distances</text></svg>

**Solution:** At maximum compression the ball has fallen \(0.55+0.15=0.70\) m and is momentarily at rest. Energy balance: \(mg(h+x)=\tfrac12kx^2\). Thus \(k=2(2.60)(9.81)(0.70)/(0.15)^2=1,587\text{ N/m}\). **Closest/keyed D: 1,585 N/m; small numerical discrepancy.**
### Q25 — Power against friction
**Problem:** A person pushes a 50.0-kg box across a level floor at a constant 1.00 m/s for 10.0 s. If the coefficient of friction is 0.200, find the person’s average power output.

**Solution:** At constant speed, the applied force balances friction: \(F=\mu_kmg=(0.200)(50.0)(9.81)=98.1\text{ N}\). Power is \(P=Fv=(98.1)(1.00)=98.1\text{ W}\). **Answer B (98 W).**
### Q26 — Centripetal acceleration
**Problem:** A 150-g ball at the end of a string moves uniformly in a horizontal circle of radius 0.600 m, completing 2 revolutions per second. Find its centripetal acceleration.

<svg viewBox="0 0 260 150" role="img" aria-label="Ball on a horizontal circular path with inward centripetal acceleration and radius 0.600 metre" xmlns="http://www.w3.org/2000/svg"><circle cx="125" cy="78" r="52" fill="none" stroke="#17324d" stroke-width="2" stroke-dasharray="5 4"/><circle cx="125" cy="78" r="4" fill="#17324d"/><circle cx="177" cy="78" r="8" fill="#087e8b"/><path d="M169 78 H135" stroke="#b36b00" stroke-width="3"/><text x="135" y="67" font-size="11">aᶜ inward</text><text x="134" y="98" font-size="11">r=0.600 m</text><text x="30" y="140" font-size="11" fill="#617182">Schematic circular path</text></svg>

**Solution:** The frequency is \(2\) rev/s, so \(\omega=2\pi f=4\pi\) rad/s. Then \(a_c=\omega^2r=(4\pi)^2(0.600)=94.7\text{ m/s}^2\). Mass is not needed. **Answer D.**
### Q27 — Jazz trios
**Problem:** A music school has 3 drummers, 4 trumpet players, and 5 pianists. How many distinct jazz trios can be formed with one musician from each group?

**Solution:** By the multiplication principle, \(3\times4\times5=60\) possible trios, one musician from each group. **Answer B.**
### Q28 — Board arrangements
**Problem:** A fence uses 5 boards 2 in wide, 10 boards 3 in wide, and 5 boards 4 in wide. How many distinct arrangements use all the boards?

**Solution:** Arrange 20 boards with repeated widths: \(N=20!/(5!10!5!)=46,558,512\) distinct sequences. **Answer B.**
### Q29 — Guessing probability
**Problem:** A six-question multiple-choice test has three possible answers per question, exactly one correct. A student guesses every answer. What is the probability of passing by answering at least four correctly?

**Solution:** For \(X\sim\operatorname{Binomial}(6,1/3)\), passing means at least four correct: \(P(X\ge4)=\sum_{k=4}^6\binom6k(1/3)^k(2/3)^{6-k}=73/729=0.1001\). **Answer D.**
### Q30 — Compass-rule traverse; stated line mismatch
**Problem:** Using the supplied traverse field-note table and the compass rule, calculate the adjusted distance of line BA. The table lists lines AB, BC, CD, DE, and EA; the target line’s label does not match the table.

<svg viewBox="0 0 330 175" role="img" aria-label="Schematic closed traverse with listed lines AB, BC, CD, DE, EA; target BA is not listed" xmlns="http://www.w3.org/2000/svg"><path d="M55 130 L105 40 L218 35 L275 112 L165 150 Z" fill="#f5f8fa" stroke="#17324d" stroke-width="3"/><text x="40" y="143" font-size="12">A</text><text x="98" y="35" font-size="12">B</text><text x="220" y="32" font-size="12">C</text><text x="280" y="117" font-size="12">D</text><text x="160" y="168" font-size="12">E</text><text x="50" y="78" font-size="11">AB</text><text x="156" y="31" font-size="11">BC</text><text x="251" y="71" font-size="11">CD</text><text x="230" y="144" font-size="11">DE</text><text x="94" y="147" font-size="11">EA</text><text x="63" y="18" font-size="10" fill="#617182">Schematic only; field values/bearings unavailable</text></svg>

**Solution:** For line length \(L_i\), compass-rule corrections are \(c_{Lat,i}=-\Sigma Lat\,(L_i/\Sigma L)\), \(c_{Dep,i}=-\Sigma Dep\,(L_i/\Sigma L)\). Then \(L_{adj}=\sqrt{(Lat_i+c_{Lat,i})^2+(Dep_i+c_{Dep,i})^2}\). Table values are missing from this transcription, so the adjustment cannot be independently evaluated. **The prompt asks for BA but lists AB; keyed D (677.9784 m) remains unverified.**
### Q31 — Actual bucket load
**Problem:** Estimate the actual bucket load in bank cubic meters for a scraper with 3.92 m³ heaped capacity, soil bucket fill factor 0.90, and load factor 0.60.

**Solution:** Using both stated factors, \(V_{BCM}=V_{heaped}F_{fill}F_{load}=(3.92\text{ m}^3)(0.90)(0.60)=2.12\text{ BCM}\). Keyed 2.35 BCM equals \(3.92(0.60)\), omitting the fill factor. **Prompt, choices, and key conflict.**
### Q32 — Combined rolling and grade resistance
**Problem:** A 36-t crawler tractor tows a 45.5-t rubber-tired scraper up a 4% grade. The scraper’s rolling-resistance factor is 50 kg/t, and 1 t = 1,000 kg. Find the total resistance of the combination in kilograms.

**Solution:** Scraper rolling resistance: \(R_r=(50\text{ kgf/t})(45.5\text{ t})=2,275\text{ kgf}\). Grade resistance on combined mass: \(R_g=0.04(36,000+45,500)=3,260\text{ kgf}\). Total \(R=2,275+3,260=5,535\text{ kgf}\) (kilograms-force, as implied by the problem’s convention). **Answer D.**
### Q33 — Dozer production
**Problem:** A power-shift crawler dozer has a rated blade capacity of 7.65 LCM and pushes loose common earth 61 m. Its maximum reverse speed in third range is 8 km/h, and job efficiency is 50 min/h. Use the supplied typical fixed-cycle-time and operating-speed tables to estimate production.

<svg viewBox="0 0 370 110" role="img" aria-label="Dozer cycle schematic with 61 metre push and reverse return" xmlns="http://www.w3.org/2000/svg"><path d="M45 45 H320 M320 76 H45" stroke="#087e8b" stroke-width="3"/><path d="M320 45 l-10 -6 v12 z M45 76 l10 -6 v12 z" fill="#087e8b"/><text x="103" y="37" font-size="12">Push 61 m at 3.2 km/h</text><text x="103" y="98" font-size="12">Return 61 m at 8 km/h</text><text x="42" y="18" font-size="10" fill="#617182">Cycle schematic; values from prompt/table transcription</text></svg>

**Solution:** Convert speeds: 3.2 km/h = 53.33 m/min and 8 km/h = 133.33 m/min. The 61-m push/return cycle time is \(t_c=0.05+61/53.33+61/133.33=1.651\) min. Production is \(Q=(7.65\text{ LCM/cycle})(50\text{ min/h})/(1.651\text{ min/cycle})=232\text{ LCM/h}\). **This conflicts with keyed 269 LCM/h.**
### Q34 — Excavator production
**Problem:** Estimate the expected production of a small hydraulic excavator in loose cubic meters per hour. Its heaped bucket capacity is 0.57 m³; it excavates sand and gravel; bucket fill factor is 0.95; job efficiency is 50 min/h; average cut depth is 4.3 m; maximum cut depth is 6.1 m; and average swing is 90°. The stated hint gives production = cycle output × cycle speed × swing-depth factor × bucket factor × efficiency, with cycle output 250 cycles per 60 min and swing-depth factor 1.00.

**Solution:** Operating time is \(50/60\) h per clock hour. Production is \((250\text{ cycles}/60\text{ min})(60\text{ min/h})(50/60)(1.00)(0.57\text{ m}^3/\text{cycle})(0.95)=112.8\text{ LCM/h}\). **Answer A (113 LCM/h).**
### Q35 — Road alignment signs
**Problem:** Which signs are used to guide drivers through a change in the road’s horizontal alignment?

**Solution:** Chevron signs indicate the direction of a horizontal curve and guide drivers along it. **Answer A.**
### Q36 — National-road lane width
**Problem:** What is the basic lane width appropriate for national roads?

**Solution:** The stated basic national-road lane width is **3.35 m (Answer C)**. This recall item provides no further design conditions to derive a different width.
### Q37 — Road delineation devices
**Problem:** Road delineation is used to provide adequate alignment guidance to road users. Which of the listed device types are used for this purpose: pavement markings, signs, guide posts, reflective delineators, lighting, and curbs or other physical devices?

**Solution:** All listed devices—pavement markings, signs, guide posts, reflective delineators, lighting, and physical devices—can provide alignment guidance. **Answer D (all).**
### Q38 — Navigation, guidance, control
**Problem:** The three essential elements of operating a motor vehicle—navigation, guidance, and control—together describe what concept?

**Solution:** Navigation, guidance, and control together describe the **driving task**. **Answer C.**
### Q39 — Destination information signs
**Problem:** What type of sign informs road users of directions and distances to destinations along their route or at intersecting roads?

**Solution:** Directional and distance information to destinations is provided by **guide signs**. **Answer B.**
### Q40 — Cumulative queuing curves
**Problem:** For cumulative queuing diagrams A(t) and D(t), assess these statements: (I) their slopes give arrival and departure rates, respectively; (II) departure rate cannot exceed server capacity; (III) cumulative departures cannot exceed cumulative arrivals; and (IV) with a queue, departures occur at service capacity, while without a queue they match arrivals, with a queue forming when arrivals first exceed service capacity. Which statements are correct?

**Solution:** For cumulative counts \(A(t),D(t)\), slopes give rates: \(\lambda=dA/dt\), \(\mu=dD/dt\). Departures cannot exceed service capacity; with an initially empty system \(D(t)\le A(t)\). With a persistent queue, service works at capacity; without a queue, departures track arrivals up to capacity. **Intended key B (all), assuming an initially empty system; statement I’s referenced figure is unavailable for full verification.**
### Q41 — Sea structure projecting from shore
**Problem:** What is the term for a structure built into the sea, not parallel to the coastline, including a berth structure that projects outward from shore?

**Solution:** A **pier** projects from the shoreline into water and may provide berthing. **Answer B.**
### Q42 — Concrete mold
**Problem:** Fresh concrete cannot retain a particular shape before it sets, so it is placed in a form or mold. What is this called in building construction?

**Solution:** The temporary mold that holds and shapes fresh concrete until it hardens is **formwork**. **Answer A.**
### Q43 — Scaffold capacity requirement
**Problem:** What capacity requirement applies to all scaffolds?

**Solution:** Scaffold capacity requirements are generally stated relative to the maximum intended load, often as a required multiple. The choices as transcribed refer to the scaffold’s own weight and do not state the criterion. **The item is defective as transcribed; keyed D is not verified.**
### Q44 — Vibration dissipation
**Problem:** What term describes a material’s ability to dissipate or deaden mechanical vibrations?

**Solution:** The ability to dissipate mechanical vibration energy is **damping**. **Answer A.**
### Q45 — Pile-driving formula inputs
**Problem:** For determining the safe capacity of piles driven by powered hammers, which data are used: average penetration per blow over the last six blows; hammer energy; hammer weight; pile weight including appurtenances; and a coefficient of restitution depending on hammer and pile weights?

**Solution:** Dynamic pile formulas relate delivered hammer energy to pile penetration/set and account for ram and pile weights, energy loss, and restitution. For example, Hiley-type relations include terms of the form \(Q_u\propto\frac{E_h}{S+C/2}\frac{W_r+e^2W_p}{W_r+W_p}\), with allowable resistance \(Q_{allow}=Q_u/FS\). The listed categories are generally relevant, but elastic compression \(C\), safety factor, and the meaning of the six-blow average are not fully stated. **D (all) is the keyed selection; exact formula inputs cannot be confirmed from the transcription.**
### Q46 — Safety discussion
**Problem:** What is the name for an informal group discussion focused on a particular safety issue, used regularly to promote safety culture and support health-and-safety discussions at job sites?

**Solution:** A regular informal job-site safety discussion is a **toolbox meeting/talk**. **Answer B.**
### Q47 — Excavation cave-in protection
**Problem:** What is the general term for methods that protect workers from cave-ins and falling or rolling material, including support, sloping, benching, and shield systems, and protect adjacent structures from collapse?

**Solution:** Shoring, sloping, benching, and shielding are types of a **protective system** for excavation hazards. **Answer C.**
### Q48 — Excavation in steps
**Problem:** What excavation method protects workers from cave-ins by cutting the excavation sides into one or more horizontal levels or steps, usually with vertical or near-vertical surfaces between levels?

**Solution:** Cutting excavation sides into horizontal steps is **benching**. **Answer A.**
### Q49 — Binding agreement
**Problem:** What is a formal or legally binding agreement between two parties called?

**Solution:** A legally binding agreement between parties is a **contract**. **Answer D.**
### Q50 — Post-construction completion stage
**Problem:** What stage follows construction completion and resolution of most punch-list and commissioning issues?

**Solution:** Transfer of the completed project to the owner/operator after closeout is **turnover**. **Answer C.**
### Q51 — Elevation against facility centerline distance
**Problem:** What type of drawing uses elevation as the vertical axis and horizontal distance along a facility centerline or other reference line as the horizontal axis?

**Solution:** A plot of elevation against distance or station along a centerline is a **profile**. **Answer C.**
### Q52 — Bar-chart drawbacks
**Problem:** Which are drawbacks of bar charts: (I) activities appear independent of one another; (II) activity sequence is not defined; and (III) it is difficult to judge whether an activity is complete?

**Solution:** Bar charts show activities without clearly representing dependencies or sequence, and completion status may be hard to judge. Statements I–III are drawbacks. **Answer D.**
### Q53 — PERT time estimates
**Problem:** When preparing a PERT/CPM network for a construction project, which time estimates should be considered: optimistic, most probable, and pessimistic?

**Solution:** PERT uses optimistic \(t_o\), most likely \(t_m\), and pessimistic \(t_p\) duration estimates. (When needed, expected time is \(t_e=(t_o+4t_m+t_p)/6\).) **Answer D (all three).**
### Q54 — Detailed material/equipment/workmanship requirements
**Problem:** What document provides detailed requirements for the materials, equipment, and workmanship to be incorporated into a project?

**Solution:** Project **specifications** set detailed requirements for materials, equipment, and workmanship. **Answer C.**
### Q55 — Bucket volume to side-outline level
**Problem:** What is the name for the volume a bucket holds up to the outline of its sides?

**Solution:** Struck or plate-line capacity is the bucket volume up to the level of the side edges. **Answer D (plate line capacity).**

---
