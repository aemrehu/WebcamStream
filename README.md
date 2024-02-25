# WebcamStream

Simple Django app to stream webcam video over local network

## Instructions

- Follow https://docs.djangoproject.com/en/5.0/intro/tutorial01/ instructions to create project.
- Then copy views.py and setup urls.py
- Move Django secret key from settings.py to secret-key.txt and ignore the file from Git if you plan on publishing on Git.

### Install requirements
    pip install -r requirements.txt

### Run
    python manage.py runserver (optional:) <ip:port> or <port>