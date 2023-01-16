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
    
2. Create the database:

    python manage.py migrate

3. Finally, run the development server:

    python manage.py runserver

4. Start the development server and visit http://127.0.0.1:8000/
