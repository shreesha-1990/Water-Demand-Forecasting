# Water-Demand-Forecasting
Water Demand Forecasting for next 24 hours

An approach to ease operations burden by providing foresight into how much water the city will require (water demand) for the next 24 hours. The City has provided time series data containing their total production, temperature, precipitation, and the occurrence
of any major festival.

The Time series is multivariate with previous 2 years of data. I tried two approaches.

Vector autoregression (VAR) is a stochastic process model used to capture the linear interdependencies among multiple time series. VAR models generalize the univariate autoregressive model (AR model) by allowing for more than one evolving variable.

ARIMA is an acronym that stands for AutoRegressive Integrated Moving Average. It is a class of model that captures a suite of different standard temporal structures in time series data

I have 2 notebooks. One for each of the approach. Data Exploration, Data Cleaning, Outlier treatment, Time series forecasting and Anomaly detections are covered in the notebooks.
