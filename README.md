# Random Forest Classifier – Customer Churn

Predict customer churn using a **Random Forest Classifier** on the BigML churn dataset.  
Includes preprocessing, hyperparameter tuning, evaluation, and feature importance analysis.

---

## 🚀 Features
- Preprocessing: imputation, one-hot encoding, stratified train/val/test split  
- Random Forest with hyperparameter tuning (GridSearchCV)  
- Metrics: Accuracy, Precision, Recall, F1, Confusion Matrix  
- Feature importance visualization  

---

## 📊 Dataset
- **Categorical**: `State`, `International plan`, `Voice mail plan`  
- **Numeric**: usage & charges (`Total day minutes`, `Total eve calls`, etc.)  
- **Target**: `Churn` (Yes/No or 0/1)  

---
## 📈 Example Results
- **Accuracy:** ~94%  
- **F1 (churn class):** ~0.76  
- **Top features:** `Customer service calls`, `Total day minutes`, `International plan`

---

## 📜 License
MIT License — free to use and adapt.
