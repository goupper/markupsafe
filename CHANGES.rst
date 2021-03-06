.. currentmodule:: markupsafe

MarkupSafe Changelog
====================


Version 1.1
-----------

Unreleased

- ``escape`` wraps ``__html__`` result in ``Markup``, consistent with
  documented behavior. (`#69`_)

.. _#69: https://github.com/pallets/markupsafe/pull/69


Version 1.0
-----------

-   Fixed custom types not invoking ``__unicode__`` when used with
    ``format()``.
-   Added ``__version__`` module attribute.
-   Improve unescape code to leave lone ampersands alone.


Version 0.18
------------

-   Fixed ``__mul__`` and string splitting on Python 3.


Version 0.17
------------

-   Fixed a bug with broken interpolation on tuples.


Version 0.16
------------

-   Improved Python 3 Support and removed 2to3.
-   Removed support for Python 3.2 and 2.5.


Version 0.15
------------

-   Fixed a typo that caused the library to fail to install on pypy and
    jython.


Version 0.14
------------

-   Release fix for 0.13.


Version 0.13
------------

-   Do not attempt to compile extension for PyPy or Jython.
-   Work around some 64bit Windows issues.


Version 0.12
------------

-   Improved PyPy compatibility.
