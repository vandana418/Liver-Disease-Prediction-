# 🩺 Indian Liver Disease Prediction (ILPD)

This project uses machine learning techniques to predict whether a patient is likely to suffer from a liver disease using the **Indian Liver Patient Dataset (ILPD)**. The model is trained on various clinical and demographic features to assist early diagnosis and treatment.

---

## 🎯 Objective

To build a classification model that can predict liver disease status (1: liver disease, 2: no liver disease) using patient health indicators and clinical test results.

---

## 📊 Dataset Information

- **Dataset Source**: UCI Machine Learning Repository  
- **Records**: 583 patients  
- **Features**:
  - Age
  - Gender
  - Total Bilirubin
  - Direct Bilirubin
  - Alkaline Phosphotase
  - Alamine Aminotransferase (ALT)
  - Aspartate Aminotransferase (AST)
  - Total Proteins
  - Albumin
  - Albumin and Globulin Ratio
  - **Target**: Liver Disease (1: patient, 2: not a patient)

---

## 🔍 Workflow

1. **Data Preprocessing**
   - Handling missing values (e.g., Albumin/Globulin Ratio)
   - Encoding gender (Male/Female)
   - Scaling numerical features

2. **Exploratory Data Analysis (EDA)**
   - Visualizing feature distributions
   - Class imbalance detection
   - Correlation analysis

3. **Model Building**
   - Algorithms used: Logistic Regression, Random Forest, SVM, XGBoost
   - Hyperparameter tuning using GridSearchCV

4. **Evaluation**
   - Accuracy, Precision, Recall, F1-Score
   - Confusion Matrix and ROC Curve

5. **Model Saving**
   - Final model saved as `liver_disease_model.pkl`

---

## 🧰 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- XGBoost
- Jupyter Notebook

---
