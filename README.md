# Python_TMLE_AIPW

This repository contains a lightweight and bias-aware implementation of **Average Treatment Effect (ATE)** estimation using two doubly robust methods: **Augmented Inverse Probability Weighting (AIPW)** and **Targeted Maximum Likelihood Estimation (TMLE)**.

Designed for clarity and reproducibility, this implementation uses only core scientific Python packages: `pandas`, `numpy`, and `statsmodels`. It is especially suitable for researchers and practitioners who want interpretable and customizable code without relying on black-box machine learning libraries.

## Highlights

- ✅ Implements **AIPW** and **TMLE** with a focus on **bias correction**
- ✅ Supports both **continuous** and **bounded probability outcomes**
- ✅ Minimal dependencies (`pandas`, `numpy`, `statsmodels`)
- ✅ Clear and transparent logic for each step of the ATE pipeline

## Applications

- Causal inference in observational studies  
- Policy evaluation and impact analysis  
- Education, public health, and social sciences research  

## File Overview

- `Python_TMLE_AIPW.py`: Main script that prepares data, estimates nuisance functions, and computes ATE using both AIPW and TMLE.

## Requirements

- Python 3.8+
- `pandas`
- `numpy`
- `statsmodels`
