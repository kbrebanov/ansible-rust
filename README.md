rust
====

[![Ansible Role](https://img.shields.io/ansible/role/3944.svg)](https://galaxy.ansible.com/list#/roles/3944)

Installs Rust

Requirements
------------

This role requires Ansible 1.4 or higher.

Role Variables
--------------

| Name           | Default                                                          | Description                 |
|----------------|------------------------------------------------------------------|-----------------------------|
| rust_version   | 1.2.0                                                            | Version of Rust to install  |
| rust_sha256sum | 2311420052e06b3e698ce892924ec40890a8ff0499902e7fc5350733187a1531 | SHA 256 checksum of package |

Dependencies
------------

None

Example Playbook
----------------

Install Rust
```
- hosts: all
  roles:
    - { role: kbrebanov.rust }
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
