release: python3 manage.py makemigrations authentication insta-clone
release: python3 manage.py migrate

web: gunicorn insta-clone.wsgi