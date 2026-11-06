# May 2022 MSTC (Questions 1–55)

[← All problem sets](ce-ref.html)

Worked solutions for all 55 May 2022 MSTC questions. Faint values, ambiguous wording, and key conflicts are flagged. Q45 is derived from the stated inputs using the standard pile-driving relation.

## Questions 1–10

### Q1 — Stock allocation
**Problem:** An investment firm must place Php100,000 in stocks A and B. Stock A returns 15% annually, but no more than Php50,000 may be invested in it; the more stable stock B returns 10%. How should the funds be divided to earn Php13,000 per year?

**Solution:** With

$A+B=100{,}000$

, the annual return is

$0.15A+0.10B=10{,}000+0.05A$

. Earning

\[
13{,}000
\]

 requires

$A=60{,}000$

, but the prompt caps A at

\[
50{,}000
\]

. At that cap, the maximum return is

\[
12{,}500
\]

. **No feasible allocation meets all the stated conditions; keyed choice D violates the cap.**

### Q2 — Rope cuts; wording ambiguity
**Problem:** A 213-ft rope is to be cut into three pieces, each 2 ft longer than the previous piece. Where should the cuts be made?

**Solution:** The intended three lengths are

\[
x,x+2,x+4
\]

 ft. Their sum gives

$3x+6=213$

, hence lengths 69, 71, and 73 ft. The cut locations measured from one end are 69 and

$69+71=140$

 ft. The choices list “69 and 73,” apparently the first and last piece lengths rather than the two cut positions. **Key: A (69 and 73); the wording “where should he make the cuts?” is imprecise.**

### Q3 — Ball dropped downward
**Problem:** A ball is thrown downward from a 180-ft building at 20 ft/s. Its height after t seconds is h = −16t² − 20t + 180. How long until it reaches the ground?

**Solution:** Set ground height h = 0:

$-16t^2-20t+180=0$

. The positive root is

$t=\frac{-20+\sqrt{11920}}{32}\approx2.80$

 s. The displayed equation's negative signs correctly represent downward initial velocity and gravity. **Answer: B (2.8 s). Key check: B.**

### Q4 — Starbucks store model conflict
**Problem:** The question gives the model f(x) = 115x² + 117x + 3963 and asks for the value in 2004, with x interpreted relative to year 2000. What value does the model predict?

**Solution:** Taking x = 4 gives f(4) = 115(4²) + 117(4) + 3963 = 6,271. This differs from the keyed value of 6,721 and the available choices; the model and answer key do not agree.

### Q5 — Radioactive material
**Problem:** After a nuclear accident, radioactive debris enters the atmosphere and may affect the milk supply. The percentage of radioactive material in raw milk after t days is modeled by y = 100(2.7)^(−t/14). Estimate the percentage after 30 days. The exponent is faint in the scan.

**Solution:** The problem gives

$y=100(2.7)^{-t/14}$

 percent. At

$t=30$

,

$y=100(2.7)^{-30/14}\approx14.3\%$

. The answer choices continue at the top of the next scan and read 6%, 7%, 4%, 5%; none matches this literal evaluation. The exponent is faint, so the model reading is uncertain. **Key check: D (5%); source expression/options do not reconcile on the readable scan.**

### Q6 — Gable triangle
**Problem:** A house has a triangular gable end with two 42-ft sides meeting at an angle of 115°. Find the gable’s area.

**Solution:** (A=\tfrac12

$42$



$42$

\sin115^\circ\approx799\,\mathrm{ft^2}). **Answer: A. Key check: A.**

### Q7 — Relative ship bearing
**Problem:** Two ships leave port at the same time. One sails N 23° E at 11 mph and the other S 67° E at 15 mph. After one hour, what is the bearing from the second ship to the first?

**Solution:** The diagram gives the ships’ positions after one hour. Resolving each course into east/north components gives a relative position of approximately 9.5 mi west and 16 mi north, or a bearing near N31°W. **Answer: A. Key check: A.**

### Q8 — Mountain height from two stations
**Problem:** A surveyor observes a mountain from a transit 1.5 m above the ground at two stations 1,200 m apart on level ground. The elevation angles are 51° and 38°. Find the mountain height above ground level.

**Solution:** Using the two elevation angles and the stated station spacing, the calculations give a mountain height of approximately 2,544 m. **Answer: B

\[
2,544 m
\]

. Key check: B.**

### Q9 — Three-point mountain geometry
**Problem:** In mountainous terrain, a geologist measures two points B and C, 928 m apart. The elevation angle from B to mountain top A is 47°10′; the angles of elevation from C to B and from C to A are 8°40′ and 32°30′, respectively. If C is at elevation 1,621 m, find A’s elevation.

**Solution:** Let the known elevation at C be 1621 m. The angle at C from B to A is

\[
32^\circ30'
\]

; the angle at B from C to A is

\[
8^\circ40'
\]

. With

$BC=928$

 m, the triangle's third angle is

\[
138^\circ50'
\]

. By the sine rule, (AC=928\sin

\[
8^\circ40'
\]

/\sin

\[
32^\circ30'
\]

\approx263) m. The elevation difference is

\[
AC\tan32^\circ30'\approx168
\]

 m, so A is about 1789 m if A is above C. The diagram/phrasing does not clearly establish vertical reference and sight-line orientation, and this does not match the choices. **Key check: B

\[
2847 m
\]

; geometry as legible does not support the keyed value.**

### Q10 — Belt around small shaft and pulley
**Problem:** A 20-in belt connects a very small motor shaft to a pulley whose center is 4 in from the shaft. Treat the shaft as a point. If 8.5 in of belt contacts the pulley, find the pulley radius to the nearest tenth of an inch.

**Solution:** For an open belt with center distance

$C=4$

 in, shaft radius (r) (faint), and large radius (R), belt length is approximately (2C+\pi\(R+r\)+(R-r)^2/C). The printed contact length appears to be 8.5 in, but the small shaft radius cannot be read reliably; the belt-length equation therefore does not determine a defensible unique (R) from this scan transcription. **Key check: D

\[
2.13 in
\]

; faint diagram/data prevent independent confirmation.**

## Questions 11–20

### Q11 — Equidistant path (parabola)
**Problem:** A ship must follow a path equidistant from a point 9 km north of a harbor port and a due-east line located 3 km south of that port. Taking the port as the origin, find the path’s equation.

**Solution:** The focus is 9 km north of the harbor origin, and the direct-east line is the directrix

$y=0$

; the vertex is halfway, ((0,4.5)), with vertical axis. Thus (x^2=-18(y-4.5)), or

$x^2+18y-81=0$

. This does not exactly match the scanned choices, which use coefficient 24 and constant 72; the stated focus/directrix distances may be represented differently in the source. **Key check: A; geometry/equation discrepancy.**

### Q12 — Baseball distance rate
**Problem:** A baseball diamond is a 90-ft square. A player runs toward first base at 30 ft/s. When the player is halfway to first, at what rate is the distance to second base changing?

**Solution:** Let x be the runner’s distance from home and y the distance to second base. Differentiate the right-triangle relation for the diamond and substitute the runner’s position and speed from the question; the resulting rate is 6√5 ft/s. **Answer: C. Key check: C.**

### Q13 — Maximum gutter capacity
**Problem:** A 12-cm-wide rectangular metal sheet is formed into a rain gutter by turning up both sides perpendicular to the base. How high should the sides be turned to maximize the gutter’s capacity?

**Solution:** If each side is turned up (x) cm, cross-sectional area is (A=x

\[
12-2x
\]

). Then

$dA/dx=12-4x=0$

, giving

$x=3$

 cm. **Answer: B. Key check: B.**

### Q14 — Particle velocity
**Problem:** A particle’s position is x = 2t² + 3 and y = t⁴ in the xy-plane. Find the x-component of its velocity at t = 5.

**Solution:**

$x=2t^2+3$

, so

$v_x=dx/dt=4t$

. At

$t=5$

,

$v_x=20$

. **Answer: C. Key check: C.**

### Q15 — Time near top of jump
**Problem:** A basketball player’s height is h(t) = −16t² + 16Tt feet, where T is the total jump duration. For T = 1 s, how long is the player at or above 75% of the maximum jump height?

**Solution:** For (h(t)=-16t^2+16t), the peak is at

$t=0.5$

 s and

$h_{max}=4$

 ft. At 75% peak, solve

$h=3$

: (16t

\[
1-t
\]

=3), giving

$t=0.25,0.75$

. Time spent there is 0.50 s. **Answer: C. Key check: C.**

### Q16 — Cooling model
**Problem:** A cake is 300°F when removed from an oven and 200°F three minutes later. Using Newton’s cooling model, formulate its temperature as a function of time and determine how long it takes to reach room temperature, 70°F.

**Solution:** Newton cooling gives

$T=70+230e^{-kt}$

. From (T

$3$

=200), (k=\ln

\[
230/130
\]

/3\approx0.1909\,\mathrm{min^{-1}}). It approaches 70°F asymptotically and never reaches it at a finite time. **Key check: B (the matching model form); “how long to cool to 70°F” has no finite solution.**

### Q17 — Temperature gradient; faint expression
**Problem:** Temperature in a rectangular box is approximated by a function of position. A mosquito at (1/2, 1, 1) wants to cool as quickly as possible. In what direction should it move? The temperature expression and box bounds are unreadable in the scan.

**Solution:** Temperature decreases fastest in the direction opposite its gradient, \(-\nabla T\), evaluated at (

\[
1/2,1,1
\]

). The printed multivariable polynomial and vector choices are too faint to transcribe confidently in the problem, so a numerical direction cannot be independently derived. **Key check: A. Expression unreadable; letter retained from key only.**

### Q18 — Mean value; faint expression
**Problem:** Find the mean value of the stated function over the stated interval using the mean value for integrals. The function and interval bounds are too faint to read reliably.

**Solution:** The scan asks for a mean value of a function over an interval, but the function and bounds are faint. The mean-value formula is (f_{avg}=(b-a)^{-1}\int_a^b f(x)\,dx); insufficiently legible input prevents a reliable numerical evaluation. **Key check: B. Expression/bounds require a clearer source image.**

### Q19 — Expected insurance claim
**Problem:** An insurer charges Php60,000 annually for car insurance and pays Php100,000 for a minor accident or Php500,000 for a major accident. The annual probabilities are 0.2 for a minor accident and 0.05 for a major accident. What amount can the company expect to make per policy?

**Solution:** Expected payout is (100{,}000

$0.2$

+500{,}000

$0.05$

=45{,}000) pesos. Subtract the annual premium of 60,000 to get expected gain of 15,000 pesos, or expected underwriting profit of 15,000 if “make” means premium less claims. No choice gives 15,000; the key says D

$35,000$

. The scan may intend a different major-claim probability/wording, but it is legible as 0.05. **Key check: D; calculation/key conflict.**

### Q20 — Present worth of escalating maintenance
**Problem:** Maintenance for an engine is expected to cost $1,555 at the end of year 1, increasing by $35 each year for the following years. At 6% interest, how much should be set aside now to cover the eight-year maintenance period? The problem lists P/A = 6.2098, A/F = 0.1010, F/A = 9.897, and P/G = 19.8445.

**Solution:** The payments form an arithmetic gradient: first payment 1,555 at year 1, then +35 per year for 8 years,

$i=6\%$

. Present worth is (1555

\[
P/A,6\%,8
\]

+35(P/G,6\%,8)), using listed factors 6.2098 and 19.8445:

\[
9{,}656+694.6\approx10{,}351
\]

 dollars. This does not match the listed $1,576–$1,776 choices, suggesting a missing decimal/scale or corrupted amount. **Key check: C

\[
$1,697
\]

; the present-worth factor/application in the source differs from the direct arithmetic-gradient result.**

## Questions 21–30

### Q21 — Buy or rent dump truck
**Problem:** A contractor can buy a dump truck for Php800,000 or rent one for Php1,189 per truck per day. The truck’s salvage value after its 5-year useful life is Php100,000, and annual maintenance costs Php20,000. At 14% annual interest, how many days per year must it be used to justify buying it?

**Solution:** Annualized ownership cost uses capital recovery on

\[
800{,}000-100{,}000
\]

 plus salvage: (800{,}000

\[
A/P,14\%,5
\]

-100{,}000

\[
A/F,14\%,5
\]

+20{,}000\). Divide this annual amount by rental cost Php1,189/day to find the break-even use-days; the printed factors/solution yield about 198 days. **Calculated: about 200 days, nearest choice C. Key check: C.**

### Q22 — House price with inflation
**Problem:** A house costs Php1,000,000 in 1991. If annual inflation is 6%, what would the same model cost in 1996?

**Solution:** 1996 is five years after 1991. (P=1{,}000{,}000

$1.06$

^5=Php1{,}338{,}226). But the wording says “In 1991” and asks “in 1996,” which is chronologically coherent; the prior premise reported as reversed is not visible in this scan. **Answer: B. Key check: B.**

### Q23 — Car spring compression
**Problem:** A family of four has a total mass of 200 kg and steps into a 1,200-kg car, compressing its spring by 3 cm. Assuming a single spring, how much lower will the car sit when loaded with 300 kg instead of 200 kg?

**Solution:** Spring stiffness

$k=200g/0.03$

. For 300 kg total, equilibrium compression is

$x=300g/k=0.045$

 m. **Answer: C. Key check: C.**

### Q24 — Spring constant from falling ball
**Problem:** A 2.60-kg ball falls from rest through 55 cm before striking a vertical coiled spring and compressing it by 15 cm. Find the spring stiffness k.

**Solution:** Energy balance over total travel

$h+x=0.55+0.15=0.70$

 m: (mg\(h+x\)=\tfrac12kx^2). Thus (k=2

$2.60$



$9.81$



$0.70$

/

$0.15$

^2\approx1{,}587.04\,\mathrm{N/m}). The options/key list 1,585 N/m (D), a small numerical discrepancy. **Calculated: 1,587.04 N/m. Key check: D

\[
1,585 N/m
\]

.**

### Q25 — Power against friction
**Problem:** A person pushes a 50.0-kg box across a level floor at a constant 1.00 m/s for 10.0 s. If the coefficient of friction is 0.200, find the person’s average power output.

**Solution:** At constant speed, (F=\mu mg=0.2

$50$



$9.81$

=98.1) N. (P=Fv=98.1

$1$

=98.1) W. **Answer: B

\[
98 W
\]

. Key check: B.**

### Q26 — Centripetal acceleration
**Problem:** A 150-g ball at the end of a string moves uniformly in a horizontal circle of radius 0.600 m, completing 2 revolutions per second. Find its centripetal acceleration.

**Solution:** Two revolutions per second gives

$omega=4\pi$

 rad/s. (a_c=\omega^2r=

$4\pi$

^2

$0.6$

=94.75\,\mathrm{m/s^2}). **Answer: D. Key check: D.**

### Q27 — Jazz trios
**Problem:** A music school has 3 drummers, 4 trumpet players, and 5 pianists. How many distinct jazz trios can be formed with one musician from each group?

**Solution:** Choose one drummer, one trumpet player, and one pianist:

$3\cdot4\cdot5=60$

. **Answer: B. Key check: B.**

### Q28 — Board arrangements
**Problem:** A fence uses 5 boards 2 in wide, 10 boards 3 in wide, and 5 boards 4 in wide. How many distinct arrangements use all the boards?

**Solution:** There are 20 boards: 5 of one width, 10 of another, and 5 of a third. The distinct sequences are

\[
20!
\]

/

\[
5!10!5!
\]

 = 46,558,512. **Answer: B. Key check: B.**

### Q29 — Guessing probability
**Problem:** A six-question multiple-choice test has three possible answers per question, exactly one correct. A student guesses every answer. What is the probability of passing by answering at least four correctly?

**Solution:** Each answer is correct with

$p=1/3$

; pass with at least 4 of 6: (\sum_{k=4}^6{6\choose k}

\[
1/3
\]

^k

\[
2/3
\]

^{6-k}=73/729\approx0.1001). **Answer: D

$0.1001$

. Key check: D.**

### Q30 — Compass-rule traverse; stated line mismatch
**Problem:** Using the supplied traverse field-note table and the compass rule, calculate the adjusted distance of line BA. The table lists lines AB, BC, CD, DE, and EA; the target line’s label does not match the table.

**Solution:** The request says adjusted distance of BA, but the table contains AB, BC, CD, DE, EA. With the compass rule, distribute total latitude/departure misclosure proportional to each line length. Applying this to AB (which appears intended instead of BA) gives an adjusted distance near the AB length

\[
about 677.9 m
\]

; exact option selection depends on carrying the faint tabulated values. **Key check: D

\[
677.9784 m
\]

.** The requested BA is absent while AB is present, so the target line is mislabeled.

## Questions 31–40

### Q31 — Actual bucket load
**Problem:** Estimate the actual bucket load in bank cubic meters for a scraper with 3.92 m³ heaped capacity, soil bucket fill factor 0.90, and load factor 0.60.

**Solution:** Applying both stated factors gives

$3.92(0.90)(0.60)=2.12\,\mathrm{BCM}$

. This value is not among the choices. The keyed A value,

\[
2.35\,\mathrm{BCM}
\]

, equals

\[
3.92(0.60)
\]

 and omits the fill factor. **The prompt, choices, and key are inconsistent.**

### Q32 — Combined rolling and grade resistance
**Problem:** A 36-t crawler tractor tows a 45.5-t rubber-tired scraper up a 4% grade. The scraper’s rolling-resistance factor is 50 kg/t, and 1 t = 1,000 kg. Find the total resistance of the combination in kilograms.

**Solution:** Scraper rolling resistance is

$50(45.5)=2{,}275\,\mathrm{kgf}$

. Grade resistance is based on the full combined mass:

$0.04(36{,}000+45{,}500)=3{,}260\,\mathrm{kgf}$

. Total resistance is

$2{,}275+3{,}260=5{,}535\,\mathrm{kgf}$

. **Answer: D.**

### Q33 — Dozer production
**Problem:** A power-shift crawler dozer has a rated blade capacity of 7.65 LCM and pushes loose common earth 61 m. Its maximum reverse speed in third range is 8 km/h, and job efficiency is 50 min/h. Use the supplied typical fixed-cycle-time and operating-speed tables to estimate production.

**Solution:** The table gives a 0.05-min fixed cycle, 3.2 km/h push speed for loose material over 61 m, and 8 km/h reverse speed. Thus

$t_c=0.05+60(0.061/3.2+0.061/8)=1.65$

 min. With 50 min/h efficiency, production is

\[
7.65(50/1.65)\approx232\,\mathrm{LCM/h}
\]

. This differs from the listed/keyed 269 LCM/h; the given speeds and answer key do not agree.

### Q34 — Excavator production
**Problem:** Estimate the expected production of a small hydraulic excavator in loose cubic meters per hour. Its heaped bucket capacity is 0.57 m³; it excavates sand and gravel; bucket fill factor is 0.95; job efficiency is 50 min/h; average cut depth is 4.3 m; maximum cut depth is 6.1 m; and average swing is 90°. The stated hint gives production = cycle output × cycle speed × swing-depth factor × bucket factor × efficiency, with cycle output 250 cycles per 60 min and swing-depth factor 1.00.

**Solution:** (P=250

$1.00$



$0.57$



$0.95$



\[
50/60
\]

=112.8\,\mathrm{LCM/h}\). **Answer: A

\[
113 LCM/h
\]

. Key check: A.**

### Q35 — Road alignment signs
**Problem:** Which signs are used to guide drivers through a change in the road’s horizontal alignment?

**Solution:** Chevron signs guide drivers through changes in horizontal alignment. **Answer: A. Key check: A.**

### Q36 — National-road lane width
**Problem:** What is the basic lane width appropriate for national roads?

**Solution:** The indicated lane width is 3.35 m. **Answer: C. Key check: C.**

### Q37 — Road delineation devices
**Problem:** Road delineation is used to provide adequate alignment guidance to road users. Which of the listed device types are used for this purpose: pavement markings, signs, guide posts, reflective delineators, lighting, and curbs or other physical devices?

**Solution:** Items I–VI include pavement markings, signs, guide posts, reflective delineators, lighting, and physical devices; all can provide alignment guidance. **Answer: D (all). Key check: D.**

### Q38 — Navigation, guidance, control
**Problem:** The three essential elements of operating a motor vehicle—navigation, guidance, and control—together describe what concept?

**Solution:** The three essential elements of the driving task are navigation, guidance, and control. **Answer: C (Driving task). Key check: C.**

### Q39 — Destination information signs
**Problem:** What type of sign informs road users of directions and distances to destinations along their route or at intersecting roads?

**Solution:** Signs showing direction and distance to destinations are guide signs. **Answer: B. Key check: B.**

### Q40 — Cumulative queuing curves
**Problem:** For cumulative queuing diagrams A(t) and D(t), assess these statements: (I) their slopes give arrival and departure rates, respectively; (II) departure rate cannot exceed server capacity; (III) cumulative departures cannot exceed cumulative arrivals; and (IV) with a queue, departures occur at service capacity, while without a queue they match arrivals, with a queue forming when arrivals first exceed service capacity. Which statements are correct?

**Solution:** For cumulative arrival and departure curves, the slopes represent arrival and departure rates. Applying that interpretation to the four statements gives the keyed combination **B (all of the above)**; the wording of statement I is ambiguous and should be checked against the original figure. **Key check: B.**

## Questions 41–55

### Q41 — Sea structure projecting from shore
**Problem:** What is the term for a structure built into the sea, not parallel to the coastline, including a berth structure that projects outward from shore?

**Solution:** A pier is a structure projecting from the shoreline into the water. **Answer: B. Key check: B.**

### Q42 — Concrete mold
**Problem:** Fresh concrete cannot retain a particular shape before it sets, so it is placed in a form or mold. What is this called in building construction?

**Solution:** The temporary form or mold that holds fresh concrete is formwork. **Answer: A (formworks). Key check: A.**

### Q43 — Scaffold capacity requirement
**Problem:** What capacity requirement applies to all scaffolds?

**Solution:** The question asks a strength requirement. The standard criterion is based on the maximum intended load. The choices instead refer to the scaffold’s own weight, so none states the criterion correctly. The closest choice is A, but the item is defective as worded. **Key check: D; conflict flagged.**

### Q44 — Vibration dissipation
**Problem:** What term describes a material’s ability to dissipate or deaden mechanical vibrations?

**Solution:** A material's ability to dissipate mechanical vibration energy is damping. **Answer: A. Key check: A.**

### Q45 — Pile-driving formula inputs
**Problem:** For determining the safe capacity of piles driven by powered hammers, which data are used: average penetration per blow over the last six blows; hammer energy; hammer weight; pile weight including appurtenances; and a coefficient of restitution depending on hammer and pile weights?

**Solution:** The listed inputs are: I average penetration per blow over the last six blows; II hammer energy; III hammer weight; IV pile weight including appurtenances; V coefficient of restitution depending on hammer/pile weights. These are the data used by the Engineering News pile formula, so all five are relevant. **Derived answer: D (all). Key check: D.** No derivation is provided in the reference; this identification follows from the conventional formula inputs and the listed wording.

### Q46 — Safety discussion
**Problem:** What is the name for an informal group discussion focused on a particular safety issue, used regularly to promote safety culture and support health-and-safety discussions at job sites?

**Solution:** An informal daily group discussion focused on a safety issue is a toolbox meeting. **Answer: B. Key check: B.**

### Q47 — Excavation cave-in protection
**Problem:** What is the general term for methods that protect workers from cave-ins and falling or rolling material, including support, sloping, benching, and shield systems, and protect adjacent structures from collapse?

**Solution:** A system that supports/limits falling or rolling material and protects adjacent structures is a protective system. **Answer: C. Key check: C.**

### Q48 — Excavation in steps
**Problem:** What excavation method protects workers from cave-ins by cutting the excavation sides into one or more horizontal levels or steps, usually with vertical or near-vertical surfaces between levels?

**Solution:** Excavating sides into horizontal levels or steps is benching. **Answer: A. Key check: A.**

### Q49 — Binding agreement
**Problem:** What is a formal or legally binding agreement between two parties called?

**Solution:** A legally binding agreement between parties is a contract. **Answer: D. Key check: D.**

### Q50 — Post-construction completion stage
**Problem:** What stage follows construction completion and resolution of most punch-list and commissioning issues?

**Solution:** After construction and resolution of punch-list/commissioning items, the project undergoes turnover. **Answer: C. Key check: C.**

### Q51 — Elevation against facility centerline distance
**Problem:** What type of drawing uses elevation as the vertical axis and horizontal distance along a facility centerline or other reference line as the horizontal axis?

**Solution:** A drawing with elevation vertically and station/distance along the centerline horizontally is a profile. **Answer: C. Key check: C.**

### Q52 — Bar-chart drawbacks
**Problem:** Which are drawbacks of bar charts: (I) activities appear independent of one another; (II) activity sequence is not defined; and (III) it is difficult to judge whether an activity is complete?

**Solution:** Bar charts do not clearly show activity dependencies, may not define sequence, and make completion status harder to assess. I, II, and III are all drawbacks. **Answer: D. Key check: D.**

### Q53 — PERT time estimates
**Problem:** When preparing a PERT/CPM network for a construction project, which time estimates should be considered: optimistic, most probable, and pessimistic?

**Solution:** PERT uses optimistic, most probable, and pessimistic duration estimates. **Answer: D (all of the above). Key check: D.**

### Q54 — Detailed material/equipment/workmanship requirements
**Problem:** What document provides detailed requirements for the materials, equipment, and workmanship to be incorporated into a project?

**Solution:** Specifications state the required materials, equipment, and workmanship. **Answer: C. Key check: C.**

### Q55 — Bucket volume to side-outline level
**Problem:** What is the name for the volume a bucket holds up to the outline of its sides?

**Solution:** The volume contained within the bucket up to the outline of its sides is the struck/plate-line capacity; the choice is “Plate line capacity.” **Answer: D. Key check: D.**

---
