release: python manage.py makemigrations && python manage.py migrate
web: uvicorn phatoffers_backend.asgi:application --host 0.0.0.0 --port $PORT
