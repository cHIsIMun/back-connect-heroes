# back-connect-heroes

🇺🇸 English | 🇧🇷 [Português](README.md)

> The Django REST backend of the Connect Heroes project (standalone API). The full, integrated version lives in [connect-heroes](https://github.com/cHIsIMun/connect-heroes).

## Overview

The API server (Django REST Framework) for **Connect Heroes** — the social network with posts, communities, connections, and messages. This repository contains only the backend; the full-stack version (back + front) is in [connect-heroes](https://github.com/cHIsIMun/connect-heroes).

## Features (API)

- Token authentication.
- Endpoints for posts (with images), likes, and comments.
- User profiles, communities, and direct messages.

## Stack

Python · Django 4.2 · Django REST Framework · Pillow · SQLite.

## Running

```bash
python3 -m venv myvenv && source myvenv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver       # http://localhost:8000
```

## Project status

Backend repository (base version). For the complete and more up-to-date project, see [connect-heroes](https://github.com/cHIsIMun/connect-heroes).

## License

This project does not yet declare a license. Until one is added, all rights are reserved by the author.
