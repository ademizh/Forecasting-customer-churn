# Forecasting-customer-churn
This repository contains code for developing predictive models to predict customer churn using various machine learning algorithms including Logistic Regression, Decision Tree, Random Forest, AdaBoost, and Gradient Boosting. These models were trained and evaluated on a mid-sized dataset with the goal of achieving a high F1-score.

Algorithms
The following machine learning algorithms were implemented and evaluated:

Decision Tree
Random Forest
AdaBoost
Gradient Boosting

Evaluation Metric
The models were evaluated using the F1-score metric, which is a harmonic mean of precision and recall. F1-score is particularly useful in imbalanced datasets like customer churn prediction, where the number of churned customers might be significantly lower than non-churned customers.

Results
The models were trained and fine-tuned using cross-validation techniques to optimize their performance. After experimentation, the best-performing model achieved an F1-score of 89% on the test dataset.

Repository Structure
data/: Contains the dataset used for training and evaluation.
models/: Contains the trained models serialized in pickle format.
notebooks/: Jupyter notebooks used for data exploration, model development, and evaluation.
