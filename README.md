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
![GET](6f8011e3-16df-4807-b4f8-39181225308d.png)

### Add Book (POST)
![POST](91894f51-1211-4720-8b88-a47562f69faa.png)

### Update Book (PUT)
![PUT](b42c3a6a-3ff5-4aba-b761-6b1bd8dc9630.png)

### Delete Book (DELETE)
![DELETE](fb3a33c2-1fcf-4a5b-abba-4cbf707a870e.png)

---

Created with ❤️ using Node.js and Express.

