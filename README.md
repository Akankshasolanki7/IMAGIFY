
---

# IMAGIFY

**IMAGIFY** is a full-stack AI-powered web application that enables users to generate high-quality images from textual descriptions. Built with the MERN stack (MongoDB, Express.js, React.js, Node.js), it leverages the Clipdrop API for image generation.

## 🚀 Live Demo

Experience the application live at: [imagify-one-dun.vercel.app](https://imagify-one-dun.vercel.app)

## 🧠 Features

* **AI-Based Image Generation**: Utilizes the Clipdrop API to create images from user-provided text prompts.
* **User Authentication**: Secure login and signup functionalities.
* **Modern UI**: Clean and user-friendly interface.
* **Full-Stack Integration**: Seamless interaction between frontend and backend components.

## 🛠️ Tech Stack

* **Frontend**: React.js, Vite, Tailwind CSS
* **Backend**: Node.js, Express.js
* **Database**: MongoDB
* **AI Integration**: Clipdrop API
* **Deployment**: Vercel

## 📁 Project Structure

```
IMAGIFY/
├── client/          # React frontend
│   ├── public/
│   └── src/
├── server/          # Express backend
│   ├── controllers/
│   ├── models/
│   └── routes/
├── .gitignore
├── README.md
└── package.json
```

## ⚙️ Installation

### Prerequisites

* Node.js and npm installed
* MongoDB database
* Clipdrop API key

### Backend Setup

1. **Navigate to the server directory**:

   ```bash
   cd server
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Configure environment variables**: Create a `.env` file in the `server` directory with the following variables:

   ```env
   MONGODB_URI=<your-mongodb-connection-string>
   JWT_SECRET=<your-jwt-secret>
   CLIPDROP_API=<your-clipdrop-api-key>
   ```

4. **Start the backend server**:

   ```bash
   npm run server
   ```

### Frontend Setup

1. **Navigate to the client directory**:

   ```bash
   cd ../client
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Configure environment variables**: Create a `.env` file in the `client` directory with the following variable:

   ```env
   VITE_BACKEND_URL=<your-backend-url>
   ```

4. **Start the frontend development server**:

   ```bash
   npm run dev
   ```

## 📄 Environment Variables Summary

### Server (`server/.env`)

* `MONGODB_URI`: MongoDB connection string.
* `JWT_SECRET`: Secret key for JSON Web Token.
* `CLIPDROP_API`: API key for the Clipdrop API.

### Client (`client/.env`)

* `VITE_BACKEND_URL`: URL of the backend server.


