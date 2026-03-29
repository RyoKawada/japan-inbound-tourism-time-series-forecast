# Time Series Forecasting of Visitor Arrivals to Japan
Using SARIMA and Prophet models to analyze
seasonality and forecast inbound tourism demand.

Source: JNTO official inbound visitor statistics
Data format: Excel
Reason: official monthly estimates published by JNTO
Goal: forecast monthly visitor arrivals to Japan using time-series methods

The dataset shows a clear upward trend in inbound tourism to Japan, 
with a sharp structural break during the COVID-19 pandemic in 2020, 
followed by a strong recovery starting in 2023.

The SARIMA model captures long-term trends and seasonality reasonably well.
However, it fails to account for the structural break caused by COVID-19,
resulting in large prediction errors during 2020–2022.
