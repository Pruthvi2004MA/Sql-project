
📘 Online Book Store – SQL Data Analysis Project
PostgreSQL | pgAdmin | Real Dataset | 20+ SQL Queries
📌 Project Overview

This project explores an Online Book Store dataset where I created the entire database, imported CSV files, and wrote SQL queries to answer both basic and advanced business questions.

The project includes:

Creating the ONLINE_BOOK_STORE database

Creating tables: BOOKS, CUSTOMERS, ORDERS

Importing CSV data into PostgreSQL

Running 20+ SQL queries

Performing joins, aggregations, filters, subqueries, and calculations

Finding real insights about customers, books, orders, genres, and revenue

This project shows my SQL skills and ability to analyze real datasets.

📁 Dataset Details
imported data :

Customers.csv

Orders.csv

These datasets contain:

BOOKS TABLE

BOOK_ID

TITLE

AUTHOR

GENRE

PUBLISHED_YEAR

PRICE

STOCK

CUSTOMERS TABLE

CUSTOMER_ID

NAME

EMAIL

PHONE

CITY

COUNTRY

ORDERS TABLE

ORDER_ID

CUSTOMER_ID

BOOK_ID

ORDER_DATE

QUANTITY

TOTAL_AMOUNT

🛠️ Technologies Used

PostgreSQL

pgAdmin 4

SQL

GitHub

🗂️ Project Files Included
📄 Onlinebookstore.sql (your main file)

This SQL file contains:

🔹 1. Database Creation

Creating ONLINE_BOOK_STORE database

Creating BOOKS, CUSTOMERS, and ORDERS tables

🔹 2. Data Import
COPY CUSTOMERS FROM 'Customers.csv';
COPY ORDERS FROM 'Orders.csv';

🔹 3. Basic SQL Queries

Examples from your file:

Retrieve all books in the Fiction genre

Books published after 1950

List customers from Canada

Orders placed in November 2023

Total stock of books

Most expensive book

Orders with quantity > 1

Orders with total amount > 20

Distinct genres

Book with lowest stock

Total revenue generated

🔹 4. Advanced SQL Queries

Total books sold per genre (JOIN)

Average price of Fantasy books

Customers with at least 2 orders

Most frequently ordered book

Top 3 most expensive Fantasy books

Quantity sold by each author

Cities of customers spending > $30

Highest spending customer

Remaining stock after fulfilling all orders

These queries reflect strong SQL skills and real-world analysis.


⭐ Basic Questions (1–10)

All Fiction books

Books after 1950

Customers from Canada

Orders in November 2023

Total stock

Most expensive book

Quantity > 1 orders

Amount > $20 orders

All genres

Book with lowest stock

Total revenue

⭐ Advanced Questions (1–9)

Books sold by genre

Average price of Fantasy books

Customers with at least 2 orders

Most frequently ordered book

Top 3 expensive Fantasy books

Quantity sold by each author

Cities where spending > $30

Highest spending customer

Remaining stock after orders


Key Insights From the Analysis

Fiction and Fantasy appear as key genres

Some books have extremely low stock

Some customers consistently spend more than others

Certain authors generate higher revenue

Remaining stock varies based on order frequency

Genre-level revenue patterns can be identified

How to Run This Project

Create a database:

CREATE DATABASE ONLINE_BOOK_STORE;


Run the table creation queries from SQL file

Import your CSV files into pgAdmin

Run the Basic queries

Run the Advanced analysis queries

View insights and results
