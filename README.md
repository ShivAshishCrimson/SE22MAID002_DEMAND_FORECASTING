# SE22MAID002_DEMAND_FORECASTING

A retail chain in India wants to use data source to build an efficient forecasting model to predict the sales SKU wise in its portfolio at its 76 different stores using historical sales data for the past 3 years on a week-on-week basis. Sales and promotional seasonality is also available for each week- SKU and store wise.
However, no other information regarding stores and products are available. Can you still forecast accurately ?

Yes, this problem can be solved by using regression approach and many more possible solutions can be used, for this assignment i am going to stick with LightGBM
LightGBM is a gradient boosting framework that uses tree based learning algorithms. It is designed to be distributed and efficient with the following advantages:
Faster training speed and higher efficiency.
Lower memory usage.
Better accuracy.
Support of parallel, distributed, and GPU learning.
Capable of handling large-scale data.

Challenges and Difficulties
Time series forecasting by regression, although widely used, can encounter several challenges. Some of the prominent issues include:
Autocorrelation: Time series information frequently displays examples of sequential connection, where the value of a variable at a specific time is reliant upon its past qualities. This violates the assumption of independence among the predictors in the regression model.

Non-stationarity: Many time series show patterns, irregularity, or different types of non-stationarity, which can violate the assumption of steady mean and variance

Seasonality and periodicity: Conventional regression models may not be prepared to deal with occasional variances in the information. This could lead to inaccurate modeling 

Outliers and anomalies: Time series data can often have outliers or anomalies, which can skew the regression model's results. Failing to address these outliers can lead to inaccurate forecasts and biased parameter estimates.

Model selection and overfitting: Choosing an appropriate regression model for time series forecasting can be challenging. Overfitting can occur when the model is excessively complex or when it captures noise in the data rather than true patterns. This can lead to poor generalization and inaccurate predictions.
Handling missing data: Time series information frequently contains missing values, which can be a problem for regression techniques. Attributing missing values without accounting for the temporal characteristic of the data can introduce biases and affect the accuracy of the forecasts.


