# Project Overview

This project predicts hourly bike rental demand using historical data. It combines exploratory data analysis (EDA) with multiple regression models to identify key demand drivers and build an accurate forecasting solution.

The final model selected is **Random Forest Regressor**, chosen based on superior performance across evaluation metrics.

# Objective

~To analyze temporal, environmental, and user-related factors influencing bike rentals and develop a regression model capable of accurately forecasting total demand.

~This project seamlessly combines exploratory analysis with predictive modeling, transforming raw rental data into actionable business intelligence.

# Dataset

* 17,379 hourly records
* 16 structured features
* Target variable: `count` (Total Bike Rentals)
* Includes time-based, environmental, and user-related variables

# Key Insights

* Strong commuter-driven peak patterns (morning & evening hours)
* Seasonal and temperature variations significantly impact demand
* Registered users show the highest correlation with total rentals
* Non-linear relationships justify ensemble modeling techniques

# Models Implemented

* Decision Tree
* Random Forest
* Gradient Boosting
* Linear Regression
* Support Vector Regressor

# Final Model

**Random Forest Regressor** achieved the lowest MAE & RMSE and highest R² score, effectively capturing non-linear relationships and feature interactions.

# Deployment

The trained model was serialized using `joblib` and saved as `model.pkl` for reuse.
It can be integrated into a Streamlit or Flask application for real-time rental demand prediction.

 **Model File:** [Download model.pkl](https://drive.google.com/file/d/1JTI-hfZN7m5gTLXyLTACbwq_FhEluIYL/view?usp=drive_link)

# Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib
