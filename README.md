# PizzaPowerbi
This repository contains a comprehensive **Pizza Dashboard project**, focusing on analyzing pizza sales data using **SQL queries** and **visualizations**. 
The dashboard provides insights into **sales trends**, **revenue analysis**, **top-selling pizzas**, and more. 
It includes interactive Power BI visualizations and SQL scripts for data manipulation and analysis.

### Key Features:
- **Interactive Visualizations:** Explore trends and metrics through interactive charts and graphs.
- **SQL Queries:** Includes SQL scripts (`pizza_sales_queries.sql`) for data extraction and analysis.
- **Project Files:** `PizzaSalesDashboard.pbix` for Power BI visualization and other relevant project files.


## SQL Queries

### A. KPI’s

1. **Total Revenue:**
```sql
SELECT SUM(total_price) AS Total_Revenue FROM pizza_sales;


