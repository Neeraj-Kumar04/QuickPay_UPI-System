# QuickPay UPI System

### UPI Payment Gateway System in C

## Overview
Welcome to the **QuickPay UPI System**! This project is a straightforward UPI (Unified Payments Interface) Payment Gateway implemented in C. The application simulates essential payment functionalities found in modern UPI-based platforms, enabling users to perform transactions through various modes, including:

- Scanning QR codes
- Mobile/contact payments
- UPI Lite payments
- Direct bank account transfers

## Features
- **🖼️ Scan & Pay**: Simulates the scanning of a QR code for quick payments.
- **📱 Mobile/Contact Payments**: Allows payments to be made by entering a mobile number or contact.
- **🔗 UPI Lite**: Facilitates payments using a UPI ID for streamlined transactions.
- **🏦 Direct Bank Transfers**: Enables users to transfer money directly to a bank account using account number and IFSC code.
- **🔒 PIN Validation**: Ensures secure transactions by requiring UPI PIN entry.
- **💳 Balance Check**: Automatically verifies sufficient balance before processing the transaction.

## How It Works
1. **Menu Selection**: The user is presented with a menu to select the desired payment mode.
2. **Input Details**: Depending on the chosen mode, users enter the required information (QR code, mobile number, UPI ID, or bank account details).
3. **Transaction Amount**: The user inputs the transaction amount along with their UPI PIN.
4. **Validation**: The application checks the entered PIN against a predefined PIN and verifies if there is sufficient balance.
5. **Transaction Processing**: If validation is successful, the transaction is processed, and the remaining balance is displayed. If not, appropriate error messages are shown.

## Code Structure
- **Main Function**: Controls the flow of the application, displaying menus, capturing user input, and processing transactions.
- **Transaction Processing**: Manages UPI PIN validation, balance checks, and execution of transactions.
- **Input Handling**: Captures the details needed for each type of transaction based on the user's choice.


### OUTPUT VIDEO 📽

https://github.com/user-attachments/assets/ed3a90f4-d365-4ced-a2ed-c25662e5e8f7



