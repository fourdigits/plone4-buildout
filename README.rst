Introduction
============


A Plone 4 buildout that works in 2018:
Uses HTTPS pypi link, new zc.buildout and setuptools.

Ready for use with mr.developer and custom version pinnings.


Buildout
--------

Buildout like so::

    virtualenv --no-site-packages venv
    ./venv/bin/python bootstrap.py --buildout-version 2.11.4
    ./venv/bin/pip install setuptools==39.1.0
    ./bin/buildout


Custom eggs / version pinning
-----------------------------

See the `eggs.cfg` and `sources.cfg` in the `config` dir.
