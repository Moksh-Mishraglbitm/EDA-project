# EDA-project
CREDIT CARD FRAUD DETECTION USING MACHINE LEARNING
=================================================

PROJECT OVERVIEW
----------------
This project analyzes credit card transaction data and builds a machine learning model to detect fraudulent transactions.

The dataset is highly imbalanced, with fraud transactions representing a very small percentage of all transactions. The project combines Exploratory Data Analysis (EDA), feature engineering, visualization, and machine learning to identify suspicious transactions.

DATASET
-------
Credit Card Fraud Detection Dataset

Features:
- Time
- V1 to V28 (PCA-transformed features)
- Amount
- Class

Target Variable:
- Class = 0 → Normal Transaction
- Class = 1 → Fraudulent Transaction

TECHNOLOGIES USED
-----------------
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

PROJECT WORKFLOW
----------------
1. Data Loading
2. Data Inspection
3. Exploratory Data Analysis
4. Class Distribution Analysis
5. Fraud vs Normal Transaction Analysis
6. Amount Distribution Analysis
7. Log Transformation
8. Correlation Heatmap
9. Data Scaling
10. Train-Test Split
11. Logistic Regression Model
12. Model Evaluation
13. ROC Curve Analysis
14. Transaction Prediction

EXPLORATORY DATA ANALYSIS
-------------------------
Performed:

- Dataset Overview
- Fraud vs Normal Count Plot
- Transaction Amount Analysis
- Boxplots
- Correlation Heatmap
- Log Amount Distribution
- Class Imbalance Analysis

KEY OBSERVATIONS
----------------
- Fraud cases are extremely rare compared to normal transactions.
- Strong class imbalance exists.
- Fraud transactions show different behavioral patterns in certain PCA features.
- Amount distributions differ between fraud and non-fraud transactions.

FEATURE ENGINEERING
-------------------
- Log Transformation of Amount
- Feature Scaling using StandardScaler
- Target Separation
- Train-Test Split

MACHINE LEARNING MODEL
----------------------
Model Used:
- Logistic Regression

Techniques Used:
- StandardScaler
- Class Weight Balancing

MODEL PERFORMANCE
-----------------
Accuracy:
~97% to 99%

Evaluation Metrics:
- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1 Score
- ROC Curve
- AUC Score

RESULTS
-------
The model successfully identifies fraudulent transactions while maintaining high performance on normal transactions.

ROC-AUC:
~0.99

The ROC curve indicates excellent discrimination capability between fraud and normal transactions.

VISUALIZATIONS
--------------
- Fraud vs Normal Count Plot
- Transaction Amount Boxplot
- Log Amount Distribution
- Correlation Heatmap
- ROC Curve

REAL-TIME PREDICTION
--------------------
The project includes transaction prediction functionality.

Input:
Transaction Features

Output:
- Fraud Transaction Detected
OR
- Normal Transaction

Confidence Score:
Displayed using prediction probabilities.

APPLICATIONS
------------
- Banking Systems
- Payment Gateways
- Fraud Monitoring
- Financial Security
- Risk Management

SKILLS DEMONSTRATED
-------------------
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Engineering
- Data Scaling
- Machine Learning
- Logistic Regression
- Fraud Analytics
- ROC Curve Analysis
- Classification
- Model Evaluation

AUTHOR
------
Moksh Mishra

STATUS
------
Completed
