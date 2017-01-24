# Superlists


[![Build Status](https://travis-ci.org/tgndevs/superlists.svg?branch=master)](https://travis-ci.org/tgndevs/superlists)
[![Style Status](https://app.snap-ci.com/tgndevs/superlists/branch/master/build_image)](https://app.snap-ci.com/tgndevs/superlists/branch/master)
[![Coverage Status](https://coveralls.io/repos/github/tgndevs/superlists/badge.svg?branch=master)](https://coveralls.io/github/tgndevs/superlists?branch=master)
[![Code Climate](https://codeclimate.com/github/tgndevs/superlists/badges/gpa.svg)](https://codeclimate.com/github/tgndevs/superlists)
[![Code Health](https://landscape.io/github/tgndevs/superlists/master/landscape.svg?style=flat)](https://landscape.io/github/tgndevs/superlists/master)
[![Requirements Status](https://requires.io/github/tgndevs/superlists/requirements.svg?branch=master)](https://requires.io/github/tgndevs/superlists/requirements/?branch=master)
[![AUR](https://img.shields.io/aur/license/yaourt.svg)]()

This Django application is to exemplify how important is including tests in our software projects.

The application has been copied from [hjwp/book-example](https://github.com/hjwp/book-example). The application is a website where users can create and share TODO lists.

![Main page](https://raw.githubusercontent.com/tgndevs/superlists/master/main.png)

- [Slides](https://tgndevs.github.io/superlists)
- [Online Demo](https://superlists-tgndevs.herokuapp.com)

## Authors

* [Adrian Moreno](https://github.com/adrianmo)
* [Guillermo Guerrero](http://github.com/ryanfox1985)
* [Jordi Pujol](https://github.com/jpahullo)


# Getting started with the Django app

## Install dependencies

For Production or Development environment:
```
pip3 install -r requirements.txt
```

For testing environment:
```
pip3 install -r requirements-test.txt
```

## Prepare the database:
To initialize the database execute:
```
python3 manage.py migrate
```

## Run server
To run the server execute:
```
python3 manage.py runserver 0.0.0.0:8000
```

# Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/tgndevs/superlists/issues and https://github.com/tgndevs/superlists/pulls. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.


# License

The repository is available as open source under the terms of the [GPL License](https://opensource.org/licenses/GPL-2.0).
