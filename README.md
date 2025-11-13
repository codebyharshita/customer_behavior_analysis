# customer_behavior_analysis
data analytics project showing customer behavior analysis using python ,sql and power Bi.

🛍️ Customer Shopping Behavior Analysis

📖 Project Overview
This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The goal is to identify spending patterns, segment customers, and generate insights that help businesses design better marketing strategies and improve profitability.

⚙️ Tech Stack

Python – Data cleaning, feature engineering, and EDA
PostgreSQL – Business-level SQL analysis and querying
Power BI – Data visualization and dashboard creation
Libraries Used: pandas, numpy, matplotlib, seaborn, psycopg2

🧩 Dataset Information

Rows: 3,900
Columns: 18
Key Features:
Customer demographics – Age, Gender, Location, Subscription Status
Purchase details – Item Purchased, Category, Purchase Amount, Season
Behavioral data – Discount Applied, Review Rating, Frequency, Shipping Type
Missing Values: 37 (in Review Rating), filled using median per product category.

🔍 Data Preparation (Python)

Steps followed:
Loaded dataset using Pandas
Checked for null and duplicate values
Renamed columns to snake_case
Created new columns:
age_group (age bins)
purchase_frequency_days (days between purchases)
Stored cleaned data in PostgreSQL for analysis

📸 Insert Python Cleaning Screenshot Here

🧮 SQL Analysis

Conducted structured business queries to extract insights such as:
Revenue by Gender
Top 5 Products by Rating
Subscribers vs Non-Subscribers
Discoun-Dependent Products
Customer Segmentation (New / Returning / Loyal)
Revenue by Age Group

📸 Insert SQL Output Screenshot Here

📊 Power BI Dashboard

An interactive Power BI dashboard was designed to present insights visually:
Total revenue distribution
Age and gender analysis
Product category trends
Discount vs. Non-discount purchases
Subscriber contribution

📸 Insert Power BI Dashboard Screenshot Here

💡 Key Insights

Female customers contributed slightly higher total revenue.
Subscribers spent more per purchase compared to non-subscribers.
Express shipping customers tend to have higher average order values.
Discounts increase sales volume but reduce overall margin.
Young and middle-aged customers form the most valuable segments.

🚀 Business Recommendations

Introduce loyalty programs for returning buyers.
Promote subscription perks for higher retention.
Optimize discount strategy to improve margins.
Target high-spending age groups through digital marketing.
Highlight top-rated products in ad campaigns.

🧠 Learnings

This project helped me understand end-to-end data analytics workflow — from raw data cleaning to SQL querying and dashboard storytelling. It showed how data insights can directly influence business decisions.
