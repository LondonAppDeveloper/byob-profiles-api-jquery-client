# BYOB Profiles API jQuery Client

Example of a simple client for the Profiles API using jQuery.

## Setup

Before this will work with the profiles api project, the following changes must be made:

 - Install `django-cors-headers` with pip.
 - Add `corsheaders` to `INSTALLED_APPS` in settings.py.
 - Add `'corsheaders.middleware.CorsMiddleware',` above `django.middleware.common.CommonMiddleware` in `MIDDLEWARE` of settings.py
 - Add `CORS_ORIGIN_ALLOW_ALL = True` to the bottom of settings.py.

Once that is done, restart the API and simply open the `registration.html` file.
