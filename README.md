# 🛍️E-commerce Customer Behavior and Segmentation Analysis
## 🎯 Project Overview
This is an end-to-end data analytics project focused on understanding and segmenting customer behavior for a retail business. The goal was to transform raw transactional data into actionable business intelligence by utilizing a standard data pipeline: Python for ETL (Extract, Transform, Load), SQL for complex analytical processing, and Power BI for interactive visualization and reporting.

The project demonstrates proficiency in data cleaning, advanced database querying, business logic implementation, and dashboard creation.

### 🔑 Key Business Questions Answered
- The analysis provided direct answers to the following strategic business questions:
- Revenue Drivers: What is the revenue contribution split between male and female customers, and across different age groups?
- Product Performance: Which products and categories are top-rated and which have the highest rate of discount application?
- Customer Segmentation: How can the customer base be segmented (New, Returning, Loyal) based on purchase history to optimize retention efforts?
- Subscription Value: Do subscribed customers spend more than non-subscribed customers, validating the subscription program?
- Operational Insights: How does shipping type affect average purchase amount, and which products drive sales within each major category?

### Tool/Technology, Core Skill Demonstrated
- Python
- SQL
- Power BI 
- GitHub

### 🛠️ Advanced SQL Highlights (Snippets)

#### 1. Top Products Ranking using RANK() (Q3)
Used the RANK() window function to accurately rank products by their average review rating, addressing a business need for inventory focus.

<img width="877" height="326" alt="image" src="https://github.com/user-attachments/assets/5a4f2820-e30b-4467-86f5-128446874ebf" />


#### 2. Customer Segmentation using CASE Statements (Q7)
Implemented core business logic using a CASE statement within a CTE to assign each customer to one of three categories based on their previous_purchases.

<img width="881" height="347" alt="image" src="https://github.com/user-attachments/assets/66c005f8-9b7f-40c0-b348-ce358442ff31" />


### 🚀 Future Enhancements

- Predictive Modeling: Use the segmented and aggregated data to build a churn prediction model using Python (Scikit-learn).
- Recency-Frequency-Monetary (RFM) Analysis: Implement a full RFM score calculation in SQL to provide a more granular, numerical segmentation of customer value.
- Time-Series Analysis: Incorporate date data (if available) to analyze sales trends and seasonality for more accurate forecasting.
