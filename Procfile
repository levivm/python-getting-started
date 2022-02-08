if [ "$FIRST_PROJECT_EXECUTION" != "true" ]; then
  release: python manage.py runscript release --traceback
fi
web: gunicorn gettingstarted.wsgi
