

# Banking System

A simple C++ console application for a basic banking system that allows users to sign up, sign in, deposit, withdraw funds, and check their balance. This project demonstrates file handling, class usage, and basic C++ concepts.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Sign Up**: Create a new account by providing personal details.
- **Sign In**: Log in to an existing account using a name and password.
- **Deposit**: Add funds to the account.
- **Withdraw**: Remove funds from the account.
- **Balance Inquiry**: Check the current balance.
- **Multiple Account Types**: Support for various account types including Savings, Checking, Fixed Deposit, Current, and Foreign Currency accounts.

## Getting Started

### Prerequisites

- C++ compiler (e.g., g++, clang++)
- Development environment (e.g., Visual Studio Code, CLion, or a simple text editor)

### Setup

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/your-username/banking-system.git
   cd banking-system
   ```

2. **Build the Application**:

   Compile the source code using a C++ compiler:

   ```bash
   g++ main.cpp -o BankingSystem
   ```

3. **Run the Application**:

   Execute the compiled program:

   ```bash
   ./BankingSystem
   ```

## Usage

### Main Menu

- **1. Signup**: Create a new account by providing details such as name, password, CNIC, gender, income, and account type.
- **2. Signin**: Log in using an existing account's name and password.
- **3. Exit**: Close the application.

### Transaction Menu (after signing in)

- **1. Deposit**: Enter an amount to deposit into the account.
- **2. Withdraw**: Enter an amount to withdraw from the account.
- **3. Balance Inquiry**: Display the current balance.
- **4. Logout**: Log out of the account.

## File Structure

- **`main.cpp`**: Source code for the project.
- **`data.txt`**: Stores user information and account details. Each line represents a user record in the format:
  ```
  name,password,cnic,gender,income,account_type,amount
  ```
- **`temp.txt`**: A temporary file used during transactions to update `data.txt`.

## Example Walkthrough

### Sign Up

1. Run the application.
2. Select `1` for Signup.
3. Enter your details as prompted.

### Sign In

1. Run the application.
2. Select `2` for Signin.
3. Enter your name and password.

### Deposit

1. After signing in, select `1` for Deposit.
2. Enter the amount you wish to deposit.

### Withdraw

1. After signing in, select `2` for Withdraw.
2. Enter the amount you wish to withdraw.

### Balance Inquiry

1. After signing in, select `3` for Balance Inquiry.

