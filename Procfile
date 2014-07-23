nginx_access: tailf /var/log/nginx/access.log
nginx_error: tailf /var/log/nginx/error.log
web: gunicorn django_demo.wsgi -b "0.0.0.0:$PORT" --log-file - --access-logfile - --log-level debug
