# Cardiovascular Disease Prediction Using Machine Learning

## Project Overview
This project predicts the likelihood of cardiovascular disease using patient health and lifestyle data. The goal is to build and compare multiple machine learning models to identify the most effective approach for classification.

---

## Dataset
The dataset contains medical examination data including:
- Age
- Gender
- Blood pressure (systolic & diastolic)
- Cholesterol levels
- Glucose levels
- Smoking, alcohol intake, and physical activity
- Target: Presence of cardiovascular disease (0 = No, 1 = Yes)

---

## Models Used
- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier

---

## Techniques Applied
- Data cleaning and preprocessing (removal of invalid medical values and ID column)
- Feature scaling using StandardScaler for numerical variables
- One-hot encoding for categorical variables (gender, cholesterol, glucose)
- Handling class imbalance using class weights and XGBoost scale_pos_weight
- Machine learning pipelines using Scikit-learn Pipeline for structured preprocessing + modeling
- 5-fold cross-validation for robust model evaluation
- Hyperparameter tuning using GridSearchCV (Random Forest optimization)
- Model evaluation using Accuracy, F1-score, and ROC-AUC
- Feature importance analysis for model interpretability (XGBoost)

---

## Results
- Best Performing Model: Tuned Random Forest (slightly higher accuracy)
- XGBoost achieved the best ROC-AUC (better ranking performance)
- Accuracy: ~0.73
- ROC-AUC (XGBoost): ~0.79

---

## Visualizations
- Class distribution plot
- Confusion matrix
- ROC curve
- Feature importance plot

---

## How to Run the Project

1. Install dependencies:
pip install -r requirements.txt

2. Open Jupyter Notebook:
Heart Disease Prediction.ipynb

3. Run all cells to reproduce results.

---

## Key Insight
Feature importance analysis showed that systolic blood pressure (ap_hi) and cholesterol levels were the strongest predictors of cardiovascular disease.
