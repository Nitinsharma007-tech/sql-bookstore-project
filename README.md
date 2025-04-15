# 📘 Bookstore SQL Analytics Project

## 🧠 Overview
This project analyzes a fictional bookstore’s operations using SQL queries. The goal is to track books, customers, and orders, generate business insights, and perform data analysis like identifying top customers, best-selling genres, and total revenue.


## 🗃️ Tables

### 1. `BOOKS`
- Stores information about books in the store
- Columns: `Book_ID`, `Title`, `Author`, `Genre`, `Published_Year`, `Price`, `Stock`

### 2. `CUSTOMERS`
- Stores customer details
- Columns: `Customer_ID`, `Name`, `Email`, `Phone`, `City`, `Country`

### 3. `ORDERS`
- Stores order information, linking books to customers
- Columns: `Order_ID`, `Customer_ID`, `Book_ID`, `Order_Date`, `Quantity`, `Total_Amount`


## 🚀 Features

- Retrieve all books in the "Fiction" genre
- Calculate the total stock of books available
- List customers who placed more than one order
- Find the most expensive book
- Track total revenue and top customers
- Analyze books by genre and author


## 🧪 How to Run
1. Run `schema.sql` in your SQL environment to create the tables (`BOOKS`, `CUSTOMERS`, `ORDERS`).
2. Import the data from your CSV files using the method described in `data-import-notes.md`.
3. Run the queries in `queries/basic_queries.sql` and `queries/advanced_queries.sql` to analyze the data.

## 📊 Sample Insight
- 💰 **Total Revenue**: $542.30
- 📦 **Most Sold Genre**: Fantasy
- 🧍‍♂️ **Top Customer**: Alex Johnson – $120.50

## 👨‍💻 Built With
- SQL (MySQL)
- GitHub for version control

## 🙌 Author
Nitin Sharma
