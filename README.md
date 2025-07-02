# MySQL Pizza Sales Analysis

This repository contains a detailed analysis of pizza sales data using MySQL. The project aims to answer critical business questions and uncover insights into sales performance, customer behavior, and product popularity through SQL querying.

## 🎯 Project Overview

The goal of this project is to leverage SQL to analyze a relational database of pizza sales. By writing a series of queries, I explored the dataset to extract actionable insights that could help a pizza business optimize its operations, marketing efforts, and revenue generation. The analysis covers over 15 distinct business questions, ranging from high-level revenue metrics to detailed product-level trends.

## ❓ Business Questions Addressed

This analysis was driven by a set of key business questions. The SQL queries were crafted to find answers to the following:

**Sales & Revenue:**
1.  What is the total revenue generated from all pizza sales?
2.  What is the total number of orders placed?
3.  What is the average order value?
4.  How does the daily and monthly revenue trend over the given period?
5.  Generate a cumulative sum of revenue over time.

**Product & Customer Insights:**
6.  Which pizza is the best-seller by revenue?
7.  Which pizza is the best-seller by quantity?
8.  Which pizza size is ordered most frequently?
9.  What is the average number of pizzas per order?
10. What are the top 5 most ordered pizzas?

**Operational Insights:**
11. What are the peak business hours (busiest times of the day)?
12. What are the busiest days of the week for orders?
13. What is the distribution of orders by pizza category (e.g., Classic, Veggie, Supreme)?
14. What percentage of sales does each pizza size contribute?
15. Which pizzas have the highest and lowest prices?

## 🛠️ Tools & Technologies

* **Database:** MySQL
* **SQL Client:** MySQL Workbench (or any standard SQL client)
* **Data Source:** CSV files containing information on orders, order details, pizzas, and pizza types.

## 🗂️ SQL Queries

All the SQL queries used for this analysis are documented and available for review. They demonstrate a range of SQL capabilities, including aggregate functions, joins, window functions (for cumulative revenue), and subqueries.

**[View the complete list of SQL Queries here](https://lnkd.in/gy7cEe8J)**

For ease of use, you can also find all queries in the `pizza_sales_analysis.sql` file within this repository.

## ✨ Key Findings (Example Insights)

* **Total Revenue:** The total revenue generated across all sales was **$817,860.05**.
* **Peak Ordering Times:** The busiest hours for the pizzeria are between **12:00 PM - 1:00 PM** and **5:00 PM - 7:00 PM**.
* **Most Popular Pizza:** "The Classic Deluxe Pizza" was identified as the most frequently ordered pizza.
* **Highest Revenue Contributor:** While popular, "The Thai Chicken Pizza" generated the most revenue due to its higher price point.
* **Sales Distribution:** The 'Large' pizza size accounts for over 45% of all sales, making it the most significant category by revenue.

*(Note: These are example findings. Please update them with the actual results from your analysis.)*

## 🚀 How to Use This Repository

To replicate this analysis, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/pizza-sales-analysis.git](https://github.com/your-username/pizza-sales-analysis.git)
    ```
2.  **Set up the Database:**
    * Create a new database in your MySQL instance (e.g., `pizza_db`).
    * Create the necessary tables (`orders`, `order_details`, `pizzas`, `pizza_types`) using the schema provided in the `.sql` file or derived from the CSVs.
3.  **Import the Data:**
    * Import the data from the provided CSV files into their corresponding tables.
4.  **Run the Queries:**
    * Execute the queries from the `pizza_sales_analysis.sql` file in your preferred SQL client to perform the analysis.

Created by **[MAYINI CHARAN]**
