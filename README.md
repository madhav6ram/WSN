## Wireless Sensor Network Simulator

This is a working fork of [WSN by darolt](https://github.com/darolt/wsn).
The repository has been updated to support Python 3.10 and the stable g++ compiler version.

### Requirements:
 - Python 3.10
 - g++
 - Various pip packages
 
### Run:
 - (Optional) Configure the variables and scenarios in config.py for testing.
 - Compile C++/Python3 wrappers using `python3 setup.py build_ext --inplace`.
 - Run using `python3 run.py`.
### TODO: 
 - Fix / Add graphs and fix NaN value "issues" in certain algorithm results.
 - Implement modern routing algorithms, suggested by scientific literature.
 - Change hard coded python 3.10 interpreter to support any version.
 - Improve formatting.
 
