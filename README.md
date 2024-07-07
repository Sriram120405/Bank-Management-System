Overview
This is a simple Customer Account Banking Management System written in C. It allows the user to create new accounts, update existing account information, perform transactions, check account details, delete accounts, and view the list of all customers. The system ensures security with a password-protected login.

Features
Create New Account: Allows the creation of a new bank account.
Update Account Information: Update the address or phone number of an existing account.
Transactions: Perform deposit and withdrawal transactions.
Check Account Details: View detailed information about an account.
Delete Account: Remove an existing account from the system.
View Customer List: Display a list of all customers.
Files
main.c: The main source code file containing all the functions and logic of the banking system.
record.dat: The file where all the account records are stored.
Functions
new_acc(): Function to create a new account.
view_list(): Function to view the list of all customers.
edit(): Function to edit the details of an existing account.
transact(): Function to perform deposit and withdrawal transactions.
erase(): Function to delete an account.
see(): Function to check the details of an existing account.
close(): Function to exit the system.
menu(): Function to display the main menu and navigate to different options.
main(): The main function that handles the login and initializes the system.
Usage
Login: On running the program, the user is prompted to enter a password. The default password is IITBBS.
Main Menu: After successful login, the main menu is displayed with the following options:
Create new account
Update information of existing account
For transactions
Check the details of existing account
Removing existing account
View customer's list
Exit
Create New Account: Follow the prompts to enter account details.
Update Account Information: Enter the account number and choose to update either the address or phone number.
Transactions: Choose to either deposit or withdraw money by entering the account number and amount.
Check Account Details: Enter the account number or name to view detailed account information.
Delete Account: Enter the account number of the account to be deleted.
View Customer List: Displays a list of all customers with their account numbers, names, addresses, and phone numbers.
Exit: Exit the system.
Requirements
C Compiler (e.g., GCC)
Windows Operating System (for windows.h dependency)
