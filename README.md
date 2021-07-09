# Description
* Use historical data of Yen daily settle prices against the USD for Time-Series forecasting and Regression analysis utilizing the Hodrick-Prescott Filter, ARMA Model, ARIMA Model, and GARCH Model
* Use the same data to perform regression analysis with Sklearn Linear Regression model to predict Yen futures returns with lagged Yen futures returns. 
## Summary
### Time Series Analysis
* Historical prices indicate Yen is far under its all time highs against the dollar as compared to 2012 and 1996
* Hodrick-Prescott Filter shows much lower noise in recent years
* ARMA Model predicts positive returns on the 5-day forecast with a range of .006-.012
* ARIMA Model predicts constant increasing returns on the 5-day forecast
* GARCH Model predicts constant increasing volatility on the 5-day forecast
### Regression Analysis
* The Out-of-Sample model performs better than the In-sample as the Root Mean Squared Error is significantly smaller.

