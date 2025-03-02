# 📌 Linear Regression Notebook

## 📖 Overview
This notebook explores **Simple and Multiple Linear Regression** using different implementation approaches. It covers methods using:
- **Statsmodels**
- **Scikit-Learn**
- **SciPy**
- **Gradient Descent**
  
Each section is structured to help understand the fundamentals of regression analysis, model evaluation, and implementation differences.

---

## 📌 Table of Contents
- [I. Data Analysis](#data-analysis)
- [II. Simple Linear Regression](#simple-linear-regression)
  - [1. Performing OLS Regression with `statsmodels`](#ols-statsmodels)
  - [2. Gradient Descent](#gradient-descent)
  - [3. Manual Method](#manual-method)
  - [4. SciPy Implementation](#scipy-implementation)
  - [5. Scikit-Learn Implementation](#scikit-learn-implementation)
- [III. Multiple Linear Regression](#multiple-linear-regression)
  - [1. Feature Normalization](#feature-normalization)
  - [2. Gradient Descent Implementation](#gradient-descent-multiple)
  - [3. Scikit-Learn Implementation](#scikit-learn-multiple)
  - [4. SciPy Implementation](#scipy-multiple)
  - [5. Statsmodels Implementation](#statsmodels-multiple)

---

## 📊 I. Data Analysis <a id="data-analysis"></a>
- This section provides **data exploration** and **preprocessing** steps.
- It includes:
  - Data visualization
  - Summary statistics
  - Correlation analysis

---

## 📉 II. Simple Linear Regression <a id="simple-linear-regression"></a>
### 🔹 1. Performing OLS Regression with `statsmodels` <a id="ols-statsmodels"></a>
- Uses **Ordinary Least Squares (OLS)** to compute regression parameters.
- Includes **statistical summaries** such as p-values, confidence intervals, and R².

### 🔹 2. Gradient Descent <a id="gradient-descent"></a>
- Implements **batch gradient descent** to optimize the cost function.

### 🔹 3. Manual Method <a id="manual-method"></a>
- Computes **theta parameters** using the **normal equation**.

### 🔹 4. SciPy Implementation <a id="scipy-implementation"></a>
- Uses `stats.linregress()` from SciPy.
- Provides slope, intercept, R², p-value, and standard error.

### 🔹 5. Scikit-Learn Implementation <a id="scikit-learn-implementation"></a>
- Uses `LinearRegression()` from **Scikit-Learn**.
- Demonstrates a fast and efficient way to perform regression.

---

## 📊 III. Multiple Linear Regression <a id="multiple-linear-regression"></a>
### 🔹 1. Feature Normalization <a id="feature-normalization"></a>
- Normalizes features to improve gradient descent performance.

### 🔹 2. Gradient Descent Implementation <a id="gradient-descent-multiple"></a>
- Extends gradient descent for **multiple variables**.

### 🔹 3. Scikit-Learn Implementation <a id="scikit-learn-multiple"></a>
- Uses `LinearRegression()` for **multivariate regression**.

### 🔹 4. SciPy Implementation <a id="scipy-multiple"></a>
- Uses **Moore-Penrose Pseudo-Inverse** from SciPy for solving multiple regression.

### 🔹 5. Statsmodels Implementation <a id="statsmodels-multiple"></a>
- Uses `sm.OLS()` for **multiple features** with full statistical insights.


