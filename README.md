# Project 2: Ames Housing

## Problem Statement

This project aims to build a price-prediction template based on data collected by the Ames, Iowa Assessor’s Office on individual residential properties sold in Ames, IA from 2006 to 2008.

## Executive Summary
### Methodology:
The project will refine a regression model, fit based on the Ames dataset, with the goal of minimizing root mean squared error, based on a holdout set (train-test-split).

### Contents:
- [01_EDA_and_Cleaning](https://github.com/kevinacrystal/Regression_Price_Prediction/blob/master/code/01_EDA_and_Cleaning.ipynb)
- [02_Preprocessing_and_Feature_Engineering](https://github.com/kevinacrystal/Regression_Price_Prediction/blob/master/code/02_Preprocessing_and_Feature_Engineering.ipynb)
- [03_Modeling_Linear_Regression_and_Submission](https://github.com/kevinacrystal/Regression_Price_Prediction/blob/master/code/03_Modeling_Linear_Regression_and_Submission.ipynb)
- [04_Modeling_Lasso_Regression](https://github.com/kevinacrystal/Regression_Price_Prediction/blob/master/code/04_Modeling_Lasso_Regression.ipynb)

## Conclusions and Recommendations

Final features for the linear regression model included the following:  
Overall-Quality-Above-Ground-Living-Area-sqft (interaction term), Exterior Quality, Exterior Condition, Kitchen Quality, Garage Area, Total Basement Sq Ft, Basement Quality, Basement Condition, Fireplace Quality, Full Bath qty, Lot Shape, Utilities
