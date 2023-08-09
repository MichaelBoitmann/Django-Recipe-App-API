# Django Recipe App API

## 

### Create an account in Docker and GitHub

### Docker Installation and Setup

### Install flake8 package

```bash
$ docker-compose run --rm app sh -c "flake8"
```

### Django Test Suite

```bash
$ docker-compose run --rm app sh -c "python manage.py test"
```

### run flake8

```bash
$ docker-compose run --rm app sh -c "flake8"
```

### Django run start project app 
### Note: (take note of '.' [dot] this is very important not to mess up)

```bash
$ docker-compose run --rm app sh -c "django-admin startproject app ."
```

### To run Django services

```bash
$ docker-compose up
```

