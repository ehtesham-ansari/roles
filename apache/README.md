Role Name
=========

Automate the deployment of an Apache web server.
created by Md.Ehtesham

Requirements
------------
the collection ansible.posix should be pre installed for firewalld module
command: ansible-galaxy collection install ansible.posix

Role Variables
--------------
#start_reload:
  - httpd
  - firewalld
#firewall_rule:
  - http
  - https


Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

---
- hosts: servers,hostgroup
  roles:
    - apache

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
