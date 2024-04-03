release: python manage.py makemigrations | python manage.py migrate
web: gunicorn RegistrationDjango.wsgi --log-file -
