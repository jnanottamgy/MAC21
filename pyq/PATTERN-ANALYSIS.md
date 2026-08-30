# MAC21 — PYQ Pattern Analysis

Derived from 4 question papers + the official course handbook.
Shorthand used below:

| Tag | Paper | Match |
|---|---|---|
| **M23** | MAC21, Sep/Oct 2023 (CSE) | ✅ exact |
| **M24** | MAC21, Jul/Aug 2024 (CSE) | ✅ exact |
| **MAM24** | MAM21, Jul/Aug 2024 (MECH/IEM/CHE) | ⚠️ Units I–IV only |
| **MAE23** | MAE21, Sep/Oct 2023 (ECE/EEE) | ⚠️ Units I–III only |
| **MP** | **MAC21 SEE Model Question Paper I** (Dept. of Mathematics) | ⭐ **exact — and predictive** |
| **P26** | 25MAC21, Jun/Jul 2026 (CSE) | ⚠️ new scheme — see `SYLLABUS-CHANGE-2025.md` |

---

## 0. ⭐ The model paper leaks into the real exam

The Department of Mathematics model paper (`MODEL-PAPER-I-MAC21.md`) carries the printed
disclaimer *"Students should not be under the impression that questions from model question
paper will appear in SEE."*

**Cross-checking it against four real papers shows that disclaimer does not hold.**
The following appeared in an actual exam, most of them word-for-word:

| Model paper question | Reappeared in | Match |
|---|---|---|
| Taylor's series method, `dy/dt = e^(−2t) − 2y`, `y(0) = 0.1`, `t = 0.1`, 4th degree | **P26** 9c | 🎯 **verbatim** |
| Coffee at 92°C, room 24°C, cooled to 80°C in 1 min, time to reach 65°C | **P26** 6c | 🎯 **verbatim** |
| Gauss-Seidel on `x + 8y + 2z = −4`; `10x + 2y + z = 59`; `2x − y + 20z = 74` | **P26** 2b | 🎯 **identical system** |
| DE of the closed circuit with L and C in series without applied e.m.f. | **P26** 5a | 🎯 **verbatim** |
| Cubic polynomial through `(2,4) (4,56) (9,711) (10,980)` by divided difference, `y` at `x = 1.5` | **M24** 7d | 🎯 **verbatim** |
| Prove `[1/(D+a)]X = e^(−ax) ∫ X e^(ax) dx` | **M23** 5b, **M24** 5b, **MAE23** 6b | 🎯 **verbatim ×3** |
| Write the steps involved in solving Cauchy's LDE | **M23** 5a | 🎯 **verbatim** |
| `f(x, y) = xy(1 − x − y)` is maximum at `(1/3, 1/3)` | **MAM24** 2b, **MAE23** 1b | 🎯 **verbatim ×2** |
| Newton-Raphson on `x² + y = 11`, `y² + x = 7`, `x₀ = 3.5`, `y₀ = −1.8` | **MAE23** 2b | 🎯 **verbatim** |
| Formula for `dy/dx` and `d²y/dx²` from Newton-Gregory forward | **M24** 7a | 🎯 **verbatim** |
| Define linear and non-linear differential equations with example | **M23** 6a, **MAE23** 6a, **P26** 6a | 🎯 **verbatim ×3** |
| Current `i = 10e^(−t) sin(2πt)`, find `t` for `i = 2` amp | **P26** 1d | same problem, Regula-Falsi instead of N-R |
| Euler's method on `dy/dx − 2y = 3eˣ` | **P26** 10b | same equation, different `h` and start |
| Expand `xy² + cos(xy)` about `(1, π/2)` | **M23** 2c, **MAM24** 2c, **MAE23** 2c | near-verbatim ×3 |
| Geometrical interpretation of many solutions for `2x + 3y = 5`; `x + 1.5y = 2.5` | **M23** 10a | same question, different system |
| Eigenvector for the largest eigenvalue by Rayleigh's power method | **M23** 10b, **M24** 9c | same method, different matrix |
| `x′ = Ax` solved by matrix method | **M23** 10d, **M24** 10d | same technique |

**That is 17 of the model paper's 40 parts traceable into real exams**, across every unit.
Several landed in the very next paper written under a *different syllabus* — which is the
strongest possible signal that the department reuses this question bank.

### What to do with this
**Work the model paper end to end. It is the single highest-yield document here** — higher
than any individual PYQ, because it is the source several PYQs were drawn from. Every part
of it is on your syllabus, and it is only 40 parts long.

---

## 1. The paper format is rigid — exploit it

Every paper, every year, without exception:

```
100 marks · 3 hours · 5 units
Unit I → Q1 or Q2      Unit IV → Q7 or Q8
Unit II → Q3 or Q4     Unit V  → Q9 or Q10
Unit III → Q5 or Q6

Each question = a) 02  b) 04  c) 07  d) 07  = 20 marks
Answer ONE full question per unit. Internal choice, always 2 options.
```

**The 2-mark part is *always* pure recall** — a definition, a formula to state, or
"write the steps involved in…". Never a calculation. That is **10 marks across the
paper available for memorisation alone**, and you get to pick the easier of two.

**The 4-mark part is a short calculation** — one iteration, one small proof, a P.I.,
a definition-plus-example.

**The two 7-mark parts are full problems.** Typically one is a standard technique and
one is a word problem or applied model.

### What this means tactically
You never have to know all of a unit — you need **one** of two questions per unit.
With internal choice, mastering ~70% of a unit reliably clears it.

---

## 2. Repeat questions — ranked by frequency

These are questions that appeared **verbatim or near-verbatim** in more than one paper.
This is the single highest-value section of this analysis.

### 🔴 Appeared 3–4 times — treat as near-guaranteed

| # | Question | Seen in | Usual slot |
|---|---|---|---|
| 1 | **Newton-Raphson for the system `x² + y² = x`, `x² − y² = y`**, `x₀ = 0.8`, `y₀ = 0.4` (or 0.3) | M23, M24, MAM24 | Unit I, 4 or 7 mk |
| 2 | **Expand `xy + cos(xy)` about `(1, π/2)`** up to 2nd degree *(sin variant in MAE23)* | M23, MAM24, MAE23 | Unit I, 7 mk (c) |
| 3 | **Prove `[1/(D+a)]X = e^(−ax) ∫ X e^(ax) dx`** | M23, M24, MAE23 | Unit III, 4 mk (b) |
| 4 | **Newton's law of cooling** word problem (object/coffee/substance) | M23, M24, MAM24 | Unit II, 4 or 7 mk |
| 5 | **Legendre's LDE** `(ax+b)²y″ + …` — `(3x+2)²`, `(2x+1)²`, `(2x+3)²` | M23, MAM24, MAE23 | Unit III, 7 mk |
| 6 | **Cauchy's LDE** `x²y″ + …` | M24, MAM24, MAE23 | Unit III, 7 mk |
| 7 | **Modified Euler's method**, h = 0.2, two iterations per stage | M23, M24, MAM24 | Unit II, 7 mk |
| 8 | **Taylor's series method** for an ODE | M23, M24, MAM24 | Unit II, 4 or 7 mk |
| 9 | **Newton's divided difference** interpolation | M23, M24, MAM24 | Unit IV, 7 mk |

### 🟠 Appeared twice

| # | Question | Seen in |
|---|---|---|
| 10 | **Open-top rectangular box, volume 108 ft³, minimum surface area** | M23, MAM24 |
| 11 | **Self-orthogonal family** `x²/(a²+λ) + y²/(b²+λ) = 1` | M23, MAE23 |
| 12 | **Bungee jumper**, m = 68.1 kg, `dv/dt = g − cv²/m`, Euler's method | M23, MAE23 |
| 13 | **`f(x,y) = xy(1 − x − y)` extreme value at `(1/3, 1/3)`** | MAM24, MAE23 |
| 14 | **Lagrange's inverse interpolation formula** (state it) | M23, MAM24 |
| 15 | **Find the missing terms** in a data table | M24, MAM24 |
| 16 | **Grouped-frequency estimation** (income group 20–25 / Covid age 35–40) | M23, MAM24 |
| 17 | **`∫₀¹ dx/(1+x²)` by Simpson's rule** → approximate π | M23, MAM24 |
| 18 | **Variation of parameters on `y″ + 2y′ + 2y = e^(±x) secⁿx`** | M23, M24 |
| 19 | **Define linear and non-linear differential equations** | M23, MAE23 |
| 20 | **Gauss-Seidel, 2 iterations, given initial approximation** | M23, M24 |
| 21 | **Rayleigh's power method**, initial vector `[1,0,0]ᵀ` | M23, M24 |
| 22 | **System of ODEs by matrix method** | M23, M24 |
| 23 | **Gauss elimination on an applied word problem** (electrical network / dietician) | M23, M24 |
| 24 | **Diagonalization / modal matrix** | M23, M24 |

---

## 3. Unit-by-unit: what actually gets asked

### UNIT I — always the same four ingredients
Across all 4 papers, Unit I is built from exactly these:
1. **Series expansion** (Taylor/Maclaurin, one *or* two variables) — 1 part, usually 4 or 7 mk
2. **Newton-Raphson** — single equation *or* system of two. **In every paper.**
3. **Maxima–minima of two variables** (r-s-t test) — 1 part
4. **Lagrange multipliers** — constrained optimisation word problem, 7 mk

The 2-mark part is always: *state Taylor's / Maclaurin's series*, *define algebraic &
transcendental equations*, *define maxima and minima*, or *geometrical interpretation of
Newton-Raphson*. Four known options.

**Lagrange-multiplier word problems seen:** hottest point on a unit sphere · open-top box
of fixed volume · max & min distance from a point to a sphere. All the same method.

### UNIT II — numerical methods dominate
Split is consistently **~2 parts numerical, ~2 parts applied ODE**.

- **Numerical (pick any 2 of 4 each year):** Taylor's series method · Euler's · Modified
  Euler's · RK4. **RK4 appeared in all 4 papers.** `h = 0.2` almost always.
- **Applied:** Newton's law of cooling · orthogonal trajectories (Cartesian *and* polar) ·
  LR / RC circuit.

2-mark part: *write Euler's formula* · *define orthogonal trajectories* · *steps to find
orthogonal trajectories* · *write the DE of an RC circuit* · *two differences between
analytical and numerical methods*.

### UNIT III — the most predictable unit in the paper
Nearly every Unit III question is assembled from:
- **CF + PI for constant coefficients** (standard cases)
- **Cauchy's OR Legendre's equation** — 7 mk, in *every single paper*
- **Variation of parameters** — 7 mk, in *every single paper*
- **The `1/(D+a)` operator proof** — 4 mk, in 3 of 4 papers
- **IVP / BVP** — small, 4 mk

2-mark part: *define linear/non-linear DE* · *define BVP* · *define non-homogeneous 2nd
order LDE* · *write the CF given the roots of the A.E.* · *steps to solve Cauchy's LDE*.

> Despite being the heaviest unit to learn, Unit III is the **most formulaic to answer**.
> Cauchy/Legendre + variation of parameters alone = 14 of the 20 marks, every year.

### UNIT IV — the most mechanical unit
- **Interpolation:** Newton-Gregory forward/backward · Lagrange's · **Newton's divided
  difference (3 papers)**
- **Special interpolation tricks:** missing terms (2 papers) · grouped-frequency
  estimation (2 papers) — *learn the cumulative-frequency setup, it is not obvious*
- **Numerical differentiation:** `y′`, `y″` from a table
- **Numerical integration:** Trapezoidal · Simpson's 1/3 · Simpson's 3/8. At least one
  appears every year; the `∫dx/(1+x²) → π` problem recurs.

2-mark part: *state Simpson's 1/3 rule* · *Lagrange's inverse interpolation formula* ·
*the `y′(x)` formula from Newton-Gregory forward* · *express `∇²yₙ` in terms of y*.

### UNIT V — essentially fully predictable (2/2 MAC21 papers agree)

| Slot | What appears |
|---|---|
| **a) 02** | Define rank · define row echelon form · consistency conditions for `AX = B` · geometric meaning of infinitely many solutions |
| **b) 04** | **Gauss-Seidel, 2 iterations** · **Rayleigh's power method** · small eigenvalue proof (λ of A ⇒ 1/λ of A⁻¹) |
| **c) 07** | **Diagonalization / modal matrix** · consistency conditions with parameters `a, b, c` · Rayleigh's power method (longer) |
| **d) 07** | **Gauss elimination on a word problem** (electrical network, dietician/nutrition) · **System of ODEs by matrix method** |

**Both MAC21 papers ended the entire exam with "system of ODEs by matrix method."**
Session 28 of your portion. It fuses Unit III with eigenvalues — high probability, and
often left unstudied because it's the last topic taught.

---

## 4. What has *never* been asked

Useful for triage if you are short on time. Across all 4 papers:
- Nothing from the syllabus was untouched over 2 years, but these appeared **only once**:
  - Backward difference *table construction* (M23 7b)
  - `∇²yₙ` expression in terms of y values (M23 7a)
  - Radius of curvature via interpolation (M23 7d)
  - Proof that `y⁗ − k⁴y = 0` has the cos/sin/cosh/sinh solution (M23 6b)
  - `(D³ − 3D² + 3D − 1)y = 2ˣ + x` (M24 6c)
- **Trapezoidal rule** appeared only once as a solved problem (M23 8b) but is stated in
  the syllabus and is the easiest of the three integration rules — cheap insurance.

---

## 5. Cross-checks against the official handbook

From `syllabus/MAC21-course-handbook.pdf`:
- **Course structure:** 2:1:1 credits, 28L + 14T + 14P. SEE = 100 marks; CIE = 50.
- **SEE instruction confirmed:** *"Answer any one question from each unit — internal choice."*
- **CO mapping:** CO1→Unit I, CO2→Unit II, CO3→Unit III, CO4→Unit IV, CO5→Unit V.
  The papers tag every part with its CO, so the unit ↔ CO mapping is 1:1 and stable.
- **The 10 lab programs map almost exactly onto the recurring exam questions:**
  extreme values of two-variable functions · Newton-Raphson (single & system) · Taylor &
  Euler · Modified Euler & RK4 · higher-order ODEs · interpolation (equi- and
  non-equispaced) · Trapezoidal/Simpson · Gauss-Seidel · Rayleigh power method.
  **If it is a lab program, it is an exam question.** That list is effectively a
  second, independent confirmation of the repeat table in §2.
- **Textbook:** B.S. Grewal, *Higher Engineering Mathematics*, 44th ed. — the numerical
  chapters are where these problems are lifted from nearly verbatim.

---

## 6. Highest-yield conclusions

0. **Work the official model paper first.** 17 of its 40 parts have been traced into real
   exams, many verbatim, across every unit and across two different syllabus schemes. It
   is short, entirely on-syllabus, and demonstrably the question bank the papers draw on.
1. **Nine questions have appeared 3+ times.** Working through just those nine covers a
   large fraction of a typical paper.
2. **Unit V is the most predictable unit and Unit III the most formulaic.** Together
   that's 40 marks with very little uncertainty.
3. **The 2-mark parts are a fixed, small pool of definitions** — roughly 20 distinct ones
   across all five units, and you choose the easier of two each time. 10 marks, pure recall.
4. **RK4, Newton-Raphson, variation of parameters, Cauchy/Legendre, Newton's divided
   difference, Gauss-Seidel, Rayleigh's power method, and system of ODEs by matrix
   method appear in essentially every paper.** Eight techniques ≈ the backbone of the exam.
5. **The lab program list predicts the exam.** Anything you implemented in the lab is a
   likely 7-mark question.
