Role Name
=========

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
