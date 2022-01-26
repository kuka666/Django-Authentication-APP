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
 
![image](https://user-images.githubusercontent.com/80199144/151259577-65ccea8c-85e1-4da1-9417-3c0e3358941c.png)

![image](https://user-images.githubusercontent.com/80199144/151259656-77de43be-d7dd-4e1c-a529-01d9eec3bb56.png)


![image](https://user-images.githubusercontent.com/80199144/151259624-884a82db-dfa6-4e2a-8ea0-e5f628e0a988.png)

![image](https://user-images.githubusercontent.com/80199144/151259598-09762e8d-4d7f-421f-9f4a-5f99f09348aa.png)

