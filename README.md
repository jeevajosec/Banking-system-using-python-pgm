# Banking-system-using-python-pgm
Banking-System-in-Python
Banking System This repository contains a simple banking system implemented in Python. The system allows users to manage their bank accounts, including functionalities for deposits, withdrawals, and checking account balances. The banking system simulates a real-world banking environment while demonstrating object-oriented programming principles. Features Account Management: Each bank account is represented as an instance of the BankAccount class, which holds account details such as name, account number, PIN, and balance.

Transaction Fees and Bonuses:

A transaction fee of 0.015% is applied to all withdrawals. A bonus of 0.01% is awarded for each deposit. Authentication: Users must authenticate using their account number and PIN before accessing their accounts.

Deposit Functionality: Users can deposit funds into their accounts. The deposited amount plus any applicable bonus is added to the account balance.

Withdrawal Functionality: Users can withdraw funds from their accounts, with the transaction fee deducted from the account balance. The system checks for sufficient funds before processing a withdrawal.

User Interaction: The program prompts the user to input their account number and PIN, provides options for deposits or withdrawals, and displays account balance information.

Code Structure Class: BankAccount init(self, name, account_number, pin, balance=0): Initializes a new bank account with a name, account number, PIN, and optional balance.

get_balance(self): Returns the current account balance.

get_transaction_fee(self, amount): Calculates and returns the transaction fee for a specified withdrawal amount.

get_transaction_bonus(self, amount): Calculates and returns the transaction bonus for a specified deposit amount.

deposit(self, amount): Processes a deposit, applying the bonus to the account balance.

withdraw(self, amount): Processes a withdrawal, deducting the transaction fee from the account balance.

Function: authenticate(account_number, pin) Authenticates the user based on the provided account number and PIN. Returns the associated BankAccount object if the credentials are valid; otherwise, returns None.
