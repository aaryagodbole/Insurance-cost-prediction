# Insurance-cost-prediction

🏥 Insurance Cost Prediction

A machine learning project that predicts medical insurance charges based on demographic and health-related factors using linear regression.

📌 Project Overview

This project performs:

✅ Data Cleaning & Preprocessing

✅ Exploratory Data Analysis (EDA)

✅ Feature Encoding & Scaling

✅ Model Training using Linear Regression

✅ Model Evaluation (MAE, MSE, R² Score)

✅ Visualizations:

Distribution plots

Scatter plots

Heatmap

Actual vs Predicted plot

Residual analysis

The goal is to build a reliable model that predicts insurance charges based on features like age, BMI, sex, smoking status, children, and region.

📂 Dataset

The dataset used: insurance.csv

Columns included:

age

sex

bmi

children

smoker

region

charges (Target variable)

🧹 Data Preprocessing

Converted categorical values using map()

Applied one-hot encoding for the region column

Scaled numerical features using StandardScaler

Split dataset into train-test sets

📊 Exploratory Data Analysis

Included visualizations:

Histogram of insurance charges

BMI vs Charges scatter plot

Boxplot of Age

Correlation heatmap

Actual vs Predicted graph

Residual plot

These help understand data trends, relationships, and model performance.

🤖 Machine Learning Model

Model used: LinearRegression (sklearn)

Metrics used for evaluation:

MAE – Mean Absolute Error

MSE – Mean Squared Error

R² Score – Model accuracy

Also included:

Training score

Coefficient analysis for feature importance

🧪 Prediction on New Data

The notebook includes a sample prediction using:

new_person = [[age, sex, bmi, children, smoker, region*]]


Scaled and passed into the trained model to estimate charges.

📁 Repository Structure
├── insurance_analysis.ipynb   # Main notebook
├── insurance.csv              # Dataset
└── README.md                  # Project documentation

🚀 Technologies Used

Python

NumPy

Pandas

Matplotlib

Seaborn

Scikit-Learn

Jupyter Notebook

⭐ Future Enhancements

Add RandomForestRegressor for better accuracy

Try Ridge/Lasso Regression

Build a Flask/Streamlit web app

Deploy model with CI/CD

🙌 Author

Aarya Godbole
Machine Learning Enthusiast & Developer
