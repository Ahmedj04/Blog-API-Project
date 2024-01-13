# Blog Management System

## Overview

This project is a simple Blog Management System with a frontend and backend. It allows users to view, create, edit, and delete blog posts through a user-friendly interface. The backend is built using Express.js, and data is stored in-memory. The frontend is served using EJS templates and communicates with the backend through API calls.

### Features

- View all blog posts
- View a specific blog post by ID
- Create a new blog post
- Edit an existing blog post
- Delete a blog post

## Prerequisites

- Node.js installed on your machine
- npm (Node Package Manager) installed

## Getting Started

Follow these steps to start the project:

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/Ahmedj04/blog-API-Project.git
    ```

2. **Navigate to the Project Directory:**

    ```bash
    cd blog-API-Project
    ```

3. **Install Dependencies:**

    ```bash
     npm i
    ```

4. **Start the Servers:**

    ```bash
    # Start the API server
    nodemon index.js

    # Start the backend server
     nodemon server.js
    ```

5. **Access the Application:**

    Open your browser and go to [http://localhost:3000](http://localhost:3000) to access the blog-API-Project.

## Usage

- Visit the main page to view all blog posts.
- Click on a post title to view the full post.
- Use the "New Post" button to create a new blog post.
- Click on the "Edit" button next to a post to edit it.
- To delete a post, click on the "Delete" button.

## API Endpoints

- **GET /posts**: Retrieve all blog posts.
- **GET /posts/:id**: Retrieve a specific blog post by ID.
- **POST /posts**: Create a new blog post.
- **PATCH /posts/:id**: Update a blog post.
- **DELETE /posts/:id**: Delete a blog post.

## Technologies Used

- Backend: Express.js, Node.js
- Frontend: EJS, HTML, CSS
- API Communication: Axios
- Data Storage: In-memory array

## Notes

- This project uses in-memory storage and is for educational purposes. It's not suitable for production use without integrating a proper database.

Feel free to explore, modify, and enhance the project! If you encounter any issues or have suggestions, please create an issue in the GitHub repository. Happy coding!
