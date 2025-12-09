🛒 Customer Shopping Behavior Analysis

A complete end-to-end data analytics project involving Python, SQL, and Power BI to analyze customer purchasing patterns and generate actionable business insights.

📌 1. Overview

This project explores a customer shopping dataset to understand purchasing behavior, revenue patterns, product performance, shipping preferences, and subscription trends.
It covers the full analytics workflow:

Loading and cleaning data using Python

Performing Exploratory Data Analysis (EDA)

Running advanced SQL queries for business insights

Building an interactive Power BI dashboard

Preparing a summary report and presentation

📁 2. Dataset

The dataset contains customer transaction data with fields such as:

Customer Details: gender, age_group, subscription_status

Purchase Information: item_purchased, category, purchase_amount, discount_applied

Behavior Indicators: review_rating, previous_purchases

Shipping Details: shipping_type

📌 Dataset is processed inside the project notebook.

🛠 3. Tools & Technologies
Task	Technology
Data loading & cleaning	Python (Pandas, NumPy)
EDA & visualization	Python (Matplotlib, Seaborn)
Data querying	SQL (PostgreSQL/MySQL/SQL Server)
Dashboard	Microsoft Power BI
Presentation	Gamma / PowerPoint
🔍 4. SQL Analysis

The project includes multiple SQL insights such as:
✔ Revenue comparison by gender
✔ Top 5 highest-rated products
✔ Discount behavior analysis
✔ Returning vs loyal customer segmentation
✔ Subscription impact on revenue
✔ Top 3 items per product category

SQL File Used: customer_behavior_sql_queries.sql 

customer_behavior_sql_queries (…

📊 5. Dashboard (Power BI)

The Power BI dashboard showcases:

Revenue by demographics

Top-selling & top-rated products

Discount usage patterns

Customer segmentation

Shipping preference trends

📁 File: customer_behavior_dashboard.pbix

🧹 6. Steps Performed (Pipeline)
Step 1 — Load Data (Python)

Read the dataset into pandas

Check for missing values

Standardize column names

Convert data types

Step 2 — Data Cleaning

Impute or remove null values

Handle inconsistent categorical values

Format review ratings

Remove duplicate entries

Step 3 — Exploratory Data Analysis

Distribution of purchase amounts

Product/category purchase frequency

Correlation between variables

Customer behavior patterns

Step 4 — SQL Deep-Dive

Ran SQL queries to answer key business questions, such as:

Do subscribed customers spend more?

What products receive the highest ratings?

Which age group contributes most to revenue?

(Queries included in file above.)

Step 5 — Dashboard Creation (Power BI)

Import cleaned dataset

Create measures (Total Revenue, Avg Spend, Discount Rate)

Build dashboards for executives & business teams

Step 6 — Report & Presentation

Insights summarized in a PPT using Gamma

Business recommendations included

📈 7. Key Insights

Some of the results generated through SQL & dashboard analysis include:

Subscribed customers have higher revenue contribution

Certain products show extremely high discount dependency

Loyal customers display higher purchase frequency

Express shipping users tend to spend more on average

Top categories dominate revenue by a large margin

(These results can be expanded once your SQL & notebook outputs are added.)

▶️ 8. How to Run This Project
Prerequisites

Install required Python libraries:

pip install pandas numpy matplotlib seaborn

Steps

Clone the project repository

Open the customer_behavior_analysis.ipynb file

Run the notebook to reproduce data cleaning & EDA

Execute SQL queries using PostgreSQL/MySQL/SQL Server

Open the Power BI .pbix file to view dashboards

📄 9. Project Structure
📁 Customer_Shopping_Behavior_Analysis
│── customer_behavior_analysis.ipynb
│── customer_behavior_sql_queries.sql
│── customer_behavior_dashboard.pbix
│── README.md
│── data (optional)
│   └── customer_data.csv

📌 10. Conclusion

This end-to-end analysis helps businesses:

Identify profitable customer segments

Optimize discounts and pricing strategy

Improve product recommendations

Understand behavior trends to increase retention

The project demonstrates your skills in Python, SQL, data modeling, visualization, and business analytics — perfect for data analyst roles.# Customer_Behavior_Analysis
Data Analytics Project Showcasing Customer Behavior Analysis using Python ,SQL and Power Bi
