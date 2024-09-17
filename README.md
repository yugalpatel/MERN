# MERN Note-taking App

## Overview

The MERN Note App is a dynamic and user-friendly note-taking application inspired by Notion, designed to offer a seamless and distraction-free note-taking experience. This project serves as an exploration into building scalable software systems with a focus on minimalistic UI and robust backend architecture. By studying and replicating features from established platforms like Notion, this project aims to provide essential note-taking functionalities while demonstrating key software engineering principles.

## App Preview

https://github.com/jp-quintana/mern-note-app/assets/87621233/10b92abc-03c0-4932-a213-aa3b375f3c80

## Motivation

In the pursuit of understanding large-scale software development, this project draws inspiration from Notion to build a note-taking application with a clean and intuitive interface. The goal is to create a minimalistic user experience that enhances productivity and allows users to focus solely on their notes without unnecessary distractions. This project also provides an opportunity to implement and integrate various technologies and methodologies in a practical setting.

## Project Features

- **Create, Edit, Duplicate, and Delete Notes:** Users can manage their notes efficiently with CRUD (Create, Read, Update, Delete) operations.
- **Basic Note Customization:** Notes can be customized with basic formatting options to suit individual preferences.
- **Note List Reorder:** Users can easily reorder their list of notes to better organize their content.
- **Basic JWT Authentication:** Secure access to the application with JSON Web Token (JWT) authentication.
- **DAO Layer Setup:** A well-defined Data Access Object (DAO) layer is set up on the server to manage database interactions and maintain a clean separation of concerns.

## Instructions to Run Locally

1. **Clone the Repository**

   ```bash
   git clone https://github.com/YOUR_USERNAME/MERN-Note-App.git
   ```

2. **Navigate to the Project Directory**

   ```bash
   cd MERN-Note-App
   ```

3. **Install Dependencies**

   - For the server:
     ```bash
     cd server
     npm install
     ```

   - For the client:
     ```bash
     cd ../client
     npm install
     ```

4. **Set Up Environment Variables**

   Create a `.env` file in both the `server` and `client` directories with the following content:

   **Server `.env` file:**
   ```
   MONGO_URI=your_mongodb_connection_string
   PORT=8080
   JWT_SECRET=your_jwt_secret_key
   ```

   **Client `.env` file:**
   ```
   REACT_APP_API_URL=http://localhost:8080
   ```

5. **Start the Server**

   ```bash
   cd server
   npm start
   ```

6. **Start the Client**

   ```bash
   cd ../client
   npm start
   ```

   Open your browser and navigate to `http://localhost:3000` to use the application.

## Technologies Used

- **Frontend:**
  - React
  - React Router
  - Axios

- **Backend:**
  - Node.js
  - Express
  - MongoDB
  - Mongoose
  - JSON Web Token (JWT)

- **Tools and Libraries:**
  - Babel
  - Webpack
  - Nodemon
