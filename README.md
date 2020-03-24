# Django Stripe Tutorial

This is me following along with (this tutorial)[https://www.youtube.com/watch?v=oZwyA9lUwRk].

## Notes

### Starting a project

```bash
$ django-admin startproject mysite
```

### Running a server

``` bash
$ python3 manage.py runserver
```
Custom port e.g. 8080

``` bash
$ python3 manage.py runserver <port number>
```

### Creating a new app

``` bash
$ python3 manage.py startapp <app_name>
```
### Alternative Databases
TODO try one of these sometime 
(Django Databases)[https://docs.djangoproject.com/en/3.0/topics/install/#database-installation]

### Migration 

The three-step guide to making model changes:

1. Change your models (in models.py).
2. Run ```python3 manage.py makemigrations <app_name>``` to create migrations for those changes
3. Run ```python3 manage.py migrate``` to apply those changes to the database.

### Django Shell

``` bash
$ python3 manage.py shell
```

### Creating an admin user

``` bash
$ python3 manage.py createsuperuser
```
