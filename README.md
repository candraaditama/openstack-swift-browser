# openstackswiftbrowser

An OpenStack Web Browser template that I build for my studies. Update to Bootstrap 4 and update HMAC that caused error at upload page. Original script can be found at : https://github.com/cschwede/django-swiftbrowser 

How to use :

1. Install swiftbrowser:

pip install django-swiftbrowser

2. Copy files to /usr/local/lib/python2.7/dist-packages/swiftbrowser

You can copy all file or just "templates" folder and views.py

3. Run development server:

django-admin runserver 0.0.0.0:8000 --settings=swiftbrowser.settings
