# Django-Simple-QuickStart

# How this repo was created?

Step 1: Create a directory to hold our Django project.
        mkdir Django-Simple-QuickStart
        cd Django-Simple-QuickStart

Step 2: Create Python3 virtual enironment and activate it.
        python3 -m venv venv
        source venv/bin/activate

Step 3: Install Django in using pip in the venv.
        pip install Django

Step 4: Create Django project in the current directory.
        django-admin startproject SimpleProject .

        [Notice the period (.) at the end of the command above. Need it to create project in the current directory itself]

        With this, you should have a dir structure that looks like this:
        > tree -L 1
        >   .
            ├── manage.py
            ├── README.md
            ├── SimpleProject
            └── venv

Step 5: Next, apply migrations to our project using the command:
        python3 manage.py migrate

Step 6: We can now run our Django server using the command:
        python3 manage.py runserver

        If you now visit the link 127.0.0.1:8000, you should be greeted with Django Welcome Page!