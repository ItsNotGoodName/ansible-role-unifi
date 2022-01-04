# ansible-role-unifi

Ansible role for installing UniFi Network Application on Debian 9, 10, and 11.
Debian 10 and 11 will install third party MongoDB and Java repositories.

This role follows Ubiquiti's [official guide](https://help.ui.com/hc/en-us/articles/220066768-UniFi-Network-How-to-Install-and-Update-via-APT-on-Debian-or-Ubuntu).

This role marks the `unifi` package on hold to prevent accidental updates. 

To update, run role with `unifi_update` tag.

## Requirements

N/A

## Role Variables

N/A

## Dependencies

N/A

## Example Playbook

```yaml
- hosts: all
  roles:
    - itsnotgoodname.unifi
```

## License

MIT

## Author Information

ItsNotGoodName
