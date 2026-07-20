# 📊 Sales Performance Dashboard

An interactive **Power BI dashboard** designed to analyze sales performance using business transaction data. The dashboard provides key insights into sales trends, profitability, regional performance, and customer purchasing patterns through dynamic visualizations and KPIs.

---

## 📌 Project Overview

This project demonstrates the use of **Power BI**, **DAX**, and **Power Query** to transform raw sales data into meaningful business insights. It enables users to monitor overall sales performance and make data-driven decisions using interactive visuals and filters.

---

## 🎯 Objectives

- Analyze overall sales performance
- Track monthly sales trends
- Compare sales across different regions
- Analyze product category performance
- Visualize payment mode distribution
- Build an interactive business dashboard

---

## 🛠️ Tech Stack

- Microsoft Power BI
- DAX (Data Analysis Expressions)
- Power Query
- Microsoft Excel

---

## 📂 Dataset

The dataset includes business transaction details such as:

- Order ID
- Order Date
- Customer Name
- Product Category
- Sales
- Profit
- Quantity
- Region
- Payment Mode

---

## 📊 Key Performance Indicators (KPIs)

- 💰 Total Sales
- 📈 Total Profit
- 📦 Total Quantity Sold
- 🛒 Total Orders

---

## 📈 Dashboard Features

- Monthly Sales Trend
- Sales by Category
- Sales by Region
- Sales by Payment Mode
- Interactive Filters (Region, Category & Payment Mode)

---

## 🧮 DAX Measures

```DAX
Total Sales =
SUM(SalesData[Sales])

Total Profit =
SUM(SalesData[Profit])

Total Quantity =
SUM(SalesData[Quantity])

Total Orders =
DISTINCTCOUNT(SalesData[Order_ID])

Average Order Value =
DIVIDE([Total Sales],[Total Orders])

Profit Margin % =
DIVIDE([Total Profit],[Total Sales])
```

---

## 📷 Dashboard Preview

![Sales Dashboard](Dashboard.PNG)

---

## 💡 Business Insights

- Identified monthly sales trends to understand business performance.
- Compared sales across different product categories.
- Analyzed regional sales contribution.
- Evaluated customer payment preferences.
- Built an interactive dashboard for faster business decision-making.

---

## 🚀 Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Modeling
- DAX Calculations
- Power Query
- Dashboard Design
- KPI Reporting
- Data Visualization
- Business Intelligence

---

## 📬 Contact

**Alisha Khot**

- LinkedIn: https://www.linkedin.com/in/alisha-khot-09825321b/
- GitHub: https://github.com/alisha1809

---

⭐ If you found this project useful, consider giving it a star!

