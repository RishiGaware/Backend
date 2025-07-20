# Backend API Server

This is a Node.js/Express backend server with authentication, file upload, and admin functionality.

## Features

- User authentication and authorization
- File upload with Multer
- Firebase integration
- Admin dashboard
- User management
- Image processing

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Firebase
- Multer (file upload)
- JWT Authentication

## Installation

1. Install dependencies:
```bash
npm install
```

2. Set up environment variables:
Create a `.env` file with:
```
PORT=5000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```

3. Start the server:
```bash
npm start
```

## API Endpoints

- `POST /api/auth/register` - User registration
- `POST /api/auth/login` - User login
- `GET /api/admin/users` - Get all users (admin only)
- `POST /api/upload` - File upload

## Project Structure

```
backend/
├── config/          # Configuration files
├── controller/      # Route controllers
├── routes/          # API routes
├── uploads/         # Uploaded files
└── server.js        # Main server file
``` 