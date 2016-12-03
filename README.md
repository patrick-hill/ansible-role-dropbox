Ansible Role: Dropbox
=========

[![Build Status](https://travis-ci.org/patrick-hill/ansible-role-dropbox.svg?branch=master)](https://travis-ci.org/patrick-hill/ansible-role-dropbox)
[![Ansible Galaxy](https://img.shields.io/badge/ansible--galaxy-patrick--hill.dropbox-blue.svg)](https://galaxy.ansible.com/patrick-hill/dropbox)


Installs [DropBox](https://www.dropbox.com) on Debian based OS.

Requirements
------------

Ansible 1.8+

Role Variables
--------------

    dropbox_version
"dropbox_version" is the dropbox version to install
    
Dependencies
------------

None.

Example Playbook
----------------

    - hosts: localhost
      gather_facts: yes
      roles:
         - role: patrick-hill.dropbox 

License
-------

BSD

Author Information
------------------

Role written in 2016 by [Patrick Hill](http://www.HillsPCWorld.com) 
