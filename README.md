KMlogger
========

[![Build Status](https://travis-ci.org/kylemede/KMlogger.svg?branch=master)](https://travis-ci.org/kylemede/KMlogger)
[![PyPI version](https://badge.fury.io/py/KMlogger.svg)](https://badge.fury.io/py/KMlogger)
[![License](https://img.shields.io/badge/license-GPL-blue.svg)](https://github.com/kylemede/KMlogger/blob/master/LICENSE)
<!--[![Coverage Status](https://coveralls.io/repos/github/kylemede/KMlogger/badge.svg?branch=master)](https://coveralls.io/github/kylemede/KMlogger?branch=master)-->

A Python logging object that provides additional functionality beyond the standard module.


Installation Notes
==================
Only uses standardized Python libraries and KMlogger is hosted on PyPi.  Thus, the easiest way to install it is:
 
 $pip install KMlogger
 
 NOTE: On OSX it can be difficult to install psutil, which KMlogger uses to detect the number of CPUs, memory...  I will update KMlogger to not require psutil soon.  please email me at kylemede@gmail.com if this hasn't been done yet and is causing a problem for you.


License
-------

Copyright 2016 Kyle Mede and contributors.

KMlogger is free software made available under the GNU GPLv3 license. 
For details see the license.txt file.
