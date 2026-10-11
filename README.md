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
- Only 27% of customers are subscribers (1,053 of 3,900); subscribers and non-subscribers spend almost the same on average ($59.49 vs $59.87)
- Repeat buyers (more than 5 previous purchases) subscribe slightly more often than others (27.6% vs 22.4%)
- Male customers generated ~68% of revenue ($157,890 vs $75,191), mainly because they are 68% of customers; average spend per customer is similar ($59.54 vs $60.25)
- Clothing is the top category by revenue ($104K), followed by Accessories ($74K)
- Young Adults (18-31) contribute the most revenue ($62K, ~27%), though differences between age groups are modest
- Hats, sneakers and coats have the highest share of discounted purchases (~49-50%)
- The Loyal segment (more than 10 previous purchases) makes up 80% of customers and ~80% of revenue
- Average purchase differs little across shipping types ($58-61); 2-Day ($60.73) and Express ($60.48) are slightly higher than Standard ($58.46)

Business Recommendations
- Run subscription-conversion campaigns for non-subscribers, who make up 73% of customers and spend as much as subscribers
- Introduce loyalty programs to move Returning and New customers toward the Loyal segment, which drives ~80% of revenue
- Review discount strategy for hats, sneakers and coats, where about half of purchases are discounted
- Focus marketing on Young Adults and on Clothing, the top segment and top category by revenue
- Highlight top-rated products such as gloves, sandals and boots in campaigns
