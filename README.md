Role Name
=========

Ansible Role to Automate Deployment of IdM using FreeIPA.


Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

---
# Target: where our play will run and options it will run with
- name: Configure FreeIPA in RHEL8
  hosts: master

# Roles: list of roles to be imported into the play
  roles:
    - role: '/home/controller/roles/configure_FreeIPA_Server'





