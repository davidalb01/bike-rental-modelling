# Bike Rental Demand Modelling

A Python project that estimates daily bike rentals using calendar information
and observed weather. I compared linear regression, a decision tree, gradient
boosting, and XGBoost using a chronological train, validation, and test split.

XGBoost had the lowest validation RMSE and achieved a test RMSE of
1,241.42 rentals per day on the final 147 days.

[View the notebook and plots](02_Bike_Rental_Modeling.ipynb)

## Data

This notebook uses `data/raw/day.csv` from the
[UCI Bike Sharing dataset](https://archive.ics.uci.edu/dataset/275/bike-sharing-dataset).
To download a fresh copy, click **Download**, extract `day.csv`, and place it
in `data/raw/` relative to the repository root.

Source: Hadi Fanaee-T (2013), Bike Sharing, UCI Machine Learning Repository.
[Dataset DOI](https://doi.org/10.24432/C5W894) ·
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## Run locally

Make sure you have the above dataset downloaded and placed in the correct folders. Install `pandas`, `numpy`,
`matplotlib`, `seaborn`, `scikit-learn`, and `xgboost` in your notebook
environment, then run all cells from the repository root.

