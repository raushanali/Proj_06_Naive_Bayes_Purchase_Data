# Proj_06_Naive_Bayes_Purchase_Data

This project uses a Naive Bayes classifier to predict whether a user will purchase a new car based on their age and estimated salary. The model is trained on a dataset of social network users, where the target variable indicates if the user purchased a car (1 = Yes, 0 = No).

Dataset
The dataset (Purchase_Logistic.csv) contains 400 entries with the following columns:

User ID

Gender

Age

EstimatedSalary

Purchased (Target: 1 = Purchased, 0 = Not Purchased)

Only the Age and EstimatedSalary features are used for prediction.

Purpose
Predict the likelihood of a user purchasing a car using demographic data.

Demonstrate the use of the Naive Bayes classification algorithm.

Evaluate the model using a confusion matrix and accuracy score.

Visualize both the original data and model predictions.

Features
Data Processing: Feature scaling using StandardScaler.

Model Training: Gaussian Naive Bayes classifier.

Evaluation: Confusion matrix and accuracy score.

Visualization: Data and predictions visualized with matplotlib.

Usage Instructions
Place the Dataset:
Ensure Purchase_Logistic.csv is in your project directory.

Install Required Libraries:
pip install pandas scikit-learn matplotlib

Requirements
Python 3.x

pandas

scikit-learn

matplotlib
