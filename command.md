* pip install django (install django) 
* django-admin startproject mysite (create django project)
* python manage.py runserver -> start the server on local port (python manage.py runserver 8000 (if you want to run it on port 8000))
* python manage.py startapp main -> to create application
* main/views -> is what is shown in the server
* "main.apps.MainConfig", -> add this line inside Installed_apps in mysite/settings.py (since main is my app name and this is a configuration to tell django that we have an app called main and it has to be configured and setup)
  * After the previous step type `python manage.py migrate` (we have updated setting.py so run manage.py and allow it make changes to project)





























source -> https://www.youtube.com/watch?v=sm1mokevMWk
