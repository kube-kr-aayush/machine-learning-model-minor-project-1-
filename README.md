# Diabetes Prediction using Machine Learning

## 📌 Project Overview

This project aims to predict whether a patient has diabetes based on demographic and medical information using a supervised machine learning approach. The project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, model evaluation, and model saving.

---

## 🎯 Problem Statement

Diabetes is one of the most common chronic diseases worldwide. Early prediction can help healthcare professionals identify high-risk patients and provide timely treatment.

The objective of this project is to build a Logistic Regression model that predicts whether a patient has diabetes based on medical and demographic features.

---

## 📂 Dataset

* **Dataset Name:** Diabetes Prediction Dataset
* **Source:** Kaggle
* **Dataset Link:** https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset

### Features

* Gender
* Age
* Hypertension
* Heart Disease
* Smoking History
* BMI
* HbA1c Level
* Blood Glucose Level

### Target Variable

* **Diabetes**

  * 0 → Non-Diabetic
  * 1 → Diabetic

---

## 🛠 Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Pickle

---

## 📊 Data Preprocessing

The following preprocessing steps were performed:

* Removed duplicate records
* Checked for missing values
* One-Hot Encoding for categorical features
* Feature Scaling using StandardScaler
* Train-Test Split (80:20)

---

## 📈 Exploratory Data Analysis (EDA)

EDA was performed using:

* Count Plots
* Histograms
* Box Plots
* Correlation Heatmap

The analysis helped understand feature distributions and relationships with the target variable.

---

## 🤖 Machine Learning Model

* Logistic Regression

---

## 📊 Model Performance

| Metric    | Score  |
| --------- | ------ |
| Accuracy  | 95.71% |
| Precision | 85.44% |
| Recall    | 62.75% |
| F1-Score  | 72.36% |

---

## 💾 Saved Files

* diabetes_model.pkl
* scaler.pkl

---

## 📁 Project Structure

```
Diabetes-Prediction-ML/

├── data/
│   └── diabetes_prediction_dataset.csv
│
├── notebook/
│   └── Diabetes_Prediction.ipynb
│
├── model/
│   ├── diabetes_model.pkl
│   └── scaler.pkl
│
├── results/
│   └── confusion_matrix.png
│
├── README.md
│
└── report.pdf
```

---

## 🚀 Future Improvements

* Train multiple machine learning models
* Perform hyperparameter tuning
* Handle class imbalance using SMOTE
* Deploy the model as a web application

---

## 👨‍💻 Author

**Aayush**

Minor Project – Supervised Machine Learning
