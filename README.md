# Advanced Time Series Forecasting for Retail Sales Optimization

## Project Overview
This project focuses on forecasting Walmart's weekly sales using historical data to enhance inventory management, staffing, and financial planning. We employ various statistical and machine learning methods, with a particular emphasis on capturing seasonal patterns and leveraging recent sales data.

## Features
- **Data Integration**: Merges multiple data sources including historical sales, store attributes, and environmental factors.
- **Time Series Analysis**: Implements trend analysis and seasonality detection to understand underlying patterns in sales data.
- **Multiple Forecasting Models**: 
  - Baseline models: Naive approach, Simple Moving Average (SMA), Exponentially Weighted Moving Average (EWMA)
  - Advanced models: Random Forest, Long Short-Term Memory (LSTM) neural networks
- **Model Evaluation**: Utilizes Mean Absolute Error (MAE) and R-squared (R²) metrics for comprehensive model assessment.


## Usage
The main analysis and model implementations are contained in the Jupyter notebook `Walmart_Sales_Forecasting__ML_2.ipynb`. To run the notebook:


## Results
Our LSTM model achieved the best performance with:
- R² score: 0.94
- Normalized MAE: 0.077

This indicates high predictive power and suggests that on average, the model's predictions are within 7.7% of the actual sales figures.
