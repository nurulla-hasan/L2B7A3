# Football Ticket Booking System

This project is a relational database management system for a football ticket booking platform. It demonstrates database design (ERD), table creation, and advanced SQL querying.

## Project Structure
- **database_setup.sql**: Contains all the DDL (CREATE, DROP) and DML (INSERT) scripts to build the database.
- **SQL Queries**: A set of queries covering essential database operations.

## Key Features
- **Database Schema**: Structured tables for `Users`, `Matches`, and `Bookings`.
- **Relational Integrity**: Uses `PRIMARY KEY`, `FOREIGN KEY`, and `CHECK` constraints to ensure data consistency.
- **Advanced SQL Techniques**:
    - Filtering with `LIKE` and `ILIKE`.
    - Data handling with `COALESCE` and `IS NULL`.
    - Complex data joining with `INNER JOIN` and `LEFT JOIN`.
    - Data analysis using `Subqueries` and `AVG()`.
    - Record management with `ORDER BY`, `LIMIT`, and `OFFSET`.

## Technologies Used
- PostgreSQL
- Beekeeper Studio (SQL Client)
- Git & GitHub

## How to Run
1. Clone this repository.
2. Open the `query.sql` file in any PostgreSQL-compatible SQL client.
3. Execute the script to create the tables and seed the data.
4. Run the provided queries to explore the dataset.

---
*Developed for the Database Management Assignment.*