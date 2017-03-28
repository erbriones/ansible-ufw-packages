ansible-ufw-packages
--------------------

[![Build Status](https://travis-ci.org/erbriones/ansible-ufw-packages.svg?branch=master)](https://travis-ci.org/erbriones/ansible-ufw-packages)

Install UFW firewall packages.

Role Variables
--------------

- `disable_alternative_firewall` (Optional) - Disables alternative system firewall (default value yes).

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: erbriones.ufw-packages }

License
-------

The MIT License. See the [LICENSE file](https://github.com/erbriones/ansible-ufw-packages/blob/master/LICENSE).
