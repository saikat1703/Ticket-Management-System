## 📌 Project Overview

This project consists of:

* **Backend** – Node.js + Express server
* **Frontend** – Frontend application (Vite-based setup assumed)

---

# 🚀 Getting Started

## 1️⃣ Clone the Repository

```bash
git clone <repository-url>
cd Qalb-IT-PracticalTask
```

---

# 🖥️ Running the Backend

### Step 1: Navigate to Backend Folder

```bash
cd Backend
```

### Step 2: Install Dependencies

```bash
npm install
```

### Step 3: Start the Server

```bash
nodemon
```

> ✅ The server runs on **[http://localhost:3000](http://localhost:3000)** by default.

---

# 💻 Running the Frontend

### Step 1: Navigate to Frontend Folder

```bash
cd Frontend
```

### Step 2: Install Dependencies

```bash
npm install
```

### Step 3: Start Development Server

```bash
npm run dev
```

---

# 🔐 Environment Variables

Currently, **no environment variables have been configured**.

Example (for future implementation):

```
MONGO_URI=your_mongodb_connection_string
PORT=3000
```

---

# 🗄️ Database Indexing

No database indexing has been applied yet.

> Future Improvement:
> Adding indexes on frequently queried fields (e.g., email, ticketId, createdAt) would improve query performance and scalability.

---

# 🔮 Future Improvements

## 🛠 Backend Improvements

1. Implement proper error handling middleware.
2. Refactor code into a clean folder structure (controllers, routes, models, services).
3. Introduce environment variables using `.env` and `dotenv`.

---

## 🎨 Frontend Improvements

1. Implement proper API error handling.
2. Create remaining pages for Ticket Creation.
3. Improve UI with modern design using Tailwind CSS.

---

# 🧱 Recommended Folder Structure (Backend)

```
Backend/
│── controllers/
│── routes/
│── models/
│── middleware/
│── config/
│── server.js
```

---

# 📦 Tech Stack

* Node.js
* Express.js
* MongoDB
* Vite
* Tailwind CSS (planned)

---

# 👨‍💻 Author

**Saikat Bishayee**
