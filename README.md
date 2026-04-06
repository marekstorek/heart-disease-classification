# Heart Disease Prediction

## Overview
This project predicts whether a patient has heart disease using classification models trained on clinical data (e.g., age, cholesterol, blood pressure).

## Data Preparation
- **Missing values:** Replaced impossible values (e.g., `0` cholesterol) with the median computed on training data only  
- **Encoding:** Converted categorical features (e.g., chest pain type, ECG results) using one-hot encoding  
- **Implementation:** Built a custom Random Forest to better understand the algorithm  

## Models
- Random Forest  
- Decision Tree  
- K-Nearest Neighbors (KNN)  

## Validation
- Used **Cross Validation** due to the small dataset size

## Results
- **Best model:** Random Forest  
- **Recall:** 0.95  
- **Accuracy:** 0.86
- **F1-Score:** 0.89
- **ROC AUC:** 0.92

High recall is important here, as it minimizes false negatives.
