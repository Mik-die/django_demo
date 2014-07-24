# web: gunicorn django_demo.wsgi -b "0.0.0.0:$PORT" --log-file - --access-logfile - --log-level debug
web: python ./manage.py runfcgi host=127.0.0.1 port=$PORT
