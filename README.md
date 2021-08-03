# Ansible Role etcd

Ansible Deploy etcd cluster

## Requirements

- Centos 7
- Ansible 2.10

## Role Variables

See [defaults/main.yml](defaults/main.yml)

## Dependencies

None

## Example Playbook

```yaml
- hosts: servers
  roles:
    - { role: daixijun.etcd, etcd_version: 3.5.0 }
```

## License

MIT

## Author Information

- Xijun Dai <daixijun1990@gmail.com>
