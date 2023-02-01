# Django Blog
Following this tutorial:

https://tutorial.djangogirls.org/en/django_start_project/

## Usage
Generate a random key with:

`python -c 'from django.core.management.utils import get_random_secret_key; \
      print(get_random_secret_key())'`

Create a file called `.env` in the root dir. Add the line `SECRET='<thekeyyougeneratedabove>'` to it.

Activate the VENV

Start server with `python manage.py runserver` from the root dir.