## 💬 Real-Time Chat App
A simple real-time chat application built with HTML, CSS, JavaScript, WebSockets, and Express.js. This app enables multiple users to join a chat room and exchange messages in real time via WebSockets.

## 🛠️ Tech Stack
- Frontend: HTML, CSS, JavaScript
- Backend: Node.js, Express.js
- Real-time Communication: Socket.IO
- Database: LokiJS

## 🚀 Features
- Real-time messaging using WebSockets
- Simple and responsive front-end using HTML/CSS/JS
- User join and disconnect notifications
- Login page for custom usernames
- Light mode and Dark mode toggle button
- Chat message persistence in between reloads and server restarts

## ℹ️ Notes
- Usernames must be unique. The app prevents duplicate names on login.
- Messages are stored using LokiJS and will persist even after server restarts.
- To delete all messages, click the delete button (trash icon) on the chat page.

## ⚙️ Installation
1. Clone the repository

```bash
git clone https://github.com/rip-super/real-time-chat-app.git
cd real-time-chat-app
```

2. Install dependencies

```bash
npm install
```
3. Start the server

```bash
npm start
```

4. Go to http://localhost:8000
