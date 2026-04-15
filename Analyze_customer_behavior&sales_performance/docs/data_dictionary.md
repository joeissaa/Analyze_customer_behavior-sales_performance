# 📂 Data Dictionary
## 📌 Overview
This document describes the structure of the dataset used in the project, including tables, columns, and their meanings.


## 💰 Sales Data Final Table

| Column Name | Description |
|------------|------------|
| Category | Product category associated with the sale |
| Customer ID | Unique identifier for the customer |
| Customer Type | Classification of the customer is new customer or not  |
| Date | Date of the sales transaction |
| Invoice ID | Unique identifier for each sales invoice |
| Month Name | Name of the month of the transaction |
| Net_Profit | Profit amount after deducting costs |
| Payment Method | The method used for payment (Bank Transfer, Cash, Credit card) |
| Product ID | Unique identifier for the product sold |
| Quantity | Number of units sold in the transaction |
| Region | Geographical location where the sale occurred |
| Total | Total price for the transaction (Quantity * Unit Price) |
| Unit Price | Selling price per single unit |


## 👤 Customers Table

| Column Name | Description |
|------------|------------|
| Customer ID | Unique identifier for each customer |
| Customer Name | Full name of the customer |
| Customer Type | Classification of the customer is new customer or not  |
| Region | Geographical area where the customer is located |

## 📦 Products Table

| Column Name | Description |
|------------|------------|
| Category | The category to which the product belongs |
| Cost | The production or purchase cost of the product |
| Product ID | Unique identifier for the product |
| Product Name | The official name of the product |

## 💬 Customer Feedback Table

| Column Name | Description |
|------------|------------|
| Invoice ID | Unique identifier for the related sales invoice |
| Product Quality Rating | Customer score for the quality of the product (0:5) |
| Rate_classify | Categorization of the rating (High, Medium, Low) |
| Service Rating | Customer score for the service provided (0:5)|