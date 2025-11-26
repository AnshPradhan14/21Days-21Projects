# 🚢 Day 1: Titanic Survival Analysis - EDA & Feature Engineering

### 📅 21 Days - 21 Projects Challenge

---

## 📖 Overview

Welcome to **Day 1** of my "21 Days, 21 Projects" challenge! 

For this inaugural project, I dove into the classic **Titanic Machine Learning** dataset. The goal was not just to predict survival, but to deeply understand the data through Exploratory Data Analysis (EDA) and create meaningful new features that could improve model performance.

This project focuses on **Univariate Analysis**, **Data Visualization**, **Feature Engineering**, and **Automated Profiling**.

---

## 📊 Key Analysis Steps

### 1. Univariate Analysis (Categorical)
I visualized the distribution of categorical variables to understand the demographics of the passengers.
* **Plots Generated:** A 2x3 grid showing counts for `Survived`, `Pclass`, `Sex`, `Embarked`, `SibSp`, and `Parch`.
* **Insights:** Checked for class imbalances and survival rates across different categories.

### 2. Univariate Analysis (Numerical)
I analyzed continuous variables to understand their spread and central tendencies.
* **Age Distribution:** Used a Histogram with a Kernel Density Estimate (KDE) to visualize the age of passengers, identifying peaks for young adults and infants.

### 3. Feature Engineering
I created new features to capture relationships that raw columns might miss:
* **`FamilySize`**: Calculated by summing `SibSp` (Siblings/Spouses) + `Parch` (Parents/Children) + 1 (the passenger themselves).
* **`IsAlone`**: A binary feature (0 or 1) derived from `FamilySize`. If `FamilySize` is 1, the passenger is marked as traveling alone. This is often a strong predictor of survival.

---

## 📑 Automated Data Profiling Report

One of the highlights of this project is the generation of a comprehensive HTML profiling report. This report provides a deep dive into every variable, showing correlations, missing values, and descriptive statistics automatically.

### 🔗 View the Report
You can find the generated report in this repository:
[**📄 View Titanic_yprofiling.html**](https://github.com/AnshPradhan14/21Days-21Projects/blob/main/Day%201/Titanic_yprofiling.html)

> **Note:** GitHub does not render HTML files directly in the browser. To view the interactive report:
> 1.  Click the link above.
> 2.  Download the file (`Raw` button or Download icon) to your local machine.
> 3.  Open the file in your preferred web browser (Chrome, Firefox, Edge, etc.).

---

## 🛠️ Technologies & Libraries

The following Python libraries were used in this analysis:

* **Python 3.12+**
* **Pandas:** For data manipulation and feature engineering.
* **Matplotlib & Seaborn:** For creating static visualizations and grids.
* **YData Profiling:** For generating the automated HTML report.



---

<p align="center">
  <b>Developed by Ansh Pradhan</b><br>
  <i>Part of the 21 Days, 21 Projects Challenge</i>
</p>
