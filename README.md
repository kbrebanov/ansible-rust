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
| rust_version   | 1.6.0                                                            | Version of Rust to install  |
| rust_sha256sum | 8630cc02432b4423d64eeae4ef071ec58e5dd1f3d555a3a3cc34b759202813f6 | SHA 256 checksum of package |

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
