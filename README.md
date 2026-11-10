# 💳 e&-Wallet-Transactions

An interactive **Excel dashboard** analyzing **5,000 digital wallet transactions** (Aug 2023 – Aug 2024) across 20 product categories, 5 payment methods, 3 device types, and 3 location types — covering revenue trends, fees, cashback, and customer payment behavior.

---

## 📌 Overview

This project turns raw digital wallet transaction data into a filterable business dashboard. It helps answer questions such as:

- How does revenue change over time?
- Which payment methods and devices drive the most transaction value?
- How much do fees and cashback cost relative to revenue?
- Which product categories (bills, travel, shopping, entertainment) generate the most value?
- How do urban, suburban, and rural users compare?

## 📊 Key Metrics

| Metric | Value |
|---|---|
| Total Revenue (Paid Amount) | **24.66M** |
| Transactions | **5,000** |
| Total Transaction Fees | **125.9K** |
| Total Cashback | **253.3K** |
| Unique Users | **3,932** |
| Merchants | **97** |
| Period | Aug 2023 – Aug 2024 |

## 🔍 Key Insights

| Area | Finding |
|---|---|
| Payment method (revenue) | Fairly balanced: **Bank Transfer** leads (5.19M), then Debit Card (5.13M), UPI (4.87M), Credit Card (4.86M), and Wallet Balance (4.60M) |
| Payment method (volume) | Bank Transfer (1,045) and Debit Card (1,022) have the most transactions |
| Device type | **Android** drives about 61% of revenue (14.96M), iOS about 30% (7.36M), Web about 9% (2.34M) |
| Location | **Urban** users make 3,485 of 5,000 transactions and pay the most fees (87.4K) |
| Top categories | Streaming Service, Water Bill, Gas Bill, Education Fee, and Movie Ticket |
| Peak months | **July 2024** (2.19M), March 2024 (2.15M), and May 2024 (2.15M) |
| Transaction status | 4,755 successful, 146 failed, 99 pending |

## 🖼️ Dashboard Components

| Visual | Description |
|---|---|
| KPI cards | Total revenue, transactions, total fees, total cashback |
| Line chart | Revenue over time |
| Bar chart | Total transactions by payment method |
| Doughnut chart | Revenue by device type |
| Pie chart | Revenue by payment method |
| Bar chart | Transactions by location type (urban, suburban, rural) |
| Slicers | Interactive filters for **Payment Method** and **Month** |

## 🗂️ Workbook Structure

| Sheet | Purpose |
|---|---|
| `Digital_Wallet_Transactions` | Raw dataset (5,000 rows × 17 columns) |
| `PivotAnalysis` | PivotTables feeding every KPI and chart |
| `Dashboard` | Final interactive dashboard with charts and slicers |

### Data Dictionary

| Column | Description |
|---|---|
| idx | Row index |
| transaction_id | Unique transaction identifier |
| user_id | Anonymized user identifier |
| transaction_date | Date and time of the transaction |
| product_category | Category (e.g. Rent Payment, Flight Booking, Streaming Service) |
| product_name | Specific product or plan purchased |
| merchant_name / merchant_id | Merchant receiving the payment |
| product_amount | Base amount of the product |
| transaction_fee | Fee charged on the transaction |
| cashback | Cashback awarded to the user |
| Paied Amount | Final amount paid after fee and cashback |
| loyalty_points | Loyalty points earned |
| payment_method | Bank Transfer, Debit Card, UPI, Credit Card, or Wallet Balance |
| transaction_status | Successful, Failed, or Pending |
| device_type | Android, iOS, or Web |
| location | Urban, Suburban, or Rural |

## 🛠️ Tools & Techniques

- Microsoft Excel
- Data cleaning and KPI design
- PivotTables and PivotCharts
- Slicers for interactive filtering

## 🚀 How to Use

1. Download or clone this repository.
2. Open the workbook in **Microsoft Excel** (2016 or later recommended).
3. Go to the **Dashboard** sheet.
4. Use the slicers to filter by payment method and month. All visuals update automatically.

> ⚠️ Slicers are not fully supported in Google Sheets or LibreOffice. Use desktop Excel for the best experience.

## 📁 Repository Structure

```
digital-wallet-transactions-dashboard/
├── digital_wallet_transactions.xlsx
├── README.md
└── screenshots/
    └── dashboard.png
```

## 👤 Author

**Mahmoud**
Data analysis
---

⭐ If you found this project useful, consider giving it a star!
