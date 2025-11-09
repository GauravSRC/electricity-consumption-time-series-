AI-Based Energy Demand Forecasting and Optimization
Overview

This project develops an AI-powered forecasting framework to optimize renewable energy distribution and storage management.
It predicts electricity demand using multiple time-series and machine learning models to support data-driven energy dispatch and bidding decisions.

Dataset

The project uses the UK National Grid Electricity Consumption dataset (2009–2024) as a representative proxy for regional renewable grid operations.
It contains half-hourly electricity demand, embedded solar/wind generation, and interconnector flow data — ideal for high-frequency forecasting tasks.

Project Workflow

Data Cleaning & Preprocessing – handling missing values, merging date-time, removing anomalies.

Feature Engineering – creation of time, lag, and holiday-based features.

Exploratory Data Analysis (EDA) – identification of seasonality, trends, and consumption patterns.

Model Training – comparison of SARIMA, XGBoost, Linear Trees, Prophet, and LSTM models.

Evaluation – performance measured using MAPE and RMSE metrics.

Future Forecasting & Scenario Simulation – demand prediction for 210 days ahead.

Key Results

LSTM and Prophet (with holidays) gave the most accurate forecasts.

The framework demonstrates strong potential for improving grid reliability and reducing operational losses.

Files

main_notebook.ipynb – full implementation with preprocessing, modeling, and forecasting

detailed_report.docx – complete project explanation and case study discussion

README.md – this file

Future Enhancements

Integration with real Indian weather and market data

Reinforcement learning for real-time bidding optimization

Streamlit dashboard for live visualization
