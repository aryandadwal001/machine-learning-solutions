# Diabetes Prediction using Linear SVM

This project predicts whether a person has diabetes using the **Pima Indians Diabetes** dataset and a **Support Vector Machine (SVM)** classifier with a **linear kernel**. The notebook contains a complete machine learning workflow: data loading, EDA, preprocessing, training, evaluation, and saving the model.

---

## Project Overview
Diabetes is a widespread public health issue. Predictive models built from diagnostic measurements can help identify at-risk individuals early. This repository demonstrates a practical, reproducible approach using **Linear SVM**—a robust and interpretable classifier when feature relationships are approximately linear.

---

## Dataset
- **Common dataset name:** Pima Indians Diabetes Dataset (available on UCI / Kaggle)
- **Features:**  
  - Pregnancies  
  - Glucose  
  - BloodPressure  
  - SkinThickness  
  - Insulin  
  - BMI  
  - Diabetes Pedigree Function  
  - Age  
- **Target:** `Outcome` (1 = Diabetic, 0 = Non-Diabetic)

---

## Model used
- **Classifier:** Support Vector Machine (SVM)
- **Kernel:** **linear**
- Linear SVM is used in the notebook implementation to classify patients as diabetic or not.

---

## Project Workflow (in Notebook)
1. **Imports** — import Python libraries (pandas, numpy, matplotlib, seaborn, scikit-learn, etc.).  
2. **Load data** — read CSV into a DataFrame and inspect shape & columns.  
3. **Exploratory Data Analysis (EDA)** — distributions, correlations, and class balance checks.  
4. **Data Cleaning** — identify and handle invalid zero values used to indicate missing data (Glucose, BloodPressure, etc.).  
5. **Feature Engineering & Scaling** — impute/replace invalid values, scale numeric features (StdScaler or MinMax).  
6. **Train/Test Split** — create reproducible train/test splits.  
7. **Modeling** — train Linear SVM (`sklearn.svm.SVC(kernel='linear')`).  
8. **Evaluation** — accuracy, precision, recall, F1-score, confusion matrix, ROC AUC (where applicable).  
9. **Predictions** — example predictions on test set / new samples.  
10. **(Optional)** Save model — use `joblib` or `pickle` to persist the trained model for deployment.

---

## Evaluation
The notebook computes standard classification metrics (accuracy, precision, recall, F1-score) and shows a confusion matrix. See the notebook’s Evaluation section for exact values and plots.

---
