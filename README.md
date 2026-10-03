# Django Docker Starter

A minimal Django backend project running inside Docker. Built as an onboarding practice for containerization basics and environment configuration.

## Tech Stack

- **Language:** Python 3.10 (Slim)
- **Framework:** Django
- **WSGI Server:** Gunicorn
- **Containerization:** Docker & Docker Compose

## Requirements

- [Docker Desktop](https://www.docker.com/products/docker-desktop/) (includes Docker Compose)

> **Note:** No local Python, Virtualenv, or Django installation is needed on the host machine. Everything runs inside the isolated Docker container.

## Quick Start / How to Run

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/HastiHosseinMardy/my-django-docker.git](https://github.com/HastiHosseinMardy/my-django-docker.git)
   cd my-django-docker

- **Admin Account Initialized:** Created an initial Django superuser account (`admin`) for secure administrative access via `/admin`.