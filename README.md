# Project_3_SQL_Analysis
# E-Commerce Order Analysis Using SQL and Python

## OVERVIEW
This project analyzes an e-commerce dataset to uncover customer purchasing behavior, order trends, coupon usage patterns, and cancellation rates. The analysis was conducted using Python, Pandas, SQLite, and SQL queries to transform raw transactional data into actionable business insights.

The objective was to answer key business questions regarding order volume, revenue generation, payment preferences, product performance, and the impact of coupon codes on order cancellations.


## DATASET
The dataset contains transactional information from an e-commerce platform with the following key attributes:
* OrderID
* Date
* CustomerID
* Product
* Quantity
* UnitPrice
* TotalPrice
* PaymentMethod
* OrderStatus
* CouponCode
* TrackingNumber
* ShippingAddress
* ReferralSource
* ItemsInCart

The data was cleaned and loaded into Python for analysis before being stored in a SQLite database for SQL querying.


## DATA CLEANING
To ensure the accuracy and reliability of the analysis, the dataset was cleaned and prepared before performing SQL queries. The data cleaning process included:

* Checking for and handling missing values in relevant columns.
* Removing duplicate records to prevent double-counting of transactions.
* Verifying and correcting data types, particularly for date and numeric fields.
* Standardizing column names for consistency and ease of querying.
* Identifying and addressing inconsistencies in categorical variables such as payment methods and order statuses.
* Validating the dataset to ensure accurate calculations and analysis results.

These steps helped improve data quality and ensured that the insights generated from the analysis were reliable and meaningful.


## KEY BUSINESS OBJECTIVES
1. Revenue Analysis
2. Customer Behavior Analysis
3. Referral Sources Analysis

## KEY INSIGHTS
* The business generated a total revenue of **1,264,761.96** with an average order value of **1,053.97**, indicating strong overall sales performance.
* **Credit Card** payments produced the highest average order value (**1,127.55**) and total revenue (**263,847.63**), suggesting higher customer spending through this payment method.
* **Online payments** were the most preferred payment option, accounting for **258 orders**.
* **Chairs** were the most frequently ordered product with **45 orders**, making them the top-selling item in the dataset.
* **Email** was the most effective referral source, generating the highest number of delivered orders (**60**) and the highest delivery rate (**24.00%**).
* Revenue peaked in **June 2024**, generating **68,068.54**, indicating a period of strong sales performance.
* **Shipped** orders were the most common order status (**258 orders**), while a notable number of orders remained pending or were cancelled.
* Orders placed **with coupons** recorded a higher cancellation rate (**21.55%**) than those without coupons (**18.77%**).
* **Credit Card** transactions had the highest cancellation rate (**23.08%**), while **Debit Card** transactions recorded the lowest (**18.97%**).
* The findings suggest opportunities to improve order fulfillment, reduce cancellations, optimize promotional campaigns, and leverage high-performing marketing channels to drive future growth.


## TOOLS USED
* Visual Studio Code (VS Code)
* Python
* Pandas
* SQLite
* SQL


## RECOMMENDATIONS
1. Strengthen email marketing efforts**, as Email generated the highest number of delivered orders and achieved the best delivery rate among all referral sources.
2. Review and optimize coupon campaigns** to address the higher cancellation rate among coupon-assisted orders and improve conversion outcomes.
3. Improve order fulfillment processes** to reduce the volume of pending and cancelled orders, thereby enhancing customer satisfaction and operational efficiency.
4. Promote high-demand products**, particularly Chairs, through targeted marketing and inventory planning to maximize sales opportunities.
5. Monitor payment method performance**, especially Credit Card transactions, to identify and address factors contributing to higher cancellation rates while leveraging their strong revenue contribution.

## CONCLUSION
This analysis provided valuable insights into sales performance, customer behavior, and order outcomes. The business generated a total revenue of **1,264,761.96** with a healthy average order value of **1,053.97**. Email emerged as the most effective referral source, while Chairs were the most frequently ordered product. Online payments were the most preferred payment method, whereas Credit Card transactions generated the highest revenue. The analysis also revealed higher cancellation rates among coupon-assisted orders and Credit Card payments. Additionally, a considerable number of orders remained pending or were cancelled, indicating opportunities for process improvement. Overall, the findings can support data-driven decisions to improve customer experience, optimize marketing efforts, and drive business growth.

