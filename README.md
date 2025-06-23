# Diabetes Prediction with Machine Learning

This project evaluates the performance of several machine learning models in predicting diabetes based on a clinical dataset of 768 individuals.

## Objective
To compare classical and advanced ML models in predicting diabetes status, with emphasis on:
- Model robustness under class imbalance
- Feature interpretability using SHAP
- Evaluation with clinical metrics like Sensitivity, Specificity, and PR-AUC

## Models Evaluated
- Logistic Regression
- XGBoost
- Random Forest
- SVM
- LightGBM

## Key Results
- **Logistic Regression** performed best: ROC-AUC 0.88, PR-AUC 0.81
- Top features: Glucose, BMI, Pregnancies, BMI_Category_obese
- Class imbalance addressed via stratification and SMOTE/SMOTETomek

## Dataset
Dataset provided by course instructor. Contains 768 samples, 8 features, and binary outcome.

## Files
- `Diabetes_Prediction.ipynb` – Full analysis notebook
- `requirements.txt` – Environment dependencies 


