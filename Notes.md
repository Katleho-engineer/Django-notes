## Step 1: Virtual environment
#### python3 -m venv my_env
#### source my_env/bin/activate
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
