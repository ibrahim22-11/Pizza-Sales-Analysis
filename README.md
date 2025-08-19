# 🍕 Pizza Sales Analysis Dashboard

An interactive dashboard project that analyzes real pizza sales data using **SQL for data transformation** and **Excel for visualization**. This dashboard uncovers patterns in customer behavior, product performance, and order trends to support better business decisions.

![Pizza Dashboard](https://github.com/ibrahim22-11/Pizza-Sales-Analysis/blob/main/Dashboard..jpg)

---

## 📅 Project Info

- **🧰 Tools Used:** SQL, Microsoft Excel  
- **📁 Completed On:** 1st August 2025  
- **📌 Status:** ✅ Completed  
- **🔗 Dashboard Preview:** [View Dashboard](https://github.com/ibrahim22-11/Pizza-Sales-Analysis/blob/main/Dashboard..jpg)

---

## 🧾 Project Overview

This project focuses on analyzing a pizza sales dataset using **SQL** for data extraction and cleaning, followed by **Excel** for dynamic dashboards and visual storytelling. The objective was to generate KPIs and interactive visuals that reveal sales insights and support decision-making.

---

## 🎯 Objectives

- Extract, clean, and analyze pizza sales data using SQL  
- Create an interactive dashboard in Excel  
- Track key performance indicators (KPIs)  
- Identify top/worst performing products and peak sales periods  

---

## 📊 KPIs Tracked

- **Total Revenue**  
- **Average Order Value**  
- **Total Pizzas Sold**  
- **Total Number of Orders**  
- **Average Pizzas per Order**

---

## 📈 Dashboard Visuals

- 📅 **Daily Trends of Total Orders** (Bar Chart)  
- ⏰ **Hourly Trends of Total Orders** (Line Chart)  
- 🍕 **Total Pizzas Sold by Pizza Category**  
- 🧀 **Percentage of Sales by Pizza Category** (Pie Chart)  
- 🍕 **Percentage of Sales by Pizza Size**  
- 🥇 **Top 5 Best-Selling Pizzas** (By Quantity Sold)  
- 🥄 **Worst 5 Selling Pizzas** (By Quantity Sold)

---

## 📁 Project Files

- 📊 **Dashboard Image:** [Click to View](https://github.com/ibrahim22-11/Pizza-Sales-Analysis/blob/main/Dashboard..jpg)  
- 📄 **Raw Data (Excel File):** [Click to Download](https://github.com/ibrahim22-11/Pizza-Sales-Analysis/blob/main/RawData.xlsx)

---

## 🛠 SQL Techniques Use

1. Data formatting 
TO_CHAR(order_date, 'DAY')


2. Time Extraction
DATE_PART('HOUR', order_time)


Used to extract the hour of the order for hourly trend analysis.

3. Percentage Calculation Formula
(SUM(order_id) * 100) / (SELECT SUM(order_id) FROM table_name)




Used to calculate category or size percentage sales.

📚 What I Learned

- Practical usage of SQL date/time functions for trend analysis  
- Techniques for KPI and percentage calculations in SQL  
- Designing visually appealing and informative dashboards in Excel  
- Recognizing sales patterns, top products, and improvement areas  

🚀 Project Outcome

This project enhanced my ability to turn raw transactional data into interactive insights using SQL + Excel.  
It represents a strong foundation in my data analytics portfolio, combining technical analysis, business insight, and storytelling.

💬 Feedback & Contributions

If you'd like to suggest improvements, collaborate, or raise an issue:

💡 Open an issue

🔁 Submit a pull request with enhancements or ideas

© 2025 Ibrahim — All rights reserved.



