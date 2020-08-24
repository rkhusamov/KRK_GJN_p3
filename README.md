Как запустить

В терминале выполнить следующие команды:

python3.7 -m pip install --upgrade pip
python3 manage.py makemigrations
python3 manage.py migrate
python3 manage.py createsuperuser -- задать логин-пароль суперюзера для админки
python manage.py runserver


Чтобы попасть в админку: http://127.0.0.1:8000/admin/