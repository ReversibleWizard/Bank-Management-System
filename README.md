# Bank Management System

This project is a **Bank Management System** developed using Python and MySQL. It provides functionalities for employees and customers to perform various banking operations efficiently, with data stored and retrieved using a MySQL database.

---

## Features

### Employee Features
1. **Login**: Employees can log in to access the system.
2. **Create New Customer Accounts**: Employees can add new customer accounts to the database.
3. **View Customer Transactions**: Employees can retrieve and review transaction details for specific accounts.
4. **Transfer Money**: Facilitate money transfers between customer accounts.
5. **Modify Customer Details**: Employees can update customer information such as address and PIN.
6. **Exit System**: Logout and exit the system.

### New Employee
- Allows the addition of new employees to the system by providing a unique employee ID and password.

### Customer Features
1. **Login**: Customers can log in to access their account functionalities.
2. **Create New Accounts**: Customers can open additional accounts.
3. **View Transactions**: Customers can check their transaction history.
4. **Transfer Money**: Customers can transfer funds to other accounts.
5. **Withdraw Money**: Customers can withdraw money from their accounts.
6. **Deposit Money**: Customers can deposit money into their accounts.
7. **Change Account Details**: Customers can update their address or PIN.
8. **Delete Account**: Customers can permanently close their accounts.
9. **Exit System**: Logout and exit the system.

### New Customer
- Facilitates adding new customers by collecting necessary details such as:
  - Name
  - Aadhaar Card Number
  - Date of Birth
  - Address
  - Account Type
  - Initial Balance
  - PIN

---

## Technical Overview

- **Language**: Python
- **Database**: MySQL
- **Connector**: Uses `mysql-connector` package for Python to interact with the database.

The system handles the following operations:
1. **Customer Account Management**: Create, update, and delete customer accounts.
2. **Transactions**: Record deposits, withdrawals, and transfers between accounts.
3. **Data Security**: Password-protected login for both employees and customers.

---

## Code Functionality

The code interacts with a MySQL database to:
- **Store and Retrieve Data**: Customer and transaction data are securely stored in a relational database.
- **Perform Error Handling**: Manages exceptions during database operations and user interactions.
- **Utilize Python Fundamentals**: Implements functionalities using loops, conditionals, and functions.

---

## Setup Instructions

1. **Database Configuration**:
   - Create a MySQL database for the system.
   - Define tables for customers, employees, and transactions.
   - Create necessary stored procedures for account creation, transaction processing, and data retrieval.

2. **Install Required Libraries**:
   Install the required Python packages using the following command:
   ```bash
   pip install mysql-connector-python
   ```

3. **Update Credentials**:
   Modify the database connection code to include your MySQL credentials.
   ```python
   connection = mysql.connector.connect(
       host="localhost",
       user="your_username",
       password="your_password",
       database="your_database_name"
   )
   ```

4. **Run the Application**:
   Execute the script to start the Bank Management System.
   ```bash
   python bank_management_system.py
   ```

---

## Future Enhancements

1. **Improved Security**:
   - Implement hashed passwords for login credentials.
   - Add two-factor authentication for sensitive operations.

2. **Enhanced User Interface**:
   - Develop a GUI for better usability.
   - Optimize the menu navigation for both employees and customers.

3. **Advanced Features**:
   - Add support for loan management.
   - Include account statements and email notifications.

4. **Performance Optimization**:
   - Optimize database queries for faster operations.
   - Implement caching for frequently accessed data.

---

## Author
**Sayak**
- B.Tech in Computer Science and Communication Engineering, KIIT University.

