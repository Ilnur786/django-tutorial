# Django tutorial project 

### (https://docs.djangoproject.com/en/4.0/intro/tutorial01/)

## My realisation of tutorial project has some features:
- I used PostgreSQL as db-driver
- Made a wider test module
- Wrap project into docker-compose

## Setup and run:
- clone repository on your local machine: git clone https://github.com/Ilnur786/django-tutorial.git
- install libs from requirements.txt: python -m pip install -r requirements.txt
- open mysite directory
- run project: python manage.py runserver

### Project was created on Windows10 (Python 3.8)

## Setup and run docker-compose:
- clone repository on your local machine: git clone https://github.com/Ilnur786/django-tutorial.git
- be sure that you have install docker and docker-compose
- setup fields in config/.env.prod if it required (optional)
- run command in project root folder: sudo docker-compose --env-file ./config/.env.prod up
### Default username: admin
### Default password: 1234

### Project was tested on WSL2 (Ubuntu 20.04)