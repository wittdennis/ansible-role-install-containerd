# install_containerd

Role to install containerd.

## Role Variables

```yaml
install_containerd_write_default_config: true # Flag if `containerd config default` command should be executed and save the output. Default: true
```

## Example Playbook

    - hosts: servers
      roles:
         - { role: wittdennis.install_containerd }

## License

MIT
