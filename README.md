drupsible.xdebug
========================

Installs and configure the PECL xdebug extension.

Requirements
------------

This role requires PHP-FPM (Fast Process Manager) to be present (both PHP5 and PHP7 are supported).
This role can be used indepedently and does NOT require Drupsible to run.

Example Playbook
----------------

- name: PECL xdebug
  hosts: localhost
  become: True
  roles:
    - role: drupsible.xdebug

License
-------

GNU General Public License v3

Author Information
------------------

Mariano Barcia - [https://github.com/mbarcia](https://github.com/mbarcia)
