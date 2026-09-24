# Bank Management System in C

## Project Overview

The Bank Management System is a simple console-based application developed using the C programming language. It allows users to perform basic banking operations such as creating an account, displaying account details, depositing money, withdrawing money, and checking the account balance.

This project is developed as part of the **CodeAlpha C Programming Internship Tasks**.

## Features

* Create a new bank account
* Display account details
* Deposit money
* Withdraw money
* Check account balance
* Menu-driven interface
* Basic input validation
* Simple and beginner-friendly implementation

## Technologies Used

* **Programming Language:** C
* **IDE:** Visual Studio Code
* **Compiler:** GCC

## Project Structure

```text
Bank-Management-System-C/
│
├── bank_management.c
└── README.md
```

## How to Run

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/Bank-Management-System-C.git
```

### Step 2: Open the Project

Open the project folder in **Visual Studio Code**.

### Step 3: Compile the Program

```bash
gcc bank_management.c -o bank
```

### Step 4: Run the Program

On Windows:

```bash
bank
```

Or:

```bash
.\bank.exe
```

## Menu Options

```text
1. Create Account
2. Display Account
3. Deposit Money
4. Withdraw Money
5. Check Balance
6. Exit
```

## Sample Output

```text
===== BANK MANAGEMENT SYSTEM =====
1. Create Account
2. Display Account
3. Deposit Money
4. Withdraw Money
5. Check Balance
6. Exit

Enter your choice: 1

Enter Account Number: 1001
Enter Account Holder Name: Hemalatha
Enter Initial Deposit: 5000

Account created successfully!
```

### Deposit Example

```text
Enter your choice: 3

Enter Account Number: 1001
Enter Deposit Amount: 2000

Amount deposited successfully!
New Balance: 7000.00
```

### Withdrawal Example

```text
Enter your choice: 4

Enter Account Number: 1001
Enter Withdrawal Amount: 1500

Amount withdrawn successfully!
Remaining Balance: 5500.00
```

## Learning Outcomes

Through this project, I learned:

* Structures in C
* Functions
* Arrays
* Conditional statements
* Switch-case
* Loops
* Searching account records
* Basic input validation
* Menu-driven programming

## Future Improvements

The project can be improved by adding:

* File handling for permanent data storage
* Multiple user authentication
* Account deletion
* Account modification
* Transaction history
* PIN/password protection

## Author

**GAVINI  NIHARIKA**

B.Tech – Electronics and Communication Engineering (ECE)

## License

This project is created for educational and internship purposes.
