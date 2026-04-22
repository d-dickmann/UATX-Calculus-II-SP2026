# Calculus II (Spring 2026)

Welcome to the Spring 2026 edition of Calculus II. This repository is the central course webpage for materials, announcements, assignments, and schedule updates.

<details>
<summary><h2>Course Info</h2></summary>

### Course Information

**Course:** STM 1002 - Calculus II  
**Term:** Spring 2026  
**Instructor:** Prof. Dorothy Dickmann  
**Email:** [ddickmann@uaustin.org](mailto:ddickmann@uaustin.org)  
**Meeting Schedule:** MWF 11:30 AM - 12:45 PM, Scarbrough Room 311  
**Office Hours:** W 9:30 AM - 11:30 AM, Second Floor, otherwise by appointment. Email me for second floor access as needed.

### Quick Links

- [Syllabus](syllabus/)
- [Schedule](#weekly-schedule-living-outline)
- [Course Materials](#course-materials)

### Course Description

This course is the second in a two-course sequence and exposes the student to mathematical ideas of accumulation, integration, and basic dynamics.

Calculus II extends ideas from differential calculus into integration, accumulation, series, and basic dynamics. The course emphasizes conceptual understanding, careful problem solving, and communication of mathematical reasoning.

### Learning Objectives

By the end of the term, students will be able to:

- Interpret the definite integral as net change from a rate and use the Fundamental Theorem of Calculus to evaluate definite integrals.
- Find antiderivatives and apply integrals to displacement, net change, and area.
- Interpret and solve separable differential equations; use slope fields and identify fixed points and stability.

### Materials and Software

- Reading: *[Mosaic Calculus](https://www.mosaic-web.org/MOSAIC-Calculus/)* (MC) by Danny Kaplan
- Additional notes/readings will be posted in `resources/` as needed.
- Reading assignments will be communicated through the [Course Materials](#course-materials) section.

You will need R and RStudio (Desktop) on your computer to run example code and complete assignments. Install R first, then RStudio. Both are free and work across platforms.

Packages that may be useful in this course include:

- `mosaicCalc` (integration and antiderivative workflows)
- `pracma` (numerical calculus tools)
- `Ryacas` (symbolic manipulation, including series expansions)
- `deSolve` (differential equations and dynamical systems)

At points in the course, Python tools may also be useful (`sympy`, `scipy`). [Google Colab](https://colab.research.google.com/) is a good option if you do not have a local Python setup.

### Course Cadence

There are 5 homework assignments and 5 quizzes.

- Homeworks are due on Fridays at 11:30a (start of class) via Populi or hard copy to the professor.
- Quizzes occur on the same Fridays (Weeks 2, 4, 6, 8, 10).
- Quiz content is aligned with the homework, and we will mark up quizzes in class immediately after.
- The final exam is during the scheduled exam period (Week 11).

Homework and quiz dates:

- Homework 1 due Friday, Apr 10 at 11:30a; Quiz 1 on Friday, Apr 10
- Homework 2 due Friday, Apr 24 at 11:30a; Quiz 2 on Friday, Apr 24
- Homework 3 due Friday, May 8 at 11:30a; Quiz 3 on Friday, May 8
- Homework 4 due Friday, May 22 at 11:30a; Quiz 4 on Friday, May 22
- Homework 5 due Friday, Jun 5 at 11:30a; Quiz 5 on Friday, Jun 5

### Evaluation

- Homework: 20%
- Quizzes: 30%
- Final Exam: 50%

</details>

## Weekly Schedule (Living Outline)

The schedule below is tentative and subject to change throughout the term. Materials, assignments, and other resources are updated in the [Course Materials](#course-materials) section.

| Block | Week | Topics | Readings | Due Dates |
| --- | --- | --- | --- | --- |
| [1](#block-1--weeks-1--2) | 1 (Mar 30-Apr 5) | Accumulation, definite integral, FTC foundations | MC Ch 33 | - |
| [1](#block-1--weeks-1--2) | 2 (Apr 6-12) | FTC, antiderivative rules, applications | MC Ch 35 (§35.1–35.4) | HW1 + Quiz 1 (Fri Apr 10) |
| [2](#block-2--weeks-3--4) | 3 (Apr 13-19) | Integration techniques (u-sub, IBP), area & surplus | MC Ch 38 | - |
| [2](#block-2--weeks-3--4) | 4 (Apr 20-26) | Geometric series & present value; modeling lab day | MC Ch 51 | HW2 + Quiz 2 (Fri Apr 24) |
| 3 | 5 (Apr 27-May 3) | Continuous probability: PDF, CDF, expected value | TBD | - |
| 3 | 6 (May 4-10) | Taylor series: intuition, convergence, log-normal synthesis | MC Ch 27 | HW3 + Quiz 3 (Fri May 8) |
| 4 | 7 (May 11-17) | Black-Scholes capstone: derivation, computation, Greeks | TBD | - |
| 4 | 8 (May 18-24) | Black-Scholes capstone: model critique, case studies, synthesis | TBD | HW4 + Quiz 4 (Fri May 22) |
| 5 | 9 (May 25-31) | DEs essentials: intro, separable equations (Mon = Memorial Day) | TBD | - |
| 5 | 10 (Jun 1-5) | Fixed points, stability, course synthesis & review | TBD | HW5 + Quiz 5 (Fri Jun 5) |
| - | 11 | Final exam week | - | Final exam |

## Course Materials

*This section will be updated with detailed course materials throughout the term. Click on the triangle to expand each section.*

<details>
<summary><h3>Block 1 — Weeks 1 & 2</h3></summary>

**Slides**
- L02 — [What's Calculus II good for? (& intro to definite integrals)](slides/L02_Motivation_Riemann_slides.pdf)
- L03 — [The Fundamental Theorem of Calculus (with in-class notes)](slides/L03_FTC_slides_WithInClassNotes.pdf)
- L04 — [Discovering Antiderivative Rules and Properties of Definite Integrals](slides/L04_Antiderivatives_slides.pdf)
- L05 — [Graphical FTC, Fluency & Quiz Prep](slides/L05_FTC_Antiderivatives_Applications_slides.pdf)

**Code**
- [Python For Calculus](https://colab.research.google.com/drive/1zFdIMs7Ua1m6cDH2dXWS9vsKFfUHMuLz#scrollTo=RmHTRR28YpC4) — **Important:** When you open this notebook in Colab, go to *File → Save a copy in Drive* so your changes are saved to your own Google Drive. Otherwise, any edits you make will be lost when you close the tab.
- [Family of Antiderivatives (notebook)](code/L04_family_of_functions.ipynb) — visualizing why +C matters and why it cancels in definite integrals (if you don't have a Python environment set up on your machine, [open in Google Colab](https://colab.research.google.com/drive/123dxrwLCY2vs9gDIil2EMqSZp2oodxqk))

**Reading**
- [Ch 33: Change & Accumulation](https://www.mosaic-web.org/MOSAIC-Calculus/Accumulation/33-intro.html) — the accumulation concept, notation, and a useful dimensional-analysis trick for checking your work (§33.4)
- [Ch 35: Integration](https://www.mosaic-web.org/MOSAIC-Calculus/Accumulation/35-integration.html) (§35.1–35.4) — net change, definite vs indefinite integrals, why +C matters, properties of integrals
- *(optional)* [Ch 34: Totaling the Little Bits](https://mosaic-web.org/MOSAIC-Calculus/Accumulation/34-visualizing.html) — a visual approach to anti-differentiation complementary to Riemann sums

**Practice Problems**
*These problems are not required, but are available for your practice*
- [Block 1 Practice Problems](/resources/PracticeProblems_Block1.pdf)
- [Block 1 Practice Problems Solutions](/resources/PracticeProblems_Block1_Solutions.pdf)

**Reference Sheet**
- [Block 1 Reference Sheet](/resources/Block1_ReferenceSheet.pdf) — key formulas and rules from Block 1 (antiderivative rules)

[**Homework 1:**](/assignments/HW1_Accumulation_FTC.pdf) Due Friday April 10. Hard copy turned in at the start of class (or scan & upload to Populi).

**Quiz 1** — Friday, April 10 (50 minutes)
- The quiz is a combination of multiple-choice/true-false and free-response problems.
- You have 50 minutes; we will debrief solutions together in the remaining 15 minutes of class.
- No notes or reference sheets; you may use a calculator for arithmetic.
- Topics covered:
  - Riemann sums: computing left/right sums, reasoning about overestimates vs. underestimates
  - Fundamental Theorem of Calculus
  - Antiderivative rules: power rule, 1/x, exponentials, trig, constant multiples, sums
  - Indefinite vs. definite integrals and the role of +C
  - Properties of definite integrals: additivity, reversing bounds, even/odd symmetry, comparison
  - Graphical FTC: reading properties of F from the graph of f
  - General application of integrals (accumulation of rate of change)

</details>

<details open>
<summary><h3>Block 2 — Weeks 3 & 4</h3></summary>

**Slides**
- L06 — [u-Substitution: Motivation & Method](slides/L06_USub_Intro_slides.pdf)
- L06b — [u-Substitution Applications](slides/L06b_USub_Applications_slides.pdf)
- L07 — [Integration by Parts](slides/L07_IBP_slides.pdf)
- L08 — [Area Between Curves & Consumer Surplus](slides/L08_Area_Surplus_slides.pdf)
- L09 — [Geometric Series & Present Value](slides/L09_Series_PV_slides.pdf)

**Code**
- [L10 Catalog Sale Modeling Notebook (Colab)](https://colab.research.google.com/drive/1HOAs2W4kXpeuNW7oKrXVL7lJXciEkPSE) — present/future value of a music catalog royalty stream. **Important:** Go to *File → Save a copy in Drive* before editing, otherwise your changes will be lost.
- [L10 Vancomycin Dosing Notebook (Colab)](https://colab.research.google.com/drive/1xp4hoOA-DrJeXEybHaw3kbpYse0gbjtN) — AUC and steady-state trough via geometric series. **Important:** Go to *File → Save a copy in Drive* before editing, otherwise your changes will be lost.

**L10 Lab Packet**
- [L10 Lab Packet Solutions (with explanations)](/resources/L10_Lab_Packet_Solutions.pdf) — full worked solutions for the Wednesday 4/22 lab packet (Dylan's catalog + vancomycin dosing), with commentary on each step.

**Supplementary Notes**
- [How does the continuous discount rate connect to the discrete discount rate?](/resources/L09_L10_DiscreteToContinuousDiscountRate.pdf) — companion notes to L09/L10 walking through the bridge from discrete discounting (`(1+r)^-t`) to continuous discounting (the `e^{-rt}` factor).

**Reading**
- [Ch 38: Symbolic Anti-differentiation](https://www.mosaic-web.org/MOSAIC-Calculus/Accumulation/38-symbolic.html) — u-substitution, integration by parts, and limits of symbolic methods.
- [Ch 51: Present and Future Value](https://mosaic-web.org/MOSAIC-Calculus/Manifestations/51-future-value.html) — discounting, net present value, and exponential logic.
- [Ch 27: Polynomials for Approximating Functions](https://mosaic-web.org/MOSAIC-Calculus/Differentiation/27-taylor.html) — Taylor polynomials and local approximation.
- *(optional)* [Ch 37: Integrals Step-by-Step (Euler Method)](https://mosaic-web.org/MOSAIC-Calculus/Accumulation/37-euler.html) — numerical integration (Euler method).

**Practice Problems**
*These problems are not required, but are available for your practice*
- [Block 2 Practice Problems](/resources/PracticeProblems_Block2.pdf)
- [Block 2 Practice Problems Solutions](/resources/PracticeProblems_Block2_Solutions.pdf)

[**Homework 2:**](/assignments/HW2_Integration_Applications.pdf) Due Friday April 24. Hard copy at the start of class.

</details>

## Repository Structure

- `assignments/` - homework and project PDFs
- `code/` - scripts, notebooks, demos
- `data/` - datasets used in class
- `resources/` - supplemental references
- `slides/` - lecture slide decks
- `syllabus/` - official course policy documents
