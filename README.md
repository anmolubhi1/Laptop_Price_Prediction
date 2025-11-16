# 💻 Laptop Price Prediction using Machine Learning

A complete end-to-end machine learning project that predicts **laptop prices** based on hardware specifications and features.

This project includes:

- Full **Exploratory Data Analysis (EDA)**
- Advanced **data cleaning and feature engineering**
- Implementation & comparison of **multiple regression algorithms**
- Visualizations using **Matplotlib** & **Seaborn**
- Final **model evaluation & metrics comparison**
- A fully documented notebook for clarity and understanding

---

## 📌 Project Overview

Laptop prices vary significantly depending on hardware, brand, and performance features.  
This project builds a predictive model that estimates laptop prices based on attributes such as:

- CPU type  
- GPU  
- RAM  
- Storage  
- Weight  
- Display  
- Brand  
- OS  
- And more…

The goal is to create a robust model with strong predictive capability and compare multiple regression algorithms.

---

## 🚀 Features

- ✔️ Cleaned & preprocessed dataset  
- ✔️ Handled missing values and inconsistent formatting  
- ✔️ Engineered new useful features  
- ✔️ Performed complete **EDA** with meaningful insights  
- ✔️ Correlation analysis for feature relationships  
- ✔️ Implemented several **regression algorithms**:
  - Linear Regression  
  - Lasso Regression  
  - Ridge Regression  
  - ElasticNet Regression  
  - Decision Tree Regressor  
  - Random Forest Regressor  
  - Gradient Boosting Regressor  
  - XGBoost Regressor  
  - KNN Regressor  
  - Support Vector Regression (SVR)
- ✔️ Compared model performance using evaluation metrics  

---

## 🛠️ Technologies Used

| Library | Purpose |
|--------|---------|
| **NumPy** | Numerical operations |
| **Pandas** | Data cleaning & manipulation |
| **Matplotlib** | Basic visualization |
| **Seaborn** | Statistical visualization |
| **Scikit-Learn** | Machine learning algorithms & metrics |
| **XGBoost** | Advanced boosting regression |
| **Jupyter Notebook** | Interactive development |

---

## 🔍 Exploratory Data Analysis (EDA)

The notebook performs detailed EDA, which includes:

- Distribution of prices  
- Relationship between hardware features and price  
- Outlier detection  
- Feature correlation heatmap  
- Boxplots, histograms, pairplots  
- Brand analysis  
- Display & performance-based pricing trends  

These visualizations help understand how different features affect laptop pricing.

---

## 🧹 Data Cleaning & Feature Engineering

Steps included:

- Removing missing or inconsistent entries  
- Converting categorical columns into numerical form  
- Splitting complex columns (e.g., `"8GB RAM" → 8"`)  
- Extracting CPU & GPU brand features  
- Normalizing units (e.g., weight, storage)  
- Creating new derived features:
  - SSD capacity  
  - HDD capacity  
  - Total storage  
  - Display type (IPS, TN, OLED)  
  - PPI (Pixels Per Inch)

---

## 🤖 Machine Learning Models Implemented

We trained multiple regression models including:

- **Linear Regression**  
- **Lasso Regression**  
- **Ridge Regression**  
- **ElasticNet Regression**  
- **KNN Regressor**  
- **Decision Tree Regressor**  
- **Random Forest Regressor**  
- **Gradient Boosting Regressor**  
- **XGBoost Regressor**  
- **Support Vector Regression (SVR)**  

Each model was evaluated using:

- **R² Score**  
- **Mean Absolute Error (MAE)**  
- **Mean Squared Error (MSE)**  
- **Root Mean Squared Error (RMSE)**  

---




