# Welcome to GOT repository

## About

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on a TV series called Game of Thrones. The detailed walkthrough is as follows. We first searched for dataset on Kaggle and did data visualisation and analysis. Then we cleaned the data and picked some variables to build a decision tree. We found that accuracy as measured by AUC was low  and thus learned some new models to improve, including Cost Complexity Pruning (CCP), Random Forest, XGBoost, XGBoost with GridSearchCV and Light GBM.

## Problem Definition

- Are we able to predict whether one character will die or not using some relevant variables?
- Which model would be the best to predict it?
- What are the data-driven insights?

## Models Used

1. Decision Tree Classification
2. Cost Complexity Pruning (CCP)
3. Random Forest Classification
4. Random Forest Classification with feature selection
5. XGBoost
6. XGBoost with GridSearchCV
7. Light GBM

## Conclusion

- Popularity is the strongest predictor for the response variable isAlive, followed by dateOfBirth, age and totalBooksin, and other variables are weaker predictors for isAlive.
- It is necessary to pick out some important variables with missing data and unreasonable outliers to fix them.
- Pure decision tree is a naive ML method in this case, we can do Cost Complexity Pruning (CCP), Random Forest, XGBoost, XGBoost with GridSearchCV and Light GBM to improve it.
- Killing popular characters potentially increases viewership rate as they are shocking and stimulate conversation online.

## What did we learn from this project?

- CCP, Random Forest(with feature selection), XGBoost and XGBoost with GridSearchCV
- Collaborating using GitHub
- Concepts about Precision, ROC AUC, and F1 Score

## References
- https://medium.com/@peterworcester_29377/a-comparison-of-grid-search-and-randomized-search-using-scikit-learn-29823179bc85#:~:text=Once%20again%2C%20the%20Grid%20Search,instead%20perform%20a%20Randomized%20Search (A comparison of Grid Search and Randomized Search using ScikitLearn)
- https://towardsdatascience.com/xgboost-fine-tune-and-optimize-your-model-23d996fab663 (XgBoost Fine Tune and Optimize your model)
- https://machinelearningmastery.com/light-gradient-boosted-machine-lightgbm-ensemble/ (Light Gradient Boosted Machine LightGBM Ensemble)
