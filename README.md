# Machine Learning Journey – Advertising Revenue Prediction

## Overview

This repository documents my hands-on journey into Machine Learning through a series of progressively more advanced projects. Rather than following isolated tutorials, the objective is to understand the reasoning behind each algorithm, evaluate different modelling techniques, and build projects that resemble real business problems.

The project (version 2 onwards) uses a synthetic digital marketing dataset to predict advertising revenue from campaign metrics such as media spend, impressions, CTR and CPC.

Each notebook builds upon the previous one, introducing additional concepts commonly used by Data Scientists and Machine Learning Engineers.

---

## Notebook 1 – Foundations of Regression: Boston Housing Price Prediction

This was my first end-to-end Machine Learning project, built using the classic Boston Housing dataset.

### Topics Covered:

* Understanding supervised learning (regression)
* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* Train-test split methodology
* Linear regression modelling

Key Takeaway:

This project established the foundational pipeline for Machine Learning workflows and introduced the concept of predicting continuous numerical outcomes using statistical models.

## Notebook 2 – Regression Model Optimisation & Validation (Marketing Mix Dataset)

This project extended the initial regression pipeline into a full model selection and validation framework using a synthetic marketing dataset.

### Topics Covered:

* Polynomial feature engineering
* Pipeline construction using Scikit-learn
* K-Fold Cross Validation
* ShuffleSplit validation strategy
* GridSearchCV for hyperparameter tuning
* Bias-variance trade-off analysis
* Permutation feature importance
* Residual diagnostics and error analysis

Key Takeaway:

This project demonstrated how model complexity impacts generalisation performance and how robust validation techniques are essential for selecting reliable models in real-world scenarios.

## Notebook 3 – Regularisation & Model Generalisation

This project represents a complete Machine Learning learning path built across three structured notebooks. Together, they form an end-to-end journey from foundational regression concepts to advanced model validation and regularisation techniques used in real-world data science workflows.


## Notebook 3A – Advertising Revenue Prediction

**Objective**

Build a complete regression pipeline from scratch using synthetic marketing campaign data.

### Topics Covered

* Exploratory Data Analysis (EDA)
* Feature Engineering
* Train/Test Split
* Linear Regression
* Random Forest Regression
* Cross Validation
* Model Evaluation (R², MAE, RMSE)
* Feature Importance
* Predicting revenue for new campaigns

---

## Notebook 3B – Model Selection & Validation

**Objective**

Improve the initial model by introducing non-linear relationships, validating model performance using multiple evaluation strategies, and understanding model complexity.

### Topics Covered

* Polynomial Regression
* Pipelines
* K-Fold Cross Validation
* ShuffleSplit Validation
* GridSearchCV
* Hyperparameter Tuning
* Residual Analysis
* Cross Validation Predictions
* Permutation Importance
* Model Complexity Analysis
* Degree Optimisation using Python Loops

---

## Notebook 3C – Regularized Regression *(in pipeline)*

The final notebook in this trilogy will focus on selecting robust regression models and understanding the trade-off between model complexity and generalisation.

Planned topics include:

* Ridge Regression
* Lasso Regression
* Elastic Net
* RidgeCV
* LassoCV
* ElasticNetCV
* Bias-Variance Trade-off
* Learning Curves
* Validation Curves
* Coefficient Interpretation
* Automated Model Comparison
* Professional Regression Pipeline

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## Learning Philosophy

The purpose of this repository is not simply to train models, but to understand *why* each technique is used, the mathematical intuition behind it, and when it should be applied in real-world Machine Learning projects.

Each notebook includes detailed explanations, observations and commentary to reinforce the concepts learned throughout the project.

---

## Future Work

Following the completion of the regression trilogy, future projects will explore:

* Classification
* Ensemble Learning
* Gradient Boosting (XGBoost & LightGBM)
* Model Explainability (SHAP)
* Machine Learning Deployment
* Real-world Marketing Analytics
* Generative AI applications

---

Thank you for visiting this repository. Feedback and suggestions are always welcome as I continue developing my Machine Learning portfolio.
