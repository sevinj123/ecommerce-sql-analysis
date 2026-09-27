# ecommerce-sql-analysis
PostgreSQL case study analyzing e-commerce sales, customers, products, revenue trends, and regional performance using JOINs, CTEs, CASE, and aggregate functions.
# E-commerce Sales Analysis with PostgreSQL

## Project Overview

This project analyzes an e-commerce dataset using PostgreSQL. The goal is to answer practical business questions related to orders, customers, products, categories, revenue, and regional performance.

The analysis includes 13 SQL questions ranging from basic filtering to multi-step CTEs and customer comparisons.

## Database Structure

The project uses five tables:

- `customers` — customer details and countries
- `orders` — order dates, customers, and statuses
- `order_items` — products, quantities, and selling prices
- `products` — product names, prices, and categories
- `categories` — product category names

## SQL Skills Used

- Filtering with `WHERE`
- Sorting with `ORDER BY`
- `INNER JOIN`
- Aggregate functions: `COUNT`, `SUM`, and `AVG`
- `GROUP BY` and `HAVING`
- `CASE` expressions
- Common Table Expressions (CTEs)
- `CROSS JOIN`
- Comparing customers with overall and country-level averages
- Window functions

## Business Questions

The analysis answers questions such as:

- How many orders exist for each status?
- How many orders are placed each month?
- What is the total value of each successful order?
- Which customers spend the most?
- Which products sell the most units?
- Which categories generate the most revenue?
- How do countries compare by orders, customers, and revenue?
- What is the average order value in each country?
- Which customers spend more than the overall customer average?
- Which customers spend more than the average in their own country?

## Key Findings

- Total revenue from successful orders was **230,175**.
- `Product_90` was the highest-revenue product, generating **13,050**.
- Azerbaijan generated the highest country revenue at **73,125**.
- Turkey generated the lowest country revenue at **13,545**.
- Average order value varied significantly by country:
  - Azerbaijan: **1,218.75**
  - Turkey: **225.75**
- Although the countries had the same number of successful orders, differences in average order value created large revenue gaps.
- **75 customers** spent more than the average customer spending in their own country.

## Files

- [`queries.sql`](queries.sql) — SQL queries used in the analysis
- `screenshots/` — selected query results from pgAdmin

## Tools

- PostgreSQL
- pgAdmin 4
- GitHub

## Author

**Sevinj**  
Aspiring Data Analyst
