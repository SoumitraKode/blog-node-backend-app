# Backend Blogs App

## Overview
This is a backend application for a blogging platform. It provides functionalities to create posts, like/unlike posts, and comment on posts. The application is built using Node.js and Express.js.

## Features
- **Create Post**: Users can create new blog posts.
- **Get All Posts**: Fetch all the blog posts.
- **Like Post**: Users can like a post.
- **Unlike Post**: Users can unlike a post.
- **Create Comment**: Users can comment on a post.

## Controllers
### Comment Controller
- `createComment(req, res)`: Creates a new comment on a post.

### Like Controller
- `likePost(req, res)`: Likes a post.
- `unlikePost(req, res)`: Unlikes a post.

### Post Controller
- `createPost(req, res)`: Creates a new post.
- `getAllPost(req, res)`: Retrieves all posts.

## Installation
1.   Install dependencies
        Using npm:
     ```bash
     npm install
2. Set up environment variables
    ```bash
    MONGO_URL=mongodb://localhost:27017/blogs-app
    PORT=3000
3. Start the Server:
    ```bash
    npm start

## Troubleshooting
If you encounter any issues during installation or while running the application, please refer to the documentation or open an issue in the repository.

