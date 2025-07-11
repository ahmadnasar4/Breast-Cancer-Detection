# Breast-Cancer-Detection-System_ML
Title: Breast Cancer Detection Using Machine Learning 
# 🩺 Breast Cancer Detection System using Machine Learning

## 📘 Project Overview

Breast cancer remains one of the leading causes of mortality among women globally. Early detection significantly improves the chances of successful treatment and survival. This project presents a complete, machine learning-based diagnostic system to predict breast cancer from clinical data using two models: a Custom Dense Neural Network and an Enhanced Random Forest Classifier. The system is implemented as a full-stack web application, complete with an interactive UI, a Flask backend, and Power BI dashboards for visual analytics.

---

## 🎯 Key Features

- Predicts if a tumor is **Benign (B)** or **Malignant (M)** based on clinical features
- Two models: 
  - `DenseNet128` using TensorFlow/Keras
  - `Enhanced Random Forest` with tuned hyperparameters
- Interactive web UI built using HTML, CSS, JavaScript & Bootstrap
- Flask-powered backend and SQLite database
- Power BI dashboards for visualizing results and trends
- Secure login system for hospital staff

---

## 🛠️ Technologies Used

- **Frontend:** HTML, CSS, JavaScript, Bootstrap
- **Backend:** Python, Flask, SQLite
- **Machine Learning:** Scikit-learn, TensorFlow/Keras
- **Visualization:** Power BI, Plotly.js
- **Data Processing:** Pandas, NumPy
- **Deployment:** Flask (Local Server)

---

## 📊 Dataset Information

- **Source:** [Kaggle - Breast Cancer Wisconsin (Diagnostic) Dataset](https://www.kaggle.com/datasets)
- **Samples:** 569
- **Features:** 30 numeric attributes from digitized images of fine needle aspirate (FNA)
- **Target:** `diagnosis` (M = Malignant, B = Benign)

---

## 🚀 Project Architecture

1. **Data Layer:** Cleansed and stored in MySQL & Excel (for Power BI)
2. **Learning Layer:** Trains DenseNet128 and Random Forest models
3. **Backend Layer:** Flask server manages API endpoints and predictions
4. **Frontend Layer:** User-friendly interface for data entry and viewing results
5. **Visualization:** Dashboards to interpret predictions and trends

---

## 🧪 Model Performance

| Model                  | Accuracy | Precision | Recall | F1 Score |
|------------------------|----------|-----------|--------|----------|
| DenseNet128 (DNN)      | 98.4%    | High      | High   | High     |
| Enhanced Random Forest | 97.1%    | High      | High   | High     |

- ROC-AUC, Confusion Matrix, and metrics across multiple train-test splits were evaluated.
- The DenseNet model slightly outperforms the Random Forest in most cases.

---


