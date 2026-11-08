Datheon Data Science & Machine Learning Internship

Welcome to my machine learning portfolio, developed during my remote internship at Datheon. This repository contains three end-to-end data science pipelines demonstrating my ability to transform raw data into actionable business intelligence using Python, Scikit-Learn, and XGBoost.

As a professional transitioning into Management Information Systems (MIS) and AI, my focus across these projects is not just on writing code, but on solving core business problems.

Repository Contents

This repository is divided into 3 core milestones:

1. Multi-Class Benchmark Classification Pipeline

Objective: Build a foundational classification model to categorize physical entities based on measurement data.

Dataset: Iris Benchmark Dataset

Algorithms: Logistic Regression, Decision Tree Classifier

Techniques Used: Exploratory Data Analysis (Seaborn pairplots), Feature Scaling (StandardScaler), Train/Test Splitting (80/20 rule).

Business Value: Demonstrates the ability to clean raw data, train algorithms, and mathematically prove accuracy using a Confusion Matrix and Classification Report (Precision, Recall, F1-Score).

2. Real Estate Housing Price Prediction (Ridge & Lasso Regression)

Objective: Perform continuous regression modeling to predict median house values based on neighborhood characteristics.

Dataset: California Housing Dataset

Algorithms: Ordinary Least Squares (OLS), Ridge (L2), and Lasso (L1) Regression.

Techniques Used: Missing value imputation, feature engineering (interaction features), multicollinearity detection (heatmaps), and hyperparameter tuning using GridSearchCV.

Business Value: Provides a framework for automated property valuation. Evaluates financial risk using metrics like Mean Absolute Error (MAE), RMSE, and Residual Error distribution to ensure models do not wildly overvalue or undervalue assets.

3. Predictive Customer Churn Classifier (Random Forest & XGBoost)

Objective: Solve severe class imbalance and predict customer attrition to inform targeted marketing strategies.

Dataset: Telco Customer Churn

Algorithms: Random Forest, XGBoost Classifier

Techniques Used: Categorical encoding (OneHotEncoder), handling imbalanced datasets with synthetic data generation (SMOTE), and extracting feature importance.

Business Value: Directly impacts company revenue by identifying high-risk customers before they cancel subscriptions. Uses the ROC-AUC curve (>80%) to rank customer risk, allowing the business to strategically deploy retention budgets only to high-value accounts.

Tools & Technologies

Language: Python 3

Data Manipulation: Pandas, NumPy

Machine Learning: Scikit-Learn, XGBoost, Imbalanced-Learn (SMOTE)

Data Visualization: Matplotlib, Seaborn

How to Run the Projects

The projects in this repository are formatted as Jupyter Notebooks (.ipynb). For the easiest experience without installing local dependencies:

Download the notebook file you wish to view.

Open Google Colab.

Click File -> Upload notebook and select the downloaded .ipynb file.

Click Runtime -> Run all to execute the code and view the visualizations.
