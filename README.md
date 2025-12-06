# CaliforniaHousing_RegressionAnalysis
Comprehensive statistical analysis of the California Housing dataset, including data cleaning, exploratory analysis, feature engineering, multicollinearity checks, linear regression models, diagnostic tests, and interpretation of results. Developed as part of SMI Assignment- 1

##Project Structure

---

## **1. Objective**

The goal of this assignment is to:
- Understand dataset structure through **descriptive statistics**
- Perform **exploratory data analysis** & visualizations
- Engineer new meaningful features
- Build and evaluate **linear regression models**
- Interpret insights and validate model assumptions

---

## **2. Dataset Overview**

The California Housing dataset includes:
- Geographic features (latitude, longitude)
- Housing characteristics (rooms, bedrooms, households)
- Demographics (population, median income)
- Target variable **median_house_value**
- Categorical feature **ocean_proximity**

This dataset is widely used for regression tasks and demonstrates socioeconomic and geographic factors affecting housing prices in California.

---

## **3. Work Completed**

### **Part 1 — EDA & Data Preparation**
- Summary statistics of all features  
- Histograms, boxplots, and scatterplots  
- Handling missing values in `total_bedrooms`  
- Correlation heatmap  
- Detection of outliers  
- Creation of new engineered features:
  - `rooms_per_household`
  - `bedrooms_per_room`
  - `population_per_household`

---

### **Part 2 — Regression Modeling & Diagnostics**
- Train–test split  
- Baseline **Linear Regression Model**  
- Evaluation metrics:
  - RMSE, MAE, R², Adjusted R²  
- **Multicollinearity check (VIF)**  
- Residual diagnostics:
  - Residual distribution
  - Residual vs predicted plot  
- Improved model using engineered features  
- Comparison of baseline vs improved models  

---

### **Part 3 — Interpretation & Insights**
- Key factors influencing house prices:
  - Median income (strongest predictor)
  - Neighborhood density
  - Rooms-to-household ratio
  - Bedrooms-to-room ratio (negative association)
- Geographic factors impact pricing (coastal effect)
- Discussion of limitations:
  - Censoring at $500,000
  - Multicollinearity
  - Linear model assumptions
- Recommendations for future modeling:
  - Tree models or non-linear approaches
  - Additional socioeconomic data
  - Handling censored values with Tobit models

---

## **4. Tools & Technologies Used**
- Python  
- Google Colab / Jupyter Notebook  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-Learn  
- Statsmodels  

---



