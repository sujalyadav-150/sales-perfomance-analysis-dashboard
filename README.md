# SQLytics Sales Dashboard 🧠📊
<p align="center">
  <img src="C:\Users\hp\OneDrive\Pictures\Screenshots\Screenshot (701).png" width="900"/>
</p>
---

## 📌 Project Overview

An interactive and dynamic sales dashboard built using **Python, MySQL, and Excel**.
Designed to extract insights from Superstore data using **SQL queries**, **Power Pivot**, **Pivot Tables**, **KPIs**, and **interactive charts** — all integrated through an **ODBC connection** for a seamless, real-time analytics experience.

---

## 🧩 1. Project Workflow Overview

This project follows a structured **ETL pipeline** using three major tools:

* **Python (Pandas)**
  Used for data cleaning, preprocessing, and splitting the main dataset into three relational tables:

  * `customers.csv`
  * `products.csv`
  * `orders.csv`

* **MySQL Workbench**
  Cleaned datasets were imported as SQL tables, and optimized queries were executed to derive business insights.

* **Excel (via ODBC connection)**
  Data was dynamically connected from MySQL into Excel using Power Pivot. KPIs, Pivot Tables, Slicers, and Charts were used to build the final interactive dashboard.

---

## 🧹 2. Data Cleaning (Python - Pandas)

* Removed duplicates and empty rows
* Handled missing values
* Created a unique `customer_id`
* Split dataset into:

  * **Customers Table** – customer details, segment, region
  * **Products Table** – product, category, sub-category
  * **Orders Table** – order ID, sales, profit, discount, quantity, shipping

---

## 💾 3. SQL Database & Queries

After importing data into MySQL, the following insights were generated:

* 📦 Orders with **Shipping Delay > 5 Days** using `DATEDIFF()`
* 📊 **Percentage Contribution** of sales (customer/product-wise)
* 🌍 **Profit by Region** using `GROUP BY`
* 🏆 **Customer Ranking** using `RANK()` window function
* 📈 **Running Total Sales** (Cumulative trend analysis)
* 🚚 Sales based on **Order Priority**
* 📦 **Sales by Sub-Category**
* 👑 **Top 10 Customers by Sales**
* 🔝 **Top 10 Products by Sales**
* 📊 **KPIs Calculation**:

  * Total Sales
  * Total Profit
  * Total Quantity
* 📅 **Yearly Sales Trend Analysis**

> ✅ All queries were optimized and stored for reuse

---

## 📊 4. Excel Dashboard (via ODBC)

### 🔷 KPI Section

* Total Orders
* Total Sales
* Total Profit
* Average Discount
* Total Quantity

> 🎨 Includes icons and visual enhancements for better UI

---

### 🔷 Pivot Tables

* Month vs Sales
* Customer vs Sales
* Month vs Profit
* Region vs Sales

---

### 🔷 Charts & Visualizations

* 📈 **Line Chart** → Monthly Sales Trend
* 📊 **Interactive Bar Chart**:

  * Quantity
  * Above Average Quantity
  * Average Quantity
  * Toggle buttons for Sales / Profit / Shipping / Quantity
* 🧑‍💼 **Top 5 Customers by Sales**
* 🌍 **Region-wise Sales Distribution**

---

### 🔷 Filters & Slicers

* Year Filter
* Month Filter
* Region Filter
* Week Filter
* Country Filter (customized)

> ✅ Fully dynamic — all visuals update instantly

---

## 🎨 5. Dashboard Design & Layout

* Modern **dark theme UI** (black + blue palette)
* Clean layout using shapes and alignment
* Interactive slicers and navigation buttons
* Well-structured KPI blocks and visual hierarchy

---

## 🚀 6. Key Features

* ✅ Real-time data connection using **ODBC**
* ✅ Fully interactive dashboard
* ✅ Clean and scalable design
* ✅ Industry-level SQL + Excel integration

---

## 📎 7. Final Thoughts

This project demonstrates how **Python, SQL, and Excel** can be combined to build a **powerful business intelligence solution**.

It reflects:

* Strong data cleaning skills
* SQL analytical thinking
* Dashboard design expertise

---

## 🙌 Author

**Sujal Yadav**

---

⭐ *If you like this project, don’t forget to star the repo!*
