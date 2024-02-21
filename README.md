## Library Management Program Description

The task involved creating a C++ program to manage a library system, allowing users to enter personal data, borrow books, extend loan periods, return books, and view data. The program is designed to efficiently handle these tasks while providing a user-friendly interface.

### Program Features

- **Personal Data Entry**: Users can input personal data, including first name, surname, street, house number, postal code, and city. This data is stored for future reference.

- **Book Borrowing**: Users can borrow books from the library. If the borrower has already borrowed a book, the program alerts them accordingly. Users can select from a list of available books and specify the return date.

- **Loan Extension**: If a user has borrowed a book, they can extend the loan period by one month.

- **Data Display**: Users can view their personal data and details of any books they have borrowed, including the return date.

- **Book Return**: Users can return borrowed books to the library.

- **Menu Interface**: The program features a menu-driven interface that guides users through the available options and provides feedback on their selections. Users can easily navigate between different functionalities using the menu.

- **Error Handling**: The program includes error handling to handle incorrect user inputs and provide appropriate feedback.

### Technical Implementation

- **Classes**: The program utilizes several classes to represent entities such as Person, Book, and Loan. These classes encapsulate relevant data and functionalities related to their respective entities, promoting code organization and maintainability.

- **Dynamic Memory Management**: The program dynamically manages memory allocation to store user data and book information. This approach ensures efficient memory usage and scalability, allowing the program to handle a variable number of users and books.

- **User Interaction**: The program interacts with users through the command-line interface, displaying prompts, menus, and messages to guide users through various actions and provide feedback on their inputs.

- **Modular Design**: The program is modularly designed, with distinct functions and classes responsible for specific tasks. This modular design facilitates code readability, reusability, and maintenance.

- **Looping Structure**: The program features a loop that continuously prompts users for input and executes the corresponding functionality based on their selections. This looping structure allows users to perform multiple actions within a single session until they choose to exit the program.

- **System Integration**: The program integrates system commands (e.g., `system("pause")`, `system("cls")`) to enhance user experience by pausing execution and clearing the console screen when necessary.

### Conclusion

Overall, the library management program provides a comprehensive solution for managing library operations, including user data entry, book borrowing, loan extension, book return, and data display. With its user-friendly interface and efficient functionality, the program facilitates seamless interaction between users and the library system.
