# EL_Chat App - Full Stack Chat & Blog App

A production-ready full-stack application featuring real-time chat, a blog system with media uploads, and JWT authentication. Built with Node.js, Express, MongoDB, and Socket.IO.

## Features

-   **Authentication**: Secure Register/Login with JWT.
-   **Real-time Chat**: Private messaging with typing indicators and online status (Socket.IO).
-   **Blog System**: Create, read, and delete posts with image uploads (Cloudinary).
-   **Responsive UI**: Built with Bootstrap 5 and custom CSS.

## Tech Stack

-   **Backend**: Node.js, Express.js
-   **Database**: MongoDB (Mongoose)
-   **Real-time**: Socket.IO
-   **Storage**: Cloudinary (for images)
-   **Frontend**: HTML5, CSS3, Bootstrap 5

## Deployment 
1.  **Environment Variables**: Add the following in the Render dashboard:
    -   `MONGO_URI`: Your MongoDB Atlas connection string.
    -   `JWT_SECRET`: A random secret key.
    -   `CLOUDINARY_CLOUD_NAME`, `CLOUDINARY_API_KEY`, `CLOUDINARY_API_SECRET`: From your Cloudinary dashboard.


## API Endpoints

-   `POST /api/auth/register`: Create user.
-   `POST /api/auth/login`: Login user.
-   `GET /api/posts`: Get all posts.
-   `POST /api/posts`: Create post (Multipart form data).
-   `GET /api/messages/:userId`: Get chat history.


