# Blog Website — Django & Python

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

A full-stack blog web application built with **Django** and **Python** — featuring user authentication, post management, comments, and a clean REST API.

---

## Features

- **User Auth** — register, login, logout with Django's authentication system
- **Blog Posts** — create, read, update, delete (CRUD) with rich text content
- **Comments** — threaded comment system on each post
- **REST API** — Django REST Framework endpoints for programmatic access
- **Admin Panel** — Django admin for content management
- **Pagination** — paginated post listing for performance

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Backend | Django 4.x, Python 3.10+ |
| Database | SQLite (dev) / PostgreSQL (prod) |
| API | Django REST Framework |
| Auth | Django Auth + Session |
| Frontend | Django Templates, Bootstrap |

---

## Getting Started

```bash
git clone https://github.com/amirasghar-ml/BLog-WebSite-Using-Django-Python.git
cd BLog-WebSite-Using-Django-Python

python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate

pip install -r requirements.txt

python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

Open [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/posts/` | List all posts |
| POST | `/api/posts/` | Create a post |
| GET | `/api/posts/<id>/` | Get a post |
| PUT | `/api/posts/<id>/` | Update a post |
| DELETE | `/api/posts/<id>/` | Delete a post |
| GET | `/api/posts/<id>/comments/` | List comments |

---

## Author

**Amir Asghar** — Senior AI/ML Engineer
[GitHub](https://github.com/amirasghar-ml) · [LinkedIn](https://www.linkedin.com/in/amir-asghar-ali-a80825112/)
