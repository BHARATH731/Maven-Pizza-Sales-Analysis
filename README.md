# 🍕 Maven Pizza Sales Analysis

## 📌 Project Overview

This repository contains a **data analytics project** focused on exploring and analyzing pizza sales data from the Maven Pizza dataset. The goal of the project is to build an **interactive Power BI dashboard** that provides meaningful insights into sales performance, product trends, and business KPIs to support data-driven decision-making.

The dashboard showcases metrics like total revenue, category-wise sales, peak sales times, and other performance indicators using interactive visualizations created in **Power BI**.

---

## 🚀 Objectives

This project was designed to:

* Analyze total pizza sales and revenue
* Break down sales by pizza category and size
* Identify top–selling and low–performing products
* Understand ordering trends by time and customer behavior
* Build an intuitive Power BI dashboard for visualization and insights

---

## 📊 Key Insights

The analyses included in this project reveal:

* **Total Sales:** Measure overall revenue generated within the period
* **Category Performance:** Compare sales across pizza categories
* **Sales Trends:** Identify peak hours, days, and order patterns
* **Product Insights:** Discover best-selling and least-selling pizzas
* **Interactive Dashboard:** Easy to filter and explore key metrics across dimensions

These insights help stakeholders refine marketing and pricing strategies, optimize inventory, and improve operational planning.

---

## 📂 Dataset

The dataset for this project includes multiple tables in CSV format representing one year of pizza sales:

| File                | Description                                        |
| ------------------- | -------------------------------------------------- |
| `orders.csv`        | Contains order IDs and timestamp of orders         |
| `order_details.csv` | Contains individual pizza orders and quantity      |
| `pizza_types.csv`   | Information about pizza categories and ingredients |
| `pizza_types.csv`   | Pizza size, price, and type details                |

These tables were used to build the data model required for reporting in Power BI.

---

## 🛠 Tools & Technologies

| Tool                                | Purpose                                    |
| ----------------------------------- | ------------------------------------------ |
| **Power BI Desktop**                | Interactive dashboard and visual analytics |
| **DAX (Data Analysis Expressions)** | Calculated measures inside Power BI        |
| **Power Query (M)**                 | Data transformation and cleaning           |
| **CSV Files**                       | Source dataset format                      |
| **GitHub**                          | Version control and project documentation  |

---

## ⚡ Performance Optimization Techniques

To ensure efficiency, scalability, and fast report performance, the following optimization strategies were implemented:

 ✅ Implemented a **Star Schema data model** for optimal query performance
 ✅ Maintained proper **Many-to-One relationships** with single-direction filtering
 ✅ Removed unnecessary columns to reduce model size and memory usage
 ✅ Avoided bi-directional relationships to prevent ambiguous filter propagation
 ✅ Used **measures instead of calculated columns** wherever possible
 ✅ Applied `SUMX()` only when row-level calculation was required
 ✅ Minimized complex nested DAX expressions
 ✅ Optimized cardinality by using appropriate key columns
 ✅ Ensured clean data types (Date, Whole Number, Decimal) for efficient storage
 ✅ Avoided redundant intermediate queries in Power Query

These practices improved dashboard responsiveness and ensured scalable performance for larger datasets.

---

## 🎯 Analytical Capabilities Enabled

The technical implementation enables powerful analytical exploration, including:

✔ Dynamic KPI tracking (Revenue, Orders, Quantity Sold)
✔ Time-based trend analysis (Daily, Monthly, Peak Hours)
✔ Category and Product-level performance breakdown
✔ Top-N and Bottom-N product analysis
✔ Revenue contribution % analysis
✔ Drill-down functionality across time hierarchies
✔ Interactive filtering across dimensions
✔ Identification of peak sales hours and high-demand periods
✔ Comparative performance analysis across pizza categories and sizes

This framework transforms raw transactional data into actionable business intelligence, supporting data-driven operational and strategic decision-making.

---

## 📈 Features & Visualizations

The Power BI dashboard includes:

✨ **KPI tiles** – Total sales, category performance, and more
📉 **Trend charts** – Time-based analysis of orders and revenue
🍕 **Category breakdowns** – Compare pizza types and sizes
🗂 **Interactive filters** – Slice data by date, category, or metric
📊 **Drill-through visuals** – Deep dive into sales performance factors

---

## 🚧 How to Use

1. Download the dataset CSV files from this repository
2. Open **Power BI Desktop**
3. Load all CSV files into Power BI
4. Set relationships between tables appropriately
5. Import the `.pbix` file (if included) for the fully built dashboard
6. Interact with slicers and visuals to explore insights

---

## ✨ What This Project Demonstrates

✔ Data modeling using real-world business data
✔ Insights through visual analytics
✔ Practical use of DAX and Power Query
✔ Dashboard storytelling for stakeholders
✔ End-to-end analytical solution
