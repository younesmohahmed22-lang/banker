# 🏦 Simple Bank System

A simple banking application built with **Python OOP** and **Gradio**.

This project simulates a basic bank account system where users can create accounts, view accounts, deposit and withdraw money, and transfer money between accounts.

---

## 🚀 Features

* 👤 Create a new bank account
* 📧 Store customer name and email
* 💰 Set an initial account balance
* 📋 Display all created accounts
* 🔢 Show the total number of accounts
* 💵 Deposit money
* 💸 Withdraw money
* 🔄 Transfer money between accounts
* ✅ Validate transactions and account information
* 🖥️ Interactive web interface using Gradio

---

## 🛠️ Technologies Used

* **Python**
* **Object-Oriented Programming (OOP)**
* **Gradio**

---

## 📚 OOP Concepts Used

This project demonstrates several important Python OOP concepts:

* **Classes and Objects**
* **Constructors (`__init__`)**
* **Instance Attributes**
* **Class Attributes**
* **Methods**
* **Properties (`@property`)**
* **Encapsulation**
* **Private-like attributes using `_balance`**

---

## 📂 Project Structure

```text
Simple-Bank-System/
│
├── banker.py
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/Simple-Bank-System.git
```

### 2. Navigate to the project folder

```bash
cd Simple-Bank-System
```

### 3. Install Gradio

```bash
pip install gradio
```

---

## ▶️ Run the Application

Run the Python file:

```bash
python banker.py
```

After running the program, Gradio will provide a local URL such as:

```text
http://127.0.0.1:7860
```

Open the URL in your browser to use the application.

---

## 💡 How It Works

### Create Account

Users can enter:

* Name
* Email
* Initial Balance

The application creates a `BankAccount` object and stores it in the `accounts` list.

### Accounts

The Accounts section allows users to:

* View all created accounts
* Display the total number of accounts

### Transactions

Users can select an account and:

* Deposit money
* Withdraw money

The system checks the transaction before updating the balance.

### Transfer Money

Users can transfer money from one account to another by entering:

* From Account
* To Account
* Amount

The application checks that both accounts exist and that the sender has enough balance.

---

## 🧠 Example

Suppose we create two accounts:

```text
Account 1
Name: Younes
Email: younes@example.com
Balance: $1000.00
```

```text
Account 2
Name: Ahmed
Email: ahmed@example.com
Balance: $500.00
```

If Account 1 transfers `$200` to Account 2:

```text
From Account: 1
To Account: 2
Amount: $200
```

The balances become:

```text
Account 1 → $800
Account 2 → $700
```

---

## ⚠️ Note

This project is an educational banking simulation.

It does **not** connect to a real bank, database, payment system, or real financial accounts.

The account data is stored in memory and will be lost when the application is stopped.

---

## 🎯 Purpose

The main purpose of this project is to practice:

* Python programming
* Object-Oriented Programming
* Functions and classes
* Data validation
* Lists and objects
* Building a simple GUI/web interface with Gradio

Python & AI Student
