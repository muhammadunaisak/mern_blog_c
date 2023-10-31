# Simple Blog App

This is a simple blog application built using React for the frontend, Node.js for the backend, and MongoDB as the database.<br>

##login

![image](https://github.com/muhammadunaisak/mern_blog_c/assets/84447232/62eeb82b-b9f1-412e-b896-5672a7d98d3d)<br>

##Register
![image](https://github.com/muhammadunaisak/mern_blog_c/assets/84447232/8c81dde3-1ca3-40b9-9be1-e6a9f806f637)

##home
![image](https://github.com/muhammadunaisak/mern_blog_c/assets/84447232/bc7eb2ab-c127-4051-bfeb-4772eaeecf6f)


## Features

- User authentication (signup, login, logout)
- Create, read, update, and delete blog posts
- View a list of blog posts
- Store blog post data in a MongoDB database

## Prerequisites

Make sure you have the following installed before running the application:

- Node.js
- MongoDB

## Installation

### Backend (Node.js)

1. Navigate to the `backend` directory: `cd backend`
2. Install dependencies: `npm install`
3. Set up environment variables:
   - Create a `.env` file based on the `.env.example` file and configure it with your MongoDB connection string and any other necessary variables.
4. Run the server: `npm start`

### Frontend (React)

1. Navigate to the `frontend` directory: `cd frontend`
2. Install dependencies: `npm install`
3. Start the application: `npm start`

The application should open in your default web browser.

## Folder Structure

- `backend`: Contains Node.js server files.
  - `controllers`: Handles business logic.
  - `models`: Defines database schemas.
  - `routes`: Defines API endpoints.
  - `utils`: Utility functions.
  - `app.js`: Entry point for the backend application.

- `frontend`: Contains React files.
  - `public`: Static assets.
  - `src`: Source files.
    - `components`: Reusable React components.
    - `pages`: Different pages of the application.
    - `services`: API calls to the backend.
    - `App.js`: Main component.
    - `index.js`: Entry point for the React application.

## Technologies Used

- Frontend: React, React Router
- Backend: Node.js, Express
- Database: MongoDB
- Other: Axios (for API requests), JWT (for authentication)


