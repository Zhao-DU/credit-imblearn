# credit-XGboost
EDA, visualiazation and analysis of German Credit data


# Predictive analytics of German Credit dataset 
- sample size n = 1000
- response variable y_1 = 300, y_0 = 700

## Dataset 

- Dataset taken from Pennstate https://online.stat.psu.edu/stat508/resource/analysis/gcd
- 700:300 imbalanced dataset 


## Dimensionality reduction and visualization
- PCA
- tSNE
- Scatterplot matrix

## Sampling techniques/transforms
- Discretization of continuous variables  
- Feature selection using chi2 test
- Over/under sampling 
  - Random, TOMEK, SMOTE, ENN
- 10-fold stratified cross-validation 

## Metrics
- F2

## Models 
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost 

## Hyperparameter optimization
- Exhaustive and random gridsearch
- Bayesian optimization using Optuna (TPE)


