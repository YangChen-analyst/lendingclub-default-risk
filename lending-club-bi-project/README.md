
# 📊 Loan Default Risk Dashboard

**Project Type:** Business Intelligence / Data Analytics / Data Science  
**Tools Used:** Tableau, Python (Pandas), Excel  
**Data Source:** [Lending Club Loan Preprocessed Dataset on Kaggle](https://www.kaggle.com/datasets/gabrielsantello/lending-club-loan-preprocessed-dataset)

---

## 📌 Problem Statement

> **Which borrower segments are high risk, and how can we reduce loan default rates?**

## 📌 Business Problem Statement

> **The goal is to identify which borrower segments are at higher risk of loan default using Lending Club data. This will be measured by comparing default rates across variables like income range, credit grade, loan purpose, and term. By analyzing these trends, we aim to recommend actionable strategies—such as stricter approval criteria for high-risk segments—to reduce default rates. This analysis supports data-driven decision-making to improve loan portfolio performance.**
---

## 🎯 Project Objectives

Build an interactive Tableau dashboard and generate statistical insights to:

- Identify patterns in **loan default behavior**.
- Visualize and segment default risk by:
  - Income Range
  - Credit Grade
  - Loan Purpose
  - Loan Term
  - Home Ownership
  - State
- Present key KPIs to stakeholders for business decisions.

---

## 📂 Dataset Overview

This project uses a **cleaned and preprocessed version** of Lending Club’s historical loan data, which includes:

- Borrower financials (income, DTI, loan amount, etc.)
- Employment and credit history
- Loan purpose, term, and status (Fully Paid / Charged Off)
- ZIP code and derived state (cleaned from full addresses)
- Engineered fields like `Default Flag` for binary modeling

Dataset link: [Kaggle Dataset](https://www.kaggle.com/datasets/gabrielsantello/lending-club-loan-preprocessed-dataset)

---

## 📈 Dashboard Features

### 🧾 KPI Summary
- Default Rate: **19.61%**
- Avg Interest Rate: **13.64%**
- Avg Loan Amount: **$14,114**
- Avg Annual Income: **$74,203**
- Avg DTI Ratio: **17.38%**
- Total Loan Volume: **$5.6 Billion**

### 📈 Trend & Risk Visuals
- **Default Rate Over Time**: with moving average trend
- **Default Rate by Income**: $0–$25K shows 26%+ default
- **Credit Grade Breakdown**: Grades G, F, E exceed 40% default
- **Purpose**: Small Business & Moving highest risk
- **Home Ownership**: Renters more prone to default than Owners
- **Loan Term**: 60-month loans ~32% default vs 15% on 36-month
- **State Map**: Regional patterns of risk across U.S. using geo-mapping

### 📊 Visual Insights
- **Line Chart:** Default Rate trend with moving average over time
- **Bar Charts:**
  - Default Rate by **Grade**, **Purpose**, **Term**, **Income Range**, and **Home Ownership**
- **Map:** Geographic risk showing default rate by **State**

---

### 🧠 Key Insight Box
- Borrowers with **income below $50k**, **Grades E-G**, and **60-month terms** show the highest default rates.

---

## 🗺️ Geographic Risk Mapping

- Cleaned addresses into **U.S. state abbreviations** using zip code endings.
- Filtered invalid or military addresses like “FPO/APO” into “Unknown” group.

---

## 💡 Actionable Insights

- Flag high-risk segments (e.g., Grade G, Income < $25k)
- Adjust interest rates and loan terms for better risk-adjusted pricing
- Use insights to inform **credit policy** and improve loan approval criteria

---
## 💡 Key Business Insight

> Lower credit grades, longer loan terms, and income below $50k significantly increase default probability. Targeted lending strategies and more stringent approvals for high-risk segments can mitigate exposure and improve ROI.

---

## 📌 Tools Used

- **Data Cleaning**: Tableau
- **Visualization**: Tableau
- **Data Modeling**: Tableau Calculated Fields & LOD Expressions
- **Platform**: GitHub, Tableau Public

---

## 📍 Author

**Yang Chen** | Data Analyst | BI Analyst | Data Enthusiast  
[LinkedIn Profile](www.linkedin.com/in/yang-chen-34a6401a1) | [GitHub](https://github.com/YangChen-analyst) | [Tableau Link](https://public.tableau.com/app/profile/yang.chen8410/vizzes)

---

## 📁 File Structure

```
📂 LendingClub-Loan-Dashboard
│
├── lending_club_loan_two.csv        # Cleaned dataset from Kaggle
├── lending_club.twbx                # Final Tableau dashboard file
├── images/                          # Dashboard visual screenshots
│   └── dashboard_screenshot.png
└── README.md
```

---

## 🧠 Skills Highlighted

- Data Cleaning & Preprocessing
- Dashboard Design (Tableau)
- KPI Engineering
- Exploratory & Descriptive Analysis
- Business Communication of Risk Insights

---

## 📬 Contact

If you have any questions or want to collaborate, feel free to connect with me on LinkedIn or reach out via email at chenyang90098@gmail.com.
