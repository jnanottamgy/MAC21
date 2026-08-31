# MAC21 — Numerical Techniques and Differential Equations

Complete exam-prep workspace for **MAC21**, B.E. Semester II, Computer Science stream,
Ramaiah Institute of Technology (Autonomous, affiliated to VTU).

Built from **6 question papers**, the official **model question paper**, the **course handbook**
and the **session-wise portion sheet**. Every numerical answer in these documents was computed
and verified, not estimated.

---

## ▶ START HERE — pick by how much time you actually have

### ⏱ Under 1 hour
**[`MAC21-Last-Minute-Predictions.pdf`](MAC21-Last-Minute-Predictions.pdf)** — 3 pages. Nothing else.

Read in this order:
1. The **2-mark bank** at the foot of each unit table — 10 marks, pure recall, cheapest in the paper.
2. Every row tagged **🟢 EXACT** — same question, same numbers, answer given. Memorise those.
3. The **in-the-hall** box on the last page.

Skip the ⬛ TOPIC rows if you are truly out of time; you cannot learn a method in 40 minutes.

### ⏱ 2 – 4 hours
Last-Minute sheet **plus** these sections of
**[`MAC21-All-7-Markers-Solved.pdf`](MAC21-All-7-Markers-Solved.pdf)**:

| Do | Why |
|---|---|
| §15 CF + P.I. | Everything in Unit III rests on it |
| §16 Cauchy · §18 Variation of parameters | Unit III Q5 = 18 of 20 marks |
| §31 Gauss-Seidel · §32 Eigenvalues | Unit V is the smallest, most predictable unit |
| §22 Divided difference · §23 Missing terms | Unit IV's two most repeated items |

That is roughly 45 marks of the paper for four hours of work.

### ⏱ About 2 days (~18 hours) — the realistic case
Two plans. **Pick one.**

| Plan | Use when | Target |
|---|---|---|
| **[`MAC21-48-Hour-Study-Plan.pdf`](MAC21-48-Hour-Study-Plan.pdf)** | You want a safe pass with least effort | **65 marks.** Answers `a + b + ONE` 7-marker per unit — you deliberately skip the second 7-marker in every question |
| **[`MAC21-Full-Coverage-Plan.pdf`](MAC21-Full-Coverage-Plan.pdf)** | You want no question to be able to surprise you | **All 35 seven-marker types**, both options in every unit. Depth is tiered: 3 reps on the 11 most frequent, 1 rep on the rest |

**Which one?** The 48-hour plan is *safer per hour spent*; the full-coverage plan is *safer against a
reshuffled paper*. If you are anxious about the paper being unusual, take full coverage. If you are
short on hours, take the 48-hour plan.

### ⏱ A week or more — learning it properly
1. [`syllabus/MAC21-portion.md`](syllabus/MAC21-portion.md) — what is actually examinable
2. [`MAC21-All-7-Markers-Solved.pdf`](MAC21-All-7-Markers-Solved.pdf) — work all 35 types end to end
3. [`pyq/MODEL-PAPER-I-MAC21.md`](pyq/MODEL-PAPER-I-MAC21.md) — sit it timed, closed book
4. Both real MAC21 papers ([2023](pyq/2023-SEP-OCT-MAC21.md), [2024](pyq/2024-JUL-AUG-MAC21.md)) — timed
5. [`MAC21-Prediction-Sheet.pdf`](MAC21-Prediction-Sheet.pdf) — the full 8-page analysis, to prioritise revision

---

## Exam format (identical in every paper checked)

```
100 marks · 3 hours · 5 units
Unit I → Q1 or Q2    Unit II → Q3 or Q4    Unit III → Q5 or Q6
Unit IV → Q7 or Q8   Unit V  → Q9 or Q10

Every question:  a) 02 + b) 04 + c) 07 + d) 07 = 20 marks
Answer ONE full question from each unit — internal choice, always 2 options.
```

**Part (a) is always pure recall** — a definition, a formula to state, or "write the steps involved in…".
Never a calculation, in any paper checked. That is 10 marks of memorisation, and you pick the easier of two.

---

## The portion this is built on

Transcribed from the official session-wise lesson plan. **28 sessions, 5 units, 1 hour each.**
Full version with tables: [`syllabus/MAC21-portion.md`](syllabus/MAC21-portion.md)

**Unit I — Series Expansion of Functions & their Applications** *(sessions 1–6)*
1. Taylor's and Maclaurin's series expansion of one variable
2. Newton-Raphson method — derivation and geometrical interpretation. Problems
3. Taylor's and Maclaurin's series expansion of two variables
4. Solution of a system of nonlinear equations using Newton-Raphson
5. Maxima and minima of functions of two variables
6. Lagrange's method of undetermined multipliers

**Unit II — First Order and First Degree DEs & Numerical Solution of First Order ODE** *(7–11)*
7. Applications of ODEs — LR and RC circuits, Newton's law of cooling
8. Orthogonal trajectories
9. Numerical solution of ODEs by Taylor's series method
10. Euler's and modified Euler's method
11. Runge-Kutta method of fourth order

**Unit III — Linear Differential Equations of Higher Order** *(12–17)*
12. LDE with constant coefficients; homogeneous solutions
13. Particular Integral for standard cases
14. Problems continued on L13
15. Cauchy's and Legendre's linear differential equations
16. Solution of initial and boundary value problems
17. Method of variation of parameters

**Unit IV — Interpolation, Numerical Differentiation & Numerical Integration** *(18–23)*
18. Finite differences
19. Newton-Gregory forward and backward difference interpolation
20. Lagrange's interpolation; Newton's divided difference interpolation
21. Numerical differentiation
22. Newton-Cotes quadrature formula; Trapezoidal rule
23. Simpson's 1/3rd and 3/8th rule

**Unit V — Linear Algebra** *(24–28)*
24. Elementary transformations, echelon form & rank; consistency of linear systems
25. Gauss elimination and Gauss-Seidel methods
26. Eigenvalues and eigenvectors of a matrix
27. Diagonalization of square matrices; Rayleigh's power method
28. Solution of a system of ODEs using the matrix method

---

## 🚨 Scheme warning — read before using the 2026 paper

The June/July 2026 paper is **`25MAC21` "Numerical Methods"**, a *different scheme* from your
**`MAC21` "Numerical Techniques and Differential Equations"**.

- Its **Unit II is entirely Multiple Integrals** — not in your syllabus at all
- It adds Regula-Falsi, LU decomposition, Weddle's rule — **not yours**
- It **drops** Cauchy, Legendre, variation of parameters, Lagrange multipliers, maxima–minima,
  and the **whole linear algebra unit** — all of which **are** yours

Roughly 70% of it is usable practice. **Do not revise from it alone** — you would walk in having
skipped ~35 marks of your own syllabus. Full delta: [`pyq/SYLLABUS-CHANGE-2025.md`](pyq/SYLLABUS-CHANGE-2025.md)

Two of the papers are also **sister papers** for other branches — MAM21 (MECH/IEM/CHE) and MAE21
(ECE/EEE). Their early units overlap well; their later units are Laplace transforms, Beta/Gamma
functions and PDEs, none of which are in MAC21. Every off-syllabus section is flagged in place.

---

## Everything in this repo

### Deliverables (PDF)
| File | Pages | What it is |
|---|---|---|
| [`MAC21-Last-Minute-Predictions.pdf`](MAC21-Last-Minute-Predictions.pdf) | 3 | Highest-probability questions per unit, with section slot, repeat count, and the answer where it is an exact repeat |
| [`MAC21-Prediction-Sheet.pdf`](MAC21-Prediction-Sheet.pdf) | 8 | Full analysis — the model-paper leak, repeats ranked, unit-by-unit breakdown, score projection |
| [`MAC21-All-7-Markers-Solved.pdf`](MAC21-All-7-Markers-Solved.pdf) | 15 | All 35 seven-marker types, both options in every unit. Method + worked example + trap |
| [`MAC21-48-Hour-Study-Plan.pdf`](MAC21-48-Hour-Study-Plan.pdf) | 4 | Targeted plan for a 65-mark floor |
| [`MAC21-Full-Coverage-Plan.pdf`](MAC21-Full-Coverage-Plan.pdf) | 4 | Every topic, depth-tiered |

### Analysis (Markdown)
- [`pyq/PATTERN-ANALYSIS.md`](pyq/PATTERN-ANALYSIS.md) — repeat questions ranked, the fixed 2/4/7/7 format, what has never been asked
- [`pyq/POSITIONAL-MAP.md`](pyq/POSITIONAL-MAP.md) — which question sits in which slot, across all papers; how to make the a/b choice
- [`pyq/SYLLABUS-CHANGE-2025.md`](pyq/SYLLABUS-CHANGE-2025.md) — MAC21 vs 25MAC21
- [`syllabus/MAC21-analysis.md`](syllabus/MAC21-analysis.md) — weightage, dependency chains, topic classification

### Papers
- ⭐ [`pyq/MODEL-PAPER-I-MAC21.md`](pyq/MODEL-PAPER-I-MAC21.md) — the departmental model paper
- [`pyq/2023-SEP-OCT-MAC21.md`](pyq/2023-SEP-OCT-MAC21.md) · [`pyq/2024-JUL-AUG-MAC21.md`](pyq/2024-JUL-AUG-MAC21.md) — exact match
- [`pyq/2026-JUN-JUL-25MAC21.md`](pyq/2026-JUN-JUL-25MAC21.md) — new scheme, partial
- [`pyq/sister-papers/`](pyq/sister-papers/) — MAM21 and MAE21, off-syllabus units flagged
- [`pyq/raw/`](pyq/raw/) — original PDFs

---

## The single most useful finding

The departmental model paper carries the printed disclaimer *"Students should not be under the
impression that questions from model question paper will appear in SEE."*

Cross-checked against four real papers, **17 of its 40 parts have appeared in actual exams**,
many word-for-word, and several in a paper written under a *different syllabus scheme*.
If you work one document end to end, work the model paper.

---

## How to read the repeat counts

Two different things, and they are tagged differently throughout:

- **EXACT n×** — the same question with the **same numbers** appeared n times. The answer given is
  the real answer; memorise it.
- **TOPIC n×** — the same **technique** appeared n times with **different numbers each time**. Any
  answer shown is one worked example, not something to reproduce. Learn the method.

Counts are always out of the papers that carry that unit: **Units I–III → 6 papers · Unit IV → 5 ·
Unit V → 3** (the 2026 scheme deleted Unit V, so 3×/3 there is a clean sweep, not a weak signal).

**These are inferences from observed frequency and slot position — not guarantees.** The paper setter
is free to ignore every one of them. Read both options before committing in the hall.
