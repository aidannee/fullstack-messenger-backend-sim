# fullstack-messenger-backend-sim

# fullstack-messenger-frontend
<img src="https://images.unsplash.com/photo-1511447333015-45b65e60f6d5?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1555&q=80"></img>

This repository contains the backend code for a simple CRUD (Create, Read, Update, Delete) messaging app built using Express and Sequelize ORM with PostgreSQL as the database.

## Overview

The backend handles the storage, retrieval, update, and deletion of messages. It provides RESTful APIs to interact with the messages stored in the database.

## Features

- **Create:** Add new messages to the database.
- **Read:** Retrieve messages from the database.
- **Update:** Modify existing messages.
- **Delete:** Remove messages from the database.

## Tech Stack

- **Framework:** Express.js
- **Database:** PostgreSQL with Sequelize ORM
- **Middleware:** Body-parser, CORS

## Getting Started

To run this backend server locally, follow these steps:

1. Clone the repository:

    ```bash
    git clone <repository_url>
    cd <backend_directory>
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Set up the database:
    - Ensure PostgreSQL is installed and running.
    - Update the `.env` file with your database connection details.

4. Start the server:

    ```bash
    npm start
    ```

    The server will start running on `http://localhost:3000`.

## API Endpoints

- **GET /messages:** Retrieve all messages.
- **POST /messages:** Create a new message.
- **PUT /messages/:id:** Update a message by ID.
- **DELETE /messages/:id:** Delete a message by ID.


- `DB_URI`: PostgreSQL database URI



Feel free to contribute or suggest improvements by creating issues or pull requests.
