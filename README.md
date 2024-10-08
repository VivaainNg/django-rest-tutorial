## Django Rest Tutorial
[![Django CI](https://github.com/VivaaindreanNg/django-rest-tutorial/actions/workflows/django-ci.yml/badge.svg)](https://github.com/VivaaindreanNg/django-rest-tutorial/actions/workflows/django-ci.yml)

This repo is just for me to keep track/practice on Django along with DRF (djangorestframework).

### To-do lists:

* [X] Remove the current/existing setups for Windows.

* [X] Setup new venv for Django.

* [X] Create a requirements.txt to list out all the necessary Python modules.

* [ ] Added functions-based views vs class-based views in Django.

* [ ] Implement unit-testing for views (using [APITestCase](https://www.django-rest-framework.org/api-guide/testing/#api-test-cases) from DRF).

* [ ] Implement [DRF Router](https://www.django-rest-framework.org/api-guide/routers/) for mapping of URL with views.

* [X] Setup [Github Actions YAML file](.github/workflows/github-actions-ci.yml) for automating unit testing.

* [ ] Add codecoverage tools in Github Action's workflow.

* [ ] Setup Docker for this project.

* [ ] Implement service layer (Based on Two Scoops of Django).

* [ ] Change from pip to [uv](https://astral.sh/blog/uv).


### Installing

A step by step guide on how to setup your local environment/setting.


1: Create a local venv(virtualenv)

```
$ python3 -m venv <envName>
```

2: Activate the venv

```
$ source <envName>/bin/activate
```

3: Install all the modules listed within requirements.txt

```
$ pip install -r requirements.txt
```

4. `cd` into **tutorialProject** and make `manage.py` file executable by:

```
$ chmod +x manage.py
```

4: To run the Django server at localhost:

```
$ ./manage.py runserver
```

5: To activate Django shell:

```
$ ./manage.py shell
```
