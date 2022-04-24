# Welcome to GOT repository

## About

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on a TV series called Game of Thrones. 
The hit series Game Of Thrones is very well-known for its fascinating plot and diverse characters, achieving high success in retaining viewership rates up until its final season. Thus, we are motivated to investigate the reasons behind the shows’ success. The detailed walkthrough is as follows. We first searched for a dataset on Kaggle and did data visualisation and exploratory data analysis. Then we cleaned the data and picked some variables to build a binary classification model. We first used a decision tree and found that accuracy as measured by AUC was low  and thus learned some new models to improve on our prediction model including Cost Complexity Pruning (CCP), Random Forest, Random Forest with Feature Selection, XGBoost, XGBoost with GridSearchCV and Light GBM.

## Problem Definition
- We will build and evaluate various machine learning models to understand the relationship between different variables in the dataset and mortality of characters(happy ending). 
- Through modeling the success of Game of Thrones, we will then derive several data-driven insights that can be used to recommend ways for other TV shows in the entertainment industry to enhance and retain their viewership rates as well.

## Machine Learning Models Used

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
- Pure decision tree is a naive ML method in this case, we can do Cost Complexity Pruning (CCP), Random Forest, XGBoost and LightGBM to improve it. 
- Other ways to improve the model in terms of efficiency include "Halving" the algorithms (Halving GridSearch) and feature selection (where you sacrifice accuracy for a low cost trade-off to gain higher efficiency through predicting the response variable with significantly lesser features) 
- Killing popular characters potentially increases viewership rate as they are shocking and stimulate conversation online.

## What did we learn from this project?

- CCP, Random Forest(with feature selection), XGBoost and XGBoost with GridSearchCV
- Resampling methods (SMOTENC) 
- Collaborating using GitHub
- Concepts about Precision, ROC AUC, and F1 Score

## References
- https://medium.com/@peterworcester_29377/a-comparison-of-grid-search-and-randomized-search-using-scikit-learn-29823179bc85#:~:text=Once%20again%2C%20the%20Grid%20Search,instead%20perform%20a%20Randomized%20Search (A comparison of Grid Search and Randomized Search using ScikitLearn)
- https://towardsdatascience.com/xgboost-fine-tune-and-optimize-your-model-23d996fab663 (XgBoost Fine Tune and Optimize your model)
- https://machinelearningmastery.com/light-gradient-boosted-machine-lightgbm-ensemble/ (Light Gradient Boosted Machine LightGBM Ensemble)
