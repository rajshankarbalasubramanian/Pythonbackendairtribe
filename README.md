
# DevTrack (Django Backend API)

DevTrack is a minimal backend API for tracking engineering issues (similar to a stripped-down GitHub Issues).
Engineers can create reporters, file issues, and retrieve/filter issues using query parameters.

---

## Tech Stack
- Python 3.x
- Django 4.x (or your version)
- JSON file storage (no database)

---

## Project Structure



python -m venv .venv

3) Install dependencies

pip install -r requirements.txt

4) Run the server

Go to the folder containing manage.py and run:
python manage.py runserver

Server runs at:

http://127.0.0.1:8000/


API Endpoints
Base URL:
http://127.0.0.1:8000


Reporter APIs
1) Create Reporter

POST /api/reporters/

2) Get All Reporters

GET /api/reporters/


3) Get Reporter by ID


Issue APIs
1) Create Issue

2) Get All Issues

GET /api/issues/

3) Get Issue by ID

GET /api/issues/?id=1

4) Filter Issues by Status

GET /api/issues/?status=open

Response (200) → list of issues with status=open








