django-axes
-------------

[![Jazzband](https://jazzband.co/static/img/badge.svg)](https://jazzband.co/) [![GitHub](https://img.shields.io/github/stars/jazzband/django-axes.svg?label=Stars&style=socialcA)](https://github.com/jazzband/django-axes) [![PyPI release](https://img.shields.io/pypi/v/django-axes.svg)](https://pypi.org/project/django-axes/) [![Supported Python versions](https://img.shields.io/pypi/pyversions/django-axes.svg)](https://pypi.org/project/django-axes/) [![Supported Django versions](https://img.shields.io/pypi/djversions/django-axes.svg)](https://pypi.org/project/django-axes/) [![Documentation](https://img.shields.io/readthedocs/django-axes.svg)](https://django-axes.readthedocs.io/) [![Coverage](https://codecov.io/gh/jazzband/django-axes/branch/master/graph/badge.svg)](https://codecov.io/gh/jazzband/django-axes)

Axes is a Django plugin for keeping track of suspicious
login attempts for your Django based website
and implementing simple brute-force attack blocking.

The name is sort of a geeky pun, since it can be interpreted as:

* ``access``, as in monitoring access attempts, or
* ``axes``, as in tools you can use to hack (generally on wood).


Functionality
-------------

Axes records login attempts to your Django powered site and prevents attackers
from attempting further logins to your site when they exceed the configured attempt limit.

Axes can track the attempts and persist them in the database indefinitely,
or alternatively use a fast and DDoS resistant cache implementation.

Axes can be configured to monitor login attempts by
IP address, username, user agent, or their combinations.

Axes supports cool off periods, IP address whitelisting and blacklisting,
user account whitelisting, and other features for Django access management.


Documentation
-------------

For more information on installation and configuration see the documentation at:

https://django-axes.readthedocs.io/


Issues
------

If you have questions or have trouble using the app please file a bug report at:

https://github.com/jazzband/django-axes/issues


Contributing
------------

See `CONTRIBUTING <CONTRIBUTING.rst>`__.
