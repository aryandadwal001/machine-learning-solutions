# Simple House Price Prediction using Linear Regression

## Project Overview 
This repository contains a basic, end-to-end machine learning project that uses **Linear Regression** to predict house sale prices. The model focuses on the relationship between house characteristics specifically **Square Footage** (`GrLivArea`), **Number of Bedrooms** (`BedroomAbvGr`), and a derived **Total Bathrooms** feature and the final sale price.

It serves as an excellent starting point for understanding the core concepts of supervised learning, feature selection, model training, and performance evaluation.

## Features Used
The model is trained on the following features:
* **`GrLivArea`**: Above ground living area square footage.
* **`BedroomAbvGr`**: Number of bedrooms above ground.
* **`TotalBathrooms`**: A derived feature combining `FullBath` + (`0.5` * `HalfBath`).

## Key Steps Implemented
1.  **Data Loading**: Imports house price data from a CSV file (`train.csv`).
2.  **Feature Engineering**: Creates the `TotalBathrooms` feature.
3.  **Data Splitting**: Divides the data into 80% training and 20% testing sets.
4.  **Model Training**: Trains a `LinearRegression` model from `scikit-learn`.
5.  **Model Evaluation**: Calculates and displays key metrics: **R-squared ($R^2$)**, **Root Mean Squared Error (RMSE)**, and **Mean Absolute Error (MAE)**.
6.  **Visualization**: Generates plots for **Actual vs Predicted Prices**, **Residuals**, and **Feature Coefficients**.
7.  **Prediction Examples**: Demonstrates the model's predictive power with sample house data.

## Prerequisites
To run this project, you need to have Python and the following libraries installed:
* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`
* `scikit-learn`

You can install them using pip:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn

