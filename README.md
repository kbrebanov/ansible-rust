[![No Maintenance Intended](http://unmaintained.tech/badge.svg)](http://unmaintained.tech/)

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
| rust_version   | 1.10.0                                                           | Version of Rust to install  |
| rust_sha256sum | f189303d52b37c8bb694b9d9739ae73ffa926cbdeffde1d5d6a5c6e811940293 | SHA 256 checksum of package |

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
