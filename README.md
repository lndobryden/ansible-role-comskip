Comskip
=========

An Ansible role for installing comskip (http://www.kaashoek.com/comskip/) on Linux
Currently supports Ubuntu 16.10
Comskip binaries install into /usr/local/bin/

Requirements
------------

Git must be installed before using this role

Role Variables
--------------

Currently none

Dependencies
------------

Git must be installed before using this role

Example Playbook
----------------

```
    - hosts: servers
      roles:
         - { role: lndobryden:comskip }
```
License
-------

BSD

Author Information
------------------

Lee Dobryden - https://github.com/lndobryden
