NotifySync - Multichannel Notification Management System
NotifySync is a full-stack notification management system featuring a unified single-screen Admin Matrix, real user authentication triggers (Login/Logout), and isolated delivery across WhatsApp, Email, and Web Push.

⚡ Quick Start

Backend (Django)
cd backend
# Activate virtual environment
..\venv\Scripts\activate  # or venv\Scripts\activate
python manage.py migrate
python manage.py seed_data
python manage.py runserver 8000
Backend runs at: http://127.0.0.1:8000

2. Frontend (React + Vite)
cd frontend
npm install
npm run dev
Frontend runs at: http://localhost:5173
