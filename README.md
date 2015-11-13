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
| rust_version   | 1.4.0                                                            | Version of Rust to install  |
| rust_sha256sum | 2de2424b50ca2ab3a67c495b6af03c720801a2928ad30884438ad0f5436ac51d | SHA 256 checksum of package |

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
