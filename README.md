# Titanic Kaggle
A quick pipeline I put together for Kaggle's "Getting Started" competition - [Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/overview).
It includes:


1.   EDA
2.   Feature imputation via k-Nearest-Neighbours
3.   Feature generation
4.   Feature scaling
5.   Modeling via Logistic regression, Random forests, XGB, SVM, SGD.
6.   Cross-validated feature selection via feature importance
7.   Cross-validated hyperparameter tuning via
     * Bayesian optimization via HyperOpt
     * Grid Search
8.   Ensembling via
     * Voting classifier
     * Stacking with a Logistic Regression meta-learner
