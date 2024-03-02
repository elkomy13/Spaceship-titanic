# Spaceship-Titanic-Project-Predicting Alternate Dimension Transport
This repository contains our solution for the Spaceship Titanic competition on Kaggle. The goal of this competition is to use machine learning to predict which passengers on the interstellar passenger liner Spaceship Titanic were transported to an alternate dimension during the collision with a spacetime anomaly.

# Data
The data consists of three CSV files:

train.csv: This file contains personal records of 10,000 passengers that were used to train the machine learning model. Each record has 12 features, including the target variable Transported, which indicates whether the passenger was transported to an alternate dimension (1) or not (0). test.csv: This file contains personal records for the remaining one-third (~4,300) of the passengers, but not the target variable. This file was used to make predictions and submit to Kaggle. sample_submission.csv: This file contains the format in which the predictions were submitted to Kaggle. It has two columns: PassengerId and Transported.

# Approach
The main steps of my approach are as follows:

Exploratory Data Analysis: we performed some basic data analysisto understand the data and identify any patterns, correlations, outliers, or missing values. Data Cleaning and Preprocessing: we dealt with the missing values, categorical variables, and outliers in the data. Feature Selection: we used a combination of domain knowledge, correlation analysis, and feature importance scores to select the most relevant features for the model. Model Building and Evaluation: we used a Light Gradient Boosting Machine(LGB) as my base model and tuned its hyperparameters using GridSearchCV. we also tried some other models, such as Logistic Regression, RandomForestClassifier, SVC, and XGBoost, and compared their performance using cross-validation and accuracy scores. we chose the best model based on the highest accuracy score on the validation set. Submission: we used the best model to make predictions on the test set and submitted the results to Kaggle. we achieved an accuracy score of ~0.81 on the public leaderboard, which ranked me among the top 17% of the participants.

# Conclusion
In this project, we applied various data science and machine learning techniques to predict which passengers on the Spaceship Titanic were transported to an alternate dimension. we used a Light Gradient Boosting Machine(LGB) as my best model and achieved an accuracy score of ~0.81 on the test set. we learned a lot from this competition and enjoyed the challenge of working with a fictional and futuristic dataset. we hope you find this project interesting and useful.
