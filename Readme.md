# A/B Testing & Regression Analysis for Landing Page Optimization

## Project Overview

This project evaluates whether a redesigned landing page significantly improves customer conversion performance compared to an existing version using **A/B testing**, **statistical hypothesis testing**, and **logistic regression**.

The analysis combines business experimentation with statistical validation to determine whether observed improvements are statistically meaningful and commercially valuable.

---

## Business Problem

A business introduced a redesigned landing page to improve customer conversion rates.

An A/B experiment was conducted:

- **Control Group** → Existing landing page  
- **Treatment Group** → Redesigned landing page

The objective was to determine whether the redesigned experience significantly improves conversion performance.

---

## Project Objective

The primary goal was to answer:

> **Does the redesigned landing page significantly improve conversion rate?**

Key evaluation areas:

- Conversion rate performance
- Statistical significance
- Practical business impact
- User behavior patterns
- Conversion drivers using logistic regression

---

## Dataset Overview

The dataset contains simulated user-level experimentation data including:

- User ID
- Experiment Group (Control/Treatment)
- Landing Page
- Conversion Status
- Age
- Gender
- Session Duration
- Pages Visited
- Device Type
- Geographic Location
- Purchase Amount

---

## Methodology

The project followed a structured experimentation workflow:

1. **Experiment Validation**
   - Randomization checks
   - Group balance verification

2. **Exploratory Data Analysis (EDA)**
   - Conversion rate comparison
   - Relative uplift analysis
   - Device and behavioral segmentation

3. **Statistical A/B Testing**
   - Hypothesis testing
   - Two-Proportion Z-Test
   - Confidence interval estimation
   - Practical significance evaluation

4. **Regression Analysis**
   - Logistic regression
   - Feature significance testing
   - Odds ratio interpretation

---

## Key Findings

### Conversion Performance
- Conversion rate improved from **11.87% → 17.95%**
- Treatment generated a **51.18% relative uplift**

### Statistical Results
- **Z-statistic:** 46.28  
- **P-value:** < 0.001  
- Improvement was **statistically significant**

### Confidence Interval
- Estimated uplift range: **5.82% – 6.33%**

### Logistic Regression Insights
- Treatment remained the **strongest predictor of conversion**
- Users exposed to the treatment page were **1.62× more likely to convert**
- Mobile users showed slightly lower conversion tendency
- Most demographic and geographic variables showed minimal influence

---

## Business Recommendations

- Roll out the redesigned landing page to a broader audience
- Optimize the **mobile user experience**
- Continue A/B testing for CTA placement, layout, and personalization
- Monitor post-rollout conversion performance

---

## Tech Stack

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **SciPy**
- **Statsmodels**
- **Scikit-learn**
- **Jupyter Notebook**

---

## Project Files

- **Notebook:** Full A/B testing and regression workflow with statistical validation and business insights.

---

## Key Takeaways

This project demonstrates practical application of:

- A/B Testing
- Hypothesis Testing
- Statistical Significance
- Confidence Intervals
- Logistic Regression
- Odds Ratio Interpretation
- Business Impact Analysis
