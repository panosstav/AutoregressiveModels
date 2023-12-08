# Times Series Forecasting

Python Project

--- 

## Time Series Forecasting with SARIMAX and ARIMA Models

This repository contains a Python project focused on Time Series Forecasting using models:
- SARIMAX (Seasonal AutoRegressive Integrated Moving Average with eXogenous factors) and
- ARIMA (AutoRegressive Integrated Moving Average) 

The purpose is to forecast a six-time series (no particular topic) using Python.

Time series forecasting is a crucial task in various domains such as finance, economics, and environmental science. 
This project provides an in-depth demonstration of how to implement SARIMAX and ARIMA models for accurate time-series predictions.

Scripts:
- sarimax.ipynb
- arima.ipynb

Data:
- test_sample.xlsx
- train_sample.xlsx
- sample_submission.xlsx

The data files showcase the desirable format, not the values used.

--- 

## Getting Started
Welcome to the world of time series forecasting using ARIMA and SARIMAX models. 
This guide will help you get started with forecasting time series data efficiently.

### Prepare Data
Before running the code, make sure you have the necessary data files ready:
- Place your time series training data in a CSV file named train.csv
- Place your time series test data in a CSV file named test.csv
- If you have exogenous variables, include them in a separate CSV file named exogenous.csv

### Install Dependencies

Install the required Python packages using Pip by running:

```pip install -r requirements.txt```

### ARIMA Forecasting

Train an ARIMA Model
1. Open and run the provided Jupyter Notebook or Python script for ARIMA time series forecasting. The code will guide you through the following steps:
- Data preprocessing
- ARIMA model selection (p, d, q parameters)
- Model training
- Model evaluation, which includes MAE (Mean Absolute Error) and RMSE (Root Mean Square Error).

2. After training the ARIMA model, it will be ready for making predictions.

### SARIMAX Forecasting

Train a SARIMAX Model
1. Open and run the provided Jupyter Notebook or Python script for SARIMAX time series forecasting. The code will guide you through the following steps:
- Data preprocessing, including handling exogenous variables
- SARIMAX model selection (p, d, q, P, D, Q, s parameters)
- Model training
- Model evaluation, which includes MAE (Mean Absolute Error) and RMSE (Root Mean Square Error)

2. After training the SARIMAX model, it will be ready for making predictions.

### Make Predictions
1. Utilize the trained ARIMA or SARIMAX models to make predictions on your test data.

2. If you included exogenous variables in SARIMAX, provide them as inputs when making predictions.

3. Evaluate the forecasted results using appropriate metrics and visualize the forecasts alongside the actual data.

--- 

## Prerequisites
- **Python 3.6+**: You need Python installed on your system to run the code.
- **Pip**: Ensure you have Pip (Python package manager) installed.

Libraries used:
- seaborn
- pandas

--- 

## Usage
Here's how you can use the ARIMA time series forecasting code:

1. Data Preparation: Ensure you have the necessary data files:   
- Place your training data in a CSV file named train.csv
- Place your test data in a CSV file named test.csv
- A sample submission CSV file should be named sample_submission.csv

3. Running the Code: Open and run the provided Jupyter Notebook or Python script to perform time series forecasting using ARIMA.
4. Model Evaluation: The code includes model evaluation, which will display the Mean Absolute Error (MAE) and Root Mean Square Error (RMSE) for each ARIMA model.
5. Generating Predictions: After training the ARIMA models, predictions for the test data will be generated and saved.
6. Submission: The predictions can be submitted to a competition or used for further analysis.

--- 

## Future work
Future work would be Time Series Forecasting with SARIMA (Seasonal AutoRegressive Integrated Moving Average) model.
