
Banking App with Tkinter GUI
This Python application provides a simple banking interface using Tkinter, allowing users to create accounts, deposit funds, withdraw funds, and check their account balances.

Features
Create Account: Users can create multiple accounts by providing their name, a unique account number, and an initial balance. The application ensures that each account number is unique, preventing duplication.

Deposit Funds: Account holders can deposit funds into their existing accounts. The application prompts users to enter their account number and the amount they wish to deposit. Deposited amounts contribute to the account balance.

Withdraw Funds: Users can withdraw funds from their accounts, provided the withdrawal amount is valid and within the account’s current balance. Users need to enter their account number and the desired withdrawal amount.

Check Account Balance: Users can check their account balance without performing any transactions. By entering their account number, users receive information about the account holder’s name and the current balance.

Error Handling: The application incorporates basic error handling to address scenarios where users might provide invalid inputs or attempt transactions that exceed their account balances. Users receive appropriate warnings and messages to guide them through valid interactions.

Usage
Run the Python script banking_app.py.

The GUI window will open, displaying buttons for various banking actions.

Click on the respective buttons to perform actions like creating an account, depositing funds, withdrawing funds, or checking the account balance.

Follow the prompts and input dialogs to provide necessary information such as account holder's name, account number, initial balance, deposit amount, or withdrawal amount.

Error messages and warnings will be displayed in message boxes if any invalid inputs or transactions are attempted.

Dependencies
Python 3.x
Tkinter (usually included in Python installations)
