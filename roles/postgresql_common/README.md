# Ansible Role: PostgreSQL Common

Performs operations common to all PostgreSQL roles, such as configuring the apt
repo.

## Usage

Install the collection locally, either via `requirements.yml`, or manually:
```bash
ansible-galaxy collection install dubzland.postgresql
```

Then apply the server role using the following playbook:
```yaml
---
- hosts: db-servers

  collections:
    - dubzland.postgresql

  roles:
    - postgresql_common
```
## License

MIT

## Author

* [Josh Williams](https://codingprime.com)
