[![Build Status](https://travis-ci.org/MrNuggelz/sklearn-lvq.svg?branch=stable)](https://travis-ci.org/MrNuggelz/sklearn-lvq)
[![Build status](https://ci.appveyor.com/api/projects/status/qiwkue1x5lgll382?svg=true)](https://ci.appveyor.com/project/MrNuggelz/sklearn-glvq)
[![CircleCI](https://circleci.com/gh/MrNuggelz/sklearn-lvq.svg?style=shield)](https://circleci.com/gh/MrNuggelz/sklearn-lvq)
[![Coverage Status](https://coveralls.io/repos/github/MrNuggelz/sklearn-lvq/badge.svg)](https://coveralls.io/github/MrNuggelz/sklearn-lvq)

# Warning

Repository and Package Name changed to sklearn-lvq!

# Generalized Learning Vector Quantization
Scikit-learn compatible implementation of GLVQ, GRLVQ, GMLVQ, LGMLVQ
RSLVQ, MRSLVQ and LMRSLVQ.

Compatible with Python2.7 and Python3.6

This implementation is based on the Matlab implementation
provided by Biehl, Schneider and Bunte (http://matlabserver.cs.rug.nl/gmlvqweb/web/)

## Important Links
- scikit-learn (http://scikit-learn.org/)
- documentation (https://mrnuggelz.github.io/sklearn-lvq/)

## Installation
Before you can install this module you need to install `numpy` and `scipy`:
```
pip install numpy scipy
```
To install this module run:
```
python setup.py install
```
or
```
pip install sklearn-lvq
```

## Examples
To run the examples `matplotlib` is needed
```
pip install matplotlib
```
The examples can be found in the examples directory.

## Testing
Requires installation of `nose` package.
```
pip install nose
```
Tests are located in the `sklearn_lvq/tests` folder
and can be run with the `nosetests` command in the main directory.

## Documentation
To build the documentation locally, ensure that you have sphinx, sphinx-gallery, pillow, sphinx_rt_theme, metric_learn and matplotlib by executing:

```
pip install sphinx pillow sphinx-gallery sphinx_rtd_theme metric_learn
```
