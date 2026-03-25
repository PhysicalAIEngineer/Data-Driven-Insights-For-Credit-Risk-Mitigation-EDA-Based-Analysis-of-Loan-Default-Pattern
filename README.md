# 📊 Credit Risk Analysis using Exploratory Data Analysis (EDA)

## 🚀 Project Overview

This project focuses on analyzing loan application data to identify **key factors that lead to loan default**. Using **Exploratory Data Analysis (EDA)**, we uncover patterns in customer and loan attributes that help financial institutions minimize risk and reduce credit loss.

The goal is to assist a consumer finance company in making **data-driven lending decisions** by distinguishing between **safe and risky applicants**.

---

## 🧠 Business Problem

A lending company faces two major risks:

* ❌ **Rejecting a safe applicant** → Loss of business opportunity
* ❌ **Approving a risky applicant** → Financial loss (credit loss)

The objective is to:

> Identify **driver variables** that indicate whether a borrower is likely to default.

---

## 📂 Dataset Description

* Source: Loan data (2007–2011)
* Contains:

  * Customer demographics
  * Financial attributes
  * Loan details
  * Loan status

### 🎯 Target Variable:

* `loan_status`

  * **Fully Paid** → Non-defaulter
  * **Charged Off** → Defaulter
  * **Current** → Excluded (incomplete information)

---

## ⚙️ Tech Stack

* **Language:** Python 🐍
* **Libraries:**

  * Pandas
  * NumPy
  * Matplotlib
  * Seaborn
* **Environment:** Jupyter Notebook

---

## 🔍 Project Workflow

### 1. Data Understanding

* Examined dataset structure, features, and missing values
* Identified relevant variables for analysis

### 2. Data Cleaning

* Removed columns with excessive missing values
* Dropped irrelevant features (IDs, URLs, etc.)
* Handled data type inconsistencies
* Filtered only relevant loan statuses

### 3. Univariate Analysis

* Studied distribution of individual variables
* Identified outliers and skewness

### 4. Bivariate Analysis

* Compared features against target variable
* Calculated default rates across categories

### 5. Multivariate Analysis

* Explored relationships between multiple variables
* Correlation heatmaps and scatter plots

---

## 📊 Key Insights

### 🔥 High-Risk Indicators

* 💰 **High Interest Rate → Higher Default Probability**
* 📉 **Low Annual Income → Increased Risk**
* 🏷️ **Loan Grades E, F, G → High Default Rates**
* 🏢 **Small Business Loans → Risky Segment**
* 📊 **High Debt-to-Income (DTI) Ratio → Strong Risk Indicator**

---

### 🛡️ Low-Risk Applicants

* 💼 Stable employment history
* 💵 Higher income levels
* 🅰️ Loan grades A & B
* 📉 Lower interest rates

---

## 💡 Business Recommendations

### ✅ Risk Mitigation Strategies:

* 🚫 **Reject Loans**:

  * High DTI + Low Income + High Interest

* ⚖️ **Adjust Loan Terms**:

  * Reduce loan amount for moderate-risk applicants

* 📈 **Risk-Based Pricing**:

  * Increase interest rates for high-risk customers

* 🎯 **Target Safe Segments**:

  * Focus on high-income, low-risk borrowers

---

## 📈 Sample Visualizations

* Default rate by loan grade
* Interest rate distribution vs default
* Loan purpose vs risk
* Income vs default relationship

---

## 📁 Project Structure

```bash
credit-risk-analysis-eda/
│
├── credit_risk_analysis_eda.ipynb   # Main notebook
├── README.md                       # Project documentation
├── data/
│   └── loan.csv                    # Dataset
```

---

## 🏆 Key Learnings

* Real-world **risk analytics in finance**
* Importance of **EDA before modeling**
* Identifying **business-relevant insights from data**
* Translating data into **actionable decisions**

---

## 🔮 Future Improvements

* 🤖 Build ML models (Logistic Regression, XGBoost)
* 📊 Develop interactive dashboards (Streamlit / Plotly)
* ⚡ Feature engineering for better prediction
* 🧠 Deploy credit risk scoring system

---

## 📌 Conclusion

EDA revealed critical patterns in borrower behavior and loan characteristics that directly impact default risk. These insights can significantly improve **loan approval strategies** and reduce **financial losses**.

---

## 👨‍💻 Author

**Chetan Sonigara**
AI Research Engineer | Autonomous Systems | Machine Learning Enthusiast

---

## ⭐ If you found this useful

Give this repo a ⭐ and share it!

---
