# django-angular-rest

## Introduction
Based on the great example originally published by Thinkster at https://github.com/brwr/thinkster-django-angular-boilerplate

While the original contains references that are specific to the Thinkster tutorial(s), this project is intended to be a rapid way to scaffold any Django/AngularJS app with generic naming conventions that can be used in any project.


## Installation

*NOTE: Requires [virtualenv](http://virtualenv.readthedocs.org/en/latest/),
[virtualenvwrapper](http://virtualenvwrapper.readthedocs.org/en/latest/) and
[Node.js](http://nodejs.org/).*

In your project folder:
* `$ git clone https://github.com/Goodworx/django-angular-rest.git`
* Rename cloned folder to anything you want. This is is your source folder. Ie:
* `$ mv django-angular-rest source`
* `$ cd source`
* `$ mkvirtualenv your-project-name`
* For development, switch to the virtualenv:
* `$ workon your-project-name`
* Then install the dependencies:
* `$ pip install -r requirements.txt`
* `$ npm install -g bower`
* `$ npm install`
* `$ bower install`
* Migrate your Django database:
* `$ python manage.py migrate`
* Now you should be able to run the fully scaffolded Django/Angular app:
* `$ python manage.py runserver`
