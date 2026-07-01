# 📊 Sales Analytics Dashboard — Power BI

An interactive Power BI dashboard built on a retail sales dataset of **1,000 orders** across Indian cities, products, and customer segments. The dashboard enables quick exploration of sales performance through dynamic KPIs, charts, and slicers.


## 📌 Objective

To analyze retail sales data and build a self-service dashboard that helps stakeholders track:
- Overall revenue performance
- Sales trends over time
- Category and product-level breakdowns
- Customer segment and city-wise distribution


## 📂 Dataset Overview

| Field | Description |
|---|---|
| Order ID | Unique identifier for each order |
| Product | Name of the product sold |
| Category | Product category (Electronics, Furniture, Office) |
| Quantity Ordered | Number of units ordered |
| Price Each | Unit price of the product |
| Sales | Total sale value (Quantity × Price) |
| Order Date | Date the order was placed |
| City | City where the order was delivered |
| State | State of delivery |
| Customer Segment | Consumer, Corporate, or Home Office |

- **Total Records:** 1,000 orders
- **Date Range:** January 2024 – December 2025
- **Cities Covered:** Mumbai, Delhi, Bengaluru, Chennai, Hyderabad, Kolkata, Pune, Ahmedabad
- **Products:** Laptop, Phone, Monitor, Mouse, Keyboard, Headphones, Notebook, Desk Chair, Table, Printer

---

## 📊 Dashboard Features

### 🔢 KPI Cards
| Metric | Value |
|---|---|
| Total Sales | ₹10,99,150 |
| Total Orders | 1,000 |
| Average Order Value (AOV) | ₹1,099 |

### 📈 Visualizations
- **Bar Chart** — Sum of Sales by Product
- **Line Chart** — Sum of Sales by Month (trend over time)
- **Pie Chart** — Sum of Sales by Category (Electronics, Furniture, Office)

### 🎛️ Interactive Slicers / Filters
- Product
- Category
- City
- Customer Segment



## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Excel | Data storage and cleaning |
| Power Query (Power BI) | Data transformation |
| Power BI Desktop | Dashboard design and publishing |
| DAX | KPI measures (Total Sales, AOV) |



## 🔄 Steps Followed

1. **Data Collection** — Gathered raw retail sales data with 1,000 records
2. **Data Cleaning** — Removed duplicates, handled nulls, standardized date formats in Excel
3. **Data Import** — Loaded the cleaned `.xlsx` file into Power BI via Power Query
4. **Data Modeling** — Verified data types, created calculated columns/measures using DAX
5. **Dashboard Design** — Built KPI cards, charts, and slicers on a 2-page layout


## 💡 Key Insights

- **Electronics** dominates sales with **74%** of total revenue
- **Furniture** accounts for **19%** and **Office** for the remaining **7%**
- Sales trend shows seasonal peaks — identifiable from the monthly line chart
- **Corporate** and **Consumer** segments are the primary buyers across major cities




