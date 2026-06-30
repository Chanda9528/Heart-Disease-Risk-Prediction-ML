# ❤️ Heart Disease Prediction System

A Machine Learning project that predicts the likelihood of heart disease based on patient health parameters. The project includes complete data preprocessing, exploratory data analysis (EDA), comparison of multiple classification models, selection of the best-performing model, and deployment using Streamlit.

---

## 📌 Project Overview

Heart disease is one of the leading causes of death worldwide. Early prediction can help doctors and patients take preventive actions.

This project builds a classification model using machine learning algorithms to predict whether a patient is at risk of heart disease. Multiple models were trained and evaluated, and the best-performing model (K-Nearest Neighbors) was selected for deployment.

---

## 🎯 Objectives

- Perform data cleaning and preprocessing
- Explore the dataset using EDA
- Train multiple machine learning models
- Compare model performance
- Select the best-performing model
- Save the trained model using Joblib
- Deploy the prediction system using Streamlit

---

## 📂 Dataset

**Dataset:** Heart Disease Dataset

The dataset contains patient medical information such as:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise-Induced Angina
- Oldpeak
- ST Slope

**Target Variable**

- HeartDisease
  - 0 → No Heart Disease
  - 1 → Heart Disease

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Streamlit

---

## 📊 Project Workflow

1. Load Dataset
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. One-Hot Encoding
6. Feature Scaling
7. Train-Test Split
8. Train Multiple Machine Learning Models
9. Compare Model Performance
10. Select Best Model
11. Save Model using Joblib
12. Deploy with Streamlit

---

## 🤖 Machine Learning Models Compared

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Decision Tree
- Support Vector Machine (SVM)

---

## 🏆 Best Model

**K-Nearest Neighbors (KNN)**

The KNN model achieved the best overall performance among the tested classification algorithms and was selected for deployment.

---

## 📁 Project Structure

```
Heart-Disease-Prediction-System/
│
├── heart.csv
├── heart_disease_prediction.ipynb
├── heart_disease_streamlit_ui.ipynb
├── streamlit_prediction.py
├── KNN_heart.pkl
├── scaler.pkl
├── columns.pkl
├── requirements.txt
└── README.md
```

---

## 🚀 Streamlit Application

The trained KNN model is integrated into a Streamlit web application where users can:

- Enter patient details
- Predict heart disease risk instantly
- Receive prediction results in a user-friendly interface

---

## ▶️ Run Locally

### Clone Repository

```bash
git clone https://github.com/your-username/Heart-Disease-Prediction-System.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Streamlit App

```bash
streamlit run streamlit_prediction.py
```

---

## 📈 Future Improvements

- Hyperparameter Tuning
- Cross Validation
- Feature Selection
- Model Explainability (SHAP/LIME)
- Deployment on Streamlit Cloud
- Integration with Flask/FastAPI

---




---


