Math 285 - Bayesian Statistics
================

## Fall 2019

Instructor: Adam Loy

Location: CMC 319

Time: 4a

Office hours: Mon 2-3, Tue 2-3, Wed 9:30-10:30, Fri 9:30-10:30, and by
appointment

-----

# Materials

Jump to: [Daily schedule](#daily-schedule)

## [Syllabus](syllabus_math315_f2019.pdf)

## Readings

The required textbook is *Bayesian Statistical Methods* by Reich and
Ghosh (2019, CRC Press) both readings and problems will be assigned from
this text, so please obtain a copy.

I will assign supplemental readings throughout the term and will post
links to them on this page.

One major supplement to the course will be the textbook *Bayesian Ideas
and Data Analysis*, which is freely available to Carls on [ProQuest
Ebook
Central](https://ebookcentral.proquest.com/lib/carleton-ebooks/detail.action?docID=1648259)

## R/RStudio

We will use R/RStudio as our computational engine. Please install the
current version of R and RStudio at the beginning of the term if you
plan to use a local version.

  - Download R: <https://cran.r-project.org/>

  - Download RStudio desktop:
    <https://www.rstudio.com/products/rstudio/download/#download>

The mirage server (<https://mirage.mathcs.carleton.edu>) is also
available for your use, *but can only be accessesed on campus of via a
VPN*.

## JAGS

We will use JAGS (Just Another Gibbs Sampler) “automate” some of the
posterior sampling via MCMC this term. *Please install JAGS using prior
to installing the R packages listed below.*

Link to the latest version:
<https://sourceforge.net/projects/mcmc-jags/files/latest/download>

## R packages

We will use numerous R packages throughout this course. They are all
installed on the mirage R Studio server. If you are working on a local
install, then please run the code chunk below to install all of the
packages. I recommend doing this at the beginning of the course to avoid
last minute installation issues preventing you from completing
assignments.

    install.packages(c("mvtnorm", "loo", "coda", "rjags"), dependencies = TRUE)

## Homework and solutions

I will post homework assignments and their solutions here. Check the
folders at the top

## Class materials

Links to any slides and handouts are in the calendar section below.
Check the folders above for the .Rmd files containing the R code used to
generate slides, etc.

-----

# Calendar

## Important dates

Homework

  - Individual assignments will be due most Tuesdays and Fridays by 4:00
    p.m.

  - Team assignments will be assigned roughly every two weeks.

Exam 1: Wednesday, October 16

Exam 2: Wednesday, November 13

Project

  - Team assignments: 4 November by 4:00 p.m.

  - Proposal and data: 11 November by 4:00 p.m.

  - Final submission: 25 November by 3:00 p.m.

## Daily schedule

BSM = *Bayesian Statistical Methods*

BIDA = *Bayesian Ideas and Data
Analysis*

| Date   | Reading                                                                                                                | Topic                                                             | Materials                                                                      |
| ------ | ---------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------- | ------------------------------------------------------------------------------ |
| 16-Sep | BSM 1.1-1.2; <br> [BIDA 2.1](https://ebookcentral.proquest.com/lib/carleton-ebooks/reader.action?docID=1648259&ppg=32) | Welcome and probability review                                    | [Slides](https://aloy.github.io/math315-fall2019/01-probability-review.html#1) |
| 18-Sep | BSM 1.3; <br> [BIDA 2.2-2.3](https://ebookcentral.proquest.com/lib/carleton-ebooks/reader.action?docID=1648259&ppg=37) | Comparing paradigms, updating prior belief, discrete priors       | [Slides](https://aloy.github.io/math315-fall2019/02-bayesian-updating.html#1)  |
| 20-Sep | 1.4.1-1.4.2; <br> [BIDA 2.4](https://ebookcentral.proquest.com/lib/carleton-ebooks/reader.action?docID=1648259&ppg=49) | Continuous priors, posterior analysis                             | [Slides](https://aloy.github.io/math315-fall2019/02-posterior-analysis.html#1) |
|        |                                                                                                                        |                                                                   |                                                                                |
| 23-Sep | BSM 1.5; <br> [BIDA 3.1](https://ebookcentral.proquest.com/lib/carleton-ebooks/reader.action?docID=1648259&ppg=56)     | Monte Carlo simulation, grid approximation, univariate prediction |                                                                                |
| 25-Sep | BSM 1.4.3                                                                                                              | Basic multivariate inference                                      |                                                                                |
| 27-Sep |                                                                                                                        | Selecting priors                                                  |                                                                                |

<!--  | | | -->

<!-- 30-Sep | | Selecting priors  | -->
