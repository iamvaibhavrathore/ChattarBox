<img width="1440" alt="chatterBox" src="https://github.com/user-attachments/assets/23cbfd02-a30e-4fbc-8980-889f425fc27f">

---

Fork - https://github.com/iamvaibhavrathore/ChattarBox.git

# ChatterBox

Welcome to **ChatterBox**! This is a full-featured chat application built with modern web technologies. Whether you're looking to chat via text, image, or share documents, ChatterBox has you covered.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation Guide](#installation-guide)
- [Environment Variables](#environment-variables)
- [Usage](#usage)
- [Contributing](#contributing)

## Overview

ChatterBox is designed to provide a seamless and engaging real-time communication experience. It leverages the power of **React** for the frontend, **Socket.io** for real-time communication, **Node.js** for the backend, **Redux-Toolkit** for state management, and **MongoDB** for data persistence.

## Features

- **Real-Time Messaging**: Chat instantly with friends or colleagues in real-time.
- **Video Communication**: Connect face-to-face with built-in video calling.
- **File Sharing**: Easily share documents and files within the chat.
- **Group Chats**: Create and participate in group conversations.
- **User Authentication**: Secure login and registration system.
- **Persistent Conversations**: Access past chats anytime with stored chat history.
- **Responsive Design**: Fully optimized for both mobile and desktop platforms.

## Technology Stack

- **Frontend**: React, Redux-Toolkit
- **Backend**: Node.js, Express.js
- **Real-Time Communication**: Socket.io
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT)
- **State Management**: Redux-Toolkit

## Installation Guide

Feel free to modify this format to suit your project's needs!

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/chatterbox.git
   ```

2. **Install Dependencies:**
   - Server-side:
     ```bash
     cd chatterbox/server
     npm install
     ```
   - Client-side:
     ```bash
     cd chatterbox/client
     npm install
     ```

3. **Set Up Environment Variables:**  
   Create a `.env` file in the `server` directory with the following variables:

   ```
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

4. # Server .env file

  FRONTEND_URL = <Frontend URL>
  MONGODB_URI  = <Mongodb URI>
  JWT_SECREAT_KEY = <JWT Secreat Key>

5. client .env file

  REACT_APP_CLOUDINARY_CLOUD_NAME = <Cloudinary cloud name>
  REACT_APP_BACKEND_URL = <Backend URL>

4. **Run the Application:**
   - Start the server:
     ```bash
     cd server
     npm start
     ```
   - Start the client:
     ```bash
     cd ../client
     npm start
     ```

   The server will be available at `http://localhost:5000/` and the client at `http://localhost:3000/`.

## Usage

Once the application is running, you can:
- Register a new account or log in with an existing one.
- Start a new chat, join group conversations, or initiate a video call.
- Share documents or other files directly within the chat interface.

## Contributing

We welcome contributions to ChatterBox! If you'd like to contribute:
1. Fork the repository.
2. Create a new feature branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.


---










