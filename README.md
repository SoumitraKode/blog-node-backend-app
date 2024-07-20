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
To install the dependencies, run:
```bash
npm install
