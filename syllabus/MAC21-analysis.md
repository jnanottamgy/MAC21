# MAC21 — Portion Analysis

Analysis of the session-wise portion in `MAC21-portion.md`.

## 1. Shape of the paper

| Unit | Title | Sessions | Hrs | Share |
|---|---|---|---|---|
| I | Series Expansion of Functions & their Applications | 1–6 | 6 | 21% |
| II | First Order ODE & Numerical Solution of First Order ODE | 7–11 | 5 | 18% |
| III | Linear Differential Equations of Higher Order | 12–17 | 6 | 21% |
| IV | Interpolation, Numerical Differentiation & Integration | 18–23 | 6 | 21% |
| V | Linear Algebra | 24–28 | 5 | 18% |

Contact hours are near-uniform (5–6 per unit), so no unit is a throwaway.
Unit weightage in the paper most likely tracks this split.

## 2. Two threads running through the course

The course name is the giveaway — it interleaves two parallel tracks:

- **Analytical / closed-form:** Unit I (series, maxima–minima, Lagrange
  multipliers), Unit II first half (LR–RC circuits, Newton's law of cooling,
  orthogonal trajectories), all of Unit III, Unit V (rank, eigenvalues,
  diagonalization).
- **Numerical / algorithmic:** Newton-Raphson (I), Taylor/Euler/RK4 for ODEs
  (II), all of Unit IV, Gauss elimination / Gauss-Seidel / Rayleigh's power
  method (V).

Roughly **half the portion is numerical method application** — plug into a
formula, tabulate, iterate. These are the highest marks-per-minute topics
because the method is fixed and only the arithmetic changes.

## 3. Topic classification

### Formula-driven — memorise the formula, marks follow
These are near-guaranteed scoring. The procedure never varies.

- Newton-Raphson iteration formula (single variable + 2×2 system)
- Taylor's series method for ODEs
- Euler's & modified Euler's method
- Runge-Kutta 4th order
- Newton-Gregory forward / backward interpolation
- Lagrange's interpolation; Newton's divided difference
- Trapezoidal rule; Simpson's 1/3 and 3/8
- Gauss elimination; Gauss-Seidel iteration
- Rayleigh's power method

### Procedure-driven — fixed method, needs practice not memory
- Homogeneous LDE with constant coefficients (auxiliary equation, root cases)
- Particular Integral for standard cases (e^ax, sin/cos, x^n, e^ax·V)
- Cauchy's & Legendre's equations (substitution x = e^z reduces to constant coeff.)
- Method of variation of parameters (Wronskian setup)
- Echelon form, rank, consistency
- Eigenvalues, eigenvectors, diagonalization
- System of ODEs by matrix method
- Maxima–minima of two variables (r, s, t test)
- Lagrange's undetermined multipliers

### Derivation / theory — likely short-answer questions
- Newton-Raphson derivation and **geometrical interpretation**
- Taylor's & Maclaurin's expansion (one and two variables)
- Finite differences (operator relations: Δ, ∇, E, δ, μ)
- Newton-Cotes quadrature formula (Trapezoidal & Simpson are its special cases)
- Consistency conditions for a system of linear equations

### Application / modelling — word problems
- LR and RC circuits
- Newton's law of cooling
- Orthogonal trajectories

## 4. Dependency chains — study in this order within a unit

- **Unit III:** Session 12 (homogeneous) → 13/14 (PI) → 15 (Cauchy/Legendre)
  → 16 (IVP/BVP) → 17 (variation of parameters). Do **not** attempt 15–17
  before 12–14 are solid; they all rest on the auxiliary-equation machinery.
- **Unit IV:** 18 (finite differences) → 19/20 (interpolation) → 21 (numerical
  differentiation, built on the interpolation polynomials) → 22/23 (integration).
  Session 18 is the foundation for the whole unit.
- **Unit V:** 24 (elementary transformations/rank) → 25 (Gauss methods) is one
  chain; 26 (eigen) → 27 (diagonalization, power method) → 28 (system of ODEs)
  is another. Session 28 needs Unit III *and* session 26.
- **Cross-unit:** Unit I session 1 (Taylor's series) is a prerequisite for
  Unit II session 9 (Taylor's series method for ODEs).

## 5. High-yield observations

1. **Unit IV is the cheapest unit to secure.** Every session except 18 is a
   formula you apply to a table of values. Master session 18's operator
   relations and the rest is mechanical.
2. **Unit III is the most expensive.** Six sessions of technique with heavy
   internal dependency and case-splitting (repeated roots, complex roots, PI
   failure cases). It carries ~21% of the portion but takes disproportionate
   time. Do not leave this for last.
3. **Numerical methods cluster into one habit.** Newton-Raphson, Taylor,
   Euler, RK4, Gauss-Seidel and Rayleigh's power method are all *iterate until
   convergence* problems. Learn the iteration discipline once — tabulate
   columns, carry 4 decimals, state the stopping criterion — and it transfers
   across four units.
4. **Sessions 3–4 and 5–6 are Unit I's real content.** One-variable Taylor
   (session 1) is revision from prior maths; two-variable expansion,
   maxima–minima and Lagrange multipliers are the new, examinable material.
5. **Session 28 is a likely full-marks question** — it fuses Unit III and
   Unit V, which makes it attractive to paper-setters.
