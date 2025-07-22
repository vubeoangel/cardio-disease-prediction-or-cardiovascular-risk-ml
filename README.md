# Cardiovascular Disease Prediction (ML Project)

This project applies multiple machine learning models to predict whether a patient is likely to have cardiovascular disease based on clinical and lifestyle features. It was completed as part of my final-year data analytics assignment at UTS.

## 🔍 Problem
Cardiovascular disease remains a major global health issue. Early detection can reduce long-term health costs and improve outcomes. This project builds a predictive pipeline to classify individuals as high-risk or not.

## 📁 Dataset
An anonymized dataset of patient health records containing:
- Age, gender, weight, height
- Systolic/diastolic blood pressure
- Cholesterol and glucose levels
- Smoking, alcohol use, physical activity
- Target: Presence of cardiovascular disease (binary)

## ⚙️ Models Used
- K-Nearest Neighbors (KNN)
- Multi-Layer Perceptron (MLP)
- Support Vector Machine (SVM)
- Random Forest
- AdaBoost

GridSearchCV was used for hyperparameter tuning, and 5-fold cross-validation was applied.

## 📊 Evaluation Metrics
- Accuracy
- F1-Score
- Confusion Matrix
- ROC-AUC

Best model: **AdaBoostClassifier**  
- AUC Score: **0.78**
- Accuracy: **72.1%**

## 🧠 Feature Engineering
- BMI, MAP (mean arterial pressure), pulse pressure
- Feature importance using RandomForest
- Correlation matrix for selection

## 📌 Tools
Python, Pandas, Scikit-learn, Matplotlib, Seaborn, Jupyter Notebook

---

## ✅ How to Use
Clone the repo, install dependencies, and run the notebook:

```bash
pip install -r requirements.txt
