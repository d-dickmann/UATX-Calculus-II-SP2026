# Calculus II (Spring 2026)

Welcome to the Spring 2026 edition of Calculus II. This repository is the central course webpage for materials, announcements, assignments, and schedule updates.

## Course Information

**Course:** STM 1002 - Calculus II  
**Term:** Spring 2026  
**Instructor:** Prof. Dorothy Dickmann  
**Email:** [ddickmann@uaustin.org](mailto:ddickmann@uaustin.org)  
**Meeting Schedule:** MWF 11:30 AM - 12:45 PM, Scarbrough Room 311  
**Office Hours:** W 9:30 AM - 11:30 AM, Second Floor, otherwise by appointment. Email me for second floor access as needed.

## Quick Links

- [Syllabus](syllabus/)
- [Schedule](#course-cadence)
- [Course Materials](#course-materials)

## Course Description

This course is the second in a two-course sequence and exposes the student to mathematical ideas of accumulation, integration, and basic dynamics.

Calculus II extends ideas from differential calculus into integration, accumulation, series, and basic dynamics. The course emphasizes conceptual understanding, careful problem solving, and communication of mathematical reasoning.

## Learning Objectives

By the end of the term, students will be able to:

- Interpret the definite integral as net change from a rate and use the Fundamental Theorem of Calculus to evaluate definite integrals.
- Find antiderivatives and apply integrals to displacement, net change, and area.
- Interpret and solve separable differential equations; use slope fields and identify fixed points and stability.

## Materials and Software

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

## Course Cadence

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

## Evaluation

- Homework: 20%
- Quizzes: 30%
- Final Exam: 50%

## Weekly Schedule (Living Outline)

The schedule below is tentative and subject to change throughout the term. Materials, assignments, and other resources are updated in the [Course Materials](#course-materials) section.

| Block | Week | Topics | Readings | Due Dates |
| --- | --- | --- | --- | --- |
| [1](#block-1--weeks-1--2) | 1 (Mar 30-Apr 5) | Accumulation, definite integral, FTC foundations | TBD | - |
| 1 | 2 (Apr 6-12) | FTC and antiderivative toolkit | TBD | HW1 + Quiz 1 (Fri Apr 10) |
| 2 | 3 (Apr 13-19) | Integration techniques (`u`-sub, integration by parts) | TBD | - |
| 2 | 4 (Apr 20-26) | Applications of integration; geometric series and present value | TBD | HW2 + Quiz 2 (Fri Apr 24) |
| 3 | 5 (Apr 27-May 3) | Continuous probability, Taylor series, and log-normal expectation | TBD | - |
| 3 | 6 (May 4-10) | Capstone: Black-Scholes big picture, interpretation, and computation | TBD | HW3 + Quiz 3 (Fri May 8) |
| 4 | 7 (May 11-17) | Differential Equations and Dynamics | TBD | - |
| 4 | 8 (May 18-24) | Differential Equations and Dynamics | TBD | HW4 + Quiz 4 (Fri May 22) |
| 5 | 9 (May 25-31) | Differential Equations and Dynamics| TBD | - |
| 5 | 10 (Jun 1-5) | Differential Equations and Dynamics | TBD | HW5 + Quiz 5 (Fri Jun 5) |
| - | 11 | Final exam week | TBD | Final exam |

## Course Materials

*This section will be updated with detailed course materials throughout the term*

### Block 1 — Weeks 1 & 2

**Slides**
- L02 — [What's Calculus II good for? (& intro to definite integrals)](slides/L02_Motivation_Riemann_slides.pdf)

**Practice Problems**
*These problems are not required, but are available for your practice*
- [Block 1 Practice Problems](/resources/practice-problems/PracticeProblems_Block1.pdf)
- [Block 1 Practice Problems Solutions](/resources/practice-problems/PracticeProblems_Block1_Solutions.pdf)

[**Homework 1:**](/assignments/HW1_Accumulation_FTC.pdf) Due Friday April 10. Hard copy turned in at the start of class (or scan & upload to Populi).

## Repository Structure

- `assignments/` - homework and project PDFs
- `code/` - scripts, notebooks, demos
- `data/` - datasets used in class
- `lectures/` - lecture notes and handouts
- `resources/` - supplemental references
- `slides/` - lecture slide decks
- `syllabus/` - official course policy documents
