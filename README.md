# 💼 Salary Prediction Using Linear Regression

This project demonstrates a simple yet powerful application of **Linear Regression** to predict employee salaries based on their **years of experience**. It is an ideal example of how statistical models can support data-driven decision-making in HR and career planning.

---

## 📌 Problem Statement

Companies and HR departments often need to estimate fair compensation for employees based on their experience level. In this project, we build a **Simple Linear Regression** model to predict salaries, helping organizations make more informed and equitable decisions.

---

## 📊 Dataset Overview

- **Source:** Public dataset from Kaggle  
- **Features:**
  - `YearsExperience`: Number of years of work experience
  - `Salary`: Annual salary in USD
- **Format:** CSV

---

## 🧪 Exploratory Data Analysis (EDA)

- Visualized the relationship between `YearsExperience` and `Salary` using a scatter plot
- Computed summary statistics and correlation coefficients
- Verified linearity, data types, and absence of missing values

---

## 🧹 Data Preprocessing

- No missing values or outliers
- Features scaled appropriately
- Dataset split into **training** and **testing** sets using `train_test_split`

---

## 🧠 Model Building

- Used **Simple Linear Regression** from Scikit-learn
- Trained the model on 80% of the dataset
- Learned a regression line:  
  `Salary = slope × YearsExperience + intercept`

---

## 📈 Model Evaluation

- **Metrics Used:**
  - Mean Squared Error (MSE)
  - R² Score
- **Results:**
  - High R² value indicating strong predictive capability
- **Visualization:**
  - Plotted regression line over actual test data points

---

## 📌 Tools & Technologies

- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---


