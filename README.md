# recipe-app-api
Recipe API Project


to start a new project 

docker-compose run --rm app sh -c "django-admin startproject app."

docker-compose run --rm app sh -c "flake8"
docker-compose run --rm app sh -c "python manage.py test"
docker-compose run --rm app sh -c "python manage.py runserver"

# to see docker images (can also be used to delete database data)
docker volume ls
docker volume rm volume_name
