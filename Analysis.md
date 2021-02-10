#### Time-Series Forecasting
The p-values of the ARMA model are pretty high. ON the contrary, the  AIC And BIC values are low as compared to those for the ARIMA models
The p-values for the ARIMA model are almost zero. BUt the AIC and BIC values are pretty high. 
FOr the yen, the ARMA and ARIMA models are not aligned.
I am not confident of using either model for trading. 

#### Linear Regression Forecasting
RMSE for out-of-sample is 0.41545437184712763
RMSE for in-sample is 0.5962037920929946

The out-of-sample RMSE is lower than the in-sample RMSE. RMSE is typically lower for training data, but is higher in this case. The larger the RMSE, the larger the difference between the predicted and observed values, which means the worse a model fits the data. Conversely, the smaller the RMSE, the better a model is able to fit the data.

So based on that the there seems to be a bit of an overfit problem. THe model performs worse on out-of-sample data compared to in-sample data.
