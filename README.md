# Music Store Data Analysis using SQL

## Project Overview

This project focuses on analyzing a digital music store database using SQL.
The objective is to explore the dataset and extract meaningful business insights such as identifying the best customers, cities with the highest revenue, and countries generating the most invoices.

The analysis helps demonstrate practical SQL skills including data aggregation, filtering, grouping, and joining multiple tables.

---

## Tools & Technologies Used

* SQL (MySQL)
* Microsoft Excel (for dataset preparation)
* GitHub (for project hosting)

---

## Dataset Description

The dataset represents a digital music store and contains multiple related tables such as:

* **customer** – Information about customers
* **invoice** – Records of purchases made by customers
* **invoice_line** – Details of each item purchased
* **track** – Information about music tracks
* **album** – Album details
* **artist** – Artist information
* **employee** – Store employee details

---

## Database Relationships

Some important relationships in the dataset include:

* `customer.customer_id → invoice.customer_id`
* `invoice.invoice_id → invoice_line.invoice_id`
* `track.track_id → invoice_line.track_id`
* `artist.artist_id → album.artist_id`
* `album.album_id → track.album_id`

These relationships allow complex queries using SQL joins.

---

## Business Questions Solved

### Easy Level Queries

1. Who is the senior most employee based on job title?
2. Which countries have the most invoices?
3. What are the top 3 values of total invoices?
4. Which city has the highest total invoice amount?
5. Which customer has spent the most money?

### Moderate Level Queries

1. Identify the best customers based on spending.
2. Find the most popular music genres by country.
3. Determine top artists based on number of tracks sold.

### Advanced Level Queries

1. Find the amount spent by each customer on each artist.
2. Identify the most popular genre for each country.
3. Determine the top customer for each country.

---

## Key Insights

* Certain countries generate a higher number of invoices compared to others.
* A few customers contribute significantly to total revenue.
* Some cities have much higher purchase activity, making them ideal for marketing or promotional events.

---

## Project Structure

```
music-store-sql-project
│
├── datasets
│   ├── customer.csv
│   ├── invoice.csv
│
├── sql_queries
│   ├── easy_queries.sql
│   ├── moderate_queries.sql
│   ├── advanced_queries.sql
│
├── screenshots
│   ├── query_results.png
│
└── README.md
```

---

## Purpose of the Project

This project demonstrates the ability to:

* Write SQL queries for data analysis
* Perform aggregations and filtering
* Use joins to combine multiple tables
* Extract business insights from relational databases

---

## Author

**Babita Khatri**

This project is part of my learning journey in **Data Analysis and Data Science**.
