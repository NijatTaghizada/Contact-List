# Contact List

A small full-stack app where you can add, edit and delete contacts. I built it to learn how a React frontend talks to a Python backend.

- Backend: Flask + Flask-SQLAlchemy, with a SQLite database
- Frontend: React, set up with Vite

## API

| Method | Route | What it does |
|---|---|---|
| GET | `/contacts` | list all contacts |
| POST | `/create_contact` | add a contact |
| PATCH | `/update_contact/<id>` | edit a contact |
| DELETE | `/delete_contact/<id>` | delete a contact |

## Run it

Backend:

```bash
cd backend
pip install flask flask-sqlalchemy flask-cors
python main.py
```

Frontend (in a second terminal):

```bash
cd frontend
npm install
npm run dev
```
