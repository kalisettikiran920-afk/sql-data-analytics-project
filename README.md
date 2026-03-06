# SQL Data Analytics Project for Sales Insights

This project focuses on performing **Exploratory Data Analysis (EDA)** and **Advanced SQL Analytics** on a sales data warehouse.  
The objective is to analyze business data stored in the **Gold Layer of the data warehouse** and extract meaningful insights using SQL queries.

The project demonstrates how SQL can be used for **data exploration, business analysis, and performance evaluation**.

---

## 📊 Project Objectives

The main goals of this project are:

- Explore the structure and contents of the analytical data warehouse
- Perform exploratory data analysis (EDA) on sales data
- Identify key business trends and patterns
- Generate analytical reports using SQL queries
- Demonstrate advanced SQL techniques used in real-world analytics

---

## 🏗️ Data Source

The analysis is performed on the **Gold Layer** of the data warehouse created in the previous project.

The Gold Layer contains **business-ready analytical tables**, including:

- `dim_customers` – Customer information  
- `dim_products` – Product details  
- `fact_sales` – Sales transaction data  

These tables follow a **Star Schema** optimized for analytical queries.

---

## 📖 Analysis Performed

The project includes multiple stages of analysis:

### 1️⃣ Database Exploration
Understanding the structure of the database.

Examples:
- Listing all tables
- Inspecting table columns
- Understanding schema structure

---

### 2️⃣ Dimension Exploration
Analyzing dimension tables to understand categorical attributes.

Examples:
- Customer countries
- Product categories and subcategories

---

### 3️⃣ Date Range Analysis
Understanding the time coverage of the dataset.

Examples:
- Earliest order date
- Latest order date
- Data availability period

---

### 4️⃣ Measures Exploration
Analyzing key numerical metrics.

Examples:
- Total sales
- Total orders
- Total quantity sold

---

### 5️⃣ Magnitude Analysis
Understanding the scale of business operations.

Examples:
- Total revenue generated
- Sales volume by product category

---

### 6️⃣ Ranking Analysis
Identifying top performing entities.

Examples:
- Top customers by revenue
- Top selling products
- Top performing categories

---

### 7️⃣ Change Over Time Analysis
Analyzing trends over time.

Examples:
- Monthly sales trends
- Revenue growth patterns

---

### 8️⃣ Cumulative Analysis
Tracking cumulative growth of sales metrics over time.

Examples:
- Running total of sales
- Cumulative revenue trends

---

### 9️⃣ Performance Analysis
Evaluating business performance metrics.

Examples:
- Product sales performance
- Customer contribution to revenue

---

### 🔟 Data Segmentation
Grouping customers or products into meaningful segments.

Examples:
- Customer segmentation by spending
- Product segmentation by revenue contribution

---

### 1️⃣1️⃣ Part-to-Whole Analysis
Understanding the contribution of different components.

Examples:
- Category contribution to total revenue
- Customer share of total sales

---

### 1️⃣2️⃣ Customer Report
Creating customer-focused analytical insights.

Examples:
- Customer purchase behavior
- Customer lifetime value

---

### 1️⃣3️⃣ Product Report
Analyzing product performance and profitability.

Examples:
- Best selling products
- Revenue contribution by product

---

## 📂 Repository Structure

```
sql-data-analytics-project/
│
├── scripts/
│ ├── 01_database_exploration.sql
│ ├── 02_dimensions_exploration.sql
│ ├── 03_date_range_exploration.sql
│ ├── 04_measures_exploration.sql
│ ├── 05_magnitude_analysis.sql
│ ├── 06_ranking_analysis.sql
│ ├── 07_change_over_time_analysis.sql
│ ├── 08_cumulative_analysis.sql
│ ├── 09_performance_analysis.sql
│ ├── 10_data_segmentation.sql
│ ├── 11_part_to_whole_analysis.sql
│ ├── 12_report_customers.sql
│ └── 13_report_products.sql
│
├── README.md
├── LICENSE
└── .gitignore
```

---

## 🛠️ Tools & Technologies

- SQL Server  
- SQL (T-SQL)  
- Git & GitHub  
- Data Warehouse (Gold Layer Tables)

---

## 🎯 Key Learnings

Through this project I learned:

- Performing exploratory data analysis using SQL
- Writing analytical queries for business insights
- Implementing ranking and segmentation analysis
- Analyzing trends and cumulative metrics
- Generating business reports using SQL

---

## 👤 Author

**Kiran Kalisetti**  
Data Analyst | SQL | Python | Power BI | Excel
