# REST API for blog posts

## Description

This project is a simple REST API built with Express.js, showcasing various endpoints to manipulate a blog collection. It features endpoints to GET all posts, POST new jokes, PATCH and DELETE existing posts. The project serves as a hands-on experience in building and testing REST APIs.

## Key Learnings

- **REST API Development**: Developed skills in creating RESTful endpoints using Express.js.
- **CRUD Operations**: Practiced implementing Create, Read, Update, and Delete (CRUD) operations in a REST API.
- **Data Filtering**: Implemented query parameters to filter jokes based on type.
- **Testing with Postman**: Gained experience in testing API endpoints and handling requests and responses using Postman.
- **JavaScript and Node.js**: Enhanced understanding of server-side JavaScript programming and Node.js capabilities.

## Installation

Clone the repository:

```bash
git clone https://github.com/lappemic/udemy-build-restapi.git
cd udemy-build-restapi
npm install
```

## Usage

Start the server:

```bash
node index.js
```

or using nodemon:

```bash
nodemon index.js
```

Navigate to http://localhost:3000 to interact with the API.

## API Endpoints

- GET /random: Fetch a random joke.
- GET /jokes/:id: Fetch a specific joke by ID.
- GET /filter: Fetch jokes filtered by type.
- POST /jokes: Add a new joke.
- PUT /jokes/:id: Update an existing joke.
- PATCH /jokes/:id: Partially update an existing joke.
- DELETE /jokes/:id: Delete a specific joke.
- DELETE /all: Delete all jokes (restricted access).
