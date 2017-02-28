Ansible Memcached
=================

Ansible role to install and configure Memcached.

Required Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: memcached, memcached_port: 11212 }

License
-------

Apache

Author Information
------------------

Alok Jani S.
