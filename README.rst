========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |requires|
        | |coveralls|
        | |codacy|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/python-daschbox/badge/?style=flat
    :target: https://readthedocs.org/projects/python-daschbox
    :alt: Documentation Status

.. |travis| image:: https://api.travis-ci.org/python-daschbox/python-daschbox.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/python-daschbox/python-daschbox

.. |requires| image:: https://requires.io/github/python-daschbox/python-daschbox/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/python-daschbox/python-daschbox/requirements/?branch=master

.. |coveralls| image:: https://coveralls.io/repos/python-daschbox/python-daschbox/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/python-daschbox/python-daschbox

.. |codacy| image:: https://img.shields.io/codacy/grade/	.svg
    :target: https://www.codacy.com/app/python-daschbox/python-daschbox
    :alt: Codacy Code Quality Status

.. |version| image:: https://img.shields.io/pypi/v/daschbox.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/daschbox

.. |wheel| image:: https://img.shields.io/pypi/wheel/daschbox.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/daschbox

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/daschbox.svg
    :alt: Supported versions
    :target: https://pypi.org/project/daschbox

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/daschbox.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/daschbox

.. |commits-since| image:: https://img.shields.io/github/commits-since/python-daschbox/python-daschbox/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/python-daschbox/python-daschbox/compare/v0.0.0...master



.. end-badges

daschbox utils box

* Free software: MIT license

Installation
============

::

    pip install daschbox

You can also install the in-development version with::

    pip install https://github.com/python-daschbox/python-daschbox/archive/master.zip


Documentation
=============


https://python-daschbox.readthedocs.io/


Development
===========

To run the all tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
