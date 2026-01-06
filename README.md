 # 🛒 Customer Shopping Behavior Analysis

An end-to-end **Data Analytics project** using **Python, SQL, and Power BI** to analyze customer purchasing behavior and generate actionable business insights.

---

## 📌 Project Overview

This project analyzes customer shopping data to understand **purchasing patterns, revenue drivers, product performance, discount behavior, shipping preferences, and subscription impact**.  
It follows the complete analytics lifecycle—from raw data cleaning to SQL-driven insights and interactive dashboards.

The project is designed to simulate **real-world business analytics work**, making it suitable for **Data Analyst / Business Analyst roles**.

---

## 🎯 Business Objectives

- Identify high-value customer segments  
- Analyze the impact of discounts and subscriptions on revenue  
- Evaluate product and category performance  
- Understand customer behavior to improve retention and pricing strategy  

---

## 📁 Dataset Description

The dataset contains customer-level transaction data with the following fields:

### Customer Details
- Gender  
- Age group  
- Subscription status  

### Purchase Information
- Item purchased  
- Product category  
- Purchase amount  
- Discount applied  

### Behavioral Indicators
- Review rating  
- Previous purchases  

### Shipping Details
- Shipping type  

📌 All preprocessing and transformations are handled within the project notebook.

---

## 🛠 Tools & Technologies

| Task | Technology |
|-----|-----------|
| Data Loading & Cleaning | Python (Pandas, NumPy) |
| Exploratory Data Analysis | Python (Matplotlib, Seaborn) |
| Business Queries | SQL (PostgreSQL / MySQL / SQL Server) |
| Dashboard & Visualization | Microsoft Power BI |
| Reporting & Presentation | Gamma / PowerPoint |

---

## 🔍 SQL Analysis

SQL queries were written to answer key business questions such as:

- Revenue comparison by gender  
- Top 5 highest-rated products  
- Discount usage and spending behavior  
- Returning vs loyal customer segmentation  
- Subscription impact on revenue  
- Top 3 items within each product category  

📄 **SQL File:**  
`customer_behavior_sql_queries.sql`

---

## 📊 Power BI Dashboard

An interactive Power BI dashboard was created to visualize insights for business stakeholders.

### Dashboard Features
- Revenue by demographics  
- Top-selling and top-rated products  
- Discount usage patterns  
- Customer segmentation (New, Returning, Loyal)  
- Shipping preference trends  

📁 **File:**  
`customer_behavior_dashboard.pbix`

---

## 🧹 Data Analytics Pipeline

### Step 1 — Data Loading
- Loaded dataset using Pandas  
- Checked missing values  
- Standardized column names  
- Converted data types  

### Step 2 — Data Cleaning
- Handled missing and inconsistent values  
- Cleaned categorical variables  
- Formatted review ratings  
- Removed duplicates  

### Step 3 — Exploratory Data Analysis (EDA)
- Purchase amount distribution  
- Product and category frequency analysis  
- Correlation analysis  
- Customer behavior trends  

### Step 4 — SQL Deep Dive
- Answered business-driven analytical questions  
- Segmented customers based on behavior  
- Evaluated revenue and engagement drivers  

### Step 5 — Dashboard Creation
- Imported cleaned data into Power BI  
- Created KPIs (Total Revenue, Avg Spend, Discount Rate)  
- Built executive-friendly dashboards  

### Step 6 — Reporting & Presentation
- Summarized insights in presentation format  
- Provided data-backed business recommendations  

---

## 📈 Key Insights

- Subscribed customers contribute **significantly higher revenue**
- Certain products show **high dependency on discounts**
- Loyal customers demonstrate **higher purchase frequency**
- Express shipping users spend more on average
- A small number of categories dominate overall revenue

---

## ▶️ How to Run This Project

### Prerequisites
Install required Python libraries:
```bash
pip install pandas numpy matplotlib seaborn

