# Task 1 - AirlineDB Schema Design

## 📌 Overview
This task was part of my SQL Developer Internship. The goal was to design and 
implement a relational database schema using MySQL Workbench.

## ✈️ Database Chosen
**Airline Database (airlinedb)** – to manage flights, passengers, bookings, and payments.

## 🗂️ Files Included
- `task1.sql` → SQL script to create `airlinedb` and its tables.
- `er-diagram.png` → ER diagram screenshot generated from MySQL Workbench.
- `README.md` → Documentation about the task.

## 🏗️ Schema Design
The database includes the following sample tables:
- `Flights` – stores flight details
- `Passengers` – stores passenger information
- `Bookings` – flight bookings by passengers
- `Tickets` – ticket details linked to bookings
- `Payments` – payment information

## ⚙️ Tech Stack
- MySQL 8.0
- Xampp


 ## ER diagram
<img width="1822" height="736" alt="ER-airline" src="https://github.com/user-attachments/assets/350431c3-c979-4f51-a3ba-3e7cc0ab9b1f" />

---
## INTERVIEW QUESTONS:
1. What is normalization?
Normalization is a way of organizing data in a database to reduce duplication and improve data integrity. It's like cleaning up your data so you don't have the same information stored in multiple places.

2. What is a primary key and foreign key?
Primary Key: A unique identifier for a record in a table. Think of it like an ID number for a student in a school database. No two students can have the same ID.
Foreign Key: A field in one table that refers to the primary key in another table. It's used to link two tables together. For example, a "student" table might have a "class ID" which is a foreign key that links to the "classes" table.

3. What are constraints?
Constraints are rules enforced on data in a database to ensure its accuracy and reliability. Examples include making sure a field isn't empty (NOT NULL) or that a value is unique.

4. What is a candidate key?
A candidate key is a column or a set of columns that can uniquely identify a record in a table. A primary key is chosen from the set of candidate keys.

5. How do you avoid data redundancy?
You avoid data redundancy by using normalization. This involves breaking down a large table into smaller, related tables and using primary and foreign keys to link them.

6. What is DDL and DML?
DDL (Data Definition Language): Commands used to define the database structure. For example, CREATE TABLE and ALTER TABLE.
DML (Data Manipulation Language): Commands used to manage data within the database. For example, INSERT, UPDATE, and DELETE.

7. What are the types of relationships in DBMS?
One-to-One: A single record in one table is related to a single record in another table.
One-to-Many: A single record in one table is related to many records in another table. (e.g., one teacher teaches many students).
Many-to-Many: Many records in one table are related to many records in another table. (e.g., many students can enroll in many different courses).

8. What is the advantage of AUTO INCREMENT?
AUTO INCREMENT automatically generates a new, unique number for each new record you add to a table. This is very useful for creating unique primary keys without having to manually keep track of the numbers.

9. What is the default storage engine in MySQL?
The default storage engine in MySQL is InnoDB. It's known for being reliable, supporting transactions, and using foreign keys.

10. What is a composite key?
A composite key is a primary key that is made up of two or more columns. It's used when a single column isn't enough to uniquely identify a record. For example, a "course registration" table might use a combination of "student ID" and "course ID" as its composite key.
