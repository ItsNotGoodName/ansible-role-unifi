# ansible-role-unifi

Ansible role that installs UniFi Network Application (UniFi Controller) on Debian 9, 10, or 11.
On Debian 9, no third party repositories except UniFi's are installed.

This role follows Ubiquiti's [official guide](https://help.ui.com/hc/en-us/articles/220066768-UniFi-Network-How-to-Install-and-Update-via-APT-on-Debian-or-Ubuntu).

This role marks the `unifi` package on hold to prevent accidental updates.

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
