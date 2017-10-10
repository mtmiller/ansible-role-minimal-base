# Ansible Minimal Base System Role

This is a simple Ansible role that can be used early to set up a minimal base
system to start from.

For now this role targets recent releases of Debian and Ubuntu.

## Requirements

* Debian or Ubuntu target system
* Ansible 2.1 or greater

## Example Playbook

This is an example playbook showing how to use this role.

    - hosts: servers
      roles:
        - mtmiller.minimal-base

## License

This role is licensed under the [MIT](https://opensource.org/licenses/MIT)
license. See [LICENSE.md](LICENSE.md) for the full license text.
