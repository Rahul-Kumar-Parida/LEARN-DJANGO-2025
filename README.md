#Github Setup
# LEARN-DJANGO-2025  

This repository contains my learning journey with **Django (2025)**. Below are the steps to set up the project from scratch.  

1. Initialize Git and push code to GitHub  
   ```bash
   git init
   git config --global user.name "Rahul Kumar Parida"
   git config --global user.email "rahulkumarparida@gmail.com"
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/Rahul-Kumar-Parida/LEARN-DJANGO-2025.git
   git push -u origin main



# Django Setup with uv


1. Create a virtual environment using uv  
   uv venv
   .\.venv\Scripts\activate   # For Windows

2. Install Django  
   uv pip install Django

3. Start a Django project  
   django-admin startproject chaiaurDjango
   cd chaiaurDjango

4. Apply migrations and run the development server  
   python manage.py migrate
   python manage.py runserver

👉 The server will start at: http://127.0.0.1:8000/
