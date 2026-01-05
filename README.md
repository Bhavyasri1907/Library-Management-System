# Library Management System
Library Management System is a software application designed to automate and simplify the daily operations of library.It helps manage books , users , and reducing manual work .
This system allows librarians to maintain records of books .
It ensures faster access to library data and improves overall library administration.
## 🔑 Features
- Add , update books records
- manage member details
- Issue status
- Search books by title or author
## 🛠 Technologies Used
- Programming Language : C++/DBMS
- Database : MySQL
## 📊 Database Schema
- The project utilizes a relational database named LibraryDB with two primary tables:
  1. lib Table: Stores name (Primary Key) and quantity.
  2. student Table: Stores unique id (Primary Key) for registration.
## 📸 Screenshots
![a](https://github.com/Bhavyasri1907/Library-Management-System/blob/main/project/Screenshot%202026-01-05%20094124.png)

![c](https://github.com/Bhavyasri1907/Library-Management-System/blob/main/project/Screenshot%202026-01-05%20111511.png)

![b](https://github.com/Bhavyasri1907/Library-Management-System/blob/main/project/Screenshot%202026-01-05%20110857.png)

## ⚙️ How to Run the Project

1. Prerequisites
- Install MySQL Server and MySQL Workbench.
- Install a C++ Compiler (MinGW recommended).
- Download the MySQL Connector/C files (include and lib folders).
2. Database Setup
3. Compiler Configuration
4. Buid and Run file
## 🔮 Future Enhancements
- Book Return Logic: Implement a "Return Book" feature to increment quantity back into the database.
- Due Dates & Fines: Add a date-tracking system to calculate late fees for students.
- Search Functionality: Implement a search feature using LIKE SQL queries to find books by keywords.
- GUI Transition: Migrate from a console-based UI to a graphical interface using Qt or WxWidgets.


