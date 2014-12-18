# ansible-sauce-connect

An Ansible role for installing Sauce Connect.

## Role Variables

- `sc_version` - Sauce Connect version
- `sc_os` - Sauce Connect operating system (default: `linux`)
- `sc_username` - Sauce Connect username (default: `YOUR_USERNAME`)
- `sc_access_key` - Sauce Connect access key (default: `YOUR_ACCESS_KEY`)
- `sc_log` - Statsite log path (default: `/var/log/sc.log`)
- `sc_log_rotate_count` - Sauce Connect log rotation count (default: `5`)
- `sc_log_rotate_interval` - Sauce Connect log rotation interval (default: `daily`)

## Example Playbook

See the [examples](./examples/) directory.
