# Predicting-Selling-price-for-used-cars

**Project Summary**

**Objective **

The primary goal was to estimate the selling price of used cars by developing a predictive model using machine learning techniques.


**Data**

The project utilized the Used Car Price Prediction Dataset, which contains 4,009 entries with features like car brand, model, model year, mileage, fuel type, and accident history.


**Methodology**

The team followed a six-phase machine learning pipeline: Problem Formulation, Data Collection and Labeling, Data Evaluation and Feature Engineering, Splitting Data and Standardization, Model Training and Evaluation, and Model Deployment.

**Key Steps**

Data cleaning involved handling null values and converting the price and milage features to a float data type.

A new feature, Age of the car, was engineered from the model_year.

Outliers in features like price, milage, and Horsepower were addressed.

Categorical features were converted to a numerical format using One-Hot, Binary, and Label Encoding.

**Model Performance & Deployment**

Two models were trained and evaluated: XGBoost Regressor and Random Forest Regressor.

The models were fine-tuned using GridSearchCV.

The XGBoost Regressor was selected as the final model because it consistently outperformed the Random Forest Regressor.

The final XGBoost model achieved a strong R² score of 84.1% (or 84%) on the test dataset, and was subsequently deployed for car price prediction.
