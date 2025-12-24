CodeMate – Realtime Collaborative Code Editor

CodeMate is a real-time collaborative code editor that allows multiple users to write, edit, and view code together in the same room. It supports live code synchronization, multiple programming languages, theme customization, and room-based collaboration, similar to tools like CodeSandbox or Replit.


🧠 Features

🔴 Real-time Code Collaboration (Socket.IO)

👥 Multiple Users in a Room

🆔 Create & Join Rooms using Room ID

📋 One-click Copy Room ID

🎨 Multiple Editor Themes

💻 Multiple Programming Languages Support

🧑‍💻 Live Connected Users List

🚪 Leave Room Functionality

🌙 Dark IDE-style UI



🛠️ Tech Stack
Frontend

React.js

CodeMirror / Monaco Editor

CSS (Flexbox)

React Router

Backend

Node.js

Express.js

Socket.IO

📸 Project UI
🔹 Landing Page

Center-aligned card UI

Input for Room ID and Username

Join existing room or create a new room

🔹 Editor Page

Left sidebar for controls & connected users

Right section for live code editor

Language & theme selector

Copy Room ID button

🔄 How It Works

User enters username and room ID or creates a new room

Socket.IO establishes a real-time connection

Code changes are instantly broadcast to all users in the room

Theme and language changes sync across users

Connected users list updates in real time
