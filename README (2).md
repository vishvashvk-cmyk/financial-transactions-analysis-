# 📊 Financial Transactions Analysis

> **Excel-based Data Analysis Project** | Pivot Tables · SUMIFS · COUNTIFS · KPI Dashboard · Charts

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data_Analysis-1F3864?style=for-the-badge&logo=databricks&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

---

## 👤 Author

| | |
|---|---|
| **Name** | Vishvash Kumar |
| **Role** | Data Analyst |
| **Email** | vishvashvk@gmail.com |
| **LinkedIn** | [linkedin.com/in/vishvash-kumar-0518123b1](https://linkedin.com/in/vishvash-kumar-0518123b1) |
| **GitHub** | [github.com/vishvashvk-cmyk](https://github.com/vishvashvk-cmyk) |

---

## 🎯 Project Overview

This project presents a complete analysis of **100,000 real financial transactions** using **Microsoft Excel** — without any coding.

The data spans from **2018 to 2023** and includes **Credit, Debit, and Transfer** transactions. The analysis clearly reveals business cash flow patterns, top customers, monthly trends, and transaction size distribution.

---

## 📁 Dataset Information

| Field | Detail |
|-------|--------|
| 📄 File | `financial_transactions.csv` |
| 🔢 Total Rows | 1,00,000 transactions |
| 📅 Period | March 2018 – March 2023 |
| 👥 Unique Customers | 1,000 |
| 💰 Total Transaction Value | ₹50,09,01,276.83 |
| 📊 Average Transaction | ₹5,009.01 |

### Columns in Dataset

| Column | Type | Description |
|--------|------|-------------|
| `transaction_id` | Integer | Unique ID for each transaction |
| `date` | Date | Transaction date (DD-MM-YYYY) |
| `customer_id` | Integer | Customer identifier (1–1000) |
| `amount` | Float | Transaction amount in ₹ (1.29 – 10,000) |
| `type` | String | Credit / Debit / Transfer |
| `description` | String | Transaction description |

---

## 📊 Excel Sheets & Analysis

| # | Sheet Name | Analysis | Key Tool Used |
|---|-----------|----------|---------------|
| 1 | `Raw Data` | Complete dataset with filters & sorting | Auto Filter, Freeze Panes |
| 2 | `Transaction By Year` | Credit/Debit/Transfer yearly breakup + Pie Chart | Pivot Table, Chart |
| 3 | `Pivot - Monthly` | Month-wise trends + Line Chart | `TEXT()`, Pivot Table, Chart |
| 4 | `Pivot - Top Customers` | Top 20 customers by revenue + Bar Chart | Pivot Table, Top 10 Filter |
| 5 | `KPI Summary` | All key business metrics in one place | `SUMIF`, `COUNTIF`, `SUMPRODUCT` |
| 6 | `Amount Buckets` | Transaction size distribution + Bar Chart | `SUMIFS`, `COUNTIFS` |

---

## 📸 Screenshots

### 1. Raw Data Sheet
![Raw Data](screenshots/raw_data.png)

---

### 2. Transaction Amount by Type & Year (Pivot + Pie Chart)
![Pivot Type Year](screenshots/pivot_type_year.png)

---

### 3. Monthly Transaction Summary (Pivot + Line Chart)
![Monthly Summary](screenshots/monthly_summary.png)

---

### 4. Top 20 Customers by Transaction Volume (Pivot + Bar Chart)
![Top Customers](screenshots/top_customers.png)

---

### 5. KPI Dashboard
![KPI Dashboard](screenshots/kpi_dashboard.png)

---

### 6. Amount Bucket Analysis (Bar Chart)
![Amount Buckets](screenshots/amount_buckets.png)

---

## 💡 Key Business Insights

### 1. 💰 Cash Flow — Business is Well Balanced
| Type | Total Amount (₹) | Transactions | % Share |
|------|-----------------|-------------|---------|
| Credit | 16,70,98,210.90 | 33,371 | 33.4% |
| Debit | 16,75,81,463.31 | 33,298 | 33.4% |
| Transfer | 16,62,16,343.80 | 33,331 | 33.2% |

> ✅ All three types are nearly equal — no single type is dominant. The business is financially stable.

---

### 2. 📅 Monthly Trend — Consistent Growth
- **March 2018:** ₹14,11,092 (Partial month — data start)
- **Peak Period:** 2019–2022 → ₹80 Lakh+ per month consistently
- **Growth:** Significant increase from 2018 to 2022
- **2023:** Partial year data (January–March only)

---

### 3. 👑 Top 5 VIP Customers
| Rank | Customer ID | Txn Count | Total Amount (₹) | Avg per Txn (₹) |
|------|------------|-----------|-----------------|----------------|
| 🥇 1 | 853 | 129 | 6,72,412.93 | 5,212.50 |
| 🥈 2 | 30 | 121 | 6,70,374.56 | 5,540.29 |
| 🥉 3 | 802 | 127 | 6,66,947.78 | 5,251.56 |
| 4 | 115 | 126 | 6,60,453.86 | 5,241.70 |
| 5 | 222 | 127 | 6,58,742.40 | 5,186.95 |

> 💡 Top 20 customers should be offered loyalty rewards and priority service.

---

### 4. 📦 Transaction Size Distribution
| Amount Range | Count | Total Amount (₹) | % of Count | % of Amount |
|-------------|-------|-----------------|-----------|------------|
| ₹0 – ₹1,000 | 9,998 | 50,16,327.86 | 10% | 1% |
| ₹1,001 – ₹2,500 | 14,879 | 2,60,41,294.47 | 15% | 5% |
| ₹2,501 – ₹5,000 | 25,033 | 9,39,16,742.46 | 25% | 19% |
| ₹5,001 – ₹7,500 | 24,901 | 15,56,99,276.90 | 25% | 31% |
| ₹7,501 – ₹10,000 | 25,130 | 21,98,94,114.70 | 25% | 44% |

> ⚠️ The ₹0–₹1,000 range accounts for 10% of transactions but only 1% of total amount — fraud monitoring is recommended.

---

### 5. 📈 KPI Summary (at a Glance)
| KPI | Value |
|-----|-------|
| Total Transactions | 1,00,000 |
| Total Amount | ₹50,09,01,276.83 |
| Average Transaction | ₹5,009.01 |
| Max Transaction | ₹10,000.00 |
| Min Transaction | ₹1.29 |
| Credit Transactions | 33,371 |
| Debit Transactions | 33,298 |
| Transfer Transactions | 33,331 |
| Unique Customers | 1,000 |

---

## 🛠️ Tools & Formulas Used

### Microsoft Excel — No Coding Required!

| Category | Formula / Feature | Use Case |
|----------|------------------|----------|
| **Aggregation** | `SUM`, `AVERAGE`, `MAX`, `MIN` | KPI calculations |
| **Conditional Count** | `COUNTIF`, `COUNTIFS` | Type-wise count, bucket count |
| **Conditional Sum** | `SUMIF`, `SUMIFS` | Type-wise total, bucket amount |
| **Text Formatting** | `TEXT(date,"yyyy-mm")` | Creating Year-Month column |
| **Unique Count** | `SUMPRODUCT(1/COUNTIF(...))` | Finding 1,000 unique customers |
| **Pivot Tables** | Group By, Top 10 Filter | Yearly, monthly, customer analysis |
| **Charts** | Pie, Line, Bar | Visualizing trends |
| **Formatting** | Conditional formatting, Banded rows | Professional dark theme |

---

## 🏢 Business Problems Solved

| # | Problem | Solution | Impact |
|---|---------|----------|--------|
| 1 | No visibility into cash flow | Type × Year pivot + Pie Chart | Clear yearly breakup by transaction type |
| 2 | Seasonal trends were unknown | Monthly pivot + Line Chart | Identified peak and slow months |
| 3 | High-value customers were unknown | Top 20 customers + Bar Chart | VIP customers identified for retention |
| 4 | Fraud detection was difficult | Amount bucket analysis | Flagged suspicious low-value transactions |
| 5 | No single management summary | KPI Dashboard | All key metrics available in one place |

---

## 📂 Project Structure

```
financial-transactions-analysis/
│
├── 📄 README.md                           ← Project documentation (this file)
├── 📊 Financial_Analysis_Report.xlsx      ← Main Excel analysis file
│
├── 📁 data/
│   └── 📄 financial_transactions.csv      ← Raw dataset (1,00,000 rows)
│
└── 📁 screenshots/
    ├── 🖼️ raw_data.png                    ← Sheet 1: Raw Data
    ├── 🖼️ pivot_type_year.png             ← Sheet 2: Type × Year Pivot
    ├── 🖼️ monthly_summary.png             ← Sheet 3: Monthly Trends
    ├── 🖼️ top_customers.png               ← Sheet 4: Top 20 Customers
    ├── 🖼️ kpi_dashboard.png               ← Sheet 5: KPI Summary
    └── 🖼️ amount_buckets.png              ← Sheet 6: Bucket Analysis
```

---

## 🚀 How to Use This Project

1. **To view raw data** → Download `data/financial_transactions.csv`
2. **To explore full analysis** → Download `Financial_Analysis_Report.xlsx` and open in Microsoft Excel
3. **For a quick overview** → View the screenshots above
4. **To understand formulas** → Check the "Formula Used" column in the KPI Summary sheet

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">

### ⭐ If you found this project helpful, please give it a Star!

**Made with ❤️ by [Vishvash Kumar](https://linkedin.com/in/vishvash-kumar-0518123b1)**

</div>
