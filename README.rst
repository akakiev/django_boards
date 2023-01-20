=============
Django Boards
=============

This project is a discussion board (a forum). The whole idea is to maintain several boards, which will behave like categories. Then, inside a specific board, a user can start a new discussion by creating a new topic. In this topic, other users can engage in the discussion posting replies.

Detailed documentation is in the "docs" directory.

Quick start
-----------

1. Clone the repository to your local machine::

    git clone git@github.com:sibtc/django-beginners-guide.git

2. Install widget tweaks module:

    pip install django-widget-tweaks
    
3. Create the database:

    python manage.py migrate

4. Finally, run the development server:

    python manage.py runserver

5. Start the development server and visit http://127.0.0.1:8000/

Tutorial:
    https://simpleisbetterthancomplex.com/series/beginners-guide/1.11/
