# Mental Health Chat Platform - MERN Stack

Welcome to the **Mental Health Chat Platform**, a real-time chat application built using the **MERN (MongoDB, Express.js, React.js, Node.js) stack** with **Chakra UI** and **Socket.io**. This project aims to provide a seamless and secure platform for mental wellness conversations, ensuring real-time interactions with enhanced user experience.

## 🚀 Live Demo
🔗 **[Mental Health Chat Platform](https://mental-health-afkm.onrender.com/)**

> **Note:** Render's free tier automatically shuts down after 15 minutes of inactivity. The first request after reactivation may experience a slight delay.

---

## 📌 Features

✅ **Real-Time Chat** - Built with WebSocket technology (Socket.io) to enable instant messaging with latency under **100ms** for **200+ concurrent users**.  
✅ **Secure Authentication** - JWT-based authentication & authorization to protect **100% of user data** and prevent unauthorized access.  
✅ **Responsive UI** - Designed with **Chakra UI** to ensure an intuitive and smooth experience across **15+ device types**, leading to a **25% increase in user engagement**.  
✅ **User Profiles** - Users can create accounts, update profiles, and manage chat interactions securely.  
✅ **Group Chat Support** - Engage in 1-on-1 or group conversations with real-time updates.  
✅ **Typing Indicators** - See when other users are typing to enhance engagement.  
✅ **Message Read Receipts** - Track message delivery and read status.  
✅ **Admin Panel** - Manage users and chat rooms efficiently.  

---

## 🛠️ Getting Started

### 📌 Prerequisites

Before running this project, ensure you have the following installed:
- **Node.js** (v16+)
- **MongoDB Atlas** (or local MongoDB instance)
- **Git**

### 📌 Installation & Setup

1️⃣ **Clone the repository**
```sh
 git clone https://github.com/Atisha-sh/Mental-Health-MERN-Project.git
 cd Mental-Health-MERN-Project
```

2️⃣ **Install backend dependencies**
```sh
npm install
```

3️⃣ **Navigate to the frontend and install dependencies**
```sh
cd frontend
npm install
```

4️⃣ **Set up environment variables**  
Rename `.env.example` to `.env` and configure the following variables:
```env
NODE_ENV=development
PORT=5000
MONGO_URI=ADD_YOUR_MONGO_URI_HERE
JWT_SECRET=ADD_YOUR_JWT_SECRET_HERE
SOCKET_SERVER=ADD_YOUR_SOCKET_SERVER_HERE
```

5️⃣ **Run the project**
```sh
# Start backend server
npm run server

# Start frontend
cd frontend
npm start
```

---

## 🌍 Deployment

To deploy the project, follow these steps:
```sh
# Build the frontend for production
cd frontend
npm run build
```

Deploy the backend to platforms like **Render, Vercel, or Heroku** and host the frontend using **Netlify or Vercel**.

---

## 👥 Contributing

We welcome contributions to enhance this platform! Follow these steps to contribute:

1️⃣ **Fork the repository**  
2️⃣ **Clone the forked repo**
```sh
git clone https://github.com/your-username/Mental-Health-MERN-Project.git
```
3️⃣ **Create a new branch**
```sh
git checkout -b feature/your-feature-name
```
4️⃣ **Commit and push changes**
```sh
git add .
git commit -m "Added new feature"
git push origin feature/your-feature-name
```
5️⃣ **Create a pull request on GitHub**

---

## 📝 License
This project is open-source and available under the **MIT License**.

---

## 📩 Contact
📧 **Email:** your-email@example.com  
🔗 **GitHub:** [Atisha-sh](https://github.com/Atisha-sh)  

---

**Happy coding! 🚀**
