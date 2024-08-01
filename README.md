# DSA Bank Project

## General Info
This project simulates a real-life banking system with two operational modes: BANKING Mode and ATM Mode. The solution is designed using C++ and utilizes the Standard Template Library (STL) extensively.

### BANKING Mode
In this mode, you can perform various banking operations. Use the following commands:

| Command | Description                   |
|---------|-------------------------------|
| S       | Open bank                     |
| O       | Open an account               |
| B       | Balance enquiry               |
| W       | Withdrawal                    |
| D       | Deposit                       |
| C       | Close account                 |
| A       | Activate ATM                  |
| U       | Unlock ATM                    |
| P       | Print all accounts            |
| I       | Apply interest to all accounts|
| E       | Exit and close all accounts   |

### ATM Mode
In this mode, you can perform ATM-specific operations. Use the following commands:

| Command | Description                   |
|---------|-------------------------------|
| X       | PIN change                    |
| F       | Fund transfer                 |
| B       | Balance enquiry               |
| W       | Withdrawal                    |
| M       | Mini statement                |

### Persistence
The application saves data from previous executions and can load all information on the next execution to ensure continuity and data integrity.

## Technologies
The project uses the following technologies:
- C++
- GNU Make

## Setup

### Clone the Project
To get started, clone the project repository:
```sh
git clone https://github.com/Vishwa-0502/Bank_Management_System
```

### Run the Project
Navigate to the `src` directory and run the following commands to compile and execute the program:
```sh
cd Bank_Management_System
make run
```
Alternatively, you can compile and run the executable as follows:
```sh
cd Bank_Management_System
make
./a.out
```

### Prerequisites
Ensure you have `g++` and `make` installed on your system. You can install these using:
```sh
# For Ubuntu/Debian
sudo apt-get update
sudo apt-get install build-essential

## Features
- **BANKING Mode**: Manage bank operations such as account creation, balance enquiries, withdrawals, deposits, and more.
- **ATM Mode**: Manage ATM operations such as PIN changes, fund transfers, balance enquiries, withdrawals, and mini statements.
- **Data Persistence**: Saves data between sessions for seamless operation.

Feel free to explore and enhance the project by contributing to the repository!

## License
This project is licensed under the MIT License - see the LICENSE file for details.

---

This README provides a clear and detailed guide to understanding and setting up the DSA Bank project, ensuring ease of use for users and contributors.
