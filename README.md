ansible-role-zram
=========

Ansible role to configure zram.

Molecule is WIP.

Role Variables
--------------

See `defaults/main.yml`

Dependencies
------------

- `community.general`

Example Playbook
----------------

```
    - hosts: servers
      become: true
      gather_facts: true
      roles:
         - { role: zram, tags: zram }
```

Author Information
------------------

@rcrawf

