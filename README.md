# 🚀 Express.js + TypeScript + PostgreSQL REST API

Hi there it's habib, In here I try 
A scalable RESTful API built with **Express.js**, **TypeScript**, and **PostgreSQL**. This project demonstrates CRUD (Create, Read, Update, Delete) operations using a clean and modular architecture.

---

## ✨ Features

- 🚀 Express.js with TypeScript
- 🐘 PostgreSQL Database
- 📦 CRUD Operations
- 🔒 Environment Variable Support
- 🛡️ Centralized Error Handling
- 📁 Modular Folder Structure
- ⚡ TypeScript Strict Mode
- 🔄 Hot Reload During Development
- 📈 Easy to Scale and Maintain

---

## 🛠️ Tech Stack

- Node.js
- Express.js
- TypeScript
- PostgreSQL
- pg (PostgreSQL Client)
- dotenv
- Nodemon / ts-node-dev


## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/Habibullah-KH/expressTs-server
```

Move into the project

```bash
cd project-name
```

Install dependencies

```bash
npm install
```

---

## 🔑 Environment Variables

Create a `.env` file in the project root.

```env
PORT=5000

CONNECTION_STRING://username:password@localhost:5432/database_name

NODE_ENV=development
```

---

## ▶️ Run the Project

Development

```bash
npm run dev
```

Build

```bash
npm run build
```

Production

```bash
npm start
```

---

## 📡 API Endpoints

### Create

```http
POST /api/users
```

### Get All

```http
GET /api/users
```

### Get Single

```http
GET /api/users/:id
```

### Update

```http
PATCH /api/users/:id
```

### Delete

```http
DELETE /api/users/:id
```

---

## 🗄️ PostgreSQL

This project uses PostgreSQL as the primary database.

Example table:

```sql
CREATE TABLE users (
    id SERIAL PRIMARY KEY,
    name VARCHAR(100) NOT NULL,
    email VARCHAR(150) UNIQUE NOT NULL,
    age INTEGER,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);
```

---

## 📜 Available Scripts

```bash
npm run dev
npm run build
npm start
```

---

## 📌 Example Response

```json
{
  "success": true,
  "message": "User created successfully",
  "data": {
    "id": 1,
    "name": "John Doe",
    "email": "john@example.com"
  }
}
```

---

## 🚀 Future Improvements

- Authentication (JWT)
- Input Validation
- Pagination
- Search & Filtering
- Docker Support
- Unit Testing
- Swagger API Documentation

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

---

## 👨‍💻 Author

**Habibullah Khondokar**

- GitHub: [https://github.com/Habibullah-KH](https://github.com/Habibullah-KH/expressTs-server.git)
