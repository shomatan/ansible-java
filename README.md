Ansible role: Java
=========

Installs java.

Requirements
------------

None.

Role Variables
--------------

    java_packages:
      - java-1.8.0-openjdk

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: shomatan.java }

License
-------

MIT

Author Information
------------------