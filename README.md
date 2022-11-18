# WeatherAppDjango
Tech: Python, Django

API used: https://docs.airnowapi.org/

1. pip install virtualenv
2. python -m venv venv (only do this when you don't have virtual enviornment yet. Already done don't do again.)
3. source venv/bin/activate to turn on VE
4. Pip install django
5. django-admin.py startproject weather (done, do not do again)
6. **Run Django server: python manage.py runserver (from weather folder)**
7. Push migration into database: python manage.py migrate (Django comes with an out-of-box migration)
8. To create Django admin: python manage.py createsuperuser
9. Create Django app: python manage.py startapp lookup
