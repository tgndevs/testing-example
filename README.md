# Superlists


[![Build Status](https://travis-ci.org/tgndevs/testing-example.svg?branch=master)](https://travis-ci.org/tgndevs/testing-example)
[![Style Status](https://app.snap-ci.com/tgndevs/testing-example/branch/master/build_image)](https://app.snap-ci.com/tgndevs/testing-example/branch/master)
[![Coverage Status](https://coveralls.io/repos/github/tgndevs/testing-example/badge.svg?branch=master)](https://coveralls.io/github/tgndevs/testing-example?branch=master)
[![Code Climate](https://codeclimate.com/github/tgndevs/testing-example/badges/gpa.svg)](https://codeclimate.com/github/tgndevs/testing-example)
[![Code Health](https://landscape.io/github/tgndevs/testing-example/master/landscape.svg?style=flat)](https://landscape.io/github/tgndevs/testing-example/master)
[![Requirements Status](https://requires.io/github/tgndevs/testing-example/requirements.svg?branch=master)](https://requires.io/github/tgndevs/testing-example/requirements/?branch=master)
[![AUR](https://img.shields.io/aur/license/yaourt.svg)]()

This Django application is for exemplify how important is including testing into your software projects.

The application have been copied from [hjwp/book-example](https://github.com/hjwp/book-example). The application is a website where users can create todo's lists and share between them.

![Main page](https://raw.githubusercontent.com/tgndevs/testing-example/master/main.png)

- [Slides](https://tgndevs.github.io/testing-example)
- [Online Demo](https://testing-example.herokuapp.com)

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

Bug reports and pull requests are welcome on GitHub at https://github.com/tgndevs/testing-example/issues and https://github.com/tgndevs/testing-example/pulls. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.


# License

The repository is available as open source under the terms of the [GPL License](https://opensource.org/licenses/GPL-2.0).
