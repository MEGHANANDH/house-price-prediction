**# House Price Prediction**



**# Objective:**

Predict house prices using regression models.



**# Approach:**

\- Exploratory Data Analysis (EDA)

\- Preprocessing (scaling numeric features + encoding categorical features)

\- Model comparison (Linear Regression, Random Forest, Gradient Boosting)



**# Results:**

Gradient Boosting performed best with the lowest RMSE and MAE.  

Feature importance analysis confirmed that `sqft\_living` and location features are the strongest predictors.



**# Usage:**

\#python

import joblib

model = joblib.load("house\_price\_model.pkl")

prediction = model.predict(sample\_input)



