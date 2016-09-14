Ansible Role:  sysdig
=========
Simple role to install sysdig.

Note:  We cannot test this one in travis since it pulls kernel-devel packages based on the kernel version.
Requirements
------------

None

Role Variables
--------------
None

Dependencies
------------
None

Example Playbook
----------------

```
- hosts: servers
  roles:
    - biggsean.sysdig
```

License
-------

MIT

