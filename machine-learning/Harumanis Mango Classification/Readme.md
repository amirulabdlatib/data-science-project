# Harumanis Mango Classification
## Introduction
## About the Dataset
This project centers around a dataset containing physical measurements of Harumanis Mango (clone number MA 128). The dataset comprises 105 tabular entries, including weight, length, circumference, and grade. The data was collected from the Fruit Collection Center in FAMA Perlis, Malaysia. It is made available under the Attribution-ShareAlike 4.0 International (CC BY-SA 4.0) license.

## Problem Statement
The primary objective of this project is to classify and predict the grade of Harumanis Mango based on the provided physical measurements, such as weight, length, and circumference.

## Data
The dataset is accessible via this link on [Kaggle](https://www.kaggle.com/datasets/mohdnazuan/harumanis-mango-physical-measurement?select=data-2023-01-18.csv). The dataset consists of the following features:

* Weight: The weight of the mango in grams (g).
* Length: The length of the mango in centimeters (cm).
* Circumference: The circumference of the mango in centimeters (cm).
* 
The target variable is 'Grade,' which classifies the mangoes as class A or class B.

## Data Preparation and Exploration
The project begins by loading the dataset, exploring its features, and performing exploratory data analysis (EDA). This includes visualizing the distribution of weight, length, and circumference, as well as examining the frequency of grades in the dataset.

The project also includes outlier detection using box plots and correlation analysis to identify relationships between the features.

## Modelling
The following machine learning models are used for classification:

* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)
* Random Forest
* CatBoost Classifier
* XGBoost Classifier
* XGBoost Random Forest Classifier
* Random Forest is selected for fine-tuning based on its performance.

## Fine-Tuning
The Random Forest model is fine-tuned using GridSearchCV with 5-fold cross-validation. The optimal hyperparameters are determined, and the model's performance is evaluated.

## Model Evaluation
The project evaluates the model's performance using a classification report, confusion matrix, and cross-validated scores for accuracy, F1 score, recall, and precision.

## Decision Tree Visualization
A decision tree is visualized and saved as a JPG file, providing insights into how the model makes predictions.

## Feature Importance
Feature importance is determined, and a bar plot illustrates the significance of each feature in the Random Forest Classifier.

## Model Persistence
The trained Random Forest model is saved as 'rf_model.joblib' and 'rf_model.pkl' for future use.

This project aims to classify Harumanis Mango based on physical measurements, offering insights into the dataset and model performance.
