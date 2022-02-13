# Django Project Starter 2

A rewrite of my original Django starter project.

The goal is to include:

* A Django project with usable configurations and folder structure
* Rest Framework configured for example app (has a simple Event model)
* Authentication ready to go (has a login page with standard authentication functionality)
* Cors ready for frontend UI (you should be able to use Vue, React or Angular)
* Ability to change project name to project name of your choice

## How to Develop

Steps:

1. Clone the project in a directory of your choice:
  ```
  git clone git@github.com:hseritt/django-project-starter2.git
  ```

2. Check the runtime.txt file. For example, if it's python-3.10.2, then you should install Python 3.10.2 (though it should work mostly with any Python 3.8+ interpreter). I prefer to use "pyenv" to install different versions of Python for my local projects but use any method you prefer.

3. Build a virtual environment. I prefer to use "pyenv virtualenv [env.name]" but use any method you prefer.
  ```
  pyenv virtualenv django-project-starter2
  pyenv local django-project-starter2
  ```

4. Install the packages in the requirements.txt file:
  ```
  pip install -r requirements.txt
  ```

## How to Use

Steps:

1. Clone the project in a directory of your choice:
  ```
  git clone git@github.com:hseritt/django-project-starter2.git
  ```

2. Go into the directory created:
  ```
  cd django-project-starter2
  ```

3. Make change-project.sh executable:
  ```
  chmod +x change-project.sh
  ```

4. Run change-project.sh with new project name:
  ```
  ./change-project.sh [ new_project_name ]
  
  # note that the project name needs to conform to Django project naming conventions
  ```

5. (Optional) Run migrations and create an admin superuser if you like:
  ```
  ./manage.py makemigrations
  ./manage.py migrate
  ./manage.py createsuperuser
  ./manage.py runserver
  ```

6. Go http://localhost:8000/example for the example app (it doesn't do anything really). To check out the Rest API, go to http://localhost:8000/api.
   
