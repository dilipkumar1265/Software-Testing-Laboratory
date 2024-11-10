# Ex.No: 8  ATM Applicationn
### DATE: 1-10-24                                                                          
### REGISTER NUMBER : 212222040037
### AIM: 
For ATM system study its system specifications and report various bugs

### Purpose:
The purpose of this study is to analyze the ATM system software requirements, understand its functionalities, and report potential issues that may impact user experience, functionality, or security.

### Scope:
The scope of this study includes identifying specifications for core ATM functions such as user authentication, cash withdrawal, deposit, balance inquiry, and transaction history review. It also covers usability, security, and operational constraints.

### Intended Audience:
This document is intended for software developers, system analysts, quality assurance teams, and stakeholders involved in the development and maintenance of ATM systems.

### Product Perspective:
The ATM system serves as a customer-facing interface for banking services. 

It enables users to perform transactions and access bank services without visiting a physical branch. 

The system interacts with the bank’s backend server for validation and processing.

### Product Functions:
The ATM system provides the following primary functions:

User Authentication: Validates user credentials using a PIN or biometric authentication.

Balance Inquiry: Allows users to view their account balance.

Cash Withdrawal: Enables users to withdraw cash from their account.

Cash Deposit: Allows users to deposit cash into their account.

Funds Transfer: Facilitates the transfer of funds between accounts.

Transaction History: Displays a summary of recent transactions.

Account Settings: Provides options for PIN change, mobile number update, etc.

### Operative Environments:
The ATM application is designed to operate in the following environments:

Operating Systems: Windows or Linux-based operating systems typically used in ATMs.

Hardware: ATMs with card readers, PIN pads, cash dispensers, deposit modules, and display screens.

Network: Secure network connectivity for communication with bank servers.

### Design/implementation constraints:

Limited screen size and user input options on ATMs.

Real-time processing requirements to ensure fast transaction completion.

Robust error handling for hardware failures (e.g., cash dispenser jam).

Compliance with banking standards and security regulations.

### Assumptions and Dependencies: 

The ATM is connected to a stable network for real-time transaction processing.

ATM users have valid bank accounts and bank-issued ATM cards.

All hardware components (e.g., card reader, cash dispenser) function correctly.

### Software interfaces 

User Interface: Touchscreen or physical button interface for user interactions.

Network Interface: Connects with bank servers to process transactions.

Backend System Interface: Retrieves and updates account information.

### Safety requirements: 

The ATM must provide physical security features, such as anti-tampering sensors.

The system should automatically log out after a period of inactivity.

Compliance with safety protocols to protect users from fraud or theft.

### Security requirements: 

Secure PIN encryption during transmission and processing.

End-to-end encryption for all transactions.

The ATM must not display sensitive information like the PIN on the screen.

Protection against unauthorized access and tampering.

### Possible Bugs:

1. Successful insertion of ATM card

2. Unsuccessful operation due to insert card in wrong angle

3. Unsuccessful operation due to invalid account Ex: other bank card or time expired card

4. successful entry of PIN number

5. un successful operation due to enter wrong PIN number 3times 6. successful selection of language

7. successful selection of account type

8. unsuccessful operation due to invalid account type

9. successful selection of withdraw operation

10. successful selection of amount to be withdrawal

11. successful withdraw operation

12. unsuccessful withdraw operation due to wrong denominations

13. unsuccessful withdraw operation due to amount is greater than day limit

14. unsuccessful withdraw operation due to lack of money in ATM

15. unsuccessful withdraw operation due to amount is greater than possible balance

16. unsuccessful withdraw operation due to transactions is greater than day limit

17. unsuccessful withdraw operation due to click cancel after insert card

18. unsuccessful withdraw operation due to click cancel after insert card & pin number

19. unsuccessful withdraw operation due to click cancel after insert card, pin number & language

20. unsuccessful withdraw operation due to click cancel after insert card, pin number, language
&account type

21. unsuccessful withdrawal operation due to click cancel after insert card, pin number, language,
account type & withdrawal operation

22. unsuccessful withdrawal operation due to click cancel after insert card, pin number, language,
account type, withdrawal operation &amount to be withdraw

### Result:
Thus, the ATM system specifications and reporting the various bugs is implemented and output was verified successfully

