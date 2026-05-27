📌 Overview

This project analyzes the shopping behavior of 3,900+ retail customers to uncover insights on revenue trends, customer segmentation, discount impact, and subscription value. The goal is to help businesses make data-driven decisions to improve customer retention and maximize revenue.

Dashboard Preview

<img width="1142" height="647" alt="image" src="https://github.com/user-attachments/assets/afdc819d-a4f0-451d-b966-2e7eabc800ef" />

📌 Project Steps:
1. Data Loading & Cleaning (Python)
   
The dataset was loaded from a CSV file using the Pandas library. It was then inspected for null values, duplicate records, and incorrect data types to ensure data quality. Age group bins were created to categorize customers into four segments — Young Adult, Adult, Middle-aged, and Senior. The cleaned dataset was then exported for SQL analysis.

2. SQL Analysis
   
Several business questions were answered using SQL queries. Total revenue was calculated by gender to understand spending differences. The top 3 best-selling items per category were identified using Window Functions. Customers who received a discount but still spent above the average purchase amount were filtered using a Subquery. Customers were segmented into New, Returning, and Loyal groups based on their purchase history using a CTE with a CASE statement. Average spend was also compared across different shipping types, and repeat buyers were analyzed based on their subscription status.

3. Power BI Dashboard
   
An interactive dashboard was built in Power BI to visualize the key findings. KPI cards display the total number of customers, average purchase amount, and average review rating at a glance. Bar charts show revenue and sales volume broken down by both category and age group. A donut chart illustrates the split between subscribed and non-subscribed customers. Dynamic slicers for Gender, Category, Shipping Type, and Subscription Status allow users to filter and explore the data interactively.
