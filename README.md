# Retail_Customer_Behavior_Analysis
Project Overview

This project analyzes customer shopping behavior using transactional retail data to uncover actionable business insights. The analysis focuses on customer demographics, purchasing patterns, discounts, subscriptions, shipping preferences, and product ratings to support data-driven decision-making in a retail environment.
The project follows an end-to-end analytics workflow, including data cleaning, exploratory data analysis (EDA), SQL-based business analysis, and interactive dashboard creation using Power BI.


Dataset Overview

Total Records: 3,900 purchase transactions
Total Features: 18 columns
Data Type: Customer demographics, purchase behavior, pricing, discounts, ratings
Missing Values:
37 missing values found only in the Review Rating column


Data Preparation & Processing

The dataset was processed using Python (Pandas) with the following steps:
Data Loading
Imported CSV data into Python using Pandas.
Initial Exploration
Checked schema, data types, summary statistics, and distributions.
Missing Value Handling
Imputed missing Review Rating values using the median to preserve distribution integrity.
Feature Engineering
Created age groups for demographic analysis.
Derived purchase frequency metrics to support customer segmentation.
Database Integration
Loaded cleaned data into PostgreSQL for structured SQL analysis.


Business Analysis (SQL)

SQL queries were written to answer real-world retail business questions, including:
Revenue comparison by gender
High-value customers using discounts
Top-rated products based on customer feedback
Impact of shipping type on average purchase value
Subscription vs non-subscription customer behavior
Customer segmentation based on loyalty and spending patterns
All queries are documented and saved as .sql files for version control.

Key Insights

🔹 Revenue by Gender
Female customers generate slightly higher total revenue than male customers.
Opportunity for gender-specific marketing strategies.

🔹 High-Value Discount Users
Identified “Smart Shoppers” who spend above average while using discounts.
Ideal targets for premium offers and loyalty incentives.

🔹 Top-Rated Products
Blouse and Dress received the highest customer ratings.
These products should be prioritized in marketing campaigns.

🔹 Shipping Preferences
Express shipping customers spend ~12% more per transaction than standard shipping users.

🔹 Subscription Impact
Subscribers spend 68% more than non-subscribers.
Subscription customers contribute 45% of total revenue.
78% repeat purchase rate, indicating strong loyalty.

🔹 Customer Segmentation

New Customers: 50%
Returning Customers: 35%
Loyal Customers: 15% (highest value group)
Primary business focus: Convert New → Returning → Loyal customers.


Power BI Dashboard

An interactive Power BI dashboard was built to visualize:
Revenue by category and gender
Customer segmentation
Shipping preferences and spend
Subscription impact
Product performance
The dashboard enables business stakeholders to explore insights dynamically and supports strategic decision-making.


Tools & Technologies

Python: Pandas, NumPy
SQL: PostgreSQL, MySQL
Visualization: Power BI


Business Recommendations

Promote subscription programs to increase customer lifetime value.
Implement loyalty rewards for returning customers.
Target express shipping users with premium offers.
Highlight top-rated products in marketing campaigns.
Personalize promotions for high-value discount users.


Conclusion

This project demonstrates a complete data analytics lifecycle, combining Python-based EDA, SQL-driven business analysis, and Power BI visualization. The insights generated can directly support retail strategy, marketing optimization, and customer retention initiatives.
