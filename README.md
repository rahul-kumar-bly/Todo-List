# Simple-Todo-WebApp-In-Django
A simple django based todo app which allows registered user to create/edit/delete task with functionality to mark as complete and revert back to un-complete.

# How to get started with this app?

Activate virtual environment in your system. 

For windows, type 
`.venv/bin/activate`

For Linux, type 
`source .venv/bin/activate`
  
Create database using
```
python manage.py makemigrations
python manage.py migrate --run-syncdb
```

Run the server using
`python manage.py runserver`
