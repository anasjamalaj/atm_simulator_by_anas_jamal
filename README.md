# ATM Machine Simulator

## Description

This project is an ATM machine simulator created in Python. It allows users to perform basic ATM transactions such as checking balance, withdrawing money, depositing money, and exiting the program. The simulator also includes basic error handling for insufficient balance and invalid transactions.

## Features

- Check balance
- Withdraw money
- Deposit money
- Exit

## How to Use

1. Run the `atm_simulator_by_anasjamal.ipynb` file.
2. Enter your PIN when prompted.
3. Select your transaction from the available options:
   - 1: Check balance
   - 2: Withdraw money
   - 3: Deposit money
   - 4: Exit
4. Follow the on-screen instructions to complete your transaction.

## Issues Encountered

### Kernel Died Issue After Entering Option 4

When users entered option 4 to exit the program, the kernel would sometimes die unexpectedly. To resolve this issue, I made the following changes:

### Multiple "No Selected Transaction" Messages

When users entered a number other than 1, 2, 3, or 4, the program displayed the "No Selected Transaction" message multiple times. To resolve this issue, I used a `transaction_completed` variable to track whether a transaction was completed. If no transaction was selected, the message was displayed only once at the end of the transaction processing.
