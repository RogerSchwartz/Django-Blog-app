🚀 Features
•	Django 3.1.0 & Python 3.9.7

•	Install via Pip, Pipenv 

•	User log in/out, sign up, password reset

•	Static files configured with Whitenoise

•	Styling with Bootstrap v4

•	Image upload



📖 Installation
It is possible to install Django using pipenvor pip. To start, clone the repo to your local machine and place it in a suitable directory.

$ git clone https://github.com/wsvincent/djangox.git
$ touch Django blog
$ cd Django blog

Pip
$ python -m venv .venv

# Windows
$ Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser

$ .venv\Scripts\Activate.ps1

# macOS
$ source djangox/bin/activate

$ pip install -r requirements.txt

$ python manage.py migrate

$ python manage.py createsuperuser

$ python manage.py runserver

# Load the site at http://127.0.0.1:8000

Pipenv
$ pipenv install

$ pipenv shell

$ python manage.py migrate

$ python manage.py createsuperuser

$ python manage.py runserver

# Load the site at http://127.0.0.1:8000
