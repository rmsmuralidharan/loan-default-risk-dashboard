# Loan Default & Credit Risk Analysis Dashboard

An interactive Power BI dashboard analyzing loan-level data to identify which borrower and loan segments drive credit risk, and how much capital is at risk as a result.

## Business Problem
Which customer and loan segments are driving loan defaults, and how much capital is the lender exposed to? This project consolidates borrower characteristics and loan attributes into a single interactive view to help risk and finance teams spot patterns quickly.

## Tools Used
- **Power Query** – data cleaning and transformation
- **Power BI** – data modeling (DAX) and dashboard visualization
- **Dataset:** Lending Club Loan Data (Kaggle, public dataset), 2015 loan issuance

## Dashboard Pages
1. **Overview** – Portfolio-level KPIs (Total Loans, Default Rate %, Amount at Risk) and issuance trend
2. **Borrower Risk Profile** – Default rate by home ownership, employment length, and loan purpose
3. **Grade Analysis** – Default rate and interest rate by loan grade (A–G), and dollar exposure by grade

## Key Insights
- Portfolio default rate: **[X]%**, with **$[X]M** in funded amount at risk
- [Borrower segment] shows the highest default rate among home ownership categories
- Borrowers with less than 2 years of employment default at a higher rate than tenured borrowers
- Grade F/G loans default at roughly **[X]x** the rate of Grade A loans, while interest rates only rise **[X]x** — suggesting risk may be underpriced at lower grades

## Files
- `Loan_Risk_Dashboard.pbix` – Power BI dashboard file
- `screenshots/` – Exported dashboard page images
- `BRD_Loan_Risk_Dashboard.docx` – Business Requirements Document

## Data Source
[Lending Club Loan Data – Kaggle](https://www.kaggle.com/datasets/wordsforthewise/lending-club) (raw CSV not included due to file size; download from source to reproduce)
