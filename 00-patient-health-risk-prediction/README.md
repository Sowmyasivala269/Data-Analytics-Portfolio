# Patient Health Risk Prediction

## Project Overview
A machine learning dashboard that predicts heart disease risk 
and computes health scores using Electronic Health Records (EHR) data.

## Problem Statement
Early identification of high-risk patients can significantly reduce 
hospital readmissions and enable preventive care interventions.

## Approach
1. Cleaned and merged patient, observation, and condition tables
2. Handled class imbalance using SMOTENC
3. Trained XGBoost classifier for risk prediction
4. Used SHAP to explain individual predictions
5. Built interactive Streamlit app for patient decision-making

## Results
- ROC-AUC Score: > 0.98
- Model successfully identifies high-risk patients
- Integrated preventive suggestions and appointment booking

## Tools & Technologies
- Python (Pandas, NumPy)
- XGBoost, Scikit-learn
- SMOTENC (imbalanced-learn)
- SHAP for explainability
- Streamlit for deployment
- Google Colab

## Status
✅ Completed — Masters Research Project