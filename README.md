# Blog Management System

## Overview

This is a simple blog management system built using Node.js and Express.js. The application is divided into two components:

1. **Backend API**: A RESTful API for managing blog posts (CRUD operations).
2. **Frontend Application**: A user interface to interact with the API for creating, editing, viewing, and deleting posts.

## Features

- View all posts
- View a specific post by ID
- Create a new post
- Edit an existing post
- Delete a post

## Technologies Used

- **Backend**: Node.js, Express.js
- **Frontend**: EJS for templating
- **HTTP Client**: Axios
- **Middleware**: body-parser

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project folder:

   ```bash
   cd project-folder
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

## Usage

### Start the Backend API

1. Navigate to the backend directory (if applicable).
2. Run the backend server:
   ```bash
   node api.js
   ```
3. The API will be running at `http://localhost:4000`.

### Start the Frontend Application

1. Navigate to the frontend directory (if applicable).
2. Run the frontend server:
   ```bash
   node app.js
   ```
3. The frontend application will be available at `http://localhost:3000`.

## API Endpoints

### Posts

- **GET** `/posts` - Retrieve all posts
- **GET** `/posts/:id` - Retrieve a specific post by ID
- **POST** `/posts` - Create a new post
- **PATCH** `/posts/:id` - Partially update a post
- **DELETE** `/posts/:id` - Delete a specific post

## Frontend Routes

- `/` - Display all posts
- `/new` - Create a new post
- `/edit/:id` - Edit an existing post
- `/api/posts/delete/:id` - Delete a post

