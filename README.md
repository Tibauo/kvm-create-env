Role Name
=========

Create Pool, Volume, Network and VM for KVm

Requirements
------------

Role Variables
--------------

```
all:
  hosts:
    kvm:
      ansible_host: 127.0.0.1
      ansible_user: root
```

Dependencies
------------


Example Playbook
----------------

```
- name: kvm
  hosts: kvm
  roles:
    - kvm
```

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
