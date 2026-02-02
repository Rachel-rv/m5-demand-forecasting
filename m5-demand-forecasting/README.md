# M5 Demand Forecasting – End-to-End Time Series Project

## Overview
This project builds an end-to-end demand forecasting system using the M5 Walmart sales dataset. 
The objective is to compare classical and modern time-series models and evaluate their business impact 
on large-scale retail inventory planning.

## Dataset
- M5 Forecasting (Walmart sales)
- Daily sales aggregated to weekly demand for improved signal stability

## Methodology
1. Exploratory data analysis (daily vs weekly demand)
2. Baseline models:
   - Naive
   - Seasonal Naive
3. Classical models:
   - SARIMA
4. Modern model:
   - Prophet
5. Model comparison using MAE and RMSE
6. Business impact analysis

## Key Insights
- Daily demand is highly noisy with intermittent zero sales.
- Weekly aggregation significantly improves forecastability.
- Prophet outperforms classical baselines by modeling seasonality and trend shifts explicitly.

## Business Impact
Improved weekly demand forecasts enable tighter inventory control, reduced stockouts, 
lower holding costs, and better service levels. Even modest forecasting improvements 
can translate into significant financial gains at Walmart-scale operations.

## Future Work
- Item-level hierarchical forecasting
- Event-aware regressors
- Deep learning models (LSTM, Temporal Fusion Transformers)
- Production deployment with retraining and alerting strategies
