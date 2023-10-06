README

AFTER DOWNLOADING, FOLLOW THESE STEPS

THE VIRTUAL ENVIRONMENT IS NAMED VENV, WHICH IS THE PACKAGE MANAGER, SO INSTALL VENV
OPEN THE TERMINAL AND PERFORM THE FOLLOWING COMMANDS:

pip install venv
venv install
venv shell
(make sure the correct interpreter is running (venv should be incorportated within the name of the interpreter, if not, go to VIEW-> COMMAND PALLETTE, then type: "Python: Select interpreter" then choose the one with venv in the name))
cd ./django_proj
python manage.py runserver

DESCRIPTIONS: 
INSTALL VENV: pip install venv

INSTALL DEPENDENCIES:venv install

RUN THE VENV SHELL: venv shell

MAKE SURE YOU ARE IN THE APP DIRECTORY: cd ./django_proj

RUN THE SERVER:  python manage.py runserver
