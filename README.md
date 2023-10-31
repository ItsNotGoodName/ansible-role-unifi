# ansible-role-unifi

UniFi Network Application for Debian 11.

MongoDB repository will be added.

This role follows Ubiquiti's [official guide](https://help.ui.com/hc/en-us/articles/220066768-UniFi-Network-How-to-Install-and-Update-via-APT-on-Debian-or-Ubuntu).

This role marks the `unifi` package on hold to prevent accidental updates.

# Requirements

N/A

# Role Variables

See [defaults/main.yml](defaults/main.yml).

# Dependencies

N/A

# Example Playbook

```yaml
- hosts: all
  roles:
    - itsnotgoodname.unifi
```
