rust
====

[![Build Status](https://travis-ci.org/kbrebanov/ansible-rust.svg?branch=master)](https://travis-ci.org/kbrebanov/ansible-rust)

Installs Rust

Requirements
------------

This role requires Ansible 1.4 or higher.

Role Variables
--------------

| Name           | Default                                                          | Description                 |
|:---------------|:-----------------------------------------------------------------|:----------------------------|
| rust_version   | 1.8.0                                                            | Version of Rust to install  |
| rust_sha256sum | d5a7c10070f8053defe07d1704762c91e94fc30a1020d16b111d63e9af365d48 | SHA 256 checksum of package |

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
