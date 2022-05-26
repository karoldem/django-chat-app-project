release: python manage.py migrate
web: gunicorn chat_app_project.asgi:application
worker: python manage.py runworker channel_layer
