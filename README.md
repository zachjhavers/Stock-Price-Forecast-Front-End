# Installation Guide

This guide will walk you through the process of installing all dependencies for a MERN (MongoDB, Express.js, React.js, Node.js) stack application. The application consists of a client folder (React) and a server folder (Node.js).

## Prerequisites

Before you begin, ensure you have the following installed on your machine:

- Node.js: [Download and Install Node.js](https://nodejs.org/)
- MongoDB: [Download and Install MongoDB](https://www.mongodb.com/try/download/community)

## Installation Steps

1. **Clone the Repository:**

  git clone https://github.com/zachjhavers/Stock-Price-Forecast-Front-End/

2. **Navigate to the Server Folder:**

  cd Stock-Price-Forecast-Front-End/server

3. **Install Server Dependencies:**

  npm install

4. **Run the Server:**

  node server.js

  The server should now be running on http://localhost:4000.

5. **Navigate to the Client Folder:**

  cd ../client

6. **Install Client Dependencies:**

  npm install

7. **Start the Client:**

  npm start


The client should now be running on http://localhost:3000.

## Notes

- Ensure that MongoDB is running locally or is accessible at the specified URI in your server code.
- You may need to customize server.js and other configuration files based on your specific requirements and environment.
- Make sure you have appropriate permissions to install packages globally if you encounter any permission errors during the installation process.

