# Retail Demand Forecasting and Inventory Optimization

## Problem
Retail businesses face demand uncertainty, leading to overstock or stockouts. This project predicts daily sales to support better inventory decisions.

## Dataset
Rossmann Store Sales dataset (~250K+ records)

## Approach
- Cleaned and preprocessed time-series retail data
- Engineered features: lag sales, seasonality, promotions
- Built XGBoost regression model
- Compared against baseline (previous-day sales)

## Results
- Baseline RMSE: ~2061  
- Model RMSE: ~1324  
- Improvement: ~35%

## Key Insight
Promotions and recent sales trends are the strongest drivers of demand.

## Business Impact
Predicted demand can be used to maintain safety stock and reduce stockouts.

## Tech Stack
Python, Pandas, Scikit-learn, XGBoost
