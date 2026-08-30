# 25MAC21 — SEE June / July 2026  ⚠️ **NEW SYLLABUS**

**Institution:** Ramaiah Institute of Technology (Autonomous, affiliated to VTU)
**Programme:** B.E. — Common to CSE / ISE / CSE(CY) / AI&DS / BT / AI&ML / CSE(AI&ML)
**Semester:** II · **Course:** **Numerical Methods** (**25MAC21**)
**Max Marks:** 100 · **Duration:** 3 Hrs
**Instruction:** Answer one full question from each unit.

> ## 🚨 This is a DIFFERENT COURSE from MAC21
> Course code changed `MAC21` → `25MAC21`. Course name changed from
> *"Numerical Techniques and Differential Equations"* → *"**Numerical Methods**"*.
> **The unit structure is substantially different.** See
> [`SYLLABUS-CHANGE-2025.md`](SYLLABUS-CHANGE-2025.md) for the full delta.

---

## UNIT — I  *(Root finding & systems of linear equations)*

**Q1.**
- **a)** Define algebraic and transcendental equations with an example each. — CO1 (02)
- **b)** Give the geometrical interpretation of Newton-Raphson method. — CO1 (04)
- **c)** Solve the system of non-linear equations using Newton-Raphson method: `x = x² + y²`; `y = x² − y²`. Take initial approximation `(1, 0.5)` and carry out two iterations. — CO1 (07)
- **d)** The current `i` in an electric circuit is given by `i = 10e^(−t) sin(2πt)`, where `t` is in seconds. Using **Regula-Falsi** method, find the value of `t` for `i = 2` amperes. Carry out three iterations. — CO1 (07)

**Q2.**
- **a)** Give a geometrical interpretation of **Regula-Falsi** method. — CO1 (02)
- **b)** Use Gauss-Seidel method to solve the following system by taking `(1, 1, 1)` as an initial approximation. Carry out two iterations: `x + 8y + 2z = −4`; `2x − y + 20z = 74`; `10x + 2y + z = 59`. — CO1 (04)
- **c)** Find a negative root of the equation `x eˣ − sin x = 0` correct to three decimal places using Newton-Raphson method. — CO1 (07)
- **d)** Solve the following system using **LU decomposition**: `2x + 4y − 3z = −9`, `−x + 2y + 2z = 2`, `x + y + z = 4`. — CO1 (07)

## UNIT — II  *(Multiple Integrals)* 🆕 **entirely new unit**

**Q3.**
- **a)** With the help of a neat diagram, mark the region of integration in `∫₀² ∫_(2−x)^(√(4−x²)) f(x, y) dy dx`. — CO2 (02)
- **b)** Evaluate `∫₀^π ∫₀^a r³ sin θ cos θ dr dθ`. — CO2 (04)
- **c)** Evaluate `∭_R (x + y + z) dx dy dz`, where R is the region bounded by `(0,0,0)`, `(1,0,0)`, `(0,1,0)`, `(0,0,1)`. — CO2 (07)
- **d)** By changing the order of integration, evaluate `∫₀^∞ ∫₀^x x e^(−x²/y) dy dx`. — CO2 (07)

**Q4.**
- **a)** Write the procedure of evaluating a triple integral by changing into **cylindrical coordinates**. — CO2 (02)
- **b)** Evaluate `∫₀¹ ∫₀^(x²) e^(y/x) dy dx`. — CO2 (04)
- **c)** Evaluate the integral `∫₀^(2a) ∫₀^(√(2ax−x²)) x² dy dx` by changing to **polar coordinates**. — CO2 (07)
- **d)** Find the volume of the sphere `x² + y² + z² = a²` using triple integration. — CO2 (07)

## UNIT — III  *(Differential equations — applications + constant coefficients)*

**Q5.**
- **a)** Write the differential equation of the closed circuit involving L and C both in series without applied e.m.f. — CO3 (02)
- **b)** Solve the boundary value problem `y″ + y = 0`, `y(0) = 2`, `y(π/2) = −2`. — CO3 (04)
- **c)** Find the orthogonal trajectories of the family of co-axial circles `x² + y² + 2gx + c = 0`, where `g` is the parameter. — CO3 (07)
- **d)** Solve the differential equation `(D² + 2D + 1)y = x e^(2x)`. — CO3 (07)

**Q6.**
- **a)** Define linear and non-linear differential equations with example. — CO3 (02)
- **b)** Show that `r = b sin θ` is the orthogonal trajectory of the family of curves `r = a cos θ`. — CO3 (04)
- **c)** The temperature of a cup of coffee is 92°C when freshly poured, the room temperature being 24°C. In one minute it was cooled to 80°C. How long a period must elapse before the temperature of the cup becomes 65°C? — CO3 (07)
- **d)** Solve `d²y/dx² − 3 dy/dx + 5y = (sin²x)/4`. — CO3 (07)

## UNIT — IV  *(Interpolation & numerical differentiation)*

**Q7.**
- **a)** Obtain the expression for `Δ²yₙ` in terms of y values. — CO4 (02)
- **b)** Find the value of x when `y = 15` from the following data using **Lagrange's inverse interpolation**. — CO4 (04)

  | x | 6 | 9 | 11 |
  |---|---|---|----|
  | y | 13 | 14 | 16 |

- **c)** From the following table, estimate the number of students who obtained marks between 70 & 75. — CO4 (07)

  | Marks | 30–40 | 40–50 | 50–60 | 60–70 | 70–80 |
  |---|---|---|---|---|---|
  | No. of students | 31 | 42 | 51 | 35 | 31 |

- **d)** The following table gives the temperature θ in °C of a cooling body at different instants of time t in seconds. Find the **rate of cooling at `t = 8` sec**. — CO4 (07)

  | t | 1 | 3 | 5 | 7 | 9 |
  |---|---|---|---|---|---|
  | θ | 85.3 | 74.5 | 67 | 60.5 | 54.3 |

**Q8.**
- **a)** Find the first order divided difference of `x₀ = 1` & `x₁ = 2` if `y = x³ + 4x + 3`. — CO4 (02)
- **b)** Find the missing terms from the following data: — CO4 (04)

  | x | 45 | 50 | 55 | 60 | 65 |
  |---|----|----|----|----|----|
  | y | 3.0 | — | 2.0 | — | −2.4 |

- **c)** If `y(0) = −3`, `y(3) = 9`, `y(4) = 30`, find the Lagrange's interpolating polynomial that takes these values. — CO4 (07)
- **d)** Find the maximum and minimum values of the function `y = f(x)` from the following data. — CO4 (07)

  | x | 1 | 3 | 5 | 7 | 9 |
  |---|---|---|---|---|---|
  | y | 9 | 11 | 13 | 63 | 209 |

## UNIT — V  *(Numerical integration & numerical solution of ODEs)*

**Q9.**
- **a)** Write the formula for **Weddle's rule** for numerical integration with `n = 6`. — CO5 (02)
- **b)** Give the geometrical interpretation of the trapezoidal rule. — CO5 (04)
- **c)** Using Taylor's series method, solve the IVP at `t = 0.1` considering derivatives up to fourth degree: `dy/dt = e^(−2t) − 2y`; `y(0) = 0.1`. — CO5 (07)
- **d)** Find `y(3.2)` for the given IVP using Modified Euler's method taking `h = 0.2`. Carry out two iterations at each stage: `dy/dx = −y/(1 + x)`; `y(3) = 2`. — CO5 (07)

**Q10.**
- **a)** Write the formula for Simpson's three-eighth rule for numerical integration with `n = 9`. — CO5 (02)
- **b)** Using Euler's method, solve `dy/dx − 2y = 3eˣ`; `y(1) = 0` at `x = 1.1` by taking `h = 0.05`. — CO5 (04)
- **c)** Find an approximate value of `∫₀^(π/2) √(1 + cos²θ) dθ` by Simpson's one-third rule by dividing the interval into 6 equal parts. — CO5 (07)
- **d)** Use Runge-Kutta method to estimate the value of `y(2.1)` by taking `h = 0.1`, given `dy/dx = y − x²`, `y(2) = 5`. — CO5 (07)
