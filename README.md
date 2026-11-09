# 🚀 Data Warehouse and Analytics Project

## 📌 Overview

This project demonstrates the development of an end-to-end **Data Warehouse and Analytics solution using Microsoft SQL Server**, following industry-standard data engineering and analytics practices.

The solution integrates sales data from two source systems (ERP and CRM), transforms raw data into structured and analytics-ready datasets, and generates meaningful business insights to support data-driven decision-making.

The project follows the **Medallion Architecture (Bronze, Silver, and Gold layers)** to ensure organized data processing, quality, integration, and accessibility for analytical reporting.

## 🎯 Project Objectives

- Build a modern SQL Server Data Warehouse.
- Integrate ERP and CRM sales data from CSV files.
- Implement the Medallion Architecture (Bronze, Silver, Gold).
- Perform data cleaning, transformation, and quality checks.
- Develop a unified data model for analytical queries.
- Generate actionable business insights using SQL.

---

## 🏗️ Data Architecture

The project follows the Medallion Architecture, consisting of three layers:

### 1. Bronze Layer – Raw Data
- Import raw ERP and CRM data from CSV files.
- Store source data in its original format.
- Maintain a centralized landing layer for incoming data.

### 2. Silver Layer – Cleaned and Transformed Data
- Clean and standardize raw datasets.
- Handle missing values, duplicates, and inconsistent data.
- Resolve data quality issues.
- Integrate ERP and CRM datasets.

### 3. Gold Layer – Business-Ready Data
- Develop analytical data models.
- Create fact and dimension tables.
- Organize data for efficient analytical queries.
- Provide business-ready datasets for reporting and insights.

---

## 📊 Project Requirements

### 1. Building the Data Warehouse (Data Engineering)

**Objective:** Develop a modern data warehouse using SQL Server to consolidate sales data and enable analytical reporting.

**Specifications:**

- **Data Sources:** Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality:** Cleanse and resolve data quality issues before analysis.
- **Integration:** Combine both sources into a unified, user-friendly data model.
- **Scope:** Focus on the latest available dataset; historical data storage is not required.
- **Documentation:** Provide clear documentation of the data model to support business stakeholders and analytics teams.

### 2. BI: Analytics and Reporting (Data Analytics)

**Objective:** Develop SQL-based analytics to generate meaningful business insights into:

- **Customer Behavior:** Understand customer profiles and purchasing patterns.
- **Product Performance:** Identify top-performing products and product categories.
- **Sales Trends:** Analyze sales performance and identify business trends.

These insights help stakeholders understand business performance and make informed strategic decisions.

---

## 🛠️ Technologies Used

|     Category    |      Technologies        | 
----------------------------------------------- 
| Database        | Microsoft SQL Server      |
| Query Language  | SQL                       |
| Architecture    | Medallion Architecture    |
| Data Sources    | ERP and CRM (CSV)         |
| Data Modeling   | Fact and Dimension Tables |
| Documentation   | Markdown, ERD             |


## 🔍 Key Business Analysis Areas

The Gold layer supports SQL-based analytical queries focusing on:

1. **Customer Analysis**
   - Customer segmentation.
   - Customer purchasing behavior.
   - Customer contribution to sales.

2. **Product Analysis**
   - Best-selling products.
   - Product category performance.
   - Revenue contribution by product.

3. **Sales Analysis**
   - Overall sales performance.
   - Sales distribution.
   - Revenue and order trends.

---


## 👩‍💻 Author

**Anamika Sreechith**

---

⭐ If you find this project interesting, feel free to explore the repository!
