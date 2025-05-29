
# 📚 Book API

A simple RESTful API built using Node.js and Express to manage a list of books. This API allows you to create, read, update, and delete book records in memory.

---

## 🚀 Features

- Add a book (auto-incrementing ID)
- Get all books
- Update a book by ID
- Delete a book by ID

---

## 🛠️ Tech Stack

- Node.js
- Express

---

## 📦 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/book-api.git
   cd book-api
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the server**:
   ```bash
   npm start
   ```

4. The API will be running at:
   ```
   http://localhost:3000
   ```

---

## 🧪 Testing with Postman

### ➕ Add a Book

- **Method**: POST  
- **URL**: `http://localhost:3000/books`  
- **Body (JSON)**:
  ```json
  {
    "title": "The Alchemist",
    "author": "Paulo Coelho"
  }
![Screenshot 2025-05-29 141702](https://github.com/user-attachments/assets/7012cad9-0f15-4792-8847-6d9df5d0440a)

  ```

### 📚 Get All Books

- **Method**: GET  
- **URL**: `http://localhost:3000/books`

![Screenshot 2025-05-29 141647](https://github.com/user-attachments/assets/5792a818-6c7a-4d7e-b7ee-908e36918de0)

### ✏️ Update a Book

- **Method**: PUT  
- **URL**: `http://localhost:3000/books/2`  
![Screenshot 2025-05-29 142106](https://github.com/user-attachments/assets/236b2905-b637-48fe-baa3-bb7b69b0575f)



  ```

### ❌ Delete a Book

- **Method**: DELETE  
- **URL**: `http://localhost:3000/books/3`
- ![Screenshot 2025-05-29 142155](https://github.com/user-attachments/assets/6fc1d696-cd6c-4eeb-9c13-9f23b086d8c2)


---

## 📁 Project Structure

```
book-api/
├── index.js
├── package.json
└── README.md
```

---

## 📌 Notes

- Data is stored in memory, so it resets when the server restarts.
- You can expand the project to use file storage or a database like MongoDB.

---

## 👩‍💻 Author

**Tanisha**  
Made with ❤️ using Node.js + Express

---

## 📜 License

This project is licensed under the ISC License.
