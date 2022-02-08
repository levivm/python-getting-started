if [ -n "$FIRST_PROJECT_EXECUTION" ]; then
  release: python manage.py runscript release --traceback
else
  echo "hola"
fi

web: gunicorn gettingstarted.wsgi
