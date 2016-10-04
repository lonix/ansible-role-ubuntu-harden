Role Name
=========

This Role should Do some basic hardening for Ubuntu Linux

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

admin_email:


Example Playbook
----------------


    - hosts: servers
      roles:
         - { role: lonix.ansible-role-ubuntu-harden, admin_email: my.little.pony@fanclub.co.uk }

License
-------

MIT

Author Information
------------------

email: lonixx@gmail.com
