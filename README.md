# Task Manager API

A Node.js and Express.js backend application that provides user authentication, task management, and rating functionality.  
Users can sign up, log in, and manage tasks securely with JWT-based sessions.  
Password security is ensured through hashing, and MongoDB aggregation is used for advanced data processing in at least one endpoint.

---

## 🚀 Features
- **User Authentication**
  - Sign up with hashed passwords (bcrypt)
  - Login with JWT-based sessions
  - Secure password handling

- **Task Management**
  - Create, update, and delete tasks
  - Rate tasks
  - View all tasks with user-specific filtering

- **Advanced Data Handling**
  - MongoDB Aggregation Framework used for at least one endpoint (e.g., rating statistics, filtering, or analytics)

---

## 🛠 Tech Stack
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Mongoose ODM)
- **Authentication:** JSON Web Token (JWT)
- **Security:** bcrypt for password hashing
- **Other:** MongoDB Aggregation Framework

---

## 📂 Project Structure
project/
│ README.md
│ package.json
│ .gitignore
│
├── config/ # DB and JWT configurations
├── controllers/ # Request handlers
├── models/ # Mongoose schemas
├── routes/ # API routes
├── middleware/ # Authentication middleware
└── utils/ # Helper functions

npm install
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

