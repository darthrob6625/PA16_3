# Robert Meza
Link: [PA3.ipynb](PA3.ipynb)

## Module 17: Practical Application 3

### Problem Statement
The objective of this assignment is to construct and evaluate multiple machine learning classification models for the purpose of assessing marketing campaigns within a banking organization. Specifically, the models to be developed and optimized include k-nearest neighbors, logistic regression, decision trees, and support vector machines. 

### Business Objective
The banking organization has requested an evaluation of the effectiveness of its marketing campaigns in order to determine whether customers are likely to respond positively.

###  Project Workflow
- Data check
- Exploratory Data Analysis (EDA)
- Preprocessing
- Feature Selection
- Classification Modeling
- Results & Analysis

### Data Analysis
The dataset comprises 21 features and more than 40,000 records, including 10 numerical features and 10 categorical features. After one-hot encoding of the categorical variables, the total number of features, prior to evaluation and further processing, was ###. I also performed scaling for the numerical data **after** I split the data in test/train. 

### Evaluation & Findings

The following table summarizes the classification models, presenting both their initial baseline configurations and their optimized performance metrics.

| Classification Model | Simple Model Accuracy (Test) | Improvement Model Accuracy |
| --- | --- | --- |
| Logistic Regression | 90.6% | 90.7% |
| K-Nearest Neighbors | 89.9%  | 89.0% | 
| Decision Trees | 88.1% | 88.46% |
| Support Vector Machines | 90/0% | - |

The following table summarizes the strongest correlations.

| Strong correlations with target y: | Value |
| --- | --- |
| duration | 0.403 |
| pdays | -0.312 |
| previous | 0.211 |
| euribor3m | -0.318 |
| poutcome_success | 0.305 |

