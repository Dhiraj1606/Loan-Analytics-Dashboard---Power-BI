# Loan Portfolio & Borrower Risk Analytics Dashboard

An interactive **Power BI dashboard** built to analyze a loan portfolio from the perspectives of **loan exposure, borrower credit quality, financial burden, and credit risk**.

---

## Project Objective

This project transforms a raw loan dataset into an interactive reporting dashboard that answers questions such as:

- Which loan purposes contribute the most to the portfolio?
- How is loan exposure distributed across **term, home ownership, and income groups**?
- Which borrower segments show higher **credit risk, delinquency, tax lien, or bankruptcy indicators**?
- How do **monthly debt, credit utilization, and credit exposure** vary across customer groups?

---

## Dashboard Pages

### 1. Loan Portfolio Overview
Focuses on:
- total loan amount
- loan count
- average loan amount
- average annual income
- loan amount by purpose, term, home ownership, and income band

### 2. Borrower Risk & Credit Profile
Focuses on:
- average credit score
- risk band distribution
- delinquency analysis
- bankruptcy and tax lien indicators
- credit score vs loan amount analysis

### 3. Debt, Income & Credit Exposure
Focuses on:
- monthly debt by borrower segment
- debt-to-income patterns
- current credit balance vs maximum open credit
- credit utilization ratio
- income vs debt analysis

### 4. Interactive Insights & Root-Cause Analysis
Focuses on:
- decomposition tree
- waterfall chart
- portfolio health gauge
- segment-level risk contribution analysis

---

## Key Metrics / DAX Measures

- Total Loan Amount
- Loan Count
- Avg Loan Amount
- Avg Annual Income
- Avg Credit Score
- Delinquency Count / Rate
- Bankruptcy Count / Rate
- Tax Lien Count / Rate
- Credit Utilization Ratio
- Debt-to-Income Ratio

---

## Tools Used

- **Power BI Desktop**
- **Power Query**
- **DAX**
- **Excel / CSV dataset**
- **GitHub**

---

## Repository Structure

```bash
loan-portfolio-dashboard/
│
├── README.md
├── dashboard/
│   └── Loan_Portfolio_Analytics.pbix
├── data/
│   ├── raw/
│   └── cleaned/
├── screenshots/
└── docs/
