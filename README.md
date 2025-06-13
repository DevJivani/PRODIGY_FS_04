# Real-time Chat Application

A real-time chat application built with the MERN stack (MongoDB, Express.js, React.js, Node.js) and Socket.IO for instant messaging.

## Features

- User authentication (register/login)
- Real-time messaging
- Chat rooms
- Message history
- User presence indicators
- Modern UI with Material-UI

## Prerequisites

- Node.js (v14 or higher)
- MongoDB
- npm or yarn

## Setup

1. Clone the repository:
```bash
git clone <repository-url>
cd chat-app
```

2. Install backend dependencies:
```bash
npm install
```

3. Install frontend dependencies:
```bash
cd client
npm install
```

4. Create a `.env` file in the root directory with the following variables:
```
MONGODB_URI=your-mongodb-url
JWT_SECRET=your-super-secret-key-change-this-in-production
PORT=5000
```

## Running the Application

1. Start the MongoDB server:
```bash
mongod
```

2. Start the backend server (from the root directory):
```bash
npm run dev
```

3. Start the frontend development server (from the client directory):
```bash
cd client
npm start
```
## Usage

1. Register a new account or login with existing credentials
2. Join the default chat room or create a new one
3. Start chatting with other users in real-time
4. Messages are persisted and will be available when you return

## Technologies Used

- Frontend:
  - React.js
  - Material-UI
  - Socket.IO Client
  - React Router
  - Axios

- Backend:
  - Node.js
  - Express.js
  - Socket.IO
  - MongoDB with Mongoose
  - JWT for authentication
  - bcrypt for password hashing

## Security Features

- Password hashing with bcrypt
- JWT-based authentication
- Protected routes
- Input validation
- CORS enabled
