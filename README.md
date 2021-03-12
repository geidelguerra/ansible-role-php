ansible-role-php
=========

Install PHP and optionally FPM

Requirements
------------

None

Role Variables
--------------

php_version: 7.4
php_fpm: no

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: geidelguerra.ansible-role-php, php_version: 7.4, php_fpm: yes }

License
-------

MIT

Author Information
------------------

Geidel Guerra
