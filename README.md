# Online Restauran


Автентифікація – це ключовий елемент будь-якого сучасного веб-додатку. Без автентифікації ми не можемо створити особисті кабінети, адміністративні панелі або захищені сторінки. Веб-сайти, які ви використовуєте щодня – Gmail, Facebook, YouTube – всі мають автентифікацію.🚀ів.

## create .env

    DB_USER = <postgres_user>
    DB_PASSWORD = <postgres_passw>
    DATABASE_NAME = "restaurant_db"


    ROOT_DB_USER = "your_postgres_user"
    ROOT_DB_PASSWORD = "your_pg_pass"

    SECRET_KEY = "pass"

## create database

1) **Postgres**: 
```
python3 pg_create_database.py
```


## Необхідні бібліотеки:
 - Flask
 - SQLAlchemy
 - Flask-Login
 - Flask-WTF

`pip install -r requirements.txt`
