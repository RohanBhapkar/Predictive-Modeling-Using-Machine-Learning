# 🤖 Predictive Modeling Using Machine Learning

## 📌 Project Overview

This project demonstrates the application of supervised machine learning techniques to predict revenue using a Coffee Shop Sales dataset. Multiple machine learning algorithms were trained and evaluated to compare their predictive performance.

## 🎯 Objectives

* Build predictive models using machine learning
* Train and test models on historical sales data
* Compare model performance
* Evaluate prediction accuracy
* Visualize model results and feature importance

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

## 📂 Dataset

The project uses the Coffee Shop Sales dataset containing transaction information such as:

* Transaction Quantity
* Unit Price
* Product Category
* Product Type
* Product Details
* Store Location
* Transaction Time

## 🔄 Data Preprocessing

The following preprocessing steps were performed:

* Loaded cleaned dataset
* Encoded categorical variables using Label Encoding
* Selected relevant features
* Created training and testing datasets
* Prepared target variable (Revenue)

## 🤖 Machine Learning Models

The following supervised learning algorithms were implemented:

### 1. Linear Regression

Used as a baseline regression model.

### 2. Decision Tree Regressor

Used to learn nonlinear relationships in the dataset.

### 3. Random Forest Regressor

Used to improve prediction performance through ensemble learning.

## 📊 Model Evaluation Metrics

The models were evaluated using:

* R² Score
* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)

## 📈 Results

| Model             | R² Score |
| ----------------- | -------- |
| Linear Regression | 0.9417   |
| Decision Tree     | 1.0000   |
| Random Forest     | 1.0000   |

### Best Model

Decision Tree Regressor achieved the highest performance with an R² Score of 1.0.

## 📉 Visualizations

The project includes:

* Model Performance Comparison
* Actual vs Predicted Revenue
* Feature Importance Analysis

## 🔍 Key Insights

* Revenue can be predicted effectively using transaction and product-related features.
* Decision Tree and Random Forest models achieved excellent performance.
* Transaction Quantity and Unit Price were the most influential predictors.
* Machine learning models successfully captured patterns in coffee shop sales data.

## 📁 Project Files

* Predictive_Modeling.ipynb
* cleaned_coffee_shop_sales.xlsx
* README.md

## 🚀 Learning Outcomes

Through this project, the following concepts were practiced:

* Supervised Learning
* Regression Modeling
* Model Evaluation
* Feature Engineering
* Data Visualization
* Machine Learning Workflow

