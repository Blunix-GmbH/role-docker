# Ansible Role: Docker

This role installs and configures docker and docker-compose.

# Example play

```yaml
- hosts: all
  roles:
    blunix.role-docker
  vars:
    docker_compose_enabled: True
    docker_compose_version: 1.26.2
```

# License

Apache-2.0

# Author Information

Service and support for orchestrated hosting environments,
continuous integration/deployment/delivery and various Linux
and open-source technology stacks are available from:

```
Blunix GmbH - Consulting for Linux Hosting 24/7
Glogauer Straße 21
10999 Berlin - Germany

Web: www.blunix.org
Email: service[at]blunix.org
Phone: (+49) 30 / 12 08 39 90
