# PersonaList Task Manager Application

Project cloned and inspired from [this repo.](https://github.com/trananhtuat/fullstack-kanban-app.git)

## Overview

PersonaList is a personal task management web application built with the MERN (MongoDB, Express, React, Node.js) stack. This project allows users to create, edit and manage boards, sections and tasks.

## Features

- User authentication and authorization
- Customized boards details
- Customized sections details
- Customized tasks details
- Kanban style
- Responsive design

## Technologies Used

- MongoDB
- Express.js
- React.js
- Node.js
- Material UI

## Project Setup

### Prerequisites

Have the following installed:

- Node.js
- npm (Node Package Manager)
- MongoDB

Clone the repository:
    ```bash
    git clone https://github.com/ZarinZaidi/DAY_41-Final_Review.git
    cd DAY_41-Final_Review
    ```

### Backend Setup

1. Install SERVER dependencies:
    ```bash
    cd server
    npm install
    ```

2. Create a `.env` file in the `server` directory with the following environment variables:
    ```env
    PORT=5000
    MONGODB_URL
    PASSWORD_SECRET_KEY
    TOKEN_SECRET_KEY
    ```

3. Start the server:
    ```bash
    npm start
    ```

### Frontend Setup

1. Install CLIENT dependencies:
    ```bash
    cd client
    npm install
    ```

2. Start the client server:
    ```bash
    npm start
    ```

## Project Structure

- `server/`: Contains the Express server, database models, routes, and controllers.
- `client/`: Contains the React application, components, and styles.