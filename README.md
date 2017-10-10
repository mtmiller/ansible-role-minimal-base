# Ansible Minimal Base System Role

[![Build Status](https://travis-ci.org/mtmiller/ansible-role-minimal-base.svg?branch=master)](https://travis-ci.org/mtmiller/ansible-role-minimal-base)
[![Ansible Role](https://img.shields.io/ansible/role/21088.svg)](https://galaxy.ansible.com/mtmiller/minimal-base)

This is a simple Ansible role that can be used early to set up a minimal base
system to start from.

For now this role targets recent releases of Debian and Ubuntu.

## Requirements

* Debian or Ubuntu target system
* Ansible 2.1 or greater

## Installation

Install this role from Ansible Galaxy with

    ansible-galaxy install mtmiller.minimal-base

## Example Playbook

This is an example playbook showing how to use this role.

    - hosts: servers
      roles:
        - mtmiller.minimal-base

## License

This role is licensed under the [MIT](https://opensource.org/licenses/MIT)
license. See [LICENSE.md](LICENSE.md) for the full license text.
