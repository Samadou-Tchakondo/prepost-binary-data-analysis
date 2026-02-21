Transforming Pre–Post Binary Data into Analytical Evidence



Aim of the Project

This project demonstrates how binary pre–post assessment data can be transformed into reproducible and interpretable statistical evidence using R. The goal is to illustrate a structured workflow for analyzing training outcomes measured through correct/incorrect questionnaire responses.



Methods Used

The analysis follows a transparent and reproducible pipeline:

Construction of total and domain-level scores from binary items

Reliability assessment using Cronbach’s alpha

Distributional evaluation through graphical inspection

Normality testing using the Shapiro–Wilk test

Within-subject comparison using the Wilcoxon signed-rank test

Estimation of effect size to quantify magnitude of change



Why the Wilcoxon Signed-Rank Test?

Because the outcome variables are derived from summed binary items, the resulting scores are bounded and non-normally distributed.
The Wilcoxon signed-rank test provides an appropriate non-parametric alternative for evaluating paired differences without assuming normality.



Key Findings

Significant improvement observed between pre- and post-training scores (p < 0.001)

Median gain of approximately 2.5 points on the total scale

Large overall effect size (r ≈ 0.80) indicating substantial practical impact

Strongest improvements observed in Statistical Reasoning, followed by Reporting & Publishing



Reproducible Report

View the full analysis on RPubs:

https://rpubs.com/Samadou_Tchakondo/prepost-binary-data-analysis




Tools

R

R Markdown

psych package

Non-parametric statistical methods
