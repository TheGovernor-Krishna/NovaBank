# 🏦 Banking Information System

A console-based **Banking Information System** developed using **Core Java** as part of a Java Development Internship. The project simulates the core functionalities of a real-world banking application by implementing secure customer management, account operations, transaction processing, and persistent data storage.

The primary objective of it is to provide a practical understanding of **Object-Oriented Programming (OOP)**, **Java Collections**, **File Handling**, **Serialization**, and **Exception Handling** through a modular and menu-driven banking application.

---

# 📖 Project Overview

NovaBank is designed as a prototype banking application that allows registered customers to perform essential banking operations through a console-based interface. The application follows a modular architecture using Java packages and demonstrates how different components of a banking system interact with each other.

The project maintains customer records, account information, and transaction history while ensuring data persistence using Java Serialization. Every operation performed by the customer is reflected immediately in the account balance and stored for future sessions.

This project was developed by following the Banking Information System problem statement provided during the Java Development Internship and focuses on implementing the core functionalities expected from a basic banking application.

---

# 🎯 Project Objectives

- Develop a modular banking application using Core Java.
- Apply Object-Oriented Programming principles in a real-world project.
- Implement secure customer registration and login.
- Manage customer accounts efficiently.
- Perform deposit, withdrawal, and fund transfer operations.
- Maintain transaction history using a mini statement.
- Store customer, account, and transaction data using Java Serialization.
- Handle invalid operations using exception handling.
- Organize the project using packages for better maintainability.
- Simulate the workflow of a basic banking management system.

---

# ✨ Key Features

NovaBank provides the following banking functionalities:

### 👤 Customer Management
- Customer Registration
- Secure Customer Login
- View Customer Profile
- Update Customer Profile
- Change Password

### 🏦 Banking Operations
- Deposit Money
- Withdraw Money
- Fund Transfer
- Check Account Balance
- Search Account

### 📄 Transaction Management
- Mini Statement
- Transaction History
- Remaining Balance Tracking

### 💾 Data Management
- Persistent Data Storage using Java Serialization
- Customer Records
- Account Records
- Transaction Records

### ⚠️ Exception Handling
- Invalid Login Credentials
- Insufficient Balance
- Invalid Transaction Amount
- Account Not Found
- Basic Input Validation

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Core Java | Application Development |
| Object-Oriented Programming (OOP) | Software Design |
| Java Collections (ArrayList) | Data Storage During Execution |
| Java Serialization | Persistent Data Storage |
| File Handling | Read/Write Object Data |
| Exception Handling | Error Management |
| LocalDateTime API | Transaction Date & Time |
| Git & GitHub | Version Control |

---

# 📂 Project Structure

```text
NovaBank
│
├── src
│   ├── com
│   │   └── novabank
│   │       ├── model
│   │       ├── service
│   │       ├── storage
│   │       ├── util
│   │       ├── exception
│   │       └── Main.java
│   │
│   ├── accounts.dat
│   ├── customers.dat
│   └── transactions.dat
│
├── Screenshots
│
├── README.md
└── .gitignore
```

---

# 📦 Packages

### 📁 model
Contains all entity classes used in the project.

- Customer
- Account
- Transaction
- Admin

---

### 📁 service

Contains the business logic of the Banking Information System.

- Customer Registration
- Login
- Deposit
- Withdrawal
- Fund Transfer
- Mini Statement
- Password Management

---

### 📁 storage

Responsible for data persistence using Java Serialization.

- DataStorage

---

### 📁 util

Contains helper classes.

- IdGenerator

---

### 📁 exception

Contains custom exception classes used for error handling.


# 💻 Application Workflow

The application follows the workflow shown below:

```
Start Application
        │
        ▼
 Main Menu
        │
 ┌──────┴────────┐
 │               │
Register      Login
 │               │
 ▼               ▼
Customer Dashboard
 │
 ├── View Profile
 ├── Update Profile
 ├── Deposit
 ├── Withdraw
 ├── Transfer
 ├── Mini Statement
 ├── Change Password
 └── Logout
```


# 🎓 Learning Outcomes

Through this project, I gained practical experience in:

- Core Java Programming
- Object-Oriented Programming (OOP)
- Java Packages
- Java Collections Framework
- File Handling
- Java Serialization
- Exception Handling
- Modular Software Development
- Git & GitHub Version Control
- Debugging and Problem Solving
