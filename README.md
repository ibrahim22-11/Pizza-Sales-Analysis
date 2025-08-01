# Pizza-Sales-Analysis
🍕 Pizza Sales Dashboard in Excel 
📌 Overview This project is a deep dive into pizza sales data using Microsoft Excel, showcasing interactive dashboards, dynamic filtering, and visual storytelling. It transforms raw data into actionable insights for business decision-making—perfect for showcasing Excel mastery in real-world analytics.

📊  Pizza Sales Data Analysis Project

Tools Used: SQL & Excel
Status: ✅ Completed on 31st July 2025

🧾 Overview

This project focuses on analyzing a pizza sales dataset to uncover key business insights using SQL for data extraction and transformation and Excel for visualization. The goal was to generate actionable KPIs and build meaningful dashboards that help understand sales patterns, customer behavior, and product performance.


🧠 Objectives / Key Tasks

Extract, clean, and analyze sales data using SQL.

Build visual dashboards in Excel to represent KPIs.

Derive insights to support business decisions.


📌 KPIs Tracked

Total Revenue

Average Order Value

Total Pizzas Sold

Total Number of Orders

Average Pizzas per Order


📈 Charts & Dashboard Requirements

📅 Daily Trends of Total Orders (Bar Chart)

⏰ Hourly Trends of Total Orders (Line Chart)

🍕 Total Pizzas Sold by Pizza Category

🧀 Percentage of Sales by Pizza Category (Pie Chart)

🍕 Percentage of Sales by Pizza Size

🥇 Top 5 Best-Selling Pizzas (by Total Quantity Sold)

🥄 Worst 5 Selling Pizzas (by Total Quantity Sold)


🛠 SQL Concepts Used

1. Date Formatting:
TO_CHAR(ORDER_DATE, 'DAY') – to extract day from order date


2. Time Extraction:
DATE_PART('HOUR', ORDER_TIME) – to get the hour of order


3. Percentage Calculation Formula:

(SUM(column_name) * 100) / 
(SELECT SUM(column_name) FROM table_name)


📚 What I Learned

Practical use of SQL date/time functions for trend analysis

Techniques for calculating percentages and KPIs

How to convert raw data into a visual story using Excel

Identifying sales patterns and best/worst performing products


🚀 Outcome

This project improved my ability to turn raw transactional data into actionable insights and present it in an understandable format using both SQL and Excel. It demonstrates a foundational project in my data analytics portfolio and showcases my analytical thinking, SQL skills, and dashboard creation abilities.
