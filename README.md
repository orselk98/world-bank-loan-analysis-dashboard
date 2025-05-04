# 🌍 World Bank IBRD Loan Analysis Dashboard (Excel Project)

This is an Excel-based dashboard project analyzing global loan data from the **World Bank IBRD (International Bank for Reconstruction and Development)**.

The dataset provides the latest snapshot of loans and guarantees issued to countries worldwide, including loan statuses, disbursements, repayments, and more — giving insight into the **scale and flow of global development finance**.

---

## 🚀 Project Overview

**Goal:**  
To analyze, visualize, and summarize global lending trends using only **Microsoft Excel** — including **Power Pivot**, **PivotTables**, **DAX**, and dynamic visualizations — and deliver a polished dashboard for stakeholders.

---

## 🧭 Workflow Summary

### 1️⃣ Data Source

- Source: [World Bank IBRD Loan Snapshot (April 2025)](https://financesone.worldbank.org/ibrd-statement-of-loans-and-guarantees-latest-available-snapshot/DS00047)
- Format: CSV with thousands of rows of project-level data

### 2️⃣ Initial Steps

- Cleaned missing values (countries, amounts, statuses)
- Verified and formatted currency fields
- Standardized column names
- Removed records with no financial significance

### 3️⃣ Analysis (Power Pivot + DAX)

Key measures created:
- Total loan amounts
- Disbursed vs undisbursed balances
- Remaining loan amounts (Due + Undisbursed)
- Disbursement rate (disbursed ÷ total original loan)
- Repayment amounts
- Average loan size
- Loan trends over time

Used **Power Pivot** to build a data model and define relationships (e.g., countries ↔ projects).

### 4️⃣ Dashboard Design

Built an interactive Excel dashboard with:
- Key metrics: Borrowing countries, active loans, disbursement rates, avg. loan size
- Top borrowers by total loan, current debt, and remaining balance
- Disbursement performance by country
- Regional breakdown of lending
- Time series trend: Loan approvals since 1970
- Slicers for timeline and region (interactive)

---

## 📊 Tools Used

| Tool | Purpose |
|:---|:---|
| **Excel** | Core environment for analysis and dashboard |
| **Power Pivot** | Data modeling and DAX calculations |
| **DAX** | KPIs and custom measures (e.g. average loan, disbursement %) |
| **PivotTables/Charts** | Dynamic visualization |
| **Slicers & Timelines** | Interactive filtering for stakeholders |

---

## 🔍 Key Insights

- Over **$923B** in total loans analyzed across **147 countries**
- India, Brazil, and Indonesia are top borrowers by total loan amount
- Average loan size is **$99M**, with over **7,000 projects financed**
- Global disbursement rate is ~**80%**, indicating high loan activity
- Clear regional trends, with Latin America and East Asia as key regions

---

## 🗂️ Files Included

- `ibrd_loan_project.xlsx` — fully interactive Excel dashboard
- `dashboard_ibrd.pdf` — formatted PDF export for quick view
- `dashboard_sc.png` — image for sharing and previews

---

## 📌 How to Use

1. Open the Excel file in Microsoft Excel (2016 or later recommended)
3. View or export charts/metrics for reporting

---

## 💡 About This Project

This was a personal analytics project built entirely in Excel without using any external BI tools — to show what’s possible inside a familiar environment when combining data modeling and design thinking.

---

## 🔗 Links

- 📊 [Live Data Source – World Bank](https://financesone.worldbank.org/ibrd-statement-of-loans-and-guarantees-latest-available-snapshot/DS00047)
---

📫 Feel free to reach out or fork the repo if you'd like to build on this or collaborate!

