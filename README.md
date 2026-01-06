# VIX Prediction with Machine Learning

## Description
This project applies machine learning techniques to financial time series in order to predict the VIX one day ahead. It combines exploratory data analysis, dynamic correlation analysis, advanced feature engineering (lags, realized volatility, PCA, stress indicators), and linear and non-linear models adapted to time series data.

## Project Structure
- Data download using Yahoo Finance  
- Exploratory data analysis (prices, returns, volatility)  
- Dynamic correlation analysis with rolling windows  
- Feature engineering:
  - Lagged variables
  - Realized volatility
  - Log-returns and moving averages
  - PCA on correlated assets
  - Stress and shock indicators  
- Model training and evaluation using time-series-aware splits  

## Models Used
- Linear Regression  
- Ridge Regression  
- Lasso Regression  
- Random Forest Regressor  
- Gradient Boosting Regressor  

## Evaluation
Models are evaluated using time series splits to avoid data leakage. Performance metrics include RMSE and R², with additional residual diagnostics to assess model behavior.

## Requirements
- Python 3.9+  
- numpy  
- pandas  
- matplotlib  
- seaborn  
- yfinance  
- scikit-learn  
- ipywidgets  
- jupyter notebook  

## Usage
1. Install the required dependencies  
2. Open the Jupyter notebook  
3. Run the cells sequentially to reproduce the analysis and results  

## Notes
This project is for educational purposes and does not constitute financial advice.
