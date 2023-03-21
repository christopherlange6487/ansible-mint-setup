# buildnotify ansible role

![CI](https://github.com/baztian/ansible-buildnotify/workflows/CI/badge.svg)

Ansible role to install [buildnotify](https://github.com/anaynayak/buildnotify) which
is a "system tray based build status notification app for `cctray.xml` feeds".

## Example Playbook

    - hosts: servers
      become: yes
      roles:
         - role: baztian.buildnotify

## License

MIT
