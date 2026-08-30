# MAC21 — Positional Slot Map

Which question appears in **which slot**, across every paper.
This is what makes the a/b choice predictable: the two options in a unit are not random —
each carries a recognisable, recurring *combination* of topics.

**Papers (MAC21-relevant only):** `MP` model paper · `M23` Sep/Oct 2023 · `M24` Jul/Aug 2024 ·
`MAM24` MAM21 2024 (Units I–IV) · `MAE23` MAE21 2023 (Units I–III) · `P26` 25MAC21 2026 (partial)

Off-syllabus content (multiple integrals, Laplace, Beta/Gamma, PDEs, Regula-Falsi,
LU decomposition, Weddle's rule) is **excluded throughout**.

---

## UNIT I — Q1 vs Q2

| | **Q1** | **Q2** |
|---|---|---|
| **MP** | a NR applicability `xe⁻ˣ=0` · b expand `aˣ` · **c NR SYSTEM** · d Lagrange (divide 24) | a explain NR system · **b `xy(1−x−y)` max** · c NR current `i=10e⁻ᵗsin2πt` · **d expand `xy²+cos(xy)` @(1,π/2)** |
| **M23** | **a geom. interp. of NR** · b expand `sin⁻¹x` · **c NR SYSTEM (0.8, 0.4)** · d Lagrange (unit sphere) | a Taylor 1-var · b `x³+y³−3axy` extreme · **c expand `xy+cos(xy)` @(1,π/2)** · d open-top box V=108 |
| **M24** | a define algebraic/transcendental · b expand `tan⁻¹x` · **c NR SYSTEM (0.8, 0.3)** · d extreme `sinx siny sin(x+y)` | a Maclaurin 1-var · b NR `xeˣ−sinx=0` · c expand `eˣlogx` · d Lagrange (dist. to sphere) |
| **MAM24** | a Taylor 2-var · **b NR SYSTEM (0.8, 0.4)** · c Maclaurin `√(1+sin2x)` · d open-top box V=108 | a Maclaurin 1-var · **b `xy(1−x−y)` max** · **c expand `xy+cos(xy)` @(1,π/2)** · d NR `x sinx+cosx=0` |
| **MAE23** | a define maxima/minima · **b `xy(1−x−y)` extreme** · c Maclaurin `tanx` · d NR `x log₁₀x=1.2` | a Taylor 2-var formula · **b NR SYSTEM (3.5, −1.8)** · **c expand `xy+sin(xy)` @(1,π/2)** · d extreme `x³+y³−3x−12y+20` |
| **P26** | a define algebraic/transcendental · **b geom. interp. of NR** · **c NR SYSTEM (1, 0.5)** · d ❌ | a ❌ · b Gauss-Seidel · c NR `xeˣ−sinx=0` · d ❌ |

### Reading
- **NR system lives in Q1(c)** — MP, M23, M24, P26 all at exactly `1c`, 7 marks. (MAM24 `1b`, MAE23 `2b`.) **5 of 6 papers.**
- **"Expand … about (1, π/2)" lives in Q2** — M23 `2c`, MAM24 `2c`, MAE23 `2c`, MP `2d`. **4 of 6, always 7 marks, always Q2.**
- **`xy(1−x−y)` maximum lives in Q2(b)** — MP, MAM24 at `2b`; MAE23 at `1b`. 4 marks.
- **Q1 = NR system + constrained optimisation.** **Q2 = 2-variable expansion + maxima–minima + single-equation NR.**

> **Both options are worth preparing** — Q1 and Q2 each hold one near-certain 7-marker.
> Decide in the hall by looking at the (d) parts.

---

## UNIT II — Q3 vs Q4

| | **Q3** | **Q4** |
|---|---|---|
| **MP** | a RK4 formula · **b Euler `dy/dx−2y=3eˣ`** · **c Taylor `e⁻²ᵗ−2y`** · **d coffee 92→80→65** | **a DE of L–C circuit** · b cardioid orth. traj. · **c MODIFIED EULER** · d RK4 |
| **M23** | a steps orth. traj. · b cooling 300→250 · **c Taylor's method** · d RK4 | a analytical vs numerical · **b bungee jumper Euler** · **c MODIFIED EULER** · **d self-orthogonal `x²/(a²+λ)+y²/(b²+λ)`** |
| **M24** | a Euler's formula · b orth. traj. `rⁿ=k cos nθ` · c RK4 · d orth. traj. `x²+y²−2a log x` | **a DE of R–C circuit** · b Taylor's method · **c MODIFIED EULER** · d coffee 90→75→60 |
| **MAM24** | a Euler's formula · b orth. traj. `r=b sinθ` · c cooling 100→70→40 · d RK4 | a define orth. traj. · b Taylor's method · **c MODIFIED EULER** · d LR circuit `Ee^(at)` |
| **MAE23** | a define orth. traj. · **b bungee jumper Euler** · c *(exact DE — peripheral)* · d RC circuit charge/current | a steps orth. traj. polar · b *(exact DE — peripheral)* · **c self-orthogonal `x²/(a²+λ)+y²/(b²+λ)`** · d RK4 |
| **P26** | *(scattered across its Q5/Q6/Q9/Q10)* — **a DE of L–C circuit**, orth. traj. co-axial circles, **coffee 92→80→65**, **Taylor `e⁻²ᵗ−2y`**, Modified Euler, **Euler `dy/dx−2y=3eˣ`**, RK4 | |

### Reading
- **Modified Euler lives at exactly `4c`** — MP, M23, M24, MAM24. **4 of 5, same slot, 7 marks.** Strongest positional lock in Unit II.
- **RK4 appears in all 6 papers**, position alternates `3d` ↔ `4d`, always 7 marks.
- **Newton's law of cooling in 5 of 6**, at `3b`, `3c`, `3d` or `4d`.
- **Orthogonal trajectories in all 6**, often two parts in one paper.
- **Q4 = Modified Euler + a circuit/orthogonal application.** **Q3 = Taylor's or RK4 + cooling.**

---

## UNIT III — Q5 vs Q6  ⭐ *most locked unit*

| | **Q5** | **Q6** |
|---|---|---|
| **MP** | **a steps Cauchy's LDE** · **b `1/(D+a)` PROOF** · c `(D²−2D+1)y=xeˣsinx` · **d VARIATION OF PARAMETERS** | a steps var. of param. · b gen. soln from A.E. · **c LEGENDRE `(x+1)²y″…`** · d IVP `y‴−y″+100y′−100y=0` |
| **M23** | **a steps Cauchy's LDE** · **b `1/(D+a)` PROOF** · **c CAUCHY `x²D²+4xD+4`** · **d VARIATION OF PARAMETERS** | **a define linear/non-linear DE** · b `y⁗−k⁴y=0` · **c LEGENDRE `(3x+2)²y″…`** · d IVP `(D²−2D)y=eˣsinx` |
| **M24** | a define non-homog. 2nd order · **b `1/(D+a)` PROOF** · **c VARIATION OF PARAMETERS** · **d CAUCHY `x²y″+xy′+y`** | a CF from roots −3±i,2,2,2 · b BVP `y″+4y′+4y=0` · c `(D³−3D²+3D−1)y=2ˣ+x` · d `y″−3y′+5y=eˣsin²x` |
| **MAM24** | a CF of 4th-order LDE · b IVP `y″−y=0` · c `(D²−2D+4)y=eˣsinx` · **d CAUCHY `x²y″−xy′`** | a define BVP · b P.I. of `y″−y′` · **c VARIATION OF PARAMETERS** · **d LEGENDRE `(2x+1)²y″…`** |
| **MAE23** | a define BVP · **b LEGENDRE `(2x+3)²y″…`** · c `(D³−7D−6)y` · **d VARIATION OF PARAMETERS** | **a define linear/non-linear DE** · **b `1/(D+a)` PROOF** · c `(D²−4D+3)y=sin3x cos2x` · **d CAUCHY `x²y″−4xy′+6y`** |
| **P26** | b BVP `y″+y=0` · d `(D²+2D+1)y=xe²ˣ` | **a define linear/non-linear DE** · d `y″−3y′+5y=(sin²x)/4` |

### Reading — this is the single most exploitable pattern in the paper
- **`1/(D+a)` proof sits at exactly `5b`** in MP, M23, M24. **3 of 3 MAC21 papers, same slot, 4 marks.** (MAE23 has it at `6b`.)
- **Variation of parameters is in Q5** in MP (`5d`), M23 (`5d`), M24 (`5c`), MAE23 (`5d`). **4 of 5.**
- **Cauchy's equation is in Q5** in M23 (`5c`), M24 (`5d`), MAM24 (`5d`).
- **Legendre's equation is in Q6** in MP (`6c`), M23 (`6c`), MAM24 (`6d`).
- **`Define linear and non-linear DE` sits at exactly `6a`** in M23, MAE23, P26. **3 papers, same slot, 2 marks.**

> ## ✅ ANSWER Q5 IN UNIT III
> In MP, M23 and M24 — all three exact-match papers — **Q5 contains
> `1/(D+a)` proof [4] + Cauchy [7] + variation of parameters [7] = 18 of 20 marks**
> from three techniques you can fully prepare. Q6 is the Legendre/miscellaneous side and
> is far less stable.

---

## UNIT IV — Q7 vs Q8

| | **Q7** | **Q8** |
|---|---|---|
| **MP** | a define fwd/bwd difference · **b formula `dy/dx`,`d²y/dx²` N-G fwd** · c `f(14.2)` backward · d Simpson 3/8 `∫dx/(1+x)²` | a `Δ²y₂`,`Δ³y₁` · **b trapezoidal `∫dx/(1+x²)`** · **c DIVIDED DIFFERENCE cubic (2,4)(4,56)(9,711)(10,980)** · d derive `d²y/dx²`, `f″(1.1)` |
| **M23** | **a `∇²yₙ` in terms of y** · b backward difference table · **c Simpson 1/3 `∫dx/(1+x²)` → π** · d radius of curvature | **a LAGRANGE INVERSE FORMULA** · b trapezoidal `∫eˣdx` · **c DIVIDED DIFFERENCE `f(1)`** · **d GROUPED FREQUENCY (income 20–25)** |
| **M24** | **a formula `y′`,`y″` N-G fwd** · b `cosh(0.56)` · c Lagrange `f(4)` · **d DIVIDED DIFFERENCE cubic (2,4)(4,56)(9,711)(10,980)** | a Simpson 1/3 formula · **b MISSING TERMS** · c `dy/dx`,`d²y/dx²` at x=7 · d Simpson 3/8 `∫(1−8x³)dx` |
| **MAM24** | a Simpson 1/3 formula · b Lagrange `f(1)` · **c DIVIDED DIFFERENCE `f(5)`** · d `y′(0)`,`y″(0)` | **a LAGRANGE INVERSE FORMULA** · **b MISSING TERMS (45…65 / 3.0,–,2.0,–,–2.4)** · **c GROUPED FREQUENCY (Covid 35–40)** · d Simpson 3/8 `∫dx/(1+x²)` |
| **P26** | **a `Δ²yₙ` in terms of y** · b Lagrange inverse `y=15` · **c GROUPED FREQUENCY (marks 70–75)** · d rate of cooling `t=8` | a 1st-order divided difference · **b MISSING TERMS (45…65 / 3.0,–,2.0,–,–2.4)** · c Lagrange polynomial · d max/min from data |

### Reading
- **"Find the missing terms" sits at exactly `8b`** — M24, MAM24, P26. **3 of 3, 4 marks.**
  MAM24 and P26 use the **identical table**: `x = 45,50,55,60,65`, `y = 3.0, –, 2.0, –, −2.4`.
- **"Lagrange's inverse interpolation formula" (state it) sits at `8a`** — M23, MAM24. 2 marks.
- **Grouped-frequency estimation** — M23 `8d`, MAM24 `8c`, P26 `7c`. 7 marks. Data changes every time.
- **Newton's divided difference in 5 of 5** — MP `8c`, M23 `8c`, M24 `7d`, MAM24 `7c`, P26 `8c`.
- **The `Δ²yₙ` / `∇²yₙ` 2-marker sits at `7a`** — M23, P26.

> ## ✅ ANSWER Q8 IN UNIT IV
> Q8 reliably bundles **Lagrange inverse formula [2] + missing terms [4] + divided
> difference [7] + grouped frequency [7]** — four highly repetitive items.

---

## UNIT V — Q9 vs Q10  ⭐⭐ *fully predictable*

Only MP, M23 and M24 have this unit (25MAC21 dropped it).

| | **Q9** | **Q10** |
|---|---|---|
| **MP** | a is every square matrix diagonalizable? · b rank = 2, find x · **c DIAGONALIZE `[[1,−1],[2,4]]`, find A⁸** · **d RAYLEIGH `[1 1 1]ᵀ`** | a define modal & spectral matrix · b geom. interp. many solutions · **c GAUSS-SEIDEL** · **d SYSTEM OF ODEs `x′=Ax`** |
| **M23** | a define row echelon form · **b GAUSS-SEIDEL (0,0,0), 2 iter** · **c MODAL MATRIX, char eq `(λ−7)²(λ+2)`** · d Gauss elimination (electrical network) | a geom. interp. infinitely many solutions · **b RAYLEIGH `[1,0,0]ᵀ`, 2 iter** · c conditions on a,b,c · **d SYSTEM OF ODEs (rabbit/wolf)** |
| **M24** | a define rank · b `λ` of A ⇒ `1/λ` of A⁻¹ · **c RAYLEIGH `[1,0,0]ᵀ`, 5 iter** · **d DIAGONALIZE, find A⁴** | a consistency conditions `AX=B` · **b GAUSS-SEIDEL (1,0,0), 2 iter** · c Gauss elimination (dietician) · **d SYSTEM OF ODEs `x₁′=x₁+x₂`** |

### Reading
- 🎯 **System of ODEs by matrix method sits at exactly `10d` — in all 3 papers. Always the very last question of the entire exam. 7 marks.**
- **Gauss-Seidel in all 3** — `9b` (M23), `10b` (M24), `10c` (MP). 4 or 7 marks.
- **Rayleigh's power method in all 3** — `9d` (MP), `10b` (M23), `9c` (M24). Initial vector `[1,0,0]ᵀ` or `[1,1,1]ᵀ`.
- **Diagonalization / modal matrix in all 3** — `9c` (MP), `9c` (M23), `9d` (M24). **Always 7 marks.**
- **Gauss elimination applied word problem** — `9d` (M23), `10c` (M24).
- **All four 2-mark slots are definitions**: rank · row echelon form · consistency conditions ·
  modal & spectral matrix · "is every square matrix diagonalizable" · geometric interpretation.

> ## ✅ ANSWER Q10 IN UNIT V
> Q10 bundles **a definition [2] + Gauss-Seidel [4] + Gauss elimination or consistency [7]
> + system of ODEs by matrix method [7]**. But Unit V is only ~6 techniques total —
> learn all of it, it is the cheapest unit in the paper.
