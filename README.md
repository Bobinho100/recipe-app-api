# recipe-app-api
Recipe API project

#Creating a recipe-app-api, a backend solution for my app.
#Using docker for a safe and clean environment
#Using github actions for automation test, and linting
#using flake8 for linting

#Used postgresql , docker compose to configure our database,
presistent data using volume, handles network configuration environment variable configuration.

#volumes: persistent data, maps directory in container to local machine

#Django ORM: Django handles database structure and changes using ORM and you can also use any database

#Model: Each model maps to a table, it contains a name, some fields, other metadata
#Creating Migrations:Ensure app is enabled in settings.py
Use django CLI, python manage.py makemigrations

#Django comes with a built in authentication system, registration, login, auth.
#Abstract BaseUser: provides feautures for authentication
#email(EmailField)
#name(charField)
#is_active(BooleanField)
Is_staff(Boolean)

User model manager
used to manage objects
Custom logic for creating objects:
hash password

#django admin
graphical interface
create, update, delete and read
