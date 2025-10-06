ATM System in Java --- PITP 2 --- Project --- 2/Octobe/2025 --- Thursday

Introduction

An ATM (Automated Teller Machine) System is a self-service machine that allows customers to perform financial transactions without the need for a human teller. This system is typically used for activities such as withdrawing money, checking account balance, and transferring funds between accounts. The ATM system described here is a basic console-based implementation in Java, designed to simulate the main operations of an ATM.

Features

User authentication (PIN entry)

Balance inquiry

Withdraw cash

Deposit funds

Transfer funds

Account details

Classes and Structure
1. ATMSystem.java

This is the main class that acts as the entry point of the system, allowing the user to interact with the ATM. The main operations like authentication and interaction with other components (e.g., Account, Transaction) are handled here.

2. Account.java

The Account class holds the details of the user’s account, including the account number, PIN, balance, and transaction history. Methods in this class manage balance checking, depositing funds, withdrawing funds, etc.

3. Transaction.java

This class manages the transaction history of an account, such as deposits, withdrawals, and transfers. It allows recording of the transaction type, amount, and timestamp.

4. ATMTransaction.java

Handles individual ATM operations, such as withdrawal and deposit processing, including checks for sufficient balance, PIN validation, etc.




