# Diabetes Prediction Data Preprocessing and Quality Enhancement Project

**Author:** Rahel Mekonen  
**ID:** 1501427  
**Course:** Data Science Applications (InSy 3056)  
**Department:** Information Systems  
**University:** Debre Berhan University  

---

# 🩺 Diabetes Prediction Data Preprocessing and Quality Enhancement

**Author:** Rahel Mekonen  
**ID:** 1501427  
**Course:** Data Science Applications (InSy 3056)  
**Department:** Information Systems  
**University:** Debre Berhan University  

---

## 📘 Project Overview

This project focuses on **data preprocessing and quality enhancement** for diabetes prediction using the **Pima Indians Diabetes dataset**.  
The objective is to clean, transform, and balance the dataset to make it suitable for reliable machine learning model training.

Through a structured data engineering workflow, missing values, class imbalance, and data inconsistencies are handled systematically, resulting in a **cleaned, normalized, and balanced dataset** ready for predictive modeling.

---

## 🧩 Key Features

- Comprehensive data cleaning and preprocessing
- Handling missing and invalid values
- Feature engineering and selection
- Data normalization using `StandardScaler`
- Class balancing using **SMOTE**
- Exporting the cleaned dataset for further modeling
- Visualization and exploratory data analysis using Jupyter Notebook

---

  Project Workflow

### 1️⃣ Data Preprocessing (`src/data_preprocessor.py`)
- Reads the raw dataset (`Diabetes Missing Data.csv`)
- Replaces invalid zero values (e.g., glucose, insulin, BMI) with NaN
- Imputes missing data using **median strategy**
- Performs **feature engineering**, including:
  - Glucose-to-BMI Ratio  
  - Age-Weighted Pedigree Score  
  - Normalized Insulin Index
- Standardizes numeric features using **StandardScaler**
- Resolves class imbalance using **SMOTE (Synthetic Minority Oversampling Technique)**
- Saves the preprocessed dataset as `cleaned_diabetes_data.csv`

### 2️⃣ Data Exploration (`notebook/analysis.ipynb`)
- Performs **Exploratory Data Analysis (EDA)** on both raw and cleaned data
- Visualizes distributions and correlations using:
  - Histograms
  - Boxplots
  - Correlation heatmaps
- Compares the dataset before and after preprocessing
- Validates class balance after applying SMOTE

### 3️⃣ Output
- A high-quality dataset free from missing values and inconsistencies
- Balanced diabetic/non-diabetic classes
- Enhanced features for better model interpretability
- Cleaned dataset ready for model training




