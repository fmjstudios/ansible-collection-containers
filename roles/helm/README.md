# Ansible Role: Helm

This role installs the Helm CLI binary on the system in question.

## Requirements

N/A

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

```yaml
helm_version: "v3.11.3"
helm_platform: linux
helm_arch: amd64
helm_bin_path: /usr/local/bin/helm
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
