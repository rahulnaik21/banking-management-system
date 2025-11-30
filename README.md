Bank Management System (C++ Project)
📌 Overview

This is a console-based Bank Management System written in C++.
It allows users to create accounts, deposit & withdraw money, check balance, close accounts, and view all saved accounts.

All account data is stored in a file (Bank.data) using file handling and retrieved when the program runs again.

✨ Features

Create a new bank account

Deposit money

Withdraw money (with minimum balance check)

Balance enquiry

Close account

Display all accounts

Persistent storage using file handling

🛠 Technologies Used

C++

OOP Concepts (Classes, Objects)

STL (map)

File Handling (ifstream, ofstream)

📁 File Structure
│── main.cpp          # Main program (your code)
│── Bank.data         # Auto-generated file storing account data
│── README.md         # Project documentation

▶️ How to Run

Compile the code

g++ main.cpp -o bank


Run the executable

./bank


The program will create/update Bank.data automatically.

🧰 Classes Used
✔ Account Class

Handles:

Account creation

Deposit

Withdraw

File input/output overloading

Minimum balance check

✔ Bank Class

Manages:

All accounts using map<long, Account>

File loading & saving

Operations: open, deposit, withdraw, close, list

🔒 Minimum Balance Rule

A user cannot withdraw money if balance falls below ₹500.
If attempted, InsufficientFunds exception is thrown.

📜 Sample Menu
1. Open Account
2. Balance Enquiry
3. Deposit
4. Withdraw
5. Close Account
6. Show All Accounts
7. Quit

📦 Data Persistence

All accounts are saved automatically in Bank.data, ensuring:

Data is not lost after program exit

Account numbers increment correctly

🚀 Future Improvements

You may add:

Login/Password system

Interest & loan system

Transaction history

Better file format (JSON/CSV)

GUI version

👨‍💻 Author

Your Name
Rahul Naik S
