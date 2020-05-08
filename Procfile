web: python -m spacy download en && gunicorn DjangoChatBotApp.wsgi --log-file -

realise: python manage.py migrate && python manage.py train