# Django Trainer Search

A full-stack **Trainer Search web application** built with a **Django REST API backend** and a **React (Node.js) frontend**.  
The application allows users to search for trainers and uses **JWT authentication** for secure user login and access control.

---

## Tech Stack

### Backend
- Django
- Django REST Framework
- JWT Authentication

### Frontend
- React
- Node.js
- npm

---

## Features
- User authentication using JWT (login & protected routes)
- Trainer search functionality
- RESTful API backend
- Decoupled frontend and backend architecture

---

## Prerequisites

Make sure the following are installed on your system:

- Python 3.10+
- Node.js 18+
- npm
- Git

---

## Backend Setup (Django)

bash
git clone https://github.com/yourusername/django-trainer_search.git
cd django-trainer_search

python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

pip install -r requirements.txt

cd trainers
python manage.py migrate
python manage.py runserver

The Django backend will run at:
http://127.0.0.1:8000

Frontend Setup (React)
cd trainer_search_app
npm install
npm start

The React frontend will run at:
http://localhost:3000

