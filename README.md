Customer Segmentation and Lookalike Model
----------------------------------------------------------------------------------------

This repository contains the code and analysis for customer segmentation and building a lookalike model using customer and transaction data. The goal of the project is to provide insights into customer behavior and create a model that recommends similar customers based on their profile and transaction history.

------------------------------------------------------------------------------------------
**Project Overview**
This project involves three main tasks:

1.Exploratory Data Analysis (EDA) and Business Insights

2.Lookalike Model

3.Customer Segmentation / Clustering

--------------------------------------------------------------------------------------------
The dataset used consists of three CSV files:

Customers.csv - Contains customer profile information.

Products.csv - Contains product details.

Transactions.csv - Contains transaction history for each customer.

---------------------------------------------------------------------------------------------
Dataset Description
1. Customers.csv
CustomerID: Unique identifier for each customer.
CustomerName: Name of the customer.
Region: Continent where the customer resides.
SignupDate: Date when the customer signed up.
2. Products.csv
ProductID: Unique identifier for each product.
ProductName: Name of the product.
Category: Product category.
Price: Product price in USD.
3. Transactions.csv
TransactionID: Unique identifier for each transaction.
CustomerID: ID of the customer who made the transaction.
ProductID: ID of the product sold.
TransactionDate: Date of the transaction.
Quantity: Quantity of the product purchased.
TotalValue: Total value of the transaction (Quantity * Price).
Price: Price of the product sold.

------------------------------------------------------------------------------------------------
Dependencies
------------------------------------------------------------------------------------------------
To run this project, make sure you have the following Python packages installed:

pandas

numpy

scikit-learn

seaborn

matplotlib

scipy
