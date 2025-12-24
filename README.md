# 🚀 CodeMate – Realtime Collaborative Code Editor

CodeMate is a **real-time collaborative code editor** that allows multiple users to write, edit, and view code together in the same room. It supports **live code synchronization**, **multiple programming languages**, **theme customization**, and **room-based collaboration**, similar to tools like CodeSandbox or Replit.

---

## 🧠 Features

- 🔴 Real-time code collaboration using **Socket.IO**
- 👥 Multiple users can join the same room
- 🆔 Create & join rooms using a **Room ID**
- 📋 One-click **Copy Room ID**
- 🎨 Multiple editor themes (Monokai, Dracula, etc.)
- 💻 Multiple programming languages support
- 🧑‍💻 Live connected users list
- 🚪 Leave room functionality
- 🌙 Clean dark IDE-style UI

---

## 🛠️ Tech Stack

### Frontend
- React.js
- CodeMirror / Monaco Editor
- CSS (Flexbox)
- React Router

### Backend
- Node.js
- Express.js
- Socket.IO

---

## 📸 Project UI Overview

### 🔹 Landing Page
- Center-aligned card UI
- Input fields for **Room ID** and **Username**
- Option to join an existing room or create a new room

### 🔹 Editor Page
- Two-part layout:
  - **Left Sidebar**: Connected users, theme & language selector, copy room ID, leave room
  - **Right Section**: Live code editor
- Real-time synchronization across users

---

## 🔄 How It Works

1. User enters a **username** and **room ID** (or creates a new room)
2. Socket.IO establishes a real-time connection with the server
3. Code changes are instantly broadcast to all users in the room
4. Theme and language changes are synchronized in real time
5. Connected users list updates automatically when users join or leave.
