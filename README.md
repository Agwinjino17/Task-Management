# Task Manager API

A simple Task Manager built with FastAPI, SQLite, and JWT Authentication.

## Tech Stack
- FastAPI
- SQLAlchemy + SQLite
- JWT Authentication
- bcrypt Password Hashing
- HTML + CSS + JS Frontend

## Setup Instructions

### 1. Clone the repo
git clone https://github.com/Agwinjino17/Task-Management.git
cd Task-Management/backend

### 2. Create virtual environment
python -m venv venv
venv\Scripts\activate

### 3. Install dependencies
pip install -r requirements.txt

### 4. Create .env file
cp .env.example .env

### 5. Run the server
uvicorn app.main:app --reload

### 6. Open frontend
Open `Frontend/index.html` in browser

## Environment Variables
| Variable | Description |
|----------|-------------|
| SECRET_KEY | JWT secret key |
| DATABASE_URL | SQLite database URL |

## API Endpoints
| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /register | Register user |
| POST | /login | Login user |
| GET | /profile | Get profile |
| GET | /tasks | Get all tasks |
| POST | /tasks | Create task |
| GET | /tasks/{id} | Get single task |
| PUT | /tasks/{id} | Update task |
| DELETE | /tasks/{id} | Delete task |

## Deployment
- Backend: https://task-management-qpzn.onrender.com
- Frontend: https://task-management-frontend-f8ja.onrender.com
- API Docs: https://task-management-qpzn.onrender.com/docs

> Note: Free tier server may take 50 seconds to wake up on first visit.
> Please open the API docs link first, wait for response, then use the frontend.
