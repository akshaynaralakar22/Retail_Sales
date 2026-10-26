# Retail Sales Data Analysis & Business Performance Report

## 📌 Project Overview

This project analyzes retail sales transaction data to evaluate overall business performance and identify meaningful patterns in sales, profit, products, categories, regions, customers, sales channels, and monthly trends.

The project follows a complete data analytics workflow from raw data preparation to business reporting and dashboard creation.

**Workflow:**  
Raw Data → Data Cleaning → Exploratory Data Analysis → Visualization → Business Insights → Dashboard

---

## 👩‍💻 Project Information

| Detail | Information |
|---|---|
| **Prepared By** | Akshay Ashok Naralakar |
| **Domain** | Data Analytics |
| **Project** | Week 1 Corporate Project |
| **Data Period** | January 2025 – August 2026 |
| **Initial Records** | 2,000 |
| **Final Records** | 1,985 |
| **Columns** | 16 |

---

## 🎯 Project Objective

The main objective of this project is to analyze retail sales data and understand business performance through:

- Sales and profit analysis
- Product and category performance
- Regional and city-wise performance
- Monthly sales and profit trends
- Sales channel performance
- Customer spending and purchase patterns
- Business KPIs and actionable insights

---

## 🗂️ Dataset

The dataset contains **2,000 retail transactions** and **16 columns** covering order, customer, product, sales, pricing, revenue, cost, profit, and payment information.

### Main Fields

- Order ID
- Order Date
- Customer ID
- Customer Name
- Product
- Category
- Region
- City
- Sales Channel
- Quantity
- Unit Price
- Discount
- Revenue
- Cost
- Profit
- Payment Method

---

## 🧹 Data Cleaning

The raw dataset was cleaned and validated using Python.

The following activities were performed:

- Handled missing values
- Removed duplicate Order IDs
- Removed invalid quantities
- Removed invalid unit prices
- Converted Order Date into datetime format
- Checked discount values
- Validated Revenue calculations
- Validated Profit calculations
- Checked customer name consistency
- Performed final data quality validation

After cleaning, **1,985 valid records** were retained for analysis.

---

## 📊 Key Performance Indicators

| KPI | Result |
|---|---:|
| **Total Revenue** | ₹7,394,263.75 |
| **Total Profit** | ₹2,584,863.75 |
| **Total Orders** | 1,985 |
| **Total Units Sold** | 4,171 |
| **Average Order Value** | ₹3,725.07 |
| **Profit Margin** | 34.96% |

---

## 📈 Analysis Performed

### Sales Performance
- Total revenue
- Total profit
- Total orders
- Units sold
- Average Order Value
- Profit margin

### Product & Category Analysis
- Revenue by category
- Profit by category
- Profit margin by category
- Top 10 products by revenue
- Top 10 products by profit
- Lowest-performing products

### Geographical Analysis
- Revenue by region
- Revenue by city
- Top 10 cities by revenue

### Time Analysis
- Monthly revenue
- Monthly profit
- Monthly order volume

### Sales Channel Analysis
- Online vs Offline orders
- Channel revenue
- Channel profit

### Customer Analysis
- Top 10 customers by revenue
- Repeat customers
- One-time customers
- Average customer spending

---

## 📊 Visualizations

The project includes business-focused visualizations such as:

1. Monthly Revenue Trend
2. Monthly Profit Trend
3. Revenue by Category
4. Revenue by Region
5. Top 10 Products by Revenue
6. Profit by Category
7. Orders by Sales Channel
8. Top 10 Customers by Revenue
9. Profit Margin by Category
10. Top 10 Cities by Revenue
11. Top 10 Products by Profit
12. Monthly Orders

Each visualization is designed to support a specific business question.

---

## 📋 Excel Dashboard

An interactive Excel dashboard was created using the cleaned dataset.

### KPI Cards

- Total Revenue
- Total Profit
- Total Orders
- Total Units Sold
- Average Order Value
- Profit Margin

### Dashboard Charts

- Revenue Trend
- Category Performance
- Regional Performance
- Top Products
- Sales Channel Performance

---

## 💡 Key Business Findings

- **Home & Kitchen** generated the highest category revenue of **₹2,154,376.20**.
- **Fashion** recorded the highest profit margin at **40.02%**.
- **Grocery** recorded the lowest profit margin at **26.87%**.
- **West** generated the highest regional revenue of **₹2,473,085.50**.
- **Pune** recorded the highest city revenue.
- **Air Fryer** was the highest revenue-generating product with **₹822,375.45**.
- **April 2025** recorded the highest monthly revenue of **₹452,265.30**.
- **February 2026** recorded the lowest monthly revenue of **₹242,841.50**.
- The **Online** channel generated **1,257 orders** and revenue of **₹4,671,139.55**.
- The analysis identified **422 repeat customers** and **23 one-time customers**.

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Microsoft Excel**

---

## 📁 Project Structure

```text
Week-1-Retail-Sales-Analytics/
│
├── data/
│   ├── raw_sales_data.csv
│   └── cleaned_sales_data.csv
│
├── python/
│   └── sales_analysis.ipynb
│
├── excel/
│   └── sales_dashboard.xlsx
│
├── report/
│   └── business_insights.pdf
│
└── README.md