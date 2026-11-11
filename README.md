# ProManage

A project and task management web application with a React frontend and an Express API backed by MongoDB.

## Features

- Create and manage projects
- Add, edit, and organize project tasks
- Navigate projects through the application sidebar and project controls

## Technology

- Frontend: React 18, React Router, Tailwind CSS
- Backend: Node.js, Express, MongoDB, Mongoose

## Repository layout

    Frontend/   React application
    backend/    Express API, routes, controllers, and models

## Run locally

Prerequisites: Node.js, npm, and a MongoDB instance.

Install and start the API:

    cd backend
    npm install
    npm run serve

Configure the backend's required environment values locally before starting it. Check backend/server.js for the names the current application reads.

In a second terminal, install and start the frontend:

    cd Frontend
    npm install
    npm start

The frontend opens at the address printed by the React development server.

## Tests

The frontend package provides the standard React Scripts test command:

    cd Frontend
    npm test

The backend package does not currently define a test script.

## Security

Keep database credentials and other secrets in local environment configuration. Do not commit populated environment files or share their values in issues or screenshots.
