Ansible Skeleton
================
Depends on ansible-development.

All playbooks should be in the playbooks/ directory.

To run a playbook:

`% ansible-playbook playbooks/foo.yml`

The command must be run in the ansible project root, so it can use the ansible.cfg
included with this project.

Refer to the ansible.cfg file for more information on the configuration used with
this project.

Add Roles
---------
To add a new role run the ansible-galaxy command in the project root and modify
the initialized files.

`% ansible-galaxy init roles/foo`

Do not forget to remove any directory and file you do not use in your new role.

Download Roles
--------------

Roles can also be downloaded an added to roles/.
