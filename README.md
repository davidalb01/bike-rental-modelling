# Bike Rental Demand Modelling

A Python project that estimates daily bike rentals using calendar information
and observed weather. I compared linear regression, a decision tree, gradient
boosting, and XGBoost using a chronological train, validation, and test split.

XGBoost had the lowest validation RMSE and achieved a test RMSE of
1,241.42 rentals per day on the final 147 days.

[View the notebook and plots](02_Bike_Rental_Modeling.ipynb)

## Run locally

Place the daily dataset file at `data/raw/day.csv`. Install `pandas`, `numpy`,
`matplotlib`, `seaborn`, `scikit-learn`, and `xgboost` in your notebook
environment, then run all cells from the repository root.
