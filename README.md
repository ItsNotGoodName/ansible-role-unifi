# ansible-role-unifi

UniFi Network Application for Debian 11 and 12.

This role follows Ubiquiti's [official guide](https://help.ui.com/hc/en-us/articles/220066768-UniFi-Network-How-to-Install-and-Update-via-APT-on-Debian-or-Ubuntu).

Following steps will be taken:

- MongoDB 7.0 Community Edition will be installed.
- `unifi` package put on hold to prevent accidental updates.

## Requirements

N/A

## Role Variables

| Variable               | Default | `Description                                     |
| ---------------------- | ------- | ------------------------------------------------ |
| `unifi_hold`           | false   | Prevent UniFi from updating during `apt upgrade` |
| `unifi_mongodb_legacy` | false   | Set MongoDB version to 4.4                       |

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
