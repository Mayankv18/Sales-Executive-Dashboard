# Sales-Executive-Dashboard

# 📊 Sales Executive Dashboard – Power BI Project

## 🚀 Project Overview

The **Sales Executive Dashboard** is an interactive **Power BI analytics solution** designed to help business leaders and sales managers monitor, analyze, and optimize sales performance across regions, products, and customer segments.

This dashboard transforms raw sales data into **actionable business insights** using KPIs, trend analysis, and dynamic filtering.

It is built to simulate **real-world corporate reporting**, similar to consulting/enterprise dashboards used in professional environments.

---

## 🎯 Business Objectives

The dashboard answers key business questions:

* What is the total revenue and profit performance?
* Which regions generate the highest/lowest sales?
* Which products or categories drive maximum revenue?
* How is monthly/quarterly growth trending?
* Who are the top customers and sales contributors?
* Where should management focus for improvement?

---

## 🛠️ Tools & Technologies Used

* **Power BI Desktop (.pbix)**
* Data Modeling (Star Schema)
* DAX (Data Analysis Expressions)
* Power Query (ETL & Data Cleaning)
* Interactive Visualizations
* KPI Cards & Drill-through Reports

---

## 📁 File Included

```
Sales Executive Dashboard.pbix
```

Contains:

* Data model
* Relationships
* Measures (DAX)
* Visual reports
* Dashboard layout

---

## 📊 Dashboard Features

### 🔹 Key KPIs

* Total Sales
* Total Profit
* Profit Margin %
* Total Orders
* Year-over-Year Growth %

### 🔹 Visual Insights

* Region-wise Sales Performance
* Category/Product Analysis
* Monthly Sales Trends
* Top 10 Customers
* Salesperson Performance
* Filters for dynamic exploration

### 🔹 Interactivity

* Slicers (Region, Category, Date)
* Drill-down capability
* Dynamic filtering
* Responsive visuals

---

## 🧠 Data Model Structure

### Fact Table

* Sales Transactions

### Dimension Tables

* Date
* Customer
* Product
* Region
* Salesperson

This follows a **Star Schema** for:

* Faster queries
* Better performance
* Easy scalability

---

## 📈 Sample KPIs Implemented (DAX Examples)

```DAX
Total Sales = SUM(Sales[Revenue])

Total Profit = SUM(Sales[Profit])

Profit Margin % = DIVIDE([Total Profit], [Total Sales])

YoY Growth % =
DIVIDE(
    [Total Sales] - CALCULATE([Total Sales], SAMEPERIODLASTYEAR(Date[Date])),
    CALCULATE([Total Sales], SAMEPERIODLASTYEAR(Date[Date]))
)
```

---

## 💼 Business Insights Delivered

This dashboard helps stakeholders:

✅ Identify best-performing regions
✅ Detect underperforming products
✅ Track growth trends
✅ Improve sales strategy
✅ Make data-driven decisions

---

## ▶️ How to Use

1. Download the `.pbix` file
2. Open using Power BI Desktop
3. Refresh data (if connected to external source)
4. Explore using slicers & filters
5. Analyze KPIs and trends

---

## 🎨 Dashboard Design Principles

* Clean corporate theme
* Consistent color palette
* Minimal clutter
* KPI-first layout
* Decision-focused visuals

---

## 👨‍💻 Author

Mayank Vijayvargiya
Data Analytics | Power BI | Business Intelligence

---
