# Software-Engineering-Software-Processes
# SustainLite

SustainLite is a web application with:
- A **React** frontend
- A **Node.js + Express** server (`server.js`)
- A **Python FastAPI** backend (in `backend/`)

---

## 1. Tech Stack

- **Frontend**
  - React (Create React App)
  - JavaScript / JSX
- **Backend (Node.js)**
  - Node.js
  - Express
- **Backend (Python)**
  - Python 3
  - FastAPI
  - Uvicorn
  - bcrypt
  - python-dotenv

---

## 2. Project Structure

```text
sustainlite/
├─ package.json          # Node/React dependencies & scripts
├─ server.js             # Node.js Express server
├─ public/               # Static assets for React
├─ src/                  # React components & frontend logic
└─ backend/
   ├─ server.py          # FastAPI backend
   ├─ requirements.txt   # Python dependencies
   └─ venv/ (optional)   # Python virtual environment (local only)
