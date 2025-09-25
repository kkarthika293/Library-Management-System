# Library Management System

## Overview
The Library Management System is a Python-based application designed to automate and streamline the management of library operations. This system handles the management of books, borrowers, and transactions, aiming to improve the efficiency of the library's day-to-day processes.

## Features
- **Book Management**: Add, search, and remove books from the library’s collection.
- **Borrower Management**: Register borrowers, track their borrowing history, and maintain records of overdue books and fines.
- **Transaction Handling**: Facilitate book checkouts and returns, along with fine calculation for overdue books.
- **File Storage**: Books, borrowers, and transaction details are stored in text files for persistent data storage.

## Technologies Used
- **Python**: The main programming language used to develop the system.
- **Object-Oriented Programming (OOP)**: Utilized OOP principles to structure the system, with classes for books, borrowers, and transactions.
- **File Handling**: Python’s file handling capabilities were used to store data persistently across sessions.

## How It Works
1. **Book Operations**: Admins can add new books, search for existing books by title or author, and delete books from the system when they are no longer available.
2. **Borrower Operations**: Borrowers can be registered, and the system tracks the books they borrow, along with their due dates. If a book is returned late, a fine is calculated.
3. **Transaction Management**: When a book is borrowed, the transaction is logged, and when it is returned, the return is recorded, along with any overdue fines if applicable.

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/library-management-system.git
   ```
2. Navigate to the project directory:
   ```
   cd library-management-system
   ```
3. Run the program:
   ```
   python library_management_system.py
   ```

## Future Enhancements
- Implement a user interface (UI) for easier interaction.
- Introduce a database system (e.g., SQLite) for better data management and scalability.
- Allow online book reservations and renewals.

---
