# 💼 Portfolio Backend (Node.js + Express)

This is the backend for my personal portfolio website. It handles API requests, contact form submissions, and database operations.

---

## 🚀 Features

* 📩 Contact form API (stores messages in database)
* 🔐 Secure backend with middleware (Helmet, Rate Limiting)
* 🌐 CORS enabled for frontend integration
* 🛢️ MySQL database integration
* ⚡ REST API built with Express.js

---

## 🛠️ Tech Stack

* Node.js
* Express.js
* MySQL
* dotenv
* express-validator
* helmet
* cors

---

## 📁 Project Structure

```
portfolio/
│
├── controllers/
├── middleware/
├── routes/
├── public/
├── db.js
├── server.js
├── package.json
└── .env (not included)
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the repository

```
git clone https://github.com/Jaya-lakshmi21/Portfolio.git
cd Portfolio
```

---

### 2️⃣ Install dependencies

```
npm install
```

---

### 3️⃣ Create `.env` file

Create a `.env` file in the root folder and add:

```
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=yourpassword
DB_NAME=yourdbname
PORT=5000
```

---

### 4️⃣ Run the server

```
npm start
```

Server will run on:

```
http://localhost:5000
```

---

## 📡 API Endpoints (Example)

* `POST /api/contact` → Submit contact form
* `GET /api/...` → Other routes

---

## 🔐 Security Notes

* `.env` file is ignored using `.gitignore`
* Sensitive data is not exposed

---

## 👩‍💻 Author

**Jaya Lakshmi**
📎 GitHub: https://github.com/Jaya-lakshmi21

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
