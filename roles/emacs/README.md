emacs ansible role
==================

![CI](https://github.com/baztian/ansible-emacs/workflows/CI/badge.svg)

Role to install Emacs on debian, ubuntu and mint.

Example Playbook
----------------

    - hosts: servers
      become: yes
      roles:
         - role: baztian.emacs

License
-------

MIT
