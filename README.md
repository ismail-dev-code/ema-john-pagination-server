# 🌐 Ema-John Server

This is the backend server for the **Ema-John** e-commerce platform. It is built with **Express.js**, uses **MongoDB** for data storage, and supports **JWT authentication** and **CORS** for secure cross-origin requests.

---

## 🚀 Features

- ⚙️ Express.js server
- 🌍 CORS enabled for client-server communication
- 🔐 JSON Web Token (JWT) based authentication
- 🛢️ MongoDB for persistent data storage
- 🔐 Environment variable support with `dotenv`

---

## 🧰 Tech Stack

- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Token (JWT)
- **Environment Configuration**: dotenv

---

## 📦 Installation

```bash
git clone https://github.com/your-username/ema-john-server.git
cd ema-john-server
npm install
```

---

## ▶️ Running the Server

Before running the server, create a `.env` file in the root directory with the following content:

```env
PORT=5000
DB_URI=your_mongodb_connection_string
ACCESS_TOKEN_SECRET=your_jwt_secret
```

Then start the server:

```bash
npm start
```

The server will run on [http://localhost:5000](http://localhost:5000) by default.

---

## 📁 Project Structure

```
ema-john-server/
├── index.js
├── .env
├── package.json
└── node_modules/
```

---

## 📑 Dependencies

- **express** `^4.21.2` – Web framework for Node.js  
- **cors** `^2.8.5` – Middleware for enabling CORS  
- **dotenv** `^16.5.0` – Loads environment variables from `.env`  
- **jsonwebtoken** `^9.0.2` – JWT token creation and verification  
- **mongodb** `^5.9.2` – MongoDB native driver for Node.js  

---

## 🔐 Environment Variables

| Variable              | Description                          |
|-----------------------|--------------------------------------|
| `PORT`                | Port number to run the server        |
| `DB_URI`              | MongoDB connection string            |
| `ACCESS_TOKEN_SECRET` | Secret key for signing JWT tokens    |

---

## 📜 License

This project is for educational purposes and does not include any license by default.

---
