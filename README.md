# MARS project

python3 manage.py startapp mars_api

# миграции
python3 manage.py makemigrations
python3 manage.py migrate

чтобы создать новую БД в консоле пишем:

**createdb mara_db**

удалить БД в консоле пишем:
**dropdb mars_db**

# админка

создание суперпользователя:

**python3 manage.py createsuperuser**
