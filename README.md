Assignment 1: EDA and Preprocessing

Overview:
This project focuses on **Exploratory Data Analysis (EDA) and Data Preprocessing**
to improve **data quality, reliability, and usefulness** for machine learning applications. 

It addresses key challenges such as **missing values, outliers, inconsistent formatting, and noise**.

Key Steps:

1. Data Exploration – Loaded dataset, analyzed unique values, performed statistical analysis.  
2. Data Cleaning– Handled missing values, removed duplicates, detected outliers, and standardized formatting.  
3. Data Analysis– Filtered data based on conditions, visualize age vs salary, and analyze distribution by location.  
4. Data Encoding – Converted categorical variables using **One-Hot Encoding**.  
5. Feature Scaling– Normalized data using **StandardScaler** and **MinMaxScaler** for better machine learning performance.  

Usage:
Simply follow the step-by-step implementation in `EDA.ipynb` to clean, analyze, and prepare the dataset.




Assignment 2: California Housing Regression Analysis

Project Overview:

This project applies various regression techniques to predict housing prices in California using the California Housing dataset from sklearn.

Steps Covered:

1: Data Preprocessing: Load dataset, convert to Pandas DataFrame, handle missing values, and scale features using StandardScaler.

2: Train Regression Models: Implement Linear Regression, Decision Tree, Random Forest, Gradient Boosting, and SVR. 

3: Model Evaluation: Assess performance using MSE, MAE, and R² Score. 

4: Comparison & Insights: Identify best and worst models and visualize results using matplotlib & seaborn.

5: Documentation & Submission: Markdown explanations included in Jupyter Notebook for clarity.

Run the Jupyter Notebook (Regression_Assignment.ipynb) for analysis.




Assignment 4:  Breast Cancer Classification Project

This project applies five machine learning classifiers—Logistic Regression, Decision Tree, Random Forest, Support Vector Machine, and k-Nearest Neighbors—to predict breast cancer (malignant vs. benign) using the scikit-learn breast cancer dataset.

Key highlights:

--Exploratory data analysis (EDA) and preprocessing

--Model training and evaluation with accuracy_score

--Hyperparameter tuning for k-NN

--Model comparison with metrics and visualizations

--Best model: Logistic Regression / Random Forest

--Worst model: Decision Tree



Assignmnet 5:Clustering Iris Dataset using KMeans and Hierarchical Clustering

Objective:
This project demonstrates unsupervised learning techniques—specifically KMeans and Hierarchical clustering—applied to the classic Iris dataset from sklearn.

Steps Followed:

Dataset Loading & Preprocessing

Loaded the Iris dataset from sklearn.datasets.

Dropped the species column to treat it as a pure clustering problem.

Applied StandardScaler to normalize feature scales.

Clustering Algorithms Implemented.

1: KMeans Clustering:

Partitioned the dataset into 3 clusters.

Visualized clusters using Sepal Length and Sepal Width features.

2: Hierarchical Clustering:

Used Ward linkage to build the dendrogram.

Cut the dendrogram to form 3 clusters.

Visualized the resulting clusters.

Visualization:

Created 2D scatter plots for both clustering methods to illustrate groupings.

Displayed a dendrogram for Hierarchical clustering.
