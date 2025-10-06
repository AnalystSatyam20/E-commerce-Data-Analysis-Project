🛒 E-commerce Data Analysis Project
📊 Overview

This project focuses on analyzing a large-scale e-commerce dataset (1 million+ records) to extract valuable business insights using Python (data cleaning & preprocessing) and Power BI (dashboard & visualization).
The aim is to understand customer behavior, sales trends, delivery performance, and business KPIs through a mix of data analytics and BI visualization.

🧠 Objectives

Clean and preprocess raw e-commerce order data using Python.

Analyze customer purchasing patterns and sales performance.

Build Power BI dashboards to visualize business metrics.

Identify trends in revenue, delivery time, and customer segments.

Provide actionable insights for improving sales and logistics efficiency.

🛠️ Tech Stack
Purpose	Tools & Libraries
Data Cleaning	Python (Pandas, NumPy)
Data Visualization	Power BI
Data Storage	CSV, Excel
Other Tools	Jupyter Notebook, Power Query


🧹 Data Cleaning Steps (Python)

Performed using Pandas and NumPy:

Removed missing or duplicate values.

Handled outliers in order_amount, delivery_time, etc.

Converted data types (date, categorical encoding).

Standardized column names.

Derived new metrics such as:

Total Spend per Customer

Average Delivery Time

Order Delay Status

📈 Power BI Dashboards
Page 1: Sales Overview

KPIs: Total Revenue, Avg Order Value, No. of Customers

Charts: Sales Trend, Top 10 Products, Region-wise Sales

Page 2: Customer Insights

KPIs: Repeat Purchase %, Customer Lifetime Value

Visuals: Top 10 customers with Highest purchase,Order count by payment method

Page 3: Delivery & Logistics

KPIs: Avg Delivery Time, % On-time vs Delayed Orders

Visuals: Delivery Time Distribution, Trend over Time
📑 Key Insights

Majority of high-value customers are concentrated in Tier 1 cities.

Average delivery time impacts repeat purchases significantly.

15% of total orders contribute to nearly 70% of total revenue (Pareto principle).

On-time delivery rate improvement could increase retention by ~10%.

🚀 How to Run the Project
1. Python Data Cleaning
# Install dependencies
pip install pandas numpy jupyter

# Open Jupyter Notebook
jupyter notebook


Run your data cleaning script or follow the steps in
📄 E-commerce sales data cleaning with python.pdf

2. Power BI Dashboard

Open Power BI Desktop

Load cleaned_ecommerce_orders.csv

Open and explore visuals as shown in E_commerce_sales_dashboards.pdf

📊 KPIs Tracked
Category	KPI	Description
Sales	Total Revenue	Overall sales performance
Customer	Avg Spend per Customer	Purchase power & loyalty
Delivery	Avg Delivery Time	Logistics efficiency
Operations	On-time %	Service reliability


👨‍💻 Author
👋 Satyam Rawat

📂 GitHub Profile
