# 🎗️ Cancer Progression Prediction using Regression

## 📌 Problem Statement

Cancer progression varies significantly across patients, and predicting the severity or stage of the disease based on clinical features is a key challenge in medical analytics. Accurate predictions can aid in treatment planning and improve patient outcomes.

This project uses regression techniques to predict a continuous target variable associated with cancer progression (e.g., disease progression metric or risk score) based on various medical and demographic features.

---

## 🎯 Objectives

- Perform thorough exploratory data analysis (EDA) to understand key features.
- Clean and preprocess the dataset to prepare it for modeling.
- Apply multiple regression algorithms to predict cancer progression scores.
- Evaluate model performance using appropriate regression metrics.
- Determine the most influential factors in disease progression.

---

## 🎯 Aim

To develop a machine learning regression model that can predict cancer progression indicators from patient data with high accuracy and interpretability.

---

## 📚 Dataset Description

- The dataset includes numerical features from medical measurements related to cancer progression.
- Features are standardized and represent physiological and biological metrics.
- **Target Variable**: A continuous numeric value representing the cancer progression score.

---

## 🧪 Exploratory Data Analysis (EDA)

- Visualized distributions of features and target variable
- Identified correlations using heatmaps
- Checked for missing values and outliers
- Used pairplots and scatter plots to examine relationships

---

## 🧼 Data Preprocessing

- Normalized numerical data (if not already scaled)
- Checked multicollinearity between features
- Split the dataset into training and testing sets (usually 80/20)

---

## 🤖 Regression Models Used

- **Linear Regression**
- **Ridge Regression**
- **Lasso Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **XGBoost Regressor** *(if implemented)*

---

## ✅ Model Evaluation

Evaluation metrics used:

- **R² Score**
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**

| Model                | R² Score |
|---------------------|----------|
| Linear Regression   | ~72%     |
| Ridge Regression    | ~75%     |
| Lasso Regression    | ~76%     |
| Decision Tree       | ~83%     |
| Random Forest       | **~87%** ✅ |

🏆 **Best Model**: **Random Forest Regressor** with approximately **87% R² Score**

---

## 📈 Visualizations

- Correlation matrix heatmap
- Actual vs. Predicted value plots
- Residual error plots
- Feature importance chart from tree-based models

---

## 🔧 Tools & Libraries

- Python (Jupyter Notebook)
- NumPy, Pandas, Seaborn, Matplotlib
- Scikit-learn
- XGBoost (optional)

---

## 📁 Project Structure

