# Retail Performance Dashboard

Leveraging a 3-years worth of Sales data, I've created a simple performance Dashboard (SQL Server &amp; PowerBI)

In this use case, I’ve received three (3) flat files (Sales from 2020 to 2022) with raw data for Sales transactions from a Retail brand with both brick & mortar and online presence. 
First step was to create one unique flat file from the three files and upload it to a SQL Server instance.
Once in SQL Server, I proceeded to normalize the dataset, by creating multiple tables:
1.	Customers
2.	Products
3.	Transactions
4.	Orders

I also created some tables to develop a RFM model (Recency, Frequency and Monetary value)
1.	Customers_RFM
2.	RFM
3.	RFM_Scoring


# CREATING THE TABLES (SQL SERVER)

![Creating_Tables_Retail_Dashboard](https://user-images.githubusercontent.com/61191669/221925854-a00fff24-fc7f-4ae9-b019-510b5357057a.png)


# CALCULATING RFM (Recency, Frequency & Monetary Value)

![RFM_1_Retail_Dashboard](https://user-images.githubusercontent.com/61191669/221926399-bb2afdbe-7793-41c4-b53f-71da7b23cc2f.png)


# CONNECTING THE TABLES TO POWERBI AND CREATING DATA MODEL (POWERBI)

![PowerBI_Retail_Dashboard_1](https://user-images.githubusercontent.com/61191669/221927016-83ea425e-5149-4ae5-9f45-4a709e056ac3.png)


# CREATING THE DASHBOARD (POWERBI)

![Retail_Dash_1](https://user-images.githubusercontent.com/61191669/221928122-22cb37db-3c48-4041-b7db-9b027be4f473.png)

![Retail_Dash_2](https://user-images.githubusercontent.com/61191669/221928169-885b6db0-57c6-4f02-9f97-2aad5d41a505.png)

![Retail_Dash_3](https://user-images.githubusercontent.com/61191669/221928198-ade6859a-2582-42d2-bb33-8be0ccc4740e.png)



