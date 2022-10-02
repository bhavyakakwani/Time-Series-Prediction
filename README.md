# Time Series Prediction

Project by: **Bhavya Kakwani**

***

# What is Time Series?

In mathematics, a time series is a series of data points indexed (or listed or graphed) in time order. Most commonly, a time series is a sequence taken at successive equally spaced points in time. Thus it is a sequence of discrete-time data. Examples of time series are heights of ocean tides, counts of sunspots, and the daily closing value of the Dow Jones Industrial Average.

A time series is very frequently plotted via a run chart (which is a temporal line chart). Time series are used in statistics, signal processing, pattern recognition, econometrics, mathematical finance, weather forecasting, earthquake prediction, electroencephalography, control engineering, astronomy, communications engineering, and largely in any domain of applied science and engineering which involves temporal measurements.

Time series analysis comprises methods for analyzing time series data in order to extract meaningful statistics and other characteristics of the data. Time series forecasting is the use of a model to predict future values based on previously observed values. While regression analysis is often employed in such a way as to test relationships between one or more different time series, this type of analysis is not usually called "time series analysis", which refers in particular to relationships between different points in time within a single series. Interrupted time series analysis is used to detect changes in the evolution of a time series from before to after some intervention which may affect the underlying variable.

# Goal

To predict Parameters 9-13 from the given dataset for every Section with the best accuracy.

# Packages Used

1) numpy
2) pandas
3) matplotlib
4) sklearn
5) random

# Models Used

1) Extra Trees Regressor
2) Random Forest Regressor

# Methodology Used

* Transformed the Data into Train and Test Dataset, by extracting 10th year data for para 9-13 for every section.

* Applied Extra Regressor Model to implement random forest and predicted the values.

* Calculated RMSE for the predicted values and plotted the graphs.

