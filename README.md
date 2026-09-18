# Simple Todo API

A beginner-friendly REST API built with Node.js and Express.

## Features

- Get all todos
- Get one todo
- Create a todo
- Update a todo
- Delete a todo

## Run locally

```bash
npm install
npm start
```

Server:

http://localhost:3000

## Endpoints

| Method | Endpoint | Description |
| --- | --- | --- |
| GET | /todos | Get all todos |
| GET | /todos/:id | Get one todo |
| POST | /todos | Create a todo |
| PUT | /todos/:id | Update a todo |
| DELETE | /todos/:id | Delete a todo |

## Example POST body

```json
{
  "title": "Learn Express"
}
```

## What you learn

This project is intentionally simple. It helps you practice:

- HTTP methods
- REST API basics
- Express routes
- Request and response
- CRUD operations
- JSON
