# DjangoTaskProject_Model_django-framework

DjangoTaskProject_Model_django-framework

django-admin startproject tareasproject

..\tareas-test\tareasproject

[manage.py]

python manage.py startapp tareas

> registrar la app tareas

  D:\pydjango\tareas-test\tareasproject\tareasproject
  
  settings.py 
  
INSTALLED_APPS = [

    #...,
    
    'tareas',
    
]

> modelos
..\tareas-test\tareasproject\tareas

  models.py
  
  # add code..



..\tareas-test\tareasproject

[manage.py]

manage.py makemigrations

manage.py migrate


> Activando modelos en el Admin de Django

..\tareas-test\tareasproject\tareas

 admin.py 
 
 # add code..


python manage.py runserver

  http://127.0.0.1:8000/

administration panel :

http://localhost:8000/admin/

user:

python manage.py createsuperuser


