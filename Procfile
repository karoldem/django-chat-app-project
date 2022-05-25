release: python manage.py migrate
web: gunicorn chat_app_project.wsgi
worker: python manage.py runworker channel_layer
