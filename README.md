## COFFEE SHOP SALES

#   over view 

This project presents an interactive Coffee Shop Sales Dashboard built to analyze key business metrics for the month of JAN 2023 TO June 2023 Sales
The dashboard provides a comprehensive view of store performance, customer behavior, and product category insights, enabling data-driven decision-making.

This project aims to solve these issues by developing an interactive Coffee Shop Sales Dashboard that consolidates all key KPIs
and visual insights into a single, easy-to-use analytics tool.

# Questions 

 KPI REQUIREMENTS
 1. Total Sales Analysis:
   - Calculate the total sales for each respective month.
   -  Determine the month-on-month increase or decrease in sales.
   - Calculate the difference in sales between the selected month and the previous month.

3. Total Orders Analysis:
  - Calculate the total number of orders for each respective month.
  - Determine the month-on-month increase or decrease in the number of orders.
  - Calculate the difference in the number of orders between the selected month and the previous month.

3. Total Quantity Sold Analysis:
  - Calculate the total quantity sold for each respective month.
  - Determine the month-on-month increase or decrease in the total quantity sold.
  - Calculate the difference in the total quantity sold between the selected month and the previous month

CHARTS REQUIREMENTS
1. Calendar Heat Map:
   - Implement a calendar heat map that dynamically adjusts based on the selected month from a slicer.
   -Each day on the calendar will be color-coded to represent sales volume, with darker shades indicating higher sales.
   - Implement tooltips to display detailed metrics (Sales, Orders, Quantity) when hovering over a specific day.

2. Sales Analysis by Weekdays and Weekends:
  - Segment sales data into weekdays and weekends to analyze performance variations.
  - Providensights into whether sales patterns differ significantly between weekdays and weekends.

3. Sales Analysis by Store Location:
  - Visualize sales data by different store locations.
  - Include month-over-month (MoM) difference metrics based on the selected month in the slicer.
  -Highlight MoM sales increase or decrease for each store location to identify trends.

4. Daily Sales Analysis with Average Line:
 - Display daily sales for the selected month with a line chart.
 - Incorporate an average line on the chart to represent the average daily sales.
 - Highlight bars exceeding or falling below the average sales to identify exceptional sales days.

5. Sales Analysis by Product Category:
 - Analyze sales performance across different product categories.
 - Provide insights into which product categories contribute the most to overall sales.

6. Top 10 Products by Sales:
- Identify and display the top 10 products based on sales volume.
- Allow users to quickly visualize the best-performing products in terms of sales.

7. Sales Analysis by Days and Hours:
 - Utilize a heat map to visualize sales patterns by days and hours.
 - Implement tooltips to display detailed metrics (Sales, Orders, Quantity) when hovering over a specific day-hour.


## TOOLS AND METHODOLOGY

  TOOL USED 
   - SQL - Cleaning data types and extract values in database and also check cross validation
    -Power Query – Data cleaning and transformation
    -power bi - to prepare dashboards using KPI ,Charts 
    
     
  # Methodology
   1.Data Cleaning 
    - Removed duplicates and handled missing entries.
     -Verified date formats

  # Dax Measure 
   - Month on Month Growth and Diff ( sales , orders , quantity) using dax formulas to  be calculate
   - Current  ,Previous (sales, orders,quantity) using dax measure
   - Totals  (sales,orders,quantity) 
   - avg sales , day and hours , some labels are also using dax formulas








      
  # Dashboard Insights
  
   1.Sales Trend Over Time:
   -Daily sales performance visualized across the entire month to identify peaks and slow periods.
   2.Category Performance:
    -Coffee, tea, bakery, and beverage categories show detailed revenue contribution and growth percentages.
  3. Store Location Analysis:
    -Sales performance by stores such as Astoria, Hell’s Kitchen, and Lower Manhattan with MoM comparison.
   4.Weekend vs Weekday Sales:
     --Weekend sales contribute 25.9%, while weekdays account for 74.4% of total sales.
   5. Hourly Sales Heatmap:
     --Identifies the busiest hours of the day and the most active days for each time slot.
  
  # Purpose

  1. This dashboard helps business stakeholders:
   - Track key performance indicators (KPIs)
   - Identify growth opportunities
   - Understand customer buying behavior
   - Optimize store operations and inventory
   -Compare performance across locations and product categories



