🏦 Bank Customer Segmentation Dashboard – Power BI

📌 Project Overview
This project focuses on analyzing bank customers using Power BI to uncover insights related to customer demographics, transaction behavior, segmentation, profitability, and risk.
The goal is to transform raw transaction-level data into actionable business insights that support data-driven decision-making.

🎯 Business Objectives
Understand who the customers are (demographics & geography)
Analyze how customers transact over time
Segment customers based on transaction behavior
Identify high-value and high-risk customers
Support customer retention, marketing, and risk monitoring strategies

📂 Dataset Description
The dataset contains transaction-level banking data, where each row represents a customer transaction.

Key Columns:
CustomerID – Unique identifier for each customer
CustomerDOB – Date of birth (used to calculate age)
CustGender – Gender of the customer
CustLocation – Customer location
CustAccountBalance – Account balance
TransactionID – Unique transaction identifier
TransactionDate & TransactionTime – Date and time of transaction
TransactionAmount (INR) – Transaction value

🧹 Data Preparation
Cleaned and transformed data using Power Query
Handled missing and invalid values logically
Calculated Age and Age Groups
Aggregated transaction-level data into customer-level metrics
Built a star-style data model for efficient analysis

📊 Dashboard Structure

🔹 Page 1: Customer Demographics
Total Customers, Average Age, Locations
Gender distribution
Age group analysis
Location-wise customer distribution

🔹 Page 2: Transaction Behavior
Total, average, and highest transaction values
Daily transaction volume vs revenue (combo chart)
Transaction trends by age group
Interactive slicers for date, time, and amount

🔹 Page 3: Customer Segmentation
Customers segmented as Lost, New, and Loyal
Revenue by segment
Average revenue and transactions per customer
Age group vs segment analysis

🔹 Page 4: Profitability & Risk Analysis
Total customer revenue
Average account balance
High-risk customer identification
Risk-level distribution
Top 10 high-revenue but high-risk customers

🧠 Key Insights
Majority of customers belong to the 25–45 age group
Loyal customers, though fewer, generate the highest revenue per customer
High-risk customers maintain low balances but still contribute significant revenue
Customer segmentation helps prioritize retention over acquisition

🛠 Tools & Technologies
Power BI Desktop
DAX (Measures & Calculated Columns)
Power Query
Data Visualization & Dashboard Design

🚀 Features
Interactive slicers synced across pages
Navigation buttons for seamless user experience
Reset filters using bookmarks
Optimized visuals for large datasets

📈 Future Enhancements
Integrate credit score data for improved risk analysis
Add customer churn indicators
Automate data refresh with live data sources

🏁 Conclusion
This project demonstrates how Power BI can be used to convert raw banking data into meaningful insights, helping businesses understand customers better and make informed strategic decisions.
