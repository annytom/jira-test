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

[![ScreenShot](https://raw.github.com/yadongwen/misc-scripts/master/screenshot.jpg)](http://youtu.be/E-C9EBM7KmI)

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

To run the test, use `python run-test-suite.py [-h] [-c CONFIGFILE]`

You may use the -c switch to specify the test configuration file you
want to use. The default file is `firefox-test-config.yaml`. (The
other two for Chrome and IE are not well tested and debugged yet.)

You may add new test cases to `YAML` files under the `test-input` folder.
Be careful when modifying the test config files and please follow the
`YAML` syntax.

Detailed test execution result will be echoed to console. Highlevel
test result is under the `test-output` folder.

There is a module called `gen-input-from-raw.py` is provided to generate
test config `YAML` files from 'raw' YAML files. It's not well tested yet.
