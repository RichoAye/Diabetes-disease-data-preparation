# Diabetes Prediction Data Preprocessing and Quality Enhancement Project

**Author:** Rahel Mekonen  
**ID:** 1501427  
**Course:** Data Science Applications (InSy 3056)  
**Department:** Information Systems  
**University:** Debre Berhan University  

---

## 📘 Project Overview

This project focuses on improving the quality of a diabetes dataset for predictive modeling. Using the **Pima Indians Diabetes Dataset**, the goal is to clean, preprocess, and enhance the data to prepare it for machine learning applications.

The project addresses key data quality issues such as missing values, outliers, feature imbalance, and inconsistent distributions — ensuring that the final dataset is balanced, reliable, and ready for model training.

---

## 🧩 Objectives

- Identify and handle missing and invalid data  
- Normalize and standardize numeric attributes  
- Engineer new meaningful features  
- Remove redundant or highly correlated features  
- Resolve class imbalance using **SMOTE**  
- Prepare the dataset for predictive model training  

---

## 🧠 Methodology

The data preprocessing pipeline consists of five structured phases:

1. **Exploratory Data Analysis (EDA)** – Analyze dataset structure, detect missing values, visualize distributions.  
2. **Data Cleaning** – Replace invalid zero values, impute missing data using median strategy.  
3. **Feature Engineering** – Create new derived features such as:
   - Glucose-to-BMI Ratio  
   - Age-Weighted Pedigree Score  
   - Normalized Insulin Index  
4. **Feature Selection** – Use **Recursive Feature Elimination (RFE)** to retain only the most predictive features.  
5. **Data Balancing** – Apply **SMOTE (Synthetic Minority Oversampling Technique)** to ensure equal class representation.  

---

## 🧰 Tools and Libraries Used

- **Python 3.11+**  
- **Pandas** – Data manipulation  
- **NumPy** – Numerical computation  
- **Scikit-learn** – Preprocessing, feature selection  
- **Imbalanced-learn** – SMOTE balancing  
- **Matplotlib / Seaborn** – Visualization  
- **Jupyter Notebook** – Analysis environment  

---



