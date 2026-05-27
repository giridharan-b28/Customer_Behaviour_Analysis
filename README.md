📌 Overview

This project analyzes the shopping behavior of 3,900+ retail customers to uncover insights on revenue trends, customer segmentation, discount impact, and subscription value. The goal is to help businesses make data-driven decisions to improve customer retention and maximize revenue.

Dashboard Preview

<img width="1142" height="647" alt="image" src="https://github.com/user-attachments/assets/afdc819d-a4f0-451d-b966-2e7eabc800ef" />

Project Steps
1️. Data Loading & Cleaning (Python)
Loaded the CSV dataset using Pandas
Checked and handled:
Missing values
Duplicate records
Incorrect data types
Performed data preprocessing and formatting
Created Age Group bins:
Young Adult
Adult
Middle-aged
Senior
Exported the cleaned dataset for SQL analysis
2️. SQL Analysis

Solved key business problems using SQL queries:

Calculated total revenue by gender
Identified the top 3 best-selling items per category using Window Functions
Found customers using discounts who spent above average using Subqueries
Created customer segments:
New
Returning
Loyal
using CTE + CASE statements
Analyzed average spending by shipping type
Studied repeat buyers based on subscription status
3️. Power BI Dashboard

Built an interactive Power BI dashboard with:

KPI Cards
Total Customers
Average Purchase Amount
Average Review Rating
Visualizations
Revenue by Category
Sales by Age Group
Subscription Status Breakdown (Donut Chart)
Customer Purchase Trends
Interactive Features
Dynamic slicers for:
Gender
Category
Shipping Type
Subscription Status
