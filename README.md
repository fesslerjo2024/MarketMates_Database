# MarketMates Database – SQL Final Project

## Overview
**MarketMates** is a relational database system designed as a final project for *Database Concepts, Design, and Application*.  
The database models a retail-style business environment, managing suppliers, products, customers, employees, departments, and customer orders.

This project demonstrates database design principles, SQL Server configuration, table relationships, data integrity through constraints, and meaningful queries for real-world business use cases.

---

## Technologies Used
- **Microsoft SQL Server**
- **T-SQL (Transact-SQL)**
- SQL Server Management Studio (SSMS)

---

## Database Features
- Full database creation and configuration
- Normalized relational schema
- Primary and foreign key constraints
- Cascading deletes and NULL-handling rules
- Sample data for testing and demonstration
- Complex SELECT queries using JOINs and formatting

---

## Database Structure

### Tables Included
- **SUPPLIER** – Stores supplier contact and location information  
- **PRODUCT** – Tracks products, pricing, inventory, and supplier relationships  
- **CUSTOMER** – Stores customer contact and address details  
- **DEPARTMENT** – Represents internal company departments  
- **EMPLOYEE** – Tracks employee information, departments, and management hierarchy  
- **EMPLOYEE_SALARY_HISTORY** – Maintains historical salary records for employees  
- **CUSTOMER_ORDER** – Records customer orders, assigned employees, costs, and order status  

---

## Key Design Concepts
- **Referential Integrity** enforced using foreign keys  
- **ON DELETE CASCADE** used where child records should be removed automatically  
- **ON DELETE SET NULL** used to preserve records when relationships change  
- **Composite Primary Key** implemented in `EMPLOYEE_SALARY_HISTORY`  
- **Self-referencing relationship** for employee managers  

---

## Sample Queries Included
The project includes a wide range of queries such as:
- Listing products with their suppliers  
- Viewing customer orders with assigned employees  
- Displaying employee salary history over time  
- Joining employees with departments and managers  
- Formatting currency values for readability  

---

## How to Run the Project
1. Open **SQL Server Management Studio (SSMS)**
2. Create a new query window
3. Run the SQL script from top to bottom
4. The script will:
   - Create the database
   - Create all tables
   - Insert sample data
   - Execute example queries

---

## Learning Outcomes
Through this project, I demonstrated:
- Relational database design from requirements
- Writing clean, readable, and structured SQL
- Implementing business rules through constraints
- Using JOINs to combine data across multiple tables
- Designing queries suitable for real-world reporting

---

## Author
**Jonathan Fessler**  
Database Concepts, Design, and Application  
Final Project – April 2025
