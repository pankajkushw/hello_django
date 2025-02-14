# hello_django
django_testing app

Django Setup in my machine
--------------------------
1. sudo apt install python3-pip

# Linux
sudo apt-get install python3-venv    # If needed
python3 -m venv .venv
source .venv/bin/activate

before commit:
git config --global user.name "pankajkushw"
git config --global user.email "pankaj.kushw@gmail.com"


Command Palette (View > Command Palette or (Ctrl+Shift+P)). Then select the Python: Select Interpreter command:


python -m pip install --upgrade pip

python -m pip install django

--django installed in venv-----------------
django-admin startproject web_project .     //project create files in web_project folder
python manage.py migrate                   // it creates a default SQLite database in the file db.sqlite3

python manage.py runserver.  //run server The install worked successfully! Congratulations!

Create a Django app



