# Car MultiClass Classification using Machine Learning and Deep Learning (ANN)
## Overview
This project focuses on classifying cars into different categories using a combination of machine learning models and an Artificial Neural Network (ANN). The goal is to predict the acceptability of cars based on various attributes, such as buying price, maintenance cost, number of doors, passenger capacity, luggage boot size, and estimated safety.

## Data Source
The dataset used for this project was obtained from Kaggle and is available at this link: https://www.kaggle.com/datasets/pranjalbatra/car-evaluation

# Evaluation
The models' performance is assessed using the following classification metrics:

* Accuracy Score
* F1 Score
*Precision Score
* Recall Score

## Key Steps
1.Exploratory Data Analysis (EDA): The initial data exploration phase involves checking for missing values, examining basic statistics, and visualizing the distribution of class labels.

2.Data Preprocessing: Categorical variables are encoded using label encoding, and the dataset is split into training and testing sets. Standardization is applied to ensure all features are on the same scale.

3.Model Selection: Various machine learning models are considered for the classification task, including Random Forest, Extra Trees, AdaBoost, K-Nearest Neighbors (KNN), and Support Vector Machine (SVM). The models are trained and evaluated based on accuracy scores.

4.Hyperparameter Tuning: The best-performing model, Random Forest, undergoes hyperparameter tuning using GridSearchCV to identify the optimal hyperparameters.

5.Artificial Neural Network (ANN): An ANN is constructed and trained for the classification task. The model architecture includes multiple dense layers with different activation functions. Early stopping is implemented to prevent overfitting.

6.Model Evaluation: The ANN model is evaluated, and the accuracy on the test data is reported. Training history is visualized to monitor model performance during training.

7.Confusion Matrix: A confusion matrix is generated to visualize the model's performance, showing true positives, true negatives, false positives, and false negatives for each class label.

## Model Performance
The best-performing model, Random Forest, achieved an accuracy score of approximately 91.1% after hyperparameter tuning. The ANN model also provided competitive results, showcasing the effectiveness of both traditional machine learning and deep learning approaches for car classification.

## Future Enhancements
For future work, you might consider further fine-tuning the ANN architecture, exploring more advanced deep learning techniques, and addressing the class imbalance issue in the dataset.
