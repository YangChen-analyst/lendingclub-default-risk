
# 📊 Loan Default Risk Analysis

This repository presents a comprehensive multi-perspective analysis of Lending Club loan data, tailored to demonstrate skills relevant to BI Analysts, Data Analysts, and Data Scientists. The same dataset is analyzed through three lenses, showcasing dashboarding, statistical exploration, and predictive modeling techniques.

---

## 📁 Repository Structure

```
loan-default-risk-analysis/
│
├── BI_Dashboard_Project/
│   ├── Tableau_Dashboard.twb
│   ├── PowerBI_Dashboard.pbix
│   ├── KPI_Definitions.md
│   └── BI_Summary_Report.md
│
├── Data_Analytics_Project/
│   ├── data_cleaning.ipynb
│   ├── statistical_analysis.ipynb
│   ├── visualizations/
│   │   ├── correlation_heatmap.png
│   │   └── purpose_defaults_barplot.png
│   └── DA_Report.md
│
├── Data_Science_Modeling/
│   ├── data_preprocessing.ipynb
│   ├── model_training.ipynb
│   ├── model_results/
│   │   ├── confusion_matrix.png
│   │   └── shap_summary_plot.png
│   └── DS_Model_Report.md
│
├── data/
│   └── lending_club_loan_two.csv
│
├── README.md
└── .gitignore
```

---

## 📌 Project Summaries

### 1. BI Analyst Project — *Loan Risk Dashboard*
- **Tools:** Tableau, Power BI
- **Objective:** Identify high-risk loan segments using dashboard KPIs
- **Insights Include:**
  - Loan volume by state, employment length, and purpose
  - Default rates by credit grade and income range
  - Monthly trends in issuances and defaults

### 2. Data Analyst Project — *What Drives Loan Defaults?*
- **Tools:** Python (Pandas, Seaborn, Matplotlib)
- **Objective:** Conduct statistical analysis to find patterns in defaults
- **Techniques:** T-tests, correlation analysis
- **Outcome:** Actionable insights for stakeholders to reduce default rates

### 3. Data Science Project — *Predicting Loan Defaults*
- **Tools:** Python (scikit-learn, SHAP)
- **Objective:** Predict loan default risk using ML
- **Models:** Logistic Regression, Random Forest, XGBoost
- **Evaluation:** ROC AUC, Precision/Recall, SHAP Interpretability

---

## 🔍 Dataset

- **Source:** Lending Club Loan Data
- **Size:** ~30 features including income, employment, credit history, loan purpose, and status
- **Target Variable:** `loan_status` — categorized as Fully Paid or Charged Off

---

## 👩‍💻 Author

- **Name:** [Your Name]
- **LinkedIn:** [Your LinkedIn URL]
- **Portfolio Website:** [Optional if hosted]

---

## 📫 Contact

For collaboration or questions, feel free to reach out via GitHub or LinkedIn.
