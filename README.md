📌 Overview
This project analyzes the shopping behavior of 3,900+ retail customers to uncover insights on revenue trends, customer segmentation, discount impact, and subscription value. The goal is to help businesses make data-driven decisions to improve customer retention and maximize revenue.

Dashboard Preview

<img width="1142" height="647" alt="image" src="https://github.com/user-attachments/assets/afdc819d-a4f0-451d-b966-2e7eabc800ef" />

Project Steps
1️ Data Loading & Cleaning (Python)

Loaded CSV dataset using Pandas
Checked for null values, duplicates, and data types
Created age group bins: Young Adult, Adult, Middle-aged, Senior
Exported clean data for SQL analysis

2 SQL Analysis
Key business questions answered:

 Total revenue by gender
 Top 3 best-selling items per category (Window Functions)
 Customers with discounts spending above average (Subquery)
 Customer segmentation: New → Returning → Loyal (CTE + CASE)
 Average spend by shipping type
 Repeat buyers by subscription status

3 Power BI Dashboard

KPI cards: Total Customers, Avg Purchase Amount, Avg Review Rating
Revenue & Sales by Category and Age Group
Subscription status breakdown (donut chart)
Dynamic slicers: Gender, Category, Shipping Type, Subscription Status





