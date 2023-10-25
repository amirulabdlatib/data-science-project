# Student Performance Prediction Using Linear Regression
This project is focused on predicting student performance using a linear regression model. The dataset used in this project is derived from student-mat.csv, containing various student attributes and their final grades.

## Data Exploration
* The dataset is loaded using pandas and consists of 395 rows and 33 columns.
* No missing data was found in the dataset, ensuring data completeness.
* The data includes both categorical and numerical features related to students' personal and academic backgrounds.

## Modelling
* Features like study time, number of failures, family relationship, absences, health, and previous grades (G1 and G2) are selected as independent variables (X) for the linear regression model.
* The final grade (G3) is chosen as the target variable (y).
* The data is split into training and testing sets for model evaluation.
* A Linear Regression model is trained on the training data and achieved an accuracy score of approximately 78.58% on the test data.

## Model Evaluation
* The model's predictions are compared to the actual final grades in the testing dataset.
* A scatter plot is created to visualize the relationship between true and predicted grades.
* A residual plot is generated to analyze the differences between predicted and true values.

## Conclusion
This project provides insights into how linear regression can be utilized to predict student performance based on various factors. It emphasizes the importance of choosing appropriate features to create an effective predictive model. Further enhancements and explorations can be made to improve the model's accuracy and better understand the factors influencing student performance.

Feel free to customize this summary to fit your project's specific details and context.
