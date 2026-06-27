# Project: Taxi Demand Forecasting

## Description
This project focuses on forecasting the number of taxi orders at airports for the next hour, enabling optimized driver allocation during peak demand periods.

## Goal
Build a taxi demand forecasting model to:
- Plan driver shifts in advance
- Reduce customer wait times
- Improve service quality and resource efficiency

## Workflow
- Data preprocessing and time series analysis
- Exploratory Data Analysis (EDA): trend and seasonality analysis
- Feature Engineering: lag features and rolling statistics
- Model training and comparison:
   - Hyperparameter tuning with GridSearchCV and TimeSeriesSplit
   - Model evaluation by RMSE, training time, and inference time
   - Selection of the optimal forecasting model
- Conclusions and recommendations

## Technologies
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, LightGBM, Time Series Analysis

## Key Results
- Identified strong daily and weekly demand patterns in taxi orders
- Built and compared Linear Regression, Decision Tree, and LightGBM models
- Best model — Linear Regression: RMSE = 34.24 on the test set, well below the required threshold of 48
- Developed a model applicable to real-time driver allocation and demand planning
