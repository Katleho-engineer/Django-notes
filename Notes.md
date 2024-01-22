## Step 1: Virtual environment
#### python3 -m venv env
#### source env/bin/activate
#### deactivate

## Step 2: Install Django
#### python3 -m pip install Django

## Step 3: Create Project
#### django-admin startproject name

## Step 4: Create an app
#### python manage.py startapp name

## Step 5: Start a development sever
#### python3 manage.py runserver
#### press ctrl c or cmd c, to stop the server

## Step 6: Make migrations
#### python3 manage.py makemigrations
#### python3 manage.py migrate

## Step 6: Create superuser for the admin
#### python3 manage.py createsuperuser

## Step 7: Load requirements file
#### pip freeze > requirements.txt

## Step 8: Install requirements
#### pip install -r requirements.txt

## Step 9: Test
#### python manage.py test

## Step 9: Coveraage report
#### pip install coverage
#### coverage run manage.py test -v 2 && coverage report
