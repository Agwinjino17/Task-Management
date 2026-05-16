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
git clone https://github.com/yourusername/task-manager.git
cd task-manager/backend

### 2. Create virtual environment
python -m venv venv
venv\Scripts\activate

### 3. Install dependencies
pip install -r requirements.txt

### 4. Create .env file
Copy .env.example to .env and fill values

### 5. Run the server
uvicorn app.main:app --reload

### 6. Open frontend
Open frontend/index.html in browser

## Environment Variables
SECRET_KEY=your_secret_key
DATABASE_URL=sqlite:///./taskmanager.db

## API Endpoints
- POST /register
- POST /login
- GET  /tasks
- POST /tasks
- GET  /tasks/{id}
- PUT  /tasks/{id}
- DELETE /tasks/{id}

## Deployment
Live URL: https://your-deployment-url.com