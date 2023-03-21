# docker ansible role

![CI](https://github.com/baztian/ansible-docker/workflows/CI/badge.svg)

Ansible role to install docker and docker-compose.

## Example Playbook

    - hosts: servers
      become: yes
      roles:
         - role: baztian.docker

## License

MIT
