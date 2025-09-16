# 🏦 OOPS – Banking System

This project demonstrates the use of Object-Oriented Programming (OOPS) concepts in building a simple Banking System.
It models Savings Accounts and Current Accounts, handling deposits, withdrawals, interest calculations, overdraft facilities, and secure balance management.

## 🚀 Features

Encapsulation → Private balance (__balance) with secure access.

Inheritance → SavingsAccount and CurrentAccount extend BankAccount.

Polymorphism → withdraw() behaves differently for savings and current accounts.

Abstraction → Core account operations are abstracted in the base class.

File Handling → Transactions can be saved and retrieved from files.

Exception Handling → Handles invalid inputs, insufficient balance, and overdrafts gracefully.

📂 Project Structure
📁 OOPS-Banking-Project
│── OOPS - Banking Project.ipynb   # Main Jupyter Notebook
│── README.md                      # Project Documentation

## 💻 Technologies Used

Python 3.x

Jupyter Notebook

## 🔑 OOPS Concepts Used

Class & Objects – Account creation and management.

Encapsulation – Balance is private.

Inheritance – Different account types extend the base class.

Polymorphism – Same method (withdraw) works differently.

Abstraction – General banking operations.

## 📊 Example Usage
## Creating accounts
savings = SavingsAccount("Pooja", 5000)
current = CurrentAccount("Sudhakar", 10000)

# Deposit
savings.deposit(2000)

## Withdraw
current.withdraw(12000)  # Allows overdraft

## Balance
print(savings.get_balance())
print(current.get_balance())

## 📝 Future Enhancements

Add Graphical User Interface (GUI).

Include database support (MySQL/SQLite) instead of file handling.

Multi-user login system.

Generate transaction reports.

## 👨‍💻 Author

Nikhilesh Final Year Student | Passionate about OOPS & Real-World Applications
