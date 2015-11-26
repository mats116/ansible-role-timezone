# README.md
# Ansible Role: mats116.timezone

An Ansible role that configure timezone on **Ubuntu 14.04 LTS**

## Requirements

none

## Role Variables

Available variables are listed below, along with default values:

```yaml
timezone: Asia/Tokyo
```

## Dependencies

none

## Example Playbook

```yaml
- hosts: web-server
  roles:
    - role: mats116.timezone
```

## License

MIT
