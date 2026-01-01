# ❤️ Heart Disease Classification using Machine Learning

## 📌 Project Overview
This project focuses on building a machine learning classification model capable of predicting whether a patient has heart disease based on various clinical and medical attributes.

Python-based data science and machine learning libraries are used to train, evaluate, and compare multiple models to determine the most effective approach.

---

## ❓ Problem Statement
**Given clinical parameters about a patient, can we predict whether or not they have heart disease?**

This is treated as a binary classification problem:
- `1` → Patient has heart disease  
- `0` → Patient does not have heart disease  

---

## 📂 Dataset
The dataset used in this project is the **Cleveland Heart Disease Dataset**.

**Sources:**
- UCI Machine Learning Repository  
  https://archive.ics.uci.edu/ml/datasets/heart+Disease
- Kaggle  
  https://www.kaggle.com/datasets/ketangangal/heart-disease-dataset-uci

---

## 🎯 Evaluation
The primary evaluation metric is **Accuracy**.

- Target accuracy: **≥ 95%**
- Additional evaluation metrics:
  - ROC Curve
  - AUC Score
  - Confusion Matrix

---

## 🧾 Features (Data Dictionary)

- `age` – Age in years  
- `sex` – 1 = male, 0 = female  
- `cp` – Chest pain type (0–3)  
- `trestbps` – Resting blood pressure (mm Hg)  
- `chol` – Serum cholesterol (mg/dl)  
- `fbs` – Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)  
- `restecg` – Resting ECG results (0–2)  
- `thalach` – Maximum heart rate achieved  
- `exang` – Exercise-induced angina (1 = yes, 0 = no)  
- `oldpeak` – ST depression induced by exercise  
- `slope` – Slope of peak exercise ST segment  
- `ca` – Number of major vessels (0–3)  
- `thal` – Thalium stress test result  
- `target` – Heart disease presence (1 = yes, 0 = no)  

---

## 🧠 Machine Learning Models Used
- Logistic Regression  
- Random Forest Classifier  
- Hyperparameter tuning using GridSearchCV / RandomizedSearchCV  
- Cross-validation for reliable model evaluation  

---

## 📊 Exploratory Data Analysis
- Feature distribution analysis  
- Crosstab analysis (e.g., sex vs target, slope vs target)  
- Data visualization using Matplotlib and Seaborn  

---

## 🔬 Experimentation
If the target evaluation metric is not achieved:
- Collect more data  
- Try advanced models such as XGBoost or CatBoost  
- Improve feature engineering  
- Optimize hyperparameters further  

---

## 🛠️ Technologies Used
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 🚀 How to Run
```bash
git clone https://github.com/shivanic17/Heart-Disease-Classification.git
cd Heart-Disease-Classification
jupyter notebook
