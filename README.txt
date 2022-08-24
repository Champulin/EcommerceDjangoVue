Ecommerce learning with Django/Vue this will use bulma css

Set up instructions for the project 
1.- create a virtual environment in W11
    pip install virtualenv
    py -m venv nameofvenv
    venvs\nameofvenv\Scripts\activate
2.- create git repository
    mkdir nameofgitrepo
    cd nameofgitrepo
    git init
    create .gitignore and README.md files    
2.- install Django and create a project
    django-admin startproject nameofproject_projectdir
    cd nameofproject_projectdir
    python manage.py makemigrations
    python manage.py migrate
    python manage.py createsuperuser
3.- create and setup apps folder
    mkdir apps\core
    python manage.py startapp core apps/core 
    mkdir apps\core\templates
    create a base.html file inside templates
that's all the setup 
