# django-hybridize
Django plugin app that allows web apps to be consumed in a Turbolinks native adapter
and uses Framework7 to style the web content to look native.

Installation

  $ pip install -e git+https://github.com/charlon/django-hybridize/#egg=hybridize

settings.py

  Add 'hybridize' to INSTALLED_APPS

In your project/app...

Standalone hybrid app

  just extend the hybridize base template using hybrid_content block

Overwrite the theme .scss files

ios-theme.scss  
android-theme.scss

Add your own .scss files as needed.
