Online Bookstore — SQL Data Analysis

Project Overview

This project performs a full-scale data analysis of an online bookstore. I used PostgreSQL (via pgAdmin) to import datasets, create a relational schema, and run 20+ SQL queries that answer both business-focused and analytical questions. The queries range from simple selections to joins, aggregations, subqueries, and advanced data insights.

Dataset Description

The project is based on three CSV files:

books.csv — Contains book details (ID, title, author, genre, price, stock, etc.)

customers.csv — Contains customer data (ID, name, email, city, country, etc.)

orders.csv — Contains order records (order ID, customer ID, book ID, order date, quantity, total amount)

These CSVs were imported into PostgreSQL tables for analysis.

SQL Queries & Business Questions
Basic Queries

List all books in a specific genre

Filter customers by location

Retrieve orders made in a particular month

Calculate total inventory value

Find high-value or frequent orders

… and more

Advanced Queries

Genre-wise book sales using JOIN

Top-spending customers

Average book price per genre

Most frequently ordered books

Remaining stock after fulfilling orders

Customer segmentation based on order count/amount

… and other deeper analytical insights

Each query in the SQL file is preceded by a comment stating the business question, making it clear what is being solved.

Key Insights & Learnings

Genres that generate the highest revenue

Customers who contribute the most to sales

Trends in orders (time-based and quantity-based)

Inventory risks — books with low or zero stock

How to use PostgreSQL effectively to answer business questions

How to Run This Project

Create a PostgreSQL database (e.g., online_book_store)

Open pgAdmin and run the Onlinebookstore.sql file to:

Create tables

Import CSV data

Execute all analysis queries

View the results in the pgAdmin Query Tool

Optionally, export results or take screenshots for reporting
