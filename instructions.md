Django - Aula 01
https://www.youtube.com/watch?v=Dzuiy-JNi-E&ab_channel=FabioRuicci

*criar migration

python manage.py sqlmigrate auth 0001
python manage.py sqlmigrate sessions 0001

*rodar migrations

python manage.py migrate

*ver status das migrations

python manage.py showmigrations

*criar apps

python manage.py startapp blog

* rodar migrations pros models
python manage.py makemigrations blog

* criar usuário para acessar o admin do django
python manage.py createsuperuser

* rodar o servidor
python manage.py runserver