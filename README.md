# ElevateLab_Task1

# 🚢 Titanic Data Cleaning & Preprocessing | AI & ML Internship Task 1

Welcome! This project is my submission for **Task 1: Data Cleaning & Preprocessing** as part of the **AI & ML Internship**.

In this task, I worked with the Titanic dataset and performed all essential steps to clean and prepare the data for machine learning models. The aim was to explore the data, handle missing values, encode categorical features, scale numerical columns, and ensure the dataset is model-ready.

---

## 🎯 Objective

The goal of this task was to take a raw dataset (Titanic passengers data) and:
- Understand its structure
- Handle missing values intelligently
- Convert categorical data into numerical format
- Normalize numerical features
- Remove outliers that could affect model performance

This is a crucial step in any ML pipeline and ensures better model accuracy and insights.

---

## 📁 Dataset Used

- **Name:** Titanic-Dataset.csv
- **Source:** [Kaggle - yasserh/titanic-dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

---

## 🛠️ Tools & Libraries

- Python 🐍
- Pandas
- NumPy
- Seaborn & Matplotlib
- Scikit-learn

---

## ✅ Steps Performed

### 1. **Data Loading & Exploration**
- Loaded the Titanic dataset using `pandas`
- Viewed basic info, structure, and missing values using `.info()` and `.isnull().sum()`

### 2. **Handling Missing Values**
- Filled missing `Age` values using **Median** to avoid outlier impact
- Filled missing `Embarked` values using **Mode**
- Dropped `Cabin` column due to high percentage of missing values

### 3. **Encoding Categorical Variables**
- Converted `Sex` using label encoding (Male = 0, Female = 1)
- Applied one-hot encoding to `Embarked`

### 4. **Outlier Detection and Removal**
- Used boxplot visualization for `Fare`
- Removed extreme outliers (top 5%) in `Fare`

### 5. **Feature Scaling**
- Scaled `Age` and `Fare` using **StandardScaler** for better model performance

### 6. **Exporting Cleaned Data**
- Saved the final cleaned dataset as `Cleaned_Titanic_Dataset.csv`

---

## 📸 Sample Output

```python
df.head()
![image](https://github.com/user-attachments/assets/672c4f3a-a4d4-4408-bd4d-b6fcd80cebd4)









