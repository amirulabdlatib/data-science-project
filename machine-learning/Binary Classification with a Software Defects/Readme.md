# Kaggle Competition: Playground Series - S3E23 -- Placed as Top 51%
## Overview
This repository contains my submission for the Kaggle competition "Playground Series - S3E23." The goal of this competition is to predict defects in a dataset containing software-related metrics.

[Competition Link](https://www.kaggle.com/competitions/playground-series-s3e23)


## Project Structure
The project is structured as follows:

* train.csv: The training dataset containing software metrics and target labels.
* test.csv: The test dataset for making predictions.
* Prediction3.csv: The CSV file containing predictions on the test data.
* Notebooks/: Jupyter notebooks containing the code used for data exploration, preprocessing, modeling, and prediction.

## Model Selection
I explored three machine learning models for this competition:

1. CatBoost: I used grid search to optimize hyperparameters and achieved an AUC of 0.7840.
2. XGBoost: This model achieved an AUC of 0.7799 without hyperparameter tuning.
3. XGBoost Random Forest: I used this model, which achieved the highest AUC of 0.7874 on the test data.

## Instructions
To reproduce the results and run the code:

1. Clone this repository to your local machine.
2. Install the required libraries, including CatBoost and XGBoost.
3. Run the Jupyter notebooks in the Notebooks/ directory in the specified order.
4. Make predictions on the test data using the selected model (in this case, XGBoost Random Forest).
5. Prepare the predictions in the Kaggle submission format and submit your results to the competition.

## Kaggle Submission
The predictions for the test data have been placed in the Prediction3.csv file. You can use this file to submit your predictions to the Kaggle competition.

## Results
The best model, XGBoost Random Forest, achieved an AUC score of 0.79173 on the leaderboard, which was the basis for my Kaggle competition submission (858/1702) Top 51%.

Good luck, and feel free to explore the code and adapt it for your own use!
