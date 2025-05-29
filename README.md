# Book API 📚

A simple Express.js REST API to manage a list of books.

## Features

- Add a new book
- View all books
- Update a book by ID
- Delete a book by ID

## Base URL

```
http://localhost:3000/books
```

## Endpoints

### 1. Get all books

```
GET /books
```

### 2. Add a new book

```
POST /books
Body:
{
    "title": "The Alchemist",
    "author": "Paulo Coelho"
}
```

### 3. Update a book

```
PUT /books/:id
Body:
{
    "title": "Updated Title",
    "author": "Updated Author"
}
```

### 4. Delete a book

```
DELETE /books/:id
```

## Screenshots

### Book List Response (GET)
![Screenshot 2025-05-29 141647](https://github.com/user-attachments/assets/be16a3bc-4bd2-4e96-9e36-6f19a0972c23)


### Add Book (POST)
![Screenshot 2025-05-29 141702](https://github.com/user-attachments/assets/0f90a60a-2c67-484a-bd00-e397ba412f15)


### Update Book (PUT)
![Screenshot 2025-05-29 142106](https://github.com/user-attachments/assets/4b7205fb-a7a0-4a7c-ba10-d33f0ce62f4d)


### Delete Book (DELETE)
![Screenshot 2025-05-29 142155](https://github.com/user-attachments/assets/552b0b2c-5b18-419f-9d04-9fd59082cb24)


---

Created with ❤️ using Node.js and Express.

