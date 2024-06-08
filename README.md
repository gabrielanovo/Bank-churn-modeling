# Bank-churn-modeling

In this project I explore customer churn for an European bank with the goal to build a model able to predict whether a customer of the bank will churn. If a customer churns, it means they left the bank and took their business elsewhere.

If we can predict which customers are likely to churn, we can take measures to retain them before they do. These measures could be promotions, discounts, or other incentives to boost customer satisfaction and, therefore, retention.

For that, I performed feature engineering on the raw dataset and applied different supervised classification modeling techniques (Naive Bayes, Decision Tree, Random Forest and XGBoost).

The analysis was performed in 5 steps. The link to the Jupyter notebook for each part of the analysis is provided under each description.



The analysis is divided as follows:

## Part 1 - Feature Engineering

Perform feature engineering on the dataset to prepare it for modeling using supervised classification models.

In this notebook I will:

* Perform feature selection by removing uninformative features.
* Perform feature extraction by creating new features from existing features.
* Perform feature transformation by modifying existing features to better suit my objectives, and by encoding of categorical features as dummies.
