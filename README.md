# Blood Donor Predictor

## Overview
The **Blood Donor Predictor** is a machine learning project that predicts **donor eligibility** from health records and availability data. It also includes a **recipient-matching module** to connect eligible donors with patients efficiently, helping improve blood donation management workflows.

---

## Key Features
- **Donor Eligibility Prediction:** Achieved ~90% accuracy during model evaluation.
- **Recipient Matching:** Maps eligible donors to recipients using health parameters and availability windows.
- **Robust Data Pipeline:** Includes preprocessing, feature engineering, and handling of missing/irregular data.
- **Model Tuning & Evaluation:** Hyperparameter optimization using Scikit-learn; supports multiple models for comparison.

---

## Tech Stack
- **Language:** Python  
- **Libraries:** Scikit-learn, Pandas, NumPy, Matplotlib  
- **Model:**  comparitive( Logistic Regression and Decision Tree Classifier)
- **Environment:** Jupyter Notebook / Python scripts  
- **Data Source:** Structured donor & recipient health records (CSV/DB export)

---

## How It Works
1. **Load Data:** Import donor and recipient health datasets.
2. **Preprocess:** Clean, encode, scale, and engineer relevant features (age, hemoglobin, last donation date, etc.).
3. **Train Model:** Fit and tune a Random Forest classifier (or compare models) to predict donor eligibility.
4. **Evaluate Performance:** Accuracy, precision/recall, F1 (project achieved ~90% accuracy).
5. **Predict New Donors:** Run eligibility predictions on incoming donor data.
6. **Match Recipients:** Filter eligible donors and match them to recipients based on blood group, location, and availability.

---
