# U of T Fin Tech BootCamp Class Unit 10 Assignment #

## Time Series

By: Ivan Kin-Ngai Fung

Date: July 20, 2021

**Objective**

The objective of this assignment was to utilize different libraries in Python to make forecasting analysis for CAD/JPY Yen's future movemnt.  Different forecasting models in Time Series and Linear Regression were deployed to determine the future exchange rate of CAD vs JPY Yen.  

In Time Series Analysis, we used Hodrick-Prescott filter, ARMA, and ARIMA to predict  future movements of price.  We also used the GARCH model to forecast the movement of the volatility. 

Furthermore, we used the SKlearn library to perform linear regression modeling to predict the CAD/JPY returns and use the model to predict the future values of the exchange rate.


**Results**

With ARMA, ARIMA models in time series, we can conclude that there has been a downward trend for the exchange rate of CAD/JPY.  This indicated a stronger Japanese Yen in the currency market.  However, the model is not a good fit to forecast the exchange rate since the p-values for the paramenters was more than 0.05 threshold.  This implies the models were not a good "fit" for predicting the future values. 

Furthermore, we can observed that the volatility of the exchange would be increasing from the results of GARCH models.  This model still was not a good fit with one of the parameters had a p-value greater than 0.05.  


In linear regression model, we can predict values based on the testing set of data.  The accuracy measure of out-sample root mean squared error shown a smaller value (0.6445) than that of the in-sample (0.842).  This suggested the performance of the unseen data was actually better than that of the training data (In-sample data).  