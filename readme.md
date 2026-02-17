

## 🧪 Environment Setup

### 📁 Backend (`/backend`)
Create a `.env` file inside the `/backend` directory:

```env
PORT=5001
MONGO_URI=your_mongo_uri
STEAM_API_KEY=your_steam_api_key
STEAM_API_SECRET=your_steam_api_secret
JWT_SECRET_KEY=your_jwt_secret
NODE_ENV=development
```
### 📁 Frontend (/frontend)

Create a `.env` file inside the `/frontend` directory:
VITE_STREAM_API_KEY=your_stream_api_key
```env
VITE_STREAM_API_KEY=your_stream_api_key
```

### 🔧 Getting Started
### 🚀 Run Backend
```bash
cd backend
npm install
npm run dev
```

### 💻 Run Frontend
```bash
cd frontend
npm install
npm run dev
```
### 📁 Tech Stack

📦 Frontend     → React, Vite, TailwindCSS

🛠️ Backend      → Node.js, Express, MongoDB

⚡ Realtime     → Stream API

🔁 Data Fetch   → TanStack Query (React Query)

🔐 Auth         → JWT (JSON Web Tokens)

