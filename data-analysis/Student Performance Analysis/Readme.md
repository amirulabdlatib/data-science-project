# Overview

This project aims to analyze the performance of students in a mathematics course using real-world data. The analysis covers data preprocessing and exploratory data analysis (EDA) to gain insights into the dataset. The dataset contains various student attributes and their final math grades (G3).

# Data Preprocessing

Imported necessary libraries, including pandas, matplotlib, seaborn, and scikit-learn's LabelEncoder.
Loaded the dataset from a CSV file and displayed the initial rows to understand the data structure.
Checked for missing data and found that there were no missing values in the dataset.
Encoded categorical variables like 'school,' 'sex,' 'address,' and 'internet' into numerical values using LabelEncoder.
Exploratory Data Analysis (EDA)
Analyzed the distribution of final math grades (G3), which showed an approximately normal distribution with a mean of 10.42, a median of 11.00, and a standard deviation of 4.58.
Explored how student gender (sex) correlates with their final math grades (G3) and found a weak positive correlation (0.103456), indicating a slight positive relationship between being female and achieving higher grades.
Investigated whether there was an age-related pattern in math performance and found a weak negative correlation (-0.16), suggesting that older students tend to achieve slightly lower grades in the math course.
Visualized the correlations between various dataset features using a heatmap to provide a comprehensive view of feature interrelationships.

#Usage

This analysis can serve as a foundation for further investigation into factors influencing student performance in mathematics.
The findings can be valuable for educational institutions, policymakers, or anyone interested in understanding the relationships between student attributes and academic achievement.
