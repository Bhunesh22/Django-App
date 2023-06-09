# Django-App

## Features
* Share Projects
* Message other developers
* Rate others work
* Search other developers


## Tech Stack
* Django
* Postgres
* Django REST Framework

## How to use
- Fork this repo
- Clone the forked repo
- Make virtual environment ``virtualenv env``
- Go to ``cd env/scripts``
- Activate the environment using ``activate``
- Come Back to base directory ``cd../..``
- Install requirements.txt ``pip install -r requirements.txt``
- Run ``python manage.py migrate``
- If you change something in any model use ``python manage.py makemigrations``
- Make a superadmin to login into the dashboard ``python manage.py createsuperuser`` it will ask for ``email`` and ``password``
- To start the server use ``python manage.py runserver``


## How to delete sql data
- `rm -rf db.sqlite3`
- `python manage.py migrate`
- `python manage.py createsuperuser`


# Home Page
<img src="./resources/images/Devsearch Home.jpg">  


# Projects Page
<img src="./resources/images/DevSearch Projects.jpg">  

# Profile Page
<img src="./resources/images/Devsearch Profile.jpg">  

# User Inbox
<img src="./resources/images/Devsearch Inbox.jpg">  

