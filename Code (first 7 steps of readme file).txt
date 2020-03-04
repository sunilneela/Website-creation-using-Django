Microsoft Windows [Version 10.0.18362.657]
(c) 2019 Microsoft Corporation. All rights reserved.

C:\Users\neela>mkvirtualenv mysubject
created virtual environment in 1583ms CPython3Windows(dest=C:\Users\neela\Envs\mysubject, clear=False, global=False) with seeder FromAppData pip=latest setuptools=latest wheel=latest app_data_dir=C:\Users\neela\AppData\Local\pypa\virtualenv\seed-v1 via=copy

(mysubject) C:\Users\neela>workon mysubject
(mysubject) C:\Users\neela>pip install django
Collecting django
  Using cached Django-3.0.3-py3-none-any.whl (7.5 MB)
Collecting asgiref~=3.2
  Using cached asgiref-3.2.3-py2.py3-none-any.whl (18 kB)
Collecting sqlparse>=0.2.2
  Using cached sqlparse-0.3.1-py2.py3-none-any.whl (40 kB)
Collecting pytz
  Using cached pytz-2019.3-py2.py3-none-any.whl (509 kB)
Installing collected packages: asgiref, sqlparse, pytz, django
Successfully installed asgiref-3.2.3 django-3.0.3 pytz-2019.3 sqlparse-0.3.1

(mysubject) C:\Users\neela>django-admin startproject myapp

(mysubject) C:\Users\neela>cd myapp

(mysubject) C:\Users\neela\myapp>dir
 Volume in drive C is Windows-SSD
 Volume Serial Number is 82E8-1697

 Directory of C:\Users\neela\myapp

03/03/2020  10:40 PM    <DIR>          .
03/03/2020  10:40 PM    <DIR>          ..
03/03/2020  10:40 PM               646 manage.py
03/03/2020  10:40 PM    <DIR>          myapp
               1 File(s)            646 bytes
               3 Dir(s)  388,397,584,384 bytes free

(mysubject) C:\Users\neela\myapp>python manage.py runserver
Watching for file changes with StatReloader
Performing system checks...

System check identified no issues (0 silenced).

You have 17 unapplied migration(s). Your project may not work properly until you apply the migrations for app(s): admin, auth, contenttypes, sessions.
Run 'python manage.py migrate' to apply them.
March 03, 2020 - 23:23:31
Django version 3.0.3, using settings 'myapp.settings'
Starting development server at http://127.0.0.1:8000/
