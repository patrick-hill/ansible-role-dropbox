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

The below are defined in vars and defaults: `vars/main.yml and defaults/main.yml`:

    dropbox_version
"dropbox_version" is the dropbox version to install

    dropbox_interactive_install
"dropbox_interactive_install" determines if you want Ansible to wait for you to run the manual command `dropbox start -i` on the target machien to complete the run

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: localhost
      gather_facts: yes
      vars:
        dropbox_interactive_install: true
      roles:
         - role: patrick-hill.dropbox 

License
-------

BSD

Author Information
------------------

Role written in 2016 by [Patrick Hill](http://www.HillsPCWorld.com) 
