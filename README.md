# Chat-App 💬

A full-stack real-time chat application built with the MERN stack (MongoDB, Express.js, React, Node.js). It features secure user authentication, one-on-one messaging, real-time updates using Socket.IO, and a modern responsive UI.

---

## 🌟 Features

* 🔐 **User Authentication**: Signup/Login with JWT-based authentication.
* 💬 **Real-Time Messaging**: One-on-one chat with Socket.IO.
* 👥 **User Search & Selection**: Browse and select users to start chatting.
* 🔔 **Live Typing Indicators** (optional to enable).
* 📸 **Image Upload Support** (Cloudinary integrated).
* 📱 **Responsive UI**: Works well on desktop and mobile screens.

---

## 🛠 Tech Stack

| Layer        | Technologies                     |
| ------------ | -------------------------------- |
| Frontend     | React, Context API, Tailwind CSS |
| Backend      | Node.js, Express.js, Socket.IO   |
| Database     | MongoDB (Mongoose ODM)           |
| Auth         | JWT, Bcrypt                      |
| Cloud Upload | Cloudinary                       |

---

## 📁 Project Structure

```bash
Chat-App/
├── client/                # React Frontend
│   ├── src/
│   │   ├── components/    # UI components
│   │   ├── pages/         # Auth, Home, Profile, Chat
│   │   └── context/       # AuthContext, ChatContext
├── server/                # Express Backend
│   ├── controllers/       # Business logic
│   ├── middleware/        # Auth middlewares
│   ├── models/            # Mongoose models
│   ├── routes/            # API routes
│   └── socket/            # Socket.IO logic
├── .env
├── package.json
└── README.md
```

---

## 🚀 Getting Started

### 🔧 Prerequisites

* Node.js ≥ 16.x
* MongoDB (local or Atlas)
* Cloudinary Account (for image uploads)

### 📦 Installation

1. **Clone the repository**

```bash
git clone https://github.com/akshat-2411/Chat-App.git
cd Chat-App
```

2. **Install server dependencies**

```bash
cd server
npm install
```

3. **Create `.env` file in `/server` directory**

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

4. **Install frontend dependencies**

```bash
cd ../client
npm install
```

5. **Run the application**

```bash
# Start backend
cd ../server
npm run server

# Start frontend
cd ../client
npm run dev
```

Visit: `http://localhost:5173` (Vite dev server)

---

## 📸 Screenshots

![Screenshot (661)](https://github.com/user-attachments/assets/686a48b3-ae3b-4f5f-9100-2dce3c77066e)
![Screenshot (662)](https://github.com/user-attachments/assets/f1490e6d-125e-4cc6-9db9-8c1c7ec36463)
![Screenshot (663)](https://github.com/user-attachments/assets/6aa84f17-9aa7-4ec5-9ab3-e754969977be)
![Screenshot (664)](https://github.com/user-attachments/assets/72aabab1-1d8e-48cb-8bd6-1fc7e7a81d4e)
![Screenshot (665)](https://github.com/user-attachments/assets/64d26b8e-eb87-4e8e-927f-60eb79e17d4b)


---

## 🧪 Future Improvements

* Group Chats & Admin Controls
* Media (video/audio) sharing
* Message Reactions & Emojis
* Message Read/Seen Status
* Deploy with Docker/CI-CD

---

## 📝 License

This project is licensed under the MIT License.
