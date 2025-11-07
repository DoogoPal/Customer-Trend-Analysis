# Customer-Shopping behavior Analysis
> **Project Overview**

This project analyzes customer Shopping behavior Analysis using transactional data from 3,900 purchases across multiple product categories. The goal is to identify spending patterns, customer segments, product preferences, and subscription trends to support strategic business decisions.

> **Dataset Summary**

Rows: 3,900

Columns: 18

Key Features:

Customer demographics: Age, Gender, Location, Subscription Status

Purchase details: Item Purchased, Category, Purchase Amount, Season, Size, Color

Shopping behavior: Discount Applied, Promo Code Used, Review Rating, Shipping Type

Missing Data: 37 null values in the Review Rating column

> **Tools & Technologies**

1. Python – Data cleaning, preparation, and feature engineering

2. Pandas, NumPy – Data analysis and transformation

3. SQL – Business transaction analysis and KPIs and Database integration for structured storage

4. Power BI – Interactive dashboard creation and visualization

> **Data Analysis Steps**

1. Data Cleaning & Preparation (Python)

Checked data types and missing values using df.info() and df.isnull().sum().

Imputed missing Review Rating values using median by product category.

Created new columns:

age_group – binned customer ages.

purchase_frequency_days – average purchase interval.

Dropped redundant column promo_code_used.

Loaded cleaned data into MySQL database.

2. SQL Analysis

a. Answered key business questions:

b. Revenue by Gender

c. High-Spending Discount Users

d. Top 5 Products by Review Rating

e. Shipping Type Comparison (Standard vs. Express)

f. Subscribers vs. Non-Subscribers – average spend & total revenue

g. Discount-Dependent Products

h. Customer Segmentation (New, Returning, Loyal)

i. Revenue by Age Group

> **3. Power BI Dashboard**

a. Built an interactive dashboard visualizing:

b. Sales by Category, Gender, and Age Group

c. Product Ratings and Discounts

d. Subscription vs. Non-Subscription Revenue

e. Shipping Method Analysis

f. Top Products by Purchase Count and Rating

**Business Insights & Recommendations**

1. Boost Subscriptions: Offer exclusive rewards for subscribers.

2. Loyalty Programs: Encourage repeat buyers to join loyalty tiers.

3. Optimize Discounts: Maintain balance between sales boost and profit margin.

4. Highlight Top Products: Use high-rated products in campaigns.

5. Target Marketing: Focus on profitable age groups and express-shipping users.

> **Key Learnings**

a. Combined Python, SQL, and Power BI for end-to-end data analysis.

b. Strengthened understanding of ETL, data modeling, and dashboard storytelling.

c. Improved ability to generate actionable insights for business decisions.

> **About Analyst**

Neha Pal

LinkedIn: www.linkedin.com/in/nehapal3355

Email: neha.pal.3355@gmail.com


> **Tags**

#Python #SQL #PowerBI #DataAnalytics #Dashboard #CustomerInsights #BusinessIntelligence
