Pipeline
========

.. image:: https://travis-ci.org/jazzband/django-pipeline.svg?branch=master
    :alt: Build Status
    :target: http://travis-ci.org/jazzband/django-pipeline

.. image:: https://coveralls.io/repos/github/jazzband/django-pipeline/badge.svg?branch=master
    :alt: Code Coverage
    :target: https://coveralls.io/github/jazzband/django-pipeline?branch=master

.. image:: https://jazzband.co/static/img/badge.svg
    :alt: Jazzband
    :target: https://jazzband.co/

.. image:: https://badge.fury.io/py/django-pipeline.svg
    :alt: PYPI
    :target: https://badge.fury.io/py/django-pipeline

.. image:: https://readthedocs.org/projects/django-pipeline/badge/?version=latest
    :alt: Documentation Status
    :target: https://django-pipeline.readthedocs.io/en/latest/?badge=latest


Pipeline is an asset packaging library for Django, providing both CSS and
JavaScript concatenation and compression, built-in JavaScript template support,
and optional data-URI image and font embedding.


Installation
------------

To install it, simply: ::

    pip install django-pipeline


Documentation
-------------

For documentation, usage, and examples, see :
https://django-pipeline.readthedocs.io


Note
-------------

This repository forked temporarily for Juniper release to add a patch which is not added by django-pipeline in version that supports Python3.5 and version tag used in upstream, for Juniper release, has a bug. The later version of django-pipeline's version supports Python>3.5. So, we added our patch on the django-pipeline==1.7.0. We can remove this fork when we will be using Python>3.5 and can use the version used by edx-platform