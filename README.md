# Library Loan System in C++

This project implements a simple console-based Library Loan System in C++. It allows users to manage personal information, borrow books, extend the loan period, and return books. The system uses classes such as `Person`, `Book`, `Date`, and `Loan` to model the borrowing process in a library setting.

## Features

- **Person Management**: Enter and display personal details including name, address, and postal information.
- **Book Management**: Choose from a pre-defined set of books to borrow.
- **Loan Management**:
  - Borrow a book.
  - Extend the loan by one month.
  - Display the current loan details.
  - Return the borrowed book.

## Classes

### `Person`
Represents a person with personal information such as:
- First Name
- Surname
- Street Address
- House Number
- Postal Code
- City

#### Methods:
- `enterData()` – Enter personal details from the user.
- `showData()` – Display the stored personal details.

### `Book`
Represents a book with a title and author.

#### Methods:
- `showData()` – Display the book’s title and author.

### `Date`
Represents a date consisting of day, month, and year.

#### Methods:
- `enterDate()` – Input a date from the user.
- `showData()` – Display the date in the format `DD.MM.YYYY`.
- `incrementByOneMonth()` – Increases the date by one month, adjusting for year transitions and month lengths.

### `Loan`
Represents a loan with:
- A `Person` object as the borrower.
- A `Book` object as the borrowed book.
- A `Date` object as the return date.
- A flag to track whether a book has been borrowed or not.

#### Methods:
- `enterData()` – Enter loan details by providing a `Person`, `Book`, and `Date`.
- `showData()` – Display loan details including the borrower, borrowed book, and return date.
- `extend()` – Extend the loan period by one month.
- `giveBack()` – Mark the book as returned.
- `get_has_book()` – Check if a person currently has a book on loan.

## Menu Options

Once the program starts, the user is presented with a menu:
1. **Enter Personal Data** – Enter or update the borrower's personal information.
2. **Borrow Book** – Borrow one of three available books and set a return date.
3. **Extend Loan** – Extend the return date by one month.
4. **Show Data** – Display the personal and loan details.
5. **Return Book** – Mark the book as returned.
0. **Exit** – Exit the program.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/LibraryLoanSystem.git
   ```
2. Navigate to the project directory:
   ```bash
   cd LibraryLoanSystem
   ```
3. Compile the C++ code using a C++ compiler such as `g++`:
   ```bash
   g++ -o library_loan_system library_loan_system.cpp
   ```
4. Run the compiled program:
   ```bash
   ./library_loan_system
   ```

## Example Usage

1. Enter personal details for the borrower.
2. Borrow one of the available books.
3. Extend the loan period if necessary.
4. Return the book to the library.

## Dependencies

- C++ Standard Library

## Future Enhancements

- Add more books and allow dynamic input for book details.
- Include a database to store loan records persistently.
- Implement more advanced error handling.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
