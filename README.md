
Java Library Management System

This is a *Java-based Library Management System* built for the command line. It supports basic functionality for both *Admins* and *Users*, such as book management, user login, borrowing/returning books, and more.

---

##  Features

###  User Authentication
- Admin and User login system
- User registration with unique ID generation

###  Book Management
- Admin can add and delete books
- Both Admin and Users can view all books
- Search books by title (case-insensitive)

###  Borrowing System
- Users can borrow available books
- Users can return previously borrowed books
- View personal list of borrowed books

---

##  Technologies Used

- *Java (Core)*
- *Object-Oriented Programming (OOP)*
- *Scanner (for CLI input)*
- *Collections (ArrayList)*

---

## How to Run

1. Open the project in any Java IDE (e.g. IntelliJ, Eclipse) or terminal.
2. Make sure all .java files are in the correct package/folder.
3. Compile and run MainApp.java.
4. Use the menu to log in, register, or manage the library.

---
Project Structure


├── MainApp.java             # Main class with login,  menu, and execution logic


├── model                   # Package for data models
 
├── Book.java                 # Book class with details like title, author, copies
  
└── User.java                 # User class for admin/user with borrowing features


├── manager                      # Package for core functionality
   
   ├── LibraryManager.java       # Manages books, users, borrow/return system
  
   └── LoginManager.java         # Handles user authentication

---
