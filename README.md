# Library Management System

This C++ program provides a solution for managing a library, including books, employees, and readers.

## Functionalities

* **Book Management:**
  * Adding new books to the database
  * Viewing the complete list of books
  * Deleting existing books

* **Employee Management:**
  * Adding new employees
  * Viewing the list of employees
  * Deleting employee information

* **Reader Management:**
  * Adding new readers
  * Viewing the list of readers
  * Deleting reader data
  * Lending books to readers
  * Returning books by readers

* **Report Generation:**
  * Displaying a report of currently borrowed books


## How to Use

1. **Compile:** Compile the C++ source code using a suitable compiler.

2. **Execute:** Run the generated executable file.

3. **Interaction:**

   * The program will display a menu with options.

   * Enter the number corresponding to the desired option and press Enter.

   * Follow the displayed instructions to perform the selected operation.

4. **Exit:** Select the "0. Exit" option from the main menu to close the program. Data will be saved automatically.

## Data Storage

The program uses text files to store data:

* `books.txt`: Contains information about books (ID, title, author, number of available copies).

* `employees.txt`: Contains information about employees (ID, name, position).

* `readers.txt`: Contains information about readers (ID, name, borrowed books).
