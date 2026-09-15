# E-Commerce Database – Week 3

## Project Description

This project is a simple **E-Commerce Database Management System** using MySQL.

The project manages:

* Seller details
* Product inventory
* Product quantities
* Seller and inventory relationships

## Database

**Database Name:** `ecommerce`

## Tables

### 1. Seller

Stores seller information.

| Column      | Description         |
| ----------- | ------------------- |
| seller_id   | Unique ID of seller |
| seller_name | Name of seller      |
| phone       | Seller phone number |

### 2. Inventory

Stores product and stock information.

| Column       | Description         |
| ------------ | ------------------- |
| inventory_id | Unique inventory ID |
| seller_id    | ID of the seller    |
| product_name | Name of product     |
| quantity     | Available quantity  |

The `seller_id` in Inventory is connected to the Seller table using a **Foreign Key**.

## Sample Data

The project contains sellers such as:

* ABC Traders
* Sri Stores
* Green Mart

Products include:

* Rice
* Sugar
* Wheat
* Oil
* Biscuits

## SQL Operations

The project demonstrates:

1. **Create Database**
2. **Create Tables**
3. **Insert Records**
4. **Display Inventory**
5. **Update Product Quantity**
6. **Count Total Products**
7. **Find Out-of-Stock Products**
8. **Find Product with Maximum Quantity**
9. **Calculate Average Quantity**
10. **Join Seller and Inventory Tables**
11. **Calculate Total Quantity**

## How to Run

1. Open **MySQL Workbench**.
2. Open the `Week 3.sql` file.
3. Run the SQL code from top to bottom.
4. The `ecommerce` database and required tables will be created.
5. Execute the SELECT queries to view the results.

## Technologies Used

* MySQL
* MySQL Workbench
* SQL

## Author

**Samuvel.U**
