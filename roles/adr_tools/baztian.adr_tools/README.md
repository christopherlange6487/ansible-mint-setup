# Ansible role to install ADR Tools

![CI](https://github.com/baztian/ansible-adr-tools/workflows/CI/badge.svg)

Role to download, install [ADR Tools](https://github.com/npryce/adr-tools) for working with [Architecture Decision Records](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions) (ADRs).

## Example Playbook

    - hosts: servers
      become: yes
      roles:
         - role: baztian.adr_tools

# License

MIT
