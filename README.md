
# README.md

# Library Management System

This is a simple command-line Library Management System written in Python. It allows you to add books, view all books, issue books, return books, and save book data to a file.

## Features

- Add new books with title, author, and ISBN.
- View all books and their status (Available/Issued).
- Issue a book by ISBN.
- Return a book by ISBN.
- Persistent storage using `library.txt`.

## How to Run

1. Make sure you have Python installed.
2. Save the code in a file named `assignment2.py`.
3. Run the program:
    ```
    python assignment2.py
    ```

## File Structure

- `assignment2.py`: Main program file.
- `library.txt`: Data file where book information is stored.

## Usage

Follow the on-screen menu to add, view, issue, or return books. Data is saved automatically.

## Notes

- The program uses a simple text file for storage.
- Make sure `library.txt` is in the same directory as the script.
- Only ISBN is used to identify books for issuing and returning.

## License

This project is for educational purposes.
