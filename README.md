# MSCA-Machine-Learning-Predictive-Analytics-Project
This repository contains information on MSCA Machine Learning Predictive Analytics team project at University of Chicago

Professor: Arnab Bose

# Team
Amily Huang: yunh@uchicago.edu

Jenny Jiang: jejiang@uchicago.edu 

Bharadwaj Kacharla: bharadwajk@uchicago.edu

Duo Zhou: zd0009@uchicago.edu

# Structure of the repository
- Raw Code: This folder includes the Python code for explanatory data analysis, feature engineering, and machine learning models
- Final Presentation: This folder contains the final presentation

# Project Description
In this project, we built several machine learning models and deep learning model to make default predictions given certain characteristics of a credit applicant and help loan company Home Credit to minimize default risk.

# Data
Home Credit Default Risk (https://www.kaggle.com/c/home-credit-default-risk/data)

# Brief on Project Workflow
### 1. EDA & Feature Engineering
- Univariate Analysis
- Bivariate Analysis
- Data Cleaning

### 2. Imbalanced Dataset Handing Approach
- Adaptive re-sampling
  * Oversample minor class (Synthetic Minority Over-sampling Technique - SMOTE)
  * Under-sample major class (Random Sampling)
- Cost-sensitive learning
  * Loss function of the classification algorithm is modified to weight the classification errors differently for major and minor class

### 3. Model Building
- Support Vector Machine
- Random Forest
- XGBoost
- ANN

### 4. Model Evaluation
- AUC
- Recall

