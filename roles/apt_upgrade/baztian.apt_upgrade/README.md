Apt upgrade ansible role
========================

![CI](https://github.com/baztian/ansible-apt-upgrade/workflows/CI/badge.svg)

Role to configure and upgrade base/official apt sources for ubuntu and mint.

Example Playbook
----------------

    - hosts: servers
      become: yes
    - vars:
        official_apt_sources_replacements:
        - regexp: http://packages.linuxmint.com
          replace: http://ftp.fau.de/mint/packages
        - regexp: http://archive.ubuntu.com/ubuntu
          replace: http://ftp.fau.de/ubuntu
      roles:
         - role: baztian.apt_upgrade

License
-------

MIT
