# Ansible : Roles collection

Ansible - Roles collection for common system services

## Requirements

**OS**: debian/ubuntu based distro

(RedHat & CentOS support in progress)

## Role Variables

For each role, look at `roles/role_name/defaults/main.yml`):

## Dependencies

None.

## Example Playbook

```
- hosts: server-1
  become: yes
  roles:
    - build-essential
    - apache
```

## License

GNU General Public License v3.0

## Author Information

by Niaina Lens.