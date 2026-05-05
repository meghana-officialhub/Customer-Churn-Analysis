# 📊 Customer Churn Prediction & Risk Segmentation Dashboard

## 🚀 Project Overview

Customer churn is a major challenge for subscription-based businesses. This project builds an end-to-end **Machine Learning pipeline** to predict customer churn and segment customers into risk categories (**High / Medium / Low**) for proactive business decision-making.

The project combines **data analysis, machine learning, and business insights** to simulate a real-world analytics use case.

---

## 🎯 Objectives

* Analyze customer data to understand churn patterns
* Build and compare multiple ML models
* Identify key factors driving churn
* Segment customers based on churn risk
* Provide actionable business recommendations

---

## 📂 Dataset

* Dataset: **Telco Customer Churn**
* Source: Kaggle
* Records: ~7,000 customers
* Features: Demographics, services, billing, contract details

---

## 🛠️ Tech Stack

* **Python**
* **Pandas, NumPy** → Data manipulation
* **Matplotlib, Seaborn** → Visualization
* **Scikit-learn** → ML models & preprocessing
* **Jupyter Notebook** → Development

---

## 🔍 Project Workflow

### 1️⃣ Data Analysis (EDA)

* Checked missing values and data types
* Analyzed class imbalance
* Correlation heatmap

### 2️⃣ Data Preprocessing

* Handled missing values
* One-hot encoding for categorical variables
* Feature scaling using StandardScaler

### 3️⃣ Feature Engineering

* Created new features:

  * `ChargesPerMonth`
  * `SeniorWithNoSupport`

### 4️⃣ Model Training

Trained and compared:

* Logistic Regression
* Random Forest
* Gradient Boosting

### 5️⃣ Model Evaluation

* Accuracy, Precision, Recall, F1-score
* ROC-AUC score
* Confusion Matrix
* ROC Curve comparison

### 6️⃣ Customer Segmentation

* Used predicted probabilities
* Segmented into:

  * 🔴 High Risk
  * 🟡 Medium Risk
  * 🟢 Low Risk

### 7️⃣ Visualizations

* Feature importance
* Churn rate by contract type
* Tenure distribution
* Risk tier distribution

---

## 📈 Key Insights

* Customers on **month-to-month contracts** have the highest churn
* **Short tenure customers** are more likely to leave
* Higher **monthly charges** increase churn probability
* High-risk customers typically:

  * Have low tenure
  * Pay higher charges
  * Lack long-term contracts

---

## 🤖 Best Model

**Gradient Boosting Classifier** performed best based on:

* Highest ROC-AUC score
* Balanced Precision & Recall

---

## 💡 Business Recommendations

* Offer incentives to convert **monthly users to long-term contracts**
* Improve onboarding for **new customers (low tenure)**
* Provide better support for high-risk segments
* Introduce personalized retention strategies

---

## ⚠️ Limitations

* No behavioral or usage data included
* Model based only on historical data
* Can be improved with real-time data and advanced tuning

---

## 📁 Project Structure

```
Customer-Churn-Analysis/
│
├── analysis.ipynb
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── model_comparison.png
├── requirements.txt
├── charts/
│   ├── feature_importance.png
│   ├── churn_by_contract.png
│   ├── tenure_distribution.png
│   ├── risk_tier_pie.png
```

---

## 📌 How to Run

```bash
pip install -r requirements.txt
```

Open the notebook:

```bash
jupyter notebook analysis.ipynb
```

---

## 👩‍💻 Author

**Meghana M.**

---

## ⭐ If You Like This Project

Give it a ⭐ on GitHub and feel free to connect!
