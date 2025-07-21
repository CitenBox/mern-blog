# MERN Community Blog Forum

Final semester project for the Full Stack course MERN (MongoDB, Express, React, Node.js).

(i did it alone. hope thats ok)

## Project Description

The system allows users to register, log in, create posts, edit and delete them, comment on posts, and manage their personal content in a user-friendly way. The project emphasizes use of JWT for authentication, bcryptjs for password hashing, a modern interface with a rich text editor, and support for image uploads.

## Installation and Running Instructions

### Prerequisites

- Node.js 18 or higher  
- MongoDB (local or MongoDB Atlas)  
- Git  
- (Optional) Gmail account for Nodemailer

### Steps

# 1. Clone the repository  
   ```bash
   git clone https://github.com/CitenBox/mern-blog-v2.git
   cd mern-blog-v2

---


```

# 2. client side installation
cd Frontend
npm install
npm start

# 3. server side installation
cd ../Backend
npm install

# create a config.env in the config folder
NODE_ENV=development
PORT=5000
URI=http://localhost:3000
MONGO_URI=mongodb://127.0.0.1:27017/mern-blog
JWT_SECRET_KEY=your_secret_key
JWT_EXPIRE=60m
RESET_PASSWORD_EXPIRE=3600000

# Optional:
SMTP_HOST=smtp.gmail.com
SMTP_PORT=587
EMAIL_USERNAME=example@gmail.com
EMAIL_PASS=your_app_password

# start the server
npm start

---

# System Architecture
## Frontend (React)

    Home page

    Login/Registration page

    Create post

    Edit post

    Comment on posts

## Backend (Express)

    User management

    Post management

    Comment handling

    Email delivery

## Database (MongoDB)

    User data

    Posts

    Comments

    Reading List information

## Security

    JWT-based authentication

    Password hashing with bcryptjs

---


# Key Features

Registration and login with JWT authentication

Create posts with title, content, and image

Edit and delete posts by the author only

Comment on posts

Reading List to manage favorite content

Image uploads to the server

Responsive and clean design

Rich text editing with CKEditor

Error handling and smooth user experience
