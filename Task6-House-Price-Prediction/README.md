Task 6 : House Price Prediction
Objective: Predict house prices using property features such as area, bedrooms, bathrooms, floors, location and condition.
Dataset: House Price Prediction Dataset from Kaggle, 2000 rows and 10 columns.
Model: Gradient Boosting Regressor
Results:

MAE: 247,238 USD
RMSE: 285,822 USD
Model predicts average price (~$537k) for most houses indicating weak feature-price relationships in the dataset

Key Steps:

Dropped Id column as it adds no predictive value
Encoded Location and Condition using get_dummies
Encoded Garage using Label Encoding (binary Yes/No)
Trained Gradient Boosting Regressor
Evaluated with MAE and RMSE
Visualized actual vs predicted prices using scatter plot
