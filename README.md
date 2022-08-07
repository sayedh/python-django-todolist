# Python Django Todo App
In this project I built a Todo app using the Django framework. 

![App Pic](https://user-images.githubusercontent.com/30685241/183311860-34cb1274-7b57-49c3-98e7-16eeb9ccdb71.jpg)


Data view in the Postgres pgAdmin tool
![pgAdmin4 table](https://user-images.githubusercontent.com/30685241/183311863-409acd74-e0a0-485b-9e96-57365bb4f52d.jpg)



## Technologies Used
* Python
* Django
* PostgreSQL

## Dependencies
* Install Python - https://www.python.org/downloads/release/python-3106/
* Install Django - https://docs.djangoproject.com/en/4.0/topics/install/
* Install Postgres - https://www.postgresql.org/download/
* Install psycopg2 - https://www.psycopg.org/docs/install.html

## Executing program
* Download the repository to your computer go to project file
```
git clone https://github.com/sayedh/python-django-todolist
cd python-django-todolist
```

* Now setup the project with the following commands
```
python manage.py runserver
python manage.py migrate
python manage.py makemigrations todos
python manage.py sqlmigrate todos 0001
python manage.py migrate
python manage.py runserver
```
* Now the app should have started, go to the following link:
```
http://127.0.0.1:8000/todos/list/
```
