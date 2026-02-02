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
    sustainlite/
    ├── backend/
    │   ├── main.py              # FastAPI application
    │   ├── database.py          # SQLite database models
    │   ├── schemas.py           # Pydantic schemas
    │   ├── auth.py              # Authentication utilities
    │   ├── requirements.txt     # Python dependencies
    │   └── README.md
    ├── frontend/
    │   ├── src/
    │   │   ├── components/      # Reusable components
    │   │   ├── context/         # React context
    │   │   ├── pages/           # Page components
    │   │   ├── services/        # API services
    │   │   ├── App.jsx          # Main app
    │   │   ├── main.jsx         # Entry point
    │   │   └── index.css        # Global styles
    │   ├── package.json
    │   └── README.md
    └── README.md                # This file
    ```
