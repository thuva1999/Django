# Hello Blog Application

A simple Django backend blog application created to learn and practice the Django framework.  

---

## Project Overview

- **Project Name:** `hello`  
- **App Name:** `app`  
- **Description:**  
  This is a basic blog application backend built using Django. It is fully functional and designed as a learning project to understand Django's core features such as models, views, URLs, and templates.

---

## Features

- Django project setup with a single app.
- **Blog operations:**  
  - **Admin-only:** create, update, delete posts  
  - **Everyone:** read posts  
- Configured CI/CD pipeline using GitHub Actions.

---

## CI/CD Implementation

To practice continuous integration and deployment, I implemented a basic CI/CD pipeline:

1. Generated dependencies:  
   ```bash
   pip freeze > requirements.txt
2. Created GitHub Actions workflow folder:
    mkdir -p .github/workflows
3. Added a YAML workflow file inside .github/workflows/ with your CI/CD configuration.
4. Added the project to GitHub:
   git add .
   git commit -m "Initial commit with CI/CD pipeline"
   git push origin main

** Getting Started**
Prerequisites

Python 3.x

Django 4.x (or latest)

Git

**Installation**

Clone the repository:

git clone https://github.com/thuva1999/Django.git


Create a virtual environment:

python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

Install dependencies:

pip install -r requirements.txt

Apply migrations:

python manage.py migrate

Create a superuser (admin) to manage posts:

python manage.py createsuperuser

Run the development server:

python manage.py runserver

Visit http://127.0.0.1:8000/ to see your project running.
