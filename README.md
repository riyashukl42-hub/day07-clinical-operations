# Day 07 — Clinical Operations Dashboard

## Problem statement
Which departments and hospitals are driving the longest patient stays,
and what does the admission type mix tell us about operational pressure?

## Dataset
- Healthcare Analytics II (Kaggle)
- 318,000+ patient records · 31 hospitals · 18 columns

## Key findings
- Severity of illness correctly predicts LoS — Extreme cases stay 3x longer than Minor
- Significant variation in LoS across hospitals — top outliers warrant clinical audit
- Emergency admissions have higher and more variable LoS than elective

## Operational recommendations
1. Target highest LoS departments for discharge planning improvement
2. Increase elective capacity to reduce emergency bed pressure
3. Audit top 3 outlier hospitals for LoS reduction opportunities

## Output
Interactive HTML dashboard — open charts/clinical_operations_dashboard.html in any browser

## Relevant to
NHS data analyst · Optum · Health Catalyst · Healthcare operations roles

## Tools
Python · Pandas · Plotly · VS Code
