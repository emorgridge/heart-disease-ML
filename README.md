# heart-disease-ML
Classification on Heart Disease Dataset
# Brief & Summary:
## Aim:
Build a model using the ‘data.csv’ employing either R or Python, with the goal of predicting if an individual has heart disease.
## Summary:
**Data Cleaning**: I found 723 duplicates, and removed them after testing the dataset's efficacy in model training; corrected data object types, researched and found incorrect or missing data values in the data dictionary. Removed missing values
**Data Exploration and feature analysis**: Plotted density plots for numerical features (age, cholesterol, etc.) to see how they differ between individuals with and without heart disease. Created count plots for categorical features (sex, chest pain type, etc.) to visualise category distributions across heart disease groups. Utilised Point Biserial correlation, and cramer's v. Features have weak correlation with each other, and some show moderate correlations with the target variable.
**Model training**: Defined Ten baseline models, fitted and computed metrics (Accuracy, precision, recall, f1 score). I identified top performers and optimised parameters using Optuna
**Model Explainability**: Coefficient Plot for Logistic Regression, Permutation Importance for LightGBM and Random Forest
