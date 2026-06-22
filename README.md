# 💬 Real-time Chat App - Backend

Node.js + Express + Socket.io + MongoDB backend for the Real-time Chat Application.

## 🌐 Live API
[https://realtime-chat-app-server-gpvv.onrender.com](https://realtime-chat-app-server-gpvv.onrender.com)

## 🛠️ Tech Stack
| Technology | Purpose |
|---|---|
| Node.js | Runtime environment |
| Express | REST API framework |
| Socket.io | Real-time communication |
| MongoDB + Mongoose | Database |
| JWT | Authentication |
| bcrypt | Password hashing |

## 📡 API Routes
| Method | Route | Description |
|---|---|---|
| POST | /api/auth/register | Register new user |
| POST | /api/auth/login | Login user |
| GET | /api/rooms | Get all rooms |
| POST | /api/rooms | Create a room |
| POST | /api/rooms/verify | Verify room password |
| PUT | /api/messages/:id | Edit a message |
| DELETE | /api/messages/:id | Delete a message |

## 💻 Run Locally

```bash
npm install
```

Create a `.env` file:
```env
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
CLIENT_URL=http://localhost:5173
```

```bash
npm run dev
```

## 👩‍💻 Developer
**Gayatri Deshaveni**
- GitHub: [@GayathriDeshaveni](https://github.com/GayathriDeshaveni)
