# Whiteboard Collaborator

A real-time collaborative whiteboard application built using the MERN stack (React, Node.js).

## Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Backend Setup](#backend-setup)
- [Frontend Setup](#frontend-setup)
- [Usage](#usage)
- [License](#license)

## Features
- Real-time drawing collaboration
- Multiple users can join simultaneously

## Tech Stack
- **Frontend:** React, HTML5 Canvas API
- **Backend:** Node.js, Express, Socket.io

## Getting Started
Follow these instructions to set up and run the project on your local machine.

### Prerequisites
- Node.js
- npm (Node Package Manager)

## Backend Setup
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/whiteboard-collaborator.git
    cd whiteboard-collaborator
    ```

2. Navigate to the `server` directory and install dependencies:
    ```bash
    cd server
    npm install
    ```

3. Set up environment variables by creating a `.env` file:
    ```plaintext
    PORT=4000
    MONGO_URI=mongodb://localhost/whiteboard
    ```

4. Start the backend server:
    ```bash
    npm start
    ```

## Frontend Setup
1. Navigate to the `client` directory and install dependencies:
    ```bash
    cd client
    npm install
    ```

2. Start the React development server:
    ```bash
    npm start
    ```

## Usage
1. Open your browser and navigate to `http://localhost:3000`.
2. Draw on the canvas and see updates in real-time across all connected clients.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any changes.


Working Website - https://white-board-9cmv.onrender.com/
