Role Name
=========

This role installs Docker container with Bitwarden RS.

Requirements
------------

Docker container engine and Python's Docker module

Role Variables
--------------

see [./defaults/main.yml](./defaults/main.yml)

Dependencies
------------

No specific dependencies

Example Playbook
----------------

```
- hosts: servers
  become: yes
  roles:
    - role: ussrlongbow.bitwardenrs
```

License
-------

[MIT License](./LICENSE)
