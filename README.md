# 📹 ConvoFy – Video Conferencing App

**ConvoFy** is a modern, full-featured video conferencing web application designed to provide a seamless virtual meeting experience. With real-time video, in-room chat, and screen sharing — all within the browser — ConvoFy focuses on performance, security, and a user-first experience.

---

## 🚀 Features Overview

### 🏗️ Modular Architecture  
- Scalable and maintainable codebase  
- Clear separation between frontend and backend logic  

### 🔐 Authentication & Authorization  
- Secure login and registration  
- JWT-based authentication  
- Role-based route protection using Passport.js  

### ⚠️ Robust Error Handling  
- Unified error management across both client and server  
- Ensures smoother user experience and easier debugging  

---

## ✨ Core Features

### 🔐 User Authentication  
- User registration and login  
- Protected routes with token-based access  

### 📹 Video Conferencing  
- Create or join virtual rooms using unique Room IDs  
- Peer-to-peer video calling powered by WebRTC  
- Real-time signaling with Socket.IO  

### 🗣️ In-Room Chat  
- Instant messaging among participants  
- Live typing indicators and message history  

### 🖥️ Screen Sharing  
- Share your screen with others during a session  

### 🧹 Room & Participant Management  
- Host controls (mute participants, kick users, end session)  
- Automatic cleanup on disconnect or tab close  

---

## 🧰 Tech Stack

### 🖥️ Frontend  
- **React.js** — Component-based UI  
- **Tailwind CSS / CSS Modules** — Styling system  
- **React Router** — Routing management  
- **Axios** — API integration  
- **WebRTC + Socket.IO Client** — Real-time video & chat  

### ⚙️ Backend  
- **Node.js & Express.js** — REST API backend  
- **MongoDB + Mongoose** — NoSQL database and schema modeling  
- **JWT** — JSON Web Token for user authentication  
- **Passport.js** — Authentication strategy manager  
- **Socket.IO** — Real-time WebSocket communication  
- **Bcrypt** — Secure password hashing  

---