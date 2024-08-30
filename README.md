## Time Series Analysis & Forecast of geological water data using ARIMA and Prophet

![Image Preview for git](https://www.verdict.co.uk/wp-content/uploads/2019/08/water-harvester.jpg)

---
### Disclaimer 
* Please open all .ipynb notebooks in google.colab , because github has problems with showing visualization packages.

### Project Overview 
---
* Build both ARIMA / Prophet  models for predicting depth to groundwater by using only univariate and multivariate dataframe in the modelling (features such as temperature, volume, hydrometry).
* Conducted Time Series analysis including decomposition of time series data, and checking for stationarity, while finally making dataset stationary.
---
### How will this project help?
* This project helps how to navigate and working with timeseries data that is not stationary and data that required detailed analysis before transforming it. Talking about, predictions this model could be used later on by geologists in order to help them to determine depth to groundwater using previous timeseries knowledge and other feature such as volume, hydrometry.
---
### Resources Used
* *packages: pandas, numpy, matplotlib, seaborn, statsmodels, missingno, pmdarima, fbprophet, sklearn.metrics*
* *Data: Acea Smart Water Analytics* - [Link for Data](https://www.kaggle.com/competitions/acea-water-prediction/data)
---
### Steps in Analysis & Forecast
1. Installation & Import of required libraries
2. Structure Investigation
* Check chronological order of dataframe
* Interpolating missing values
3. Visualization of target time series data
4. Resampling/Smoothing
5. Time Series EDA
6. Stationarity
* Augmented Dickey-Fulle test
* Visual test of stationarity
7. Making data Stationary
8. ACF/PACF
9. Modelling
10. Train/test split
11. Auto-Arima
12. Prophet (Univariate)
13. Prophet (Multivariate)
---
### Reference
[1] https://towardsdatascience.com/how-to-color-a-pandas-dataframe-41ee45db04f6

[2] https://machinelearningmastery.com/time-series-forecasting-with-prophet-in-python/#:~:text=To%20use%20Prophet%20for%20forecasting,type%20of%20seasonality%2C%20and%20more

[3] https://towardsdatascience.com/significance-of-acf-and-pacf-plots-in-time-series-analysis-2fa11a5d10a8















