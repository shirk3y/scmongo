=======
Scrapy httpcache mongo
=======

A MongoDB backend for HTTP cache storage. It stores responses using GridFS.

Requirements
============

* Scrapy 0.14 or above
* pymongo 2.4 or above

Install
=======

Download and run: ``python setup.py install``

or

``pip install -e git+https://github.com/shirk3y/scrapy-httpcache-mongo.git#egg=scrapy-httpcache-mongo``

Usage
=====

To use it, set the following Scrapy setting in your project::

    HTTPCACHE_STORAGE = 'scmongo.httpcache.MongoCacheStorage'
