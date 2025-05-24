# Day-Ahead-Weather-Predictor

## Overview
The project includes a process for weather forecasting using a dataset containing various meteorological parameters over time. It begins by importing and exploring the dataset, including checking its shape, descriptive statistics, and correlations between features using a correlation heatmap. The data is then cleansed and preprocessed, checking for duplicates and null values before visualizing initial trends of the weather features over time, noting seasonality in temperature and dew point. Finally, the project demonstrates building and evaluating a forecast model using a Long Short-Term Memory (LSTM) network to predict hourly temperature, showing promising evaluation metrics.

## Data Details
The dataset used is from a private source and contains 35059 entries (rows) and 7 columns.The dataset includes the following weather parameters:
- time
- temperature
- dew_point
- wind_speed
- wind_direction
- visibility
- clouds.total

## Code
You can find the project code in the Notebook.ipynb file.
