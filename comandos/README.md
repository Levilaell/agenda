Iniciar o projeto

````
python -m venv venv
. venv/bin/activate
pip install django
django-admin startproject project .
python manage.py startapp <app>

````

Configurar o Git

````
git config --global user.name 'Nome'
git config --global user.email 'email'
git config --global init.defaultBranch main
# Configurar .gitignore
git init
git add .
git commit -m 'Mensagem'
git remote add origin URL_DO_GIT
git push origin main

````

Migrando base de dados

````
python manage.py makemigrations
python manage.py migrate