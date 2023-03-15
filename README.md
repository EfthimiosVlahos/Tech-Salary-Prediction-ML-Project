# Tech-Salary-Prediction-ML-Project

## Project Overview
How much should someone earn based on level education and experience? Despite the fact that salary may not always be the primary (nor even the secondary or tertiary) motivation for accepting a job offer or staying in a role.
- Predict a continuous dependent variable from a number of independent variables using a regression model. The dataset was taken from [Stack Overflow Annual Developer Survey 2021](https://insights.stackoverflow.com/survey)
- Data transformation and machine learning to create a model that predicts a salary based on: country of residence, profession (job type), education level and years of experience. Access the full Python code [here](https://github.com/EfthimiosVlahos/Tech-Salary-Prediction-ML-Project/blob/master/salary_prediction_regression_ML.ipynb).

## Objectives
* The objective is to make accurate salary predictions based on existing known salaries by job and location. As a result, the model can help companies and existing/future employees to negotiate more competitive payments. For HR professionals, leaders and recruiters, salary is a matter from company success (and budget) perspective. For employees and job seekers, it is important for reasons that go beyond employment.

## Methodology
- Data Wrangling - `Dropped misssing or null salaries values in the dataset, replacing the Years of Experience to the mean and analyzed/removed outliers.`
- Exploratory Data Analysis - `Analyzed the data and summarized the main characteristics.`
- Data Visualization - `Used boxplot, bar plot, scatter plot and violin plot to visualize the data and it's characteristics.`
- Machine Learning Algorithms - ` The models trained were: Lasso, ElasticNet, Decision Tree Regressor, KNeighbors Regressor, Random Forest Regressor and Gradient Boosting Regressor.`
- Evaluation Metrics Used - `Mean Absolute Error (MAE) and R-squared`

## Conclusions
Gradient Boosting Regressor Model resulted in a better performace applying prepocessing steps (Standard Scale, One Hot Encoding and Ordinal Coding) for specific features. The Model Evaluation resulted: **Mean Absolute Error of 13,612.26 and R-squared of 75.8%.**
