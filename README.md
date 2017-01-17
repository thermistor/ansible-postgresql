# Ansible role for postgresql

Configures postgresql.

## Example playbook

Only specify the major and minor version, don't specify the patch version.

    - role: postgresql
      postgresql_version: 9.6
      tags:
        - postgresql

## License

MIT

