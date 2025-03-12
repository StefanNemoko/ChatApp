# Real-Time Chat App (Rust + Tokio + React Native + Expo)

## **Tech Stack**

### **Backend (Rust + Tokio + Axum)**
- **Tokio**: Async runtime for handling multiple chat clients.
- **Axum**: Web framework for handling HTTP/WebSocket routes.
- **Tungstenite/Tokio-Tungstenite**: WebSocket library for real-time communication.
- **Redis (optional)**: Store active users and chat history.
- **SQLx/PostgreSQL**: Database for storing messages.

### **Frontend (React Native + Expo)**
- **React Native with Expo**: Cross-platform mobile app.
- **WebSockets**: Real-time communication with the backend.
- **Recoil/Redux**: State management for chat messages.

---

## **Project Roadmap** 🚀

### **1. Setup Rust Backend**
- [ ] Initialize Rust project
- [ ] Install dependencies: `tokio`, `axum`, `tungstenite`, `serde`, `sqlx`
- [ ] Create a **WebSocket endpoint** for real-time chat
- [ ] Store messages in **PostgreSQL**

### **2. Build React Native Frontend**
- [ ] Setup Expo + React Native
- [ ] Create a **chat UI** with message bubbles
- [ ] Connect to the **WebSocket server**
- [ ] Handle **real-time message updates**

### **3. Enhance Features**
- [ ] **User authentication** (JWT-based login)
- [ ] **Typing indicators** (broadcast when user is typing)
- [ ] **Read receipts** (track seen messages)
- [ ] **Push notifications** (Expo Notifications API)

---

## **Next Steps**
- Implement the backend WebSocket server
- Set up the frontend WebSocket connection
- Optimize and test performance

---

### **Want to contribute?**
- Clone the repo and start coding! 🚀
