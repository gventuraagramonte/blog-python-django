# blog-python-django
This is my blog using django-python3

Steps

<h4>Create a virtualenv</h4>
1. virtualenv env

<h4>Enter in virtualenv</h4>
2. source env/bin/activate

<h4>Install django</h4>
3. pip install django

<h4>Create a proyect (this step is alternative because in this repository exist blog project)</h4>
4. django-admin startproject blog

<h4>Exec this command every time that modified settings</h4>
5. cd src
    python3 manage.py makemigrations
    python3 manage.py migrate
    python3 manage.py runserver

<h4>Rename the folder static to static_in_env</h4>
6. python3 manage.py collectstatic
This command install collectstatic and will created a folder static_root
