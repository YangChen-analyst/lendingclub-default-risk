# 📊 Loan Default Risk Analysis — End-to-End BI, Data Analytics & Data Science Project

This project demonstrates a full pipeline — from data cleaning, exploratory data analysis (EDA), and statistical testing to predictive modeling and an interactive BI dashboard — to identify and mitigate high-risk borrower segments in Lending Club’s loan portfolio.

---

## 🚀 **Business Objective**

**Key Question:** *Which borrower segments pose higher loan default risk, and how can Lending Club adjust lending policies to reduce losses?*

By combining data analytics, machine learning, and BI visualization, this project enables stakeholders to:
- Pinpoint borrower characteristics linked to higher defaults.
- Visualize risk concentration by geography, credit grade, income, and purpose.
- Deploy predictive models to flag high-risk loans proactively.

---

## 📂 **Repository Structure**

```
loan-default-risk-analysis/
│
├── data/
| ├── lending_club_info.csv
│ └── lending_club_loan_two.csv # Cleaned Kaggle dataset
│
├── notebooks/
│ ├── 01_data_cleaning.ipynb # Missing values, feature engineering
│ ├── 02_statistical_analysis.ipynb # EDA, correlation, significance tests
│ ├── 03_model_training.ipynb # Model training, tuning, SHAP explainability
│
├── visualizations/
│ ├── correlation_heatmap.png
│ ├── purpose_defaults_barplot.png
│ ├── confusion_matrix.png
│ ├── shap_summary_plot.png
│
├── dashboard/
│ ├── lending_club.twbx # Tableau BI Dashboard
│ ├── images/
│ │ └── dashboard_screenshot.png
│
├── reports/
│ ├── DA_DS_Report.md  # Detailed write-up: EDA + ML + Insights
│ ├── Loan_Default_Risk_Report.docx  # Final formatted DS/ML report
│
├── README.md
└── .gitignore
---
```
## 📊 **Project Workflow**

| Phase | Deliverable | Tools |
|-------|--------------|-------|
| **1 Data Cleaning & Preprocessing** | Remove duplicates, handle nulls, engineer `Default Flag` | Python (Pandas) |
| **2 Exploratory Data Analysis (EDA)** | Correlation heatmaps, T-tests, pattern discovery | Python (Seaborn, Matplotlib) |
| **3 Predictive Modeling** | Logistic Regression, Random Forest, XGBoost, SHAP | scikit-learn, SHAP |
| **4 Business Intelligence Dashboard** | Interactive Tableau dashboard for business users | Tableau |
| **5 Executive Presentation** | 10-slide deck summarizing risk insights & recommendations | PowerPoint |

---

## 🗂️ **Dataset Overview**

- **Source:** [Kaggle Lending Club Dataset](https://www.kaggle.com/datasets/gabrielsantello/lending-club-loan-preprocessed-dataset)
- **Rows:** ~1M historical loan records
- **Features:** ~30 variables (income, employment, credit grade, purpose)
- **Target:** `loan_status` → Fully Paid or Charged Off
- **Key Feature Engineering:** Derived binary `Default Flag`; state-level aggregation

---


## ✅ **Key Results**

- **Best Performing Model:** XGBoost (ROC AUC: 0.72)
- **Most Influential Features:** `sub_grade`, `annual_inc`, `int_rate`, `open_acc`, `loan_amnt`
- **SHAP Explainability:** Higher `sub_grade` and `int_rate`, and lower `annual_inc` significantly drive default predictions.
- **Business Implication:** These features guide Lending Club’s risk-based loan pricing and approval strategies.


---

## 📈 **Dashboard Highlights**

The Tableau dashboard provides:
- KPI summary (default rate, loan amount, income)
- Risk by **income**, **grade**, **purpose**, **term**, **home ownership**
- Regional map of default risk across U.S. states

✅ *The dashboard helps stakeholders quickly spot emerging grid instability and adjust policies accordingly.*

---

## 💡 **Actionable Recommendations**

1. Tighten approval criteria for **Grades E–G** and incomes below **$50k**.
2. Offer shorter loan terms to reduce default exposure.
3. Adjust interest rates for risk-based pricing.
4. Monitor states with growing default clusters.
5. Integrate predictive model scores into loan origination systems.

---

## 👤 **Author**

**Yang Chen** | Data Analyst | BI Developer | Data Science Enthusiast  
- **LinkedIn:** [linkedin.com/in/yang-chen-34a6401a1](https://www.linkedin.com/in/yang-chen-34a6401a1)
- **GitHub:** [YangChen-analyst](https://github.com/YangChen-analyst)
- **Tableau Public:** [Tableau Portfolio](https://public.tableau.com/app/profile/yang.chen8410/vizzes)

---

## 📫 **Contact**

Feel free to connect on LinkedIn or open an issue for questions and collaboration opportunities!

---

---

## 🔑 **Usage**

1. Clone this repo  
2. Open notebooks in order: 1️⃣ → 2️⃣ → 3️⃣  
3. Review `DA_DS_Report.md` for a detailed narrative  
4. Open `lending_club.twbx` in Tableau for BI insights.

---

## 🏆 **This project showcases:**

- Solid BI design with Tableau.
- Robust EDA and statistical testing.
- Predictive modeling with clear explainability.
- Actionable business insights for stakeholders.

---

## ✅ Ready to mitigate loan default risk — backed by data-driven insights!
