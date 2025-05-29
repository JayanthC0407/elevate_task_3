# 📚 Edunet Labs Internship - Task 3

## 🛠 Project Title: Book Management REST API with Node.js and Express

### 👨‍💻 Developed by: Jayanth Chintalapati

---

## 📌 Objective

Create a fully functional REST API using **Node.js** and **Express.js** that allows users to perform **CRUD operations** (Create, Read, Update, Delete) on a list of books stored in memory.

---

## 🧰 Tech Stack

- Node.js
- Express.js
- RESTful API
- JSON (for request & response handling)
- Postman (for testing endpoints)

---

## 🚀 How to Run the Project

1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/task-3-book-api.git
   cd task-3-book-api

2. **Install dependencies**
   ```npm install

3. **Start the server**
   ```node index.js

4. **Test endpoints using Postman or VS Code REST client**
      | Method | Route        | Description          |
      | ------ | ------------ | -------------------- |
      | GET    | `/books`     | Returns all books    |
      | POST   | `/books`     | Adds a new book      |
      | PUT    | `/books/:id` | Updates a book by ID |
      | DELETE | `/books/:id` | Deletes a book by ID |

5. **Sample Book Object**
       {
         "id": 1,
         "title": "The Alchemist",
         "author": "Paulo Coelho"
       }

6. **Example Requests (Postman)**
    POST /books
    {
      "title": "Atomic Habits",
      "author": "James Clear"
    }

    PUT /books/1 
    {
      "title": "Updated Title"
    }
    
    DELETE /books/1
    No body required.

