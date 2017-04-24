# first-flask
My first python / flask tutorial repo

https://scotch.io/tutorials/getting-started-with-flask-a-python-microframework

$ pip install virtualenv
$ pip install virtualenvwrapper
$ export WORKON_HOME=~/Envs
$ source /usr/local/bin/virtualenvwrapper.sh

$ mkvirtualenv my-venv
$ workon my-venv

$ mkdir my-project
$ cd my-project

$ pip install Flask

$ pip freeze
click==6.6
Flask==0.11.1
itsdangerous==0.24
Jinja2==2.8
MarkupSafe==0.23
Werkzeug==0.11.11

$ pip freeze > requirements.txt

$ export FLASK_APP=hello_world.py
$ flask run
 * Serving Flask app "hello_world"
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
