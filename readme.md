# Python Virtual Environment Setup
## Requirements 
Python 3.3 or later

## Checking installed packages
$ pip3 list

## Creating virtual environment directory
In the desired working directory, use the command
$ python -m venv (new project/directory name)

## Activating virtual environment (Linux/MacOS)
$ source (new project/directory name)/bin/activate

## Activating virtual environment (Windows)
$ .\(new project/directory name)\Scripts\activate

## Checking python version in virtual environment
$ python --version

## Checking packages in virtual environment
$ pip3 list

# Install Desired packages using pip
## Caching the dependencies using
$ pip freeze

## Saving to requirements.txt
$ pip freeze > requirements.txt

## Deactivating virtual environment
$ decativate

## Deleting virtual environment folder
$ rm -r (new project/directory name)

# Reactivating
Follow the steps of setting up the virtual environment
After that use the command
$ pip install -r requirements.txt

# Note for version control
Add the virtual environment folder to .gitignore
