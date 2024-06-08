# Bank-churn-modeling

In this project I explore customer churn for an European bank with the goal to build a model able to predict whether a customer of the bank will churn. If a customer churns, it means they left the bank and took their business elsewhere.

If we can predict which customers are likely to churn, we can take measures to retain them before they do. These measures could be promotions, discounts, or other incentives to boost customer satisfaction and, therefore, retention.

For that, I performed feature engineering on the raw dataset and applied different supervised classification modeling techniques (Naive Bayes, Decision Tree, Random Forest and XGBoost).

The analysis was performed in 5 steps, described below.


## Part 1 - Feature Engineering

Perform feature engineering on the dataset to prepare it for modeling using supervised classification models.

In this notebook I will:

* Perform feature selection by removing uninformative features.
* Perform feature extraction by creating new features from existing features.
* Perform feature transformation by modifying existing features to better suit my objectives, and by encoding of categorical features as dummies.

## Part 2 - Construct a Naive Bayes model

Build and test a Naive Bayes model to predict whether a customer will churn.

In this notebook I will:

* Perform feature engineering.
* Perform encoding of categorical features as dummies.
* Conduct stratification during data splitting.
* Fit a Naive Bayes model.
* Evaluate the model on test data using precision, recall, and F1 score.
* Build a confusion matrix of the model's predictions.

## Part 3 - Decision tree tuning & cross-validation

Build and test a Decision Tree model to predict whether a customer will churn.

In this notebook I will:

* Perform feature engineering.
* Perform encoding of categorical features as dummies.
* Perform stratification during data splitting.
* Fit a decision tree model.
* Build a confusion matrix of the model's predictions.
* Plot the decision tree and examining its splits.
* Evaluate the model using precision, recall, and F1 score. 
* Use `GridSearchCV` to cross-validate the model and tune the following hyperparameters:
  - `max_depth`  
  - `min_samples_leaf` 

## Part 4 - Random forest tuning & cross-validation

Build and test a Random Forest model to predict whether a customer will churn.

In this notebook I will:

* Perform feature engineering.
* Perform encoding of categorical features as dummies.
* Conduct stratification during data splitting.
* Fit a model.
* Perform model evaluation using precision, recall, and F1 score.
* Use `GridSearchCV` to cross-validate the model and tune the following hyperparameters:  
    - `max_depth`  
    - `max_features`  
    - `min_samples_split`
    - `n_estimators`  
    - `min_samples_leaf`  


## Part 5 - XGBoost tuning & cross-validation

Build and test an XGBoost model to predict whether a customer will churn.

In this notebook I will:

* Perform feature engineering.
* Perform encoding of categorical features as dummies.
* Conduct stratification during data splitting.
* Fit an XGBoost model.
* Use `GridSearchCV` to cross-validate the model and tune the following hyperparameters:
  - `max_depth`  
  - `min_child_weight`  
  - `learning_rate`  
  - `n_estimators`  
* Perform model evaluation using precision, recall, and F1 score.
* Build a confusion matrix of the model's predictions.
* Examine and plot feature importance.
