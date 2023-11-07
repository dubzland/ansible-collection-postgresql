# Ansible Role: PostgreSQL Server

Installs and configures the PostgreSQL database server.

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
    - postgresql_server
```
## License

MIT

## Author

* [Josh Williams](https://codingprime.com)
