# check-security-updates

This role enables to verify if security updates needs to be installed on a system.

## Requirements

No requirements.

## Role Variables

| Name                                     | Type | Location            | Description                                                                                                         |
| ---------------------------------------- | ---- | ------------------- | ------------------------------------------------------------------------------------------------------------------- |
| check_security_updates_fail_if_unpatched | bool | `defaults/main.yml` | Flag indicating if the playbook should fail if security updates are needed on the remote host. Defaults to `false`. |
| check_security_updates_needed            | bool | `output fact`       | Flag indicating if security updates are needed on the remote host.                                                  |

## Dependencies

No dependencies.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: servers
  roles:
    - { role: julb.check_security_updates }
```

## License

MIT

## Author Information

More to find on my [Github](https://github.com/julb).

## Contributing

This project is totally open source and contributors are welcome.

When you submit a PR, please ensure that the syntax has been checked.
