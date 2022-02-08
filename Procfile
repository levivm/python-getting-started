release: if [ -n "$FIRST_PROJECT_EXECUTION" ]; then python manage.py runscript release --traceback ; fi
web: gunicorn gettingstarted.wsgi
