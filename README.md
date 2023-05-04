# FRED-timeseries

### Are we headed for a recession?

This code snippet is for data manipulation and visualization of time series data. It does not provide any direct predictive models for recession. However, the time series data used in the code, such as the yield curve data, can be used as one of the inputs for predictive models for recession.

In general, predicting a recession is a complex task that requires a comprehensive analysis of various economic indicators, such as GDP growth, unemployment rate, inflation rate, and consumer spending, among others. Time series analysis is one of the many tools that can be used to analyze and understand the patterns and trends in these economic indicators over time.

The time series data is read from a csv file, which is downloaded from https://fred.stlouisfed.org/searchresults?st=treasury.


### Classes

The lab includes the following classes:

- `TimeSeries`: This class holds a date/value series of data.
- `Difference`: This class represents a time series that is the difference between two other time series.
- `Fred`: This class is based on a csv file downloaded from fred.stlouis.org.
- `dgs3mo`: This class represents the 3-month treasury series from FRED.
- `dgs10`: This class represents the 10-year treasury series from FRED.

### Functions

The lab includes the following function:

`recession_visual`: This function plots a graphic visual showing the inverted yield curve.

