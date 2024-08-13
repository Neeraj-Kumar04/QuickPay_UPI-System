# QuickPay_UPI-System

### UPI Payment Gateway System in C

### Overview
This project is a simple UPI (Unified Payments Interface) Payment Gateway system implemented in C. The application simulates basic payment functionalities commonly found in UPI-based payment platforms. It allows users to perform transactions through various modes, including scanning QR codes, mobile/contact payments, UPI Lite payments, and direct bank account transfers.

### Features
- **Scan & Pay**: Simulates the scanning of a QR code for payment.
- **To Mobile/Contact**: Allows payments to be made by entering a mobile number or contact.
- **UPI Lite**: Facilitates payments using a UPI ID.
- **To Bank Account**: Enables users to transfer money directly to a bank account using account number and IFSC code.
- **PIN Validation**: Ensures secure transactions by requiring UPI PIN entry.
- **Balance Check**: Automatically checks for sufficient balance before processing the transaction.

### How It Works
1. The user is presented with a menu to select the payment mode.
2. Depending on the chosen mode, the user enters the required details (QR code, mobile number, UPI ID, or bank account details).
3. The user inputs the transaction amount and their UPI PIN.
4. The application checks the entered PIN against a predefined PIN and verifies if there is sufficient balance.
5. If the validation is successful, the transaction is processed, and the remaining balance is displayed. If not, appropriate error messages are shown.

### Code Structure
- **Main Function**: Controls the flow of the application, displaying menus, capturing user input, and processing transactions.
- **Transaction Processing**: Handles the validation of the UPI PIN, checks the balance, and executes the transaction.
- **Input Handling**: Captures the details needed for each type of transaction based on the user's choice.

### OUTPUT VIDEO 📽

https://github.com/user-attachments/assets/ed3a90f4-d365-4ced-a2ed-c25662e5e8f7



