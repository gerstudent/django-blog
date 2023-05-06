# Introduction

Repository contains source code for blog application written in Django framework. Project was created in educational purposes.

## Prerequisites
Be sure you have the following installed on your development machine:

1. Python >= 3.7
2. Git
3. pip 
4. Virtualenv

## Setup

To run this project in your development machine, follow these steps:

1. (optional) Create and activate a [virtualenv](https://virtualenv.pypa.io/).

2. Ensure that the executable `pg_config` is available on your machine. You can check this using `which pg_config`. If not, install the dependency with one of the following.
  - macOS: `brew install postgresql` using [Homebrew](https://brew.sh/)
  - Ubuntu: `sudo apt-get install libpq-dev`
  - [Others](https://stackoverflow.com/a/12037133/8122577)

3. Fork this repo and clone your fork:

    `git clone https://github.com/gerstudent/django-blog`

4. Install dependencies:

    `pip install -r requirements.txt`

5. Create a development database:

    `./manage.py migrate`

6. If everything is alright, you should be able to start the Django development server:

    `./manage.py runserver`

7. Open your browser and go to http://127.0.0.1:8000, you will be greeted with a welcome page.


## Special files in this repository

Apart from the regular files created by Django (`project/*`, `welcome/*`, `manage.py`), this repository contains:

```
django-blog/         
├── templates          - application templates
└── requirements.txt   - list of dependencies
```
