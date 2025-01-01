# 📚 Bookshelf API
The Bookshelf API is a simple yet powerful RESTful web service designed to manage a digital bookshelf. Built with Node.js and Hapi.js, this project demonstrates how to create a lightweight API using a local database (file-based or in-memory storage). It’s perfect for learning backend development with minimal dependencies.


## 🚀 Features
- Add a Book: Store details like title, author, year, and genre.
- Get All Books: Retrieve a list of all books in the bookshelf.
- Get Book by ID: Fetch details of a specific book using its unique ID.
- Update a Book: Modify the details of an existing book.
- Delete a Book: Remove a book from the bookshelf.

## 🛠️ Technologies Used

- Backend: Node.js, Hapi.js
- Database: Local storage (file-based JSON or in-memory storage)
- Validation: Joi for request validation
- Testing: Lab and Code for unit and integration testing

## Project Structure

Here is the structure of the **Bookshelf-API** project:

```plaintext
bookshelf-api/  
├── node_modules/             # Installed dependencies  
├── src/                      # Source code  
│   ├── books.js              # Contains book-related logic or data  
│   ├── handler.js            # Handlers for request logic  
│   ├── routes.js             # Defines API endpoint routes  
│   └── server.js             # Main server file  
├── .eslintrc.js              # ESLint configuration  
├── .gitignore                # Specifies files to ignore in Git  
├── .prettierrc.json          # Prettier configuration for code formatting  
├── eslint.config.mjs         # ESLint configuration (optional, modern format)  
├── package-lock.json         # Lock file for dependencies  
├── package.json              # Project dependencies and scripts  
└── README.md                 # Project documentation
```


## Follow these steps to set up and run the **Bookshelf API** on your local machine:

1. **Clone this repository**:  
   ```bash
   git clone https://github.com/your-username/bookshelf-api.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd bookshelf-api
   ```
3. **Install dependencies**:
   ```bash
   npm install
   ```
4. **npm install**:
   ```bash
   npm start
   ```

## 📄API Endpoints

- POST /books: Add a new book.
- GET /books: Retrieve all books.
- GET /books/{id}: Retrieve a specific book by ID.
- PUT /books/{id}: Update a book by ID.
- DELETE /books/{id}: Delete a book by ID.

## 🤝 Contributing
Contributions are welcome! Please open an issue or submit a pull request.
