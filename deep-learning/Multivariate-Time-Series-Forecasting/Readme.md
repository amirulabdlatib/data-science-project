
# Time Series Forecasting using LSTM Neural Network

## Problem Statement

Predicting the future values of revenue, sales quantity, average cost, and the average annual payroll of the region for the next 32 months based on historical data from January 1, 2015, to April 1, 2020.

## Data

The dataset includes key features:

*Revenue
*Sales Quantity
*Average Cost
*The Average Annual Payroll of the Region

## Methodology

1. Data Preparation
2. Load and visualize the time series data.
3. Split into training and forecasting sets.
4. Scale the data using MinMaxScaler.
5. Create time series generators for training and testing.
6. Modeling
7. Utilize an LSTM neural network with appropriate architecture.
8. Train the model using the Adam optimizer and mean squared error (MSE) loss function.
9. Implement early stopping to prevent overfitting.

## Evaluation

* Monitor the training process and visualize the loss.
* Generate test predictions and compare them with true values.
* Forecasting
* Retrain the model on the entire dataset for forecasting.
* Apply the trained model to predict the next 32 months' values.


## Results
The forecasted values for revenue, sales quantity, average cost, and the average annual payroll of the region for the next 32 months are stored in the forecast_df DataFrame.
