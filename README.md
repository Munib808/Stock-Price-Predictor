# Stock Price Predictor

A comprehensive Jupyter Notebook for predicting stock prices using machine learning models.  
This project downloads historical stock data for **Apple Inc. (AAPL)** from Yahoo Finance, performs exploratory data analysis, and implements multiple regression models to predict future stock prices.

---

## Features
- **Data Collection**: Automatically downloads historical AAPL stock data from Yahoo Finance (2015–2023)  
- **Data Preprocessing**: Handles data cleaning and preparation for machine learning  
- **Exploratory Data Analysis**: Visualizes trends and patterns in the stock data  
- **Multiple Models**: Implements various regression algorithms:
  - Linear Regression  
  - Lasso Regression  
  - Ridge Regression  
  - Random Forest Regressor  
  - Extra Trees Regressor  
- **Model Evaluation**: Uses metrics like Mean Squared Error (MSE) and R² score  
- **Hyperparameter Tuning**: Implements `GridSearchCV` for optimal model performance  

---

## Data Source
The notebook uses **Yahoo Finance API** via the `yfinance` library to download historical stock data for **AAPL (Apple Inc.)** from January 1, 2015 to December 31, 2023.

---

## Models Implemented
- **Linear Regression**: Baseline linear model  
- **Lasso Regression**: Linear model with L1 regularization  
- **Ridge Regression**: Linear model with L2 regularization  
- **Random Forest Regressor**: Ensemble method using multiple decision trees  
- **Extra Trees Regressor**: Extremely Randomized Trees ensemble method  

---

## Evaluation Metrics
- Mean Squared Error (MSE)  
- R-squared (R²) score  

---

## Results
The notebook includes comprehensive evaluation of each model's performance, allowing comparison of different approaches to stock price prediction.

---

## Dependencies
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  
- yfinance  
