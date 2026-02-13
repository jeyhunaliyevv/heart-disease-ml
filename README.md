# Heart Disease Prediction (Medical Dataset)

## Overview
This project analyzes a medical dataset of patient health metrics and builds baseline machine learning models to predict the presence of a heart condition (**Result: 1/0**).

## Dataset
Source: Kaggle  
Size: **1318 samples, 11 features**

**Main features**
- Age
- Gender (1 = male, 0 = female)
- Heart Rate (bpm)
- Systolic / Diastolic Blood Pressure (mmHg)
- Blood Sugar (mg/dL)
- CK-MB (ng/mL)
- Troponin (ng/mL)
- Target: **Result** (1 = heart condition, 0 = no condition)

## Approach
- Data cleaning (missing values, basic checks)
- Encoding categorical variables
- Feature scaling (when needed)
- Outlier handling (when needed)
- Modeling: **Logistic Regression** and **Random Forest**
- Evaluation: Accuracy, Precision, Recall, F1-score

## Results
- Best model: **Random Forest**
- Test accuracy: **~98%**
- Key drivers: older age, higher blood pressure, and elevated cardiac enzymes (CK-MB, Troponin) are associated with higher risk.

## Repository Structure
- `MEDICAL_DATASET.ipynb` – analysis and modeling notebook
- `requirements.txt` – dependencies

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook
