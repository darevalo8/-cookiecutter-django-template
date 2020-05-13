# Template cookie cutter Django


[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

This tool allows you to create an organized Django project structure, making easier the process of development and deploy to production.
The benefits of this template are:
  - Better structured projects
  - Added docker configuration

This tool is inspired by pydany's work https://github.com/pydanny/cookiecutter-django, collecting functions that I currently need. I hope other developers who 
have these needs will use this tool.

### Installation

Template cookie cutter Django requires [Cookie cutter] last version to run.

Install Cookie cutter

```sh
pip install cookiecutter
```

Create a new project

```sh
 cookiecutter https://github.com/darevalo8/cookiecutter-django-template
 cd [project name] 
 docker-compose -f local.yml build
```
The above commands work for both local and production

To test the project
```sh
 docker-compose -f local.yml up
```


License
----

MIT



