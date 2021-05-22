# Python Library Template

Template for creating python libraries easily.

<br/>

## Why do I need this folders and files?

* python_lib_name: This folder will contain your library. It has to be renamed as your library's name.
* tests: Folder that will contain the tests for your library.
* venv: Not included in the repo because it has many files (check .gitignore). It is very recommended to have all the packages that need to be installed in the virtual environment, so that they don't interfere with the packages installed on your machine.
* requirements.txt: In this txt file I am leaving the basic packages that are needed to actually create a Python library. Install them before starting.
* setup.py: File that will help us build the library.

<br/>

## What are the steps I need to follow in order to create a new library?

1) Create a virtual environment to store all the dependencies that will be needed. This is highly recommended to ensure that the dependencies you add don't collide or conflict another dependencies that already are on your machine.

```
python -m venv <name of your venv>
source venv/bin/activate
```

2) Install the requirements.txt file.

```
pip install -r requirements.txt
```

3) You are ready to start coding! Remember to update the setup.py with the new dependencies you add.