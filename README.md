# PythonBackend

A test backend app

Django + react app

# Setup Django

1. pip install virtualenv
2. python -m virtualenv env
   or
   virtualenv env
3. env\scripts\activate # activate virtual environment
4. pip install django
5. django-admin startproject mynotes
6. cd mynotes
7. python manage.py runserver
8. python manage.py startapp api
9. python manage.py migrate
