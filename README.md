Ansible Role: install etckeeper
=========

[![Build Status](https://travis-ci.org/officel/ansible-role-etckeeper.svg?branch=master)](https://travis-ci.org/officel/ansible-role-etckeeper)
[![Ansible Role](https://img.shields.io/badge/galaxy-officel.etckeeper-blue.svg?maxAge=2592000)](https://galaxy.ansible.com/officel/etckeeper/)

Install & init etckeeper.

Requirements
------------

use epel repository.

maybe require git config user.name & email on CentOS 7.
see test/Dockerfile.centos-7.

    git config --global user.name  "rooooot"
    git config --global user.email "rooooot@localhost"


Role Variables
--------------

none.

Dependencies
------------

none.

Example Playbook
----------------

    - hosts: all
      become: true
      roles:
         - officel.etckeeper

License
-------

MIT / BSD

Author Information
------------------

This role was created by raki.
