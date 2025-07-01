# Elevate Labs Internship

## Tack 5: 💳 Java Bank Simulation Project

A simple Java-based banking application that simulates real-world bank account operations like **depositing**, **withdrawing**, viewing **balance**, and viewing **transaction history**, using Object-Oriented Programming (OOP) principles.

---

## 🛠️ Tools & Technologies

- **Java**
- **Visual Studio Code**
- **Terminal / Command Line**
- **Java Extension Pack** (VS Code)

---

## 📁 Folder Structure

BANK ACCOUNT SIMULATION/
├── src/
│ ├── Account.java # Bank account class (OOP logic)
│ └── BankApp.java # Main class with the user interface
├── bin/ # Compiled Java bytecode (auto-generated)
├── lib/ # (Optional) external libraries
└── .vscode/ # VS Code settings

---

## 🚀 How to Run

### 🔧 Step 1: Compile the Program

Open terminal at the root of the project:

````bash
javac -d bin src/*.java

▶️ Step 2: Run the Program

    java -cp bin BankApp

🧠 Features
    Create a new bank account with an initial deposit
    Deposit money into the account
    Withdraw money (with balance checks)
    View current account balance
    Display full transaction history with timestamps

🧱 Classes Overview
    Account.java
    Handles all account-related operations:
        deposit(double amount)
        withdraw(double amount)
        getBalance()
        printTransactionHistory()

    BankApp.java
        The main program that:
            Takes user input
            Allows operations via a simple CLI menu
            Interacts with Account class

🧪 Sample Output
``` java
    Welcome to Simple Bank App!
    Enter your name: Alice
    Enter account number: 123456
    Enter initial deposit amount: 1000

    Choose an option:
    1. Deposit
    2. Withdraw
    3. View Balance
    4. View Transaction History
    0. Exit
    Your choice: 1
    Enter deposit amount: 200
    Deposited $200.0 successfully.
````
