# django-hybridize
Django plugin app that allows apps to be consumed in native-hybrid mobile apps.

Installation

  $ pip install -e git+https://github.com/charlon/django-hybridize/#egg=hybridize

settings.py 

  Add 'hybridize' to INSTALLED_APPS

In your project/app...

Standalone hybrid app

  just extend the hybridize base template using hybrid_content block
  
Addaptive hybrid app
