# 📊 SQL Data Retrieval Queries – MySQL Practice

This repository demonstrates core **SQL data retrieval techniques** using the `gauridb1` e-commerce database. It includes essential query patterns for selecting, filtering, and sorting data effectively from various tables like `customers`, `orders`, `products`, and `payments`.

---

## 🎯 Objectives Covered

### 1. Selecting Data

- Retrieve all columns from a table for full visibility of records.
- Select specific columns to fetch only relevant fields like customer name, ID, or email.
- Useful when working with large tables and aiming for performance optimization.

---

### 2. Filtering with WHERE Clause

The project includes examples of using:

- **AND**: To apply multiple conditions that must all be true.
- **OR**: To return records meeting at least one condition.
- **LIKE**: For pattern matching, especially in text-based searches.
- **BETWEEN**: To filter data within a specific numeric or date range.
- **Combined Conditions**: Applying logical grouping for more refined filtering (e.g., mixing `OR` with `BETWEEN`).

These filters help in narrowing down large datasets to extract precise information.

---

### 3. Sorting Results with ORDER BY

This section demonstrates:

- Sorting records alphabetically or numerically in **ascending** or **descending** order.
- Sorting by **multiple columns** for layered sorting (e.g., by customer ID and date).
- Using **ORDER BY with WHERE** to get sorted filtered results.
- Applying **LIMIT** to show only top results (e.g., top 3 highest priced products).

Sorting is vital for organizing data views and prioritizing key records.

---

## 🧠 Key Learning Outcomes

- Understand the difference between `SELECT *` and column-specific retrieval.
- Apply various filtering techniques to extract accurate subsets of data.
- Master sorting records by one or more criteria, with or without limits.
- Learn how to combine all three concepts to write powerful and flexible SQL queries.

---

## 📁 Tables Used

- **Customers**: For retrieving user contact information.
- **Products**: For product details and pricing.
- **Orders**: For filtering by customer and date.
- **Payments**: For filtering by amounts and payment dates.

---

## 🛠 Tools Used

- MySQL 8.x  
- MySQL Workbench  
- GitHub 

---
---

