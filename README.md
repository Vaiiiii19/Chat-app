# Chat Application

A simple real-time chat application built with Node.js, Express, Socket.io, and React.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Features

- User authentication (Sign Up, Log In)
- Real-time messaging
- Online user status
- Message history

## Installation

### Prerequisites

- Node.js (v14.x or later)
- npm or yarn

### Backend Setup

1. Clone the repository:

    ```sh
    git clone https://github.com/yourusername/chat-app.git
    cd chat-app
    ```

2. Install backend dependencies:

    ```sh
    cd server
    npm install
    ```

3. Create a `.env` file in the `server` directory with the following content:

    ```env
    PORT=3000
    JWT_SECRET=your_jwt_secret
    MONGO_URI=your_mongodb_connection_string
    ```

4. Start the backend server:

    ```sh
    npm start
    ```

### Frontend Setup

1. Navigate to the `client` directory:

    ```sh
    cd ../client
    ```

2. Install frontend dependencies:

    ```sh
    npm install
    ```

3. Start the frontend development server:

    ```sh
    npm start
    ```

The frontend will be running at `http://localhost:3000` and the backend at `http://localhost:3001`.

## Usage

1. Open your browser and go to `http://localhost:3000`.
2. Sign up for a new account or log in with an existing account.
3. Start chatting in real-time with other users.

## Project Structure

```plaintext
chat-app/
│
├── client/               # Frontend React application
│   ├── public/
│   └── src/
│       ├── components/
│       ├── hooks/
│       ├── pages/
│       ├── services/
│       └── App.js
│
├── server/               # Backend Node.js application
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   └── server.js
│
├── README.md
└── package.json
