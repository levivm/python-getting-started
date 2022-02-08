release: if [ -n "$FIRST_PROJECT_EXECUTION" ] && [ "$FIRST_PROJECT_EXECUTION" != "true" ]; then python manage.py runscript release --traceback ; fi
web: gunicorn gettingstarted.wsgi
