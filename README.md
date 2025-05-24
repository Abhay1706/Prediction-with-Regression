# Prediction-with-Regression

# 📊 Regression Projects Portfolio

This repository contains two machine learning projects using **Linear Regression**:
1. **Salary Prediction** based on years of experience
2. **Delivery Time Prediction** based on sorting time

Each project follows a structured approach from problem definition to model evaluation.

---

## 🧠 1. Objective

### 🔹 Salary Prediction
To predict employee **salaries** based on their **years of experience** using a simple linear regression model.

### 🔹 Delivery Time Prediction
To estimate **delivery time** based on **sorting time**, helping improve logistics efficiency and forecasting.

---

## 🛠️ 2. Solution

### 🔹 Salary Prediction
- **Model Used**: Simple Linear Regression (`scikit-learn`)
- **Dataset**: Clean, no null or missing values
- **Independent Variable**: `YearsExperience`
- **Dependent Variable**: `Salary`
- **Train-Test Split**: 80:20
- **Model Metrics**:
  - RMSE: **59.12**
  - Coefficient (slope): **9460.66**
  - Intercept: **25521.23**
  - R² Score: **0.9219**

### 🔹 Delivery Time Prediction
- **Model Used**: Linear Regression (3 variants tested)
- **Dataset**: Preprocessed and cleaned, no outliers found
- **Independent Variable**: `Sorting Time`
- **Dependent Variable**: `Delivery Time`
- **Best Performing Model**:
  - RMSE: **1.51**
  - R² Score: **0.5318**

---

## 💼 3. Business Impact

### 🔹 Salary Prediction
- Supports **salary negotiations**, **budget forecasting**, and **human resource planning**
- Enables companies to **standardize salary structures** based on experience data
- Helps avoid over/under-paying employees, improving retention and fairness

### 🔹 Delivery Time Prediction
- Allows **logistics and supply chain** teams to better estimate delivery schedules
- Improves **operational efficiency** by analyzing the impact of sorting time
- Facilitates **resource allocation** for peak hours or bottlenecks

