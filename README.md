Logistic Regression for Employee Retention
This project uses logistic regression to analyze HR data and predict whether employees are likely to leave the company. The analysis includes exploratory data analysis (EDA), feature selection, and model training using scikit-learn.

Dataset:
The dataset used is HR_comma_sep.csv and includes:

satisfaction_level

last_evaluation

number_project

average_montly_hours

time_spend_company

Work_accident

promotion_last_5years

Department

salary

left (Target variable: 1 = left, 0 = stayed)

Exploratory Data Analysis:
Plotted salary vs retention as a bar chart

Plotted department vs retention

Identified key features using correlation with left

Key Insights:
Low satisfaction and low salary are the strongest indicators of attrition.

Time spent at the company and promotion history also impact retention.

Model Building:
A Logistic Regression model was built using scikit-learn:

Steps:
Preprocessed the dataset

Encoded categorical columns (like salary)

Selected important features:

satisfaction_level

Work_accident

promotion_last_5years

time_spend_company

salary

Split data into training and test sets

Trained the model and predicted on test set

Measured model accuracy
