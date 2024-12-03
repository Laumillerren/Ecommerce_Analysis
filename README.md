# Ecommerce_Analysis

The primary goal of this project is to predict sales amounts based on five years of daily sales data from Walmart stores across California, Texas, and Wisconsin. 
The project aims to leverage historical data to build models capable of accurate forecasting to support inventory management, revenue optimization, and customer satisfaction.

The dataset includes five years of daily sales records, stratified by state, store, category, department, and item, with additional explanatory variables such as promotions and holidays. 
This data was provided by Walmart for the M5 competition hosted on Kaggle in 2020. For this project, Level 7 aggregation (state and department level) was selected for meaningful insights. (see aggregation.R file)

Linear Regression, Random Forest, and XGBoost models were applied to the target variable (value). Linear regression model was applied directed to the processed data. 
Random Forest is an ensemble-based model that leverages bagging and decision trees. XGBoost is a gradient-boosting model.
Models were evaluated using mean squared error (MSE), root mean squared error (RMSE), mean absolute error (MAE), and R-squared. 