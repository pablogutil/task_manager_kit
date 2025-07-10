# ✅ Task Manager Kit

A clean full-stack Task & To-Do management app using React (frontend) and FastAPI (backend).

This project demonstrates basic CRUD operations, user interactions, and persistent task storage — ideal for showcasing full-stack skills.

---

## 🔧 Features

- 📝 Create, update, and delete tasks
- ✅ Mark tasks as completed
- 🧩 REST API built with FastAPI
- 💅 Frontend built with React + Tailwind
- 💾 SQLite or in-memory DB
- 🔒 CORS-ready backend for local dev

---

## ⚙️ Tech Stack

- React + Vite + Tailwind CSS (Frontend)
- FastAPI + SQLite + Uvicorn (Backend)
- Axios for API requests

---

## ▶️ Run Locally

### 🖥️ Backend

```bash
cd backend
python -m venv venv && source venv/bin/activate
pip install -r requirements.txt
uvicorn main:app --reload
