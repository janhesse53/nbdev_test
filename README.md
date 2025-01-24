# nbdev_test


<!-- WARNING: THIS FILE WAS AUTOGENERATED! DO NOT EDIT! -->

This file will become your README and also the index of your
documentation.

## Developer Guide

If you are new to using `nbdev` here are some useful pointers to get you
started.

### Install nbdev_test in Development mode

``` sh
# make sure nbdev_test package is installed in development mode
$ pip install -e .

# make changes under nbs/ directory
# ...

# compile to have changes apply to nbdev_test
$ nbdev_prepare
```

## Usage

### Installation

Install latest from the GitHub
[repository](https://github.com/janhesse53/nbdev_test):

``` sh
$ pip install git+https://github.com/janhesse53/nbdev_test.git
```

or from [conda](https://anaconda.org/janhesse53/nbdev_test)

``` sh
$ conda install -c janhesse53 nbdev_test
```

or from [pypi](https://pypi.org/project/nbdev_test/)

``` sh
$ pip install nbdev_test
```

### Documentation

Documentation can be found hosted on this GitHub
[repository](https://github.com/janhesse53/nbdev_test)’s
[pages](https://janhesse53.github.io/nbdev_test/). Additionally you can
find package manager specific guidelines on
[conda](https://anaconda.org/janhesse53/nbdev_test) and
[pypi](https://pypi.org/project/nbdev_test/) respectively.

## How to use

Fill me in please! Don’t forget code examples:

``` python
suits
```

    ['♤', '♡', '♢', '♧']

``` python
ranks
```

    [None, 'J', 'Q', 'K', 'A', '7', '8', '9', '10']

``` python
Card(1,3)
```

    NameError: name 'store_attr' is not defined
    [0;31m---------------------------------------------------------------------------[0m
    [0;31mNameError[0m                                 Traceback (most recent call last)
    Cell [0;32mIn[10], line 1[0m
    [0;32m----> 1[0m Card([38;5;241m1[39m,[38;5;241m3[39m)

    File [0;32m~/nbs/nbdev_test/nbdev_test/card.py:15[0m, in [0;36mCard.__init__[0;34m(self, suit, rank, trump)[0m
    [1;32m     13[0m [38;5;28;01mclass[39;00m [38;5;21;01mCard[39;00m:
    [1;32m     14[0m     [38;5;124m'[39m[38;5;124mA playing card[39m[38;5;124m'[39m
    [0;32m---> 15[0m     [38;5;28;01mdef[39;00m [38;5;21m__init__[39m([38;5;28mself[39m, suit:[38;5;28mint[39m, rank:[38;5;28mint[39m, trump:[38;5;28mint[39m[38;5;241m=[39m[38;5;241m11[39m): store_attr()
    [1;32m     16[0m     [38;5;28;01mdef[39;00m [38;5;21m__str__[39m([38;5;28mself[39m): [38;5;28;01mreturn[39;00m [38;5;124mf[39m[38;5;124m'[39m[38;5;132;01m{[39;00mranks[[38;5;28mself[39m[38;5;241m.[39mrank][38;5;132;01m}[39;00m[38;5;132;01m{[39;00msuits[[38;5;28mself[39m[38;5;241m.[39msuit][38;5;132;01m}[39;00m[38;5;124m'[39m 
    [1;32m     17[0m     [38;5;21m__repr__[39m [38;5;241m=[39m [38;5;21m__str__[39m

    [0;31mNameError[0m: name 'store_attr' is not defined
