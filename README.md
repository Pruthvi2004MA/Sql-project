# Online Bookstore — SQL Data Analysis

## Project Overview
This project implements a complete data analysis of an **online bookstore** using SQL. I import real datasets (CSV) into PostgreSQL using pgAdmin, create relational tables, and then write **20+ SQL queries** to answer business-oriented questions. The analysis covers both basic and advanced SQL skills including joins, aggregations, subqueries, and more.

## Dataset Description
The project is based on three CSV files:

- `books.csv` — Book metadata (book ID, title, author, genre, published year, price, stock)  
- `customers.csv` — Customer information (customer ID, name, email, city, country)  
- `orders.csv` — Order transactions (order ID, customer ID, book ID, order date, quantity, total amount)  

These datasets are loaded into PostgreSQL tables for analysis.

## SQL Queries & Business Questions
The analysis involves **two parts**:

1. **Basic Queries**  
   - List all Fiction books  
   - Retrieve all customers from a city  
   - Filter orders by date or amount  
   - Calculate total stock or total revenue  
   - … and more

2. **Advanced Queries**  
   - Genre-wise total books sold  
   - Top-spending customers  
   - Average price per genre  
   - Most frequently ordered books  
   - Remaining stock after orders  
   - … and additional deep-analysis

Each query is commented with the original business question, followed by your SQL solution.

## Key Insights
- Genre-level sales distribution (which genres sell the most)  
- High-value customers who make the most purchases  
- Trends in book orders (quantity, total amount)  
- Books with low or zero stock — inventory risk  
- Average price comparisons across genres  

## How to Run This Project
1. **Create a PostgreSQL database** (e.g., `online_book_store`)  
2. **Open pgAdmin** → run the SQL file `Onlinebookstore.sql` to:  
   - Create tables  
   - Import data from CSVs  
   - Execute all analysis queries  
3. **View results** in pgAdmin’s Query Tool  
4. Optionally, export query results or take screenshots

## Project Structure (Suggested)





