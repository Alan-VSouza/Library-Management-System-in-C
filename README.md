# Library Management System

This project implements a library management system that allows various operations such as user and book registration, loan and return of books, and more.

## Main Features

The system provides the following features:

1. **User Registration**: Allows the registration of new users with detailed information such as name, CPF, address, emails, and phone numbers.
2. **Book Registration**: Allows adding new books to the system with information like ISBN, title, genre, authors, and number of pages.
3. **Book Loan**: Registers the loan of a book to a user.
4. **Book Return**: Registers the return of a borrowed book.
5. **List of Books**: Displays all books registered in the system with details such as title and availability.
6. **User Lookup**: Allows searching for registered users by CPF.

## Data Structures

### `usuario` (User)
- **CPF**: Unique identifier for the user.
- **Name**: Full name of the user.
- **Address**: Street, number, and postal code.
- **Emails**: List of emails associated with the user.
- **Phones**: List of phone numbers associated with the user.
- **Date of Birth**: User's date of birth.
- **Profession**: User's profession.

### `livro` (Book)
- **ISBN**: Unique identifier for the book.
- **Title**: Title of the book.
- **Genre**: Genre of the book (e.g., Fiction, Non-fiction).
- **Authors**: List of up to 3 authors of the book.
- **Page Count**: Total number of pages in the book.

## How to Run the Project

1. Download the project files.
2. Compile the source code using GCC or any other compiler compatible with C99.
3. Run the program to interact with the library management system.

Example of compilation and execution:

```bash
gcc Trabalho\ Gerenciamento\ Biblioteca.c -o library
./library
