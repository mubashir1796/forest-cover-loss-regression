#  Predicting Forest Cover Loss Using Multiple Linear Regression

## Overview
This project applies **Multiple Linear Regression (MLR)** to predict **global forest cover loss**
using environmental and socio-economic indicators.  
The final model achieves an **R² score of 0.91**, demonstrating strong explanatory and predictive performance.

The project also focuses on **interpretability**, highlighting which factors are most influential in
driving deforestation.

---

## Problem Statement
Forest cover loss is a critical environmental and development challenge. Understanding how measurable
factors such as urbanization, policy strength, and climate indicators relate to deforestation can
support better policy discussions and sustainable planning.

This project explores whether forest cover loss can be accurately predicted using multiple linear
regression and identifies key contributing variables.

---

## Dataset & Features
The dataset consists of the following predictors:

- **Annual Temperature Rise (°C)**
- **Urbanization Rate (%)**
- **Deforestation Policies Index (0–10)**
- **Industrial Activity (CO₂ emissions / metric tons)**
- **Rainfall Levels (mm)**

**Target Variable:**
- **Forest Cover Loss (sq km per year)**

---

## Methodology
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature relationship and correlation analysis
- Multiple Linear Regression model training
- Model evaluation using **R² score** and residual diagnostics

---

## Key Findings
- **Deforestation Policies Index** shows a strong negative correlation with forest loss  
  *(r = -0.73)*, indicating stronger policies are associated with reduced deforestation.
- **Urbanization Rate** has a moderate positive relationship with forest cover loss.
- Temperature rise and industrial activity show weaker positive relationships, while rainfall
  exhibits minimal correlation.
- Residual analysis supports the suitability of a linear regression model.

---

## Results
- **Model:** Multiple Linear Regression  
- **Performance Metric:**  
  - **R² = 0.91**

The model explains approximately **91% of the variance** in forest cover loss.

---

## Repository Structure

predicting-forest-cover-loss-mlr/
├── data/
│ ├── raw/
│ └── processed/
├── notebooks/
├── src/
├── visuals/
├── results/
├── requirements.txt
└── README.md

