# Blog Post API

## Description

This blog post API, built with Express.js, serves as a backend for managing blog posts, including creating, reading, updating, and deleting entries. The project showcases the development of a RESTful API and interaction with it through a front-end interface, demonstrating CRUD operations on an in-memory data store.

## Key Learnings

- **RESTful API Development**: Mastered designing and implementing RESTful APIs using Express.js.
- **CRUD Operations**: Implemented Create, Read, Update, and Delete operations.
- **EJS Templating**: Utilized EJS for dynamic HTML content rendering.
- **Express.js and Body Parsing**: Leveraged Express.js and `body-parser` middleware for request handling and parsing.

## Installation

To set up the project locally:

1. Clone the repository:

```bash
git clone https://github.com/lappemic/udemy-api-blog.git
cd udemy-api-blog
```

2. Install the dependencies:

```bash
npm install
```

## Running the Project

1. Start the API server (index.js):

```bash
nodemon index.js
```

This starts the backend server on http://localhost:4000.

2. In a new terminal, start the front-end server (server.js):

```bash
nodemon server.js
```

This starts the front-end server on http://localhost:3000.

3. Open a web browser and go to http://localhost:3000 to interact with the application.

## API Endpoints

- GET /posts: Retrieve all blog posts.
- GET /posts/:id: Retrieve a specific post by ID.
- POST /posts: Create a new blog post.
- PATCH /posts/:id: Update a specific post by ID.
- DELETE /posts/:id: Delete a specific post by ID.
- DELETE /all: Delete all posts (restricted access).

## Project Structure

- index.js: Main server file for the API with route definitions.
- server.js: Backend server for handling front-end requests.
- views/: EJS templates for rendering the blog interface.
- public/: Static files for styling.

```

```
