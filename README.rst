===============================
AllAuth Skeleton
===============================
The Project Includes a basic Skeleton Code based on the 
Django AllAuth Library with custom templates added for better visuals.

===============================
Features
===============================
The Following Pages have custom templates added

- Login
- Password Reset
- Signup
- Password reset From Key

===============================
Technology Stack
===============================

- Python 3.5
- Django 1.11
- Twitter Bootstrap 3
- Django AllAuth 0.32


===============================
Running the example application
===============================

Assuming you use virtualenv, follow these steps to download and run the app.

::

    $ git clone https://github.com/sumeet-dang/allAuth-Skeleton.git
    $ virtualenv venv
    $ . venv/bin/activate
    $ pip install -r requirements.txt
    $ cp .env.example .env
    Set the database Url in .env file to path of your database.

Now we need to create the database tables and an admin user.
Run the following and when prompted to create a superuser choose yes and
follow the instructions:

::

    $ python manage.py migrate
    $ python manage.py createsuperuser


Now you need to run the Django development server:

::

    $ python manage.py runserver

You should then be able to open your browser on http://127.0.0.1:8000 and
see a page with links to sign in or sign up.
