## Coronary Heart Disease (CHD) Risk Analysis
Statistical Modeling and Predictive Analysis of Cardiovascular Risk Factors

## Project Overview
This project provides a deep dive into the clinical determinants of Coronary Heart Disease (CHD) using a dataset of 462 patients. The objective is to identify key risk factors and build a predictive model to assist in medical screening and public health recommendations.


## Key Analytical Steps
Exploratory Data Analysis (EDA): Detailed study of distributions (skewness, outliers) and correlations between biological (LDL, BMI) and behavioral (tobacco, alcohol) variables.

Hypothesis Testing: * Student's t-test: Comparing LDL cholesterol levels between smokers and non-smokers.

Chi-squared Test: Analyzing the independence between smoking habits and CHD occurrence.

Statistical Modeling:

Simple Linear Regression: Studying the link between LDL and systolic blood pressure.

Multiple Logistic Regression: Identifying significant predictors of CHD through Odds Ratios and p-values.

Model Evaluation: Performance assessment using Cross-Validation, ROC Curves, and AUC to determine the optimal classification threshold.

## Key Findings & Recommendations
The model identified several major risk factors: Smoking, LDL levels, Family History, Type A personality score, and Age.
The project concludes with clinical recommendations, such as prioritizing screenings for individuals over 40 and systematic LDL monitoring.

## Tech Stack
Language: Python 

Libraries: Pandas, NumPy, Scikit-learn, Statsmodels, Matplotlib, Seaborn
