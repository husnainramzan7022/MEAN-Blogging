## Blogging Platform - Share Your Thoughts with the World

This Blogging Platform is a MEAN stack web application designed for writers, tech enthusiasts, and businesses to share and engage in meaningful discussions. The application is built using MongoDB, Express.js, Angular, and Node.js, offering a seamless experience for users.

## Overview

Social media and blogging play an increasingly significant role in the digital world, allowing individuals and organizations to share ideas, build audiences, and grow brands. However, many users struggle with content discoverability and effective audience engagement.

This blogging platform solves these challenges by providing a focused, user-friendly interface where writers can publish content, readers can interact, and businesses can promote relevant content efficiently.

## Features

### 🌍 Application Features:

🎨 Single-page web application with a responsive navbar

🔄 Full CRUD capabilities with a RESTful API

🛡️ Secure MongoDB database with restrictions and validation

🔒 Encrypted passwords for enhanced security

📱 Fully responsive UI adapting to all screen sizes

🔍 SEO-friendly URL structures for better discoverability

📜 Server logging system for tracking activities

### 👥 User Features:

🔑 Register/Login accounts

✅ Stay logged in using local storage

🔓 Log out securely

✍️ Create, edit, and delete blog posts

💬 Comment on posts and engage with other users

📌 Save favorite articles for later reading

🔔 Follow favorite authors and receive updates

## Tech Stack

### Frontend:

Angular 6

TypeScript

Bootstrap

Angular CLI

### Backend:

Node.js

Express.js

MongoDB

JSON Web Token (JWT)

bcrypt for password encryption

## ScreenShots

### SignUp

![Screenshot (63)](https://github.com/user-attachments/assets/8db7b536-c40d-42fb-ad91-c151cbd5de8b)

### Login

![Screenshot (62)](https://github.com/user-attachments/assets/5af5a4ef-f125-4a8a-b432-fa2e85b803ca)

### HomePage

![homepage](https://github.com/user-attachments/assets/ac20dffa-187c-4ead-8538-946288a15bb1)

### Profile

![myprofile](https://github.com/user-attachments/assets/c1f9496c-8751-4e34-b354-c0582c7d9b25)

### Article

![addarticle](https://github.com/user-attachments/assets/14f6fab1-5d16-41ae-ad8a-d6a48f2c1837)

## Installation & Setup

### Clone the Repository

git clone https://github.com/your-username/blogging-platform.git
cd blogging-platform

### Backend Setup

cd server
npm install

### Create a .env file in the server directory and add:

MONGO_URI=your-mongodb-url
JWT_SECRET=your-jwt-secret

### Start the backend:

npm start

### Frontend Setup

cd client
npm install

### Configure API base URL in /client/src/environments/environment.ts.

### Start the frontend:

ng serve

## License

This project is open-source and available under the MIT License.
