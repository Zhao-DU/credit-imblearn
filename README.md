# Goal

The purpose of this repo is to test ideas about statistical learning methods on imbalanced datasets, including: 

- Oversampling/Undersampling (Random, SMOTE, ENN, TOMEK and various combinations of the two)
- Feature selection (chi2, forward/backward, XGBoost importance)
- Feature engineering (OneHot)
- Cross-validation (k-fold-stratified)
- Metric (F1, F2, PR-curve AUC)
- Cost-sensitive Models ((weighted) logistic regression, (weighted) SVM, (weighted) DecisionTree, XGBoost)
- Bayesian Hyperparameter Optimization (Optuna)

## Dataset 

- Dataset taken from https://online.stat.psu.edu/stat508/resource/analysis/gcd
