# Simple Go CRUD API Tutorial

This repositories provides a simple CRUD (Create, Read, Update, Delete) API using the Go programming language with the help of Gin.

## Prerequisites

Before you begin, ensure you have the following prerequisites installed:

- [Go](https://go.dev/) (version 1.14 or later)
- [Gin web framework](https://github.com/gin-gonic/gin) (used for creating the API)

## Getting Started

1. Clone the repository:

```bash
git clone git@github.com:billharit/go-crud-api-tutorial.git
```

2. Install required dependencies (Gin):

```bash
go get -u github.com/gin-gonic/gin
```

3. Run the Applications

```bash
go run main.go
```

This will start the server on localhost:8080.

## Endpoints

The API provides the following endpoints:

- GET /books: Get a list of all books.
- GET /books/:id: Get a book by its ID.
- POST /books: Create a new book.
- PATCH /checkout: Check out a book (decrease quantity).
- PATCH /return: Return a book (increase quantity).

## Using the API

You could use curl for accessing the api, i prefer using postman for testing the API I'll provide the postman version on this [Postman Link](https://www.postman.com/flight-cosmologist-10066955/workspace/go-crud-tutorial/collection/23846392-c6f930ef-5517-48d6-8201-a0b00806cad1?action=share&creator=23846392)

## References

This repositories is made following a youtube tutorial that can be accessed here:
https://www.youtube.com/watch?v=8uiZC0l4Ajw&ab_channel=AlexMux
