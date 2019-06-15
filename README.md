## Creating a new project
Upon starting a terminal, run
```
pipenv shell
```
This starts a shell in a virtual environment for this project specifically. 

Install whichever packages you need, such as
```
pipenv install flask==0.12.1 //for a specific version
pipenv install numpy
pipenv install pytest --dev //for a dev dependency
```
Lock the environment to push it to production
```
pipenv lock
```

## Installation
If you want to run the package as a user, install using 
```
pipenv install --ignore-pipfile
```
which ignores dev dependencies. 
If you want to run as a developer, type
```
pipenv install --dev
```

## Links
Pipenv: A Guide to the New Python Packaging Tool
https://realpython.com/pipenv-guide/
Python Application Layouts: A Reference
https://realpython.com/python-application-layouts/