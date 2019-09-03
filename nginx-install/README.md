Role Name
=========

This is the simple role for installing nginx in Linux environment

Requirements
------------

User must have sudo access

Role Variables
--------------
Nothing

Dependencies
------------
ansible gather facts must be on

Example Playbook
----------------

Including this role

    - hosts: servers
      roles:
         - { role: srinics.nginx-install }

License
-------

BSD

Author Information
------------------
Srinivasan Rajendran
