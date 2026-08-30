# MAC21 — SEE Model Question Paper I  ⭐ **HIGHEST VALUE DOCUMENT**

**Issued by:** Department of Mathematics, Ramaiah Institute of Technology
**Course & Branch:** B.E., Computer Science Engineering Stream
**Subject:** Numerical Techniques and Differential Equations · **Code:** MAC21
**Semester:** II · **Max Marks:** 100 · **Duration:** 3 Hrs
**Instruction:** Answer ONE full question from each unit.
**Source:** MAC21 course manual, pp. 35–37 (same manual as the portion sheet)

> **Official note printed on the paper:** *"Students should not be under the
> impression that questions from model question paper will appear in SEE."*
>
> **⚠️ The evidence contradicts that disclaimer.** See §"Model paper → real paper"
> in [`PATTERN-ANALYSIS.md`](PATTERN-ANALYSIS.md). Multiple questions from this model
> paper have appeared **verbatim** in actual exams, including the June/July 2026 paper.

---

## UNIT — I

**Q1.**
- **a)** Can you find a solution for the equation `x e^(−x) = 0` near `x = 2` using Newton-Raphson method? Justify your answer. — CO1 (02)
- **b)** Expand `aˣ` in powers of x up to first three terms. — CO1 (04)
- **c)** Solve the system of non-linear equations using Newton-Raphson method (carry out two iterations): `x² + y = 11`, `y² + x = 7`, given `x₀ = 3.5`, `y₀ = −1.8`. — CO1 (07)
- **d)** Divide 24 into three parts such that the continued product of the first, square of the second and cube of the third may be maximum. — CO1 (07)

**Q2.**
- **a)** Explain the Newton-Raphson method to find the solution of a system of non-linear simultaneous equations. — CO1 (02)
- **b)** Show that `f(x, y) = xy(1 − x − y)` is maximum at the point `(1/3, 1/3)`. — CO1 (04)
- **c)** The current `i` in an electric circuit is given by `i = 10e^(−t) sin(2πt)` where `t` is in seconds. Using **Newton-Raphson** method, find the value of `t` correct to three decimals for `i = 2` amp. — CO1 (07)
- **d)** Expand the function `xy² + cos(xy)` about `(1, π/2)` up to second degree terms. — CO1 (07)

## UNIT — II

**Q3.**
- **a)** Write Runge-Kutta formula of fourth order to solve first order and first degree ODE. — CO2 (02)
- **b)** Using Euler's method solve `dy/dx − 2y = 3eˣ`; `y(0) = 0` at `x = 0.2` by taking `h = 0.1`. — CO2 (04)
- **c)** Using Taylor's series method solve the IVP `dy/dt = e^(−2t) − 2y`; `y(0) = 1/10` at `t = 0.1 and 0.2`, considering derivatives up to 4th degree. — CO2 (07)
- **d)** The temperature of a cup of coffee is 92°C when freshly poured, the room temperature being 24°C. In one minute it was cooled to 80°C. How long a period must elapse before the temperature of the cup becomes 65°C? — CO2 (07)

**Q4.**
- **a)** Write the DE of the closed circuit involving L and C both in series without applied e.m.f. — CO2 (02)
- **b)** If `dr/dθ = r cot(θ/2)` is the differential equation of the family of cardioids `r = a(1 − cos θ)`, then find its orthogonal trajectory. — CO2 (04)
- **c)** Use Euler's modified method to solve `y′ = 4e^(0.8x) − 0.5y` for `x = 0.2(0.2)0.4`, given `y(0) = 2`. — CO2 (07)
- **d)** Solve `dy/dx = (x² + y²)/eˣ`; `y(0) = 1` at `x = 0.2 and 0.4` using R-K method of fourth order. — CO2 (07)

## UNIT — III

**Q5.**
- **a)** Write the steps involved in solving Cauchy's LDE. — CO3 (02)
- **b)** If `D = d/dx` and `X = X(x)`, prove that `[1/(D+a)] X = e^(−ax) ∫ X e^(ax) dx`. — CO3 (04)
- **c)** Solve `(D² − 2D + 1)y = x eˣ sin x`. — CO3 (07)
- **d)** Solve `y″ − 3y′ + 2y = cos(e^(−x))` by the method of variation of parameters. — CO3 (07)

**Q6.**
- **a)** Write the steps involved in solving the LDE by the method of variation of parameters. — CO3 (02)
- **b)** Find the general solution of a homogeneous equation whose auxiliary equation is `λ³(λ + 4)²(λ² + 2λ + 5)² = 0`. — CO3 (04)
- **c)** Solve `(x+1)² y″ + (x+1) y′ + y = 4 cos[log(x+1)]`  *(Legendre)*. — CO3 (07)
- **d)** Solve `y‴ − y″ + 100y′ − 100y = 0`, `y(0) = 4`, `y′(0) = 11`, `y″(0) = −299`. — CO3 (07)

## UNIT — IV

**Q7.**
- **a)** Define forward and backward difference with an example. — CO4 (02)
- **b)** Write the formula to find `dy/dx` and `d²y/dx²` by using Newton-Gregory forward interpolation formula. — CO4 (04)
- **c)** Compute `f(14.2)` from the following table by applying Newton's backward interpolation formula. — CO4 (07)

  | x | 10 | 12 | 14 | 16 | 18 |
  |---|----|----|----|----|----|
  | y = f(x) | 0.240 | 0.281 | 0.318 | 0.352 | 0.384 |

- **d)** Evaluate `∫₀¹ dx/(1+x)²` using Simpson's 3/8th rule taking 6 subintervals. Compare the result with the exact value. — CO4 (07)

**Q8.**
- **a)** Determine `Δ²y₂` and `Δ³y₁` from the following data. — CO4 (02)

  | x | 1 | 2 | 3 | 4 | 5 |
  |---|---|---|---|---|---|
  | y | 0.0567 | 1.2345 | 1.5678 | 1.0023 | 1.786 |

- **b)** Evaluate `∫₀¹ dx/(1+x²)` using trapezoidal rule taking four equal strips. — CO4 (04)
- **c)** Find the cubic polynomial which passes through the points `(2,4)`, `(4,56)`, `(9,711)`, `(10,980)` using Newton's divided difference method and hence estimate the value of y when `x = 1.5`. — CO4 (07)
- **d)** Derive an expression for `d²y/dx²` using Newton's forward interpolation formula and hence find the value of `f″(1.1)` from the following data. — CO4 (07)

  | x | 1 | 1.2 | 1.4 |
  |---|---|-----|-----|
  | f(x) | 0 | 6 | 21 |

## UNIT — V

**Q9.**
- **a)** Is every square matrix diagonalizable? Justify. — CO5 (02)
- **b)** If `A = [[4−x, 2√5, 0], [2√5, 4−x, √5], [0, √5, 4−x]]`, find the value of x for which the rank of the matrix is 2. — CO5 (04)
- **c)** Diagonalize the matrix `A = [[1, −1], [2, 4]]` and hence find `A⁸`. — CO5 (07)
- **d)** Find the eigenvector corresponding to the largest eigenvalue of `[[2, −1, 0], [−1, 2, −1], [0, −1, 2]]` by taking `[1 1 1]ᵀ` as the initial approximation, by Rayleigh's power method, correct to two decimal places. — CO5 (07)

**Q10.**
- **a)** Define modal and spectral matrix. — CO5 (02)
- **b)** Give the geometrical interpretation of many solutions by considering the system of linear equations `2x + 3y = 5`; `x + 1.5y = 2.5`. — CO5 (04)
- **c)** Use Gauss-Seidel method to solve the system `x + 8y + 2z = −4`; `10x + 2y + z = 59`; `2x − y + 20z = 74`. — CO5 (07)
- **d)** Suppose a particle is moving in a planar force field and its position vector x satisfies `x′ = Ax` with `x(0) = [2.9, 2.6]ᵀ` where `A = [[4, −5], [−2, 1]]`. Solve this initial value problem for `t ≥ 0` using matrix method. — CO5 (07)
