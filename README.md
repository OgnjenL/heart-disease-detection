# Heart Disease Prediction using Machine Learning

This project applies supervised machine learning to predict the presence of heart disease based on clinical and personal health data. It compares several classification models and evaluates their performance using ROC AUC, cross-validation.

---

## Dataset

- **Source**: [Kaggle](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
- **Features**: 13 medical attributes (e.g., cholesterol, resting ECG, max heart rate)
- **Target**: Binary — `1` indicates presence of heart disease, `0` indicates no disease

---

## Objectives

- Build and compare multiple classification models
- Tune hyperparameters for best performance
- Evaluate using appropriate metrics (ROC AUC, confusion matrix)


---

## Models Used

- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest Classifier
- XGBoost Classifier

---

##  Techniques Applied

- Stratified K-Fold Cross-Validation
- Hyperparameter tuning with `GridSearchCV`
- Data visualization (Seaborn, Matplotlib)
- Confusion Matrix & ROC Curve analysis

---

## Visualizations

- Correlation heatmap
- Class distribution bar chart
- Model comparison plot
- Confusion matrix
- ROC curve
  
---

## What I Learned

- How to compare models using ROC AUC and cross-validation
- The value of model interpretability in health-related tasks
- How to tune Random Forest hyperparameters effectively
  
---
