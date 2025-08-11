# Todo List App

## Overview
This is a full-stack Todo List application built with React (frontend) and Node.js/Express (backend). It allows users to create, update, and delete tasks, with data stored in MongoDB.

## Features
- Add, edit, and delete todos
- Mark todos as completed
- Persistent storage with MongoDB
- RESTful API with Express and Mongoose

## Technologies Used
- Frontend: React, HTML, CSS, JavaScript
- Backend: Node.js, Express.js, MongoDB, Mongoose
- Environment variables managed with dotenv

## Installation and Setup

### Backend
1. Navigate to the backend folder:
   ```bash
   cd backend
2. Install dependencies:
   npm install
3. Create a .env file in the backend folder with your MongoDB connection string:
   MONGO_URI=your_mongo_connection_string_here
4. Start the server:
   node server.js
### Frontend
1. Navigate to the frontend folder:
   cd frontend
2. Install dependencies:
   npm install
3. Start the React app:
   npm start

### Usage
Open your browser and go to http://localhost:3000 to use the frontend.

Backend API runs on http://localhost:5000.

