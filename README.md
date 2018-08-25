# cpi
The Jupyter notebook is split into two parts.

Part 1 contains code to predict Singapore's monthly Consumer Price Index via traditional time-series modelling. I explore the use of autoregressive, moving average, and ARMA models; model identification is achieved via the Box-Jenkins method.

Part 2 contains code to predict Singapore's monthly Consumer Price Index via LSTM (Long Short Term Memory) network.

I find that the LSTM network produces more accurate out-of-sample forecasts than the autoregressive model.

The data is obtained from Singstat Table Builder. CPI data spans from January 1961 to December 2017.
