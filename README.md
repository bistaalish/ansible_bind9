# Install bind9 on Linux
bind9 is a DNS server.

## Currently Supported.

- Debian 12.2

## Prepare
1. Edit the forwarders file.
2. Edit the reverse file.
3. Edit the named.conf.local.
4. Edit the named.conf.options
5. Edit the host in each .yml files.
6. change the host file
7. Change the remote_user
## Installtion

```bash
ansible-playbook -i hosts install.yaml
```
