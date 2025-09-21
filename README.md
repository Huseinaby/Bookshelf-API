#  Bookshelf API

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/Hapi.js-000000?style=for-the-badge&logo=hapi&logoColor=white" alt="Hapi.js">
  <img src="https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white" alt="ESLint">
</p>

A simple RESTful API for managing a collection of books, allowing users to perform basic CRUD (Create, Read, Update, Delete) operations. This project was developed as a final submission for the "Belajar Membuat Aplikasi Back-End untuk Pemula" (Learning to Build a Back-End Application for Beginners) course on the **Dicoding** platform.

The application is built with vanilla Node.js and the Hapi.js framework, with data being stored in-memory in a local array (no database).

##  Key Features

-   **Add a New Book**: Save a new book with details like title, author, and summary.
-   **Get All Books**: Retrieve a list of all saved books.
-   **Get Book by ID**: Fetch the details of a specific book using its unique ID.
-   **Update Book Data**: Modify the information of an existing book.
-   **Delete a Book**: Remove a book from the collection.
-   **Query Parameters**: Filter the book list based on `name`, `reading` status, or `finished` status.

##  Teck Stack

-   **Runetime Environtment**: Node.js
-   **Web Framework**: Hapi.js
-   **Unique ID Generation**: nanoid
-   **Code Linter**: ESLint
-   **Development Tools**: Nodemon

##  Installation & Setup

Follow these steps to get the project running on your local machine.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Huseinaby/Bookshelf-API.git
    cd Arsip
    ```
2.  **Install dependencies:**
    ```bash
    npm install
    ```
3.  **Run server:**
    ```bash
    npm run start
    ```
    The API will be available at `http://localhost:5000`.