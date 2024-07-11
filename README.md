# Bankist

Bankist is a simple banking application designed to simulate basic banking functionalities. It allows users to log in, view their account balance, make transfers, request loans, and close their accounts. This README provides an overview of the project structure, important functions, and their usage.

## Project Structure

The Bankist project consists of three main files:

1. **HTML File**: Contains the structure and layout of the banking application user interface.
2. **CSS File**: Provides styling for the HTML elements to create a visually appealing interface.
3. **JavaScript File (script.js)**: Implements the functionality of the banking application, including user authentication, account operations, and UI updates.

## Key Functions and Usage

### User Authentication
- **Function**: `btnLogin.addEventListener('click', function (e) { ... })`
- **Usage**: Handles user login functionality. Verifies the entered username and PIN against the account data and displays the user's dashboard upon successful login.

### Display Movements
- **Function**: `displayMovements(acc, sort = false) { ... }`
- **Usage**: Renders the account movements (deposits and withdrawals) in the UI. Optionally sorts the movements if specified.

### Transfer Money
- **Function**: `btnTransfer.addEventListener('click', function (e) { ... })`
- **Usage**: Allows the user to transfer money to another account. Validates the transfer amount and recipient account, updates account balances, and logs the transaction.

### Request Loan
- **Function**: `btnLoan.addEventListener('click', function (e) { ... })`
- **Usage**: Enables users to request a loan from the bank. Validates the loan amount and user's eligibility based on their transaction history. If approved, adds the loan amount to the user's account.

### Close Account
- **Function**: `btnClose.addEventListener('click', function (e) { ... })`
- **Usage**: Allows users to close their bank accounts. Requires confirmation of username and PIN, deletes the account data from the system, and hides the user interface.

### Sort Movements
- **Function**: `btnSort.addEventListener('click', function (e) { ... })`
- **Usage**: Allows users to sort their transaction movements in ascending or descending order based on the transaction amount.

### Update UI
- **Function**: `updateUI(acc) { ... }`
- **Usage**: Updates the user interface with the latest account details, including balance, transaction history, and summary information.

### Logout Timer
- **Function**: `startLogOutTimer() { ... }`
- **Usage**: Initiates a timer to automatically log out the user after a certain period of inactivity. Displays a countdown timer in the UI and logs out the user when the time expires.

## Conclusion

Bankist provides a comprehensive yet simplified banking experience, allowing users to perform essential banking operations seamlessly. With its intuitive user interface and robust functionality, it serves as an effective tool for understanding banking concepts and practicing financial transactions.

## Note 
Payment Gateway integration and the backend part is yet too come in this project with some more functionalities.
Stay Tuned..........
