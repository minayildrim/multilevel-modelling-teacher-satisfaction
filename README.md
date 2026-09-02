# Multilevel Modelling: Teacher Satisfaction

Multilevel modelling analysis of teacher job satisfaction and intention to leave the teaching profession using R.

## Overview

This project investigates factors associated with **teacher job satisfaction** and **intention to leave the teaching profession** using multilevel modelling in R.

Because teachers are nested within schools, observations are not independent. The analysis therefore accounts for the hierarchical structure of the data by modelling variation at both the **teacher level** and the **school level**.

## Research Questions

The analysis addresses the following questions:

1. Which individual-level characteristics are associated with teachers' job satisfaction?
2. Which individual- and school-level factors are associated with teachers' intention to leave the teaching profession?
3. How much of the variation in teacher outcomes can be attributed to differences between schools?

## Data Structure

The data have a hierarchical structure, with **teachers nested within schools**.

The analysis considers predictors at different levels of the hierarchy, allowing individual teacher characteristics and school-level characteristics to be examined simultaneously.

## Statistical Methods

The project applies multilevel modelling techniques, including:

* Multilevel linear modelling
* Multilevel logistic modelling
* Random-intercept models
* Fixed effects
* Random effects
* Intraclass correlation coefficient (ICC)
* Likelihood-ratio tests
* Model comparison
* Multicollinearity assessment
* Model diagnostics
* Interpretation of individual- and school-level effects

### Outcome Variables

Two outcomes are analyzed:

**Teacher job satisfaction**

A continuous outcome analyzed using a multilevel linear model.

**Intention to leave the teaching profession**

A binary outcome analyzed using a multilevel logistic model.

## Key Predictors

The models consider teacher-level and school-level characteristics, including variables related to:

* Teacher demographics
* Age
* Teaching experience
* Perceived stress
* School characteristics
* School-level disadvantage
* Perceived respect within the school environment

## Model Specification

The multilevel models account for the clustering of teachers within schools through school-level random effects.

The analysis first evaluates the random-effects structure and then assesses the contribution of fixed effects. Model comparison and statistical significance are used to develop the final model specifications.

## Main Findings

The results indicate that **perceived stress is an important predictor of both teacher job satisfaction and intention to leave the teaching profession**. Higher perceived stress is associated with lower job satisfaction and substantially higher odds of considering leaving the profession.

The analysis also shows that teacher- and school-level characteristics contribute to differences in the outcomes, highlighting the importance of accounting for the hierarchical structure of educational data.

## Software and Packages

The analysis was conducted using **R** and **R Markdown**.

Main R packages used include:

* `lme4`
* `lmerTest`
* `ggplot2`
* `performance`

## Repository Contents

```text
multilevel-modelling-teacher-satisfaction/
│
├── README.md
└── multilevel_modelling_teacher_satisfaction.Rmd
```

### `multilevel_modelling_teacher_satisfaction.Rmd`

Contains the complete analysis, including:

* Data preparation
* Exploratory analysis
* Model specification
* Random-effects analysis
* Fixed-effects analysis
* Model comparison
* Multicollinearity assessment
* Final models
* Model interpretation
* Statistical conclusions

## Reproducibility

The analysis is provided as an R Markdown document combining the statistical code, results, and interpretation.

The original dataset may not be included in this repository because of course, data-sharing, or redistribution restrictions.

## Academic Project

This project was completed as part of coursework in **Multilevel Modelling** and demonstrates the application of hierarchical statistical models to educational data.

## Author

**Mina Nur Yildirim**

M.Sc. Quantitative Data Science
University of Tübingen
