# 🏥 Diabetes Prediction System

## 📌 Overview

This project focuses on predicting whether a patient has diabetes based on medical features such as glucose level, BMI, blood pressure, and age.

---

## 📊 Data Science (EDA)

* Performed data cleaning by handling missing values (zero values replaced with median)
* Analyzed feature distributions and relationships
* Identified key factors influencing diabetes

### 🔍 Key Insights

* Glucose is the most important factor affecting diabetes
* BMI and age also play significant roles
* Data cleaning was crucial for improving model reliability

---

## 🤖 Machine Learning

Built classification models to predict diabetes.

### Models Used:

* Logistic Regression

  * Accuracy: ~75%
  * Recall: ~67%

* Decision Tree

  * Accuracy: ~74%
  * Recall: ~67%

---

## ⚠️ Important Insight

Recall is a critical metric in this project because missing a diabetes case (false negative) can have serious health consequences.

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🚀 Future Improvements

* Hyperparameter tuning
* Advanced models (Random Forest, XGBoost)
* Feature scaling and engineering
* Deployment as a web application
