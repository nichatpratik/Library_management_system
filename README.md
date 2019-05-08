# Library_management_system
A simple library management system for displaying the online catalog for the library. 

### Installing the project
1. Go to the directory on your machine where you want to store your project repositories: `cd ~/projects` (or something similar)
2. Clone this repository: `git clone https://github.com/nichatpratik/Library_management_system.git`
3. Change directory: `cd library`
4. I have created a virtual environment: `python3 -m venv ENV`
5. Activate the environment `source ENV/bin/activate`
6. Install the dependencies: `pip install -r requirements.txt` 
7. Change directories to the django project: `cd library`

Now you are all set to run the Django management commands

## Some common Django management commands you will want to use

- `python manage.py shell` starts the Python interpreter that is Django aware.
- `python manage.py dbshell` starts the shell for SQLite3 (or whatever RDBMS you configure)
- `python manage.py runserver` runs your application on port 8000 (point your browser at http://127.0.0.1:8000)
- `python manage.py test catalog` runs the test suite in the `catalog/tests.py` file
- `python manage.py makemigrations` checks for changes to your models and makes a migration file
- `python manage.py migrate` converts migration files to SQL and implements the changes in the database
