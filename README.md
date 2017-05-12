Make sure that you have already django installed. If you haven´t get it here: https://www.djangoproject.com/
Also make sure that you get the Python Version 3.5. If you haven´t get it here: https://www.python.org/downloads/
For an easier handling also get pip. If you haven´t get it here: https://pip.pypa.io/en/latest/installing/

How to start on Windows:
1. Start an console and get into the directory where the project is.
2. Install an virtual wrapper with: pip install virtualenvwrapper-win
3. Start the django-enviroment with: mkvirtualenv tmp_ppsz_master
4. Install django on this enviroment with: pip install django
5. Get into the directory where manage.py is.
6. Initialise with: python manage.py migrate
7. Run the server with: python manage.py runserver

How to start on Linux:
1. Get into the directory where the project is.
2. Install django on this enviroment with: pip install django
3. Initialise with: python3 manage.py migrate
4. Run the server with: python3 manage.py runserver

After you have started the Server you can check your Browser on this site: http://127.0.0.1:8000/todo/
