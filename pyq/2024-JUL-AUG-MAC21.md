# MAC21 — SEE July / August 2024

**Institution:** Ramaiah Institute of Technology (Autonomous, affiliated to VTU)
**Programme:** B.E. — Common to CSE / ISE / CSE(CY) / AI&DS / BT / AI&ML / CSE(AI&ML)
**Semester:** II · **Course:** Numerical Techniques and Differential Equations (MAC21)
**Max Marks:** 100 · **Duration:** 3 Hrs
**Instruction:** Answer one full question from each unit.

> This is a **direct-match** paper: same course code, same branch, same syllabus.
>
> ⚠️ **Transcription note:** the source PDF is an OCR scan whose reading order is
> scrambled. Question *content* below is reliable; a few part labels (a/b/c/d)
> and mark splits are reconstructed from the standard 2/4/7/7 pattern and may be
> slightly off. Check `raw/2024-JUL-AUG-MAC21.pdf` if an exact label matters.

---

## UNIT — I

**Q1.**
- **a)** Define algebraic & transcendental equations with an example. — CO1 (02)
- **b)** Expand `tan⁻¹x` in powers of `(x − 1)` up to the term containing fourth degree. — CO1 (04)
- **c)** Solve the system of non-linear equations `x² + y² = x`, `x² − y² = y` using Newton-Raphson method (carry out two iterations), given `x₀ = 0.8`, `y₀ = 0.3`. — CO1 (07)
- **d)** Find the extreme values of `f(x, y) = sin x · sin y · sin(x + y)`, for `0 < x < π`, `0 < y < π`. — CO1 (07)

**Q2.**
- **a)** Write Maclaurin's series for the function of one variable. — CO1 (02)
- **b)** Find a negative root of the equation `x eˣ − sin x = 0` using Newton-Raphson method, correct to three decimals. — CO1 (04)
- **c)** Expand the function `eˣ log x` about `(1, −3)` up to second degree terms. — CO1 (07)
- **d)** Find the maximum and minimum distances of the point `(2, 3, 8)` from the sphere `x² + y² + z² = 56`. — CO1 (07)

## UNIT — II

**Q3.**
- **a)** Write Euler's formula to solve first order and first degree ODE. — CO2 (02)
- **b)** If `rⁿ = k cos(nθ)` is the orthogonal trajectory of a given family of curves, where k is a parameter, find the differential equation of that family. — CO2 (04)
- **c)** Using Runge-Kutta method of fourth order, find y at `x = 0.2` taking `h = 0.2`, if `dy/dx = x² + y²`, `y(0) = 1`. — CO2 (07)
- **d)** Obtain the orthogonal trajectories of the family of curves `x² + y² − 2a log x = c`, where c is the parameter. — CO2 (07)

**Q4.**
- **a)** Write the DE of the closed circuit involving R and C along with a voltage source E. — CO2 (02)
- **b)** Using Taylor's series method solve the IVP at `t = 0.1`: `dy/dt = e^t − 2y`, `y(0) = 1`, considering derivatives up to 3rd degree. — CO2 (04)
- **c)** Use Euler's modified method to solve `dy/dx = ...`, `y(3) = 2` at `x = 3.4` taking `h = 0.2` (perform two iterations at each stage). — CO2 (07)
- **d)** The temperature of a cup of coffee is 90°C when freshly poured, the room temperature being 24°C. In one minute it has cooled to 75°C. How long must elapse before the temperature of the coffee becomes 60°C? — CO2 (07)

## UNIT — III

**Q5.**
- **a)** Define non-homogeneous linear differential equation of 2nd order with an example. — CO3 (02)
- **b)** If `D = d/dx` and `X = X(x)`, prove that `[1/(D+a)] X = e^(−ax) ∫ X e^(ax) dx`. — CO3 (04)
- **c)** Solve `y″ + 2y′ + 2y = eˣ sec²x` by the method of variation of parameters. — CO3 (07)
- **d)** Solve `x² y″ + x y′ + y = x log x`  *(Cauchy form)*. — CO3 (07)

**Q6.**
- **a)** Write the complementary function if the roots of the auxiliary equation are `−3 ± i, 2, 2, 2`. — CO3 (02)
- **b)** Solve the boundary value problem `y″ + 4y′ + 4y = 0`, `y(1) = 0`, `y′(0) = −1`. — CO3 (04)
- **c)** Solve `(D³ − 3D² + 3D − 1)y = 2ˣ + x`. — CO3 (07)
- **d)** Solve `y″ − 3y′ + 5y = eˣ sin²x`. — CO3 (07)

## UNIT — IV

**Q7.**
- **a)** Write the formula to find `y′(x)` and `y″(x)` using Newton-Gregory forward interpolation formula when `x = x₀`. — CO4 (02)
- **b)** From the table below, estimate the value of `cosh(0.56)`. — CO4 (04)

  | x | 0.5 | 0.6 | 0.7 | 0.8 |
  |---|-----|-----|-----|-----|
  | cosh(x) | 1.1276 | 1.1855 | 1.2552 | 1.3374 |

- **c)** Use Lagrange's interpolation formula to find the value of `f(4)` from the given data. — CO4 (07)
- **d)** Find the cubic polynomial `y = a + bx + cx² + dx³` which passes through the points `(2, 4)`, `(4, 56)`, `(9, 711)`, `(10, 980)` using Newton's divided difference method, and hence estimate y when `x = 1.5`. — CO4 (07)

**Q8.**
- **a)** Write Simpson's 1/3rd rule for numerical integration. — CO4 (02)
- **b)** Find the missing terms in the following data. — CO4 (04)

  | x | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
  |---|---|---|---|---|---|---|---|
  | y | 2 | 5 | — | 13 | 22 | — | 63 |

- **c)** Find `dy/dx` and `d²y/dx²` at `x = 7` from the given data. — CO4 (07)
- **d)** Using Simpson's 3/8th rule, obtain an approximate value of the integral `∫ (1 − 8x³) dx` by considering seven equidistant ordinates. — CO4 (07)

## UNIT — V

**Q9.**
- **a)** Define rank of a given matrix. — CO5 (02)
- **b)** Prove that if λ is an eigenvalue of a matrix A, then `1/λ` is an eigenvalue of the inverse matrix `A⁻¹`. — CO5 (04)
- **c)** Find the eigenvector corresponding to the largest eigenvalue of the matrix `A = [[1, 3, −1], [3, 2, 4], [−1, 4, 10]]` by Rayleigh's power method, taking `[1, 0, 0]ᵀ` as the initial approximation. (Carry out five iterations.) — CO5 (07)
- **d)** Diagonalize the matrix `A` and hence find `A⁴`. — CO5 (07)

**Q10.**
- **a)** Write the conditions for consistency and inconsistency of the system of linear equations `AX = B`. — CO5 (02)
- **b)** Solve the system `5x + 2y + z = 12`; `x + 4y + 2z = 15`; `x + 2y + 5z = 20` using Gauss-Seidel method, taking `(1, 0, 0)` as initial approximation. Perform two iterations. — CO5 (04)
- **c)** The following table gives the amount in milligrams of vitamin A, vitamin C and calcium contained in 1 gram of three different foods. A dietician wants to prepare a meal that provides 200 mg of vitamin A, 250 mg of vitamin C and 300 mg of calcium. How much of each food should be used? *(Use Gauss elimination method.)* — CO5 (07)

  |  | Food 1 | Food 2 | Food 3 |
  |---|---|---|---|
  | Vitamin A | 10 | 30 | 20 |
  | Vitamin C | 50 | 30 | 25 |
  | Calcium | 60 | 20 | 40 |

- **d)** Solve the system of first order and first degree linear ODEs `x₁′ = x₁ + x₂`, `x₂′ = 3x₁ + 3x₂`; `x₁(0) = 0`, `x₂(0) = 1`, using the matrix method. — CO5 (07)
