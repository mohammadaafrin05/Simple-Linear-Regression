# Simple-Linear-Regression
This repository contains implementations of Simple Linear Regression on both a toy dataset and the Boston Housing dataset. 
The project includes:
Analytic formulation for computing regression coefficients and performance measures (Sum of Squared Errors (SSE), R²).
Gradient descent optimization methods, including:
Full-batch Gradient Descent.
Stochastic Gradient Descent.
Analysis of Boston Housing dataset to identify the input attribute that best follows a linear relationship with the output price.

linear_regression_gradient_descent.py:
Implements gradient descent on Least Mean Square (LMS) loss.
Includes both full-batch and stochastic gradient descent with stopping criteria.
Outputs the final regression coefficients, SSE, and R² value for comparison.
boston_housing_analysis.py:

Downloads the Boston Housing dataset.
Analyzes the input attributes to find the one that best follows a linear relationship with housing prices.
Implements both analytic and gradient descent methods for regression.

Performance Metrics:
Sum Squared Error (SSE): Measures the total deviation of the predicted values from the actual data points.

R² Value (Coefficient of Determination): Measures how well the regression model fits the data (1.0 represents a perfect fit).

