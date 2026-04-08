## Title
COMPARATIVE ANALYSIS OF RANDOM FOREST, XGBOOST, AND SGB FOR HEALTHCARE COST PREDICTION

## Objectives
- To compare the predictive performance of Random Forest, XGBoost, and SGB for healthcare cost prediction using demographic and lifestyle features.
- To analyze feature importance and SHAP explanations for each model, in order to understand which risk factors (such as smoking, age, BMI, and number of
children) drive healthcare costs.
- To provide practical guidance for insurers and healthcare stakeholders on which model and feature set are most suitable for risk estimation and cost
prediction in this type of tabular data.

## Dataset
- Public Health Insurance Cost dataset (Kaggle), 1,338 records of individual patients.
- Problem type: Supervised regression task to predict continuous healthcare costs.
- Consist of 7 variables: age, sex, bmi, children, smoker, region, charges

## Code Description 
- random_model.ipynb (random forest model code)
- sgb_model.ipynb (SGB model code)
- xgb_model.ipynb (XGB model code)
- fullinsurance.csv (dataset)

## Usage Instructions 
- Load Datasets provided
- Import the important tools (all provided in the code)
- Run the model

## Code Repository or DOI
[![DOI](https://zenodo.org/badge/1204950362.svg)](https://doi.org/10.5281/zenodo.19472029)


