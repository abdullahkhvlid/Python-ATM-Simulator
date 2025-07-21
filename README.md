ATM Simulation – Python CLI Application

This is a command-line based ATM simulation script written in Python. It allows a user to interact with a virtual bank account and perform basic banking operations such as balance inquiry, withdrawal, and deposit. 

The script uses simple conditionals, user input handling, and error checking to simulate an ATM environment for learning purposes.

Project Objective

The purpose of this project is to practice:

- Python input/output operations
- Control flow using conditionals
- Exception handling (try/except)
- Basic arithmetic operations
- String manipulation and data masking

Features

1. Account holder name input (with name masking for privacy)
2. Hardcoded initial balance set at 12,000
3. Options menu with the following functionality:
   - Balance inquiry
   - Withdraw money
   - Deposit money
   - Exit
4. Input validation with exception handling for invalid data types

Code Overview

- `user[:3] + "******"` masks the account holder's name for simulated privacy.
- `try/except` block ensures that non-integer inputs do not crash the program.
- The program maintains a simple, single-user session with a hardcoded balance.

Sample Interaction

Input:
    enter your name: Ali

Menu:
    1. Balance Inquiry
    2. Withdraw Money
    3. Deposit Money
    4. Exit

User selects:
    Enter Option: 3
    enter your deposit amount: 300

Output:
    amount deposited, your account balance is: 12300

File Structure

atm_simulation.py

Limitations

- No database or persistent storage is used.
- No account authentication (username/password).
- Single-user simulation with hardcoded initial balance.
- Designed for educational purposes only.

Requirements

- Python 3.x

To Run

Use any Python environment or terminal:

    python atm_simulation.py



