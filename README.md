# task2
# E-Commerce Sales Analysis – Pivot Table Report

This repository contains the deliverables for **Task 2: Pivot Table Analysis** using the provided e-commerce transaction dataset.

## 📁 Files Included

- `ecommerce_dataset_updated.csv` — Original dataset containing transaction records.
- `Pivot_Report.xlsx` — Excel workbook with pivot tables and charts.
- `Pivot_Report.pdf` — PDF export of the pivot analysis for easy viewing.
- `Insights.txt` — Summary of 5 key business insights derived from the data.

## 📊 Analysis Overview

Using Microsoft Excel (or Google Sheets), I performed exploratory data analysis on the e-commerce dataset to uncover trends in:
- Sales performance by product category
- Payment method preferences
- Monthly sales trends
- Discount impact on final pricing

### Key Steps Performed:
1. **Data Import & Cleaning**: Loaded CSV and ensured proper formatting (dates, currency).
2. **Helper Column**: Added `Discount_Amount` = `Price - Final_Price`.
3. **Pivot Tables Created**:
   - Total Sales by Category
   - Sales by Category × Payment Method
   - Monthly Sales Trend (using `Purchase_Date`)
4. **Visualizations**: Added pivot charts and conditional formatting for clarity.
5. **Interactive Filters**: Used slicers for dynamic exploration.
6. **Insight Generation**: Derived actionable business observations.

## 💡 Sample Insights (see `Insights.txt` for full list)
- Toys and Home & Kitchen were top revenue-generating categories.
- Net Banking dominated high-value transactions.
- August–September 2024 showed peak sales, likely due to seasonal demand.
- Average discount across all products was ~22%, with Beauty offering the highest discounts.

## 🛠 Tools Used
- Microsoft Excel (or Google Sheets)
- Basic formulas (`TEXT`, subtraction for discount)
- PivotTables, PivotCharts, Slicers

## 📬 Submission
Submitted as part of the Data Analyst Internship Application – Task 2.

---
© 2026 | Prepared with ❤️ using real transaction data
