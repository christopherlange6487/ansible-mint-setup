Ansible role to install several additional software pieces
==========================================================

![CI](https://github.com/baztian/ansible-other-installs/workflows/CI/badge.svg)

Role to install various useful packages that don't require
fancy setup.

Example Playbook
----------------

    - hosts: servers
      become: yes
      roles:
         - role: baztian.other_installs

License
-------

MIT
