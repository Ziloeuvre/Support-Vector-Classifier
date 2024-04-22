Exploratory Data Analysis (EDA) on Heart Dataset and Usage of SVC Model for Heart Disease Prediction
Overview
This repository contains code and documentation for performing Exploratory Data Analysis (EDA) on a heart disease dataset and utilizing a Support Vector Classifier (SVC) model to predict the presence of heart disease.

The dataset used for this analysis contains various attributes related to heart health, such as age, sex, chest pain type, resting blood pressure, cholesterol levels, and more.

Contents
heart.csv: The dataset used for analysis.
heart_eda.ipynb: Jupyter Notebook containing the EDA process.
heart_prediction.ipynb: Jupyter Notebook demonstrating the usage of SVC model for heart disease prediction.
README.md: Documentation providing an overview and usage instructions.
Exploratory Data Analysis (EDA)
The EDA process involves:

Loading the dataset.
Cleaning and preprocessing the data.
Analyzing the distribution of features.
Investigating correlations between variables.
Visualizing key insights using plots and charts.
The EDA helps in understanding the dataset and identifying patterns or trends that may be relevant for predicting heart disease.

Usage of SVC Model for Heart Disease Prediction
The SVC model is utilized for predicting the presence of heart disease based on the features available in the dataset. The usage involves:

Splitting the dataset into training and testing sets.
Scaling the feature variables.
Performing hyperparameter tuning using GridSearchCV.
Training the SVC model with the best hyperparameters.
Making predictions on the testing set.
Evaluating the model performance using accuracy score.
The SVC model is chosen for its ability to handle non-linear classification tasks and its flexibility in handling high-dimensional data.

Requirements
Python 3.x
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
scikit-learn