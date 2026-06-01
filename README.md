
# 📊 Sales & Customer Dashboard — Tableau

An interactive Tableau workbook featuring two dashboards that analyze sales performance and customer behavior across years, regions, and product categories.

---

## 🖼️ Dashboard Preview

> _Add a screenshot of your dashboard here_
> `![Dashboard Preview](dashboard_preview.png)`

---

## 📌 Project Overview

This project visualizes sales and customer data from a retail business operating across multiple regions. It allows stakeholders to compare current-year vs. prior-year performance and drill into customer-level trends.

---

## 📂 Dataset

The workbook connects to 4 CSV files:

| File | Description |
|------|-------------|
| `Orders.csv` | Order-level data — sales, profit, quantity, discount, dates |
| `Customers.csv` | Customer ID and name mapping |
| `Products.csv` | Product category, sub-category, and name |
| `Location.csv` | City, state, region, and country by postal code |

**Year range:** 2020 – 2023  
**Region:** EU market

---

## 📈 Dashboards & Sheets

### Sales Dashboard
Tracks overall business performance with year-over-year comparisons:
- **KPIs** — Total Sales, Profit, Orders, Quantity (CY vs PY with % difference)
- **Weekly Trends** — Sales and profit over time
- **Sub-Category Comparison** — Performance breakdown by product sub-category
- **Min/Max Highlights** — Best and worst performing periods

### Customer Dashboard
Focuses on customer-level analysis:
- **Customer KPIs** — Total customers, avg. sales per customer (CY vs PY)
- **Top Customers** — Ranked by sales/profit
- **Orders per Customer** — Distribution of order frequency
- **Customer Trends** — Weekly customer activity

---

## ⚙️ Features

- 📅 **Year filter (2020–2023)** — Switch between years using a parameter control
- 🔗 **Interactive filters** — Click on sub-categories, customers, or weeks to cross-filter
- 📐 **Calculated fields** — CY/PY comparisons, % differences, KPI indicators, min/max bands

---

## 🛠️ Tools Used

- **Tableau Desktop** 2026.1
- **Data source:** CSV files (Orders, Customers, Products, Location)

---

## 🚀 How to Open

1. Clone or download this repo
2. Place the CSV files in the same folder as the `.twb` file (or update the data source path)
3. Open `Sales___Customer_dashboard.twb` in Tableau Desktop

> **Note:** This is a `.twb` (not `.twbx`) file, so the CSV data files must be kept alongside it.

---

## 🔗 Live Dashboard

> _Publish to Tableau Public and paste your link here:_
> [View on Tableau Public](#)

---

## 👤 Author

**Ishaan Bhingardev**  
[GitHub](https://github.com/Ishaan9284)
