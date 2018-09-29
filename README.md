# cpi
The Jupyter notebook is split into two parts.

Part 1 contains code to predict Singapore's monthly inflation rate (based on the Consumer Price Index) via traditional time-series modelling. I explore the use of autoregressive, moving average, and ARMA models; model identification is achieved via the Box-Jenkins method.

Part 2 contains code to predict Singapore's monthly inflation rate via LSTM (Long Short Term Memory) network.

I find that an AR(6) model achieves an RMSE of 0.5024% on the test set, whereas the LSTM model achieves an RMSE of 0.5150% on the test set.

The data is obtained from Singstat Table Builder. CPI data spans from January 1961 to December 2017.
