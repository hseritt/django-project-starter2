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
