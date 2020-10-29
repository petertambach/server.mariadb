Role Name
=========

MariaDB, install MariaDB server / client for Debian and Centos machines.
Default is version 10.4
Currently CentOS 7 is tested up to MariaDB version 10.5

Requirements
------------

Just make sure Ansible has access.

Example Playbook
----------------

    - hosts: all
      roles:
        - mariadb
      vars:
        - mariadb_version: 10.5 # optional
        - mariadb_secure_installation: True
        - mariadb_root_password: "some incredible difficult password goes here"

TODO
----

- Make todo and finish role

License
-------

BSD

Author
------
Peter Tambach, info@petertambach.com
