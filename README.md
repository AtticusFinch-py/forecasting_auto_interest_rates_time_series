# Car Loan Interest Rate Forecasting Project

## Project Overview
This project applies time series analysis techniques to forecast interest rates on car loans. We utilize the SARIMAX (Seasonal Autoregressive Integrated Moving Average with eXogenous variables) model to understand the trends and seasonality in historical interest rate data and make future predictions.

## Background
Interest rates on car loans are influenced by various factors, including economic indicators and policy decisions. Accurate forecasting of these rates can aid financial institutions in decision-making and risk management, as well as assist consumers in planning their finances.

## Data
The dataset consists of historical interest rates on 60-month car loans. The data is resampled to a quarterly frequency to capture seasonal patterns, with NaN values handled via forward-fill amd back-fill imputation to maintain data continuity.

## Model
We employ a SARIMAX model that takes into account both endogenous (historical interest rates) and exogenous variables (economic indicators, policy changes, etc.) to predict future interest rates.

## Forecasting
Our model provides a forecast for the interest rates for the next four quarters, giving stakeholders valuable insights into future trends.

## How to Use

For a deeper dive into the methodology, data preprocessing, and model evaluation, please refer to the Jupyter notebooks and scripts included in this repository.

## Contact
If you have any questions or would like to contribute to the project, please feel free to reach out.

