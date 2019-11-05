# blog-python-django
This is my blog using django-python3

Steps

<h4>Create a virtualenv</h4>
1.</br> virtualenv env

<h4>Enter in virtualenv</h4>
2.</br> source env/bin/activate

<h4>Install django</h4>
3.</br> pip install django

<h4>Create a proyect (this step is alternative because in this repository exist blog project)</h4>
4.</br> django-admin startproject blog

<h4>Exec this command every time that modified settings</h4>
5. </br>
    cd src</br>
    python3 manage.py makemigrations</br>
    python3 manage.py migrate</br>
    python3 manage.py runserver</br>

<h4>Rename the folder static to static_in_env</h4>
6. </br>
python3 manage.py collectstatic</br>
This command install collectstatic and will created a folder static_root
