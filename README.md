# Node.js E-Commerce Machine Test

A simple REST API built with Node.js, Express.js and MongoDB for user authentication.

## Features

- User registration
- Email validation
- Duplicate email check
- Password confirmation
- Password hashing using bcrypt
- User login
- JWT token generation
- JWT authentication middleware
- Protected profile route
- Basic error handling

## Tech Stack

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- bcryptjs
- dotenv

## Project Structure

```text
server/
├── src/
│   ├── config/
│   │   └── db.js
│   ├── controllers/
│   │   └── authController.js
│   ├── middleware/
│   │   └── authMiddleware.js
│   ├── models/
│   │   └── User.js
│   └── routes/
│       └── authRoutes.js
├── .env.example
├── .gitignore
├── package.json
└── server.js