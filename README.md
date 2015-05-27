rust
====

Installs Rust

Requirements
------------

This role requires Ansible 1.4 or higher.

Role Variables
--------------

| Name           | Default                                                          | Description                 |
|----------------|------------------------------------------------------------------|-----------------------------|
| rust_version   | 1.0.0                                                            | Version of Rust to install  |
| rust_sha256sum | aab0d853314675d5e80e427c613a0e646ae75fbbc856b886dab682280f825d53 | SHA 256 checksum of package |

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
