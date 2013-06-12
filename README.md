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

To configure the test environment on Windows,
first download and install `Python2.7.3` from the official 
[website](http://www.python.org/download/releases/2.7.3/), 
then [download](http://www.lfd.uci.edu/~gohlke/pythonlibs/#pip) and 
install `pip-1.3.1.win-amd64-py2.7.‌exe`.
`PyYAML` is also required. Please download and unzip from 
[here](http://pyyaml.org/download/pyyaml/PyYAML-3.10.zip), and 
run `python setup.py install` and `python setup.py test` to install.
Last but most important, please install the python binding of
`selenium` with `pip install selenium`.


## Usage

usage: `python run-test-suite.py [-h] [-c CONFIGFILE]`

optional arguments:

  -h, --help            show this help message and exit
  
  -c CONFIGFILE, --configfile CONFIGFILE
  
                        provide your YAML file for test configuration here.
                        
                        The defalt file is firefox-test-config.yaml which can
                        
                        server as an example.
