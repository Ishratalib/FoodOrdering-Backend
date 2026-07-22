release: python manage.py migrate
web: gunicorn food_ordering.wsgi --log-file - --bind 0.0.0.0:$PORT
