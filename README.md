# Blinkt

Ansible Role to install packages and example code for the Pimoroni Blinkt! LED array on Raspbian/Debian OS on a Raspberry Pi.

## Requirements

This role does not depend on anything.

## Role Variables

This role has no configuration variables.

## Dependencies

This role has no dependencies.

## Example Playbook

First install this Role from Ansible Galaxy.

```bash
ansible-galaxy install agarthetiger.blinkt
```

Then add this role to your playbook.

```yaml
- hosts: all
  roles:
      - blinkt
```

## License

MIT

## Author Information

Andrew Garner (@agarthetiger)
