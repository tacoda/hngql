# HNGQL

## Initial Setup

```
python3 -m venv venv
source venv/bin/activate
pip install django==2.1.4 graphene-django==2.2.0 django-filter==2.0.0 django-graphql-jwt==0.1.5
django-admin startproject hngql
cd hngql
python manage.py migrate
python manage.py runserver
```
