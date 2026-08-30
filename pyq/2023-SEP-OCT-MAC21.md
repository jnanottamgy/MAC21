# MAC21 — SEE September / October 2023

**Institution:** Ramaiah Institute of Technology (Autonomous, affiliated to VTU)
**Programme:** B.E. — Common to CSE / ISE / CSE(CY) / AI&DS / BT / AI&ML / CSE(AI&ML)
**Semester:** II · **Course:** Numerical Techniques and Differential Equations (MAC21)
**Max Marks:** 100 · **Duration:** 3 Hrs
**Instruction:** Answer one full question from each unit.

> This is a **direct-match** paper: same course code, same branch, same syllabus.

---

## UNIT — I

**Q1.**
- **a)** Give the geometrical interpretation of Newton-Raphson iteration formula. — CO1 (02)
- **b)** Expand `sin⁻¹x` in powers of x up to second degree term. — CO1 (04)
- **c)** Solve the system of non-linear equations `x² + y² = x`, `x² − y² = y` using Newton-Raphson method (carry out two iterations), given `x₀ = 0.8`, `y₀ = 0.4`. — CO1 (07)
- **d)** The temperature T at any point (x, y, z) in space is `T = 400xyz²`. Find the highest temperature on the surface of the unit sphere `x² + y² + z² = 1`. — CO1 (07)

**Q2.**
- **a)** Write Taylor's series for the function of one variable. — CO1 (02)
- **b)** Examine `x³ + y³ − 3axy` for extreme values. — CO1 (04)
- **c)** Expand the function `xy + cos(xy)` about the point `(1, π/2)` up to second degree terms. — CO1 (07)
- **d)** A rectangular box open at the top is to have volume of 108 cubic ft. Find the dimensions of the box if its total surface area is minimum. — CO1 (07)

## UNIT — II

**Q3.**
- **a)** Write the steps involved in finding the orthogonal trajectories of the curve `f(x, y, c) = 0`. — CO2 (02)
- **b)** An object is heated to 300°F and allowed to cool in a room whose air temperature is 80°F. After 10 minutes the temperature of the object is 250°F. What will be its temperature after 20 minutes? — CO2 (04)
- **c)** Using Taylor's series method, find the particular solution of `dy/dx = 3eˣ + 2y`, `y(0) = 0` at `x = 0.2`, considering terms up to fourth degree. Compare the result with the exact solution. — CO2 (07)
- **d)** Solve the IVP `y′ = 0.25y² + x²`, `y(0) = −1` at `x = 0.2` taking `h = 0.2` using Runge-Kutta method of fourth order. — CO2 (07)

**Q4.**
- **a)** Write any two differences between analytical and numerical methods. — CO2 (02)
- **b)** A bungee jumper of mass 68.1 kg leaps from a stationary hot air balloon. Use `dv/dt = g − cv²/m` where `g = 9.8 m/s²`, `c = 0.25 kg/m` to compute velocity for the first three seconds of free fall by Euler's method in steps of 1 second. — CO2 (04)
- **c)** Solve the IVP `dy/dx = xy + x²eˣ − 2xeˣ`, `y(1) = 0` at `x = 1.2` taking step length 0.2, using Modified Euler's method. Carry out 2 iterations. — CO2 (07)
- **d)** Show that the family of curves `x²/(a²+λ) + y²/(b²+λ) = 1` is self-orthogonal, where λ is the parameter. — CO2 (07)

## UNIT — III

**Q5.**
- **a)** Write the steps involved in solving Cauchy's LDE. — CO3 (02)
- **b)** If `D = d/dx` and `X = X(x)`, prove that `[1/(D+a)] X = e^(−ax) ∫ X e^(ax) dx`. — CO3 (04)
- **c)** Solve `(x²D² + 4xD + 4)y = x² sin(2x)`  *(Cauchy form)*. — CO3 (07)
- **d)** Solve `y″ + 2y′ + 2y = e^(−x) sec³x` by the method of variation of parameters. — CO3 (07)

**Q6.**
- **a)** Define linear and non-linear differential equations with an example. — CO3 (02)
- **b)** If `k ≠ 0`, show that the general solution of `y⁗ − k⁴y = 0` can be expressed as `y = C₁cos kx + C₂ sin kx + C₃ cosh kx + C₄ sinh kx`. — CO3 (04)
- **c)** Solve `(3x+2)² y″ + 3(3x+2) y′ − 36y = 8x² + 4x + 1`  *(Legendre form)*. — CO3 (07)
- **d)** Solve `(D² − 2D)y = eˣ sin x`, `y(0) = 8`, `y′(0) = 1`  *(IVP)*. — CO3 (07)

## UNIT — IV

**Q7.**
- **a)** Obtain the expression for `∇²yₙ` in terms of y values. — CO4 (02)
- **b)** Construct the backward difference table representing the function `y = 2x² − x + cos 2` over the interval (2, 3) with step length `h = 0.2`, and hence write the value of `∇²y₃`. — CO4 (04)
- **c)** Use Simpson's 1/3rd rule to evaluate `∫₀¹ dx/(1+x²)` considering seven equidistant ordinates, and hence find an approximate value of π. — CO4 (07)
- **d)** Use an appropriate interpolation formula to find the radius of curvature at `x = 3.0` from the data: — CO4 (07)

  | x | 3 | 5 | 7 | 9 | 11 |
  |---|---|---|---|---|----|
  | y | 28.27 | 78.54 | 153.93 | 254.47 | 380.13 |

**Q8.**
- **a)** Given two points (x₀, y₀) and (x₁, y₁), write Lagrange's inverse interpolation formula. — CO4 (02)
- **b)** Evaluate `∫₀¹ eˣ dx` approximately in steps of 0.2 using the trapezoidal rule. — CO4 (04)
- **c)** Using Newton's divided difference formula, find an interpolating polynomial for the data and hence find `f(1)`. — CO4 (07)

  | x | −1 | 0 | 2 | 3 |
  |---|----|---|---|---|
  | f(x) | −8 | 3 | 1 | 12 |

- **d)** A survey conducted in a factory reveals the following. Estimate the probable number of persons in the income group 20 to 25. — CO4 (07)

  | Income per hour (Rs.) | <10 | 10–20 | 20–30 | 30–40 | 40–50 |
  |---|---|---|---|---|---|
  | No. of persons | 20 | 45 | 115 | 210 | 115 |

## UNIT — V

**Q9.**
- **a)** Define row echelon form of a matrix. — CO5 (02)
- **b)** Use Gauss-Seidel method to solve: `2x + 17y + 4z = 35`; `3x + y + 10z = 24`; `28x + 4y − z = 32`. Use (0, 0, 0) as the initial approximation, carry out 2 iterations. — CO5 (04)
- **c)** If the characteristic equation of `A = [[3, −2, 4], [−2, 6, 2], [4, 2, 3]]` is `(λ − 7)²(λ + 2) = 0`, find its non-singular modal matrix. — CO5 (07)
- **d)** Write the system of linear equations from the given electrical network. Use Gauss-elimination method to find currents in various branches. *(figure in paper)* — CO5 (07)

**Q10.**
- **a)** Explain the geometrical interpretation of infinitely many solutions for the system `2x + y = 3` and `4x + 2y = 6`. — CO5 (02)
- **b)** Use Rayleigh's power method to find the largest eigenvalue and corresponding eigenvector of `A = [[2, −2, 1], [1, 3, −1], [−1, 2, 2]]`, taking `[1, 0, 0]ᵀ` as the initial approximation. Carry out two iterations. — CO5 (04)
- **c)** Find the conditions on `a, b, c` so that the system is solvable: `x + 2y − z = a`; `2x + y + z = b`; `x − y + 2z = c`. Find all possible solutions if `a = 1, b = −1, c = 2`. — CO5 (07)
- **d)** The rabbit population r and wolf population w are governed by `dr/dt = 4r − 2w`, `dw/dt = r + w`. If initially `r = 240` and `w = 300`, what are the populations at time t? — CO5 (07)
