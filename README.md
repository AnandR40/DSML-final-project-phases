# Wave Energy Farm Prediction

This project applies machine learning models to predict total power output from a large-scale wave energy farm dataset.

## Dataset
- The dataset contains **36043 rows and 149 columns**.
- The target variable is **Total_Power**.
- Features include positional coordinates, power output from different sources, and other numerical indicators.

## Project Workflow
1. **Exploratory Data Analysis (EDA)**
   - Checked for missing values (No missing values found).
   - Performed statistical analysis and correlation analysis.
   - Generated a heatmap to identify the most correlated features with **Total_Power**.

2. **Model Training & Evaluation**
   - Models used:
     - **Linear Regression**
     - **Decision Tree Regressor**
     - **Random Forest Regressor**
     - **Support Vector Regressor (SVR)**
   - RMSE Scores:
     - Linear Regression: **269.89** (Best Model)
     - Decision Tree: **10,137.97**
     - Random Forest: **7,489.10**
     - SVR: **121,583.74** (Performed poorly)

3. **Hyperparameter Tuning**
   - Tuned the **Linear Regression model** using GridSearchCV.
   - Best parameters: `fit_intercept` selection.
   - Best RMSE achieved through tuning.


