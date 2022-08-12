# django-roulette

Django, PostgreSQL and Docker


```bash
docker-compose build
```
```bash
docker-compose up -d
```
```bash
docker-compose logs -f
```

```bash
$ docker-compose down -v
$ docker-compose -f docker-compose.prod.yml up -d --build
$ docker-compose -f docker-compose.prod.yml exec web python manage.py migrate --noinput
$ docker-compose -f docker-compose.prod.yml exec web python manage.py collectstatic --no-input --clear
```


