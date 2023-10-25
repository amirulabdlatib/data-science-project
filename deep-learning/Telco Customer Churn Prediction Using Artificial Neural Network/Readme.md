# Telco Customer Churn Prediction Using Artificial Neural Network
This project aims to predict customer churn in a telecommunication company using an Artificial Neural Network (ANN) implemented with TensorFlow. The dataset used for this project is sourced from Kaggle.

## Data
The dataset contains information about telco customers and includes the following features:

* Churn (the target variable): Customers who left within the last month.
* customers have signed up for various services, such as phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies.
* Customer account information, including tenure, contract type, payment method, paperless billing, monthly charges, and total charges.
* Customer demographic information, including gender, age range, and whether they have partners and dependents.
* The dataset comprises 7043 rows and 21 columns.

## Exploratory Data Analysis (EDA)
* Initial data exploration using pandas, numpy, and visualization libraries to understand the dataset's structure.
* Analysis of the distribution of churned and non-churned customers.
* Examination of the relationship between gender and churn.
* Visualization of contract distribution and other factors.
* Analysis of tenure and monthly charges distribution using histograms and box plots.

## Data Cleaning
* Dropped the "customerID" column as it was useless for the project.
* Examined and converted data types where necessary.
* Handled missing values in the "TotalCharges" column.
* Encoded categorical variables using LabelEncoder.

## Correlation Analysis
* Calculated the correlation between features and the target variable (Churn).
* Visualized the correlation matrix using a heatmap to identify essential features.

## Modeling with TensorFlow
* Created an ANN model using TensorFlow and Keras.
* Split the data into training and testing sets.
* Trained the ANN model and evaluated its performance using binary cross-entropy loss and accuracy metrics.
* Generated classification reports to assess the model's performance.

## Handling Imbalanced Dataset
Addressed the issue of imbalanced data using oversampling of the minority class. This technique improves the model's performance on predicting customer churn.
