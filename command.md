source -> https://www.softcover.io/read/92780ad5/django_book/frontmatter

* `pip install pipenv` -> installing pip envirnoment
* `pipenv install django` -> install django using pipenv
* `pipenv shell` -> activate virtual envirnomane
* `django-admin startproject mysite` (create django project)
* `python manage.py runserver` -> start the server on local port (python manage.py runserver 8000 (if you want to run it on port 8000))
* `python manage.py startapp main` -> to create application
     * Usually a project is whole and an app is part of the project (app vs project) 
     * After creating an app, you have to add it in the inside the django projects setting.py insalled apps, inorder to tell it that we have created an app and it needs to use it.
* "main.apps.MainConfig", -> add this line inside Installed_apps in mysite/settings.py (since main is my app name and this is a configuration to tell django that we have an app called main and it has to be configured and setup)
  * After the previous step type `python manage.py migrate` (we have updated setting.py so run manage.py and allow it make changes to project)
  * `python manage.py makemigrations main` -> command to run when you have made changes to your model






























