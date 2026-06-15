# 🏠 House Price Prediction ML Project

This project focuses on building a machine learning model to predict house prices using a regression dataset from Kaggle.


## 📊 Project Overview

The goal of this project is to analyze housing data and build a regression model that predicts house prices based on various property features such as square footage, number of bedrooms, bathrooms, lot size, and more.

## 📁 Dataset Information

The dataset contains 1000 records with the following features:

- Square_Footage  
- Num_Bedrooms  
- Num_Bathrooms  
- Year_Built  
- Lot_Size  
- Garage_Size  
- Neighborhood_Quality  
- House_Price (Target Variable)

## 🧹 Data Preprocessing

- Checked for missing values → None found  
- Checked for duplicate records → None found  
- Performed exploratory data analysis  
- Visualized feature distributions and correlations  

## 📈 Exploratory Data Analysis

- Correlation heatmap was used to analyze relationships between features  
- Box plots were used to detect outliers  
- Strong correlation was observed between Square Footage and House Price  

## 🤖 Model Building

- Model used: Random Forest Regressor  
- Train-test split: 80/20  
- Random state: 42  

## 📊 Model Performance

- Train R² Score: ~0.995  
- Test R² Score: ~0.990  

The model performed very well due to strong linear relationships in the dataset.

## 🔍 Feature Impact Analysis

An experiment was conducted by removing the Square Footage feature.

- With Square Footage: R² ≈ 0.99  
- Without Square Footage: R² ≈ -0.03  

This shows that Square Footage is the dominant feature influencing house price prediction in this dataset.

## 🧠 Key Learnings

- Feature importance plays a major role in regression problems  
- A single strong feature can significantly influence model performance  
- Model evaluation should always include baseline comparisons  

## 🚀 Tech Stack

- Python  
- Pandas  
- Scikit-learn  
- Plotly  
- Jupyter Notebook  

## 📌 Author

Built as a learning project for machine learning practice.
