# 📊 Customer Churn Prediction – End-to-End Machine Learning Project

**Author:** Deepesh Gautam  
**Role:** BI / Data Scientist | Aspiring AI Expert  
**Date:** August 2025  

---

## 🚀 Project Overview
Customer churn is a critical challenge for subscription-based businesses.  
This project predicts which customers are most likely to churn, enabling proactive retention strategies.

We built, evaluated, and improved multiple models (Logistic Regression, Random Forest, XGBoost) and generated actionable business insights.

---

## 🛠 Tech Stack
- **Languages:** Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost)
- **Tools:** Jupyter Notebook
- **Techniques:** Data preprocessing, feature engineering, model evaluation, business insight generation

---

## 📂 Dataset
- **Source:** [Telco Customer Churn Dataset – Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn)
- **Size:** ~7,000 records, 20+ features
- **Target Variable:** `Churn` (Yes / No)

---

## 📈 Workflow
1. **Problem Definition**
2. **Data Overview**
3. **Data Preprocessing**
4. **Baseline Model – Logistic Regression**
5. **Model Improvement – Random Forest & XGBoost**
6. **Feature Importance Analysis**
7. **Business Recommendations**
8. **Conclusion & Next Steps**

---

## 📊 Results
| Metric              | Logistic Regression | Random Forest | XGBoost |
|--------------------|--------------------|---------------|---------|
| Accuracy           | 0.80               | 0.83          | **0.85**|
| ROC-AUC            | 0.84               | 0.87          | **0.89**|
| Precision@Top10%   | 0.71               | 0.75          | **0.78**|

---

## 💡 Key Insights
- High **MonthlyCharges** + Low **Tenure** → High churn probability.
- Customers paying via **Electronic Check** churn more often.
- Customers with fewer additional services are more likely to leave.

---

## 📌 Recommendations
- Offer **loyalty discounts** to new customers within the first 3 months.
- Encourage **auto-payment options** with incentives.
- Bundle additional services to improve retention.

---

## 🖥 How to Run
```bash
## 🔗 Quick Access

- 📂 **GitHub Repo:** [Dvipg / customer-churn-prediction](https://github.com/Dvipg/customer-churn-prediction)
- 📄 **View Notebook on GitHub:** [customer-churn-prediction-end-to-end.ipynb](customer-churn-prediction-end-to-end.ipynb)
- 🚀 **Run in Google Colab:** [Open in Colab](https://colab.research.google.com/github/Dvipg/customer-churn-prediction/blob/main/customer-churn-prediction-end-to-end.ipynb)
- 📜 **PDF Report:** [Download PDF](customer-churn-prediction-end-to-end.pdf)
- 📦 **Requirements:** [requirements.txt](requirements.txt)


# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook Churn_Prediction_Project.ipynb
