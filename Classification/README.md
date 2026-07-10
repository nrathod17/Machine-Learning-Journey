
# Machine Learning Classification Journey: From Fundamentals to Ensemble Learning

## 📌 Overview

This repository documents my structured journey into Machine Learning, focusing on **supervised classification algorithms** and their practical application in a marketing and advertising analytics context.

The project follows a progressive learning approach — starting with foundational statistical models and gradually moving towards advanced machine learning techniques used in real-world predictive modelling.

Each notebook builds upon the previous one, applying consistent machine learning workflows:

* Data preparation
* Exploratory Data Analysis (EDA)
* Feature engineering
* Model development
* Validation strategies
* Performance evaluation
* Business interpretation

The datasets are based around synthetic marketing campaign scenarios, designed to replicate real-world advertising problems such as:

* Predicting user engagement
* Campaign success prediction
* Customer response modelling
* Marketing performance optimisation

---

# 🎯 Business Context

Working in the advertising industry, I wanted to explore how Machine Learning can support decision-making in areas such as:

* Identifying high-performing campaigns
* Predicting customer engagement
* Understanding important campaign drivers
* Improving targeting strategies

The projects use synthetic data to create realistic marketing scenarios while allowing full control over:

* Data generation
* Noise introduction
* Feature relationships
* Model behaviour analysis

---

# 📚 Notebook Roadmap

## Notebook 1 — Foundations of Classification: Logistic Regression

### Objective

Build the first end-to-end classification pipeline and understand probability-based prediction.

### Topics Covered

* Supervised classification fundamentals
* Logistic Regression
* Data preprocessing
* Train-test split
* Stratified sampling
* Classification metrics
* Confusion matrix
* Precision, Recall, F1 Score
* ROC Curve
* Precision-Recall Curve
* Logistic Regression coefficients
* Cross-validation
* L1/L2 regularisation

### Key Learning

Understanding how linear models classify outcomes and how model evaluation differs from regression problems.

---

# Notebook 2 — Distance-Based Learning: K-Nearest Neighbours

### Objective

Understand how predictions can be made based on similarity and distance between observations.

### Topics Covered

* Instance-based learning
* KNN Classification
* Euclidean distance (L2)
* Manhattan distance (L1)
* Feature scaling
* MinMaxScaler
* Encoding techniques
* Choosing optimal K
* Elbow method
* F1 score optimisation
* Weighted KNN
* Decision boundaries
* KNN Regression
* Curse of dimensionality
* Memory complexity

### Key Learning

Understanding why distance-based algorithms require scaling and how local patterns can create flexible decision boundaries.

---

# Notebook 3 — Support Vector Machines (Maximum Margin Classification)

### Objective

Explore maximum-margin classification and kernel-based learning.

### Topics Covered

* LinearSVC
* SVC
* Maximum margin principle
* Support vectors
* Soft margin classification
* Regularisation parameter (C)
* Gaussian/RBF kernel
* Gamma parameter
* Kernel trick
* Decision boundaries
* Nystroem approximation
* RBFSampler
* Pipeline workflows
* Model validation

### Key Learning

Understanding how models can create complex boundaries by transforming the feature space.

---

# Notebook 4 — Rule-Based Learning: Decision Trees (In Pipeline)

### Objective

Understand interpretable machine learning models based on decision rules.

### Topics Covered

* DecisionTreeClassifier
* DecisionTreeRegressor
* Recursive splitting
* Gini Index
* Entropy
* Information gain
* Classification error
* Tree visualisation
* Feature importance
* Overfitting
* Tree pruning
* Cost complexity pruning
* Hyperparameter tuning
* Graphviz export

### Key Learning

Understanding how models learn human-readable decision rules and why controlling complexity is essential.

---

# Notebook 5 — Ensemble Learning (In Pipeline)

### Objective

Understand how combining multiple models improves predictive performance.

### Topics Covered

## Bagging

* Bootstrap sampling
* BaggingClassifier
* Variance reduction

## Random Forest

* RandomForestClassifier
* RandomForestRegressor
* Feature randomness
* Out-of-Bag evaluation
* Feature importance

## Extra Trees

* Extremely Randomised Trees
* Random feature selection

## Voting Models

* Hard voting
* Soft voting
* Combining multiple learners

## Boosting

* Decision stumps
* AdaBoost
* Gradient Boosting
* Loss functions
* Residual learning
* GradientBoostingClassifier
* GradientBoostingRegressor
* XGBoost introduction

## Evaluation

* ROC Curve
* Precision-Recall Curve
* Cross validation
* Model comparison

### Key Learning

Understanding how ensembles reduce errors by combining multiple weak learners into stronger predictive systems.

---

# 🛠️ Technologies Used

## Programming

* Python

## Libraries

* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost

## Machine Learning Techniques

* Classification
* Regression
* Model evaluation
* Feature engineering
* Cross validation
* Hyperparameter tuning
* Ensemble modelling

---

# 📂 Repository Structure

```
Machine-Learning-Classification-Journey/

│
├── Notebook_1_Logistic_Regression.ipynb
│
├── Notebook_2_KNN.ipynb
│
├── Notebook_3_SVM.ipynb
│
├── Notebook_4_Decision_Trees.ipynb
│
├── Notebook_5_Ensemble_Methods.ipynb
│
└── README.md
```

---

# 📈 Learning Progression

The progression follows increasing model complexity:

```
Logistic Regression
        ↓
K-Nearest Neighbours
        ↓
Support Vector Machines
        ↓
Decision Trees
        ↓
Ensemble Learning
```

Each algorithm introduces a different way of learning from data:

| Algorithm           | Learning Approach                  |
| ------------------- | ---------------------------------- |
| Logistic Regression | Probability-based linear modelling |
| KNN                 | Similarity and distance            |
| SVM                 | Maximum margin separation          |
| Decision Tree       | Rule-based splitting               |
| Ensembles           | Combining multiple learners        |

---

# 🚀 Future Development

Planned extensions:

* Naive Bayes
* Unsupervised Learning

  * K-Means
  * DBSCAN
  * PCA
* Advanced Model Selection

  * GridSearchCV
  * RandomizedSearchCV
  * Pipeline optimisation
* Model Explainability

  * SHAP
  * Feature importance analysis
* End-to-end Marketing Prediction Project

---

# 📌 Final Reflection

This repository represents my transition from learning individual machine learning algorithms to understanding complete modelling workflows.

The focus is not only on achieving predictions, but understanding:

* Why an algorithm works
* When to use it
* Its limitations
* How to evaluate it properly
* How it applies to real business problems

Machine Learning is not only about selecting models — it is about understanding the relationship between data, assumptions, evaluation, and decisions.
