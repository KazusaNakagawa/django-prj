## Start Project

1. Creat project

- admin: <site name> --> backend

```bash
docker-compose run web django-admin startproject backend .
```

2. Creat app

2-1. appname: note

```bash
$ python manage.py startapp <app name>

$ tree note
note/
├── __init__.py
├── admin.py
├── apps.py
├── migrations
│   └── __init__.py
├── models.py
├── tests.py
└── views.py
```

2-2. create `urls.py`

3. migrate

```bash
python manage.py migrate
```

## Ref

- https://docs.djangoproject.com/en/4.0/intro/tutorial01/
