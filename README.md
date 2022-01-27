# Django Letsgo

A shell script to automate the django project creation process. This also includes the initial routing. The following actions are performed when you run this script: 
* Creation of the project folder 
* Creating and activating virtual enviroment
* Updating pip to latest version
* Installing neccessary pip packages
* Starting django project `django-admin startproject`
* Starting an app `python manage.py startapp`
* Writing to settings .py, urls .py, views .py, templates
* Adding static files to project
* Making migrations and migrating them
* Running the server for the first time
* Add an AuthApp with working login and Register


## Getting Started

To get started, download the latest release and extract the files on your PC

### Usage
* Place the script anywhere you wish
* Open the folder in Git-Bash and type the following command
```
$ source django-letsgo -p <projectname>
    
    flags:
     -p <projectname> : Start a django project with the name <projectname>
     -a               : Start the authapp with working login and register pages
     -h               : Show this help
```
* Wait for few seconds and your server is running.


## Contributing
To contribute just make a [PR](https://github.com/neerajadhav/django-letsgo)

