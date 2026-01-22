# Loan Approval & Risk Analysis – Power BI Project

## Project Overview

This project focuses on analyzing loan approval patterns and credit risk using an interactive **Power BI dashboard**. The dashboard provides insights into approval rates, rejection trends, applicant risk profiles, and financial metrics to support data-driven decision-making in the finance and lending domain.

The analysis is based on a Kaggle-sourced loan approval dataset containing applicant demographics, income details, credit history, loan amount, and property information.

---

## Objectives

* Analyze overall **loan approval and rejection trends**
* Identify **risk factors** affecting loan rejection
* Evaluate approval rates across **income groups, CIBIL scores, assets, and demographics**
* Enable interactive exploration for business and risk analysis

---

## Key KPIs

* **Total Applications**
* **Approved Loans**
* **Rejected Loans**
* **Loan Approval Rate (%)**
* **Total Loan Amount**
* **Total Asset Value**

---

## Dataset Description

**Source:** Kaggle (Loan Approval Dataset)
**Records:** 2,000 loan applications
**Domain:** Finance / Banking / Credit Risk

### Main Columns:

* Applicant & Co-applicant Income
* Loan Amount & Loan Term
* Credit History (CIBIL indicator)
* Property Area
* Education Level
* Employment Status
* Dependents
* Loan Status (Approved / Rejected)

---

## Data Cleaning & Transformation (Power Query)

* Renamed columns for clarity and professional naming
* Corrected data types for numeric and categorical fields
* Handled missing values using **financial logic** (median loan amount, standard loan term, default credit history)
* Standardized categorical values (Yes/No, Y/N)
* Converted dependent category `3+` into numeric format
* Created derived columns such as **Approval Flag** for KPI calculations

---

## Data Modeling

* Built a clean single-table model optimized for reporting
* Created calculated columns and measures using **DAX**
* Enabled slicing by income range, CIBIL range, loan amount range, and demographics

---

## Dashboard Features

* KPI cards for instant performance overview
* Loan approval rate by:

  * Income range
  * CIBIL score range
  * Employment type
  * Education level
* Risk analysis by dependents
* Approved loans distribution by asset value range
* Rejected loans trend across income segments
* Fully interactive slicers and cross-filtering

---

## Tools & Technologies

* **Power BI Desktop**
* **Power Query** (ETL & data cleaning)
* **DAX** (KPIs & measures)
* **CSV Dataset (Kaggle)**

---

## Business Insights

* Applicants with **higher CIBIL scores and asset values** show significantly higher approval rates
* Loan rejection increases with **lower income groups and poor credit history**
* Higher number of dependents is associated with increased rejection risk
* Education and employment status influence approval probability

---

## Project Files

* `Loan Approval Project.pbix` – Power BI dashboard file
* `loan_approval_dataset.csv` – Raw dataset
* `README.md` – Project documentation

---

## How to Use

1. Download the `.pbix` file
2. Open in **Power BI Desktop**
3. Refresh data if required
4. Use slicers to explore different applicant and risk segments

---

## Author

**Liza Rani Dash**
Aspiring Data Analyst | Power BI | SQL | Advanced Excel

---

## Notes

This project is intended for **learning, portfolio, and interview demonstration purposes** in the finance and data analytics domain.
