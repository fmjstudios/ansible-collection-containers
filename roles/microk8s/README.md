# Ansible Role: MicroK8S

This role installs the Snap package _MicroK8S_ on the system in question.

## Requirements

N/A

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

```yaml
docker_path: /usr/bin/docker
microk8s_privileged_users:
  - ar
  - br
```

## Dependencies

None.

## Example Playbook

```yaml
    - hosts: all
      roles:
        - role: microk8s
```

## License

Proprietary

## Author Information

This role was created in 2023 by [Maximilian Gindorfer](https://fmj.dev).
