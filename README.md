# 💬 Messaging App

A real-time messaging application built with **React Native** for the mobile frontend and **Node.js** with **Socket.io** for the backend. This project is a great starting point for understanding how real-time communication works using modern web and mobile technologies.

---

## 🚀 Features

- 🔁 Real-time messaging using Socket.io
- 📱 React Native mobile app (Expo-compatible)
- 🌐 Node.js backend with Express server
- 💡 Clean, modular, and scalable architecture
- 🔧 Easy to extend with authentication and database support (MongoDB, Firebase, etc.)

---

## 🧱 Project Structure

```
messaging-app/
├── frontend/          # React Native mobile app
│   ├── App.js         # Entry point of the app
│   ├── socket.js      # Socket.io client
│   └── screens/
│       └── ChatScreen.js
│
├── backend/           # Node.js + Express + Socket.io server
│   ├── server.js      # Main server file
│   ├── routes/        # Placeholder for REST routes
│   ├── controllers/   # Placeholder for route logic
│   └── models/        # Placeholder for DB models
│
├── .gitignore
├── LICENSE
└── README.md
```

---

## 🛠️ Installation & Running Locally

### 🔙 Backend Setup

1. Navigate to the backend folder:

```bash
cd backend
```

2. Install dependencies:

```bash
npm install
```

3. Start the backend server:

```bash
node server.js
```

The backend will run on `http://localhost:5000`.

### 📲 Frontend Setup

1. Navigate to the frontend folder:

```bash
cd frontend
```

2. Install dependencies:

```bash
npm install
```

3. Start the React Native app (Expo):

```bash
npx expo start
```

Use an emulator or Expo Go on your mobile device to test the app.

---

## 🌐 Tech Stack

### Frontend:
- React Native (Expo)
- React Navigation
- Socket.io-client

### Backend:
- Node.js
- Express.js
- Socket.io

---

## 🧩 Future Improvements

- ✅ Add authentication (JWT, OAuth)
- ✅ Add persistent storage using MongoDB or Firebase
- ✅ Add chat rooms and private messaging
- ✅ Integrate push notifications
- ✅ UI improvements and message timestamps

---

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## 👨‍💻 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 🤝 Acknowledgements

Inspired by the need for simple, extensible chat apps in modern mobile development.


