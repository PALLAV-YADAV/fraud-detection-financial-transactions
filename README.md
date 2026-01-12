# Fraud Detection in Financial Transactions

## 📌 Project Overview
This project presents an end-to-end machine learning solution for detecting fraudulent
financial transactions. The goal is to proactively identify fraud while providing
actionable insights that can be implemented in real-world financial systems.

The project was completed as part of a Data Science & Machine Learning internship
assignment.

---

## 🧠 Business Problem
Financial institutions face significant losses due to fraudulent transactions.
Fraud cases are rare but highly costly, making early detection critical.

This project focuses on:
- Identifying fraudulent transactions
- Understanding key fraud indicators
- Proposing prevention strategies
- Evaluating effectiveness of fraud detection systems

---

## 📂 Dataset
- Transaction-level financial dataset
- ~6.3 million records
- Highly imbalanced target variable (`isFraud`)
- Link: https://drive.usercontent.google.com/download?id=1VNpyNkGxHdskfdTNRSjjyNa5qC9u0JyV&export=download&authuser=0

**Key Features:**
- Transaction type
- Transaction amount
- Account balances before and after transactions
- Engineered balance difference features

> Dataset used strictly for academic and evaluation purposes.

---

## ⚙️ Methodology
1. Data understanding & preprocessing
2. Missing value, outlier & multicollinearity analysis
3. Exploratory Data Analysis (EDA)
4. Feature engineering & selection
5. Handling class imbalance
6. Model training & evaluation
7. Model interpretation
8. Business recommendations

---

## 🤖 Models Used
- **Logistic Regression** (Baseline)
- **Random Forest Classifier** (Final Model)

Random Forest was selected due to its superior recall and F1-score for fraudulent
transactions.

---

## 📊 Evaluation Metrics
Due to class imbalance, the following metrics were emphasized:
- Recall (Fraud Detection)
- Precision
- F1-score
- Confusion Matrix

---

## 🔍 Key Fraud Indicators Identified
- High transaction amounts
- Large balance inconsistencies
- Transaction types: TRANSFER and CASH_OUT
- Abnormal post-transaction balances

These indicators align with real-world fraud behavior.

---

## 🛡️ Fraud Prevention Recommendations
- Real-time monitoring of high-risk transaction types
- Dynamic thresholds for large transactions
- Balance consistency checks
- Velocity-based transaction controls
- Model-based risk scoring

---

## 📈 Measuring Effectiveness
- Reduction in fraud rate
- Monitoring false positives
- Recall & precision tracking
- A/B testing
- Financial loss reduction analysis

---

## 🧪 Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📁 Repository Structure
├── Fraud_Detection_Accredian.ipynb

├── README.md


---

## 📌 Conclusion
The project demonstrates how machine learning can be effectively applied to fraud
detection while maintaining interpretability and business relevance. The proposed
solution is scalable and suitable for real-world deployment.

---

## 👤 Author
**Pallav Yadav**  
(Data Science & Machine Learning)
