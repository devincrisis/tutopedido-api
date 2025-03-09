# 📦 Tutopedido-api

## 🚀 Project Overview
This is the backend API for the small business ordering system. It is built using **Node.js** and **Express**, with a **PostgreSQL/MongoDB** database. Orders will be received via WhatsApp and processed through this API.

## 📂 Project Structure
```
backend/
│── src/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── services/
│   ├── middlewares/
│   ├── config/
│   ├── app.js
│   ├── server.js
│── .env.example
│── .gitignore
│── package.json
│── README.md
```

## 🛠️ Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/backend.git
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file based on `.env.example` and configure your database settings.
4. Run the development server:
   ```bash
   npm run dev
   ```

## 📡 API Endpoints (Example)
- `POST /orders` - Receive a new order
- `GET /orders/:id` - Retrieve order details
- `PATCH /orders/:id/status` - Update order status
- `POST /menu` - Add menu items
- `GET /menu` - Retrieve menu items
