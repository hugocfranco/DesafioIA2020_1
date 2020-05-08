web: gunicorn DjangoChatBotApp.wsgi --log-file -

realise: python -m spacy download en && python manage.py migrate && python manage.py train