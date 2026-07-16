# BankingSystem
# 🏦 Console Banking Application (Java)

A simple **Console-Based Banking Application** developed in **Java** to demonstrate the core concepts of **Object-Oriented Programming (OOP)**.

This project allows users to create bank accounts, deposit money, withdraw money, and check account balances through a menu-driven console interface.

---

## 📌 Features

- Create Savings and Current Accounts
- Deposit Money
- Withdraw Money
- View Account Balance
- Display Customer and Account Details
- Menu-driven Console Application

---

## 🚀 Technologies Used

- Java
- OOP Concepts
- Collections Framework (ArrayList)
- Scanner Class

---

## 🏗️ Project Structure

```
BankingSystem
│
├── entities
│   ├── Customer.java
│   ├── Account.java
│   ├── SavingsAccount.java
│   └── CurrentAccount.java
│
├── service
│   └── Bank.java
│
└── main
    └── Main.java
```

---

## 📚 OOP Concepts Implemented

### 🔹 Encapsulation
- Private data members
- Getters and Setters
- Data hiding

### 🔹 Abstraction
- Abstract class `Account`
- Abstract method `withdraw()`

### 🔹 Inheritance
- `SavingsAccount` extends `Account`
- `CurrentAccount` extends `Account`

### 🔹 Polymorphism
- Method overriding of `withdraw()`
- Runtime polymorphism using the `Account` reference

---

## 💻 Menu Options

```
===== BANK MENU =====

1. Create Account
2. Deposit
3. Withdraw
4. View Balance
5. Display Account Details
6. Exit
```

---

## 📖 Class Description

### Customer
Stores customer information.

**Fields**
- Customer ID
- Customer Name
- Phone Number
- Address

---

### Account (Abstract)

Contains common properties of every account.

**Fields**
- Account Number
- Balance
- Customer

**Methods**
- deposit()
- withdraw() (Abstract)
- getBalance()
- displayAccountDetails()

---

### SavingsAccount

Extends Account.

Implements withdrawal with a minimum balance condition.

---

### CurrentAccount

Extends Account.

Implements withdrawal with an overdraft limit.

---

### Bank

Manages all accounts.

Functions:
- Create Account
- Search Account
- Deposit Money
- Withdraw Money
- Display Balance
- Display Account Details

---

### Main

Contains the menu-driven interface and interacts with the user.

---

## ▶️ How to Run

1. Clone the repository

```
git clone https://github.com/parmar3/BankingSystem.git
```

2. Open the project in Eclipse or IntelliJ IDEA.

3. Run `Main.java`.

4. Follow the menu instructions.

---

## 📸 Sample Output

```
===== BANK MENU =====

1. Create Account
2. Deposit
3. Withdraw
4. View Balance
5. Display Account Details
6. Exit

Enter Choice : 1

Enter Customer ID : 101
Enter Customer Name : John
Enter Phone Number : 9876543210
Enter Address : Pune

Enter Account Number : ACC101
Enter Initial Balance : 5000

1. Savings Account
2. Current Account

Choose Account Type : 1

Account Created Successfully.
```

---

## 🎯 Learning Outcomes

This project helped in understanding:

- Object-Oriented Programming
- Java Inheritance
- Runtime Polymorphism
- Abstract Classes
- Encapsulation
- Java Collections
- Menu-driven Console Applications

---

## 📄 Author

**Sakshi Parmar**

Java Backend Developer | MCA Graduate

