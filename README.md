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
- Data cleaning and preprocessing
- Feature scaling (StandardScaler)
- Handling class imbalance (class weights + scale_pos_weight)
- Cross-validation (5-fold CV)
- Hyperparameter tuning (GridSearchCV)
- Model evaluation (Accuracy, F1-score, ROC-AUC)
- Feature importance analysis

---

## Results
- Best Model: XGBoost / Tuned Random Forest
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
