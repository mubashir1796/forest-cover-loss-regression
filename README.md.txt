# Predicting Forest Cover Loss Using Multiple Linear Regression

## Overview  
This project applies a **Multiple Linear Regression (MLR)** approach to predict **global forest cover loss** using real-world environmental and socio-economic indicators. The goal is twofold:  
1) build a reliable predictive model, and  
2) interpret the drivers of deforestation through coefficients and feature relationships.

Using a case-study learning approach, the project moves from raw data exploration to model evaluation and interpretation. The final model achieves **R² = 0.91**, showing strong explanatory and predictive performance.

---

## Problem Statement  
Forest cover loss is a major environmental and development challenge. Understanding which measurable factors are associated with higher deforestation can support better policy discussions and sustainable planning.

This project asks:  
**Can forest cover loss be accurately predicted using multiple linear regression, and which variables appear most influential?**

---

## Dataset & Features  
The dataset includes multiple predictors linked to forest loss. Features used:

- **Annual Temperature Rise (°C)**  
- **Urbanization Rate (%)**  
- **Deforestation Policies Index (0–10)**  
- **Industrial Activity (CO₂ emissions / metric tons)**  
- **Rainfall Levels (mm)**  

**Target variable:**  
- **Forest Cover Loss (sq km per year)**

---

## Methodology  
The workflow follows an end-to-end ML case-study pipeline:

1. **Data Cleaning & Preprocessing**  
   - Checked missing values and consistency  
   - Ensured numeric formatting and clean feature ranges  

2. **Exploratory Data Analysis (EDA)**  
   - Visualized distributions and trends  
   - Studied feature relationships and correlation structure  

3. **Model Training**  
   - Implemented Multiple Linear Regression  
   - Split data into training/testing sets  
   - Fit model using training data  

4. **Evaluation & Diagnostics**  
   - Evaluated predictive strength using **R² score**  
   - Checked residual behavior for linear fit validity  

---

## Key Visual Findings  

### 1) Urbanization vs. Forest Cover Loss  
A moderate **positive relationship** appears between urbanization and forest cover loss. Higher urban growth generally aligns with increased deforestation pressure.

### 2) Correlation Matrix Insights  
- **Deforestation Policies Index vs Forest Loss: r = −0.73**  
  Strong negative relationship → stronger policies correlate with reduced forest loss.  
- **Urbanization Rate vs Forest Loss: r = 0.49**  
  Moderate positive association → urban expansion correlates with more loss.  
- Temperature rise and industrial activity show weaker positive links, while rainfall has near-zero correlation.

### 3) Residual Plot  
Residuals are mostly centered around zero with fairly stable variance, supporting that multiple linear regression is an appropriate fit with only minor curvature at higher values.

### 4) Target Distribution  
Forest cover loss is approximately bell-shaped with mild skew, indicating regression suitability while suggesting a few high-loss outliers.

---

## Results  
- **Final Model: Multiple Linear Regression**  
- **Performance:**  
  - **R² = 0.91**  

This indicates the model explains about **91% of the variance** in forest cover loss using the selected predictors.

---

## Conclusion  
The model shows that forest cover loss can be effectively predicted using environmental and socio-economic indicators. Policy strength emerges as the most protective factor, while urbanization appears as a key pressure variable.  

This work demonstrates how interpretable ML methods can contribute to understanding real environmental challenges.

---

## Repository Structure  
