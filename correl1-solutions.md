# MSTC — Mathematics and Surveying

Worked solutions for 23 MSTC problems. Unclear problem wording or answer choices are noted where they affect the calculation.

## Question 1 — Elevation of a mountain peak

**Problem:** A mountain peak A is 1,040 m above sea level. From A, peak B is seen at an elevation angle of 10°. An aircraft directly over A reads 2,820 m above sea level and measures a 46°12′ angle of depression to B. Find B’s elevation.

**Solution:**

Peak A is 1,040 m above sea level. The pilot directly above A is at 2,820 m; hence the vertical leg is 2,820-1,040=1,780 m. The depression angle is 46°12′; the angle between the vertical and line of sight is 43°48′. From the diagram, the other triangle angles are 80° and 56°12′.

$$
\frac{AB}{\sin 43^\circ48'}=\frac{1780}{\sin 56^\circ12'}
\quad\Longrightarrow\quad AB\approx1482.60\text{ m}.
$$

B is 10° above A’s horizontal level, so its elevation is 1,040 + 1482.60 sin 10° = 1,297.45 m above sea level.

## Question 2 — Minimum triangular sale from a square field

**Problem:** A square farm field has sides of 2,261 yd. A tree is 1,898 yd from one corner and 1,009 yd from an adjacent corner. A neighbor buys a triangular part bounded by a straight fence joining two adjacent field sides and passing through the tree. Find the minimum possible area sold and the fence length.

**Solution:**

The field side is 2,261 yd; the tree is 1,898 yd from corner A and 1,009 yd from adjacent corner C. In triangle ABC, the angle (θ) at A follows from the cosine rule:

$$
1009^2=2261^2+1898^2-2(2261)(1898)\cos\theta,
\qquad \theta\approx26.27^\circ.
$$

Resolve (AB) relative to side (AC): (b=1898sinθ≈840 yd), and (a=2261-1898cosθ≈559 yd). For the minimum-area fence through the tree, the intercepts on the perpendicular field sides are (2a) and (2b).

$$
A=\frac{(2a)(2b)}2=2ab\approx2(559)(840)=\boxed{939{,}120\text{ yd}^2},
$$

$$
L=\sqrt{(2a)^2+(2b)^2}\approx\boxed{2018\text{ yd}}.
$$

These are approximate because the component lengths are rounded before the final calculation.

## Question 3 — Minimum roadway curve radius

**Problem:** Find the minimum allowable curve radius for a highway with design speed 100 km/h, maximum superelevation 0.12, and maximum tire-pavement friction coefficient 0.12.

**Solution:**

Use the metric highway-design relation (R=V^2/[127(e+f)]), with (V=100 km/h), superelevation (e=0.12), and side-friction factor (f=0.12):

$$
R=\frac{100^2}{127(0.12+0.12)}=328.08\text{ m}.
$$

**Answer: 328 m approximately.**

## Question 4 — Distance traveled by a rebounding ball

**Problem:** A ball is dropped from 10 ft and rebounds to half the preceding drop height each time. Find its total travel distance over all rebounds.

**Solution:**

The ball first falls 10 ft. Rebound heights form 5+2.5+1.25+·s, a geometric series with sum (5/(1-1/2)=10 ft). Each rebound height is traveled upward and downward:

$$
S=10+2(10)=\boxed{30\text{ ft}}.
$$

This assumes infinitely many rebounds, as the question’s geometric-series model does.

## Question 5 — Concrete batch weights with aggregate moisture

**Problem:** For a 1 m³ concrete batch, dry sand weighs 600 kg at 5% moisture, aggregate weighs 1,200 kg at 3% moisture, cement weighs 300 kg, and mixing water is 150 kg. Find the batch weights of sand, aggregate, cement, and added water.

**Solution:**

Apply the stated moisture percentages to the listed dry aggregate weights. Sand carries (600(0.05)=30 kg) of water; coarse aggregate carries (1200(0.03)=36 kg).

$$
W_{sand}=600+30=\boxed{630\text{ kg}},\qquad
W_{agg}=1200+36=\boxed{1236\text{ kg}},
$$

$$
W_{water}=150-30-36=\boxed{84\text{ kg}},\qquad
W_{cement}=\boxed{300\text{ kg}}.
$$

## Question 6 — Alphabetical volume order

**Problem:** A librarian shelves a twelve-volume encyclopedia in alphabetical order of the spelled-out volume numbers. Between which volumes should annual supplement Volume 13 be placed?

**Solution:**

The librarian orders volumes by spelling out their numbers. “Ten,” “thirteen,” “three,” and “twelve” occur alphabetically in that sequence. **Volume 13 goes between Volumes 10 and 3.**

## Question 7 — Water required to raise room relative humidity

**Problem:** A 3 m × 3 m × 2.7 m bedroom is at 20°C and 20% relative humidity. Find the liters of water vapor to add to reach 60% relative humidity. At 20°C, saturated vapor pressure is 17.5 torr; water molecular weight is 18 g/mol and R = 62.4 L·torr/(mol·K).

**Solution:**

The room volume is 3(3)(2.7) = 24.3 m³ (24,300 L). At 20°C, saturated vapor pressure is 17.5 torr. The required partial-pressure increase is

$$
\Delta p=(0.60-0.20)(17.5)=7.0\text{ torr}.
$$

With (T=293 K) and (R=62.4 L·torr/(mol·K)):

$$
\Delta n=\frac{\Delta pV}{RT}
=\frac{(7)(24{,}300)}{(62.4)(293)}\approx9.31\text{ mol},
$$

so the added water mass is 9.31 mol × 18 g/mol ≈ 168 g, about **0.168 L of liquid-water equivalent**. The question asks for liters of vapor without giving a reference pressure; a gas volume is therefore not uniquely defined. The liquid-water equivalent is the unambiguous interpretation used here.

## Question 8 — Exponential processing time

**Problem:** Toll-collection time is exponentially distributed with a mean of 23 s. Find the probability a randomly selected vehicle takes at least 25 s to process.

**Solution:**

For an exponential waiting time with mean μ=23 s), λ=1/23 s^-1. The survival probability is

$$
P(X\ge25)=e^{-25/23}\approx\boxed{0.337\;(33.7\%)}.
$$

## Question 9 — Net torque on a wheel

**Problem:** Find the net torque about the wheel axle shown in the diagram, given a friction torque of 0.60 N·m opposing motion. The figure supplies the applied forces and lever arms.

**Solution:**

Take counterclockwise positive. From the diagram, the 28 N force at radius 0.24 m is counterclockwise; 18 N at 0.24 m and 35 N at 0.12 m are clockwise:

$$
\tau_{applied}=28(0.24)-18(0.24)-35(0.12)=-1.80\text{ N·m}.
$$

Friction opposes that clockwise tendency, adding 0.60 N·m; net torque is -1.20 N·m. **Answer: 1.20 N·m clockwise.** The printed first torque line appears to use 0.28 m once, conflicting with the 24 cm radius in the diagram and the later line; the result uses the diagram’s radius.

## Question 10 — Critical path

**Problem:** A project starts at time zero. Activities and durations are Start→A (7), A→B (6), A→C (5), A→D (2), B→G (18), C→F (4), C→E (13), D→G (18), E→H (7), F→H (7), F→I (5), and G→I (5); H and I lead to Finish with zero duration. Find the critical path.

**Solution:**

The route times include A–B–G–I = 36, A–D–G–I = 32, A–C–E–H = 32, A–C–F–H = 23, and A–C–F–I = 21 time units. The longest route is the critical path: **A-B-G-I**, project duration **36** time units. One route is omitted from the prompt’s list, but it does not affect the longest route.

## Question 11 — Present worth index

**Problem:** A project costs $150,000 initially, has no salvage value, and saves $30,000 annually for 10 years. At 10% interest, calculate the present-worth index.

**Solution:**

The annual savings are 30,000 for 10 years at 10%; first cost is 150,000 and salvage is zero. The present-worth factor is

$$
(P/A,i,n)=\frac{(1+i)^n-1}{i(1+i)^n}=6.1446.
$$

$$
PW_{savings}=30{,}000(6.1446)=\$184{,}338,\qquad
PI=\frac{184{,}338}{150{,}000}=\boxed{1.23}.
$$

## Question 12 — Reversed-curve stations

**Problem:** A proposed highway uses a reverse curve to avoid a historic monument. Both curves have the same radius, their intersection angles are 42° and 30°, and the PI stations are 21+00 and 25+00. Find the PC, PRC, and PT stations.

**Solution:**

The two curves share radius R; their intersection angles are 42° and 30°, so the tangent lengths are R tan 21° and R tan 15°. The spacing between the PI points is 2,100 ft:

$$
R(\tan21^\circ+\tan15^\circ)=2100
\quad\Rightarrow\quad R\approx3221\text{ ft}.
$$

Thus T1 ≈ 1,237 ft and T2 ≈ 863 ft. The first PI is at Sta. 46+00, so PC = 46+00 − 12+37 = 33+63. Curve lengths are L1 ≈ 2,361 ft and L2 ≈ 1,686 ft: **PC ≈33+63, PRC ≈57+24, PT ≈74+10**. Small rounding differences from the printed work are expected.

## Question 13 — Gothic-arch width

**Problem:** A Gothic arch is a circular portion as shown. Using the dimensions and point D in the diagram, find the arch width W at D.

**Solution:**

The diagram gives circle center C=(6,0), radius 10, and point D=(x,3). From (x−6)²+3²=10², x=6−√91≈−3.54 because D is left of the y-axis. If the requested width spans the symmetric arch, W=2√91≈19.08 units. The printed answer doubles 3.54 to report 7.08 ft, which is the width between the y-axis and D mirrored across it; that geometry conflicts with the diagram’s right endpoint at (x=6). The intended width needs clarification.

## Question 14 — Three-row flags, upside-down duplicates

**Problem:** Using a French-tricolor pattern of three rows and five available colors, count the possible flags when adjacent rows cannot have the same color.

**Solution:**

There are (5·4·4=80) ordered flags with adjacent rows different. Reversal fixes the 20 flags with identical top and bottom colors (5 choices for that color and 4 for the middle). Burnside’s count is

$$
N=\frac{80+20}{2}=\boxed{50}.
$$

## Question 15 — Selecting five colors from nine

**Problem:** How many different selections of five colors can be made from nine available colors?

**Solution:**

Order does not matter:

$$
\binom95=\frac{9!}{5!4!}=\boxed{126}.
$$

## Question 16 — Nickel-alloy mixture

**Problem:** How many milligrams of a 45%-nickel steel should be combined with 6 mg of pure nickel to produce an alloy that is 78% nickel?

**Solution:**

Let (x) mg be the mass of the 45%-nickel alloy; adding 6 mg pure nickel makes a 78% mixture:

$$
0.45x+6=0.78(x+6)\quad\Rightarrow\quad x=\boxed{4\text{ mg}}.
$$

## Question 17 — Rate at which two cars separate

**Problem:** Car A travels west at 11.5 km/h. Two and a half hours later, car B travels north at 22.5 km/h. Five hours after B starts, find the rate at which the distance between the cars is changing.

**Solution:**

At the stated observation time, the west–east separation is x = 11.5(5)+11.5(2.5) = 86.25 km, and the north–south separation is y = 22.5(5) = 112.5 km. Their separation is s = √(x²+y²) = 141.76 km. Differentiate s² = x²+y²:

$$
\frac{ds}{dt}=\frac{x(11.5)+y(22.5)}s
=\frac{86.25(11.5)+112.5(22.5)}{141.76}
\approx\boxed{24.85\text{ km/h}}.
$$

The diagram’s delay label is faint; the written work uses the stated 2.5-hour delay.

## Question 18 — Probability of engine or drivetrain repairs

**Problem:** The probabilities that a car under warranty needs engine repairs, drivetrain repairs, or both are 0.87, 0.36, and 0.29, respectively. Find the probability it needs one or both kinds of repairs.

**Solution:**

With PA)=0.87, PB)=0.36, and PAcap B)=0.29:

$$
P(A\cup B)=P(A)+P(B)-P(A\cap B)=0.87+0.36-0.29
=\boxed{0.94\;(94\%)}.
$$

The printed work labels 0.65 as the intersection once, then substitutes 0.29. The question’s stated “or both” probability is 0.29; the calculation uses that value.

## Question 19 — Paint for two coats

**Problem:** A gallon of latex paint covers 400 ft². How many gallon containers are needed for two coats on every wall of a 14 ft × 18 ft room with 8 ft ceilings?

**Solution:**

For a 14 ft by 18 ft room with 8 ft walls, wall area per coat is (2(14)(8)+2(18)(8)=512 ft^2). Two coats require (1,024 ft^2). At 400 ft²/gal:

$$
V=1024/400=\boxed{2.56\text{ gal}}.
$$

If only whole gallons can be purchased, round up to 3 gallons. No door/window deductions are specified.

## Question 20 — Granular subbase thickness from structural number

**Problem:** A flexible pavement requires structural number 6. The asphalt layer is 4 in. with coefficient 0.44; the crushed-stone base is 6 in. with coefficient 0.14; the granular subbase coefficient is 0.08. All drainage coefficients are 1. Find the minimum granular-subbase thickness.

**Solution:**

Using the given structural-number equation with drainage coefficients (m=1):

$$
6=(4)(0.44)+(6)(0.14)+t_3(0.08)
\quad\Rightarrow\quad t_3=\boxed{42.5\text{ in.}}
$$

Round up to approximately 43 in. for a whole-inch construction thickness.

## Question 21 — Excavator production

**Problem:** Estimate a small hydraulic excavator’s production in loose m³/h. Its heaped bucket capacity is 0.57 m³; the material is sand and gravel with fill factor 0.95; job efficiency is 50 min/h; average cut depth is 4.3 m, maximum cut depth 6.1 m, average swing 90°, cycle output 250 cycles/h, and swing-depth factor 1.0.

**Solution:**

Using 250 cycles/h, 0.57 m³/cycle bucket volume, fill factor 1.0, efficiency 0.95, and 50 productive minutes per hour:

$$
Q=250(0.57)(1.0)(0.95)(50)/(60)
=112.81≈113 loose m^3/h.
$$

## Question 22 — Finishing a screeded concrete surface

**Problem:** What is the concrete finishing operation that brings a screeded slab to true grade with enough mortar to obtain the desired finish?

**Solution:**

Bringing the surface to the specified grade is **leveling** (choice c in the scan).

## Question 23 — Premolded inserts for shrinkage cracking

**Problem:** What is the operation in which premolded inserts are placed during or immediately after edging to control shrinkage cracking in a concrete slab?

**Solution:**

Installing premolded inserts to control shrinkage cracking is **jointing** (choice a in the scan).

# HPGE — Hydraulics and Geotechnical Engineering

Worked solutions for 40 HPGE problems. Unclear problem wording or answer choices are noted where they affect the calculation.

## Question 1 — Effective vertical stress in clay

**Problem:** A 7.6 m clay layer underlies 15.2 m of sand. Sand unit weights are 21.2 kN/m³ saturated and 18.2 kN/m³ dry; clay saturated unit weight is 18.8 kN/m³. Find effective vertical pressure at the clay midpoint (a) with the water table at ground level, (b) after it falls 10 m when sand above it has 20% saturation, and (c) with no water in the sand while it remains at that same moisture condition.

**Solution:**

The sand is 15.2 m thick, the clay is 7.6 m thick, and the point is at the clay midpoint, 3.8 m below its top. Use γ_w=9.81 kN/m^3. From the difference between saturated and dry sand unit weights:

$$
21.2-18.2=(eγ_w)/(1+e)\quad\Rightarrow\quad e≈0.440,
\qquad G_s=(18.2(1+e))/(9.81)≈2.67.
$$

**(a) Water table at ground.** Both layers above the point are saturated:

$$
σ'_v=(21.2-9.81)(15.2)+(18.8-9.81)(3.8)
=207.3 kPa.
$$

**b) Water table lowered 10 m.** The upper 10 m of sand is moist at S=0.20:

$$
γ_moist=((G_s+Se)γ_w)/(1+e)
=((2.67+0.20(0.440))(9.81))/(1.440)=18.79 kN/m^3.
$$

$$
σ'_v=18.79(10)+(21.2-9.81)(5.2)+(18.8-9.81)(3.8)
=281.3 kPa.
$$

**(c) No water in the sand, same moisture state.**

$$
σ'_v=18.79(15.2)+(18.8-9.81)(3.8)
=319.8 kPa.
$$

## Question 2 — Moisture content, void ratio, porosity

**Problem:** A saturated soil sample weighs 1,600 g and weighs 1,000 g after drying. Grain specific gravity is 2.67. Find water content, void ratio, and porosity.

**Solution:**

Water mass is 600 g and dry soil mass is 1,000 g; the soil-grain specific gravity is 2.67. Thus

$$
w=600/1000=60%,\qquad e=G_sw=2.67(0.60)=1.60,
$$

$$
n=(e)/(1+e)=(1.60)/(2.60)=61.5%.
$$

## Question 3 — Consolidated-drained triaxial test

**Problem:** A consolidated-drained triaxial test on clay has confining pressure 240 kPa and deviator stress at failure 450 kPa. Find the friction angle, shear stress on the failure plane, and normal stress on the plane of maximum shear.

**Solution:**

Confining pressure is σ_3=240 kPa; deviator stress at failure is 450 kPa, so σ_1=690 kPa. Mohr-circle center C=690+240)/2=465 kPa, radius R=690-240)/2=225 kPa. The scan assumes zero cohesion (failure envelope through the origin):

$$
sinφ=R/C=225/465\quad\Rightarrow\quadφ=28.9^\circ.
$$

$$
τ_f=Rcosφ=225cos28.9^\circ≈197 kPa,
\qquad σ_n,,max shear=C=465 kPa.
$$

## Question 4 — Hydrostatic force on a vertical circular plate

**Problem:** A vertical circular plate of radius 300 mm is submerged in water with its top edge 2 m below the surface. Find the hydrostatic force on one side and its location relative to the plate centroid and the liquid surface. The prompt’s force unit is printed as kPa; state force in appropriate units.

**Solution:**

Radius r=0.300 m; the top is 2.0 m below the surface, so centroid depth is bar h=2.30 m, and area A=π0.3)^2=0.2827 m^2.

$$
F=γ_w hA=9.81(2.30)(0.2827)=6.38 kN.
$$

For a circle, I_G = π(0.6)⁴/64 = 0.006362 m⁴. Center-of-pressure offset below the centroid is

$$
e=(I_G)/(A h)=0.00978 m=9.78 mm,
\quad h_CP=2.30+0.00978=2310 mm below the surface.
$$

The prompt gives force in kPa, but the dimensional result is force in kN.

## Question 5 — Boussinesq point-load stress

**Problem:** Using Boussinesq’s point-load relation, find vertical stress for a surface load Q = 2,500 kN at (a) 3 m directly below, (b) 6 m directly below, and (c) 6 m below and 3 m horizontally from the load line.

**Solution:**

Use p=0.477QN/z^2, N=[1+r/z)^2]^-2.5, and Q=2500 kN. Directly beneath the load N=1:

$$
p_z=3=0.477(2500)/3^2=132.5 kPa,
\qquad p_z=6=0.477(2500)/6^2=33.1 kPa.
$$

At r=3 m,z=6 m, N=[1+3/6)^2]^-2.5=0.5724, so p=0.4772500)0.5724)/36=19.0 kPa.

## Question 6 — Westergaard point-load stress

**Problem:** Using Westergaard’s point-load relation, find vertical stress for Q = 2,500 kN at a point 6 m below the load and 3 m horizontally from its line of application.

**Solution:**

For Q=2500 kN,r=3 m,z=6 m, the scan gives N=[1+2r/z)^2]^-1.5 and p=0.318QN/z^2:

$$
N=[1+2(0.5)^2]^-1.5=0.5443,
\qquad p=(0.318(2500)(0.5443))/(36)=12.0 kPa.
$$

## Question 7 — Water spilled from a rotating open cylinder

**Problem:** An open cylindrical vessel 1.3 m in diameter and 2.1 m high is two-thirds full of water. It rotates about its vertical axis at 87 rpm. Find the volume of water spilled, in liters.

**Solution:**

Diameter 1.3 m, height 2.1 m, initial water depth 2H/3=1.4 m; radius R=0.65 m. Angular speed ω=872π/60)=9.11 rad/s. The center-to-rim free-surface difference is

$$
Δ h=(ω^2R^2)/(2g)=1.787 m.
$$

At spill onset, subtract the parabolic depression volume from the cylinder volume to the rim. The initial volume is two-thirds of the cylinder capacity. The resulting loss is approximately **257 L**. The printed solution gives 259 L; the difference is rounding.

## Question 8 — Force on rear end of an accelerating tank

**Problem:** A closed horizontal cylindrical tank, 1.5 m in diameter and 5 m long, is completely full of water and carried by a truck accelerating forward at 4 m/s². Find the total force on its rear end. The force unit at the end of the scanned prompt is unreadable; the absolute pressure datum is also not specified.

**Solution:**

The horizontal tank has diameter 1.5 m and length 5 m. Its pressure-head increase from front to rear is the acceleration head. Following the pressure reference drawn in the diagram, the head at the rear circular end centroid is the full longitudinal head change plus the 0.75 m radius:

$$
Δ h=(aL)/(g)=(4(5))/(9.81)=2.039 m,\qquad
\bar h=2.039+0.75=2.789 m.
$$
$$
A=(π)/(4)(1.5)^2=1.767 m^2,\qquad
F=γ_w\bar hA=9.81(2.789)(1.767)=48.4 kN.
$$

**Boundary-condition note:** “Completely filled” in a closed tank does not itself set an absolute gauge pressure. The result follows the pressure reference shown in the diagram; without a pressure datum, only the front-to-rear pressure difference is determined.

## Question 9 — Can water content exceed 100%?

**Problem:** Can soil water content exceed 100%?

**Solution:**

Water content is w=M_w/M_s. In organic or very porous soils, water mass can exceed dry-solid mass. **Choice (c): it can be greater than 100%.**

## Question 10 — SPT range for loose granular soil

**Problem:** For what standard penetration test blow-count range is a granular soil deposit classified as loose?

**Solution:**

The scan’s classification table assigns **4–10 blows** to “Loose.” Boundary values overlap neighboring categories in the reproduced table; use the stated loose interval.

## Question 11 — Dry density of saturated soil

**Problem:** A saturated soil has water content 30% and grain specific gravity 2.6. Find its dry density in g/cm³.

**Solution:**

Given w=0.30, G_s=2.6, and S=1, Se=wG_s gives e=0.78. With water density 1.00 g/cm^3:

$$
ρ_d=(G_sρ_w)/(1+e)=(2.6)/(1.78)
=1.46 g/cm^3.
$$

## Question 12 — Coarser particles mixed into clay

**Problem:** What happens to liquid limit and plasticity index when coarser particles such as sand and silt are mixed into clay?

**Solution:**

Adding sand/silt generally reduces clay fraction and plasticity: **both liquid limit and plasticity index decrease (choice a).**

## Question 13 — Shear strength of a “cohesion soil”

**Problem:** How is the shear strength of the soil termed “cohesion soil” in the prompt related to the angle of shearing resistance? The source term may be unclear.

**Solution:**

The scan wording is “cohesion soil,” likely meaning **cohesionless soil**. Mohr–Coulomb strength is

$$
τ_f=c+σ'tanφ.
$$

For cohesionless soil c=0, so at fixed effective normal stress strength is proportional to tanφ: **choice (d)**. If “cohesive soil” was intended, cohesion (c) also contributes and the choices do not fully describe strength.

## Question 14 — Darcy–Weisbach pipeline head loss

**Problem:** Water flows at 20 L/s through a 500 m long, 150 mm diameter pipe with friction coefficient 0.02. Find the head loss.

**Solution:**

Given f=0.02,L=500 m,Q=0.020 m^3/s,D=0.150 m:

$$
h_f=(0.0826fLQ^2)/(D^5)
=(0.0826(0.02)(500)(0.020)^2)/((0.150)^5)
=4.35 m.
$$

## Question 15 — Force on the lower part of a plate crossing oil and water

**Problem:** A vertical plate 1.2 m wide and 2 m long is half submerged in oil of specific gravity 0.84 and half in fresh water, with its shorter upper edge at the liquid surface. Find the hydrostatic force on the lower half. The diagram’s specific-gravity label appears to conflict with the stated 0.84.

**Solution:**

The lower half is 1.0 m high by 1.2 m wide, so A=1.2 m^2. Oil of specific gravity 0.84 lies above fresh water. At the lower-half centroid, pressure head in water units is 0.841.0)+0.50=1.34 m:

$$
F=9.81(1.34)(1.2)=15.8 kN.
$$

The diagram’s oil specific gravity reads 0.84; OCR text misreads it once as 0.64.

## Question 16 — Pressure beneath a rectangular footing

**Problem:** A 450 kN column load is carried by a 1.5 m × 2.5 m rectangular footing. Soil pressure spreads at 2 vertical to 1 horizontal. Find pressure 2.7 m below the footing.

**Solution:**

Load 450 kN, footing 1.5×2.5 m, depth 2.7 m. A 2V:1H spread means horizontal spread on each side = 2.7/2 = 1.35 m. Thus the spread plan dimensions are 1.5 + 2(1.35) = 4.2 m and 2.5 + 2(1.35) = 5.2 m:

$$
q=(450)/(4.2(5.2))=20.6 kPa.
$$

<svg viewBox="0 0 520 240" role="img" aria-label="Two vertical to one horizontal load spread beneath a rectangular footing" xmlns="http://www.w3.org/2000/svg">
  <rect width="520" height="240" fill="#fff"/>
  <path d="M90 55H270V80L330 185H30L90 80Z" fill="#e7f0f5" stroke="#17324d" stroke-width="3"/>
  <path d="M90 80L30 185M270 80L330 185" fill="none" stroke="#087e8b" stroke-width="3" stroke-dasharray="7 5"/>
  <path d="M180 22V48" stroke="#bd4a36" stroke-width="3"/>
  <path d="M172 38L180 54L188 38" fill="none" stroke="#bd4a36" stroke-width="3"/>
  <path d="M50 205H310M90 215V195M270 215V195" stroke="#40546a" stroke-width="1.5"/>
  <path d="M90 103L45 180M270 103L315 180" stroke="#40546a" stroke-width="1.5"/>
  <text x="192" y="36" font-size="15">450 kN</text><text x="110" y="74" font-size="14">1.5 × 2.5 m footing</text>
  <text x="175" y="140" font-size="14">2V : 1H</text><text x="165" y="229" font-size="14">spread area at 2.7 m depth</text>
</svg>

## Question 17 — Irrigation hectares served

**Problem:** A trapezoidal irrigation canal has bottom width 2.50 m, water depth 0.90 m, side slope 1.5H:1V, bed slope 0.001, and Manning roughness 0.025. At a duty of 3.0 L/s per hectare for clay-loam rice land, estimate the hectares served.

**Solution:**

For bottom width b=2.50 m, depth y=0.90 m, side slope z=1.5H:1V,

$$
A=y(b+zy)=0.90[2.50+1.5(0.90)]=3.465\text{ m}^2,
$$
$$
P=b+2y\sqrt{1+z^2}=2.50+2(0.90)\sqrt{1+1.5^2}=5.745\text{ m},
\qquad R_h=A/P=0.6031\text{ m}.
$$
$$
V=\frac{1}{n}R_h^{2/3}S^{1/2}
=\frac{1}{0.025}(0.6031)^{2/3}(0.001)^{1/2}=0.903\text{ m/s},
\qquad Q=VA=3.129\text{ m}^3/\text{s}.
$$

At 3.0 L/s per hectare:

$$
Area=3129/3=1043 ha.
$$

## Question 18 — Ship moves from seawater to fresh water

**Problem:** A ship with vertical sides near the waterline weighs 40 MN with cargo and drafts 6.7 m in seawater (SG 1.026). After unloading 2 MN, its draft is 6.4 m in seawater. Find its draft in fresh water with the reduced cargo.

**Solution:**

After unloading, the ship weighs 38 MN and has seawater draft 6.4 m. For the same displacement weight, displaced volume varies inversely with water density. With seawater specific gravity 1.026:

$$
d_fresh=1.026(6.4)=6.566 m≈6.57 m.
$$

## Question 19 — Mountain height from barometer readings

**Problem:** An improvised barometer liquid has weight 0.80 that of mercury. Readings at a mountain base and summit are 950 mm and 600 mm. Find the mountain height in kilometers.

**Solution:**

Barometer liquid specific gravity is 0.80 relative to mercury; readings differ by 0.950-0.600=0.350 m. The liquid specific weight is 0.8013.6)9.81)=106.73 kN/m^3, so pressure difference is 37.36 kPa. With the given constant air specific weight 12 N/m^3=0.012 kN/m^3:

$$
h=\frac{37.36}{0.012}=3113\text{ m}\approx3.11\text{ km}.
$$

This follows the problem’s constant-air-density approximation.

## Question 20 — Weight of floating wood

**Problem:** A 50 mm × 100 mm wooden piece, 1.5 m long, floats vertically in a 1.8 m deep curing tank with 0.50 m projecting above water. Find its weight in newtons.

**Solution:**

Cross-section 0.05×0.10=0.005 m^2; submerged length is 1.5-0.50=1.0 m. By flotation, weight equals buoyancy:

$$
W=γ_wV=9810(0.005)(1.0)=49.05 N.
$$

## Question 21 — Force needed to open a hinged gate

**Problem:** A vertical rectangular gate 1.5 m wide and 3 m high is bottom-hinged. Water reaches the top on one side and stands 2 m below the top on the other. Find the horizontal force at the gate top needed to open it.

**Solution:**

Gate width 1.5 m, height 3 m. Left depth is 3 m; right depth is 1 m. Resultants are P_1=9.811.5)3)1.5)=66.22 kN acting 1 m above the bottom, and P_2=9.810.5)1.5)1)=7.36 kN acting 1/3 m above it. Moment equilibrium about the bottom hinge:

$$
3T+P_2\left(\frac{1}{3}\right)=P_1(1)
\quad\Rightarrow\quad T=21.26\text{ kN}.
$$

<svg viewBox="0 0 520 230" role="img" aria-label="Differential water depths and hydrostatic resultants on the hinged vertical gate" xmlns="http://www.w3.org/2000/svg">
  <rect width="520" height="230" fill="#fff"/>
  <path d="M100 35V185H390" fill="none" stroke="#17324d" stroke-width="4"/>
  <path d="M105 40H250V185H105Z" fill="#a7dce5" opacity=".65"/>
  <path d="M255 135H385V185H255Z" fill="#a7dce5" opacity=".65"/>
  <path d="M250 35V185" stroke="#26384b" stroke-width="7"/>
  <circle cx="250" cy="185" r="8" fill="#bd4a36"/>
  <path d="M250 35H315" stroke="#bd4a36" stroke-width="3" marker-end="url(#arr)"/>
  <path d="M180 135H242" stroke="#087e8b" stroke-width="4" marker-end="url(#arr2)"/>
  <path d="M320 169H258" stroke="#8b5a1e" stroke-width="4" marker-end="url(#arr3)"/>
  <path d="M70 40V185M62 40H78M62 185H78M415 135V185M407 135H423M407 185H423" stroke="#40546a" stroke-width="1.5"/>
  <text x="35" y="115" font-size="15">3 m</text><text x="427" y="163" font-size="14">1 m</text>
  <text x="190" y="128" font-size="15">P₁</text><text x="298" y="162" font-size="15">P₂</text>
  <text x="322" y="41" font-size="14">T</text><text x="258" y="208" font-size="13">bottom hinge</text>
  <defs><marker id="arr" markerWidth="8" markerHeight="8" refX="6" refY="3" orient="auto"><path d="M0,0 L6,3 L0,6" fill="#bd4a36"/></marker><marker id="arr2" markerWidth="8" markerHeight="8" refX="6" refY="3" orient="auto"><path d="M0,0 L6,3 L0,6" fill="#087e8b"/></marker><marker id="arr3" markerWidth="8" markerHeight="8" refX="6" refY="3" orient="auto"><path d="M0,0 L6,3 L0,6" fill="#8b5a1e"/></marker></defs>
</svg>

## Question 22 — Rectangular canal dimensions at the same discharge

**Problem:** A rectangular irrigation canal is 5.4 m wide and 1.2 m deep, with hydraulic slope 0.001 and roughness 0.013. Find dimensions for a more hydraulically appropriate section that carries the same discharge at the same slope.

**Solution:**

Original section 5.4×1.2 m: A=6.48 m^2,P=7.8 m,R=0.8308 m. Manning gives V=2.148 m/s, so Q=13.92 m^3/s. For the more economical rectangle b=2d: A=2d^2,P=4d,R=d/2. Substitute in Manning’s equation at the same Q,S,n and solve:

$$
d≈1.76 m,\qquad b=2d≈3.52 m.
$$

## Questions 23–24 — Curved sector gate forces

**Problem (Question 23):** The shown sector gate has a cylindrical surface with radius 8 m and length perpendicular to the page of 10 m. Find the horizontal force on the gate.

**Solution:** The cylindrical gate has radius 8 m, length 10 m, and a 60° sector angle. Its vertical projection height is 8 sin 60° = 6.928 m.

**Horizontal component.** It equals the force on the vertical projected rectangle:

$$
F_H=\gamma_w\bar h A_{proj}
=9.81\left(\frac{6.928}{2}\right)(6.928\cdot10)
=2356\text{ kN}.
$$

**Problem (Question 24):** For the same shown cylindrical sector gate, radius 8 m and length perpendicular to the page 10 m, find the total vertical force.

**Solution:**



**Vertical component.** It equals the weight of water above the curved surface. The cross-sectional water area is trapezoid area (4+8)/(2)6.928)=41.57 m^2 minus sector area (60)/(360)π8)^2=33.51 m^2, or 8.06 m². Hence

$$
F_V=9.81(8.06)(10)=791\text{ kN downward}.
$$

## Question 25 — Inclined-orifice jet range

**Problem:** A water tank has a side inclined 45° to horizontal and water depth 8 m. An orifice on the inclined side is under 5 m head and 3 m vertically above the tank bottom. With velocity coefficient 1.0 and negligible air resistance, find the horizontal ground distance from the orifice center. The diagram and solution give inconsistent vertical distances from the orifice to the ground (the prompt diagram marks a 2 m tank-bottom clearance, while the solution uses 1.2 m); this detail is unresolved.

**Solution:**

The orifice head is 5 m and the velocity coefficient is 1. The jet leaves normal to the 45° tank wall, at 45° above horizontal. The ground is 4.2 m below the orifice (3 m to the tank bottom plus 1.2 m to ground in the diagram).

$$
v=C_v\sqrt{2gH}=\sqrt{2(9.81)(5)}=9.9045\text{ m/s},\qquad
v_y=v\sin45^\circ=7.003\text{ m/s}.
$$
$$
-4.2=v_yt-\1/2gt^2
\quad\Rightarrow\quad t=1.88\text{ s},\qquad
x=v\cos45^\circ t=13.2\text{ m}.
$$

The diagram below is a schematic redraw of the scanned geometry.

<svg viewBox="0 0 680 250" role="img" aria-label="Redrawn inclined tank, orifice, and projectile path from the source diagram" xmlns="http://www.w3.org/2000/svg">
  <rect width="680" height="250" fill="#fff"/>
  <path d="M35 215H645" stroke="#26384b" stroke-width="3"/>
  <path d="M90 35H185L270 130H90Z" fill="#e8f3f5" stroke="#26384b" stroke-width="3"/>
  <path d="M94 42H181L214 80H94Z" fill="#9ad4df" opacity=".8"/>
  <circle cx="224" cy="82" r="5" fill="#bd4a36"/>
  <path d="M224 82Q375 -42 530 215" fill="none" stroke="#087e8b" stroke-width="3" stroke-dasharray="8 6"/>
  <path d="M224 82l32-32" stroke="#bd4a36" stroke-width="3"/>
  <path d="M90 38V130M75 38H85M75 130H85" stroke="#34495e" stroke-width="1.5"/>
  <path d="M290 82V215M282 82H298M282 215H298" stroke="#34495e" stroke-width="1.5"/>
  <path d="M185 35L224 82" stroke="#bd4a36" stroke-width="1.5" stroke-dasharray="4 4"/>
  <path d="M204 61a27 27 0 0 1 26 14" fill="none" stroke="#34495e" stroke-width="1.5"/>
  <text x="45" y="77" font-size="15">8 m</text>
  <text x="121" y="70" font-size="14">5 m head</text>
  <text x="124" y="117" font-size="14">3 m</text>
  <text x="304" y="152" font-size="14">4.2 m</text>
  <text x="222" y="45" font-size="14">45°</text>
  <text x="266" y="91" font-size="15">jet</text>
  <text x="410" y="230" font-size="15">horizontal range x</text>
  <text x="548" y="210" font-size="14">ground</text>
</svg>

## Question 26 — Safe concentric load on a square footing

**Problem:** A square footing 2.0 m on a side is founded 1.0 m into cohesionless soil with unit weight 16 kN/m³ and friction angle 25°. Using Terzaghi general-shear bearing capacity and factor of safety 3, find the concentric safe load.

**Solution:**

For a 2 m square footing embedded 1 m in soil with unit weight 16 kN/m³ and friction angle 25°, use the supplied general-shear factors Nq = 12.7 and Nγ = 8.34, with cohesion zero. Surcharge is γDf = 16 kPa.

$$
q_ult=qN_q+0.40γ BN_γ
=16(12.7)+0.40(16)(2)(8.34)=309.95 kPa.
$$
$$
q_allow=q_ult/3=103.32 kPa,\qquad
P=q_allowB^2=103.32(4)=413 kN.
$$

This neglects footing self-weight. The printed solution substitutes q = 1 instead of γDf = 16 kPa, giving 159 kN; its substitution conflicts with the stated depth and soil unit weight.

## Question 27 — Vertical flow through layered soil

**Problem:** Three soil layers have, top to bottom, thicknesses 3, 4, and 6 m and permeabilities 1×10⁻⁴, 3.2×10⁻², and 4.1×10⁻⁵ cm/s. For vertical flow, find flow rate per square meter in L/h at hydraulic gradient 0.50.

**Solution:**

For vertical flow through layers in series, the total thickness is 13 m. The table gives k1 = 1×10⁻⁴ cm/s, k2 = 3.2×10⁻² cm/s, and k3 = 4.1×10⁻⁵ cm/s, with layer thicknesses 3, 4, and 6 m.

$$
k_{v,eq}=\frac{13}{\frac{3}{1\times10^{-4}}+\frac{4}{3.2\times10^{-2}}+\frac{6}{4.1\times10^{-5}}}
=7.37\times10^{-5}\text{ cm/s}=2.65\times10^{-3}\text{ m/h}.
$$
$$
Q=k_{v,eq}iA=(2.65\times10^{-3})(0.50)(1)
=1.325\times10^{-3}\text{ m}^3/\text{h}=1.325\text{ L/h}.
$$

## Question 28 — Thickness reduction from void-ratio change

**Problem:** An 8 m soil layer has initial void ratio 1.0, which decreases by one-half under compression. Find the layer thickness reduction.

**Solution:**

Initial layer thickness is 8 m; void ratio changes from 1.0 to 0.5.

$$
Δ H=(H(e_1-e_2))/(1+e_1)
=(8(1-0.5))/(1+1)=2 m.
$$

## Question 29 — Seepage proportionality

**Problem:** Seepage through soil is proportional to which hydraulic/material quantities?

**Solution:**

Darcy’s law is Q = kiA, with i = Δh/L. For fixed geometry, seepage is proportional to both permeability and total head loss. **Choice (c).**

## Question 30 — Gage pressure under variable unit weight

**Problem:** A liquid has variable unit weight γ = 12 + 0.5h kN/m³, where h is depth in meters. Find gage pressure at 3 m depth.

**Solution:**

Given γ(h) = 12 + 0.5h kN/m³, integrate from the surface to 3 m:

$$
p=\int_0^3(12+0.5h)\,dh
=\left[12h+0.25h^2\right]_0^3
=38.25\text{ kPa}.
$$

## Question 31 — Specific gravity from apparent submerged weight

**Problem:** A prism measuring 1.5 m × 1.0 m × 2.0 m weighs 29.4 kN in water. Find its specific gravity.

**Solution:**

Prism volume is 1.5×1.0×2.0 = 3.0 m³. Interpreting “weighs 29.4 kN in water” as apparent weight:

$$
W_app=γ_wV(G_s-1)\quad\Rightarrow\quad
G_s=1+(29.4)/(9.81(3.0))=2.00.
$$

The printed solution sets 29.4 kN equal to buoyant force and reports SG = 1.0. That would treat 29.4 kN as the displaced-water weight rather than apparent weight.

## Question 32 — Dry density from bulk density and water content

**Problem:** A soil has bulk density 2.3 g/cm³ and water content 15%. Find its dry density.

**Solution:**

$$
\rho_d=\frac{\rho_{bulk}}{1+w}
=\frac{2.3}{1.15}=2.00\text{ g/cm}^3.
$$

## Question 33 — Clay thickness change

**Problem:** A 9 m soft-clay layer has initial void ratio 1.0, which decreases by one-fourth under compression. Find the thickness reduction.

**Solution:**

The solution interprets the void ratio as reduced to one-fourth: e1 = 1, e2 = 0.25, H = 9 m.

$$
\Delta H=\frac{H(e_1-e_2)}{1+e_1}
=\frac{9(1-0.25)}{1+1}=3.375\text{ m}.
$$

## Question 34 — Moist unit weight

**Problem:** A soil has dry unit weight 15 kN/m³. Water is added until its moisture content is 25%. Find the resulting moist unit weight.

**Solution:**

$$
γ=γ_d(1+w)=15(1+0.25)=18.75 kN/m^3.
$$

## Question 35 — Reservoir head difference

**Problem:** Water flows at 10 m³/s through a 3 m diameter, 2,500 m long pipeline between reservoirs. With friction coefficient 0.018 and minor losses neglected, find the difference in reservoir surface elevations.

**Solution:**

Neglecting minor losses, the surface-elevation difference equals Darcy–Weisbach friction loss. Given f = 0.018, L = 2,500 m, Q = 10 m³/s, and D = 3 m:

$$
h_f=(0.0826fLQ^2)/(D^5)
=(0.0826(0.018)(2500)(10)^2)/(3^5)
=1.53 m.
$$

## Question 36 — Change in velocity head

**Problem:** Velocity head at one section is 5 m. At the next section, flow velocity increases by one-half its original value. Find the new velocity head.

**Solution:**

Velocity increases by one-half its previous value, so V2 = 1.5V1. Velocity head varies as V²:

$$
((V^2)/(2g))_2=1.5^2(5)=11.25 m.
$$

## Question 37 — Mean velocity in a trapezoidal channel

**Problem:** Water depth in a trapezoidal channel is 2.4 m; width is 3 m at the base and 5 m at the water surface. If discharge is 12 m³/s, find mean velocity.

**Solution:**

Water depth is 2.4 m; channel width grows from 3 m at the bottom to 5 m at the water surface. Area is A = [(3+5)/2](2.4) = 9.6 m².

$$
V=Q/A=12/9.6=1.25 m/s.
$$

## Question 38 — Primary consolidation settlement

**Problem:** A clay layer is 8 m thick, with initial intergranular pressure 180 kPa, pressure increase 120 kPa, consolidation coefficient 0.315, and void ratio 1.132. Find primary consolidation settlement.

**Solution:**

Use H = 8 m, Cc = 0.315, e0 = 1.132, initial effective pressure 180 kPa, and pressure increase 120 kPa.

$$
S_c=\frac{HC_c}{1+e_0}\log_{10}\left(\frac{180+120}{180}\right)
=\frac{8(0.315)}{2.132}\log_{10}\left(\frac{300}{180}\right)
=0.262\text{ m}.
$$

## Question 39 — Specific weight of an anchored sphere

**Problem:** A sphere of radius 400 mm is submerged in seawater of SG 1.026 and anchored to the seabed. The mooring line tension is 800 N. Find the sphere’s specific weight.

**Solution:**

Radius is 0.4 m. The anchor tension acts downward, so buoyancy balances sphere weight plus the 0.800 kN tension.

$$
V=\frac{4}{3}\pi(0.4)^3=0.2681\text{ m}^3,\qquad
\gamma_{sea}=1.026(9.81)=10.065\text{ kN/m}^3.
$$
$$
\gamma_s=\frac{\gamma_{sea}V-0.800\text{ kN}}{V}=7.08\text{ kN/m}^3.
$$

## Question 40 — Jet force on a plate moving toward the nozzle

**Problem:** A 20 mm diameter water jet moving at 8 m/s strikes a plate normally. The plate moves toward the nozzle at 5 m/s. Find the force on the plate.

**Solution:**

Jet diameter is 0.020 m, jet speed 8 m/s, and plate speed toward the nozzle is 5 m/s. Relative impact speed is 13 m/s; the force is the incoming momentum flux in the moving plate frame.

$$
F=\rho A V_r^2
=1000\left[\frac{\pi}{4}(0.020)^2\right](13)^2
=53.1\text{ N}.
$$

The printed line’s formula evaluates to 53.1 N; its reported 531 N is a factor-of-ten arithmetic error.

## Notes

Some question wording, diagram values, and answer choices are unclear or inconsistent; those cases are flagged with the relevant problem.
