# First Django
Simple TOdo application built with Django which demonstrates what I have learned.

## Languages/Frameworks
- HTML5
- Django

## Database
Django converts our Python code into sequel code. which can be executed on our database.
```
python3 manage.py makemigrations --dry-run
```

Applying built-in Django apps
```
python3 manage.py showmigrations
```

Setting up permissions
```
python3 manage.py migrate
```

Create login to look at tables and potentially make changes to them if needed
```
python3 manage.py createsuperuser
```

*Postgres was later used due to Heroku updates deleting data from SQLite*

## Requirements
```
asgiref==3.3.1
coverage==5.3.1
Django==3.1.5
gunicorn==20.0.4
psycopg2-binary==2.8.6
pytz==2020.5
sqlparse==0.4.1
```

## Deployment
1. Installing Heroku
```
npm install -g heroku
```
2. Loging Into Heroku
```
heroku login -i
```
