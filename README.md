# M5-Walmart-Sales-Forecasting
This is [Kaggle Competition](https://www.kaggle.com/c/m5-forecasting-accuracy) for predicting next 28 data sales for products in 3 states of United States (California, Texas, and Wisconsin)

This Competition consist of sales data of 10 stores each having 30490 products 
from year 2011-01-29 to 22-05-2016.Out of this last 28 days are used as test data for 
Public Score Evaluation and next 28 days after them 23-05-2016 to 19-06-2016 are used for Private Score Evaluation in this Competition.<br/>


In this Competition are using Weighted Root Mean Squared Scaled Error (WRMSSE) as evaluation metric.

Given File Data:
* calendar.csv - Contains information about the dates on which the products are sold.
* sell_prices.csv - Contains information about the price of the products sold per store and date.
* sales_train_validation.csv - Contains the historical daily unit sales data per product and store [d_1 - d_1913]
* sales_train_evaluation.csv - Includes sales [d_1 - d_1941] (labels used for the Public leaderboard)
* sample_submission.csv - The correct format for submissions.

File In This Repository:
* m5-accuracy-crisp-dm.ipynb - Contains all my Introduction, Problem Statement, EDA Process, Preprocessing, Feature Engineering, Modeling, Model Evaluation.

Features:
1. Lagged Features
2. Rolling Demand Features
3. Price Features
4. Time Features
5. Revenue Features

Model Used:
1. Linear Regression
2. Ridge Linear Regression
3. LGBM Regressor
