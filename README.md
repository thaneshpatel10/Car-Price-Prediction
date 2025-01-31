**#Car Selling Price Prediction** 

**This project aims to predict the selling price of used cars using various machine learning models. The dataset includes multiple features such as car brand, model, year, fuel type, transmission, and mileage.**

Table of Contents:
Dataset
Preprocessing
Models Used
Performance Metrics
Results
Usage
Future Improvements

Dataset:
The dataset contains information about used cars, including:
Car Name
Model Year
Fuel Type
Transmission Type
Mileage
Engine Power
Number of Owners
Selling Price

Preprocessing:
Dropped unnecessary columns (Unnamed: 0, Mileage Unit)
Encoded categorical variables using OneHotEncoder
Scaled numerical features
Split data into training and testing sets (80/20 ratio)

Models Used:
I implemented and compared the following regression models:
Linear Regression
Lasso Regression
Ridge Regression
KNN Regressor
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor
XGBoost Regressor

Performance Metrics:
Each model was evaluated using:
R² Score
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)

Results:
Random forest, Gradient Boosting and XGboost performed well with Highest R2 score and lowest Mean Absolute Error and Root Mean Square Error,
this may be due to imbalanced dataset, these models perform well with the imbalanced dataset also.


Future Improvements:
Hyperparameter tuning using GridSearchCV
Feature selection using SHAP values
Experimenting with CatBoost and LightGBM
Applying log transformation to the target variable

Author
Developed by [Thanesh Patel G S] 🚀

This dataset was taken from Kaggle
