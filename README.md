# DevRoom 🚀

### Real-Time Collaborative Coding Platform for Developers

DevRoom is a full-stack collaborative coding platform that enables developers to create coding rooms, write and execute code in real time, communicate instantly, and collaborate seamlessly. It is designed to simulate a modern developer workspace with secure authentication, live code execution, and real-time interaction.

---

## 📌 Overview

Modern software development often requires real-time collaboration, quick code testing, and smooth communication between team members. DevRoom addresses this by providing a platform where multiple developers can collaborate in coding rooms, execute code instantly, and interact through real-time communication channels.

This project demonstrates full-stack engineering concepts including scalable backend architecture, secure authentication, real-time communication, API integrations, and cloud database management.

---

## ✨ Key Features

* 🔐 **Secure Authentication**

  * JWT-based authentication
  * Google OAuth login integration
  * Protected routes and session management

* 👨‍💻 **Real-Time Collaborative Coding**

  * Create and join coding rooms
  * Collaborate with multiple users simultaneously
  * Real-time code synchronization using Socket.io

* ⚡ **Live Code Execution**

  * Execute code instantly using Judge0 API
  * Supports multiple programming languages
  * Fast response and output rendering

* 💬 **Real-Time Communication**

  * Live chat for room participants
  * Instant event broadcasting with Socket.io

* 🌦 **Weather API Integration**

  * External API integration for dynamic data fetching
  * Demonstrates third-party service handling

* ☁ **Cloud Database**

  * MongoDB Atlas for scalable cloud storage
  * User, room, and session data persistence

* 📱 **Responsive UI**

  * Optimized for desktop and mobile
  * Smooth and modern user experience

---

# 🏗 System Architecture

## Frontend

Responsible for UI rendering, user interaction, authentication flows, and API communication.

### Technologies Used

* React.js
* JavaScript
* Axios
* Socket.io Client
* CSS / Tailwind (if applicable)

---

## Backend

Handles business logic, authentication, room management, and real-time communication.

### Technologies Used

* Node.js
* Express.js
* Socket.io
* JWT
* REST APIs

---

## Database

* MongoDB Atlas

---

## External Services / APIs

* Google OAuth API
* Judge0 API
* OpenWeather API

---

# 🛠 Tech Stack Summary

| Layer                   | Technologies                |
| ----------------------- | --------------------------- |
| Frontend                | React.js, JavaScript, Axios |
| Backend                 | Node.js, Express.js         |
| Database                | MongoDB Atlas               |
| Authentication          | JWT, Google OAuth           |
| Real-Time Communication | Socket.io                   |
| Code Execution          | Judge0 API                  |
| Deployment              | Vercel / Render             |

---

# 📂 Project Structure

```bash
DevRoom/
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── App.js
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── sockets/
│   └── server.js
│
├── package.json
└── README.md
```

---

# ⚙ Installation & Setup

## 1. Clone Repository

```bash
git clone <repository-url>
cd DevRoom
```

---

## 2. Backend Setup

```bash
cd backend
npm install
```

Create `.env` file:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
GOOGLE_CLIENT_ID=your_google_client_id
JUDGE0_API_KEY=your_api_key
CLIENT_URL=http://localhost:3000
```

Run backend:

```bash
npm start
```

---

## 3. Frontend Setup

```bash
cd frontend
npm install
npm start
```

---

# 🔒 Security Features

* Password protection
* JWT token verification
* Secure API routes
* Protected room access
* OAuth authentication support

---

# 🚀 Performance Highlights

* Optimized API calls
* Efficient socket event handling
* Low-latency room communication
* Scalable MongoDB storage
* Clean modular architecture

---

# 📈 Learning Outcomes

This project helped strengthen expertise in:

* Full-stack application development
* REST API design
* Authentication and authorization
* Real-time systems using WebSockets
* Cloud database integration
* Scalable project architecture
* Production deployment workflows

---

# 🔮 Future Enhancements

* 🎥 Video conferencing
* 🤖 AI-powered coding assistant
* 📝 Code history/versioning
* 🏆 Competitive coding mode
* 📊 Analytics dashboard
* 🎙 Voice collaboration

---

# 👨‍💻 Author

## Ayush Yadav

B.Tech — Computer Science & Engineering (Data Science)
SRM Institute of Science and Technology

GitHub: https://github.com/ay001-web

