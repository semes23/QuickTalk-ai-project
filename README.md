## QuickTalk: Instant Communication Platform

🚀 **QuickTalk** is a contemporary real-time chat solution, developed using the MERN stack, WebSockets, and JSON Web Token (JWT) authentication. It offers effortless communication through immediate messaging, secure user verification, and an intuitive user interface.

## 🌐 Live Application Preview

🔗 [Experience QuickTalk Live\!](https://quicktalk-frontend.onrender.com)

## 📌 Core Capabilities

✅ **Live Messaging** – Provides instant chat functionality via WebSockets.
✅ **Secure User Access** – Implements robust login and registration processes with JWT.
✅ **Direct Conversations** – Supports private one-on-one chat between users.
✅ **Modern User Interface** – Crafted with React, styled using Tailwind CSS and DaisyUI.
✅ **Email Notifications** – Facilitates password resets through NodeMailer.

-----

## 🛠 Technology Stack

### **Client-Side:**

  - React.js
  - TailwindCSS + DaisyUI

### **Server-Side:**

  - Node.js
  - Express.js
  - MongoDB (via Mongoose ODM)

### **Additional Technologies:**

  - WebSockets (Socket.io for real-time communication)
  - JWT (for authentication and authorization)
  - NodeMailer (for sending password reset emails)

-----

## ⚡ Setup Guide

### **1️⃣ Obtain the Codebase**

```bash
 git clone "respository-link"
 cd quicktalk
```

### **2️⃣ Install Project Dependencies**

#### **Backend Setup**

```bash
 cd backend
 npm install
```

#### **Frontend Setup**

```bash
 cd frontend
 npm install
```

### **3️⃣ Configure Environment Variables**

Create a `.env` file within the `backend` directory and populate it with the following:

```env
BASE_URL=your_frontend_url
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
FRONTEND_URL=your_frontend_url
JWT_SECRET=your_jwt_secret
MONGODB_URI=your_mongodb_connection_string
NODE_ENV=your_node_environment
PORT=your_backend_port
SMTP_EMAIL=your_smtp_email
SMTP_HOST=your_smtp_host
SMTP_PASS=your_smtp_password
SMTP_PORT=your_smtp_port
SMTP_USER=your_smtp_user
```

Create a `.env` file within the `frontend` directory and add:

```env
BASE_URL=your_backend_url
```

### **4️⃣ Launch the Application**

#### **Backend Execution**

```bash
 npm run dev
```

#### **Frontend Execution**

```bash
 npm run dev
```

### **5️⃣ Access QuickTalk**

Navigate to `http://localhost:[PORT]` in your web browser to start using the application.

-----

## 🎯 Planned Enhancements

🚀 **Video & Voice Communication** – Integration of WebRTC for richer interactions.
🚀 **File Sharing Functionality** – Ability to upload and exchange images and documents.
🚀 **End-to-End Encryption** – Implementing enhanced security for all chat messages.

-----

## 🛠 Contributing to QuickTalk

We welcome and appreciate contributions\! Please follow these steps to contribute:

1.  Fork the repository and clone it to your local machine.
2.  Create a new feature branch: `git checkout -b your-feature-name`
3.  Commit your changes with a clear message: `git commit -m 'Implement new feature'`
4.  Push your branch to your forked repository: `git push origin your-feature-name`
5.  Submit a pull request to the main repository 🚀

