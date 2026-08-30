# ⚠️ MAC21 → 25MAC21 : the syllabus changed

The June/July 2026 paper is **25MAC21 "Numerical Methods"**, not
**MAC21 "Numerical Techniques and Differential Equations"**. Same institution, same
semester, same branches — different scheme. The unit structure was substantially rebuilt.

## Which one are you on?

**Your own documents both say MAC21 (old scheme):**
- Your portion sheet footer: *"MAC21 - Numerical Techniques and Differential Equations"*
- Your model paper header: *"Subject Code: MAC21 · Numerical Techniques and Differential Equations"*

They are self-consistent, so **this repo is built for MAC21 (old scheme)** unless you say
otherwise. The 2026 paper is stored as reference and cross-checked below.

## Unit-by-unit delta

| Unit | **MAC21** (your scheme) | **25MAC21** (2026 scheme) |
|---|---|---|
| **I** | Taylor/Maclaurin expansion (1 & 2 variables) · Newton-Raphson (single + system) · maxima–minima of two variables · Lagrange multipliers | Algebraic & transcendental equations · Newton-Raphson (single + system) · **Regula-Falsi** · Gauss-Seidel · **LU decomposition** |
| **II** | First-order ODE applications (LR/RC, Newton's cooling, orthogonal trajectories) · numerical ODE (Taylor, Euler, Mod. Euler, RK4) | 🆕 **Multiple Integrals** — double & triple integrals, change of order, polar & cylindrical coordinates, volume by triple integration |
| **III** | Higher-order LDE: constant coefficients, P.I. · **Cauchy's & Legendre's** · IVP/BVP · **variation of parameters** | Circuit DE · BVP · orthogonal trajectories · Newton's law of cooling · constant-coefficient LDE with P.I. |
| **IV** | Finite differences · Newton-Gregory fwd/bwd · Lagrange · divided difference · numerical differentiation · Newton-Cotes, Trapezoidal, Simpson's 1/3 & 3/8 | Finite differences · Lagrange (incl. **inverse**) · divided difference · numerical differentiation · max/min from tabulated data |
| **V** | **Linear Algebra** — elementary transformations, echelon & rank, consistency, Gauss elimination, Gauss-Seidel, eigenvalues & eigenvectors, diagonalization, Rayleigh's power method, system of ODEs by matrix method | Numerical integration (Trapezoidal, Simpson's 1/3 & 3/8, **Weddle's rule**) · numerical ODE (Taylor, Euler, Mod. Euler, RK4) |

## Dropped in the new scheme *(still yours if you're on MAC21)*

- Taylor's & Maclaurin's series expansion
- Maxima and minima of functions of two variables
- Lagrange's method of undetermined multipliers
- **Cauchy's and Legendre's linear differential equations**
- **Method of variation of parameters**
- **All of Unit V linear algebra** — eigenvalues, eigenvectors, diagonalization,
  Rayleigh's power method, system of ODEs by matrix method, rank & consistency

## Added in the new scheme *(NOT yours if you're on MAC21)*

- Regula-Falsi method
- LU decomposition
- **The entire multiple-integrals unit** — double/triple integrals, changing the order
  of integration, polar and cylindrical coordinates, volume by triple integration
- Weddle's rule

## If you are on MAC21 (assumed)

The 2026 paper is still **partially usable**, because the overlap is real:

| 2026 question | Usable for MAC21? |
|---|---|
| Unit I — Newton-Raphson (1c, 2c) | ✅ yes |
| Unit I — Regula-Falsi, LU decomposition (1d, 2a, 2d) | ❌ not in your syllabus |
| Unit I — Gauss-Seidel (2b) | ✅ yes — it's your **Unit V** |
| Unit II — all of it (multiple integrals) | ❌ **skip entirely** |
| Unit III — all of it (cooling, orthogonal trajectories, BVP, constant-coeff LDE) | ✅ yes — spans your Units II & III |
| Unit IV — all of it (interpolation, numerical differentiation) | ✅ yes — your Unit IV |
| Unit V — all of it (Simpson, Weddle, Taylor, Euler, Mod. Euler, RK4) | ✅ mostly — **except Weddle's rule**, which is not yours. The numerical-ODE parts are your Unit II. |

**Net:** roughly 70% of the 2026 paper is usable practice for you. Skip its Unit II
entirely, plus Regula-Falsi, LU decomposition and Weddle's rule.

**And note what it does NOT test that you must still know:** Lagrange multipliers,
maxima–minima, Taylor/Maclaurin expansion, Cauchy & Legendre, variation of parameters,
and the whole of linear algebra. Do not let the 2026 paper narrow your revision.
