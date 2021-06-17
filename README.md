# Forecast_Daily_Home_Energy_Demand

## Problem Statement: 

To accurately predict energy demands throughout the day based on seasonality, trend, and covariates like outside temperature and humidity.

## Dataset:
This dataset includes measurements of 9 rooms in a house, monitored with a ZigBee wireless sensor network. 

The time series has 24 dimensions.
It includes weather and climate data: temperature, pressure, humidity, wind speed, visibility and dewpoint measured from Chievres airport (Belgium). 

The data set is averaged for 10 minutes period and spanning 4.5 months.

Timeframe:
1/11/2016 – 5/27/2016 (19736 observations)

## Modeling:
Univariate: 1. sNaive, 2.sARIMA, 3. Fourier, 4. TBATS
  
Multivariate: 1. VAR (Energy and Outside Temperature variables),2.Regression with ARIMA Errors: is_8a_10p (daytime indicator), Outside temperature  - Independent variables
Energy – Dependent variable

## Metric:
RMSE : The Root Mean Squared Error is defined as the square root of the average squared error.


