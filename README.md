# 🏦 Simple Bank System

A simple interactive banking application built with **Python Object-Oriented Programming (OOP)** and **Gradio**.

This project demonstrates how Python OOP concepts can be combined with Gradio to build a simple web-based banking application that allows users to create bank accounts, view accounts, deposit money, and withdraw money.

---

## 🚀 Project Overview

The **Simple Bank System** is an educational Python project designed to demonstrate practical Object-Oriented Programming concepts through a real-world banking example.

The application provides a simple web interface where users can:

- Create new bank accounts
- View all existing accounts
- Display the total number of accounts
- Deposit money
- Withdraw money
- Check account balances
- Validate transactions
- Prevent withdrawals exceeding the available balance

---

## 🛠️ Technologies Used

- **Python 3**
- **Object-Oriented Programming (OOP)**
- **Gradio**
- **Virtual Environment (.venv)**

---

## 🧠 OOP Concepts Demonstrated

This project applies several important Python OOP concepts.

### 1. Classes and Objects

The `BankAccount` class represents a bank account.

```python
class BankAccount:
    def __init__(self, name, email, balance):
        self.name = name
        self.email = email
        self._balance = balance
