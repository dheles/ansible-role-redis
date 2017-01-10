Ansible Role: Redis
=========

Installs ~~and configures~~ the Redis in-memory data structure store

WIP Notice
----------
This role is a Work-In-Progress. It will improve when I have a project that justifies the additional effort, when I have time to burn on it, or someone contributes a pull-request. It is limited in the following ways:

* This could not be much more basic.
* Installs only from the OS package manager
* Only tested against a very limited set of OSes/versions

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

    - hosts: app
      roles:
         - { role: redis }

License
-------

CC0

Author Information
------------------

Drew Heles
