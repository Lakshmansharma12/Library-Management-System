Here's a **README** file for your Library Management System project:

---

# Library Management System

### Overview

The **Library Management System** is a C++ console-based application designed to automate the process of managing books in a library. It provides functionalities for adding, removing, updating, borrowing, returning, and searching for books. The system keeps track of each book's availability and includes features for sorting books, recommending available books, and displaying a list of borrowed books.
![image](https://github.com/user-attachments/assets/cdc93983-12a7-468b-8125-0a99937d2e95)

### Features

1. **Add Book**: Add new books to the library by providing a unique ID, title, and author.
2. **Remove Book**: Remove books from the library using their unique ID.
3. **Update Book Information**: Update the details of a book (title, author) using its ID.
4. **List All Books**: View the complete list of books along with their availability status.
5. **Borrow Book**: Borrow a book by its ID, marking it as unavailable and recording the borrower's name.
6. **Return Book**: Return a borrowed book by its ID and make it available again.
7. **Search by Title**: Search for a book using its title.
8. **Search by Author**: Search for books by the author's name.
9. **List Borrowed Books**: View a list of all borrowed books along with the borrower's name.
10. **Recommend Book**: Recommend other available books by the same author if the desired book is unavailable.
11. **Sort Books by Title or Author**: Sort the list of books alphabetically by title or by author.

### Project Structure

- **Book Class**: Represents individual books, with attributes such as ID, title, author, and availability status.
- **Library Class**: Manages a collection of books and provides all the functionalities (add, remove, borrow, return, search, etc.).
- **Main Function**: Provides a user interface for interacting with the library system through a menu-driven approach.

### How to Use

1. **Add a Book**: Enter the book ID, title, and author. Ensure that no two books share the same ID.
2. **Remove a Book**: Specify the ID of the book to be removed.
3. **Update Book Information**: Use the book's ID to update its title or author.
4. **Borrow a Book**: Enter the book's ID to borrow it. The system will mark it as unavailable and record your name.
5. **Return a Book**: Use the book's ID to return it. The system will mark it as available.
6. **Search**: Use either the title or the author to search for a book.
7. **Sort**: Choose to sort books by either title or author for easier browsing.
8. **Recommendations**: If a book is unavailable, the system will recommend another available book by the same author.

### System Requirements

- **C++ Compiler**: You need a C++ compiler such as `g++` to compile and run this program.

### Compilation and Execution

To compile and run the program, use the following commands in the terminal:

```bash
g++ library_management.cpp -o library_management
./library_management
```

### Flowchart

```plaintext
+-----------------------------------+
|        Library Management         |
+-----------------------------------+
| 1. Add Book                       |
| 2. Remove Book                    |
| 3. Update Book Information        |
| 4. List All Books                 |
| 5. Borrow Book                    |
| 6. Return Book                    |
| 7. Search Book by Title           |
| 8. Search Book by Author          |
| 9. List Borrowed Books            |
| 10. Recommend Book                |
| 11. Sort Books by Title/Author    |
| 12. Exit                          |
+-----------------------------------+
         User Input (Choice)
                |
                v
     +-------------------------------+
     |   Selected Operation           |
     +-------------------------------+
                |
                v
      +---------------------------+
      |  Perform Action / Update   |
      +---------------------------+
                |
                v
       +-----------------------+
       |  Display Result / Menu |
       +-----------------------+
```

### Future Scope

- **User Management**: Implement a system for user registration and login to manage borrowing histories.
- **Genre-based Search**: Allow searching and categorization of books by genre.
- **Due Dates & Penalties**: Implement a system for managing due dates for borrowed books and tracking late fees.
- **Graphical User Interface (GUI)**: Upgrade the system to a GUI-based application for easier usage and a more user-friendly experience.
- **Data Persistence**: Store the library’s data in a file or database so that information is retained between sessions.

### Contact

For any questions or feedback, feel free to contact the developer:

- **Email**: lakshmansharma217@gmail.com
- **GitHub**: https://github.com/Lakshmansharma12
