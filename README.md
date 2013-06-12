jira-test
=========

This is a demo function test suite for JIRA using selenium webdriver. 
The test suite is written in Python using unittest. It covers three 
major use cases: 

* issue creation
* issue searching
* issue updating

The test boasts the following features:

* data-driven
* cross-platform
* multi-browser support
* loosely coupled
* easy to extend
* easy to maintain

Here is a short video for a quick introduction.

[![ScreenShot](https://raw.github.com/yadongwen/misc-scripts/master/screenshot.jpg)](http://youtu.be/vt5fpE0bzSY)

## Requirements

Below are the steps to configure the test environment on Windows.
First download and install `Python2.7.3` from [here](http://www.python.org/download/releases/2.7.3/).
Then install `pip-1.3.1.win-amd64-py2.7.‌exe` from [here](http://www.lfd.uci.edu/~gohlke/pythonlibs/#pip).
`PyYAML` is also required. Please download and unzip from [here](http://pyyaml.org/download/pyyaml/PyYAML-3.10.zip).
Then run the following commands to install:

* `python setup.py install`
* `python setup.py test`

## Usage
