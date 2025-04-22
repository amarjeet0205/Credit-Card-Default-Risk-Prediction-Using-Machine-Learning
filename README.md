# 💳 Credit Card Risk Prediction

This project aims to predict the credit risk of individuals using historical credit card usage data. We use various machine learning models to classify customers into different risk categories and identify the best-performing model.

---

## 📊 Dataset

The dataset contains the following features:

- Customer Demographics (Age, Gender, Marital Status, etc.)
- Credit Card Usage Patterns (Bill Amounts, Payment History, etc.)
- Past Payment Behavior

The target variable is the **credit risk classification** (e.g., low, medium, high risk).

---

## 🧠 Models Used

We trained and evaluated the following models:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- XGBoost Classifier

---

## 🏆 Best Model: XGBoost

After comparing performance metrics such as accuracy, precision, recall, F1-score, and ROC-AUC, **XGBoost** emerged as the best-performing model.

### ✅ Why XGBoost Performed Best:

- Handles **imbalanced data** well with built-in scale_pos_weight.
- Robust to **outliers and missing values**.
- Efficient handling of **non-linear relationships** and **feature interactions**.
- High **accuracy and generalization** across test data.
- Offers **feature importance** which helped us interpret the results.

---

## 📈 Performance Metrics (Sample)

| Model             | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|------------------|----------|-----------|--------|----------|---------|
| Logistic Regression | 78%    | 0.76      | 0.74   | 0.75     | 0.80    |
| Random Forest       | 84%    | 0.83      | 0.81   | 0.82     | 0.88    |
| **XGBoost**         | **89%**| **0.88**  | **0.87**| **0.88** | **0.93**|

---

## 📦 Requirements

- Python 3.x
- Jupyter Notebook
- pandas, numpy, matplotlib, seaborn
- scikit-learn
- xgboost

You can install them via:

```bash
pip install -r requirements.txt


