docker-compose build

docker-compose run app sh -c
    "python manage.py runserver"
    "python manage.py migrate"
    "python manage.py test"