# Banking-System
This is a simple banking system implemented in C++ by using concepts of Object Oriented Programming. It allows users to perform various banking operations such as opening an account, checking balance, making deposits, withdrawing funds, closing an account, and displaying all accounts.

# Usage
Once the program is running, follow the on-screen prompts to interact with the banking system. Here are the available options:

1.Open an Account: Enter the customer's first name, last name, and initial balance to create a new account.
2.Balance Enquiry: Enter an account number to check the balance of the corresponding account.
3.Deposit: Enter an account number and the amount to deposit funds into the account.
4.Withdrawal: Enter an account number and the amount to withdraw funds from the account.
5.Close an Account: Enter an account number to close the account.
6.Show All Accounts: Display details of all the existing accounts.
7.Quit: Exit the program.

# Skills Used

1.C++ Programming: The entire code is written in C++, utilizing various features and concepts of the language.

2.Object-Oriented Programming (OOP): The code follows the principles of OOP by using classes and objects to encapsulate data and functionality.

3.File Input/Output: The code utilizes file input/output operations to store and retrieve account information from a file ("Bank.data").

4.Data Structures: The map container from the C++ Standard Template Library (STL) is used to store and manage bank accounts, allowing efficient access and modification of account data.

5.Exception Handling: The code demonstrates the use of exception handling to handle the InsufficientFunds exception when attempting to withdraw more funds than the account balance allows.

6.Input/Output Streams: The code uses input/output streams (cin, cout, ifstream, ofstream) to interact with the user and read/write data from/to files.

7.Control Flow: The code employs control flow constructs such as loops (do-while, while) and conditional statements (if-else, switch-case) to implement the menu-based user interface and control program execution.

8.Friend Functions: The code defines friend functions for the Account class to allow input/output stream operators (<< and >>) to access private member variables.

9.Header Files: The code includes various header files (iostream, fstream, cstdlib, vector, map) to import required libraries and use their functionalities.
