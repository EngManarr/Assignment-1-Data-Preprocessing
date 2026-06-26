📊 Machine Learning Assignment 1
Data Preprocessing – House Prices Dataset
📌 Project Overview

This project focuses on applying complete data preprocessing techniques on the House Prices: Advanced Regression Techniques dataset.
The goal is to prepare clean and engineered data suitable for regression modeling.

The workflow includes:

Data loading and inspection
Data cleaning and handling missing values
Exploratory Data Analysis (EDA)
Feature engineering
Preparing final dataset for modeling
📂 Dataset

The dataset used is from Kaggle:

train.csv → contains features and target variable (SalePrice)
test.csv → used for final prediction preparation

Dataset link:
https://www.kaggle.com/c/house-prices-advanced-regression-techniques

🛠️ Project Steps
1. Data Loading
Loaded training and testing datasets using pandas
Inspected dataset shape and structure
Identified data types and optimized memory usage
2. Data Cleaning
Handled missing values using appropriate strategies:
Numerical values → mean/median imputation
Categorical values → mode or “None” category
Treated special features like PoolQC, Fence, and Alley
Applied log transformation to reduce skewness in SalePrice
Removed or analyzed outliers in key features
3. Exploratory Data Analysis (EDA)
Correlation analysis between numerical features and target
Visualized key relationships such as:
GrLivArea vs SalePrice
Neighborhood vs SalePrice
Identified most important features affecting house prices
4. Feature Engineering
Created new feature:
TotalSF = TotalBsmtSF + 1stFlrSF + 2ndFlrSF
Encoded categorical variables:
Label Encoding for ordinal features
One-Hot Encoding for nominal features
Prepared dataset for machine learning models
📊 Tools & Libraries
Python
Pandas
NumPy
Matplotlib / Seaborn
Scikit-learn
🚀 Output

The final dataset is clean, processed, and ready for regression modeling.

👩‍💻 Author

Student Project – Machine Learning Assignment 1
Instructor: Ibrahim O. Kaware
