# Building a Chatroom with Django, WebSocket, and ASGI

## Introduction

This guide will walk you through building a simple chatroom application using Django, WebSocket, and ASGI (Asynchronous Server Gateway Interface). We'll use Django Channels to integrate WebSockets into our Django project.

## Prerequisites

- Python 3.7+
- Django 3.0+
- Django Channels
- Redis (optional, for production use)

## Setup

### Steps

```bash
# Install Django and Django Channels
pip install django channels

# Create a new Django project
django-admin startproject chatproject

# Navigate to the project directory
cd chatproject

python manage.py startapp app
```
```bash
pip manage.py makemigrations

pip manage.py migrate

python manage.py runserver
```

