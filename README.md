# README
# In The Name Of ALLAH
HyperLight is a simple django app to aggregate RSS feeds.

Features

    Locally stored feed link, title and description.
    Locally stored entry link, title and description.
    Show recent entries.
    String search of locally stored data.
    Uses Django admin to manage feeds and support for multiple users.
    Easy to install - simple requirements.

How to use

Simply run these lines and enjoy !

    python manage.py migrate
    python manage.py createsuperuser
    python manage.py runserver
    
Requirements

    Django >= 1.8
    django-braces
    factory_boy
    feedparser
    mock
    pytz
