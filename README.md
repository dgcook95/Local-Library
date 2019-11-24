# Local-Library
This project simulates a local library, where users can check books out, and librarians can perform administrative tasks. This goal of this project was to demonstrate user permissions as it relates to a web application.

This project was inspired by https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/

Users can:
- Sign up for an account
- View all books and authors in the library
- View the books they're currently borrowing and their due date

Librarians can:
- View all books and authors
- Update any metadata about books and authors (all from their login)
- Create new books and authors
- Delete books and authors
- Alter book instances
- Renew books for users

I used a variation of class based views and function based views, but they're interchangeable and either can be used.
