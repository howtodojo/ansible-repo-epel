# ansible-repo-epel

![](https://github.com/howtodojo/ansible-repo-epel/actions/workflows/ci.yml/badge.svg)

This role enables the EPEL (Extra Packages for Enterprise Linux) repository on RHEL-based systems.

## Requirements

- RHEL/CentOS/AlmaLinux/Rocky Linux 9 or 10

## Role Variables

- `epel_enabled`: Enable EPEL repository (default: true)

## Dependencies

None.

## Example Playbook

```yaml
- hosts: servers
  roles:
    - muhammadpanji.repo_epel
```

## License

BSD

## Author Information

This role was created by Muhammad Panji.