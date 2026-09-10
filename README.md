# Bank Management System
Demo link : https://drive.google.com/file/d/1AfEcVp9-tM8L70HZOlNLB4gMbyitqCct/view?usp=sharing
## Overview

The **Bank Management System** is a Java-based desktop application designed to simulate basic banking operations with a graphical user interface (GUI). It allows users to create accounts, log in, and perform various banking transactions such as deposits, withdrawals, balance inquiries, and more.

## Features

- **User Authentication:** Signup and login functionality for new and existing users.
- **Account Management:** Create and manage bank accounts.
- **Transactions:** Deposit, withdraw, and check account balance.
- **Mini Statement:** View recent transactions.
- **PIN Management:** Change or reset account PIN.
- **Fast Cash:** Quick withdrawal options.
- **Date Selection:** Uses the JCalendar library for date picking in forms.

## Technology Stack

- **Language:** Java (Desktop Application)
- **GUI:** Java Swing
- **External Library:** [JCalendar](https://toedter.com/jcalendar/) (`com.toedter.calendar.JDateChooser`)

## Project Structure

```
bank managment system/
├── bank/
│   └── management/
│       └── system/
│           ├── BalanceEnquriy.java
│           ├── Con1.java
│           ├── Deposit.java
│           ├── Fastcash.java
│           ├── JDateChooser.java
│           ├── Mini.java
│           ├── Pin.java
│           ├── Signup.java
│           ├── Signup2.java
│           ├── Signup3.java
│           ├── Withdrawl.java
│           ├── login.java
│           └── main_Class.java
└── lib/
    └── jcalendar-x.x.jar
```

## How to Run

1. **Requirements:**
   - Java JDK (8 or above)
   - JCalendar library (`jcalendar-x.x.jar`)

2. **Compilation:**
   ```sh
   javac -cp ".;lib\\jcalendar-x.x.jar" bank\\management\\system\\*.java
   ```

3. **Manifest File:**  
   Create a file named `manifest.txt` with:
   ```
   Main-Class: bank.management.system.main_Class
   ```

4. **Packaging:**
   ```sh
   jar cfm BankManagementSystem.jar manifest.txt bank\\management\\system\\*.class
   ```

5. **Running:**
   ```sh
   java -cp "BankManagementSystem.jar;lib\\jcalendar-x.x.jar" bank.management.system.main_Class
   ```

## Notes

- The application is intended for educational and demonstration purposes.
- Ensure the `lib` directory with the JCalendar JAR is present for the application to function correctly.
- All data is handled in-memory unless additional database integration is implemented.
- GUI Of The Project :
- Home Page
  ![Screenshot 2024-09-13 203116](https://github.com/user-attachments/assets/02954fe9-6a38-453a-80ad-7615d958b27e)
  Application form :
  ![Screenshot 2024-09-13 201556](https://github.com/user-attachments/assets/abf1490f-a2aa-4994-ae9b-8c0713129e88)
  ![Screenshot 2024-09-13 201740](https://github.com/user-attachments/assets/fa829306-06a9-4a6d-978f-a001a8fcff7d)
  ![Screenshot 2024-09-13 201858](https://github.com/user-attachments/assets/a2f3c827-83aa-4548-b40f-945a23695e18)
  ATM :
  ![Screenshot 2024-09-13 202156](https://github.com/user-attachments/assets/0d9af248-13d6-45b0-818c-0715f3bf75a0)
  Equiry Details :
  ![Screenshot 2024-09-13 203142](https://github.com/user-attachments/assets/44e6a01e-3dc5-4aca-b2c5-cf0191de7327)



  

  


