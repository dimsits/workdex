# My Website

This project is a full-stack web application using Node.js for the backend and React for the frontend. This README provides instructions on how to set up and run the project.

## Table of Contents

- [Installation](#installation)
  - [Backend](#backend)
  - [Frontend](#frontend)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [License](#license)

## Installation

### Backend

1. **Navigate to the backend directory**:

    ```bash
    cd backend
    ```

2. **Install the backend dependencies**:

    ```bash
    npm install
    ```

3. **Set up the environment variables**:

    Create a `.env` file in the `backend` directory with the following content:

    ```env
    DB_HOST=localhost
    DB_USER=root
    DB_PASSWORD=yourpassword
    DB_NAME=yourdatabase
    PORT=5000
    ```

4. **Run database migrations**:

    ```bash
    npx sequelize-cli db:migrate
    ```

### Frontend

1. **Navigate to the frontend directory**:

    ```bash
    cd frontend
    ```

2. **Install the frontend dependencies**:

    ```bash
    npm install
    ```

## Usage

### Running the Backend

1. **Navigate to the backend directory**:

    ```bash
    cd backend
    ```

2. **Start the backend server**:

    ```bash
    npm run dev
    ```

    This will start the server on the port specified in the `.env` file (default is `5000`).

### Running the Frontend

1. **Navigate to the frontend directory**:

    ```bash
    cd frontend
    ```

2. **Start the frontend development server**:

    ```bash
    npm start
    ```

    This will start the frontend development server and open the application in your default browser.

## Project Structure

