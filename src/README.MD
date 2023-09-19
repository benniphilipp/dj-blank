# Django APP Basic
python manage.py startapp accounts

# Crate ENV
virtualenv env

# Active ENV
. env/bin/activate

# Install Dajngo 
pip install Django

# Crate Django APP
django-admin startproject src

# Django Start APP Name
python manage.py startapp NAME

# PIP
pip freeze > requirements.txt

# Django CMD
python3 manage.py makemigrations && python3 manage.py migrate

python3 manage.py runserver

python manage.py collectstatic
python manage.py createsuperuser

python manage.py compress

# Github

    - Branrch
    git branch --list
    git branch _name
    git checkout _name

    - Push
    git add .
    git commit -m '_text'
    git push origin 'branch_name'


# Git-Projekt klonen für Neues Projekt
git clone https://github.com/benniphilipp/dj-blank.git

    - mv dj-blank NeuesProjekt
    - cd NeuesProjekt
    - git remote remove origin
    - git remote add origin https://github.com/Benutzer/NeuesProjekt.git

# 
https://gist.github.com/brizandrew/685a588fbefbd64cd95ed9ec4db84848
https://github.com/kottenator/django-compressor-toolkit