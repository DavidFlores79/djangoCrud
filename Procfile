web: gunicorn simple_crud.wsgi --log-file - 
#or works good with external database
web: python manage.py migrate && gunicorn simple_crud.wsgi