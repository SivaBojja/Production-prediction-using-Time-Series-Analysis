# Production-prediction-using-Time-Series-Analysis

Time series analysis is a method of analyzing a sequence of data collected over an interval of time. It allows one to see the factors that influence certain variables and how these variables change over a period. It is mainly used to forecast/predict future data based on historical data. Two methods in which time series analysis can be performed is:

Autoregressive Integrated Moving Average (ARIMA):
In this method, the next step in the sequence is a linear function of differentiated observations and Residual errors at prior time steps. It combines both the Moving average and Auto Regression as well as a differencing preprocessing step of the sequence to make the sequence stationary, called integration. The notation for the model involves specifying the order for the Auto Regression, Integration, and Moving Average models as parameters to an ARIMA function. This method is suitable for univariate time series with trend and without seasonal components.

Seasonal Autoregressive Integrated Moving-Average with Exogenous Regressors (SARIMA):
This method models the next step in the sequence as a linear function of the differenced observations, errors, differenced seasonal observations, and seasonal error at prior time steps. It combines the ARIMA models with the ability to perform the same autoregression, differencing , and moving average modeling at the seasonal level. The notation for the model involves specifying the order for the AR(p), I(d), and MA(q) models as parameters to an ARIMA function and AR(P), I(D), MA(Q) and m parameters at the seasonal level. A SARIMA model can be used to develop AR, MA, ARMA and ARIMA models. The method is suitable for univariate time series with trend and/or seasonal components.

