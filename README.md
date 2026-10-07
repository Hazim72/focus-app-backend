# focus-app-backend

Django REST Framework backend for Focus App.

## Architecture
- Django project in `config/` (settings: `base.py`, `dev.py`, `prod.py`)
- Apps in `apps/`: `users`, `focus_sessions`, `stats`
- Requirements in `requirements/`: `base.txt`, `dev.txt`, `prod.txt`
- OpenAPI docs via `drf-spectacular`
