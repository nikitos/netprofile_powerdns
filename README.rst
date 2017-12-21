netprofile_powerdns
===================

Getting Started
---------------

- cd <directory containing this file>

- $venv/bin/pip install -e ./

- add config options to client section of ini file:

.. code:: INI

    [app:app_npclient]

    ...

    netprofile.client.pdns.ns1 = 1.2.3.4
    netprofile.client.pdns.ns2 = 4.3.2.1

- $venv/bin/pserve development.ini

