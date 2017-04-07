PXE - Preboot Execution Environment Server
==========================================

Role to Setup a PXE Environment on Debian, Ubuntu, CentOS, RedHat

Requirements
------------

None.

Role Variables
--------------



Dependencies
------------

- { role: rvalente.tftpd }

Example Playbook
----------------

```
- hosts: servers
  roles:
    - { role: rvalente.pxe }
```

License
-------

See `LICENSE`

Author Information
------------------

Ronald Valente
