# Python-Github-Onboarding
This repository is a short introduction and collection of best practices for dev projects using Python in VSCode.

# Virtual Environment
One of the main advantages in using python for a project is the ease of access to a host of third party packages useing something called the pip installer. By simply running:
```
pip install name_of_package
```
A desired package will be installed into your development environment, However what happens when you have multiple projects requireing different python versions?

Python has a feature called a virtual environment (venv for short) that enables a user to specify and save a local version of a dev environment with a specific python version separate from the default global environment.

useful commands:
```
pip freeze > requirements.txt
```

```
pip install -r requirements.txt
```
