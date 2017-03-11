[![Build Status](https://travis-ci.org/lndobryden/ansible-role-comskip.svg?branch=master)](https://travis-ci.org/lndobryden/ansible-role-comskip)
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

Example Playbook
----------------

```
    - hosts: servers
      roles:
         - lndobryden.comskip
```
License
-------

BSD

Author Information
------------------

Lee Dobryden - https://github.com/lndobryden
