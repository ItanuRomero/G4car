web: gunicorn G4car.wsgi:application --log-file - --log-level debug
python manage.py collectstatic --noinput
manage.py migrate