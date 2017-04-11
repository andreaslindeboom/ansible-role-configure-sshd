# Configure the SSH server (Ansible role)
This role configures `sshd` to be a bit more secure than the defaults.

## Requirements
A target host that accepts incoming SSH connections from Ansible on a user with sudo rights.

## Role Variables
None.

## Dependencies
None.

## Example usage
```
- hosts: servers
  roles:
     - configure-sshd
```

## License
BSD
