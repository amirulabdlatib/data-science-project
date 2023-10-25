# Job Placement Prediction
## Overview
This project aims to predict job placement for fresh graduates using machine learning. It addresses the growing need for accurate and efficient recruitment and selection methods for job placements. The project leverages past data and machine learning to predict whether a candidate will get placed.

## Dataset
The dataset used for this project is sourced from (Kaggle)[https://www.kaggle.com/datasets/ahsan81/job-placement-dataset]. It includes various features, such as gender, educational percentages, board of education, subjects studied, work experience, test scores, and more. The target variable is "status," which indicates whether a candidate was placed.

## Evaluation
The project aims to achieve a prediction accuracy of 90% in determining whether a candidate will be placed.

## Exploratory Data Analysis
Initial data exploration was conducted, which included checking for missing values, data types, and summary statistics. Visualizations were used to analyze the impact of various features, such as gender, work experience, specialization, and more, on job placement.

## Correlation Analysis
Correlation analysis was performed to identify influential features for job placement prediction. Key features include specialization, employment test scores, degree percentages, and more, with correlations of ±0.1 or greater with the target variable.

## Modelling
Several machine learning models were evaluated for their job placement prediction accuracy, including LinearSVC, k-Neighbors Classifier, and ensemble classifiers (RandomForestClassifier and ExtraTreesClassifier). The ExtraTreesClassifier exhibited the highest accuracy.

The ExtraTreesClassifier was further fine-tuned using RandomizedSearchCV and GridSearchCV. The best parameters for the model were identified through these processes.

## Model Accuracy

* Default model accuracy: 83.0%
* RandomizedSearchCV model accuracy: 80.23%
* GridSearchCV model accuracy: 82.6%

## Model Deployment
The best model (default model) was saved for future use. It can now be used to make job placement predictions for new data.

Feel free to customize this summary and include additional information or sections in your README.md. Good luck with your project on GitHub!
