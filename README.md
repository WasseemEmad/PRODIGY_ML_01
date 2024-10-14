# PRODIGY_ML_01

#**House Price Prediction using Linear Regression**

This repository contains a project for predicting house prices based on various features using linear regression. The goal is to build a model that can accurately estimate the sale price of a house given specific input features such as square footage, number of bedrooms, and bathrooms. The project includes data preprocessing, outlier handling, model training, evaluation, and performance improvement using a log transformation.

##**Project Overview**
###**The project follows these main steps:**

###**Data Exploration and Cleaning:**

Load the dataset and inspect it for any missing values.
Identify and handle outliers in the SalePrice column using the interquartile range (IQR) method.

###**Feature Engineering:**

Create new features to represent the total area and total number of bathrooms by combining relevant columns.
Use Total_Area, Total_Bathrooms, and BedroomAbvGr as input features for the prediction model.

###**Data Splitting and Standardization:**

Split the dataset into training and testing sets.
Apply standard scaling to normalize the features.

###**Model Training:**

Train a linear regression model using the training dataset.
Make predictions on the test set.

###**Evaluation and Visualization:**

Evaluate the model's performance using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R² Score.
Visualize the predictions against the actual values to assess the model's performance.

###**Improving Model Performance:**

Apply a log transformation to the target variable (SalePrice) to handle skewness and improve the model's predictive capability.
Retrain the model and evaluate its performance using the original scale for a direct comparison.

##**Results and Conclusion**
The model performs linear regression to predict the house sale price based on features like total area, number of bedrooms, and total bathrooms. The application of a log transformation significantly improves prediction accuracy by reducing skewness and stabilizing the variance.

##**Key Evaluation Metrics (Post Log Transformation):**
**Mean Squared Error (MSE):** Evaluates the average squared difference between actual and predicted values.
**Root Mean Squared Error (RMSE):** The square root of MSE, providing error in the same units as the target variable.
**Mean Absolute Error (MAE):** Represents the average absolute difference between actual and predicted values.
**R² Score:** Measures the proportion of variance in the target variable explained by the features.
