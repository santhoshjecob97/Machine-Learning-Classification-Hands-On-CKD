# Machine-Learning-Classification-Hands-On-CKD
# 🧠 Chronic Kidney Disease (CKD) Prediction using Classification Algorithms

This project builds and compares multiple machine learning classification models to predict whether a patient has **Chronic Kidney Disease (CKD)**, using a given dataset from a hospital.

---

## 📁 Files Included

- `CKD Using Classifications Algo.ipynb`: Full notebook with step-by-step implementation and outputs.
- `model.pkl`: Final Random Forest model saved with best accuracy.
- `output/classification_report_random_forest.txt`: Evaluation report.
- `output/model_comparison_table.csv`: Comparison of all models.
- `requirements.txt`: Libraries used in the project.

---

## ✅ Steps Covered

1. **Problem Statement**  
   Predict CKD status using patient medical attributes.

2. **Dataset Info**  
   - Rows: 400  
   - Features: 24 (mixed categorical and numerical)

3. **Preprocessing**  
   - Null value handling  
   - Label encoding & one-hot encoding  
   - Feature scaling (where required)

4. **Model Building & Tuning**  
   - Logistic Regression  
   - K-Nearest Neighbors  
   - Decision Tree  
   - Random Forest ✅ (Selected)  
   - Support Vector Machine  
   - Naive Bayes

5. **Evaluation Metrics**  
   - Accuracy  
   - Precision, Recall, F1-Score  
   - Confusion Matrix  
   - ROC AUC (for final model)

6. **Best Model**  
   - Random Forest  
   - Accuracy: 98%  
   - Chosen for its robustness and generalization

---

## 🔍 How to Run

1. Clone the repo
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
