# MuhaMind

A personal content aggregator built with Next.js and Django.

## 🚀 Getting Started

### Frontend

```bash
cd frontend
npm install
npm run dev
```

Visit: http://localhost:3000

### Backend

```bash
cd backend
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Visit: http://localhost:8000

## 🛠️ Tech Stack

-   **Frontend**: Next.js 15, TypeScript, Sass
-   **Backend**: Django, PostgreSQL
-   **State Management**: Redux Toolkit

## 📁 Project Structure

```
MuhaMind/
├── frontend/          # Next.js app
└── backend/           # Django API
```
