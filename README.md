# Filtering-Projection

1. Using SELECT * and Specific Columns
Select all columns from products table

SELECT * FROM products;
Select specific columns from customers

SELECT customer_id, name, email FROM customers;


2. Applying WHERE Conditions with AND, OR, LIKE, BETWEEN
WHERE with AND

SELECT * FROM orders 
WHERE customer_id = 1 AND order_date > '2025-01-01';
WHERE with OR

SELECT * FROM customers 
WHERE city = 'New York' OR city = 'Chicago';
WHERE with LIKE

SELECT product_id, product_name FROM products
WHERE product_name LIKE '%Phone%';
WHERE with BETWEEN

SELECT * FROM payments
WHERE amount_paid BETWEEN 500 AND 1000;
Combining conditions

SELECT * FROM orders
WHERE (customer_id = 1 OR customer_id = 3)
AND order_date BETWEEN '2025-01-01' AND '2025-06-30';


3. Sorting with ORDER BY
Basic ascending sort

SELECT name, email FROM customers
ORDER BY name ASC;
Descending sort

SELECT product_name, price FROM products
ORDER BY price DESC;
Multi-column sorting

SELECT customer_id, order_date FROM orders
ORDER BY customer_id ASC, order_date DESC;
Sorting with WHERE conditions

SELECT * FROM payments
WHERE payment_date IS NOT NULL
ORDER BY payment_date DESC;
Sorting with LIMIT

SELECT * FROM products
ORDER BY price DESC
LIMIT 3;
