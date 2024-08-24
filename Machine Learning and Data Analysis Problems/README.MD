# Machine Learning Techniques and Data Analysis with Python

This repository contains solutions to various machine learning and data analysis problems, providing practical examples and detailed explanations of fundamental techniques and concepts.

## 1. K-Nearest Neighbors (KNN) and Decision Trees

### Description:
- **Objective:** Analyze customer default status using machine learning models.
- **Tasks:**
  - **K-Nearest Neighbors (KNN):** Implemented KNN with \( K=3 \) using Manhattan distance to predict the class of a new sample.
  - **Decision Tree:** Constructed a decision tree using entropy as a purity measure to predict the class of a sample.
  - **Comparison:** Discussed the resilience of KNN versus Decision Trees to irrelevant features in datasets.

### Tools Used:
- Python
- `scikit-learn` for implementing KNN and Decision Trees

## 2. Support Vector Machines (SVM)

### Description:
- **Objective:** Work with a 2D plane to separate two classes using SVM.
- **Tasks:**
  - **Linear Decision Boundary:** Used SVM logic to create a linear decision boundary.
  - **Slope and Intercept:** Calculated and identified the slope and intercept of the decision boundary.
  - **Support Vectors:** Identified the support vectors that determine the decision boundary.

### Tools Used:
- Python
- `scikit-learn` for SVM implementation

## 3. Hierarchical Clustering

### Description:
- **Objective:** Perform hierarchical clustering on 2D data points.
- **Tasks:**
  - **Clustering Implementation:** Performed hierarchical clustering using Manhattan distance.
  - **Dendrogram Construction:** Visualized the clustering process with a dendrogram.
  - **Outlier Detection:** Discussed the ability of hierarchical clustering to detect outliers.
  - **Dendrogram Pruning:** Explained methods to prune the dendrogram for clearer results.

### Tools Used:
- Python
- `scipy` and `matplotlib` for clustering and dendrogram visualization

## Bonus Questions

### Topics Covered:
- **Bias-Variance Trade-Off:** Discussion on the trade-off between bias and variance, and its impact on overfitting and underfitting.
- **Confusion Matrix:** Definition of the confusion matrix, its components, and the information it provides.
- **ROC Curve:** Explanation of the ROC curve, its role in evaluating model performance, and interpretation.
- **Regularization:** Description of regularization techniques and examples of how they prevent overfitting.

## Dataset

### Files:
- **train.csv:** Contains the training data with features and labels.
- **test.csv:** Contains the test data for model evaluation.

### Dataset Description:
- **train.csv:** Includes various attributes relevant to the problem, used for training machine learning models.
- **test.csv:** Contains features only, used for predicting outcomes and evaluating model performance.


