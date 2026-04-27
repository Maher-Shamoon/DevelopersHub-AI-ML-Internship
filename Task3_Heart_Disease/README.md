# Task 3: Heart Disease Prediction

## Objective
Predict whether a patient is at risk of heart disease.

## Dataset
- **Name:** Heart Disease UCI Dataset
- **Source:** UCI ML Repository via GitHub
- **Size:** 303 patients, 14 columns
- **Target:** Binary — 1 = Disease, 0 = No Disease

## Models Applied
- Logistic Regression
- Decision Tree Classifier

## Key Results & Findings
- Both models achieved approximately 80-85% accuracy
- ROC-AUC scores above 0.85
- Chest pain type (cp) is the strongest predictor
- Max heart rate (thalach) and vessel count (ca) also important
- False Negatives are the most critical error in medical ML