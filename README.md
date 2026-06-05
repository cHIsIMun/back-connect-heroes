# back-connect-heroes

🇧🇷 Português | 🇺🇸 [English](README.en.md)

> Backend Django REST do projeto Connect Heroes (API standalone). Versão completa e integrada vive em [connect-heroes](https://github.com/cHIsIMun/connect-heroes).

## Visão geral

Servidor de API (Django REST Framework) do **Connect Heroes** — a rede social com posts, comunidades, conexões e mensagens. Este repositório contém apenas o backend; a versão full-stack (back + front) está em [connect-heroes](https://github.com/cHIsIMun/connect-heroes).

## Funcionalidades (API)

- Autenticação por token.
- Endpoints de posts (com imagens), likes e comentários.
- Perfis de usuário, comunidades e mensagens diretas.

## Stack

Python · Django 4.2 · Django REST Framework · Pillow · SQLite.

## Como executar

```bash
python3 -m venv myvenv && source myvenv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver       # http://localhost:8000
```

## Estado do projeto

Repositório de backend (versão base). Para o projeto completo e mais atual, veja [connect-heroes](https://github.com/cHIsIMun/connect-heroes).

## Licença

Este projeto ainda não declara uma licença; até que uma seja adicionada, todos os direitos são reservados ao autor.
