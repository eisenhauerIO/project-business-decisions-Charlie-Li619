# Replication of Andrews et al. (2022)  
## The Returns to College Major Choice

---

## Overview

This project replicates key insights from:

Andrews, R. J., Imberman, S. A., Lovenheim, M. F., & Stange, K. M. (2022).  
*The Returns to College Major Choice: Average and Distributional Effects, Career Trajectories, and Earnings Variability.*  
NBER Working Paper No. 30331.

The original paper studies how earnings vary across college majors and over the career distribution.  
It shows that different majors are associated with large differences in labor market outcomes.

This replication project focuses on reproducing the main descriptive patterns and estimating simple regression models that relate college major choice to earnings outcomes.

---

## Data

The dataset contains information on labor market outcomes across **173 college majors**, including:

- median earnings  
- unemployment rates  
- employment levels  
- major categories  

Each observation represents an aggregated college major rather than an individual worker.

---

## Methodology

The analysis proceeds in four steps:

1. **Descriptive statistics**  
   Summary statistics of earnings and unemployment across majors.

2. **Earnings comparison across majors**  
   Ranking majors by median earnings and comparing average earnings across major categories.

3. **Distribution analysis**  
   Visualizing how earnings are distributed across different fields of study.

4. **Regression analysis**  
   Estimating a log earnings regression:

\[
\log(Median_i) = \alpha + \beta MajorCategory_i + \gamma UnemploymentRate_i + \epsilon_i
\]

This specification allows the coefficients to be interpreted approximately as percentage differences in earnings across majors.

---

## Key Findings

The results show clear differences in labor market outcomes across college majors.

- Engineering and computer-related majors have the highest earnings.
- Majors in arts and education tend to have lower median earnings.
- Majors with higher unemployment rates tend to have lower earnings.

These patterns suggest that labor market demand and skill specialization play an important role in shaping earnings differences across fields of study.

