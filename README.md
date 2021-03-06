# Requirements
 - Python (3.5, 3.6, 3.7, 3.8, 3.9)
 - Django (3.1)
# using docker
```docker-compose up -d --build```

 # Or

# Installation
1. ```git clone https://github.com/hemanth-sp/user_activity.git```
2. ```cd user_activity```
3. ```python3.8 -m venv venv```
4. ```source venv/bin/activate ```
5. ```pip3 install -r requirements.txt```
6. ```python3 manage.py migrate```
7. ```python3 manage.py runserver```

# Populate dummy data using management command
```python manage.py populate_dummy_data```

or specify the number of user objects to create by default 3, use below command to add more data for example 10 user objects

```python manage.py populate_dummy_data --users 10 ```


# Demo url 
 (localhost)
 - http://127.0.0.1:8000/api/v1/users_activities

 (live)
 - http://139.59.5.26/api/v1/users_activities


# helper lib
 - factory-boy used to populate dummy or fake data in management command