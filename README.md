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

## 📈 Sample Insights
- **Top 10 products contribute to 60% of total sales.**
- **Customers from Region X have the highest average order value.**
- **Repeat customers generate 3x more revenue than new customers.**

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

