# Ansible: Docker

An Ansible Role that installs [Docker](https://www.docker.com) on Linux.

## Pre-Requisites

None.

## Ansbile role structure

```
ansible-docker
├── tasks
│   ├── setup-RedHat.yml
│   ├── setup-Debian.yml
│   ├── main.yml
│   ├── docker-users.yml
│   └── docker-compose.yml
├── meta
│   └── main.yml
├── handlers
│   └── main.yml
├── defaults
│   └── main.yml
└── README.md
```
