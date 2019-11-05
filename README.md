# blog-python-django
This is my blog using django-python3

Steps

Create a virtualenv
1. virtualenv env

Enter in virtualenv
2. source env/bin/activate

Install django
3. pip install django

Create a proyect (this step is alternative because in this repository exist blog project)
4. django-admin startproject blog

Exec this command every time that modified settings
5. cd src
    python3 manage.py makemigrations
    python3 manage.py migrate
    python3 manage.py runserver

Rename the folder static to static_in_env
6. python3 manage.py collectstatic
This command install collectstatic and will created a folder static_root
