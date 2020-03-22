Ansible Role: Nextcloud
=========

A performance oriented installation of [Nextcloud](https://nextcloud.com/).

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

This role depend on the roles listed below. It is not necessary to configure them since this role already does it.

- geerlingguy.repo-epel
- geerlingguy.repo-remi
- geerlingguy.apache
- geerlingguy.php
- geerlingguy.apache-php-fpm
- geerlingguy.mysql
- geerlingguy.redis

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - vnkomv.nextcloud

License
-------

MIT

Author Information
------------------

This role was created in 2020 by [Désiré-Lévi Kouablan](https://levikouablan.net).
