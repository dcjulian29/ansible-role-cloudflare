# Ansible Role: cloudflare

[![Lint](https://github.com/dcjulian29/ansible-role-cloudflare/actions/workflows/lint.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-cloudflare/actions/workflows/lint.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-cloudflare.svg)](https://github.com/dcjulian29/ansible-role-cloudflare/issues)

This an Ansible role to install and run cloudflare argo tunnels

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.cloudflare
  src: https://github.com/dcjulian29/ansible-role-cloudflare.git
  version: main
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

- None
