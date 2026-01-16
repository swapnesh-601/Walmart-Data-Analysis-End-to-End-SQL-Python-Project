# Walmart-Data-Analysis-End-to-End-SQL-Python-Project

![Python](https://img.shields.io/badge/Python-3.x-blue)
![SQL](https://img.shields.io/badge/SQL-MySQL%20%7C%20PostgreSQL-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![MySQL](https://img.shields.io/badge/Database-MySQL-blue)
![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL-blue)
![Project](https://img.shields.io/badge/Project-Data%20Analysis-success)

Walmart Data Analysis is an end-to-end project using Python and SQL to clean, transform, and analyze Walmart sales data. It answers key business questions on revenue, sales trends, payment methods, customer behavior, and profit analysis using MySQL and PostgreSQL.

<img width="1452" height="760" alt="Walmart Project" src="https://github.com/user-attachments/assets/86cd0990-6274-4e0c-a16e-24ab7ed76ceb" />


# Walmart Data Analysis: End-to-End SQL + Python Project

## 📌 Project Overview
This project is an **end-to-end data analytics solution** designed to extract meaningful business insights from Walmart sales data. It covers the complete analytics lifecycle—from data exploration and cleaning using **Python**, to advanced **SQL analysis** in **MySQL and PostgreSQL**, and finally publishing the project with professional documentation.

This project is well-suited for **data analysts and beginners** looking to strengthen their skills in:
- Data preprocessing and cleaning
- Feature engineering
- SQL-based business problem solving
- Data pipeline creation
- Analytics project documentation

---

## 📊 Dataset Information
- **Dataset Source:** Kaggle  
- **Dataset Link:**  
  [https://www.kaggle.com/datasets/najir0123/walmart-10k-sales-datasets--BUSINESS-PROBLEM  ](https://www.kaggle.com/datasets/najir0123/walmart-10k-sales-datasets)
- **Records:** ~10,000 sales transactions  
- **Format:** CSV  

---

## 🛠️ Tools & Technologies
- **Python** (Pandas, NumPy)
- **SQL** (MySQL, PostgreSQL)
- **SQLAlchemy**
- **Jupyter Notebook**
- **Git & GitHub**

---

## 🔍 Project Workflow

### 1. Data Exploration
**Goal:** Understand the dataset structure and identify potential issues.

**Steps Performed:**
- Used `.head()` to preview data
- Used `.info()` to check column names, data types, and null values
- Used `.describe()` to analyze data distribution and summary statistics

---

### 2. Data Cleaning
**Objective:** Ensure data accuracy and consistency.

**Key Actions:**
- Removed duplicate records
- Handled missing values by dropping or imputing where required
- Fixed incorrect data types (dates, numeric fields)
- Cleaned currency columns using `.replace()`
- Validated the final cleaned dataset

---

### 3. Feature Engineering
**New Column Created:**
- `total_amount = unit_price * quantity`

**Purpose:**  
This feature simplifies revenue, profit, and aggregation analysis in SQL.

---

### 4. Load Data into MySQL and PostgreSQL
**Steps:**
- Created database connections using SQLAlchemy
- Automated table creation
- Loaded cleaned data into both MySQL and PostgreSQL
- Verified data integrity using SQL queries

---

## 📈 SQL Business Analysis

### Business Questions Solved

1. **Payment Method Analysis**
   - Identify different payment methods
   - Number of transactions per payment method
   - Total quantity sold per payment method

2. **Highest-Rated Category per Branch**
   - Display branch, category, and average rating

3. **Busiest Day for Each Branch**
   - Based on number of transactions

4. **Quantity Sold by Payment Method**
   - List payment_method and total_quantity

5. **Product Rating Analysis by City**
   - Average rating
   - Minimum rating
   - Maximum rating

6. **Total Profit by Category**
   - Profit Formula:  
     `total_profit = unit_price * quantity * profit_margin`
   - Ordered from highest to lowest profit

7. **Most Common Payment Method per Branch**
   - Display branch and preferred payment method

8. **Sales Shift Analysis**
   - Categorized sales into:
     - MORNING
     - AFTERNOON
     - EVENING
   - Identified which shift has the highest number of invoices

9. **Revenue Decrease Analysis**
   - Identified **Top 5 branches**
   - Highest decrease ratio in revenue
   - Compared **2023 vs 2022**

---

## 📑 Key Learnings
- End-to-end data analytics pipeline development
- Writing complex SQL queries for real-world business problems
- Working with both MySQL and PostgreSQL
- Transforming raw data into actionable business insights

---

## 🚀 How to Run This Project
1. Download the dataset from the Kaggle link provided above  
2. Install required Python libraries  
3. Run data exploration, cleaning, and feature engineering in Python  
4. Load data into MySQL and PostgreSQL  
5. Execute SQL queries to generate insights  

---

## 🙏 Credits
- **YouTube Channel:** *Zero Analyst*  
- **Dataset Source:** Kaggle  

---

## ⭐ Author
**Swapnesh Das**  
Data Analytics & SQL Projects

