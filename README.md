# RegressionModels
Data Science Procedures for Regression Models
There are various kinds of regression techniques available to make predictions. These techniques are mostly driven by three metrics (number of independent variables, type of dependent variables and shape of regression line)

What are the types of Regressions?
- Linear Regression
- Logistic Regression (classification therefore, out of scope)
- Polynomial Regression
- Stepwise Regression (not required)
- Ridge Regression
- Lasso Regression
- ElasticNet Regression -- TODO
- Robust Regression (Huber & Random Sample Consensus RANSAC & Theil Sen Regression Models) -- TODO

Features of Regression Models <br>
There must be linear relationship between independent and dependent variables
Multiple regression suffers from multicollinearity, autocorrelation, heteroskedasticity.
Linear Regression is very sensitive to Outliers. It can terribly affect the regression line and eventually the forecasted values.
Multicollinearity can increase the variance of the coefficient estimates and make the estimates very sensitive to minor changes in the model. The result is that the coefficient estimates are unstable
In case of multiple independent variables, we can go with forward selection, backward elimination and step wise approach for selection of most significant independent variables.
It is generally good to normalise the features for regression - Anything from the Gaussian family will be underpinned by the normality assumption

## Project Title
Application of Regression models to predict maximum temperature - Lasso & Ridge Regression

## Motivation
- Set up a regression machine learning model pipeline for Linear/Polynominal/Rigge & Lasso Regression Models and evaluation of performance
- Use different EDA tools (sweetviz) 
- Implementation quick methods for analysis of interaction terms
- Implement a methods to determine optimal polynominal terms for features 
- Learn how to use learning curves to determine model improvements

## Build Status
Project in Development - Further Regression Methods may be added 

## Getting Started
Python version: 3.6.5
Notebooks: 20201222_Regularised_Linear_Models_WeatherWW2

Additional Notes:
There is a quick methods to save requirements from the notebook by running pip3 freeze > requirements.txt once the project has been completed

### Installing
cd Documents/GitHub/RegressionModels/
source GLM_WWII_env/bin/activate
python -m pip install -r requirements.txt

### Running the tests
Not implemented

**Break down into end to end tests** 
## Deployment
Not implemented

## Screenshots
Not implemented

## Versioning
Not implemented
