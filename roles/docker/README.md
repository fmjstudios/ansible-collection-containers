# Ansible Role: Docker

This role installs the Docker Engine package on the system in question.

## Requirements

N/A

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

```yaml
docker_ce_users: []
```

## Dependencies

None.

## Example Playbook

```yaml
    - hosts: all
      roles:
        - role: helm
```

## License

Proprietary

## Author Information

This role was created in 2023 by [Maximilian Gindorfer](https://fmj.dev).
