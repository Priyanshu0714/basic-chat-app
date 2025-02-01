# Basic Chat App(in-progress)

A global real-time chat application built using **Socket.io**, allowing users to communicate instantly.

## Features
- Global chat functionality
- Real-time messaging using **Socket.io**
- Simple UI for easy communication

## Technologies Used
- **Node.js** (Backend)
- **Express.js** (Server)
- **Socket.io** (WebSockets for real-time chat)
- **HTML, CSS, JavaScript** (Frontend)

## Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/Priyanshu0714/chat-app.git
   cd chat-app
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Run the server:**
   ```sh
   node server.js
   ```

4. **Open the app in your browser:**
   ```sh
   http://localhost:3000
   ```

## How It Works
1. A user joins the chat and gets connected via **WebSockets**.
2. Messages sent by one user are broadcasted in real time to all users.
3. The chat updates instantly without refreshing the page.

## Future Improvements
- Private chat rooms
- User authentication
- Message history storage using a database

## Contributing
If you'd like to contribute, feel free to fork the repository and submit a pull request!

---
Developed by **Priyanshu Choudhary**
