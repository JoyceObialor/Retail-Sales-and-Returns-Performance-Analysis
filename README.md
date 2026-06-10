# Retail Sales and Returns Performance Analysis
## Table of Contents
1. Project Overview
2. Business Problem
3. Rationale for the Project
4. Objectives
5. Data Description
6. Tech Stack
7. Project Scope
8. Methodology
9. Project Visualization
10. Result  
11. Actionable Recommendations
12. Future Work
13. Conclusion
---
## 1. Overview
This project analyzes retail sales performance and sales returns to understand how returned orders affect and business outcomes.The analysis combines sales, profit, order, delivery, and return data to identify trends,evaluate financial impact, and highlight areas for operational improvement. It consist of two interative sales performance and sales returns dashboard, KPIs, and advanced visualization techniques, this study identifies key business insights, trends, and patterns to drive operational and strategic decisions.

---
## 2. The Business Problem
Businesses continues to generate strong sales and profit, indicating healthy business performance. However, product returns remain a recurring challenge that can reduce revenue, increase operational costs, and affect customer satisfaction.

To sustain growth and maximize profitability, the business aims to minimize avoidable returns and improve revenue retention. However, there is limited visibility into where returns occur most frequently and the factors driving them.

This creates a gap between current performance and the desired state of optimized revenue retention. Therefore, this project seeks to analyze sales and return patterns across customer segments, products, regions, and shipping methods to uncover insights that support better decision-making and targeted improvement initiatives.

---
## 3. Project Rationale
Product returns are a common challenge in retail businesses and can affect revenue and profitability. Understanding return patterns helps organizations reduce losses, improve customer satisfaction, and make better operational decisions. While overall sales performance is tracked, the impact of returns across products, regions, and customer segments is often less visible. This project provides a data-driven assessment of sales and return trends to support informed decision-making.

---
## 4. Objective
- Sales performance overview
- Measure the total revenue lost due to product returns
- Identify customer segments with the highest return rates
- Determine product categories and Sub-categories with the highest returns
- Analyze return patterns across different regions
- Examine trends in return rates over time


---
## 5. Data Descrption
The project used two primary table retail sales table and calender table and was modeleded ensuring realtionship between the orderdate and calendar table. the data was sourced from kaggle dataset 

---
## 6. Tech Stack
 Microsoft Excel:
- Pivot Tables for data aggregation and analysis
- Interactive Dashboards and KPI Cards
- Charts, Visualizations, and Slicers for dynamic reporting

 ### Power Query 
Loaded and transformed the retail dataset
Performed data quality checks for duplicate and null values
Imported a separate Calendar Table for time-based analysis
Established a one-to-many relationship between the Calendar Table and Retail Dataset
Created custom columns such as:
Delivery Days
Delay Flag

--
### Data Modeling & Measures
Return Rate, Profit Margin, Returned Sales,Sales Lost Percentage, Total Returned Orders, Average Delivery Days
- flaticon: Hosted product images for visual representation in dashboard
--
## Dashboard design and Insights

### Sale Performance: 
- The business sold Quantity value Sold 37873, generated $2.3M in sales, $286.4K in profit, and maintained a 12% profit margin.
- Customer Segment: The Consumer segment was the largest revenue contributor, generating $1.2M in sales, followed by Corporate ($0.7M) and Home Office ($0.4M).
- Monthly Sales Trend: The  month of Febrauary genrwted more sales, generating $271K in sales folowed by september
- Quaterly sales Trends: Sales peaked in Q4 ($704.8K), followed by Q3 ($620.2K), while Q2 ($458.3K) recorded the lowest sales.
- Region: The West region contributed the highest sales ($725.5K), followed by the East ($678.8K), Central ($501.2K), and South ($391.7K) regions.
- Category: Technology was the top-performing category, accounting for 51% of total sales, followed by Office Supplies (43%) and Furniture (6%).
- Least Sub-category: Tables (-79%), Bookcases (-16%), and Supplies (-5%) were the least profitable Sub-categories, highlighting areas requiring attention.



