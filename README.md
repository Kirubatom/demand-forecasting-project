# Retail Demand Forecasting and Inventory Optimization

## Overview
This project builds a machine learning model to predict retail sales and support inventory planning decisions.

## Dataset
Rossmann Store Sales dataset (~250K+ records)

## Approach
- Feature engineering (lag features, seasonality)
- Model: XGBoost
- Baseline: Previous-day sales

## Results
- Baseline RMSE: ~2061  
- Model RMSE: ~1324  
- Improvement: ~35%

## Business Impact
Used predicted demand to design a simple inventory strategy with safety stock to reduce stockouts.

## Tech Stack
Python, Pandas, Scikit-learn, XGBoost
