
ansible role samba config
=========

Configures samba for my home network.

Requirements
------------

None

Role Variables
--------------

The role only copies a simple smb.conf over to the remote host, so
there's none.

Dependencies
------------

richardskumat.ansible_role_samba

Example Playbook
----------------



```
---
- name: Converge
  hosts: all
  roles:
    - richardskumat.ansible_role_samba
    - richardskumat.ansible_role_samba_config

```

License
-------

GPLv3

Author Information
------------------

Richard Skumat

https://github.com/richardskumat/
