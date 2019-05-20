Role Name
=========

A brief description of the role goes here.

Requirements
------------

This role doesn't have requirement

Role Variables
--------------
Vars:

base_repository_dir

Host vars:

base_use_local_repositories: (default - False) 
base_use_only_local_repositories: (default - False)
base_yum_local_repositories: []
base_firewall_zones: []
base_packages: [] (default - [vim])

base_yum_local_repositories:
  - id: 
    name: 
    baseurl: 

base_firewall_zones:
  - name: 
    interfaces: []
    services: []

Dependencies
------------

This role doesn't have dependecies

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

