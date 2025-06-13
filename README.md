# 📊 Telco Customer Churn Prediction

This project explores a real-world churn prediction problem using logistic regression and feature engineering.

---

## 📂 Dataset

- Source: [Telco Customer Churn Dataset – Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- File: `Telco-Customer-Churn.csv`
- 7,043 customer records

---

## 🧰 Tools Used

- Python, pandas, seaborn, matplotlib
- Scikit-learn for preprocessing and logistic regression
- Google Colab for development

---

## 🔑 Key Steps

1. Cleaned missing and non-numeric fields (TotalCharges)
2. One-hot encoded categorical features
3. Scaled numeric features using StandardScaler
4. Trained and evaluated a logistic regression classifier

---

## 📈 Insights

- Short-tenure, month-to-month customers were most likely to churn.
- Categorical features like `Contract` and `PaymentMethod` are strong churn indicators.
- Logistic regression gives a strong baseline with balanced precision and recall.

---

## 📈 Next Steps

- Compare performance with Random Forest or XGBoost
- Apply SHAP or LIME for feature importance explanations
- Deploy model with Streamlit or Flask

---
