# 📊 Task 3: SQL for Data Analysis

## 🎯 Objective
The objective of this task is to use SQL queries to extract, manipulate, and analyze structured data from an Ecommerce dataset using SQLite.

---

## 🛠 Tools Used
- SQLite
- DataGrip (JetBrains)
- GitHub

---

## 📁 Dataset

The dataset used for this task is:

Ecommerce_data.csv

The CSV file is included inside the ZIP submission.  
It contains customer, order, product, region, sales, and profit data.

Total records in dataset: **113,270 rows**

---

## 🏗 Database Design

The raw dataset (`ecommerce_raw`) was normalized into the following tables:

- `customers`
- `orders`
- `products`
- `order_items`

This improves data structure and allows proper JOIN operations.

---

## 📌 SQL Concepts Used

The following SQL concepts were applied:

- SELECT
- WHERE
- GROUP BY
- ORDER BY
- Aggregate Functions (SUM, AVG)
- INNER JOIN
- Subqueries
- CREATE VIEW
- CREATE INDEX
- Data Normalization

---

## 📈 Analysis Performed

### 1️⃣ Total Rows Validation
Verified dataset size using COUNT(*)

### 2️⃣ Revenue by Region
Calculated total sales grouped by customer region.

### 3️⃣ Top Customers by Revenue
Identified highest spending customers.

### 4️⃣ Revenue per Customer (JOIN)
Used JOIN across normalized tables to calculate revenue.

### 5️⃣ Customers Spending Above Average
Used subquery with HAVING and AVG.

### 6️⃣ View Creation
Created a view `customer_revenue` for reusable revenue analysis.

### 7️⃣ Index Optimization
Indexes created on:
- customer_id
- order_id

To improve query performance.
