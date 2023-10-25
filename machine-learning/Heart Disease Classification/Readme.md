# Heart Disease Prediction

## Overview
This project is aimed at predicting the presence of heart disease in individuals using machine learning techniques. The dataset used contains various medical attributes like age, sex, cholesterol levels, and more, making it a valuable resource for early diagnosis of heart disease.

## Model Building
Logistic Regression
We started by implementing a logistic regression model and fine-tuned its hyperparameters using both RandomizedSearchCV and GridSearchCV. The best hyperparameters for our logistic regression model were found to be C=0.38566204211634725 and solver='liblinear'. The model achieved an accuracy of approximately 0.852 on the test set.

### Random Forest Classifier
We also explored the Random Forest Classifier, and after hyperparameter tuning, the best parameters were n_estimators=560, min_samples_split=12, min_samples_leaf=15, and max_depth=3. This model also achieved an accuracy of approximately 0.869 on the test set.

### Model Evaluation
We went beyond simple accuracy and performed a comprehensive evaluation of our models:

* ROC Curve and AUC Score: We visualized the ROC curve and calculated the AUC metric to assess binary classification performance.

* Confusion Matrix: A confusion matrix was generated to understand true positives, true negatives, false positives, and false negatives.

* Classification Report: This report provided precision, recall, and F1-score for both classes, offering a more detailed view of model performance.

* Cross-Validation: We used cross-validation to ensure the robustness of our models. The cross-validated metrics included accuracy, precision, recall, and F1-score.

* Feature Importance: For the logistic regression model, we examined feature importance to understand which attributes contributed most to the predictions.

## Conclusion
This project demonstrates a comprehensive approach to building and evaluating machine learning models for heart disease prediction. It not only provides accurate predictions but also offers insights into the factors contributing to the risk of heart disease.

For more details, refer to the Jupyter Notebook and Python code provided in this repository.
