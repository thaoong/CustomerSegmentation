# Customer Segmentation using RFM and K-means clustering
* This is the Final-term Project for Machine Learning in Business Analytisc course in University of Economic and Law, VNU by our team with 5 members.
* My duties: Data cleaning, EDA, Data analytics, Design dashboard

**Technical stack:** 
* Python
* Power BI

## 1. Overview
- Data source: This project used the dataset of a gift retailer and homewares from an online store in the UK from Kaggle.
- Objectives: The goal of the project is to segment customers based on RFM value. From there, analyze customer characteristics to propose appropriate marketing strategies to maximize revenue.

## 2. Data cleaning and EDA
[EDA](https://github.com/thaoong/CustomerSegmentation/blob/main/EDA.ipynb)

**Perform data cleaning & preprocessing through the following steps:**
* Remove canceled transaction
* Remove rows with unreasonable values ​​(negative price and quantity)
* Remove null values ​​of CustomerNo column
* Remove duplicated rows
* Add columns "month_year" and "TotalMoney" for each transaction to performm EDA

**Some insights gained from the EDA process**:
* The UK is the country has highest revenue and number of transactions.
* November 2019 is the month with the highest number of transactions and revenue.
* 3 products have highest number of transactions are Cream Hanging Heart T-light Holder, Jumbo Bag Retrospot and Regency 3 Tier.
* 2 products have highest revenue are Paper Craft Little Birdie and Medium Ceramic Top Storage Jar.

## 3. Data modeling
The data model has 2 tables: 
- Transaction table have data about the transactions, products info in transaction, customers and day of transactions.
- CustomerCluster table has data about each cluster and has relationship with Transaction table through column CustomerNo.
![image](https://github.com/user-attachments/assets/73936383-91a8-4255-8571-3677a47ea68d)

## 4. Dashboard
### 4.1. Sales dashboard
![image](https://github.com/user-attachments/assets/99429064-31f3-4d09-8b62-cdfbc56c7747)

### 4.2. Cluster dashboard
![image](https://github.com/user-attachments/assets/4dc5cd25-e9c6-49f3-aa4f-6e2e820bca9d)


