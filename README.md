# ansible-role-unifi

UniFi Network Application for Debian 11 and 12.

This role follows Ubiquiti's [official guide](https://help.ui.com/hc/en-us/articles/220066768-UniFi-Network-How-to-Install-and-Update-via-APT-on-Debian-or-Ubuntu).

Following steps will be taken:

- Official MongoDB apt repository will be added.
- `libssl1.1` package will be added for Debian 12.
- `unifi` package put on hold to prevent accidental updates.

## Requirements

N/A

## Role Variables

See [defaults/main.yml](defaults/main.yml).

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
