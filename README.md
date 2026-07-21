# Retail_Customers_Insights_Dashboard
Retail Customer Insights Dashboard

An end-to-end Data Analytics project using Python, PostgreSQL, and Power BI to analyze customer purchasing behavior and build an interactive business intelligence dashboard.

Project Overview

This project analyzes 3,900 retail customer transactions to understand customer purchasing behavior, spending patterns, product preferences, and subscription trends. The data was cleaned and transformed using Python, analyzed with PostgreSQL, and visualized through an interactive Power BI dashboard to support data-driven business decisions.

Business Problem

Retail businesses collect large amounts of customer transaction data but often struggle to convert it into actionable insights.

This project answers important business questions such as:

Which customer groups generate the highest revenue? Which products receive the best customer ratings? How do discounts affect purchasing behavior? Are subscribers more valuable than non-subscribers? Which customer segments should be targeted for marketing campaigns? Dataset Information Attribute Details Total Records 3,900 Total Columns 18 Domain Retail / E-Commerce Data Includes Customer demographics, purchases, subscriptions, reviews, discounts, shipping, seasons, product categories

The dataset contains:

Customer demographics Purchase history Product information Subscription status Discount usage Shipping preferences Customer review ratings Tech Stack Python Pandas NumPy PostgreSQL SQL Queries Window Functions Aggregate Functions CTEs Power BI Interactive Dashboard KPI Cards Charts Filters & Slicers Project Workflow Step 1 Data Collection Imported retail customer transaction dataset into Python. Loaded data using Pandas for analysis. Step 2 Data Cleaning (Python)

Performed data preprocessing to improve data quality.

Tasks completed:

Loaded dataset Checked data types Explored summary statistics Identified missing values Filled missing values in Review Rating using the median rating of each product category Standardized column names using snake_case Removed redundant columns Verified data consistency Created new features for analysis Step 3 Feature Engineering

Created additional analytical columns including:

Age Group Teen Young Adult Adult Senior Purchase Frequency (Days)

These features helped improve customer segmentation and dashboard analysis.

Step 4 Database Integration Connected Python with PostgreSQL Loaded the cleaned dataset into PostgreSQL Performed SQL-based business analysis Step 5 SQL Business Analysis

Solved multiple business problems using SQL.

Key analyses include: Revenue by Gender High Spending Customers using Discounts Top Rated Products Shipping Type Comparison Subscriber vs Non-Subscriber Analysis Discount Dependent Products Customer Segmentation Top Products by Category Repeat Buyers vs Subscription Status Revenue by Age Group Step 6 Power BI Dashboard

Built an interactive dashboard containing:

Revenue KPIs Customer demographics Product performance Subscription analysis Discount insights Customer segmentation Interactive filters and slicers

The dashboard allows users to explore customer behavior dynamically and supports business decision-making.

Dashboard Features Revenue Overview Customer Demographics Product Category Performance Top Rated Products Subscription Insights Discount Analysis Customer Segmentation Interactive Filters Key Business Insights Identified the highest revenue-generating customer groups. Compared purchasing behavior between subscribers and non-subsscribers. Found top-performing products based on customer ratings. Evaluated the impact of discounts on sales. Segmented customers into New, Returning, and Loyal groups. Analyzed revenue contribution by age group. Business Recommendations

Based on the analysis:

Improve customer subscription programs. Introduce loyalty rewards for repeat customers. Optimize discount strategies. Promote top-rated products. Target marketing campaigns toward high-value customer segments.

Skills Demonstrated Data Cleaning Exploratory Data Analysis (EDA) Feature Engineering SQL Query Writing Database Management Business Intelligence Dashboard Development Data Visualization Business Analytics Problem Solving Learning Outcomes

Through this project, I gained hands-on experience in:

Cleaning and transforming real-world datasets Writing SQL queries to solve business problems Integrating Python with PostgreSQL Building interactive Power BI dashboards Converting raw data into actionable business insights Future Improvements Build predictive models for customer purchase behavior. Add customer lifetime value (CLV) analysis. Develop sales forecasting dashboards. Automate the ETL pipeline using scheduled workflows. Deploy the dashboard using Power BI Service. Why this project?

This project demonstrates an end-to-end data analytics workflow—from data cleaning and database management to SQL analysis and interactive dashboard creation. It highlights practical skills commonly required for Data Analyst, Business Analyst, and BI Analyst roles, making it a strong portfolio project for recruiters.
