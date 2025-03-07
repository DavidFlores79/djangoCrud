web: gunicorn simple_crud.wsgi --log-file - 
#or works good with external database
web: python manage.py migrate --no-input && gunicorn simple_crud.wsgi
