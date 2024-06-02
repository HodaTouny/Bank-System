# Bank System

This is a simple bank system implemented using Python for backend development and SQL for database management. The system's main goal is to manage multiple banks, their branches, customers, loans, and accounts efficiently.

## Features

- **Bank Management**: Each bank has a unique name, code, and address.
- **Branch Management**: Banks have multiple branches, each identified by a branch number and address.
- **Customer Management**: Branches have multiple customers, each identified by their SSN, name, phone number, and address.
- **Loan Management**: Branches offer various types of loans, each identified by a loan number, loan type, and amount.
- **Account Management**: Customers can have multiple accounts, each identified by an account number, balance, and type.
- **Functionalities**:
  - **User Management**: Signing up new users (e.g., customers, employees) and updating user details.
  - **Bank Management**: Adding a new bank and its branches by administrators.
  - **Customer Management**: Adding new customers by employees.
  - **Loan Operations**: Requesting, starting, accepting, rejecting, and paying loans by customers and employees.

## Implementation Details

- **Database**: The system's data is stored in a relational database using SQL.
- **ERD (Entity-Relationship Diagram)**: An ERD has been designed to visualize the relationships between different entities (banks, branches, customers, loans, and accounts).
- **Python**: The backend logic and functionalities are implemented in Python, leveraging SQL queries to interact with the database.

## Getting Started

1. **Database Setup**: Create the necessary tables in your preferred SQL database management system using the provided schema.
2. **Python Setup**: Ensure Python is installed on your system.
3. **Run the Application**: Execute the main Python script to start the Bank System application.
