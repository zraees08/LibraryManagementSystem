# LibraryManagementSystem
Description
This project implements a simple Library Management System in Java. It includes classes for managing users, books, and the library itself. Users can borrow and return books, and the system provides functionalities such as adding users, adding books, checking out books, returning books, displaying the list of books, and searching for books by title or ID.

Setup and Run Instructions

1. Prerequisites
   - Java Development Kit (JDK)
   - Integrated Development Environment (IDE) for Java (e.g., IntelliJ IDEA, Eclipse)

2. Clone Repository
   
   git clone https://github.com/your-username/library-management-system.git
   cd library-management-system
   

3. Open in IDE
   Open the project in your preferred Java IDE.

4. Run the Program
   Locate the `Library.java` file and run the `main` method. This will start the Library Management System.

Key Features and Functionalities

1. Add Book
   - Adds a new book to the library with details such as ID, title, author, genre, and availability status.

2. Add User
   - Adds a new user to the library with details such as ID, name, and contact information.

3. Check Out Book
   - Allows a user to borrow a book by specifying their user ID and the book's title.

4. Return Book
   - Enables a user to return a borrowed book by specifying their user ID and the book's title.

5. Display Books
   - Displays a list of all books in the library, including their ID, title, author, genre, and availability status.

6. Search Book by Title or ID
   - Allows users to search for a book by either its title or ID.

7. Exit Program
   - Exits the Library Management System.

Example Usage

// Code snippets for using Library Management System functionalities

// Create a new book and add it to the library
Library.addBook(1, "The Great Gatsby", "F. Scott Fitzgerald", "Fiction", true);

// Create a new user and add them to the library
Library.addUser(101, "John Doe", 1234567890);

// Check out a book for a user
Library.bookCheckOut(101, "The Great Gatsby");

// Return a book to the library
Library.returnBook(101, "The Great Gatsby");

// Display the list of books in the library
Library.displayBook();

// Search for a book by title
Book foundBook = Library.searchBookbyTitle("The Great Gatsby");

// Search for a book by ID
Book foundBookByID = Library.searchBookbyID(1);

Feel free to explore and modify the code as needed for your use case. Enjoy using the Library Management System!
