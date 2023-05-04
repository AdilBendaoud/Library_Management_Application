# Library Management Application

📚 This is a GUI application built with Python that allows librarians to manage their library. The application provides an intuitive user interface for adding, removing, and updating books, as well as managing borrowers and tracking borrowed books.

## Conception

### Use case diagram

![useCase](https://user-images.githubusercontent.com/116393842/236274279-9b0334d3-23e0-49bc-a375-441e684d3456.png)

### Class diagram

![classe](https://user-images.githubusercontent.com/116393842/236274750-f9863e8d-c879-4bbf-9b35-7b267608f192.png)


## Features

1. Borrowing/Returning Books: Users can borrow or return books by entering their ID and reference of the book
2. Book Management: Librarians can add, delete, and update books with all relevant information.
3. Librarian Management: Admins can add, delete, and update librarians and view all users in the database.
4. History: A record of all transactions of borrowing and returning books.
5. Members Management: Admins can add, delete, and update members and view all their information, including the name of the books they took.

## Requirements

- Python 3.x 
- MySQL

## Getting Started

👉 When the app starts, use the following credentials to log in:
- Username: admin
- Password: admin

🚀 To get started, follow these steps:
1. Create a MySQL database named "library" in your preferred MySQL database management system.
```SQL
CREATE DATABASE library ;
```
2. Clone the repository to your local machine.
3. Install the required dependencies using pip:
```bash
pip install -r requirements.txt
```
4. Run the app by executing the `Login.py` file:
```bash
python3 Login.py
```
5. Log in using the provided credentials and start managing your library!

## Screenshots

📸 Here are some screenshots of the app:

librarian can add books by filling the forme in right side menu and also he can add image of the book by clicking on the uplaod image button

![livre_add](https://user-images.githubusercontent.com/116393842/236278352-520c1a74-4f68-4703-8b10-63e84e9213d0.PNG)

librarian can transaction by typing the id of the member and reference of the book. **Note :** A member cannot borrow a book if he has already borrowed the same book but has not yet returned it.

![emprunt_add](https://user-images.githubusercontent.com/116393842/236278548-aedcfc6a-8502-4a62-affd-b7973110eb3a.PNG)



## Acknowledgments

🙏 Special thanks to my teacher for inspiring us to build this app and for providing guidance and support throughout the development process. This project was a collaboration between me and [BOUFARRA Oussama](https://github.com/OussamaBu)

