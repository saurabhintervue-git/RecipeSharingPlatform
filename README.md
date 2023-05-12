### Recipe Sharing Platform

- This is a MERN (MongoDB, Express, React, Node.js) stack application that allows users to share and discover recipes. Users can create and view recipes, as well as rate and comment on recipes created by others. The application also includes user authentication and authorization, and allows users to save their favorite recipes.

## Required Features for Both Frontend and Backend

- Displaying a list of recipes
- Adding a new recipe
- Updating an existing recipe
- Deleting a recipe
- User authentication (signup, login, logout)

## Backend Requirements

- Use MongoDB database to store recipes and user information
- Use Express.js to create a RESTful API for CRUD operations
- Use Mongoose.js to define database models and interact with the database
- Use JWT for user authentication and authorization
- Use CORS to allow cross-origin requests

## Frontend Requirements

- Use React.js to create a single-page application (SPA)
- Use Axios to make HTTP requests to the backend API
- Use React Router to handle client-side routing
- Use Redux to manage application state

## Brownie Points

- Search functionality for recipes
- Sorting recipes by name, rating, or date
- Pagination for recipe list
- User authorization (Admin, Contributor, Reader)

## Backend Dependencies

- Node.js (v14 or later)
- Express.js (v4.17 or later)
- Mongoose.js (v6.0 or later)
- JWT (v8.5 or later)
- Cors (v2.8 or later)

## Frontend Dependencies

- React.js (v18 or later)
- React Router (v6 or later)
- Redux (v4 or later)
- Axios.js (v0.24 or later)
- Bootstrap or Material UI (latest version)

## Database Connection

- Create a MongoDB Atlas account (https://www.mongodb.com/cloud/atlas)
- Create a new cluster and a new database
- Add a new user to the database and copy the connection string

## Installation for the App

- Download the zip file of the project and extract it to a folder on your computer.
- Open a terminal or command prompt and navigate to the server folder.
- Run the command "npm install" to install the project dependencies for the server.
- Navigate to the client folder.
- Run the command "npm install" to install the project dependencies for the client.

## Running the App

- Open a terminal or command prompt and navigate to the server folder.
- Run the command "npm start" to start the server.
- Open another terminal or command prompt and navigate to the client folder.
- Run the command "npm start" to start the client.
- Open a web browser and navigate to http://localhost:3000 to view the app.