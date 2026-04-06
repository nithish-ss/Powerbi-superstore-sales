📊 Superstore Sales Performance Dashboard (2019–2020)

Interactive Power BI dashboard analyzing sales, profit, and regional performance to uncover business insights and trends.



🚀 Project Overview

This project presents an interactive sales dashboard built using Power BI to analyze the performance of a retail superstore across regions, categories, and time.

The dashboard provides insights into sales, profit, customer behavior, and delivery performance, helping businesses make data-driven decisions.


🎯 Objectives

- Analyze overall sales and profit performance
- Understand regional sales distribution
- Identify top-performing states and categories
- Track monthly sales and profit trends
- Evaluate operational metrics like delivery time



📌 Key KPIs

- 💰 Total Sales: 1.6M
- 📈 Total Profit: 175K
- 📦 Total Orders: 3003
- 🛒 Items per Order: 7.43
- 🚚 Avg Delivery Time: 4 Days
- 📊 Profit Margin: 11%



📊 Dashboard Features

- 🗺️ Sales and Profit by State (Map Visualization)
- 📈 Monthly Sales & Profit Trends (Year-over-Year)
- 🏆 Top 5 States by Sales
- 📦 Sales by Category
- 🚚 Sales by Ship Mode
- 🎛️ Interactive Region Filter (Central, East, South, West)


🔍 Key Insights

- California generates the highest sales among all states
- Office Supplies category contributes the most revenue
- Customers purchase an average of 7+ items per order
- Sales show a noticeable increase in the last quarter (Q4)
- Standard Class shipping is the most preferred mode



🛠️ Tools & Technologies

- Power BI (Power query for data cleaning and transformation)
- DAX (Data Analysis Expressions)
- Data Modeling
- Data Visualization
- Implemented slicers and tooltips

## 🧮 DAX Measures

`Total Sales = SUM('Superstore_Sales_Data'[Sales])`

`Total Profit = SUM('Superstore_Sales_Data'[Profit])`

`Total Orders = DISTINCTCOUNT('Superstore_Sales_Data'[Order ID])`

`Profit Margin (%) = DIVIDE([Total Profit], [Total Sales])`

`Items per Order = DIVIDE([Total Quantity], [Total Orders])`

`Avg Delivery Time = AVERAGE(
    DATEDIFF(
        'Superstore_Sales_Data'[Order Date],
        'Superstore_Sales_Data'[Ship Date],
        DAY))`


📁 Dataset
- Superstore Sales Dataset (commonly used for analytics practice)



📸 Dashboard Preview
![superstoredashboard](https://github.com/user-attachments/assets/a00ab1aa-21c0-4057-8e71-b331265db501)



💡 Learnings

- Built interactive dashboards using Power BI
- Applied DAX measures for KPI calculations
- Improved data storytelling and visualization skills
- Understood business insights from raw data

