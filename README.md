# InstaClone – Full‑Stack Social Media Application

InstaClone is a **production‑ready full‑stack social media application** inspired by Instagram, developed using the **MERN (MongoDB, Express.js, React, Node.js) stack**. The project demonstrates practical implementation of modern web development concepts, RESTful API design, authentication, media handling, and scalable backend architecture.

This project has been developed as part of hands‑on learning and is suitable for **technical evaluation, internships, and entry‑level software development roles**.

---

## Key Features

### Authentication & Authorization

* Secure user registration and login
* JWT‑based authentication
* Role‑protected and user‑specific routes

### User Profiles

* View and manage user profiles
* Personalized user data handling

### Posts & Engagement

* Create and delete posts
* Image upload support
* Like and comment functionality

### Messaging System

* One‑to‑one user conversations
* Conversation and message persistence using MongoDB

### Media Handling

* Image uploads using Multer
* Secure file storage and access

---

## Technology Stack

### Frontend

* React (Vite)
* Tailwind CSS
* JavaScript (ES6+)

### Backend

* Node.js
* Express.js
* MongoDB with Mongoose
* JSON Web Tokens (JWT)
* Multer (media uploads)

---

## Project Structure

```
instaclone-main/
│
├── backend/
│   ├── controllers/      # Request handling logic
│   ├── middlewares/      # Authentication & validation middleware
│   ├── models/           # Mongoose schemas
│   ├── routes/           # API routes
│   └── index.js          # Server entry point
│
├── frontend/
│   ├── src/              # React components & pages
│   ├── public/           # Static assets
│   └── vite.config.js
│
├── package.json
└── README.md
```

---

## Installation & Setup

### Prerequisites

* Node.js (v18 or higher recommended)
* MongoDB (local or cloud)

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/instaclone.git
cd instaclone-main
```

### Step 2: Backend Setup

```bash
cd backend
npm install
npm start
```

Create a `.env` file inside the `backend` directory:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

### Step 3: Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

The application will be available at:

* Frontend: `http://localhost:5173`
* Backend API: `http://localhost:5000`

---

## API Overview

* `/api/users` – Authentication and user management
* `/api/posts` – Post creation, likes, and comments
* `/api/conversations` – User conversations
* `/api/messages` – Messaging functionality

---

## Code Quality & Best Practices

* Modular folder structure
* RESTful API design
* Middleware‑based authentication
* Secure environment variable handling
* Clean and readable codebase

---

## Future Enhancements

* Real‑time messaging using WebSockets / Socket.IO
* Follow and unfollow system
* Notifications module
* Story feature
* Deployment with CI/CD pipeline

---

## Author

**Aryan Mishra**
B.Tech – Computer Science & Engineering (AI & ML)
