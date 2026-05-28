# 🧪 A/B Testing & Regression Analysis for Landing Page Optimization

> Evaluating the impact of a redesigned landing page on conversion behavior using statistical hypothesis testing and logistic regression.

---

## 📌 Overview

A business introduced a redesigned landing page to improve customer conversion rates. This project conducts a full A/B experiment — from randomization validation to statistical testing and multivariate regression — to determine whether the redesign drives a meaningful, statistically significant uplift in conversions.

---

## 📊 Key Results

| Metric | Value |
|---|---|
| Conversion Uplift | +6.08 percentage points |
| Relative Uplift | 51.18% over control |
| Statistical Significance | α = 0.05 ✅ |
| Primary KPI | Conversion Rate |
| Secondary KPIs | Session Duration, Pages Visited, Purchase Amount |

---

## 🔬 Methodology

1. **Experiment Validation** — randomization check across device type, location, and age distribution
2. **EDA** — conversion rate, session duration, pages visited, purchase amount by group
3. **A/B Testing** — Z-test for proportions with confidence interval analysis
4. **Relative Uplift Analysis** — treatment vs control performance gap
5. **Logistic Regression** — multivariate model controlling for demographic and behavioral factors
6. **Device-Level Analysis** — conversion breakdown across device types

---

## 📈 Business Insight

> The treatment landing page **significantly outperformed** the control group.
> Logistic regression confirmed the redesigned page remained the **strongest predictor of conversion** even after controlling for age, location, and device type.

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Statsmodels](https://img.shields.io/badge/Statsmodels-4051B5?style=flat)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white)

---

## 📁 Project Structure

```
ab-testing-regression-analysis/
│
├── A_B_Testing_Regression_Analysis.ipynb   # Main analysis notebook
├── AB Testing Data.csv                      # Dataset
└── README.md
```
