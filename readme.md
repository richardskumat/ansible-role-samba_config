
ansible role samba config
=========

Configures samba for my home network.

Requirements
------------

None

Role Variables
--------------

```
samba_config_file_path
```

defaults to sample-smb.conf in files directory.

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
    - { role: richardskumat.ansible_role_samba_config, samba_config_file_path: "/path/to/your/smb.conf" }

```

License
-------

GPLv3

Author Information
------------------

Richard Skumat

https://github.com/richardskumat/
