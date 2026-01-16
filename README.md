# DIS08-GroupIlias-Karim-Liam-Sara
Gruppen Repository für DIS08 Datenmodellierung

# Data Modeling Project – World Cup Success & Population  
**Winter Semester 2025/26**

This repository documents our **Data Modeling course project**.  
The goal of the project is to analyze whether countries with larger populations tend to be more successful at FIFA World Cups, using transparent data processing and basic statistical methods.

The repository is structured along the **three milestones** defined in the course.

---

## Project Overview

The project follows a clear analytical pipeline:

1. Definition of research questions and hypothesis  
2. Data collection and data pipeline construction  
3. Statistical analysis and interpretation  

All steps are documented in this repository to ensure transparency and reproducibility.

---

## Milestone 1 – Research Design & Data Selection

In **Milestone 1**, we define the conceptual foundation of the project.

Main components:
- Motivation of the research topic
- Formulation of three guiding **research questions**
- Definition of one **testable statistical hypothesis**
- Selection of suitable datasets:
  - FIFA World Cup results
  - World Bank population data
- Discussion of data scope, limitations, and licensing

This milestone clarifies **what we want to analyze and why**.

---

## Milestone 2 – Data Collection & Data Pipeline

**Milestone 2** focuses on building a structured and transparent data pipeline.

Main components:
- Loading raw CSV datasets
- Harmonizing country identifiers
- Matching population data to the corresponding World Cup years
- Definition of the observation unit as **(country, year)**
- Merging all relevant information into a single dataset

The result of this milestone is an **augmented dataset** that combines:
- World Cup performance
- Population size per country and year

This dataset serves as the basis for all further analyses.

---

## Milestone 3 – Analysis & Statistical Modeling

In **Milestone 3**, we perform the statistical analysis.

Main components:
- **Operationalization of variables**
  - Success: binary indicator (podium vs. non-podium)
  - Population: logarithmized population size (log10)
- Group comparison between:
  - Countries with podium finishes
  - Countries without podium finishes
- Application of a **Welch t-test** to account for unequal group sizes and variances
- Calculation of an **effect size (Cohen’s d)** to assess practical relevance
- Additional exploratory analysis using a graded success measure and correlation

---

## Results – High-Level Summary

The main numerical results of the analysis are:

- **Observation counts**
  - Podium observations: *n = 39*
  - Non-podium observations: *n = 3003*

- **Mean population size (log10 scale)**
  - Podium countries: *≈ 7.68*
  - Non-podium countries: *≈ 6.25*

- **Group comparison (Welch t-test)**
  - *t ≈ 22.9*
  - *p ≈ 7.4 × 10⁻²⁸*

- **Effect size**
  - *Cohen’s d ≈ 1.22* (large effect)

- **Supplementary analysis**
  - Correlation between population size and graded success: *r ≈ 0.13* (weak positive association)

Overall, the results indicate a **strong statistical association** between population size and World Cup success, while also showing that population alone explains only a limited share of overall performance.

---

## Interpretation & Limitations

Important points for interpretation:
- Population size appears to be a relevant factor, but **not a sufficient explanation** for World Cup success.
- The analysis is limited to the **World Cup context**; countries without regular participation are not included.
- Other potentially important factors (e.g. economic resources, football culture, infrastructure, talent development) are not modeled.

---

## Tools & Technologies

The project was implemented using:
- Python
- Jupyter Notebooks
- Git & GitHub for version control and documentation

---

## Conclusion

This repository provides a complete overview of our Data Modeling project, from research design and data processing to statistical analysis and interpretation.  
The milestone-based structure reflects the course design and supports clear communication of both methodology and results.

