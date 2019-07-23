Common_setup
=========

A role for configure default setup for new servers.

Requirements
------------

No requirements needed ;) just Python into your servers.

Role Variables
--------------

Define into vars/main.yml
packages:
  - vim
  - htop
  - build-essential
  - libssl-dev
  - libffi-dev
  - python-dev
  - python-setuptools
  - python3-pip

Dependencies
------------

No dependencies, I love freedom !

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: cloud_factory_online_common_ansible }

License
-------

BSD

Author Information
------------------

Alex FAIVRE - Author of blog cloudfactoryonline.com a blog for DevOps Lovers, IT enthusiatics and curious people :)
