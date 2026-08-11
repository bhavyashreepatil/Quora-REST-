# Quora REST API

A simple Quora-style application built using Node.js and Express.js.
The project demonstrates RESTful API design and CRUD operations for managing posts.

## Features

- Create a new post
- View all posts
- View a specific post
- Update a post
- Delete a post

## Tech Stack

- Node.js
- Express.js
- REST API
- EJS

## CRUD Operations

| Operation | HTTP Method | Endpoint |
|-----------|-------------|----------|
| View all posts | GET | /posts |
| View a post | GET | /posts/:id |
| Create a post | POST | /posts |
| Update a post | PUT | /posts/:id |
| Delete a post | DELETE | /posts/:id |

## How to Run

1. Clone the repository:

   git clone <your-repository-url>

2. Navigate to the project folder:

   cd <project-folder>

3. Install dependencies:

   npm install

4. Start the server:

   node index.js

5. Open:

   http://localhost:8080

## API Testing

The APIs were tested using Hoppscotch.

## Future Improvements

- Add a database
- Add user authentication
- Add comments and likes
- Improve frontend UI
