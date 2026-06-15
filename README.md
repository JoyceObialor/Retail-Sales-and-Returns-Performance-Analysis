# Retail Sales and Returns Performance Analysis
## Table of Contents
1. Project Overview
2. Business Problem
3. Rationale for the Project
4. Objectives
5. Data Description
6. Tech Stack
7. Insights and visualization
8. Actionable Recommendations
9. Conclusion
---
## 1. Project Overview
This project analyzes retail sales performance and product returns to understand how returns impact overall business outcomes. The analysis combines sales, profit, order, delivery, and return data to identify trends, evaluate financial performance, and highlight areas for operational improvement.

The project includes two interactive dashboards:

- Sales Performance Dashboard
- Sales Returns Dashboard
  
These dashboards use key performance indicators (KPIs), visualizations, and trend analysis to support data-driven business decisions.

---
## 2. The Business Problem
Businesses continue to generate strong sales and profit, indicating healthy business performance. However, product returns remain a recurring challenge that can reduce revenue, increase operational costs, and affect customer satisfaction.

To sustain growth and maximize profitability, the business aims to minimize avoidable returns and improve revenue retention. However, there is limited visibility into where returns occur most frequently and the factors driving them.

This creates a gap between current performance and the desired state of optimized revenue retention. Therefore, this project seeks to analyze sales and return patterns across customer segments, products, regions, and shipping methods to uncover insights that support better decision-making and targeted improvement initiatives.

---
## 3. Project Rationale
Product returns are a common challenge in retail businesses and can affect revenue and profitability. Understanding return patterns helps organizations reduce losses, improve customer satisfaction, and make better operational decisions. While overall sales performance is tracked, the impact of returns across products, regions, and customer segments is often less visible. This project provides a data-driven assessment of sales and return trends to support informed decision-making.

---
## 4. Objectives
- Sales performance overview
- Measure the total revenue lost due to product returns
- Identify customer segments with the highest return rates
- Determine sub-categories with the highest returns
- Analyze return patterns across different regions
- Examine trends in return rates over time

---
## 5. Data Description
The dataset for this analysis was sourced from FP20 Analytics (https://fp20analytics.com/datasets/). It contains sales data across regions, product categories, customer segments, and time periods. Key variables include sales, profit, order date, and returns. The data was cleaned by checking for inconsistencies and missing values. The model consists of a retail sales table and a calendar table, linked through the order date to enable time-based analysis. 

---
## 6. Tech Stack and Methodology
**Tech Stack**
- Microsoft Excel
- Power Query 
- Pivot Tables
- Charts, Slicers, and Interactive Dashboard Visualizations
- Flaticon (for product image hosting and visual enhancement)

### Methodology

### 1. Data Preparation & Cleaning
- Loaded the retail sales dataset and calendar into Power Query
- Performed data quality checks to identify and remove duplicates and null values
- Standardized data formats for consistency across fields
### 2. Data Modeling
- Imported a separate Calendar Table to support time-based analysis
- Established a one-to-many relationship between the Calendar Table and Retail Sales dataset using the Order Date field
- Created custom columns to support deeper analytical insights
### 3. Data Transformation
- Transformed raw data using Power Query for structured analysis
- Ensured consistency in date, category, and product-level fields
- Prepared dataset for aggregation and visualization
### 4. Data Analysis Approach
**Descriptive Analytics**: Focuses on summarizing historical data to explain what happened in sales performance and return patterns. It links KPIs such as sales, profit, and return rate to visual insights to identify trends across time, regions, customer segments, and product sub-categories.
Analysis covers:
- Sales Performance Analysis
- Return Trend Analysis
- Customer Segment Analysis
- Product Sub-Category Analysis
- Regional Performance Analysis
- Shipping Mode Analysis
 ### 5. Visualization & Dashboard Design
- Built interactive dashboards using Excel
- Used Pivot Tables for data aggregation and summarization
- Designed KPI cards to display key metrics such as sales, profit, sales lost and return rate
- Created charts and slicers for dynamic filtering and insight exploration
- Enhanced visual storytelling using product images hosted on Flaticon.com 
### 6. Measures Created
- Return Rate
- Profit Margin
- Returned Sales
- Sales Lost Percentage
- Total Returned Orders
-Average Delivery Days

---
## 7. Visualization and Insights

### Sale Performance Analysis: 
- The business recorded a total of 37,873 units sold, generated $2.3M in sales, $286.4K in profit, and maintained a 12% profit margin.
- Customer Segment: The Consumer segment was the largest revenue contributor, generating $1.2M in sales, followed by Corporate ($706.1K) and Home Office ($429.7K).
- Monthly Sales Trend: Monthly sales showed an overall upward trend in the second half of the year, increasing from $161.1K in February to a peak of $271.7K in November, before easing slightly to $248.8K in December.
- Quaterly sales Trends: Sales peaked in Q4 ($704.8K), followed by Q3 ($620.2K), while Q2 ($458.3K) recorded the lowest sales.
- Region: The West region contributed the highest sales ($725.5K), followed by the East ($678.8K), Central ($501.2K), and South ($391.7K) regions.
- Category: Technology was the top-performing category, accounting for 51% of total sales, followed by Office Supplies (43%) and Furniture (6%).
- Least Sub-category: Tables (-79%), Bookcases (-16%), and Supplies (-5%) were the least profitable Sub-categories, highlighting areas requiring attention.
<img width="2130" height="1305" alt="image" src="https://github.com/user-attachments/assets/7a09de0f-ce67-4477-b846-61ac5f090b08" />

---
### Sales Return Analysis 
- 800 orders were returned, representing 8% of total orders and $180.5K account for sales lost.
- February (10.9%) and August (10.5%) recorded the highest monthly return rates, while January had the lowest (6.0%).
- Yearly Return Trend: Return rates increased throughout the year, increasing from 7.6% in 2014 to 8.7% in 2017, the highest recorded rate indicating that returns became more frequent as the business grew.
- Customer Segement: The Corporate segment recorded the highest return rate (9%), followed by Consumer (8%) and Home Office (7%).
- Sub-category: Machines had the highest return rate (11.3%), followed by Tables (9.4%), Paper (9.0%), and Binders (9.0%).
- Regional Return: The West region generated the highest profit ($100K+) but also recorded the highest return rate (16%), indicating a significant opportunity to reduce revenue leakage.
- Shiping Mode: Return rates varied by shipping mode, with Same Day (11.8%) recording the highest return rate, followed by First Class (9.9%), Standard Class (7.5%), and Second Class (6.9%).
<img width="2145" height="1292" alt="image" src="https://github.com/user-attachments/assets/12e9ff7c-8c91-4408-96e8-26159a0f82b1" />

---
## 8. Actionable Recommendations
- Review loss-making categories such as tables, bookcases, and Supplies to improve revenue generation
- Increase marketing efforts toward the Consumer segment, which generates the highest sales.
- Conduct customer feedback surveys and review order requirements to improve product fit, order accuracy, and customer satisfaction.
- Strengthen product quality checks, enhance product descriptions, and provide clearer usage guidance to reduce avoidable returns.
- Review packaging processes to ensure orders are delivered accurately and in good condition 
- Leverage customer feedback to identify recurring issues affecting the region and implement targeted interventions to reduce revenue losses while maintaining sales performance. 

---
## 9. Conclusion
This project analyzed retail sales performance and product return patterns using key performance indicators such as sales, profit, and return rate. The analysis showed overall sales performance, but highlighted returns behaviours as a key driver of revenue loss across specific segments, regions, and product Sub-Categories.

The insights demonstrate my ability to perform end-to-end data analysis and translate findings into actionable business recommendations aimed at improving profitability and reducing return rates.

---
## Author

_Joyce Obialor_
- 👉 [GitHub Profile](https://github.com/JoyceObialor)
- Entry-Level Data Analyst | Data science student
