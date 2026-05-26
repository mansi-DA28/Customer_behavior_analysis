# Customer_behavior_analysis
Data analytics project showcasing  customer behavior analysis using python, sql and power Bi

Overview

This project analyzes customer shopping behavior using transactional retail data to uncover insights into customer preferences, spending patterns, subscription trends, and product performance.

The project demonstrates a complete data analytics workflow using Python for data cleaning and exploratory data analysis (EDA), PostgreSQL for SQL-based business analysis, Power BI for interactive dashboard creation, and Gamma for presentation design.

The main objective of this project is to transform raw customer transaction data into meaningful business insights that support data-driven decision-making.

Dataset
Dataset Type: Retail / Customer Shopping Data
Total Records: 3,900 transactions
Total Features: 18 columns

Key Features
Customer demographics such as age, gender, and location
Purchase details including category, item purchased, and purchase amount
Shopping behavior including discount usage, subscription status, and shipping type
Customer engagement metrics such as review ratings and previous purchases

Data Quality
Missing values were identified in the Review Rating column
Data was cleaned and standardized before analysis

Tools & Technologies
Python
Pandas
NumPy
PostgreSQL
Power BI
Gamma
GitHub

Project Workflow
1. Data Loading & Exploration (Python)
Imported the dataset using Pandas
Performed initial exploration using:
df.info()
df.describe()
df.isnull().sum()

2. Data Cleaning
Handled missing values in review ratings
Renamed columns using snake_case formatting
Removed redundant columns
Checked data consistency

3. Feature Engineering
Created additional features such as:
age_group
purchase_frequency_days

4. SQL Analysis (PostgreSQL)
Performed business analysis using SQL queries:
Revenue analysis by gender
Subscriber vs non-subscriber comparison
Top-rated products
Customer segmentation
Revenue by age group
Discount usage analysis

5. Built an interactive dashboard with:
KPI cards
Revenue trends
Product category analysis
Customer segmentation visuals
Slicers and filters for interactivity

6. Reporting & Presentation
Created a detailed project report
Designed a presentation using Gamma for project storytelling
Dashboard
Dashboard Features
Total Revenue Overview
Customer Segmentation
Revenue by Gender
Top Product Categories
Subscription Insights
Shipping Type Analysis


Key Results & Insights
Subscribers showed higher average spending compared to non-subscribers
Loyal customers contributed significantly to repeat revenue
Certain products performed better during discount campaigns
Express shipping users had higher average purchase values
Specific age groups contributed more to total revenue

Business Recommendations
Introduce customer loyalty programs
Promote subscription-based benefits
Optimize discount strategies for profitability
Focus marketing on high-value customer segments
Highlight top-performing products in campaigns
