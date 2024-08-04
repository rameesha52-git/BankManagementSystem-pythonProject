# BankManagementSystem-pythonProject
This project is a simple Bank Management System implemented using Python and the Tkinter library for the graphical user interface (GUI). The application provides fundamental banking functionalities such as account creation, account login, amount depositing, amount withdrawal, and balance checking.

## Features
+ Account Creation and User Login
+ Deposit and Withdrawal
+ Balance Inquiry
+ Transaction history
+ Logout

## Requirements
+ Python 3.x
+ Tkinter library (which is usually included with Python)

## Code Structure
The code is organized into the following functions:

+ __init__(self, master) : This function initializes the BankSystem object with the specified parameters, sets the title and geometry of the main window, and creates the "Create Account" and "Login" frames.
+ create_account() : This function creates a new account with the name, age, salary, and PIN entered by the user in the corresponding Entry widgets.
+ login() : This function validates the entered PIN against the saved account details and displays the account information if the PIN is correct.
+ deposit() : This function allows the user to deposit money into their bank account and updates the balance accordingly.
+ withdraw() : This function allows the user to withdraw money from their bank account, if the balance is sufficient, and updates the balance accordingly.
+ view_transaction() : This function allows the user to view their transaction history for the current session.

 ## Conclusion
This project demonstrates the implementation of a basic Bank Management System using Python and Tkinter. It covers essential banking operations while providing a graphical user interface for easy interaction. The application is designed to be intuitive and user-friendly, making it a suitable foundation for more complex banking systems.

