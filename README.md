# 🏦 Peak Horizon Bank Enterprise Banking Analytics

An end-to-end banking analytics solution built with Python, Snowflake, SQL, and Power BI.

This project demonstrates a complete modern Business Intelligence workflow—from raw CSV files to an interactive executive dashboard. The solution integrates data engineering, data warehousing, dimensional modeling, DAX, and dashboard design to deliver actionable banking insights.

## 📌 Project Overview

Financial institutions rely on data to monitor customer behavior, transaction activity, and account performance. This project simulates an enterprise banking analytics environment by transforming raw banking data into a scalable analytical model.

The solution includes:

* Data profiling with Python
* Data loading into Snowflake
* Data transformation using SQL
* Star schema data modeling
* Power BI semantic model
* Interactive executive dashboards
* Business-focused KPI reporting

## 🛠 Technology Stack
* Python:	Data profiling & preprocessing
* Pandas:	Data analysis
* Snowflake: Cloud Data Warehouse
* SQL: Data transformation
* Power BI:	Dashboard & visualization
* DAX: Business calculations
* GitHub: Version control

## 📂 Project Architecture
CSV Files
      │
      ▼
Python Data Profiling
      │
      ▼
Snowflake RAW Layer
      │
      ▼
Snowflake STAGING Layer
      │
      ▼
Snowflake ANALYTICS Layer
      │
      ▼
Power BI Semantic Model
      │
      ▼
Executive Dashboard

## 📊 Data Model

The solution uses a Star Schema consisting of one fact table and multiple dimension tables.

### Fact Table
* FACT_TRANSACTION

### Dimension Tables
* DIM_CUSTOMER
* DIM_ACCOUNT
* DIM_PRODUCT
* DIM_PRODUCT_CATEGORY
* DIM_PRODUCT_SUBCATEGORY
* DIM_DATE

This design improves query performance, scalability, and analytical flexibility.

## 📈 Dashboard Pages

### 📊 Page 1 — Executive Overview
Provides an overall snapshot of banking performance.

### Key KPIs
* Total Transaction Amount
* Total Transactions
* Average Transaction Amount
* Unique Customers
* Visualizations
* Transaction Amount by Product Category
* Transactions by Account Type
* Regional Performance
* Transaction Channel Analysis
* Interactive Filters

**Business Question**

*What is happening across the bank?*

### 📈 Page 2 — Performance Analytics

Focuses on trends and time intelligence.

### Features
* Monthly Transaction Trend
* 3-Month Rolling Average
* Month-over-Month Growth
* Quarter-over-Quarter Growth
* Performance Matrix

**Business Question**

*How is performance changing over time?*

### 👥 Page 3 — Customer Segmentation

Analyzes customer demographics and engagement.

### KPIs
* Total Transaction Amount
* Active Customers
* Average Account Balance
* Unique Customers

### Visualizations
* Customer Status Distribution
* Customers by Region
* Average Account Balance by Region
* Transaction Amount by Gender

**Business Question**

*Who are our customers and how are they performing?*

## 📊 Key DAX Measures

Examples of measures used throughout the report include:

* Total Transaction Amount
* Total Transactions
* Average Transaction Amount
* Average Account Balance
* Active Customers
* Unique Customers
* Rolling 3-Month Average
* Month-over-Month Change
* Quarter-over-Quarter Change

## 💼 Business Value

This solution enables decision-makers to:

* Monitor customer engagement
* Analyze transaction trends
* Compare regional performance
* Track customer activity
* Identify growth opportunities
* Support data-driven banking decisions

## 🎯 Skills Demonstrated

### Data Engineering
* Data profiling
* Data validation
* ETL concepts

### SQL
* Joins
* Aggregations
* CASE expressions
* Window functions
* Views
* Data transformations

### Snowflake
* Data warehouse design
* Schema organization
* Fact and dimension modeling
  
### Power BI
* Star schema modeling
* Relationship management
* DAX calculations
* Time intelligence
* Interactive dashboards
* KPI development

### Business Intelligence
* Executive reporting
* Performance analysis
* Customer segmentation
* Data storytelling

## ⭐ Project Summary

This project showcases the complete lifecycle of a modern Business Intelligence solution—from raw data ingestion and warehouse design to interactive dashboards and executive reporting. It demonstrates practical experience with enterprise analytics tools and best practices, including Python, Snowflake, SQL, dimensional modeling, DAX, and Power BI, to transform raw banking data into meaningful business insights.
