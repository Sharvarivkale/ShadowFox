Project Overview

This repository demonstrates building regression models (Linear Regression and Random Forest Regressor) to predict house prices (MEDV) using features such as number of rooms, crime rate, tax rate, pupil-teacher ratio, etc. Emphasis is on data cleaning, feature analysis, model training, evaluation, and interpretation of feature importances.

Dataset

File: HousingData.csv

Target: MEDV — Median value of owner-occupied homes (in $1000s)

If the dataset is private or restricted, include a small example CSV or provide instructions to obtain the dataset.

Features (common)

Typical features included in the Boston dataset:

CRIM, ZN, INDUS, CHAS, NOX, RM, AGE, DIS, RAD, TAX, PTRATIO, B, LSTAT

Preprocessing

Check and handle missing values (e.g., data.fillna(data.mean()))

Feature scaling using StandardScaler (needed for some models like Linear Regression)

Train/test split (commonly test_size=0.2, random_state=42)

Models:
Linear Regression — baseline, interpretable
Random Forest Regressor — usually better performance on this dataset and provides feature importances

Evaluation Metrics
For regression use:
MAE — Mean Absolute Error
MSE — Mean Squared Error
RMSE — Root Mean Squared Error
R² — Coefficient of Determination (used as regression “accuracy”)
Results (observed during experiments)
These are the example results obtained while running experiments in this project.

Random Forest Regressor (All features)
MAE: 2.0675
MSE: 8.2437
R²: 0.8876

Note: exact values may vary depending on data split and random seed.<img width="762" height="525" alt="Screenshot 2025-10-05 112858" src="https://github.com/user-attachments/assets/c78a65a7-a2c9-4332-867f-922e9e563d12" />
<img width="558" height="616" alt="Screenshot 2025-10-05 112842" src="https://github.com/user-attachments/assets/07df7678-b2c3-4d5a-a1b8-73d3e1fd8106" />
<img width="485" height="620" alt="Screenshot 2025-10-05 112827" src="https://github.com/user-attachments/assets/158dad89-7db2-4f27-8985-2fc8b0510bfa" />
<img width="583" height="390" alt="Screenshot 2025-10-05 112911" src="https://github.com/user-attachments/assets/686e4666-bb77-449c-bb2c-7a98b8e48f58" />
 If you re-run experiments, update these numbers.
