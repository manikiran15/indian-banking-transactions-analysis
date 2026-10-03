# indian-banking-transactions-analysis
Indian Banking Transactions Analysis using Microsoft Excel — data cleaning, feature engineering, PivotTables, interactive dashboard and business insights.
# Indian Banking Transactions Analysis Using Excel

## 📊 Project Overview

This project analyzes Indian banking transaction data using Microsoft Excel.

The project follows an end-to-end data analysis workflow, starting from data understanding and cleaning, followed by feature engineering, analysis, visualization, interactive dashboard development, and business insights.

---

## 🎯 Business Objective

The main objectives of this project are:

- Analyze banking transaction patterns
- Understand regional transaction activity
- Analyze monthly transaction trends
- Understand payment-mode usage
- Examine fraud-flagged transactions by branch
- Calculate important transaction KPIs
- Build an interactive Excel dashboard
- Generate meaningful business insights

---

## 🛠️ Tools Used

- Microsoft Excel
- Excel Formulas
- PivotTables
- PivotCharts
- Slicers
- Conditional Formatting
- Data Visualization

---

## 📂 Dataset

The dataset contains 500 banking transaction records.

Important fields include:

- Transaction ID
- Customer ID
- Customer Name
- Account Number
- Region
- City
- Branch Name
- Account Type
- Transaction Type
- Transaction Amount
- Payment Mode
- Transaction Date
- Transaction Status
- Balance After Transaction
- Is Fraud

---

## 🔄 Project Workflow

### 1. Data Understanding

Reviewed the dataset structure, columns, data types, transaction information, customer information, payment information, and fraud-related fields.

### 2. Data Cleaning

Performed:

- Duplicate checking
- Missing-value checking
- Text consistency checking
- Negative-value checking
- Date validation

### 3. Feature Engineering

Created:

- Year-Month
- Net Change
- Fraud Flag
- Transaction Category
- Customer Type

### 4. Data Analysis

Performed analysis using:

- PivotTables
- Aggregation functions
- Transaction counts
- Transaction amounts
- Regional analysis
- Monthly analysis
- Payment-mode analysis
- Branch-level fraud analysis

### 5. Dashboard Development

Created an interactive Excel dashboard containing:

- Total Transactions
- Total Transaction Amount
- Average Transaction Amount
- Fraud Transactions
- Regional Transaction Volume
- Monthly Transaction Trend
- Payment Mode Usage
- Fraud Transactions by Branch

### 6. Interactive Filtering

Added slicers for:

- Region
- Payment Mode
- Transaction Type

---

## 📈 Key KPIs

| KPI | Result |
|---|---:|
| Total Transactions | 500 |
| Total Transaction Amount | ₹9,39,33,780 |
| Average Transaction Amount | ₹1,87,867.60 |
| Fraud-Flagged Transactions | 13 |

---

## 🔍 Key Insights

### Regional Activity

The North region recorded the highest transaction volume among the five regions, while East recorded the lowest.

### Payment Mode

Debit Card represented the largest payment-mode share at 26%, while Net Banking represented 16%.

### Fraud

13 out of 500 transactions were flagged as fraud, representing a 2.6% flagged-transaction rate.

### Monthly Trends

Transaction volume fluctuated across the observation period, with several peaks and declines.

---

## 📊 Dashboard

The final dashboard provides an interactive view of banking transaction activity.

It includes:

- Regional Transaction Volume
- Monthly Transaction Trend
- Payment Mode Usage
- Fraud Transactions by Branch
- KPI cards
- Interactive slicers

---

## 📁 Project Structure

```text
indian-banking-transactions-analysis/
│
├── README.md
│
├── Excel_Project/
│   └── Indian_Banking_Transactions_Analysis.xlsx
│
├── Screenshots/
│   ├── banking_dashboard.png
│   ├── data_cleaning.png
│   └── pivot_analysis.png
│
└── Documentation/
    └── Project_Documentation.pdf
