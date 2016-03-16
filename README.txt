hyperopt: Distributed Asynchronous Hyper-parameter Optimization
===============================================================

Hyperopt is a Python library for serial and parallel optimization over awkward
search spaces, which may include real-valued, discrete, and conditional
dimensions.

Official project git repository:
http://github.com/hyperopt/hyperopt

Documentation:
http://hyperopt.github.io/hyperopt

Announcements mailing list:
https://groups.google.com/forum/#!forum/hyperopt-announce

Discussion mailing list:
https://groups.google.com/forum/#!forum/hyperopt-discuss


Thanks
------
This project has received support from
* National Science Foundation (IIS-0963668),
* Banting Postdoctoral Fellowship program,
* National Science and Engineering Research Council of Canada (NSERC),
* D-Wave Systems, Inc.



Changes in https://github.com/jbajor/hyperopt
=============================================
* Fixed fmin function import. That fixes Trials when using Python 3.5
* Updated code to use the current version of pymongo
* dill is used instead of cPickle and is now a requirement

Unfortunately, tests are written for Python 2 and have not been run after
making changes. Above changes fix problems I had using Hyperopt, but might
not work for you. I might update tests and make further changes to the code
if time allows.
