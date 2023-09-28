# Receipe Web API

Receipe API Project. I am learning this from a Video Course

## Few Commands

```bash
docker build . -t receipe-api

docker-compose build

docker-compose run --rm app sh -c "flake8"

docker-compose run --rm app sh -c "django-admin startproject app ."

docker-compose up

docker-compose down

python ./app/manage.py test

docker-compose run --rm app sh -c "python .\manage.py test"

docker-compose run --rm app sh -c "python manage.py startapp core"

docker-compose run --rm app sh -c "python manage.py wait_for_db"

docker-compose run --rm app sh -c "python manage.py test && flake8"

docker-compose run --rm app sh -c "python manage.py makemigrations"
```
