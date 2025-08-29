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
