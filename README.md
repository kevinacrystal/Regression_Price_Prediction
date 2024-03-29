# Project 2: Ames Housing

## Problem Statement

This project aims to build a price-prediction template based on data collected by the Ames, Iowa Assessor’s Office on individual residential properties sold in Ames, IA from 2006 to 2008.

## Executive Summary
### Methodology:
The project will refine a regression model, fit based on the Ames dataset, with the goal of minimizing root mean squared error, based on a holdout set.

### Contents:
- [01_EDA_and_Cleaning](https://github.com/kevinacrystal/Regression_Price_Prediction/blob/master/code/01_EDA_and_Cleaning.ipynb)
- [02_Preprocessing_and_Feature_Engineering](https://github.com/kevinacrystal/Regression_Price_Prediction/blob/master/code/02_Preprocessing_and_Feature_Engineering.ipynb)
- [03_Modeling](https://github.com/kevinacrystal/Regression_Price_Prediction/blob/master/code/03_Modeling.ipynb)


## Conclusions and Recommendations

Several regression models were tested, including Linear Regression, Lasso, Ridge, and ElasticNet.
The best performing model was Ridge, which acheived a root mean squared error of $22,227. This model also acheived good R-squared scores (0.939 on the training set, 0.921 on the testing set) which suggest slight overfitting.
