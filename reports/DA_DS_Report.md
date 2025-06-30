# Loan Default Risk Analysis Report — Data Analytics & Data Science

## 📊 Key Data Insights

- **Higher interest rates (`int_rate`) and lower annual incomes (`annual_inc`) are strongly associated with defaults.**
- **Loans with 60-month terms are significantly riskier than 36-month terms.**
- **Subgrades G1–G5 are most predictive of default**, followed by high revolving credit utilization.
- **Defaulted loans tend to have larger loan amounts and monthly installments.**
- **SHAP analysis confirms that `sub_grade`, `int_rate`, and `annual_inc` are the most impactful features across predictions.**
- **Chi-square tests reveal that `grade`, `purpose`, `home_ownership`, and `verification_status` are significantly associated with default likelihood.**

## 1. Executive Summary
This report presents a comprehensive analysis of the Lending Club loan dataset, focusing on identifying key factors that contribute to loan defaults. The analysis integrates data cleaning, exploratory data analysis (EDA), statistical testing, predictive modeling using Logistic Regression, Random Forest, and XGBoost, and interpretability using SHAP. The goal is to guide Lending Club’s lending strategies and minimize default risk.

## 2. Data Overview
- Source: Kaggle Lending Club Dataset
- Total Records: ~396,000
- Features: ~30
- Target Variable: `loan_status` converted to binary `default_flag`
- Key Variables: `int_rate`, `loan_amnt`, `annual_inc`, `grade`, `sub_grade`, `purpose`, `dti`, `revol_util`

## 3. Model Performance Comparison
**Metrics Summary:**
- Logistic Regression: F1-Score (Default class) = 0.41, ROC AUC = 0.67
- Random Forest: F1-Score = 0.11, ROC AUC = 0.70 (but poor recall)
- XGBoost: F1-Score = 0.43, ROC AUC = 0.72 — Best overall balance

## 4. SHAP Explainability Insights
SHAP values provided interpretability of XGBoost model outputs. Top features impacting default prediction include:
- `sub_grade`: Higher sub-grades (e.g., G5) strongly linked to defaults.
- `annual_inc`: Lower incomes increase default risk.
- `int_rate`: High interest rates push loans toward default.
- `open_acc`, `loan_amnt`, `dti`, and `revol_util` also play significant roles.

## 5. Actionable Recommendations
- Tighten lending for grades E–G and sub-grades G1–G5.
- Prioritize applicants with lower DTI and higher income.
- Consider rate adjustments for high-risk segments.
- Use SHAP and predictive model scores to flag high-risk borrowers during underwriting.

## 6. Appendix
Refer to Jupyter notebooks for full code, plots, and evaluation outputs.

