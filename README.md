# 🏦 Bank Management System – CLI  Project (C++)

A Command-Line Based **Bank Management System** implemented in **C++** using **Object-Oriented Programming (OOP)** and **Standard Template Library (STL)** data structures like `map`, `stack`, `queue`,`vector`, and BST. This mini project simulates core banking operations like customer registration, deposit/withdrawals, transaction history, employee login, and service request handling.

---

## 📌 Features

### 👨‍💼 Employee Functionalities
- Login using Employee ID & password
- Create and modify customer accounts
- View all customer accounts
- Process customer service requests
- Register new employee accounts

### 👨‍💻 Customer Functionalities
- Create a new bank account
- Login and perform transactions
- Modify personal information
- Deposit / Withdraw money
- Transfer funds between accounts
- View transaction history
- Submit service requests

---

## 🧠 Concepts & Technologies Used

- **Object-Oriented Programming (OOP)**  
  - Classes & Encapsulation (`Bank` class and nested `AccountNode`)
- **File Handling**  
  - Persistent data storage using `.csv` files for accounts and credentials
- **Data Structures**
  - `map`: Stores account and employee login credentials
  - `stack`: Tracks last 10 transactions
  - `queue`: Manages customer service requests
  - `vector`: Maintains global transaction history
- **Binary Search Tree (BST)**  
  - Used to manage account records for fast search, insert, and modify
- **System Libraries**
  - `windows.h` for console color and UI enhancements
