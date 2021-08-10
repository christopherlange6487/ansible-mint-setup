# Ansible role to install squeezeplay

![CI](https://github.com/baztian/ansible-squeezeplay/workflows/CI/badge.svg)

Role to install [squeezeplay](https://sourceforge.net/projects/lmsclients/files/squeezeplay/linux/). See [Logitech Squeezebox Wiki entry](https://wiki.slimdevices.com/index.php/SqueezePlay.html) for additional information.

## Example Playbook

    - hosts: servers
      become: yes
      roles:
         - role: squeezeplay

## License

MIT
