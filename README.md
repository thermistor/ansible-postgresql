# Ansible role for postgresql

Configures postgresql, and creates backups.

Backup keeps 14 daily backups and 10 weekly backups by default. It creates a
a custom format backup by default.

## Example playbook

Only specify the major and minor version, don't specify the patch version.

    - role: postgresql
      postgresql_version: 9.6
      tags:
        - postgresql

## License

MIT

