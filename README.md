# Ansible Runner Container

Ansible Runner is a tool and Python library that helps when interfacing with Ansible directly or as part of another system. Ansible Runner works as a standalone tool, a container image interface, or a Python module that can be imported. The goal is to provide a stable and consistent interface abstraction to Ansible.

## Include packages

This container images container based on Rocky Linux 9 with the following packages:

- Anabile
  - ansible-runner
  - ansible-core

## Version Info

| tags   | ansible-runner | ansible-core |
| ----   | -------------- | ------------ |
| v1.0.0 | 2.3.3          | 2.15.1       |

## Getting Started

### Pre-requisites

- [ansible-builder](https://github.com/ansible/ansible-builder)

### Building

Run the following command:

```console
ansible-builder build -t kheeklab/ee-base:dev

```

This will build the container image with the name kheeklab/ee-base:dev.
