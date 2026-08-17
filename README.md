# OnlineQuiz

A full-stack web application for creating, taking, and grading online quizzes — built as a B.Tech team mini-project. Django backend with a JavaScript-driven frontend and a relational database for quiz and result management.

---

## About this project

This was built as a team project during my B.Tech at College of Engineering Thrikkaripur. I contributed to the backend and schema design as part of the team; the final version here was pushed as a single commit representing our completed work.

## What it does

- Create and manage quizzes with multiple-choice questions
- User authentication for students taking quizzes
- Automated grading and result processing
- View quiz results and history

## My contributions

I worked on backend logic and schema design as part of a 2-3 person team. Specific ownership of individual files/features isn't cleanly separable from this single-commit history, but my primary focus areas were the Django models and backend quiz/result processing logic.

## Tech stack

- **Backend:** Django (Python)
- **Frontend:** JavaScript, HTML, CSS
- **Database:** SQLite (development)

## Repository structure

```
OnlineQuiz/
├── Quiz/              # Django app — models, views, quiz logic
├── onlineQuiz/         # Django project config (settings, urls)
├── media/              # User-uploaded media (if any)
├── manage.py
└── requirements.txt    # (add if missing)
```

## Getting started

**Requirements:** Python 3.8+, Django

```bash
# Clone
git clone https://github.com/AshakUmesh/OnlineQuiz.git
cd OnlineQuiz

# Install dependencies
pip install django
# (or: pip install -r requirements.txt, if present)

# Run migrations
python manage.py migrate

# Create a superuser (for admin access)
python manage.py createsuperuser

# Start the development server
python manage.py runserver
```

Visit `http://localhost:8000` to use the app, or `http://localhost:8000/admin` for the Django admin panel.

## Known limitations

- SQLite database is for development only — not suitable for production use
- No `requirements.txt` currently checked in — dependencies inferred from imports (should be added)
- Single-commit history — this repo represents the completed state of a team project rather than incremental development history

---

*B.Tech mini-project, College of Engineering Thrikkaripur, 2020-2024.*
