reg
===
INSTRUCTIONS

1) download the reg folder from github - this is a django app

github- reg

1) Create a django project 
django-admin.py startproject myproject . 
2) Copy and paste the 'reg' folder into the same directory as manage.py 

3) open myproject/settings.py 
-add 'reg' to installed apps 

4) open myproject/urls.py 

-add this to urls 
url(r'^reg/', include('reg.urls')), 

5) sync database 
python manage.py sycncdb


example at djangoreg.herokuapp.com
