# Website-creation-using-Django

Django Project Steps:

1. Go to any working directory you want.

2. Use following command to create Virtualenv space
       
             Windows: mkvirtualenv mysubject


3. Go into your Virtualenv space using:
       
              Windows: workon mysubject

4. Install Django inside Virtualenv space using:
        
              pip install Django

5. Check Django version using:
       
              python -m django --version

6. Create first project using:
       
             django-admin startproject myapp

7. Check if project is built successfully, go to mysite directory first:
             
             python manage.py runserver

8. Create app called personalweb using:
          
            python manage.py startapp personalweb

9. Set up project url using information provided in mysite_url.txt(Django2 and Django1 aredifferent)


10. Go to personalweb directory, create a file called urls.py, copy paste the information provided inpersonalweb_url.txt


11. Add your personalweb app to settings.py (add following code to INSTALLED_APPS section):
                 
              'personalweb.apps.PersonalwebConfig',

12. Go to personalweb directory, define a new view called index in views.py.(information providedin personalweb_view.txt)



13. Go to personalweb directory, create a directory called templates. In templates, create adirectory called personalweb, in personalweb create a file called index.html. ( content ofindex.html is provided in index_html.txt)







