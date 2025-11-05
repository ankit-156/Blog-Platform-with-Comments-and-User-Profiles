# Fullstack Blog Platform

This zip contains both frontend (React) and backend (Node.js + Express + MongoDB) with Socket.IO for realtime comments/posts.

## Quick start

1. Start backend:
```
cd backend
npm install
cp .env.example .env   # then edit .env to add MONGO_URI and JWT_SECRET
npm run dev
```

2. Start frontend (in a separate terminal):
```
cd frontend
npm install
npm start
```

Frontend expects `REACT_APP_API_URL` to point to the backend (default http://localhost:5000).
