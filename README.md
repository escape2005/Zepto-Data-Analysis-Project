# 🛒 Zepto Inventory Data Analysis using SQL

A complete SQL-based data analytics project built on a real-world e-commerce inventory dataset inspired by Zepto's product catalog. This project demonstrates the end-to-end workflow of a Data Analyst, including database design, data cleaning, exploratory data analysis (EDA), and business-driven SQL querying to extract actionable insights.

## 📌 Project Overview

This project simulates how SQL is used in retail and e-commerce organizations to analyze inventory data, identify pricing patterns, monitor stock availability, and generate business insights.

The project covers:

* Database creation and data import
* Exploratory Data Analysis (EDA)
* Data cleaning and preprocessing
* Business-oriented SQL analysis
* Inventory and pricing analytics

---

## 📂 Dataset Description

The dataset represents an e-commerce inventory where each row corresponds to a unique product SKU.

### Attributes

| Column                 | Description                        |
| ---------------------- | ---------------------------------- |
| sku_id                 | Unique identifier for each product |
| category               | Product category                   |
| name                   | Product name                       |
| mrp                    | Maximum Retail Price (₹)           |
| discountPercent        | Discount offered (%)               |
| discountedSellingPrice | Final selling price (₹)            |
| availableQuantity      | Available inventory units          |
| weightInGms            | Product weight (grams)             |
| outOfStock             | Product stock status               |
| quantity               | Package quantity                   |

---

# 🛠️ Technologies Used

* PostgreSQL
* SQL
* pgAdmin

---

# 📋 Project Workflow

## 1. Database Design

* Created the inventory table using appropriate SQL data types
* Defined a primary key for unique SKU identification

---

## 2. Data Import

* Imported CSV data into PostgreSQL
* Handled encoding and formatting issues
* Validated successful data loading

---

## 3. Exploratory Data Analysis (EDA)

Performed initial exploration to understand the dataset by:

* Counting total records
* Identifying unique product categories
* Checking missing values
* Detecting duplicate product names
* Comparing in-stock and out-of-stock products

---

## 4. Data Cleaning

Improved data quality by:

* Removing invalid records with zero pricing
* Standardizing monetary values
* Validating inventory-related fields

---

## 5. Business Analysis

Generated meaningful business insights using SQL queries, including:

* Top discounted products
* High-value out-of-stock products
* Estimated inventory value by category
* Premium products with low discounts
* Categories with the highest average discounts
* Price-per-gram analysis
* Product weight segmentation
* Inventory weight distribution across categories

---

# 📊 Key SQL Concepts Demonstrated

* SELECT
* WHERE
* ORDER BY
* GROUP BY
* HAVING
* Aggregate Functions
* CASE Statements
* Common Table Expressions (CTEs)
* Window Functions
* Data Cleaning
* String Functions
* Numeric Calculations

---

# 📈 Sample Business Questions Solved

* Which products offer the highest discounts?
* Which expensive products are currently unavailable?
* Which categories contribute the highest inventory value?
* Which categories provide the best average discounts?
* Which products provide the best value based on price per gram?
* How is inventory distributed across different weight ranges?

---

# 📁 Repository Structure

```
├── zepto.csv
│
├── Zepto_SQL_Data_Analysis.sql
│
└── README.md
```

---

# 🚀 Learning Outcomes

Through this project, I gained practical experience in:

* Writing optimized SQL queries
* Cleaning and transforming real-world datasets
* Performing exploratory data analysis
* Extracting business insights from inventory data
* Applying SQL to solve real-world retail and e-commerce problems

---

# 💼 Portfolio Highlights

This project demonstrates skills relevant to Data Analyst, Business Analyst, and SQL Developer roles, including:

* SQL Query Writing
* Data Cleaning
* Exploratory Data Analysis
* Inventory Analytics
* Pricing Analysis
* Retail Data Analytics
* Business Intelligence

---

# 📌 Future Enhancements

* Develop an interactive Power BI dashboard
* Build Tableau visualizations
* Perform trend analysis using historical inventory data
* Add sales and customer datasets for deeper analytics

---

# 📄 License

This project is intended for educational and portfolio purposes.
