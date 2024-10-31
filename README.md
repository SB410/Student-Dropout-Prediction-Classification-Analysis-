# Student-Dropout-Prediction-Classification-Analysis-
This project predicts student dropout rates using demographic, academic, and financial data. After cleaning and feature engineering, we tested several models, with Random Forest performing best. The model identifies at-risk students, supporting educational institutions in improving retention.

Project Overview
This repository contains code and documentation for the Student Dropout Prediction project, which aims to predict whether a student will drop out of their undergraduate program. Using multiple datasets, including student demographic, academic progress, and financial aid information, we apply machine learning models to forecast student dropout rates.

Dataset

	•	Static Data: Demographic and enrollment information for each student.
	•	Progress Data: Academic performance data for each term.
	•	Financial Aid Data: Student loans, scholarships, and other financial information.

Key Steps

	1.	Data Wrangling: Merging datasets by Student ID, cleaning missing values, and performing feature engineering.
	2.	Feature Engineering: Creating new variables, such as the moving average of financial data, and encoding categorical variables.
	3.	Modeling: Training various classification models (Random Forest, Gradient Boosting, Logistic Regression, and KNN) with hyperparameter tuning.
	4.	Evaluation: Evaluating model performance using metrics such as accuracy, precision, recall, and F1-score.
