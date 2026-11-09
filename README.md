# 📊 SQL Exploratory Data Analysis (EDA) Project

## 📌 Overview
This project focuses on performing **Exploratory Data Analysis (EDA) using SQL** to extract key business insights from a structured database. By leveraging SQL queries, we analyze various aspects such as **sales trends, customer behavior, and product performance** to uncover actionable insights.

## 💡 Key Objectives
- Perform **data cleaning** and preprocessing using SQL.
- Extract **sales, customer, and product insights** from a relational database.
- Utilize **aggregation, joins, window functions, and CTEs** to perform in-depth analysis.
- Optimize queries for better performance and efficiency.

## 🏗️ Database Schema
The dataset consists of multiple relational tables, including:
- **Customers**: Contains customer information (ID, Name, Location, etc.).
- **Orders**: Tracks purchases, order dates, and customer IDs.
- **Products**: Stores product details (ID, Name, Category, Price, etc.).
- **Sales**: Links orders and products to track revenue and quantity sold.

## 🔍 Key Analyses
### 1️⃣ Sales Analysis
- Total revenue, average order value, and monthly revenue trends.
- Best-selling products and categories.
- Revenue distribution across different customer segments.

### 2️⃣ Customer Insights
- Customer retention and churn analysis.
- Identifying high-value customers.
- Purchase frequency and order trends.

### 3️⃣ Product Performance
- Most and least profitable products.
- Stock and inventory turnover analysis.
- Product category-wise sales breakdown.

## 🛠️ SQL Techniques Used
- **Aggregate Functions** (`SUM`, `AVG`, `COUNT`, `MAX`, `MIN`)
- **Joins** (`INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN`)
- **Window Functions** (`ROW_NUMBER()`, `RANK()`, `DENSE_RANK()`, `LAG()`, `LEAD()`)
- **Common Table Expressions (CTEs)**
- **Subqueries and Nested Queries**
- **Group By & Having Clauses**
- **Case Statements for Conditional Analysis**

## 📂 Project Structure
```
📦 SQL-EDA-Project
 ┣ 📜 queries.sql  # Collection of SQL queries for EDA
 ┣ 📜 insights.md  # Summary of findings and key takeaways
 ┣ 📜 dataset.csv  # Sample dataset (if applicable)
 ┣ 📜 README.md    # Project documentation
```

## 🚀 How to Run
1. Clone the repository:
   ```sh
   git clone https://github.com/abhi-0404/sql-exploratory-data-analysis-project.git
   ```
2. Load the dataset into your preferred SQL database (MySQL, PostgreSQL, SQL Server, etc.).
3. Run the SQL queries from !scripts[sql-exploratory-data-analysis-project/scripts] to explore the dataset and extract insights.

## 📈 Questions This Analysis Answers

Each script answers one business question. Restore `datasets/DataWarehouseAnalytics.bak` and run them in order to reproduce every result.

| Question | Script | Technique |
|---|---|---|
| What tables and columns does the warehouse contain? | `01_database_exploration` | `INFORMATION_SCHEMA` |
| Which countries, categories and products exist? | `02_dimension_exploration` | `DISTINCT` |
| What period does the data cover, and how old are customers? | `03_date_range_exploration` | `MIN`, `MAX`, `DATEDIFF` |
| What are total sales, orders, quantity and average price? | `04_measure_exploration` | `SUM`, `COUNT`, `AVG` |
| How are revenue and customers distributed across countries and categories? | `05_magnitude_analysis` | `GROUP BY` |
| Which products and customers rank highest and lowest? | `06_ranking_analysis` | `RANK`, `DENSE_RANK`, `ROW_NUMBER` |
| How do sales change month to month and year to year? | `07_change_overtime_analysis` | `DATETRUNC`, `DATEPART` |
| What are the running totals and moving average prices? | `08_cumulative_analysis` | `SUM() OVER`, `AVG() OVER` |
| How does each product compare with its own average and last year? | `09_performance_analysis` | `LAG`, `AVG() OVER` |
| How do customers split into VIP, Regular and New, and products into cost bands? | `10_data_segmentation` | `CASE` |
| What share of total sales does each category contribute? | `11_part_to_whole_analysis` | `SUM() OVER` |
| One view per customer: segment, age group, recency, order value, monthly spend | `12_report_customers` | CTEs, segmentation |
| One view per product: performance band, recency, order revenue, monthly revenue | `13_report_products` | CTEs, segmentation |

## 🔗 Future Enhancements
- Integrate with **Power BI/Tableau** for interactive visualizations.
- Automate SQL queries using **Python scripts.**
- Expand analysis with **predictive analytics** using machine learning.

## 🤝 Contributing
Feel free to fork the repository and submit **pull requests** for improvements! Suggestions and collaborations are welcome. 🚀

## 📜 License
This project is licensed under the **MIT License**.

---
💡 *If you found this project helpful, consider giving it a ⭐ on GitHub!*

