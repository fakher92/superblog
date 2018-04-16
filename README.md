# Superblog API

This is a little node server with CRUD interface:


# Installation
Install npm stuff `npm i`

Create a copy of env file: `cp .env.example .env`  and set your credentials


# Start node server

`node server/server.js`

# Routes
- GET `/api/posts` all posts
- POST `/api/posts` creates a post. The request body must contain the post itself. See model
- DELETE `/api/posts:id` deletes a post by given id eg: `/api/posts/5ad4ce741a411bc2cb787445`
- PUT `/api/posts:id` deletes a post by given id
  eg: `/api/posts/5ad4ce741a411bc2cb787445`

# Model
```javascript
{
    name: String,
    age: Number
}
```
