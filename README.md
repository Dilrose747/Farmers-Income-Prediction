#  Predicting Farmers' Income in West Bengal Using Linear Regression (SPSS)

This project analyzes the economic determinants of rice farmers' income in West Bengal, India. Using SPSS, a multiple linear regression model was developed to predict annual earnings based on agricultural and financial variables. The study identifies key predictors such as land size, government subsidy, and loan amount, and offers actionable insights for policymakers to enhance income stability and support sustainable agricultural development.

---

##  Objectives

- To analyze the relationship between various agricultural and economic factors and farmers' income.
- To develop a linear regression model that predicts farmers' earnings.
- To assess the impact of subsidies, loans, and market conditions on income.
- To provide data-driven recommendations for policy and financial planning.

---

##  Dataset

- **Source**: [Kaggle Dataset - Farmers' Earnings in West Bengal](https://www.kaggle.com/datasets/renuprasad/farmers-earnings-westbengal)
- **Variables**:
  - Numerical: Age, Land Size (Acres), Loan Amount, Interest Rate, Government Subsidy, Market Price per Kg, Crop Loss %, Farming Experience, Annual Earnings
  - Categorical: Irrigation Type, Weather Impact
- **Year**: 2022

---

##  Methodology

1. **Data Preprocessing**:
   - Missing values handled using mean imputation.
   - Categorical variables (e.g., Irrigation Type, Weather Impact) were dummy coded.
   - Logical inconsistencies (e.g., experience > age) were removed.
   - Square-root transformation applied to earnings to correct skewness.
   - Outliers identified and removed using standardized residuals and Cook’s Distance.

2. **Exploratory Data Analysis (EDA)**:
   - Summary statistics, histograms, scatter plots, and correlation analysis were performed.
   - Variables with weak correlation to the target were excluded from the final model.

3. **Model Development**:
   - Linear regression using square-root of earnings as the dependent variable.
   - Train-Test Split: 90% training, 10% testing.
   - Performance metrics: R², Adjusted R², Standard Error.

4. **Model Evaluation**:
   - Residual plots and Q-Q plots checked for normality and homoscedasticity.
   - Post-outlier removal model: **R² = 0.871**, indicating strong model fit.

---

##  Key Findings

- **Strongest Predictors**:
  - **Government Subsidy (β = 0.741)** – Most influential.
  - **Land Size (β = 0.566)** – Larger plots yield higher income.
- **Moderate Predictors**:
  - Loan Amount, Farming Experience, Market Price per Kg.
- **Negative Impact**:
  - **Interest Rate (β = -0.117)** – Higher rates reduce earnings.

---

##  Policy Recommendations

1. **Increase Direct Government Subsidies** to improve financial outcomes.
2. **Lower Interest Loan Schemes** to reduce financial burdens on farmers.
3. **Promote Land Consolidation and Cooperative Farming** for better economies of scale.
4. **Enhance Market Infrastructure** to ensure fair pricing and reduce post-harvest loss.
5. **Encourage Skill Development and Tech Adoption** to boost productivity.

---

##  Tools Used

- **Software**: IBM SPSS Statistics
- **Techniques**: Linear Regression, Outlier Detection, Correlation Analysis, Data Transformation

---

##  Conclusion

The SPSS regression model provides valuable insights into key economic factors affecting farmers' income. Strengthening subsidy policies, providing affordable credit, and promoting agricultural innovation can significantly improve financial outcomes for farmers in West Bengal.

---

##  References

- [Kaggle Dataset: Farmers' Earnings - West Bengal](https://www.kaggle.com/datasets/renuprasad/farmers-earnings-westbengal)
- GeeksforGeeks articles on data preprocessing and SPSS

---


