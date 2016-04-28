ansible-elasticsearch-packages
==============================

[![Build Status](https://travis-ci.org/jmatt/ansible-elasticsearch-packages.svg?branch=master)](https://travis-ci.org/jmatt/ansible-elasticsearch-packages)

Install elasticsearch v 5.0 packages for LSST SQuaRE infrastructure.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: jmatt.elasticsearch-packages }

License
-------

See the [LICENSE file](https://github.com/jmatt/ansible-elasticsearch-packages/blob/master/LICENSE).
