Summary of Library Database System Project
This project involves the creation and management of a SQL-based library database system designed to streamline library operations. The database includes several interconnected tables: Branch, Employee, Books, Customer, IssueStatus, and ReturnStatus. Each table has a specific structure with defined primary and foreign key constraints to maintain data integrity.

Key Components:
1) Branch Table: Stores information about library branches, including branch number (primary key), manager ID, address, and contact number.
2) Employee Table: Contains employee details with employee ID (primary key), name, position, salary, and branch number (foreign key referencing Branch table).
3) Books Table: Holds book details such as ISBN (primary key), title, category, rental price, availability status, author, and publisher.
4) Customer Table: Records customer information, including customer ID (primary key), name, address, and registration date.
5) IssueStatus Table: Tracks issued books with issue ID (primary key), customer ID (foreign key referencing Customer table), book name, issue date, and ISBN (foreign key referencing Books table).
6) ReturnStatus Table: Manages returned books with return ID (primary key), customer ID, book name, return date, and ISBN (foreign key referencing Books table).

Key Methods:
a) Data Retrieval: Efficiently fetch data such as available books, employee salaries, book issuance records, and more.
b) Data Manipulation: Insert, update, and delete records in various tables to keep the database current.
c) Data Aggregation: Summarize data such as the count of books in each category or the number of employees in each branch.

Example SQL Queries:
a) Retrieve available books: Get the titles, categories, and rental prices of all books currently available for rent.
b) List employee salaries: Display employee names and salaries in descending order.
c) Issued books and customers: Fetch the titles of books issued along with the corresponding customer names.

This project provides a robust foundation for managing a library's data and operations, ensuring efficient tracking of books, employees, and customers. It includes SQL scripts for setting up the database, creating tables, and performing common queries, making it a valuable resource for library management and data analysis.






