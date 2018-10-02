# Ansible Role: apt

Commandline package manager for debian-base system.

[https://packages.debian.org/stretch/apt](https://packages.debian.org/stretch/apt)

# Role Variables

```
apt_packages: []
```

apt packages to install.

# Example Playbook

```
- hosts: server
  vars:
    apt_packages:
      - zip
      - unzip
  roles:
    - { role: honomoa.apt }
```

# License
CC BY-SA 3.0
