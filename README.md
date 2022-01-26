# Django-Authentication-APP
Django authentication app, with design, login and register. Used Database PostgreSQL



# Instalation
#### Create the virtualenv and activate

1.virtualenv venv
2.source venv/bin/activate

#### Install the requirements
bash
pip install -r requirements.txt


#### Migrate and Runserver
bash
python manage.py makemigrations
python manage.py migrate
python manage.py runserver

#### Change the Datbase Settings in Advantage.settings.py
bash
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'database name',              #YOUR DATABASE NAME
        'USER': 'postgres',                   #USER NAME
        'PASSWORD': 'postgresql password',    #YOUR PASSWORD
        'HOST': 'localhost',
    }
}

#Example

## When you run the server go to http://127.0.0.1:8000/
 

