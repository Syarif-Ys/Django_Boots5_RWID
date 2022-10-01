# Django_Boots5_RWID

1. django-admin startproject config .
2. python .\manage.py runserver
3. new python package "settings"
4. new python file "base.py"
5. code in settings.py ==> move to ==> base.py
6. new python file "development.py"
7. di development.py import semua file dari base.py "from .base import *"
8. python .\manage.py startapp blog
9. registrasi apps 'blog' dari apps.py di folder blog pada development
10. Config == Project, blog == apps
