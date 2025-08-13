# From Single to Multiple Linear Regression Boston Housing Case Study
Predicting Boston housing prices using simple and multiple linear regression. Includes correlation analysis, feature selection, model evaluation (R², RMSE, MAE), and visualizations for interpretability.

From Single to Multiple Linear Regression — Boston Housing Case Study
Project Overview

This project explores the application of Simple Linear Regression and Multiple Linear Regression using the Boston Housing Dataset. The objective was to understand the relationship between housing prices (medv) and key predictor variables.
We started by building a simple regression model using one feature (rm - average number of rooms) and then expanded to a multiple regression model using six predictors: rm, b, lstat, ptratio, tax, and chas. The goal was to compare performance, interpret coefficients, and learn how additional features impact model accuracy.

The project includes:

    Data preprocessing (handling missing values, filtering outliers, selecting relevant features)

    Exploratory Data Analysis (EDA) with correlation analysis for positive and negative relationships

    Building and evaluating regression models with performance metrics (R², RMSE, MAE)

    Checking multicollinearity with Variance Inflation Factor (VIF)

    Visualization of regression results, including 2D and 3D plots

Tools & Technologies

    Python (NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, statsmodels)

    Jupyter Notebook for step-by-step implementation and visualization

    EDA techniques to understand feature relationships

    Linear regression algorithms for prediction

Skills Gained

    Understanding of Simple vs Multiple Linear Regression

    Correlation analysis for feature selection

    Interpreting regression coefficients in real-world context

    Detecting multicollinearity using VIF

    Evaluating regression models with error metrics

    Data visualization for regression interpretation

Approach

    Data Preparation

        Loaded and cleaned the Boston Housing dataset

        Removed medv values above 50 (outliers)

        Selected relevant features based on correlation analysis

    Model 1 — Simple Linear Regression

        Predictor: rm (average number of rooms)

        R²: 0.46 | RMSE: 5.65 | MAE: 4.13

    Model 2 — Multiple Linear Regression

        Predictors: rm, b, lstat, ptratio, tax, chas

        R²: 0.803 | RMSE: 3.41 | MAE: 2.73

    Multicollinearity Check

        Calculated VIF for predictors to ensure low redundancy

    Visualization

        Scatter plots, regression line

 Conclusion

Adding more relevant features improved R² from 0.46 to 0.803, showing a much better fit and reduced prediction error. This project demonstrates the power of feature selection and model expansion in regression analysis.
