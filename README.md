# FINE BANK 

This is a remake of another project of mine, made during a python bootcamp. 
[First-project]()

## INDEX

### ABOUT THIS PROJECT


### 


### DATABASE

As you can see in bank_setup/settings.py, I'm using sqlite3 as a database, for practicality. But these settings could be easily changed. For example, I usually use the following formatting as my database model using mySQL:

>DATABASES = {
>    'default': {
>        'ENGINE': 'django.db.backends.'+os.getenv('ENGINE'),
>        'NAME': os.getenv('NAME'),
>        'USER': os.getenv('USER'),
>        'PASSWORD': os.getenv('PASSWORD'),
>        'HOST': os.getenv('HOST'),
>        'PORT': os.getenv('PORT'),
>    }
>}

Sensitive data is kept safe in an .env file (keeping in the .gitignore list):

>SECRET_KEY='secret-key-from-django'
>ENGINE='mysql'
>NAME='db-name'
>USER='root-or-other'
>PASSWORD='user-password'
>HOST='host-ip'
>PORT='number-of-the-port'

