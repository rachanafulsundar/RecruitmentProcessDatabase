# Recruitment Database Management System

## Project Overview
This project is a database management system for the Recruitment branch of the HR Department in a company. It tracks the status of a candidate's application throughout the interview and hiring process. The project includes designing, implementing, and testing the database with various functionalities such as views, stored procedures, user-defined functions, transactions, triggers, and security roles.

---

## Table of Contents
1. [Abstract](#abstract)
2. [Features](#features)
3. [Database Schema](#database-schema)
4. [Implementation](#implementation)
5. [Testing](#testing)
6. [Technologies Used](#technologies-used)
7. [Setup Instructions](#setup-instructions)
8. [How to Use](#how-to-use)
9. [Conclusion](#conclusion)
10. [Author](#author)

---

## Abstract
This project focuses on:
- Designing a robust database schema.
- Implementing key features like views, stored procedures, and triggers to track candidates' application statuses and manage recruitment-related data.
- Testing the database's functionality to ensure integrity and reliability.

---

## Features
- **Database Schema**: Comprehensive schema with normalized tables for jobs, applications, candidates, interviews, and more.
- **Stored Procedures**: For tasks like counting applications by status and retrieving interviews by type.
- **User-Defined Functions**: For custom queries like fetching recent interviews and application details.
- **Triggers**: To automatically update statuses based on related events.
- **Transactions**: Ensuring data consistency during complex operations.
- **Views**: Predefined queries for easy access to critical data.
- **Security Roles**: Role-based permissions for database security.

---

## Database Schema
The database includes tables for:
- **Job Positions and Types**: Tracks job categories and positions.
- **Candidates and Applications**: Manages candidate details and application processes.
- **Interviews and Feedback**: Stores details of interviews and related feedback.
- **Reimbursements and Complaints**: Tracks financial transactions and complaints.

---

## Implementation
Key implementation highlights:
1. **Creating Tables**: SQL scripts to define tables with appropriate constraints.
2. **Inserting Data**: Predefined data for testing and demonstration purposes.
3. **Testing Queries**: Views, stored procedures, and functions for testing database operations.

---

## Testing
The database has been rigorously tested to ensure:
- Accurate data retrieval.
- Proper functioning of stored procedures, triggers, and transactions.
- Role-based access control.

---

## Technologies Used
- **Database Platform**: SQL Server
- **Programming Language**: SQL
- **Tools**: SQL Server Management Studio (SSMS)
