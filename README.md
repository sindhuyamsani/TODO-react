# TODO-react

Create todo app with Django and React.

#

## Tools

- Django 4
- React Js
- Python 3



# How to Run Project


## Install Backend Requirements

```
pip install pipenv
``` 

```
pipenv shell
```

```
pipenv install
```

## Install Frontend Dependencies

```
cd frontend
```

```
npm install
npm audit
```

## Migrate Backend Models

```
cd ..
cd backend
```

```
python manage.py makemigrations todo
```

```
python manage.py migrate
```

## Add Super User

```
python manage.py createsuperuser
```

## Run Django Server

```
python manage.py runserver
```

## Run FrontEnd

open new terminal in `frontend` directory and run this command.

```
npm start
```

## Open On Browser

App Page
[localhost:3000](http://localhost:3000/)

Django Admin Page
[127.0.0.1:8000/admin](http://127.0.0.1:8000/admin)

#

